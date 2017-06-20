+++
markets = ["in"]
title = '''IN Service Reminder Regular Due/Pdue 008 Children's Day'''
draft = true

[[module]]
path='email_modules/preheader'
color='''nothing'''
segmentif = ["(user.CustomAttribute['Segment'] == 'A')","(user.CustomAttribute['Segment'] == 'B')"]
segmentifdelimit = " || "

	preheader = '''Long time, no see! Your Ford <%${user.CustomAttribute['Selected_Vehicle']}%> is due for service, and our experts can't wait to make sure it's running at its absolute best.'''
	
[[module]]
path='email_modules/preheader'
color='''nothing'''
segmentelseif = ["(user.CustomAttribute['Segment'] == 'C')","(user.CustomAttribute['Segment'] == 'D')"]
segmentelseifdelimit = " || "
	
	preheader = '''Your Ford <%${user.CustomAttribute['Selected_Vehicle']}%> was due for service on <% ${user.CustomAttribute['NextServiceDate']} %>. It's important to service regularly.'''

[[module]] #Header Logo
path='email_modules/header/logo'
color='white'

	image = '''white'''
	url_link = '''https://www.india.ford.com/?emailid=EDM_<%${user.CustomAttribute['DMCDATE']}%>_APMKTC4L_<%${user.CustomAttribute['DMCCAMPAIGN']}%>'''

[[module]] #Cover 06
path='email_modules/cover/02'
color='''white'''
segmentif = ["(user.CustomAttribute['Segment'] == 'A')","(user.CustomAttribute['Segment'] == 'B')"]
segmentifdelimit = " || "

	title = '''It's time for a visit'''
	copy = '''Hello <%${user.CustomAttribute['FullName']}%><br /><br />Long time, no see! Your Ford <%${user.CustomAttribute['Selected_Vehicle']}%> is due for service, and our experts can't wait to make sure it's running at its absolute best.<br /><br />Your next service is due on: <% ${user.CustomAttribute['NextServiceDate']} %> '''
	cta1_text = '''GET A CALLBACK'''
	cta1_url = '''https://www.india.ford.com/ford-service/service-bookings?emailid=EDM_<%${user.CustomAttribute['DMCDATE']}%>_APMKTC4L_<%${user.CustomAttribute['DMCCAMPAIGN']}%>'''
	cta1_link_name = '''callback'''
	cta2_text = '''FIND A DEALER'''
	cta2_url = '''http://www.india.ford.com/locate-dealer?emailid=EDM_<%${user.CustomAttribute['DMCDATE']}%>_APMKTC4L_<%${user.CustomAttribute['DMCCAMPAIGN']}%>_locate-dealer'''
	cta2_link_name = '''locate_dealer'''
	icon = '''in_edm2_svc_wrench_20160801'''

[[module]] #Cover 06
path='email_modules/cover/02'
color='''white_ot'''
segmentelseif = ["(user.CustomAttribute['Segment'] == 'C')","(user.CustomAttribute['Segment'] == 'D')"]
segmentelseifdelimit = " || "

	title = '''Your service is now past due'''
	copy = '''Hello <%${user.CustomAttribute['FullName']}%><br /><br />Your Ford <%${user.CustomAttribute['Selected_Vehicle']}%>'s service is overdue. For the wellbeing of you and your Ford, it's important that you visit a Ford service centre soon.<br /><br />We've got your back. Contact us today and continue to enjoy carefree driving.'''
	cta1_text = '''GET A CALLBACK'''
	cta1_url = '''https://www.india.ford.com/ford-service/service-bookings?emailid=EDM_<%${user.CustomAttribute['DMCDATE']}%>_APMKTC4L_<%${user.CustomAttribute['DMCCAMPAIGN']}%>'''
	cta1_link_name = '''callback'''
	cta2_text = '''FIND A DEALER'''
	cta2_url = '''http://www.india.ford.com/locate-dealer?emailid=EDM_<%${user.CustomAttribute['DMCDATE']}%>_APMKTC4L_<%${user.CustomAttribute['DMCCAMPAIGN']}%>_locate-dealer'''
	cta2_link_name = '''locate_dealer'''
	icon = '''in_edm2_svc_wrench_urgent_20160801'''

[[module]] #Cover 11
path='email_modules/cover/03'
color='white'

	copy = '''<span style="color:#b3b3b3">VIN No: <% ${user.CustomAttribute['VIN_Number']} %><br />Last reported service date: <% ${user.CustomAttribute['Last_Call_Date']} %><br />Last reported mileage: <% ${user.CustomAttribute['Mileage']} %></span>'''

[[module]] #Banner Image No Link
path = '''email_modules/image/banner_nolink'''
color = '''white'''
segmentif = ["(user.CustomAttribute['CityOffer'] == 'Offer')"]

	image = '''in_edm2_childday_20161104'''

[[module]]
path='email_modules/cover/02'
color='''white'''
segmentif = ["(user.CustomAttribute['CityOffer'] == 'Offer')"]

	title='''Children's Day Event'''
	copy='''We've got games... We've got fun... We've got your little one's covered.<br /><br />The quality of experiences and opportunities has a profound impact on a child's life and so we'd like to take your kids around our workshop floor, show them how your car's serviced, show them techniques and of course play a few games.<br /><br />Come for a service from <span style="font-weight:bold">Nov 12-14</span> and <span style="font-weight:bold">celebrate Children's Day with Ford</span>. '''
	cta1_text='''FIND A DEALER'''
	cta1_url='''http://www.india.ford.com/locate-dealer?emailid=EDM_<%${user.CustomAttribute['DMCDATE']}%>_APMKTC4L_<%${user.CustomAttribute['DMCCAMPAIGN']}%>_locate-dealer'''
		
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
	textlink2_link_name = '''parts_calclator'''
	cta1_text = '''FIND A DEALER'''
	cta1_url = '''http://www.india.ford.com/locate-dealer?emailid=EDM_<%${user.CustomAttribute['DMCDATE']}%>_APMKTC4L_<%${user.CustomAttribute['DMCCAMPAIGN']}%>_locate-dealer'''
	cta1_link_name = '''locate_dealer_2'''

[[module]] #Cover 05
path='email_modules/cover/02'
color='''white'''
segmentif = ["(user.CustomAttribute['Segment'] == 'B')","(user.CustomAttribute['Segment'] == 'D')"]
segmentifdelimit = " || "

	title = '''Flexi Service Plan'''
	copy = '''Sign up for a tailored service plan and save up to 25% when you get an oil change, no matter how long you've owned your Ford. And coverage is 100% transferrable, increasing the resale value of your vehicle.'''
	cta1_text = '''FIND OUT MORE'''
	cta1_url = '''http://www.india.ford.com/ford-service/solutions?emailid=EDM_<%${user.CustomAttribute['DMCDATE']}%>_APMKTC4L_<%${user.CustomAttribute['DMCCAMPAIGN']}%>'''
	cta1_link_name = '''flexi_plan'''
	icon = '''in_edm2_flexiplan_20160801'''

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

[[module]] #Footer IN Online
path='email_modules/footer/in/online'
color='white'
+++
