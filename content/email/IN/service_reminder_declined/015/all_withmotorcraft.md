
+++
markets = ["in"]
title = '''IN Service Reminder Declined 014 nooffer '''

[[module]]
path='email_modules/preheader'


	preheader = '''We noticed that you declined an important part of your servicing at your last appointment. That's got us worried.'''

[[module]] #Banner Image No Link
path = '''email_modules/image/banner_nolink'''
color = '''white'''

	image = '''in_edm2_fordsvc_20160801'''

[[module]]
path='email_modules/spacer/default'
color='white'

	height="30" 


[[module]]
path='email_modules/singles/title'
color='''white_ot'''

	title = '''Your Ford <%${user.CustomAttribute['Model']}%>'s <%${user.CustomAttribute['BTBPriority']}%> needs attention'''

[[module]]
path='email_modules/spacer/default'
color='white'

	height="30" 

[[module]]
path='email_modules/singles/copy'
color='''white'''

	copy = '''We noticed that you declined an important part of your servicing at your last appointment. That's got us worried.<br /><br />When you come into a Ford service centre, you're putting your vehicle into the best hands possible. Our trained technicians know the specifics of your Ford vehicle and only use genuine Ford parts.<br /><br />As part of the Ford family, we've got your back. Visit us at a Ford dealer soon. '''

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
    
[[module]] #Service Status No Copy
path='email_modules/custom/svcstatus_nocopy'
color='white_in'

    toptitle='''Your Ford <%${user.CustomAttribute['Model']}%>'s Health Status'''
	segmentAgreen = '''(user.CustomAttribute['Brake'] == 'G')'''
	segmentAyellow = '''(user.CustomAttribute['Brake'] == 'Y')'''
	segmentAred = '''(user.CustomAttribute['Brake'] == 'R')'''
		icon1green = '''in_edm2d_status_brake_black_20160801'''
		title1green = '''Brakes'''
		subtitle1green = '''Good to go'''
		icon1yellow = '''in_edm2d_status_brake_black_20160801'''
		title1yellow = '''Brakes'''
		subtitle1yellow = '''Service soon'''
		icon1red = '''in_edm2d_status_brake_white_20160801'''
		title1red = '''Brakes'''
		subtitle1red = '''Service immediately'''
	segmentBgreen = '''(user.CustomAttribute['Tyre'] == 'G')'''
	segmentByellow = '''(user.CustomAttribute['Tyre'] == 'Y')'''
	segmentBred = '''(user.CustomAttribute['Tyre'] == 'R')'''
		icon2green = '''in_edm2d_status_tyre_black_20160801'''
		title2green = '''Tyres'''
		subtitle2green = '''Good to go'''
		icon2yellow = '''in_edm2d_status_tyre_black_20160801'''
		title2yellow = '''Tyres'''
		subtitle2yellow = '''Service soon'''
		icon2red = '''in_edm2d_status_tyre_white_20160801'''
		title2red = '''Tyres'''
		subtitle2red = '''Service immediately'''
	segmentCgreen = '''(user.CustomAttribute['Battery'] == 'G')'''
	segmentCyellow = '''(user.CustomAttribute['Battery'] == 'Y')'''
	segmentCred = '''(user.CustomAttribute['Battery'] == 'R')'''
		icon3green = '''in_edm2d_status_battery_black_20160801'''
		title3green = '''Batteries'''
		subtitle3green = '''Good to go'''
		icon3yellow = '''in_edm2d_status_battery_black_20160801'''
		title3yellow = '''Batteries'''
		subtitle3yellow = '''Service soon'''
		icon3red = '''in_edm2d_status_battery_white_20160801'''
		title3red = '''Batteries'''
		subtitle3red = '''Service immediately'''

[[module]]
path='email_modules/spacer/default'
color='white'

	height="30" 

[[module]] #Cover 11
path='email_modules/singles/copy'
color='white'

	copy = '''VIN No: <% ${user.CustomAttribute['VIN']}%><br />Last reported service date: <%${user.CustomAttribute['Last_Reported_Service_Date']}%><br />Last reported mileage (Kms): <% ${user.CustomAttribute['Mileage']}%>'''

[[module]]
path='email_modules/spacer/default'
color='white'

	height="30" 


[[module]]
path='email_modules/spacer/platinum_20'
color='white'

[[module]]
path='email_modules/dual/05'
color='white'

	title1 = '''Service Price Promise'''
	text_box_height = '''320'''
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