+++
markets = ["in"]
title = '''IN Service Reminder Regular Due/Pdue 015 Summer Camp East'''
draft=true

[[module]]
path='email_modules/preheaderbefore'
color='''nothing'''
segmentif = ["(user.CustomAttribute['Esplit'] == 'Due')"]

	preheader = '''Your Ford <%${user.CustomAttribute['Model']}%> is due for service, and our experts can't wait to make sure it's running at its absolute best. Hello <%${user.CustomAttribute['FullName']}%>, long time, no see! Your Ford <%${user.CustomAttribute['Model']}%> is due for service, and our experts can't wait to make sure it's running at its absolute best.'''

[[module]]
path='email_modules/preheaderbefore'
color='''nothing'''
segmentelseif = ["(user.CustomAttribute['Esplit'] == 'PastDue')"]

	preheader = '''Your Ford <%${user.CustomAttribute['Model']}%> was due for service on <%${user.CustomAttribute['NextServiceDate']}%>. It's important to service regularly. Hello <%${user.CustomAttribute['FullName']}%>, your Ford <%${user.CustomAttribute['Model']}%>'s service is overdue. For the wellbeing of you and your Ford, it's important that you visit a Ford service centre soon.'''

[[module]]
path='email_modules/body'
color='''nothing'''

[[module]]
path='email_modules/preheaderafter'
color='''nothing'''
segmentif = ["(user.CustomAttribute['Esplit'] == 'Due')"]

	preheader = '''Your Ford <%${user.CustomAttribute['Model']}%> is due for service, and our experts can't wait to make sure it's running at its absolute best. Hello <%${user.CustomAttribute['FullName']}%>, long time, no see! Your Ford <%${user.CustomAttribute['Model']}%> is due for service, and our experts can't wait to make sure it's running at its absolute best.'''

[[module]]
path='email_modules/preheaderafter'
color='''nothing'''
segmentelseif = ["(user.CustomAttribute['Esplit'] == 'PastDue')"]

	preheader = '''Your Ford <%${user.CustomAttribute['Model']}%> was due for service on <%${user.CustomAttribute['NextServiceDate']}%>. It's important to service regularly. Hello <%${user.CustomAttribute['FullName']}%>, your Ford <%${user.CustomAttribute['Model']}%>'s service is overdue. For the wellbeing of you and your Ford, it's important that you visit a Ford service centre soon.'''
 
[[module]] #Header Logo
path='email_modules/header/logodesktop'
color='white_pb'

	image = '''white_pb'''
	url_link = '''https://www.india.ford.com/'''

[[module]] #Cover 06
path='email_modules/cover/02'
color='''white'''
segmentif = ["(user.CustomAttribute['Esplit'] == 'Due')"]

	title = '''It's time for a visit'''
	copy = '''Hello <%${user.CustomAttribute['FullName']}%><br /><br />Long time, no see! Your Ford <%${user.CustomAttribute['Model']}%> is due for service, and our experts can't wait to make sure it's running at its absolute best.<br /><br />Your next service is due on: <% ${user.CustomAttribute['NextServiceDate']} %> '''
	cta1_text = '''GET A CALLBACK'''
	cta1_url = '''https://www.india.ford.com/#overlay/content/ford/in/en_in/site-wide-content/overlays/forms/service-booking.html/'''
	cta1_link_name = '''callback'''
	cta2_text = '''FIND A DEALER'''
	cta2_url = '''https://www.india.ford.com/locate-dealer/'''
	cta2_link_name = '''locate_dealer'''
	icon = '''in_edm2_svc_wrench_20160801'''

[[module]] #Cover 06
path='email_modules/cover/02'
color='''white_ot'''
segmentif = ["(user.CustomAttribute['Esplit'] == 'PastDue')"]

	title = '''Your service is now past due'''
	copy = '''Hello <%${user.CustomAttribute['FullName']}%><br /><br />Your Ford <%${user.CustomAttribute['Model']}%>'s service is overdue. For the wellbeing of you and your Ford, it's important that you visit a Ford service centre soon.<br /><br />We've got your back. Contact us today and continue to enjoy carefree driving.'''
	cta1_text = '''GET A CALLBACK'''
	cta1_url = '''https://www.india.ford.com/#overlay/content/ford/in/en_in/site-wide-content/overlays/forms/service-booking.html/'''
	cta1_link_name = '''callback'''
	cta2_text = '''FIND A DEALER'''
	cta2_url = '''https://www.india.ford.com/locate-dealer/'''
	cta2_link_name = '''locate_dealer'''
	icon = '''in_edm2_svc_wrench_urgent_20160801'''

[[module]]
path='email_modules/singles/copy'
color='''white'''

	copy = '''VIN No: <% ${user.CustomAttribute['VIN']}%><br />Last reported service date: <%${user.CustomAttribute['Last_Reported_Service_Date']}%><br />Last reported mileage (Kms): <% ${user.CustomAttribute['Mileage']}%>'''

[[module]]
path='email_modules/spacer/default'
color='white'

	height="30"

[[module]] #Banner Image No Link
path = '''email_modules/image/banner_nolink'''
color = '''white'''

	image = '''in_edm2_summer_camp_north_20170315'''

[[module]]
path='email_modules/spacer/default'
color='white'

	height="20"

[[module]]
path='email_modules/singles/title'
color='''white'''

	title = '''The heat is on!'''

[[module]]
path='email_modules/spacer/default'
color='white'

	height="30"

[[module]]
path='email_modules/singles/copy'
color='''white'''

	copy = '''Get your car geared up for the summer. Drive into any Ford Service Centre and enjoy hot offers including free 50+ point Car Check-up, Car Body Wash and discounts up to 50%*. And if your car is more than 5 years old, you will receive an extra 10%* off! <span style="font-weight:bold">Offers valid from 27th March to 2nd April.</span>'''

[[module]] #Custom 4 Icons
path='email_modules/custom/4icons'
color='white'

	title = ''''''
	icon1_url='''http://www.india.ford.com/locate-dealer'''
	icon1_link_name = '''locate_dealer'''
	icon1_image='''in_edm2_summer_camp_ac_20170316'''
	icon1_text = '''10%* off on<br />AC Gas & Filter'''
	icon2_url='''tel:18004252500'''
	icon2_link_name = '''locate_dealer2'''
	icon2_image='''in_edm2_summer_camp_coolant2_20170316'''
	icon2_text = '''10%* off<br />on Coolant'''
	icon3_url='''tel:18002097400'''
	icon3_link_name = '''locate_dealer3'''
	icon3_image='''in_edm2_summer_camp_oil_filter_20170316'''
	icon3_text = '''50%* off<br />on Oil Filter'''
	icon4_url='''https://partscalculator.fordind.com:1443/Fill_Field'''
	icon4_link_name = '''locate_dealer4'''
	icon4_image='''in_edm2_summer_bodypaint_20170316'''
	icon4_text = '''20%* off<br />on Full Body Paint<br />(Labour only)'''

	[[module]] #Custom 4 Icons
path='email_modules/custom/4icons'
color='white'

	title = ''''''
	icon1_url='''http://www.india.ford.com/locate-dealer'''
	icon1_link_name = '''locate_dealer'''
	icon1_image='''in_edm2_summer_camp_coolant_20170316'''
	icon1_text = '''&#8377;1000* off<br />on Batteries'''
	icon2_url='''tel:18004252500'''
	icon2_link_name = '''locate_dealer2'''
	icon2_image='''in_edm2_summer_camp_tyres_20170316'''
	icon2_text = '''Attractive Gift*<br />on purchase of 4 tyres'''
	icon3_url='''tel:18002097400'''
	icon3_link_name = '''locate_dealer3'''
	icon3_image='''in_edm2_summer_camp_brake_pads_20170316'''
	icon3_text = '''10%* off<br />on Brake Pads'''
	icon4_url='''https://partscalculator.fordind.com:1443/Fill_Field'''
	icon4_link_name = '''locate_dealer4'''
	icon4_image='''in_edm2_summer_camp_5yr_20170316'''
	icon4_text = '''10%*off on all<br />Ford approved<br />Value Added Services'''

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

[[module]] #Cover 05
path='email_modules/cover/02'
color='''white'''
segmentif = ["(user.CustomAttribute['SSPStatus'] == 'NO')"]

	title = '''Scheduled Service Plan'''
	copy = '''Our peace-of-mind service plans keep your Ford performing its best. Enjoy up to 5 years of capped pricing and save up to 10% on servicing. And coverage is 100% transferrable, increasing your Ford's resale value.'''
	cta1_text = '''FIND OUT MORE'''
	cta1_url = '''https://www.india.ford.com/owner/scheduled-service-plan/'''
	cta1_link_name = '''SSP'''
	icon = '''in_edm1_extendedwarranty_20160801'''

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

	text = '''*Terms and conditions apply. Offer valid on all Ford cars serviced between Mar 20 - 26. Extra 10% discount applicable only on vehicles retailed before year 2011. Offer on Tyre is applicable on purchase of a set of 4 tyres & only on select brand. For more details visit your nearest Ford workshop.'''

[[module]] #Footer IN Online
path='email_modules/footer/in/online'
color='white'
+++