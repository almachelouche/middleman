+++
markets = ["in"]
title = '''IN Lost Customer 003 Q1'''
draft = true

[[module]]
path='email_modules/preheader'


	preheader = '''We noticed that your Ford hasn't been serviced lately. You're an important member of the Ford family, so that's got us worried. '''

[[module]] #Header Logo
path='email_modules/header/logodesktop'
color='white_pb'

	image = '''white_pb'''
	url_link = '''https://www.india.ford.com/'''

[[module]] #Cover 07
path='email_modules/cover/02'
color='''white'''

	title='''<%${user.CustomAttribute['FullName']}%>, your Ford may need attention'''
	copy='''We noticed that your Ford hasn't been serviced lately. You're an important member of the Ford family, so that's got us worried.<br /><br />To stay safe on the road, it's important that you follow your <a href="https://www.india.ford.com/owner/scheduled-service-plan/" name="service_plan" style="text-decoration:underline; color:#2D96CD;" >service plan</a> and replace worn-out parts as soon as possible.<br /><br />We've got your back. Visit us at a Ford dealer soon. '''
	cta1_text='''BOOK A SERVICE'''
	cta1_url='''https://www.india.ford.com/content/ford/in/en_in/site-wide-content/overlays/forms/service-booking/'''
	cta1_link_name = '''service_booking'''

[[module]] #Split 15
path='email_modules/split/11'
color='white'

	title = '''Limited time offer'''
	copy = '''When you come in for service between January 1 and March 31, you'll enjoy a massive 20% off all Ford parts and labour¹.''' 
	image_url = '''https://www.india.ford.com/locate-dealer/'''
	image_link_name = '''locate_dealer_image_15'''
	image = '''in_edm2_save20_20170105'''

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
	textlink1_url = '''https://www.fordservicepricepromise.com/?extcmp=serca_101115_105328_fordind/'''
	textlink1_link_name = '''price_calculator'''
	title2 = '''Pick Up & Drop'''
	text2 = '''Stay home while we pick up, service, and return your vehicle to you. The easiest way to keep your Ford in top shape.'''
	title3 = '''Parts Cost Calculator'''
	text3 = '''We tell you exactly how much a replacement part will cost before you even visit the service centre.'''
	textlink2_text = '''Check parts price'''
	textlink2_url = '''https://partscalculator.fordind.com:1443/Fill_Field?extcmp=hp_eb_nav/'''
	textlink2_link_name = '''parts_calculator'''
	cta1_text = '''FIND A DEALER'''
	cta1_url = '''https://www.india.ford.com/locate-dealer/'''
	cta1_link_name = '''locate_cealer_2'''

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
