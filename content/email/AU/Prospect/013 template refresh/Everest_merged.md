+++
markets = ["au"]
title = '''AU Prospect 013 Everest-merged'''


[[module]]
path='email_modules/preheaderbefore'

segmentif = ["(user.CustomAttribute['IMD'] == 'P2')"]

	preheader='''The Ford Everest is waiting for you at a nearby dealership!'''

[[module]]
path='email_modules/preheaderbefore'

segmentelse = ["(user.CustomAttribute['IMD'] == 'P1')"]

	preheader='''Click through to see the latest offers on our most capable SUV, the Ford Everest'''

[[module]]
path='email_modules/body'

[[module]]
path='email_modules/preheaderbefore'

segmentif = ["(user.CustomAttribute['IMD'] == 'P2')"]

	preheader='''The Ford Everest is waiting for you at a nearby dealership!'''

[[module]]
path='email_modules/preheaderbefore'

segmentelse = ["(user.CustomAttribute['IMD'] == 'P1')"]

	preheader='''Click through to see the latest offers on our most capable SUV, the Ford Everest'''

[[module]] #Header Logo
path='email_modules/header/logo'
color='white'

	image = '''white'''
	url_link = '''https://www.ford.com.au/'''

    [[module]]
path='email_modules/image/banner'
color='white'
segmentif = ["(user.CustomAttribute['IMD'] == 'P2')"]

    image = '''au_edm5_everest1_20161013'''
	url_link='''https://www.ford.com.au/suv/everest/'''
	url_link_name='''p2everest'''

	

[[module]] #Banner Image
path='email_modules/image/banner'
color = '''white'''
segmentelse = ["(user.CustomAttribute['IMD'] == 'P1')"]

	image = '''au_edm5_everest1_20161013'''
    url_link='''https://www.ford.com.au/suv/everest/'''
	url_link_name='''p1everest'''
    
    
[[module]]
path='email_modules/singles/2ctablocksideoutline'
color='''white'''

	cta1_text = '''LATEST OFFER'''
	cta1_url = '''https://www.ford.com.au/latest-offer/everest-trend-4wd/'''
	cta1_link_name = ''''''
	cta2_text = '''LOCATE A DEALER'''
	cta2_url = '''http://google.com'''
	cta2_link_name = ''''''

[[module]]
path='email_modules/cover/master'
color='''white'''

	icon=''''''
	title=''''''
	copy='''Hi <%${user.CustomAttribute['FullName']}%>
    <br/><br/>
    Push yourself to the limit with the bold new Ford Everest 4WD, and love every minute of it. 
    <br/><br/>
    In addition to the Terrain Management System which makes light work of any terrain, Everest also delivers the smart tech and capabilities you need for better on-road driving. Enjoy an unbeatable 3,000kg towing capability and a suite of driver assist technologies, including Lane Keeping System and Adaptive Cruise Control. 
    <br/><br/>
    Right now, the Ford Everest Trend 4WD is available at $59,990* Driveaway.
    <br/><br/>''

	cta_direction = '''vertical'''

	cta_1_copy = '''DISCOVER MORE'''
	cta_1_link_url = '''https://www.ford.com/1'''
	cta_1_link_name = '''link_1_name_here'''
	cta_1_icon = ''''''
	cta_1_type = '''block'''
	cta_1_width = '''240'''

+++
[[module]] #Banner Image
path='email_modules/image/banner'
color='white'

	image='''au_edm2_svc_new_banner_20170926'''
	url_link='''https://www.ford.com.au/owners/service/'''
	url_link_name="servicebanner"

[[module]]
path='email_modules/spacer/platinum_20'
color='white'

	height="20"

[[module]]
path='email_modules/dual/05'
color='white'

	title1 = '''Ford Owners App'''
	text_box_height = '''310'''
	copy1 = '''Download the <a href="https://www.ford.com.au/owners/vehicle-support/app-download/" name="accessory1" style="text-decoration:underline; color:#2D96CD">Ford Owners App</a> for instant access to “how-to” videos, roadside assistance information, service reminders, vehicle owner manuals, and more.'''
	cta1a_text = '''Download App Now'''
	cta1a_url = '''https://www.ford.com.au/owners/vehicle-support/app-download/'''
	cta1a_link_name = '''link_name_here'''
	image1 = '''au_edm1_owner-app2_20170629'''
	image1_link_url = '''https://www.ford.com.au/owners/vehicle-support/app-download/'''
	image1_link_name = '''link_name_here'''
	title2 = '''Get Accessorised'''
	copy2 = '''Whether you need a nudge bar, or a tow pack for your weekend adventure, only <a href="https://www.ford.com.au/suv/everest/smart-accessories/" name="accessory1" style="text-decoration:underline; color:#2D96CD">Ford Genuine Accessories</a> perfectly integrate with your Everest.'''
	cta2a_text = '''Discover Accessories'''
	cta2a_url = '''https://www.ford.com.au/suv/everest/smart-accessories/'''
	cta2a_link_name = '''link_name_here'''
	image2 = '''au_edm1_everest02_20170629'''
	image2_link_url = '''https://www.ford.com.au/suv/everest/smart-accessories/'''
	image2_link_name = '''link_name_here'''

[[module]]
path='email_modules/spacer/platinum_20'
color='white'

	height="20"

[[module]]
path='email_modules/dual/05'
color='white'

	title1 = '''SYNC® Support'''
	text_box_height = '''310'''
	copy1 = '''Learn how to set up Emergency Assistance, familiarise yourself with common voice commands and more on the SYNC® Support Portal.'''
	cta1a_text = '''Become a SYNC® Expert'''
	cta1a_url = '''https://www.ford.com.au/owners/technology/sync-support/sync1/'''
	cta1a_link_name = '''link_name_here'''
	image1 = '''au_edm1_support_20170629'''
	image1_link_url = '''https://www.ford.com.au/owners/technology/sync-support/sync1/'''
	image1_link_name = '''link_name_here'''
	title2 = '''Ford Service'''
	copy2 = '''Enjoy the convenience of a Free Loan Car² when you book your next scheduled service. That's what service should be.'''
	cta2a_text = '''Find Out More'''
	cta2a_url = '''https://www.ford.com.au/owners/service/'''
	cta2a_link_name = '''link_name_here'''
	image2 = '''au_edm1_service_20170629'''
	image2_link_url = '''https://www.ford.com.au/owners/service/'''
	image2_link_name = '''link_name_here'''


[[module]] #Footer AU Social
path='email_modules/footer/au/social'
color='white'

[[module]] #Footer Disclaimer
path='email_modules/footer/disclaimer'
color='white'

	text = ''''''
[[module]] #Footer AU Online
path='email_modules/footer/au/online'
color='white'
+++
