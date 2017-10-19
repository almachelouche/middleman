+++
markets = ["in"]
title = '''IN Service Reminder Regular Due/Pdue 021 Rest'''

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
 
[[module]] #Banner Image No Link
path = '''email_modules/image/banner_nolink'''
color = '''white'''

  image = '''in_edm2_fordsvc_20170321'''
    
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
color='''white_ot'''
segmentif = ["(user.CustomAttribute['Esplit'] == 'PastDue')"]

	title = '''Your service is now past due'''    

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
	cta2_text = '''&nbsp;BOOK A PICK-UP'''
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

[[module]]
path='email_modules/spacer/platinum_20'
color='white'

[[module]]
path='email_modules/dual/05'
color='white'

	title1 = '''Service Price Promise'''
	text_box_height = '''340'''
	copy1 = '''Get an affordable service with Ford's Integrated Calculator. Be it scheduled maintenance, part change, or both; you can calculate the all-inclusive cost online, and pay the Ford dealer exactly what you see on the screen!'''
	cta1a_text = '''CHECK SERVICE PRICE'''
	cta1a_url = '''https://www.fordservicepricepromise.com/'''
	cta1a_link_name = '''price_calculator'''
	image1 = '''in_edm5_service_journey_20170927'''
	image1_link_url = '''https://www.youtube.com/watch?v=EpUVjpuhxEE&t=133s/'''
	image1_link_name = '''service_journey_image'''
	title2 = '''Ford Genuine Parts'''
	copy2 = '''Don't take chances with your family's safety. Fake parts have no guarantees, whereas Ford ensures that our parts meet every quality standard, and work together to give the best results. So, stick to Ford genuine parts from authorised Service Centers, and drive your car without any worries.'''
	cta2a_text = '''CHECK HOW AFFORDABLE'''
	cta2a_url = '''https://www.india.ford.com/surprisingly-affordable/'''
	cta2a_link_name = '''surprisingly_affordable'''
	image2 = '''in_edm6_safety_tvc_20170927'''
	image2_link_url = '''https://www.youtube.com/watch?v=oLJOVLqzHys'''
	image2_link_name = '''safety_video_image'''

[[module]]
path='email_modules/spacer/platinum_20'
color='white'

[[module]]
path='email_modules/dual/05'
color='white'

	title1 = '''Motorcraft&#174; is Here'''
	text_box_height = '''320'''
	copy1 = '''Motorcraft&#174; parts are now available at Ford showrooms nationwide! Recommended by Ford, Motorcraft&#174; parts deliver exceptional value and uncompromising quality. Best of all, they’re designed specifically for your Ford vehicle. So next time you service your Ford EcoSport, ask about Motorcraft&#174; parts.'''
	cta1a_text = '''LEARN MORE'''
	cta1a_url = '''https://www.fordservicepricepromise.com/'''
	cta1a_link_name = '''motorcraft'''
	image1 = '''in_edm5_service_journey_20170927'''
	image1_link_url = '''https://www.india.ford.com/owner/ford-motorcraft-parts/'''
	image1_link_name = '''motorcraft_image'''
	title2 = '''Service Price Promise'''
	copy2 = '''Get an affordable service with Ford's Integrated Calculator. Be it scheduled maintenance, part change, or both; you can calculate the all-inclusive cost online, and pay the Ford dealer exactly what you see on the screen!'''
	cta2a_text = '''CHECK SERVICE PRICE'''
	cta2a_url = '''https://www.fordservicepricepromise.com/'''
	cta2a_link_name = '''price_calculator'''
	image2 = '''in_edm5_service_journey_20170927'''
	image2_link_url = '''https://www.fordservicepricepromise.com/'''
	image2_link_name = '''price_calculator_image'''

[[module]]
path='email_modules/spacer/platinum_20'
color='white'    

[[module]] #Cover 05
path='email_modules/cover/02'
color='''green_pb'''
segmentif = ["(user.CustomAttribute['SSPStatus'] == 'NO')"]

	title = '''Scheduled Service Plan'''
	copy = '''Our peace-of-mind service plans keep your Ford performing its best. Enjoy up to 5 years of capped pricing and save up to 10% on servicing. And coverage is 100% transferrable, increasing your Ford's resale value.'''
	cta1_text = '''VIEW PLANS'''
	cta1_url = '''https://www.india.ford.com/owner/scheduled-service-plan/'''
	cta1_link_name = '''ssp'''
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

[[module]] #Footer IN Online
path='email_modules/footer/in/online'
color='white'
+++