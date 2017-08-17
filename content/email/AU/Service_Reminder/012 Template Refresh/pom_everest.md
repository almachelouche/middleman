+++
markets = ["au"]
title = '''AU POM 001 Everest '''

[[module]]
path='email_modules/preheader'

	preheader='''Our Ford-trained technicians are ready to ensure your Ford is in top shape'''
    

[[module]] #Banner Image
path='email_modules/image/banner'
color='white'

	image = '''au_edm2_pom_new_banner_20170817'''
	url_link = '''https://www.ford.com.au/owners/service/'''
    
[[module]]
path='email_modules/spacer/default'
color='white'

	height="30"
    
[[module]]
path='email_modules/singles/copy'
color='''white'''

	copy = '''Hi <%${user.CustomAttribute['FullName']}%>, <br /><br />We hope you're enjoying your new Ford <span style="color:#2D96CD"><%${user.CustomAttribute['Model']}%></span>.<br /><br />Now that you've been on the road for a few months your <%${user.CustomAttribute['Model']}%> is due for its complimentary 2-month/3,000km <a href="https://www.ford.com.au/owners/service/peace-of-mind-inspection/" style="text-decoration:underline; color:#2D96CD">Peace of Mind Service Inspection</a>&#185;. Our Ford trained technicians will inspect your vehicle and ensure it's running at its absolute best.<br /><br />Book your 'Peace of Mind' Service Inspection with <span style="color:#2D96CD"><%${user.CustomAttribute['Dealer_Name']}%></span> on <span style="color:#2D96CD"><%${user.CustomAttribute['Dealer_Phone']}%></span> today, or <a href="https://www.ford.com.au/dealership/" style="text-decoration:underline; color:#2D96CD">locate your nearest dealer</a>.'''

[[module]]
path='email_modules/spacer/default'
color='white'

	height="30"

[[module]]
path='email_modules/singles/ctablock'
color='''white'''
segmentif = ["(user.CustomAttribute['SERVAPPT'] == 'YES')"]

	cta1_text = '''BOOK YOUR INSPECTION'''
	cta1_url = '''https://www.ford.com.au/owners/service/book-service/'''
	cta1_link_name = '''service_booking'''

[[module]] #Banner Image
path='email_modules/image/banner'
color='white'

	image='''au_edm2_everest_accessories1_20170629'''
	url_link='''https://www.youtube.com/watch?v=oYpHsbyN3h4&feature=youtu.be'''
	url_link_name='''everestvideo'''
    
[[module]]
path='email_modules/singles/copy'
color='''white'''

	copy = '''<br/><br/>Did you know your Everest uses something called Diesel Exhaust Fluid? Also known as AdBlue®, this fluid helps reduce vehicle emissions.<br/><br/>It's important that you maintain AdBlue® fluid. So, when your Everest begins to run low, you can purchase a new bottle from your local Ford dealer, selected petrol stations, and automotive retailers.<br/><br/>For more information, and guidance on how to refill your AdBlue® levels, watch the video above or visit the <a href="https://www.ford.com.au/owners/service/ad-blue/#" style="text-decoration:underline; color:#2D96CD;" >Ford AdBlue®</a> website.<br/><br/>'''  
    
[[module]]
path='email_modules/singles/title'
color='''white'''

	title = '''Ger Personal'''   
    
[[module]]
path='email_modules/singles/copy'
color='''white'''

	copy = '''When looking to personalise your Ford Everest there are no better accessories than Ford Genuine Accessories. <a href="https://www.ford.com.au/suv/everest/smart-accessories/" style="text-decoration:underline; color:#2D96CD;" >Click here</a> to see the full range.'''    
    
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

	title1 = '''Fully Loaded<br/>Tow Pack'''
	text_box_height = '''310'''
	copy1 = '''With up to 3,000kg&#178; towing capacity, take on the most epic journeys with the Genuine Ford towpack. The tow pack pairs perfectly with the Everest's Dynamic Stability Control, automatically adapting to changing loads for greater control.'''
	image1 = '''au_edm2_everest_accessories2_20170629'''
	image1_link_url = '''https://www.ford.com.au/suv/everest/smart-accessories/'''
	image1_link_name = '''link_name_here'''
	title2 = '''No Nonsense<br/>Nudge Bar'''
	copy2 = '''Like our range of bull bars, the genuine Ford nudge bar provides added protection to the front of your Everest and has met Ford's stringent engineering and safety standards.'''
	image2 = '''au_edm2_everest_accessories3_20170629'''
	image2_link_url = '''https://www.ford.com.au/suv/everest/smart-accessories/'''
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
2） 800mm water wading available on 4x2 Hi-Rider and 4x4 models only. Achieve when maintain a steady speed of 7kms/hr.<br /><br />
3） This accessory is a Supplier Branded Accessory and is not manufactured or Warranted by Ford. The warranty is provided by the manufacturer. Contact your authorized Ford dealer for details of the accessory manufacturer’s warranty applicable to this accessory.<br /><br />
4） Braked towing capacity when fitted with a Genuine Ford Tow pack and accessory Tow Ball, subject to State and Territory towing regulations.'''

[[module]] #Footer AU Online
path='email_modules/footer/au/online'
color='white'    
+++