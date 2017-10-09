+++
markets = ["ph"]
title = '''PH Ford Ranger Raptor All'''

[[module]]
path='email_modules/preheader'
color='''white'''

preheader = '''Are you ready for the ultimate off-roader?'''

[[module]] #Header Logo
path='email_modules/header/logo'
color='white'

	image = '''white'''
	url_link = '''https://www.ford.com.ph/'''

[[module]] #Banner Image
path='email_modules/image/banner'
color='white'

	image = '''AU_edm6_raptor_20170920'''
		url_link='''https://www.ford.com.ph/trucks/ranger/raptor/?intcmp=hp-new-brand-gallery#overlay/content/ford/ph/en_ph/ranger-content/video-overlays/raptor-videos/video1.html'''
	url_link_name='''raptor'''

[[module]]
path='email_modules/spacer/default'
color='white'

	height="30"
    
[[module]]
path='email_modules/singles/copy'
color='''white'''

	copy = '''Hello <%${user['FirstName']}%>'''
    
[[module]]
path='email_modules/spacer/default'
color='white'

	height="30"
    
[[module]]
path='email_modules/singles/title'
color='''white'''

	title = '''Are you ready for the ultimate off-roader?'''

[[module]]
path='email_modules/spacer/default'
color='white'

	height="30"

[[module]]
path='email_modules/singles/copy'
color='''white'''

	copy = '''The world of off-road driving is about to get a little wild. The ultimate off-road performance truck, Ranger Raptor is almost ready for release. Sure, we know you love your <%${user.CustomAttribute['Model']}%>, but we thought you should see this.<br /><br />Click the link below to get a sneak peek at the prototype in action.'''
    
[[module]]
path='email_modules/spacer/default'
color='white'

	height="30"
    
[[module]]
path='email_modules/singles/ctablock'
color='''white'''

	cta1_text = '''See the Prototype Testing'''
	cta1_url = '''https://www.ford.com.ph/trucks/ranger/raptor/?intcmp=hp-new-brand-gallery#overlay/content/ford/ph/en_ph/ranger-content/video-overlays/raptor-videos/video1.html'''
	cta1_link_name = '''raptor'''

[[module]] #PH Social
path = 'email_modules/footer/ph/social'
color = 'white'

[[module]] #PH Online
path = 'email_modules/footer/ph/online'
color = 'white'
+++