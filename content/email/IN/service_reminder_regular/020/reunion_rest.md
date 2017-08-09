+++
markets = ["in"]
title = '''IN Service Reminder Regular Due/Pdue 020 Reunion Rest'''

[[module]]
path='email_modules/preheaderbefore'

segmentif = ["(user.CustomAttribute['Esplit'] == 'Due')"]

	 preheader = '''Your Ford <%${user.CustomAttribute['Model']}%> is due for service, and our experts can't wait to make sure it's running at its absolute best. Hello <%${user.CustomAttribute['FullName']}%>, long time, no see! Your Ford <%${user.CustomAttribute['Model']}%> is due for service, and our experts can't wait to make sure it's running at its absolute best.'''

[[module]]
path='email_modules/preheaderbefore'

segmentelseif = ["(user.CustomAttribute['Esplit'] == 'PastDue')"]

	 preheader = '''Your Ford <%${user.CustomAttribute['Model']}%>'s service is overdue. For the wellbeing of you and your Ford, it's important that you visit a Ford service centre soon. Hello <%${user.CustomAttribute['FullName']}%>Your Ford <%${user.CustomAttribute['Model']}%>'s service is overdue. For the wellbeing of you and your Ford, it's important that you visit a Ford service centre soon.'''

[[module]]
path='email_modules/body'


[[module]]
path='email_modules/preheaderafter'

segmentif = ["(user.CustomAttribute['Esplit'] == 'Due')"]

	 preheader = '''Your Ford <%${user.CustomAttribute['Model']}%> is due for service, and our experts can't wait to make sure it's running at its absolute best. Hello <%${user.CustomAttribute['FullName']}%>, long time, no see! Your Ford <%${user.CustomAttribute['Model']}%> is due for service, and our experts can't wait to make sure it's running at its absolute best.'''

[[module]]
path='email_modules/preheaderafter'

segmentelseif = ["(user.CustomAttribute['Esplit'] == 'PastDue')"]

    preheader = '''Your Ford <%${user.CustomAttribute['Model']}%>'s service is overdue. For the wellbeing of you and your Ford, it's important that you visit a Ford service centre soon. Hello <%${user.CustomAttribute['FullName']}%>Your Ford <%${user.CustomAttribute['Model']}%>'s service is overdue. For the wellbeing of you and your Ford, it's important that you visit a Ford service centre soon.'''
 
[[module]] #Header Logo
path='email_modules/header/logodesktop'
color='white_pb'

    image = '''white_pb'''
    url_link = '''https://www.india.ford.com/'''
  
[[module]]
path='email_modules/spacer/default'
color='white'

	height="30"

[[module]]
path='email_modules/singles/icon'
color='''white'''
segmentif = ["(user.CustomAttribute['Esplit'] == 'Due')"]

	icon = '''in_edm2_svc_wrench_20160801'''

[[module]]
path='email_modules/singles/icon'
color='''white'''
segmentif = ["(user.CustomAttribute['Esplit'] == 'PastDue')"]

	icon = '''in_edm2_svc_wrench_urgent_20160801'''
    
[[module]]
path='email_modules/spacer/default'
color='white'

	height="30"

[[module]]
path='email_modules/singles/title'
color='''white'''
segmentif = ["(user.CustomAttribute['Esplit'] == 'Due')"]

	title = '''It's time for a visit'''
    
[[module]]
path='email_modules/singles/title'
color='''white'''
segmentif = ["(user.CustomAttribute['Esplit'] == 'PastDue')"]

	title = '''<span style="color:#FF6600;">Your service is now past due</span>'''    

[[module]]
path='email_modules/spacer/default'
color='white'

	height="30"

[[module]]
path='email_modules/singles/copy'
color='''white'''
segmentif = ["(user.CustomAttribute['Esplit'] == 'Due')"]

	copy = '''Hello <%${user.CustomAttribute['FullName']}%><br /><br />Long time, no see! Your Ford <%${user.CustomAttribute['Model']}%> is due for service, and our experts can't wait to make sure it's running at its absolute best.<br /><br />Your next service is due on: <% ${user.CustomAttribute['NextServiceDate']} %> '''
    
[[module]]
path='email_modules/singles/copy'
color='''white'''
segmentif = ["(user.CustomAttribute['Esplit'] == 'PastDue')"]

	copy = '''Hello <%${user.CustomAttribute['FullName']}%><br /><br />Your Ford <%${user.CustomAttribute['Model']}%>'s service is overdue. For the wellbeing of you and your Ford, it's important that you visit a Ford service centre soon.<br /><br />We've got your back. Contact us today and continue to enjoy carefree driving.'''    

[[module]]
path='email_modules/spacer/default'
color='white'

	height="30"
    
[[module]]
path='email_modules/singles/2ctablocksideoutline'
color='''white'''
	cta1_text = '''BOOK A SERVICE'''
	cta1_url = '''https://www.india.ford.com/#overlay/content/ford/in/en_in/site-wide-content/overlays/forms/service-booking.html/'''
	cta1_link_name = '''callback'''
	cta2_text = '''&nbsp;&nbsp;FIND A DEALER&nbsp;&nbsp;'''
	cta2_url = '''https://www.india.ford.com/locate-dealer/'''
	cta2_link_name = '''locate_dealer'''    

[[module]]
path='email_modules/spacer/default'
color='white'

	height="30"

[[module]] #Cover 11
path='email_modules/cover/03'
color='white'

  copy = '''VIN No: <% ${user.CustomAttribute['VIN']}%><br />Last reported service date: <%${user.CustomAttribute['Last_Reported_Service_Date']}%><br />Last reported mileage (Kms): <% ${user.CustomAttribute['Mileage']}%>'''

[[module]] #Banner Image No Link
path = '''email_modules/image/banner_nolink'''
color = '''white'''

  image = '''in_edm2_reunion_20170809'''
    
[[module]]
path='email_modules/spacer/default'
color='white'

	height="20"

[[module]]
path='email_modules/singles/title'
color='''white'''

	title = '''Get ready for a reunion for Ford!'''

[[module]]
path='email_modules/spacer/default'
color='white'

	height="30"

[[module]]
path='email_modules/singles/copy'
color='''white'''

	copy = '''Reunions are a great opportunity to reconnect with friends and family. This Reunion season, reunite with Ford and enjoy some great service offers, exclusively for you.<br/><br/>If you purchased a Ford between 2007 and 2012, go to your nearest Ford Service Centre and enjoy a 25% discount on brakes, suspension and clutch parts, labour and VAS, and get a free oil filter replacement, too! Hurry, you don't want to miss this opportunity.*'''

  
[[module]]
path='email_modules/spacer/default'
color='white'

	height="30"

[[module]]
path='email_modules/singles/ctablock'
color='''white'''

	cta1_text = '''BOOK A SERVICE'''
	cta1_url = '''https://www.india.ford.com/#overlay/content/ford/in/en_in/site-wide-content/overlays/forms/service-booking.html/'''
	cta1_link_name = '''book_service'''
    
[[module]] #Banner Image No Link
path = '''email_modules/image/banner_nolink'''
color = '''white'''

  image = '''in_edm2_reunion_offer_20170809_desktop'''   

[[module]] #Banner Image No Link
path = '''email_modules/image/banner_nolink'''
color = '''white'''

  image = '''in_edm2_fordsvc_20170321'''

[[module]] #Custom 02
path='email_modules/custom/3columncolortexttitle'
color='white'

  title1 = '''Service Price Promise'''
  text1 = '''Calculate your service cost online and pay just that.'''
  textlink1_text = '''<br />Check service price'''
  textlink1_url = '''https://www.fordservicepricepromise.com/'''
  textlink1_link_name = '''price_calculator'''
  title2 = '''Pick Up & Drop'''
  text2 = '''When it's time to service your Ford, get it done from home.'''
  title3 = '''Ford Genuine Parts'''
  text3 = '''Buy Ford genuine parts and drive your car without any worries.'''
  textlink2_text = '''Check how affordable'''
  textlink2_url = '''https://www.india.ford.com/surprisingly-affordable/'''
  textlink2_link_name = '''surprisingly_affordable'''
  cta1_text = '''FIND A DEALER'''
  cta1_url = '''https://www.india.ford.com/locate-dealer/'''
  cta1_link_name = '''locate_dealer_2'''

[[module]] #Footer 4 Icons
path='email_modules/footer/4icons'
color='white'

  icon1_url='''https://www.india.ford.com/locate-dealer/'''
  icon1_link_name = '''locate_dealer_footer'''
  icon1_image='''in_dealers_20160414'''
  icon2_url='''https://fordassured.in/'''
  icon2_link_name = '''ford_assured'''
  icon2_image='''in_ford_assured_20160401'''
  icon3_url='''tel:18004252500'''
  icon3_link_name = '''tel_Customer_Care'''
  icon3_image='''in_customer_care_number_20160401'''
  icon4_url='''tel:18002097400'''
  icon4_link_name = '''tel_RSA'''
  icon4_image='''in_rsa_no_20160615'''
    
[[module]] #Footer IN Social
path='email_modules/footer/in/social'
color='white'

[[module]] #Footer Disclaimer
path='email_modules/footer/disclaimer'
color='white'

  text='''*Tearms and conditions apply. Offers only valid in North region.'''

[[module]] #Footer IN Online
path='email_modules/footer/in/online'
color='white'
+++