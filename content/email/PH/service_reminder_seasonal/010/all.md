+++
markets = ["ph"]
title = 'PH Service Reminder Seasonal 010 All'

preheader = '''When you're looking for high-quality tires and batteries, there's no better place to visit than your nearest Ford dealer. Purchase GoodYear tires directly from us and you'll enjoy'''

[[module]] #Header Logo
path='email_modules/header/logo'
color='white'

	image = '''white'''
	url_link = '''http://www.ford.com.ph/'''

[[module]] #Cover 07
path='email_modules/cover/02'
color='''white'''

	title = '''Buy three tires, get one free'''
	copy = '''Did you know tires need to be replaced every 60,000km? With the rainy season on the way, it's important that you replace old tires ASAP.<br /><br />That's why when you buy three tires, we'll give you the fourth free. That's a savings of up to Php 5,000! You'll also enjoy free wheel alignment and tire balancing (at selected dealerships).<br /><br />And rest assured, our certified Ford technicians only use top-quality, accredited tire brands. '''
	cta1_text = '''FIND OUT MORE'''
	cta1_url = '''http://www.ford.com.ph/buying/service'''
	cta1_link_name = '''tire_campaign'''


[[module]] #Custom 01
path='email_modules/custom/3columntitle3icons'
color='white'

	title = '''Why Ford servicing?'''
	icon1 = '''ph_edm2_fordsvc_a_20160801'''
	text1 = '''Your custom designed service plan keeps your vehicle performing at its best. '''
	icon2 = '''ph_edm2_fordsvc_b_20160801'''
	text2 = '''Ford service centre equipment is built and calibrated specifically for your vehicle. '''
	icon3 = '''ph_edm2_fordsvc_c_20160801'''
	text3 = '''A record of regular servicing improves your vehicle's re-sale value.'''

[[module]] #Banner Image No Link
path = '''email_modules/image/banner_nolink'''
color = '''white'''

	image = '''ph_edm2a_tirechange_20160801'''

[[module]] #Dual 02
path='email_modules/dual/02'
color='white'

	icon1 = '''ph_edm2_call_20160801'''
	title1 = '''Book it now'''
	cta1_text = '''Call your Ford Dealer on<%${user.CustomAttribute['Work_Phone']}%>'''
	cta1_url = '''tel:<%${user.CustomAttribute['Home_Phone']}%>'''
	cta1_link_name = '''link_name_here'''
	cta2_text = '''Find your nearest Ford Dealer'''
	cta2_url = '''http://www.ford.com.ph/locate-a-dealer/'''
	cta2_link_name = '''find_dealer'''
	icon2 = '''ph_edm2_ownerprofile_20160801'''
	title2 = '''Anything changed? '''
	copy = '''Update your details now so you don't miss our latest offers.'''
	cta3_text = '''UPDATE NOW'''
	cta3_url = '''https://www.ford.com.ph/owner/login'''
	cta3_link_name = '''anything_changed'''

[[module]] #PH Social
path = 'email_modules/footer/ph/social'
color = 'white'

[[module]] #PH Online
path = 'email_modules/footer/ph/online'
color = 'white'
+++