+++
markets = ["au"]
title = '''AU POM 001 Mustang'''

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
path='email_modules/spacer/default'
color='white'

	height="30"

	[[module]]
path='email_modules/cover/03'
color='''white'''

	copy='''Hi <%${user.CustomAttribute['FullName']}%>, <br /><br />We hope you're enjoying your new Ford <span style="color:#2D96CD"><%${user.CustomAttribute['Model']}%></span>. Now that you've been on the road for a few months your <%${user.CustomAttribute['Model']}%> is due for its complimentary 2-month/3,000km <a href="https://www.ford.com.au/owners/service/peace-of-mind-inspection/" style="text-decoration:underline; color:#2D96CD">Peace of Mind Service Inspection</a>&#185;. Our Ford trained technicians will inspect your vehicle and ensure it's running at its absolute best. Book your 'Peace of Mind' Service Inspection with <span style="color:#2D96CD"><%${user.CustomAttribute['Dealer_Name']}%></span> on <span style="color:#2D96CD"><%${user.CustomAttribute['Dealer_Phone']}%></span> today, or <a href="https://www.ford.com.au/dealership/" style="text-decoration:underline; color:#2D96CD">locate your nearest dealer</a>.'''

		[[module]]
path='email_modules/singles/ctablock'
color='''white'''
segmentif = ["(user.CustomAttribute['SERVAPPT'] == 'YES')"]

	cta1_text = '''BOOK YOUR SERVICE'''
	cta1_url = '''https://www.ford.com.au/owners/service/book-service/'''
	cta1_link_name = '''BOOK YOUR SERVICE'''
    
    [[module]] #Banner Image
path='email_modules/image/banner'
color='white'

	image = '''au_edm2_mustang_accessories1_20170629'''
	url_link = '''https://www.ford.com.au/owners/service/'''

[[module]]
path='email_modules/cover/03'
color='''white'''

	copy='''<br />When looking to personalise your Ford Mustang there are no better accessories than Ford Genuine Accessories & Ford licenced Accessories (FLA). See a selection below or <a href="https://www.ford.com.au/cars/mustang/smart-accessories/" style="text-decoration:underline; color:#2D96CD;" >Click here</a> to see the full range.'''

[[module]]
path='email_modules/spacer/platinum_20'
color='white'

[[module]]
path='email_modules/dual/05'
color='white'

	title1 = '''Track Handling Pack&#178;'''
	text_box_height = '''260'''
	copy1 = '''Assembled with Ford Performance Parts, the high-performance Track Handling Pack is the perfect suspension system for the driver who demands the most from their Mustang.'''
	image1 = '''au_edm2_mustang_accessories2_20170629'''
	image1_link_url = '''https://www.ford.com.au/cars/mustang/smart-accessories/'''
	image1_link_name = '''link_name_here'''
	title2 = '''Mobile Text Centers&#178;'''
	copy2 = '''Designed to work with production struts, shocks and sway bars, the Mustang Lowering Kit lowers your Mustang by 2.5cm for a more aggressive stance.'''
	image2 = '''au_edm2_mustang_accessories3_20170629'''
	image2_link_url = '''https://www.ford.com.au/cars/mustang/smart-accessories/'''
	image2_link_name = '''link_name_here'''

[[module]]
path='email_modules/spacer/platinum_20'
color='white' 
 
 [[module]]
path='email_modules/dual/05'
color='white'

	title1 = '''Fastback High Rise Spoiler'''
	text_box_height = '''260'''
	copy1 = '''Painted in Absolute Black this high rise rear spoiler will give your Mustang real presence.'''
	image1 = '''au_edm2_mustang_accessories5_20170714'''
	image1_link_url = '''https://www.ford.com.au/cars/mustang/smart-accessories/'''
	image1_link_name = '''link_name_here'''
	title2 = '''Body Styling Kit'''
	copy2 = '''Add a stylish and dynamic look to your Mustang. This styling kit includes a front spoiler, side rockers, stripe kit, and much more.'''
	image2 = '''au_edm2_mustang_accessories5_20170629'''
	image2_link_url = '''https://www.ford.com.au/cars/mustang/smart-accessories/'''
	image2_link_name = '''link_name_here'''

 [[module]]
path='email_modules/spacer/platinum_20'
color='white'
 
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
	image = '''au_edm2_ownersappfinal_20170714'''

[[module]] #Footer AU Social
path='email_modules/footer/au/social'
color='white'

[[module]] #Footer Disclaimer 
path='email_modules/footer/disclaimer'
color='white'

	text = '''DISCLAIMERS:<br /><br />
				1) 'Peace of Mind' Service Inspection expires after 5,000km's or 4 months after delivery of your new Ford (whichever is first).<br /><br /> 
				2) Ford Licensed Accessory.<br /><br />'''

[[module]] #Footer AU Online
path='email_modules/footer/au/online'
color='white'
+++