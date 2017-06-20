+++
markets = ["in"]
title = '''IN Service Reminder Regular Lost Customer 009 EW Offer'''
draft = true

[[module]]
path='email_modules/preheader'
color='''nothing'''

	preheader = '''Long time, no see! We noticed that your Ford <%${user.CustomAttribute['Selected_Vehicle']}%> hasn't been fully serviced lately, and that's got us worried.'''

[[module]] #Header Logo
path='email_modules/header/logo'
color='white'

	image = '''white'''
	url_link = '''https://www.india.ford.com/?emailid=EDM_<%${user.CustomAttribute['DMCDATE']}%>_APMKTC4L_<%${user.CustomAttribute['DMCCAMPAIGN']}%>'''

[[module]] #Cover 06
path='email_modules/cover/02'
color='''white'''

	title = '''It's time for a visit'''
	copy = '''Hello <%${user.CustomAttribute['FullName']}%><br /><br />Long time, no see! We noticed that your Ford <%${user.CustomAttribute['Selected_Vehicle']}%> hasn't been fully serviced lately, and that's got us worried.<br /><br />To stay safe on the road, it's important that you follow your <a href="http://www.india.ford.com/ford-service/solutions/scheduled-service?emailid=EDM_<%${user.CustomAttribute['DMCDATE']}%>_APMKTC4L_<%${user.CustomAttribute['DMCCAMPAIGN']}%>" style="text-decoration:underline; color:#2D96CD;" >service plan</a> and replace worn-out parts as soon as possible.<br /><br />Your next service is due on: <% ${user.CustomAttribute['NextServiceDate']} %>'''
	cta1_text = '''GET A CALLBACK'''
	cta1_url = '''https://www.india.ford.com/ford-service/service-bookings?emailid=EDM_<%${user.CustomAttribute['DMCDATE']}%>_APMKTC4L_<%${user.CustomAttribute['DMCCAMPAIGN']}%>'''
	cta1_link_name = '''callback'''
	cta2_text = '''FIND A DEALER'''
	cta2_url = '''http://www.india.ford.com/locate-dealer?emailid=EDM_<%${user.CustomAttribute['DMCDATE']}%>_APMKTC4L_<%${user.CustomAttribute['DMCCAMPAIGN']}%>_locate-dealer'''
	cta2_link_name = '''locate_dealer'''
	icon = '''in_edm2_svc_wrench_20160801'''

[[module]] #Cover 11
path='email_modules/cover/03'
color='white'

	copy = '''<span style="color:#b3b3b3">VIN No: <% ${user.CustomAttribute['VIN_Number']} %><br />Last reported service date: <% ${user.CustomAttribute['Last_Call_Date']} %><br />Last reported mileage: <% ${user.CustomAttribute['Mileage']} %></span>'''

[[module]] #Split 15
path='email_modules/split/11'
color='white'
segmentif = ["(user.CustomAttribute['Segment'] == 'A')"]

	title = '''Limited time offer'''
	copy = '''When you come in for service between October 1 and December 31, you'll enjoy a massive 15% off all Ford parts and labour¹.'''
	image_url = '''http://www.india.ford.com/locate-dealer?emailid=EDM_<%${user.CustomAttribute['DMCDATE']}%>_APMKTC4L_<%${user.CustomAttribute['DMCCAMPAIGN']}%>_locate-dealer'''
	image_link_name = '''locate_dealer_image'''
	image = '''in_edm2_save15_20161024'''

[[module]] #Split 15
path='email_modules/split/11'
color='white'
segmentelseif = ["(user.CustomAttribute['Segment'] == 'B')"]

	title = '''Limited time offer'''
	copy = '''When you come in for service between October 1 and December 31, you'll enjoy a massive 25% off all Ford parts and labour¹.'''
	image_url = '''http://www.india.ford.com/locate-dealer?emailid=EDM_<%${user.CustomAttribute['DMCDATE']}%>_APMKTC4L_<%${user.CustomAttribute['DMCCAMPAIGN']}%>_locate-dealer'''
	image_link_name = '''locate_dealer_image'''
	image = '''in_edm2_save25_20161024'''

	[[module]] #Split 15
path='email_modules/split/11'
color='white'
segmentelseif = ["(user.CustomAttribute['Segment'] == 'C')"]

	title = '''Limited time offer'''
	copy = '''When you come in for service between October 1 and December 31, you'll enjoy a massive 35% off all Ford parts and labour¹.'''
	image_url = '''http://www.india.ford.com/locate-dealer?emailid=EDM_<%${user.CustomAttribute['DMCDATE']}%>_APMKTC4L_<%${user.CustomAttribute['DMCCAMPAIGN']}%>_locate-dealer'''
	image_link_name = '''locate_dealer_image'''
	image = '''in_edm2_save35_20161024'''

[[module]] #Cover 05
path='email_modules/cover/02'
color='''green_pb'''
segmentif = ["(user.CustomAttribute['CityOffer'] == 'Offer')"]

	title = '''Extended peace of mind'''
	copy = '''You are now eligible for a huge 15% discount on Extended Warranty for your Ford <%${user.CustomAttribute['Selected_Vehicle']}%>, before November 30th. Act now! '''
	cta1_text = '''STAY COVERED'''
	cta1_url = '''https://www.india.ford.com/ford-service/buyextendedwarranty?emailid=EDM_<%${user.CustomAttribute['DMCDATE']}%>_APMKTC4L_<%${user.CustomAttribute['DMCCAMPAIGN']}%>'''
	cta1_link_name = '''warranty_info'''
	icon = '''in_edm1_extendedwarranty_20160801'''

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
	textlink1_url = '''https://www.fordservicepricepromise.com/?extcmp=serca_101115_105328_fordind?emailid=EDM_<%${user.CustomAttribute['DMCDATE']}%>_APMKTC4L_<%${user.CustomAttribute['DMCCAMPAIGN']}%>'''
	textlink1_link_name = '''price_calculator'''
	title2 = '''Pick Up & Drop'''
	text2 = '''Stay home while we pick up, service, and return your vehicle to you. The easiest way to keep your Ford in top shape.'''
	title3 = '''Parts Cost Calculator'''
	text3 = '''We tell you exactly how much a replacement part will cost before you even visit the service centre.'''
	textlink2_text = '''Check parts price'''
	textlink2_url = '''https://partscalculator.fordind.com:1443/Fill_Field?emailid=EDM_<%${user.CustomAttribute['DMCDATE']}%>_APMKTC4L_<%${user.CustomAttribute['DMCCAMPAIGN']}%>'''
	textlink2_link_name = '''parts_calculator'''
	cta1_text = '''FIND A DEALER'''
	cta1_url = '''http://www.india.ford.com/locate-dealer?emailid=EDM_<%${user.CustomAttribute['DMCDATE']}%>_APMKTC4L_<%${user.CustomAttribute['DMCCAMPAIGN']}%>_locate-dealer'''
	cta1_link_name = '''locate_cealer_2'''

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

	icon1_url='''http://www.india.ford.com/locate-dealer?emailid=EDM_<%${user.CustomAttribute['DMCDATE']}%>_APMKTC4L_<%${user.CustomAttribute['DMCCAMPAIGN']}%>_locate-dealer'''
	icon1_link_name = '''locate_dealer_footer'''
	icon1_image='''in_dealers_20160414'''
	icon2_url='''https://fordassured.in/?emailid=EDM_<%${user.CustomAttribute['DMCDATE']}%>_APMKTC4L_<%${user.CustomAttribute['DMCCAMPAIGN']}%>_Ford-Assured'''
	icon2_link_name = '''ford_assured'''
	icon2_image='''in_ford_assured_20160401'''
	icon3_url='''tel:18004252500'''
	icon3_link_name = ''''''
	icon3_image='''in_customer_care_number_20160401'''
	icon4_url='''tel:18002097400'''
	icon4_link_name = ''''''
	icon4_image='''in_rsa_no_20160615'''

[[module]] #Footer IN Social
path='email_modules/footer/in/social'
color='white'

[[module]] #Footer Disclaimer
path='email_modules/footer/disclaimer'
color='white'
segmentif = ["(user.CustomAttribute['Segment'] == 'A')"]

		text='''1. Offer applicable only in Kerala. Excludes accessories, tyres, body shop jobs covered by insurance, and VAS (accessory, exterior & interior cleaning).'''

[[module]] #Footer Disclaimer
path='email_modules/footer/disclaimer'
color='white'
segmentelseif = ["(user.CustomAttribute['Segment'] == 'B')"]

	text='''1. Excludes accessories, tyres, body shop jobs covered by insurance, and VAS (accessory, exterior & interior cleaning).'''

	[[module]] #Footer Disclaimer
path='email_modules/footer/disclaimer'
color='white'
segmentelseif = ["(user.CustomAttribute['Segment'] == 'C')"]

	text='''1. Offer applicable only in Rajasthan. Excludes accessories, tyres, body shop jobs covered by insurance, and VAS (accessory, exterior & interior cleaning).'''

[[module]] #Footer IN Online
path='email_modules/footer/in/online'
color='white'
+++
