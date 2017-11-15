+++
markets = ["in"]
title = '''IN Service Reminder Regular Lost Customer 021 Motorcraft'''

[[module]]
path='email_modules/preheader'


	preheader = '''We noticed that your Ford <%${user.CustomAttribute['Model']}%> hasn't been fully serviced lately, and that's got us worried. Hello <%${user.CustomAttribute['FullName']}%>, long time, no see! We noticed that your Ford <%${user.CustomAttribute['Model']}%> hasn't been fully serviced lately, and that's got us worried.'''

[[module]] #Banner Image No Link
path = '''email_modules/image/banner_nolink'''
color = '''white'''

	image = '''in_edm2_fordsvc_20160801'''

[[module]]
path='email_modules/singles/title'
color='''white'''

	title = '''It's time for a visit'''   

[[module]]
path='email_modules/spacer/default'
color='white'

	height="30"

[[module]]
path='email_modules/singles/copy'
color='''white'''

	copy = '''Hello <%${user.CustomAttribute['FullName']}%><br /><br />Long time, no see! We noticed that your Ford <%${user.CustomAttribute['Model']}%> hasn't been fully serviced lately, and that's got us worried.<br /><br />To stay safe on the road, it's important that you replace worn-out parts as soon as possible.<br /><br />Your next service is due on: <% ${user.CustomAttribute['NextServiceDate']} %><br /><br />Too busy to visit a service centre? No problem. We'll pick up your vehicle from your home, and return it to you when service is done.''' 

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

[[module]]
path='email_modules/singles/copy'
color='''white'''

	copy = '''VIN No: <% ${user.CustomAttribute['VIN']} %><br />Last reported service date: <% ${user.CustomAttribute['Last_Reported_Service_Date']} %><br />Last reported mileage (Kms): <% ${user.CustomAttribute['Mileage']} %>'''

[[module]]
path='email_modules/spacer/default'
color='white'

	height="30"

[[module]] #Split 15
path='email_modules/split/11'
color='white'

	title = '''Limited time offer'''
	copy = '''When you come in for service between October 1 and December 31, you'll enjoy a massive 20% off all Ford parts and labour¹.'''
	image_url = '''https://www.india.ford.com/locate-dealer/'''
	image_link_name = '''locate_dealer_image'''
	image = '''in_edm2_save20_20170105'''

[[module]]
path='email_modules/spacer/platinum_20'
color='white'

[[module]]
path='email_modules/dual/05'
color='white'
segmentif = ["(user.CustomAttribute['ModelMerge'] == 'EcoSport 2 yrs Plus owners')"]

	title1 = '''Motorcraft&#174; is Here'''
	text_box_height = '''375'''
	copy1 = '''Motorcraft&#174; parts are now available at Ford showrooms nationwide! Backed by Ford, Motorcraft&#174; parts deliver exceptional value and uncompromising quality. Ask us about Motorcraft&#174; parts next time you service your EcoSport.'''
	cta1a_text = '''LEARN MORE'''
	cta1a_url = '''https://www.india.ford.com/owner/ford-motorcraft-parts/'''
	cta1a_link_name = '''motorcraft'''
	image1 = '''in_edm2_motorcraft_20171026'''
	image1_link_url = '''https://www.india.ford.com/owner/ford-motorcraft-parts/'''
	image1_link_name = '''motorcraft_image'''
	title2 = '''Service Price Promise'''
	copy2 = '''Get an affordable service with Ford's Integrated Calculator. Be it scheduled maintenance, part change, or both; you can calculate the all-inclusive cost online, and pay the Ford dealer exactly what you see on the screen!'''
	cta2a_text = '''CHECK SERVICE PRICE'''
	cta2a_url = '''https://www.fordservicepricepromise.com/'''
	cta2a_link_name = '''spp'''
	image2 = '''in_edm2_spp_20171026'''
	image2_link_url = '''https://www.fordservicepricepromise.com/'''
	image2_link_name = '''spp_image'''

[[module]]
path='email_modules/dual/05'
color='white'
segmentelseif = ["(user.CustomAttribute['ModelMerge'] == 'All Model')"]

	title1 = '''Service Price Promise'''
	text_box_height = '''350'''
	copy1 = '''Get an affordable service with Ford's Integrated Calculator. Be it scheduled maintenance, part change, or both; you can calculate the all-inclusive cost online, and pay the Ford dealer exactly what you see on the screen!'''
	cta1a_text = '''CHECK SERVICE PRICE'''
	cta1a_url = '''https://www.fordservicepricepromise.com/'''
	cta1a_link_name = '''spp'''
	image1 = '''in_edm2_spp_20171026'''
	image1_link_url = '''https://www.fordservicepricepromise.com/'''
	image1_link_name = '''spp_image'''
	title2 = '''Ford Genuine Parts'''
	copy2 = '''Don't take chances with your family's safety. Ford Genuine Parts are designed specifically for your Ford vehicle, to ensure it always performs like new. So stick with Ford Genuine Parts, available at Ford service centres nationwide.'''
	cta2a_text = '''CHECK HOW AFFORDABLE'''
	cta2a_url = '''https://www.india.ford.com/surprisingly-affordable/'''
	cta2a_link_name = '''surprisingly_affordable'''
	image2 = '''in_edm2_ford_parts_20171026'''
	image2_link_url = '''https://www.india.ford.com/surprisingly-affordable/'''
	image2_link_name = '''surprisingly_affordable_image'''
    
[[module]]
path='email_modules/spacer/platinum_20'
color='white'    

[[module]]
path='email_modules/spacer/default'
color='white'

	height="30"

[[module]]
path='email_modules/singles/title'
color='''white'''

	title = '''My Ford Profile'''

[[module]]
path='email_modules/spacer/default'
color='white'

	height="30"

[[module]]
path='email_modules/singles/copy'
color='''white'''

	copy = '''Name&#58; <%${user['FirstName']}%> <%${user['LastName']}%><br />Email&#58; <%${user.CustomAttribute['RealEmail']}%><br />Phone&#58; <%${user.CustomAttribute['Mobile_Phone']}%><br />Address&#58; <%${user.CustomAttribute['Address_1']}%> <%${user.CustomAttribute['Address_2']}%><br /><br />Anything changed?'''
    
[[module]]
path='email_modules/spacer/default'
color='white'

	height="30"

[[module]]
path='email_modules/singles/2textcta'
color='''white'''

	cta1_text = '''UPDATE DETAILS'''
	cta1_url = '''https://www.india.ford.com/#/overlay/content/ford/in/en_in/site-wide-content/overlays/forms/profile-update-form.html?req_firstName=<%${user['FirstName']}%>&req_lastName=<%${user['LastName']}%>&req_mobileNumber=<%${user.CustomAttribute['Mobile_Phone']}%>&req_EmailID=<%${user.CustomAttribute['RealEmail']}%>&req_BuildingNo=<%${user.CustomAttribute['Address_1']}%>&req_StreetRoad=<%${user.CustomAttribute['Address_2']}%>&req_Area=<%${user.CustomAttribute['Area']}%>&req_Landmark=<%${user.CustomAttribute['Landmark']}%>&req_city=<%${user.CustomAttribute['City']}%>&req_State=<%${user.CustomAttribute['State']}%>&req_postCode=<%${user.CustomAttribute['Post_Code']}%>'''
	cta1_link_name = '''profile_update'''
	cta2_text = '''VISIT OWNER SITE'''
	cta2_url = '''https://www.india.ford.com/owner/dashboard/#/overlay/content/ford/in/en_in/site-wide-content/overlays/form-overlay/login.html'''
	cta2_link_name = '''owner_dashboard'''
		cta1_icon='''more'''

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

	text='''1. Excludes accessories, tyres, body shop jobs covered by insurance, and VAS (accessory, exterior & interior cleaning).'''

[[module]] #Footer IN Online
path='email_modules/footer/in/online'
color='white'
+++
