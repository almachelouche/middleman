+++
markets = ["ph"]
title = '''PH Regular Service Reminder_Mail Merge'''

[[module]]
path='email_modules/preheader'


	preheader = '''Learn about our Oil Save Packs that keep your engine running smoothly.'''

[[module]] #Header Logo
path='email_modules/header/logo'
color='white'

	image = '''white'''
	url_link = '''https://www.ford.com.ph/'''

[[module]]
path='email_modules/cover/02'

color='''white'''
icon='''th_edm2_svc_wrench_20160801'''
title='''It’s time for a visit'''
copy='''Hello <%${user['FirstName']}%><br /><br />Your <%${user.CustomAttribute['Model']}%> is due for service, and our experts can’t wait to make sure it’s running at its absolute best.<br /><br />Your next service is: <NextServiceDate>.<br /><br />We are introducing “60 Minutes Express Service Guaranteed”, a new scheduled maintenance service, with an online booking system that guarantees a 60minute service!'''
cta1_text='''BOOK NOW'''
cta1_url='''https://onlinebooking.ford.co.th/'''

[[module]]
path='email_modules/cover/02'

color='''white'''
icon='''th_edm2_svc_wrench_20160801'''
title='''It’s time for a visit'''
copy='''Hello <%${user['FirstName']}%><br /><br />Your <%${user.CustomAttribute['Model']}%> is due for service, and our experts can’t wait to make sure it’s running at its absolute best.<br /><br />Your next service is: <NextServiceDate>.<br /><br />It's important to book your service today. Just click below to contact <%${user.CustomAttribute['Dealer_Name']}%> (during business hours) or to find your nearest dealer.'''

cta1_text='''CALL <%${user.CustomAttribute['Dealer_Phone']}%>'''
cta1_url='''tel:<%${user.CustomAttribute['Dealer_Phone']}%>'''
cta2_text='''FIND A DEALER'''
cta2_url='''https://www.ford.co.th/locate-a-dealer/'''
cta2_url_link_name='''find_dealer'''

[[module]]
path='email_modules/cover/02'

color='''white'''
icon='''th_edm2_svc_wrench_urgent_20160801'''
title='''You missed important service'''
copy='''Hello <%${user['FirstName']}%><br /><br />Is your <%${user.CustomAttribute['Model']}%> still safe to drive? Come in for service and let our experts inspect your Ford to ensure it’s still in top condition.<br /><br />It’s important to book your service today.<br /><br />We are introducing “60 Minutes Express Service Guaranteed”, a new scheduled maintenance service, with an online booking system that guarantees a 60minute service!'''
cta1_text='''BOOK NOW'''
cta1_url='''https://onlinebooking.ford.co.th/'''

[[module]]
path='email_modules/cover/02'

color='''white'''
icon='''th_edm2_svc_wrench_urgent_20160801'''
title='''You missed important service'''
copy='''Hello <%${user['FirstName']}%><br /><br />Is your <%${user.CustomAttribute['Model']}%> still safe to drive? Come in for service and let our experts inspect your Ford to ensure it’s still in top condition.<br /><br />Book your service today. Just click below to contact <%${user.CustomAttribute['Dealer_Name']}%> (during business hours) or to find your nearest dealer.'''

cta1_text='''CALL <%${user.CustomAttribute['Dealer_Phone']}%>'''
cta1_url='''tel:<%${user.CustomAttribute['Dealer_Phone']}%>'''
cta2_text='''FIND A DEALER'''
cta2_url='''https://www.ford.co.th/locate-a-dealer/'''
cta2_url_link_name='''find_dealer'''

[[module]]
path='email_modules/cover/03'

color='''white'''
copy='''VIN No: <% ${user.CustomAttribute['VIN']} %><br />Last reported service date: <% ${user.CustomAttribute['Last_Reported_Service_Date']} %><br />Last reported mileage: <% ${user.CustomAttribute['Mileage']} %>'''

[[module]] #Custom 01
path='email_modules/custom/3columntitle3icons'
color='white'

	title = '''Why Ford servicing?'''
	icon1 = '''ico_2e_fordsvc_a'''
	text1 = '''Your custom designed service plan keeps your vehicle performing at its best.'''
	icon2 = '''ico_2e_fordsvc_b'''
	text2 = '''Ford service centre equipment is built and calibrated specifically for your vehicle. '''
	icon3 = '''ico_2e_fordsvc_c_th'''
	text3 = '''A record of regular servicing improves your vehicle’s re-sale value.'''

[[module]] #Banner Image No Link
path = '''email_modules/image/banner_nolink'''
color = '''white'''

	image = '''th_edm2_whyfordsvc_20161115'''


[[module]] #Split 04
path='email_modules/split/04'
color='green'

	title='''Save big on oil'''
	copy='''Keep your engine running smoothly. Enjoy a 500 THB discount when you buy a 3-visit Oil Save Pack!'''
	cta1_text='''FIND OUT MORE'''
cta1_url='''https://www.ford.co.th/owner/oil-save-pack/'''
cta1_icon='''more'''
cta1_link_name = '''OSP'''
image = '''th_edm2_savebigonoil_20170122'''


[[module]] #PH Social
path = 'email_modules/footer/ph/social'
color = 'white'

[[module]] #PH Online
path = 'email_modules/footer/ph/online'
color = 'white'
+++