+++
markets = ["au"]
title = '''AU Enews 012 0-6 month'''

[[module]]
path='email_modules/preheader'
color='''white'''

	preheader='''Joining the Ford lineup in 2018, Ranger Raptor will be the ultimate performance off-road truck designed to conquer the toughest of all terrains.
    '''

	[[module]] #Header eNews #non NSW
path='email_modules/header/enews'
color='black'

	title = '''Insider'''
	date = '''<date> '''
	copy = '''IN THIS ISSUE:<br /> <module 1>| <module 2> | <module 3> |<module 4>'''

[[module]] #Header Logo
path='email_modules/header/logodesktop'
color='black'

	image = '''black'''
	url_link = '''https://www.ford.com.au/'''

[[module]] # eNews Top Story
path='email_modules/custom/enews_topstory'
color='black'
segmentif = ["(user.CustomAttribute['Model'] == <models name> </models>"]

	title = '''Ranger Raptor is Coming!'''
	copy = '''In 2018, Raptor Ranger is coming to Australia, bringing along with it the newest way to be tough. This ultimate off-road performance truck is already causing quite the buzz. Click below to get exclusive updates on the launch of this ultimate off-road 4x4.
    '''
	cta1_text = '''WATCH THE VIDEO'''
	cta1_url = '''https://www.ford.com.au/commercial/ranger/raptor/?intcmp=bb-fau-vhp-ford%20ranger-fau-vhp-ford%20ranger-return#overlay/content/ford/au/en_au/ranger-content/overlay-videos/raptor-videos/video1.html '''
	cta1_link_name = '''RangerRaptor'''
	cta1_icon = '''<picture>'''


[[module]] #Banner Image	#Ranger &Everest version
path='email_modules/image/banner'
color='white'

segmentif = ["(user.CustomAttribute['Model'] == "]

	image = '''<image>'''
	url_link = '''<link>'''



	[[module]] #Split 01
path='email_modules/split/01'
color='green'

    title = '''Did you know Ford sells tyres?'''
	copy = '''At Ford, we're committed to offering you tyres at competitive prices. That's why we're very excited to announce our Low Price Tyre Guarantee. We'll match a competitor's price on selected tyres we stock.   
    '''
	cta1_text = '''LEARN MORE'''
	cta1_url = '''<link>'''
	cta1_link_name = '''LPTG'''
	cta1_icon = '''<name>'''
	image = '''<image>'''


[[module]] #Split 02
path='email_modules/split/02'
color='lightblue'

	title = '''Engine and Oil Health 101'''
	copy = '''Your car's engine is the most important part of your car. It is the heart of your car, the component that help your car run smoothly. Click below to watch to learn how to keep your engine performing at its best and make sure your engine oil is okay.'''
	cta1_text = '''WATCH NOW'''
	cta1_url = '''https://youtu.be/yM6vCGm-AAQ'''
	cta1_link_name = '''Engine and oil'''
	cta1_icon = '''<icon>'''
	image = '''<image>'''


[[module]] # Owner App Image Right
path='email_modules/custom/ownerapp_imgr'
color='black'

	title = '''Ford Owners App'''
	text1 = '''Want more information, tools, and tips right at your fingertips? Try the Ford Owners App.'''
	text2 = '''<br />&nbsp;&#8226;&nbsp;&nbsp;&nbsp;Streamline service reminders<br />&nbsp;&#8226;&nbsp;&nbsp;&nbsp;Locate a dealer/service centre<br />&nbsp;&#8226;&nbsp;&nbsp;&nbsp;View "how-to" videos<br />'''
	cta1_text = '''iOS'''
	cta1_url = '''https://itunes.apple.com/au/app/ford-owners/id990342351?mt=8'''
	cta1_link_name = '''ios1'''
	cta2_text = '''ANDROID'''
	cta2_url = '''https://play.google.com/store/apps/details?id=com.ford.fordowners&hl=en/'''
	cta2_link_name = '''android1'''
	image = '''owner_app_20160328'''

[[module]] #Footer AU Social
path='email_modules/footer/au/social'
color='white'

[[module]] #Footer AU Online
path='email_modules/footer/au/online'
color='white'
+++

