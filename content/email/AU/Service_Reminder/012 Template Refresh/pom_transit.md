+++
markets = ["au"]
title = '''AU POM 001 Transit '''

[[module]]
path='email_modules/preheader'

	preheader=''''''
    
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
path='email_modules/singles/copy'
color='''white'''

	copy = '''Hi <%${user.CustomAttribute['FullName']}%>, <br /><br />We hope you're enjoying your new Ford <span style="color:#2D96CD"><%${user.CustomAttribute['Model']}%></span>. Now that you've been on the road for a few months your <%${user.CustomAttribute['Model']}%> is due for its complimentary 2-month/3,000km <span style="text-decoration:underline; color:#2D96CD">Peace of Mind Service Inspection</span>&#185;. Our Ford trained technicians will inspect your vehicle and ensure it’s running at its absolute best. Book your 'Peace of Mind' Service Inspection with <span style="color:#2D96CD"><%${user.CustomAttribute['Dealer_Name']}%></span> on <span style="color:#2D96CD"><%${user.CustomAttribute['Dealer_Phone']}%></span> today, or locate your nearest dealer.'''

[[module]]
path='email_modules/spacer/default'
color='white'

	height="30"

[[module]]
path='email_modules/singles/ctablock'
color='''white'''

	cta1_text = '''BOOK YOUR INSPECTION'''
	cta1_url = '''https://www.ford.com.au/owners/service/book-service/'''
	cta1_link_name = '''service_booking'''

[[module]] #Banner Image
path='email_modules/image/banner'
color='white'

	image='''au_edm2_transit_video_20170629'''
	url_link='''https://www.youtube.com/watch?v=oYpHsbyN3h4&feature=youtu.be'''
	url_link_name='''transitvideo'''
    
[[module]]
path='email_modules/singles/copy'
color='''white'''

	copy = '''<br/><br/>Did you know your Transit uses something called Diesel Exhaust Fluid? Also known as AdBlue®, this fluid helps reduce vehicle emissions.<br/><br/>It’s important that you maintain AdBlue® fluid levels. So, when your Everest begins to run low, you can purchase a new bottle from your local Ford dealer, selected petrol stations, and automotive retailers.<br/><br/>For more information, and guidance on how to refill your AdBlue® levels, watch the video above or visit the <a href="https://www.youtube.com/watch?v=oYpHsbyN3h4&feature=youtu.be" style="text-decoration:underline; color:#2D96CD;" >Ford AdBlue®</a> website.<br/><br/>'''  
    
[[module]]
path='email_modules/singles/title'
color='''white'''

	title = '''Ger Personal'''   

[[module]]
path='email_modules/spacer/default'
color='white'

	height="30"
    
[[module]] #Banner Image No Link
path = '''email_modules/image/banner_nolink'''
color = '''white'''

	image = '''au_edm2_transit_accessories_20170629'''
    
[[module]]
path='email_modules/singles/copy'
color='''white'''

	copy = '''When looking to personalise your Ford Transit there are no better accessories than Ford Genuine Accessories. <a href="https://www.ford.com.au/shopping/accessories/" style="text-decoration:underline; color:#2D96CD;" >Click here</a> to see the full range.'''    
    
[[module]]
path='email_modules/spacer/default'
color='white'

	height="30"

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
	image = '''au_edm2_ownerapp_20170707'''

[[module]] #Footer AU Social
path='email_modules/footer/au/social'
color='white'

[[module]] #Footer Disclaimer 
path='email_modules/footer/disclaimer'
color='white'

	text = '''DISCLAIMERS:<br /><br />
				1) ‘Peace of Mind’ Service Inspection expires after 5,000km’s or 4 months after delivery of your new Ford (whichever is first).<br /><br /> '''

[[module]] #Footer AU Online
path='email_modules/footer/au/online'
color='white'    
+++