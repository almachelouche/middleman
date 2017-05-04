+++
markets = ["ph"]
title = '''PH Regular Service Reminder_Mail Merge_V2'''

[[module]]
path='email_modules/preheaderbefore'
color='''nothing'''
segmentif = ["(user.CustomAttribute['Esplit'] == 'Due')"]

	 preheader = '''Keep your vehicle in top shape with us. Book your maintenance today.'''

[[module]]
path='email_modules/preheaderbefore'
color='''nothing'''
segmentelse = ["(user.CustomAttribute['Esplit'] == 'PastDue')"]

	 preheader = '''Did you forget to visit for maintenance? Book an appointment now.  '''

[[module]]
path='email_modules/body'
color='''nothing'''

[[module]]
path='email_modules/preheaderafter'
color='''nothing'''
segmentif = ["(user.CustomAttribute['Esplit'] == 'Due')"]

	 preheader = '''Keep your vehicle in top shape with us. Book your maintenance today.'''

[[module]]
path='email_modules/preheaderafter'
color='''nothing'''
segmentelse = ["(user.CustomAttribute['Esplit'] == 'PastDue')"]

	 preheader = '''Did you forget to visit for maintenance? Book an appointment now.  '''

[[module]] #Header Logo
path='email_modules/header/logo'
color='white'

  image = '''white'''
  url_link = '''https://www.ford.com.ph/'''

[[module]]
path='email_modules/cover/02'
segmentif = ["(user.CustomAttribute['Esplit'] == 'Due')"]

color='''white'''
icon='''th_edm2_svc_wrench_20160801'''
title='''It’s time for a visit'''
copy='''Hello <%${user['FirstName']}%><br /><br />Your <%${user.CustomAttribute['Model']}%> is due for service, and our experts can’t wait to make sure it’s running at its absolute best.<br /><br />Your next service is: <strong><% ${user.CustomAttribute['NextServiceDate']} %></strong>.<br /><br />It's important to book your service today. Just click below to contact <%${user.CustomAttribute['Dealer_Name']}%> (during business hours) or to find your nearest dealer.<br /><br />If you have already booked your appointment, please kindly disregard this email.'''

cta1_text='''FIND A DEALER'''
cta1_url='''https://www.ford.com.ph/locate-a-dealer/'''
cta1_url_link_name='''find_dealer'''
cta2_text='''CALL <%${user.CustomAttribute['Dealer_Phone']}%>'''
cta2_url='''tel:<%${user.CustomAttribute['Dealer_Phone']}%>'''

[[module]]
path='email_modules/cover/02'
segmentelse = ["(user.CustomAttribute['Esplit'] == 'Past Due')"]

color='''white'''
icon='''th_edm2_svc_wrench_urgent_20160801'''
title='''<span style="color:#ff6600">You missed important service</span>'''
copy='''Hello <%${user['FirstName']}%><br /><br />Is your <%${user.CustomAttribute['Model']}%> still in tip-top shape? Come in for service and let our experts inspect your Ford to ensure it’s still running at its absolute best.<br /><br />Book your service today. Just click below to contact <%${user.CustomAttribute['Dealer_Name']}%> (during business hours) or to find your nearest dealer.<br /><br />If you have already booked your appointment, please kindly disregard this email.'''

cta1_text='''FIND A DEALER'''
cta1_url='''https://www.ford.com.ph/locate-a-dealer/'''
cta1_url_link_name='''find_dealer'''
cta2_text='''CALL <%${user.CustomAttribute['Dealer_Phone']}%>'''
cta2_url='''tel:<%${user.CustomAttribute['Dealer_Phone']}%>'''

[[module]]
path='email_modules/cover/03'

color='''white'''
copy='''<span style="color:#b3b3b3;">VIN No: <% ${user.CustomAttribute['VIN']} %><br />Last reported service date: <% ${user.CustomAttribute['Last_Reported_Service_Date']} %><br />Last reported mileage: <% ${user.CustomAttribute['Mileage']} %></span>'''

[[module]] #Custom 01
path='email_modules/custom/3columntitle3icons'
color='white'
segmentif = ["(user.CustomAttribute['Esplit'] == 'Due')"]

  title = '''Why Ford servicing?'''
  icon1 = '''ph_edm2_fordsvc_a'''
  text1 = '''Your custom-designed service plan keeps your vehicle performing at its best.'''
  icon2 = '''ph_edm2_fordsvc_b'''
  text2 = '''Ford service center equipment is built and calibrated specifically for your vehicle. '''
  icon3 = '''ph_edm2_fordsvc_c'''
  text3 = '''A record of regular servicing improves your vehicle’s re-sale value.'''

[[module]] #Banner Image No Link
path = '''email_modules/image/banner_nolink'''
color = '''white'''
segmentif = ["(user.CustomAttribute['Esplit'] == 'Due')"]

  image = '''ph_edm2b_tirepromotion_20161221'''

[[module]] #Cover 05
path='email_modules/cover/02'
color='''slatescreen'''

  title = '''Extended Peace of Mind'''
  copy = '''A Premium Extended Warranty<sup>1</sup> gives you worry-free driving for up to 5 years. It covers most mechanical and electrical parts, and labor charges too.'''
  cta1_text = '''GET PEACE OF MIND'''
  cta1_url = '''https://www.ford.com.ph/owner/warranties/'''
  cta1_link_name = '''extended_warranty'''
  icon = '''ph_edm_extendedwarranty_20160801'''

[[module]] #Cover 05
path='email_modules/cover/02'
color='''white'''

  title = '''Need any help?'''
  copy = '''Call our Customer Assistance Centre with any questions at<br /><a style="color:#2D96CD" href="tel:(+632) 866 9408">(+632) 866 9408</a><br />or<br /> <a style="color:#2D96CD" href="tel:1-800-10-736-3673">toll-free 1-800-10-736-3673</a>'''
  cta_text = '''+63-2-866-9408'''
  cta_url = '''tel:6328669408'''
  cta_link_name = '''any_questions_call'''
  icon = '''ph_edm2_call_20160801'''

  [[module]] #PH Social
path = 'email_modules/footer/ph/social'
color = 'white'

[[module]] #Footer Disclaimer
path='email_modules/footer/disclaimer'
color='white'

  text='''Disclaimer: <br /><br />[1] Extended Warranty covers vehicles for the first 36 months or up to 100,000 km, whichever comes first.'''

[[module]] #PH Online
path = 'email_modules/footer/ph/online'
color = 'white'
+++