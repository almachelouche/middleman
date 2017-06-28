+++
markets = ["au"]
title = '''AU POM Mustang'''

[[module]]
path='email_modules/preheader'
color='''white'''

	preheader='''Our Ford-trained technicians are ready to ensure your Ford is in top shape.'''


[[module]] #Header Logo
path='email_modules/header/logo'
color='white'

	image = '''white'''
	url_link = '''https://www.ford.com.au/'''


[[module]] #Banner Image
path='email_modules/image/banner'
color='white'

	image = '''AU_edm2_svc_banner_20160615'''
	url_link = '''https://www.ford.com.au/owners/service/'''

	[[module]]
path='email_modules/cover/03'
color='''white'''

	copy='''<br />Hi <%${user.CustomAttribute['FullName']}%><br /><br />We hope you’re enjoying your new Ford <nameplate>.<br />Now that you’ve been on the road for a few months your <nameplate> is due for its complimentary 2-month/3,000&#185;km  ‘Peace of Mind’ Service Inspection. Our Ford trained technicians will inspect your vehicle and ensure it’s running it’s absolute best.<br /><br />Service Inspection. <br /><br />Book your ‘Peace of Mind Service Inspection' with <Dealer Name> on <Dealer Phone> today, or find your nearest dealer here. '''

		[[module]]
path='email_modules/singles/ctablock'
color='''white'''

	cta1_text = '''BOOK YOUR INSPECTION'''
	cta1_url = '''https://www.ford.com.au/owners/service/book-service/'''
	cta1_link_name = '''BOOK YOUR INSPECTION'''
    
    [[module]] #Banner Image
path='email_modules/image/banner'
color='white'

	image = '''AU_edm2_svc_banner_20160615'''
	url_link = '''https://www.ford.com.au/owners/service/'''

[[module]]
path='email_modules/cover/03'
color='''white'''

	copy='''<br />When looking to personalise your Ford <nameplate> there are no better accessories than Ford Genuine Accessories. Click here to see the full range.'''

 [[module]] #Split 13
path='email_modules/split/13'
color='white'

	title1='''Track Handling Pack'''
	title2='''Mobile Text Centers'''
	copy1='''Assembled with Ford Performance Parts, the high-performance Track Handling Pack is the perfect suspension system for the driver who demands the most from their Mustang.'''
	copy2='''Designed to work with production struts, shocks and sway bars, the Mustang Lowering Kit lowers your Mustang by 2.5cm for a more aggressive stance.<br/><br/>'''
	image1='''tms_20160328'''
    image1_url='''http://google.com'''
    image1_name='''Some'''
    image2='''tms_20160328'''
    image2_url='''http://google.com'''
    image2_name='''Some'''
    
    [[module]] #Split 13
path='email_modules/split/13'
color='white'

	title1='''Fastback High Rise Spoiler'''
	title2='''Body Styling Kit'''
	copy1='''Painted in Absolute Black this high rise rear spoiler will give your Mustang real presence.<br/><br/>'''
	copy2='''Add a stylish and dynamic look to your Mustang. This styling kit includes a front spoiler, side rockers, strip kit, and much more.'''
	image1='''tms_20160328'''
    image1_url='''http://google.com'''
    image1_name='''Some'''
    image2='''tms_20160328'''
    image2_url='''http://google.com'''
    image2_name='''Some'''
 
[[module]] # Owner App Image Right
path='email_modules/custom/ownerapp_imgr'
color='white'

	title = '''Know your Ford'''
	text1 = '''Did you know with the Ford Owner app, you can accesss the entire SYNC Phrasebok, read your vehicle's Owner Manual and watch useful 'How To' videos?<br/><br/>'''
	text2 = '''Download the Ford Owner app and get started today.<br/><br/>Just search Ford Owners in your app store.'''
	cta1_text = '''iOS'''
	cta1_url = '''https://itunes.apple.com/au/app/ford-owners/id990342351?mt=8'''
	cta1_link_name = '''ios1'''
	cta2_text = '''ANDROID'''
	cta2_url = '''https://play.google.com/store/apps/details?id=com.ford.fordowners&hl=en/'''
	cta2_link_name = '''android1'''
	image = '''AU_edm2_owner_app2_20160615'''

[[module]] #Footer AU Social
path='email_modules/footer/au/social'
color='white'

[[module]] #Footer Disclaimer 
path='email_modules/footer/disclaimer'
color='white'

	text = '''DISCLAIMERS:<br /><br />
				1) ‘Peace of Mind’ Service Inspection expires after 5,000km’s or 4 months after delivery of your new Ford (whichever is first).<br /><br /> 
				2) Ford Licensed Accessory.<br /><br />'''

[[module]] #Footer AU Online
path='email_modules/footer/au/online'
color='white'
+++