+++
markets = ["au"]
title = '''AU POM 001 Ranger'''

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

	copy = '''Hi <%${user.CustomAttribute['FullName']}%>, <br /><br />We hope you're enjoying your new Ford <span style="color:#2D96CD"><%${user.CustomAttribute['Model']}%></span>.<br /><br /> Now that you've been on the road for a few months your <%${user.CustomAttribute['Model']}%> is due for its complimentary 2-month/3,000km <a href="https://www.ford.com.au/owners/service/peace-of-mind-inspection/" style="text-decoration:underline; color:#2D96CD">Peace of Mind Service Inspection</a>&#185;. Our Ford trained technicians will inspect your vehicle and ensure it's running at its absolute best. <br /><br />Book your 'Peace of Mind' Service Inspection with <span style="color:#2D96CD"><%${user.CustomAttribute['Dealer_Name']}%></span> on <span style="color:#2D96CD"><%${user.CustomAttribute['Dealer_Phone']}%></span> today, or <a href="https://www.ford.com.au/dealership/" style="text-decoration:underline; color:#2D96CD">locate your nearest dealer</a>.'''
    
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
    
[[module]] #Banner Image No Link
path = '''email_modules/image/banner_nolink'''
color = '''white'''

	image = '''au_edm2_ranger_accessories_20170629'''

[[module]]
path='email_modules/spacer/default'
color='white'

	height="30"

[[module]]
path='email_modules/singles/copy'
color='''white'''

	copy = '''When looking to personalise your Ford <span style="color:#2D96CD"><%${user.CustomAttribute['Model']}%></span> there are no better accessories than Ford Genuine Accessories. See a selection below or <a href="https://www.ford.com.au/commercial/ranger/smart-accessories/" style="text-decoration:underline; color:#2D96CD;" >click here</a> to see the full range.'''    
    
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

	title1 = '''Air Intake Snorkel&#178;'''
	text_box_height = '''260'''
	copy1 = '''Tackle deep-water crossings and dusty roads with Ranger's high-strength, durable, UV-resistant polyethylene snorkel.'''
	image1 = '''au_edm2_ranger_accessories1_20170629'''
	image1_link_url = '''https://www.ford.com.au/commercial/ranger/smart-accessories/'''
	image1_link_name = '''link_name_here'''
	title2 = '''Smart Tonneau Cover&#179;'''
	copy2 = '''This UV-resistant soft tonneau cover helps protect your equipment from rain and dust, without drilling fitments, exposed straps or cotton reels.'''
	image2 = '''au_edm2_ranger_accessories2_20170629'''
	image2_link_url = '''https://www.ford.com.au/commercial/ranger/smart-accessories/'''
	image2_link_name = '''link_name_here'''

[[module]]
path='email_modules/spacer/platinum_20'
color='white'

[[module]]
path='email_modules/dual/05'
color='white'

	title1 = '''Serious Bonnet Protection'''
	text_box_height = '''260'''
	copy1 = '''Protect the front of your bonnet from stones, bugs and other small objects with our tough, durable, UV-resistant bonnet protector.'''
	image1 = '''au_edm2_ranger_accessories3_20170629'''
	image1_link_url = '''https://www.ford.com.au/commercial/ranger/smart-accessories/'''
	image1_link_name = '''link_name_here'''
	title2 = '''Fully Loaded Tow Pack&#8308;'''
	copy2 = '''The comprehensive Ford Tow Pack perfectly pairs with Ranger's Dynamic Stability Control technology for next-level towing.'''
	image2 = '''au_edm2_ranger_accessories4_20170629'''
	image2_link_url = '''https://www.ford.com.au/commercial/ranger/smart-accessories/'''
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