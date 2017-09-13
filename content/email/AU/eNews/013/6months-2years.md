+++
markets = ["au"]
title = '''AU Enews 013 6-2year'''


[[module]] 
path='email_modules/preheader'
color='''white'''

	preheader='''Joining the Ford lineup in 2018, Ranger Raptor will be the ultimate performance off-road truck designed to conquer the toughest of all terrains.'''

[[module]]
path='email_modules/body'
color='''white'''

[[module]]
path='email_modules/preheader'
color='''white'''

	preheader='''Joining the Ford lineup in 2018, Ranger Raptor will be the ultimate performance off-road truck designed to conquer the toughest of all terrains.'''

	[[module]] #Header eNews 
path='email_modules/header/enews'
color='black'

	title = '''Insider'''
	date = '''<date>'''
	copy = '''IN THIS ISSUE:<br /><module 1>| <module 2> | <module 3> | <module 4> '''

[[module]] #Header Logo
path='email_modules/header/logodesktop'
color='black'

	image = '''black'''
	url_link = '''https://www.ford.com.au/'''

[[module]] #eNews Top Story 
path='email_modules/custom/enews_topstory'
color='black'

    title = '''Ranger Raptor is Coming!'''
	copy = '''In 2018, Raptor Ranger is coming to Australia, bringing along with it the newest way to be tough. This ultimate off-road performance truck is already causing quite the buzz. Click below to get exclusive updates on the launch of this ultimate off-road 4x4.
    '''
	cta1_text = '''WATCH THE VIDEO'''
	cta1_url = '''https://www.ford.com.au/commercial/ranger/raptor/?intcmp=bb-fau-vhp-ford%20ranger-fau-vhp-ford%20ranger-return#overlay/content/ford/au/en_au/ranger-content/overlay-videos/raptor-videos/video1.html '''
	cta1_link_name = '''RangerRaptor'''
	cta1_icon = '''play'''

	[[module]] #Banner Image #NON NSW
path='email_modules/image/banner'
color='white'

	image = '''<image>'''
	url_link = '''<link>'''


[[module]] #Split 02 
path='email_modules/split/02'
color='green'
segmentelse = ["(user.CustomAttribute['Model'] =="]

    title = '''Did you know Ford sells tyres?'''
	copy = '''At Ford, we're committed to offering you tyres at competitive prices. That's why we're very excited to announce our Low Price Tyre Guarantee. We'll match a competitor's price on selected tyres we stock.'''
	cta1_text = '''LEARN MORE'''
	cta1_url = '''<link>'''
	cta1_link_name = '''LPTG'''
	cta1_icon = '''more'''
	image = '''<image>'''

	[[module]] #Split 01
path='email_modules/split/01'
color='darkblue'

	title = '''Engine and Oil Health 101'''
	copy = '''Your car's engine is the most important part of your car. It is the heart of your car, the component that help your car run smoothly. Click below to watch to learn how to keep your engine performing at its best and make sure your engine oil is okay.'''
	cta1_text = '''WATCH NOW'''
	cta1_url = '''https://youtu.be/yM6vCGm-AAQ'''
	cta1_link_name = '''engineandoil'''
	cta1_icon = '''play'''
	image = '''<image>'''

	[[module]] #Split 02
path='email_modules/split/02'
color='lightblue'

    title = '''Support Breast Cancer Research'''
	copy = '''We partnered with the National Breast Cancer Foundation to support breast cancer research. We asked granddaughters to talk to their grandmothers about their experiences with breast cancer. Hear the inspiring words from these women.'''
	cta1_text = '''GET INSPIRED NOW'''
	cta1_url = '''https://www.facebook.com/FordAustralia/videos/vb.126096123746/10156683020833747/?type=2&theater'''
	cta1_link_name = '''SBCR'''
	cta1_icon = '''more'''
	image = '''<Image>'''


[[module]] #Footer AU Social
path='email_modules/footer/au/social'
color='white'


[[module]] #Footer Disclaimer
path='email_modules/footer/disclaimer'
color='white'

	text='''Disclaimers:<br /><br />
	1. The Low Price Tyre Guarantee offer is available on selected tyres of listed brands that are stocked by participating Ford dealers. Competitor tyres must be new, identical and available from an Australian tyre retailer. Offer includes "4 for 3" or similar competitor offers, but excludes competitor cashback offers, gift cards, "wheel and tyre" bundles, tyres purchased under an instalment payment plan, clearance and liquidation stock and any competitor quotes that cannot be verified. Offer is available until 31st August 2017 at participating Ford dealers to private retail and Blue Business Fleet customers. Includes valid competitor’s quote within 30 days after purchase. Various adjustments, including fitment and freight, apply to ensure a like-for-like price comparison. See your participating Ford dealer for full terms and conditions.'''
    

[[module]] #Footer AU Online
path='email_modules/footer/au/online'
color='white'

+++
