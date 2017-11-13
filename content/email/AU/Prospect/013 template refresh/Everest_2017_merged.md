+++
markets = ["au"]
title = '''AU Prospect 013 Everest-merged'''
draft = true

[[module]]
path='email_modules/preheaderbefore'

	preheader='''Click through to see the latest offers on our most capable SUV, the Ford Everest'''

[[module]]
path='email_modules/body'

[[module]]
path='email_modules/preheaderbefore'

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
path='email_modules/singles/copy'
color='''white'''
segmentif = ["(user.CustomAttribute['IMD'] == 'P2')"]
	copy = '''<br />Hi <%${user.CustomAttribute['FullName']}%>, <br /><br />Ever wondered what's beyond the horizon? It's time to explore it all with the new Ford Everest. Sand, snow, desert or bush - nothing gets in the way of this powerful performer. <br /><br /><span style="color:#FFFFFF">Right now, the Ford Everest Trend 4WD is available at $59,990* Driveaway.</span>'''

[[module]]
path='email_modules/singles/copy'
color='''white'''
segmentelse = ["(user.CustomAttribute['IMD'] == 'P1')"]
	copy = '''<br />Hi <%${user.CustomAttribute['FullName']}%>, <br /><br />Ever wondered what's beyond the horizon? It's time to explore it all with the new Ford Everest. Sand, snow, desert or bush - nothing gets in the way of this powerful performer. <br /><br /><span style="color:#FFFFFF">Right now, the Ford Everest Trend 4WD is available at $59,990* Driveaway.</span>'''


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

    title1 = '''Get Accessorised'''
    text_box_height = '''310'''
	copy1 = '''Whether you need a nudge bar, or a tow pack for your weekend adventure, only <a href="https://www.ford.com.au/suv/everest/smart-accessories/" name="accessory1" style="text-decoration:underline; color:#2D96CD">Ford Genuine Accessories</a> perfectly integrate with your Everest.'''
	image1 = '''au_edm1_everest02_20170629'''
	image1_link_url = '''https://www.ford.com.au/suv/everest/smart-accessories/'''
	image1_link_name = '''link_name_here'''
	title2 = '''Have you seen the Ford Ranger?'''
	copy2 = '''With its winning combination of brute strength and innovative technology. There's no stopping the Ranger from getting the job done.'''
	image2 = '''au_edm1_owner-app2_20170629'''
	image2_link_url = '''https://www.ford.com.au/owners/vehicle-support/app-download/'''
	image2_link_name = '''link_name_here'''
	

[[module]]
path='email_modules/spacer/platinum_20'
color='white'

	height="20"

[[module]]
path='email_modules/dual/05'
color='white'

	title1 = '''Free Loan Car&#185;'''
	copy1 = '''Life shouldn't stop when you service your vehicle. That's why we offer a <a href="https://www.ford.com.au/owners/service/" name="freeloan" style="text-decoration:underline; color:#2D96CD">Free Loan Car&#185</a>  when you book a scheduled service.'''
	image1 = '''au_edm2_free_loan_car_20170818'''
	image1_link_url = '''https://www.ford.com.au/owners/service/'''
	image1_link_name = '''Some'''
	title2 = '''Insurance & Warranties'''
	copy2 = '''Ford Dealerships are your one-stop shop for insurance, warranties and finance. Drive home with peace of mind knowing you’re covered from day one.'''
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
