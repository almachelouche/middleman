+++
markets = ["in"]
title = '''IN Service Reminder Regular Lost Customer 019 all'''

[[module]]
path='email_modules/preheader'


	preheader = '''We noticed that your Ford <%${user.CustomAttribute['Model']}%> hasn't been fully serviced lately, and that's got us worried. Hello <%${user.CustomAttribute['FullName']}%>, long time, no see! We noticed that your Ford <%${user.CustomAttribute['Model']}%> hasn't been fully serviced lately, and that's got us worried.'''

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

	icon = '''in_edm2_svc_wrench_20160801'''
    
[[module]]
path='email_modules/spacer/default'
color='white'

	height="30"

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

	copy = '''Hello <%${user.CustomAttribute['FullName']}%><br /><br />Long time, no see! We noticed that your Ford <%${user.CustomAttribute['Model']}%> hasn't been fully serviced lately, and that's got us worried.<br /><br />To stay safe on the road, it's important that you follow your <a href="https://www.india.ford.com/owner/scheduled-service-plan/" name="service_plan" style="text-decoration:underline; color:#2D96CD;" >service plan</a> and replace worn-out parts as soon as possible.<br /><br />Your next service is due on: <% ${user.CustomAttribute['NextServiceDate']} %>''' 

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

	copy = '''VIN No: <% ${user.CustomAttribute['VIN']} %><br />Last reported service date: <% ${user.CustomAttribute['Last_Reported_Service_Date']} %><br />Last reported mileage (Kms): <% ${user.CustomAttribute['Mileage']} %>'''

[[module]] #Split 15
path='email_modules/split/11'
color='white'

	title = '''Limited time offer'''
	copy = '''When you come in for service between July 1 and September 30, you'll enjoy a massive 20% off all Ford parts and labour¹.'''
	image_url = '''https://www.india.ford.com/locate-dealer/'''
	image_link_name = '''locate_dealer_image'''
	image = '''in_edm2_save20_20170105'''

[[module]]
path='email_modules/spacer/default'
color='white'

	height="30"

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

[[module]] #Footer Disclaimer
path='email_modules/footer/disclaimer'
color='white'

	text='''1. Excludes accessories, tyres, body shop jobs covered by insurance, and VAS (accessory, exterior & interior cleaning).'''

[[module]] #Footer IN Online
path='email_modules/footer/in/online'
color='white'
+++
