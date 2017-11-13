+++
markets = ["au"]
title = '''AU Prospect 013 EcoSport-Merged'''

[[module]]
path='email_modules/preheaderbefore'

segmentif = ["(user.CustomAttribute['IMD'] == 'P2')"]

	preheader='''The Ford EcoSport is waiting for you at a nearby dealership!'''


[[module]]
path='email_modules/preheaderbefore'

segmentelse = ["(user.CustomAttribute['IMD'] == 'P1')"]

	preheader='''Click through to see the latest offers on the Ford EcoSport the city-sized SUV'''

[[module]]
path='email_modules/body'

[[module]]
path='email_modules/preheaderbefore'

segmentif = ["(user.CustomAttribute['IMD'] == 'P2')"]

	preheader='''The Ford EcoSport is waiting for you at a nearby dealership!'''

[[module]]
path='email_modules/preheaderbefore'

segmentelse = ["(user.CustomAttribute['IMD'] == 'P1')"]

	preheader='''Click through to see the latest offers on the Ford EcoSport the city-sized SUV'''


[[module]] #Header Logo
path='email_modules/header/logo'
color='white'

	image = '''white'''
	url_link = '''https://www.ford.com.au/'''

  
  [[module]]
path='email_modules/image/banner'
color='white'
segmentif = ["(user.CustomAttribute['IMD'] == 'P2')"]

    image = '''au_edm5_ecosport2_20161013'''
	url_link='''https://www.ford.com.au/suv/ecosport/'''
	url_link_name='''p2ecospott''' 

[[module]]
path='email_modules/image/banner'
color='white'
segmentelse = ["(user.CustomAttribute['IMD'] == 'P1')"]

    image = '''au_edm5_ecosport1_20161013'''
	url_link='''https://www.ford.com.au/suv/ecosport/'''
	url_link_name='''p1ecospott''' 

[[module]]
path='email_modules/singles/2ctablocksideoutline'
color='''white'''

	cta1_text = '''LATEST OFFER'''
	cta1_url = '''https://www.ford.com.au/latest-offer/ecosport-ambiente/'''
	cta1_link_name = ''''''
	cta2_text = '''EVEREST FEATURES'''
	cta2_url = '''http://google.com'''
	cta2_link_name = ''''''

[[module]]
path='email_modules/singles/copy'
color='''white'''

	copy = '''Hi <%${user.CustomAttribute['FullName']}%>
    <br/><br/>
    Take on any urban challenge with the city-sized Ford EcoSport SUV.
    <br/><br/>
    EcoSport delivers tonnes of space – to the tune of 705 litres of flexible cargo space, fold-down 60:40 seats, and 20 smart storage compartments. Plus, the voice-activated SYNC system lets you stay connect to your world and favourite apps, while your hands stay safely on the steering wheel. 
    <br/><br/>
    <br /><br /><span style="color:#000000">Right now, the Ford EcoSport Ambiente Manual is available $18,990* Driveaway.</span>
    '''

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


