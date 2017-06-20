+++
markets = ["in"]
title = '''IN Service Reminder Regular Due/Pdue 010 All'''
draft = true

[[module]]
path='email_modules/preheader'

segmentif = ["(user.CustomAttribute['Segment'] == 'A') || (user.CustomAttribute['Segment'] == 'B')"]

	preheader = '''Long time, no see! Your Ford <%${user.CustomAttribute['Model']}%> is due for service, and our experts can't wait to make sure it's running at its absolute best.'''

[[module]]
path='email_modules/preheader'

segmentelseif = ["(user.CustomAttribute['Segment'] == 'C') || (user.CustomAttribute['Segment'] == 'D')"]

	preheader = '''For the wellbeing of you and your Ford, visit a Ford service centre soon.'''

[[module]] #Header Logo
path='email_modules/header/logo'
color='white'

	image = '''white'''
	url_link = '''https://www.india.ford.com/'''

[[module]] #Cover 06
path='email_modules/cover/02'
color='''white'''
segmentif = ["(user.CustomAttribute['Segment'] == 'A') || (user.CustomAttribute['Segment'] == 'B')"]


	title = '''It's time for a visit'''
	copy = '''Hello <%${user.CustomAttribute['FullName']}%><br /><br />Long time, no see! Your Ford <%${user.CustomAttribute['Model']}%> is due for service, and our experts can't wait to make sure it's running at its absolute best.<br /><br />Your next service is due on: <% ${user.CustomAttribute['NextServiceDate']} %> '''
	cta1_text = '''GET A CALLBACK'''
	cta1_url = '''https://www.india.ford.com/content/ford/in/en_in/site-wide-content/overlays/forms/service-booking/'''
	cta1_link_name = '''callback'''
	cta2_text = '''FIND A DEALER'''
	cta2_url = '''https://www.india.ford.com/locate-dealer/'''
	cta2_link_name = '''locate_dealer'''
	icon = '''in_edm2_svc_wrench_20160801'''

[[module]] #Cover 06
path='email_modules/cover/02'
color='''white_ot'''
segmentelseif = ["(user.CustomAttribute['Segment'] == 'C') || (user.CustomAttribute['Segment'] == 'D')"]

	title = '''Your service is now past due'''
	copy = '''Hello <%${user.CustomAttribute['FullName']}%><br /><br />Your Ford <%${user.CustomAttribute['Model']}%>'s service is overdue. For the wellbeing of you and your Ford, it's important that you visit a Ford service centre soon.<br /><br />We've got your back. Contact us today and continue to enjoy carefree driving.'''
	cta1_text = '''GET A CALLBACK'''
	cta1_url = '''https://www.india.ford.com/content/ford/in/en_in/site-wide-content/overlays/forms/service-booking/'''
	cta1_link_name = '''callback'''
	cta2_text = '''FIND A DEALER'''
	cta2_url = '''https://www.india.ford.com/locate-dealer/'''
	cta2_link_name = '''locate_dealer'''
	icon = '''in_edm2_svc_wrench_urgent_20160801'''

[[module]] #Cover 11
path='email_modules/cover/03'
color='white'

	copy = '''VIN No: <% ${user.CustomAttribute['VIN']} %><br />Last reported service date: <%${user.CustomAttribute['Last_Reported_Service_Date']}%><br />Last reported mileage: <% ${user.CustomAttribute['Mileage']} %>'''
[[module]] #Banner Image No Link
path = '''email_modules/image/banner_nolink'''
color = '''white'''
segmentif = ["(user.CustomAttribute['CityOffer'] == 'Offer')"]

	image = '''in_edm2_svc_megacamp_20161125'''

[[module]]
path='email_modules/cover/01'
color='''white'''
segmentif = ["(user.CustomAttribute['CityOffer'] == 'Offer')"]

title='''The best time to pamper your car'''
copy='''The new year is just around the corner and it's time for us to get our cars ready for a new season. So spread the word about Ford's Mega Service Camp from 28th Nov to 7th Dec; It's the best time to drive in for exciting offers and a free general check-up.<br /><br />Happy Servicing!'''

[[module]] #Custom 01
path='email_modules/custom/3columntitle3icons'
color='white_ot'
segmentif = ["(user.CustomAttribute['CityOffer'] == 'Offer')"]

	title = ''''''
	icon1 = '''in_edm2_svc_engineoil_20161125'''
	text1 = '''25% Discount<br />on Engine Oil'''
	icon2 = '''in_edm2_svc_oilfilter_20161125'''
	text2 = '''25% Discount<br />on Oil Filter'''
	icon3 = '''in_edm2_svc_labour_20161125'''
	text3 = '''25% Discount<br />on Labour'''

[[module]] #Custom 01
path='email_modules/custom/3columntitle3icons'
color='white_ot'
segmentif = ["(user.CustomAttribute['CityOffer'] == 'Offer')"]

	title = ''''''
	icon1 = '''in_edm2_svc_brakepads_20161125'''
	text1 = '''5% Discount<br />on Brake Pads'''
	icon2 = '''in_edm2_svc_vehiclehealth_20161125'''
	text2 = '''Free<br />vehicle health check-up'''
	icon3 = '''in_edm2_svc_topwash_20161125'''
	text3 = '''Free<br />top wash'''

[[module]] #Banner Image No Link
path = '''email_modules/image/banner_nolink'''
color = '''white'''

	image = '''in_edm2_fordsvc_20160801'''

[[module]] #Custom 02
path='email_modules/custom/3columncolortexttitle'
color='white'

	title1 = '''Service Price Promise'''
	text1 = '''We ensure that there are no surprises in your service cost. The price you see online is the price you pay.'''
	textlink1_text = '''Check service price'''
	textlink1_url = '''https://www.fordservicepricepromise.com/?extcmp=serca_101115_105328_fordind'''
	textlink1_link_name = '''price_calculator'''
	title2 = '''Pick Up & Drop'''
	text2 = '''Stay home while we pick up, service, and return your vehicle to you. The easiest way to keep your Ford in top shape.'''
	title3 = '''Parts Cost Calculator'''
	text3 = '''We tell you exactly how much a replacement part will cost before you even visit the service centre.'''
	textlink2_text = '''Check parts price'''
	textlink2_url = '''https://partscalculator.fordind.com:1443/Fill_Field?extcmp=hp_eb_nav'''
	textlink2_link_name = '''parts_calclator'''
	cta1_text = '''FIND A DEALER'''
	cta1_url = '''https://www.india.ford.com/locate-dealer/'''
	cta1_link_name = '''locate_dealer_2'''

[[module]] #Custom 01
path='email_modules/custom/3columntitle3icons'
color='white'

	title = '''Great service is everything'''
	icon1 = '''in_edm2_fordsvc_a_20160801'''
	text1 = '''Your custom designed service plan keeps your vehicle performing at its best.'''
	icon2 = '''in_edm2_fordsvc_b_20160801'''
	text2 = '''Ford service centre equipment is built and calibrated specifically for your vehicle.'''
	icon3 = '''in_edm2_fordsvc_c_20160801'''
	text3 = '''A record of regular servicing improves your vehicle's re-sale value.'''

[[module]] #Banner Image No Link
path = '''email_modules/image/banner_nolink'''
color = '''white'''

	image = '''in_edm2_greatsvc_20160801'''

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

[[module]] #Footer IN Online
path='email_modules/footer/in/online'
color='white'
+++
