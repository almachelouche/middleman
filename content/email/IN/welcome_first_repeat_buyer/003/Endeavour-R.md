+++
markets = ["in"]
title = '''IN Welcome 003 Endeavour R'''
draft = true

[[module]]
path='email_modules/preheader'


	preheader='''There's nothing quite like a new car. So it really means a lot to us that you chose another Ford.'''

[[module]] #Header Logo
path='email_modules/header/logodesktop'
color='white_pb'

	image = '''white_pb'''
	url_link = '''https://www.india.ford.com/'''

[[module]] #Cover 01
path='email_modules/cover/01'
color='''white'''

 
	title = '''We love having you in the family'''
	copy = '''There's nothing quite like a new car. So it really means a lot to us that you chose another Ford. <br /><br />You're part of the Ford family, and we want to be sure you always enjoy the ride. So you can rest assured that we'll continue to be here for you. Just like you have been for us. '''

[[module]] #Banner Image No Link
path = '''email_modules/image/banner_nolink'''
color = '''white'''

	image = '''in_edm1&4_np_endeavour_20160801'''

[[module]] #Cover 01
path='email_modules/cover/01'
color='''white_gt'''
 
	title = '''Your Free First Service '''
	copy = '''Keep your vehicle in top shape with us. Enjoy a free inspection and a car wash - on us - within the first 3 months or 2500 kilometers, whichever comes first. <br /><br />Contact <%${user.CustomAttribute['Dealer_Name']}%> on <a href="tel:<%${user.CustomAttribute['Dealer_Phone']}%>" style="text-decoration:underline; color:#2D96CD;" ><%${user.CustomAttribute['Dealer_Phone']}%></a> for more information.'''

[[module]] #Cover 05
path='email_modules/cover/02'
color='''green_pb'''
segmentif = ["(user.CustomAttribute['Segment'] == 'N') || (user.CustomAttribute['Segment'] == 'P')"]


	title = '''Extended Peace of Mind'''
	copy = '''Extend your Ford Endeavour's warranty up to 3 years and enjoy worry-free driving. Your warranty protects your Ford against mechanical and electrical failures, and labour charges too¹.'''
	cta1_text = '''GET PEACE OF MIND'''
	cta1_url = '''https://www.india.ford.com/owner/extended-warranty/'''
	cta1_link_name = '''warranty_info'''
	icon = '''in_edm1_extendedwarranty_20160801'''

[[module]] #Split 01
path='email_modules/split/01'
color='white'

	title = '''Time to Accessorise'''
	copy = '''Make your Ford Endeavour your own, with Ford Genuine Accessories that define your style. From the nudge bar to the body graphics - customise your Ford with us.'''
	cta1_text = '''MAKE IT YOURS'''
	cta1_url = '''https://www.india.ford.com/suvs/endeavour/accessories/'''
	cta1_link_name = '''endeavour_exterior'''
	cta1_icon = '''more'''
	image = '''in_edm1_acc_endeavour_20160801'''

[[module]] # Owner App Image Right
path='email_modules/custom/ownerapp_imgr'
color='black'

	title = '''Ford Owners App'''
	text1 = '''Owning a Ford has never been easier, thanks to the Ford Owners App:'''
	text2 = '''<br />&nbsp;&#8226;&nbsp;&nbsp;&nbsp;Utilize the service checklist<br />&nbsp;&#8226;&nbsp;&nbsp;&nbsp;Access Roadside Assistance<br />&nbsp;&#8226;&nbsp;&nbsp;&nbsp;Watch videos about your Ford<br />&nbsp;&#8226;&nbsp;&nbsp;&nbsp;Find a dealer near you'''
	cta1_text = '''iOS'''
	cta1_url = '''https://itunes.apple.com/in/app/ford-owners/id990342351?mt=8'''
	cta1_link_name = '''oa_ios'''
	cta2_text = '''Android'''
	cta2_url = '''https://play.google.com/store/apps/details?id=com.ford.fordowners&hl=en'''
	cta2_link_name = '''oa_android'''
	image = '''owner_app_20160328'''

[[module]] #Dual 04
path='email_modules/dual/04'
color='white'

	title1 = '''Owner Manual'''
	copy1 = '''Download your Owner Manual on your device for access anytime anywhere. '''
	cta1a_text = '''<br /><br />DOWNLOAD NOW'''
	cta1a_url = '''https://www.india.ford.com/owner/owner-manual/'''
	cta1a_link_name = '''owner_manual'''
	cta1b_text = ''''''
	cta1b_url = ''''''
	cta1b_link_name = ''''''
	cta1c_text = ''''''
	cta1c_url = ''''''
	cta1c_link_name = ''''''
	icon1 = '''in_edm1_ownermannual_20160801'''
	title2 = '''Get In SYNC<sup style="font-size: 75%; line-height: 0; position: relative; vertical-align: baseline; top: -0.5em;">®</sup>'''
	copy2 = '''Your Ford Endeavour comes with Ford SYNC<sup style="font-size: 75%; line-height: 0; position: relative; vertical-align: baseline; top: -0.5em;">®</sup> for hands-free control while you drive. '''
	cta2a_text = '''<br /><br />LEARN ABOUT SYNC</a><sup style="font-size: 75%; line-height: 0; position: relative; vertical-align: baseline; color:#2d96cd; top: -0.5em;text-decoration:none">®</sup>'''
	cta2a_url = '''https://www.india.ford.com/sync/'''
	cta2a_link_name = '''sync'''
	cta2b_text = ''''''
	cta2b_url = ''''''
	cta2b_link_name = ''''''
	cta2c_text = ''''''
	cta2c_url = ''''''
	cta2c_link_name = ''''''
	icon2 = '''in_edm1_sync_20160801'''

[[module]] #Footer 4 Icons
path='email_modules/footer/4icons'
color='white'

	icon1_url='''https://www.india.ford.com/locate-dealer/'''
	icon1_link_name = '''locate_dealer'''
	icon1_image='''in_dealers_20160414'''
	icon2_url='''tel:18004252500'''
	icon2_link_name = '''tel_Customer_Care'''
	icon2_image='''in_customer_care_number_20160401'''
	icon3_url='''tel:18002097400'''
	icon3_link_name = '''tel_RSA'''
	icon3_image='''in_rsa_no_20160615'''
	icon4_url='''https://www.fordservicepricepromise.com/?extcmp=serca_101115_105328_fordind'''
	icon4_link_name = '''price_calculator'''
	icon4_image='''in_svc_price_20160801'''

[[module]] #Footer IN Social
path='email_modules/footer/in/social'
color='white'

[[module]] #Footer Disclaimer
path='email_modules/footer/disclaimer'
color='white'
segmentif = ["(user.CustomAttribute['Segment'] == 'N') || (user.CustomAttribute['Segment'] == 'P')"]


	text='''1. Second year factory warranty is applicable for all Ford vehicles manufactured after 1st January 2008.'''

[[module]] #Footer IN Online
path='email_modules/footer/in/online'
color='white'

+++