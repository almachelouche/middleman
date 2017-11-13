+++
markets = ["au"]
title = '''AU Prospect 013 Focus_merged'''


[[module]]
path='email_modules/preheaderbefore'

segmentif = ["(user.CustomAttribute['IMD'] == 'P2')"]

	preheader='''The Ford Focus is waiting for you at a nearby dealership!'''

[[module]]
path='email_modules/preheaderbefore'

segmentelse = ["(user.CustomAttribute['IMD'] == 'P1')"]

	preheader='''Click through to see the latest offers on the cutting edge Ford Focus'''

[[module]]
path='email_modules/body'

[[module]]
path='email_modules/preheaderbefore'

segmentif = ["(user.CustomAttribute['IMD'] == 'P2')"]

	preheader='''The Ford Focus is waiting for you at a nearby dealership!'''

[[module]]
path='email_modules/preheaderbefore'

segmentelse = ["(user.CustomAttribute['IMD'] == 'P1')"]

	preheader='''Click through to see the latest offers on the cutting edge Ford Focus'''
    
[[module]] #Header Logo
path='email_modules/header/logo'
color='white'

	image = '''white'''
	url_link = '''https://www.ford.com.au/'''

 [[module]]
path='email_modules/image/banner'
color='white'
segmentif = ["(user.CustomAttribute['IMD'] == 'P2')"]

    image = '''au_edm5_focus1_20161013'''
	url_link='''https://www.ford.com.au/cars/focus/'''
	url_link_name='''p2fiesta'''

	

[[module]] #Banner Image
path='email_modules/image/banner'
color = '''white'''
segmentelse = ["(user.CustomAttribute['IMD'] == 'P1')"]

	image = '''au_edm5_focus1_20161013'''
    url_link='''https://www.ford.com.au/cars/focus/'''
	url_link_name='''p1fiesta'''
   
   
    
[[module]]
path='email_modules/singles/2ctablocksideoutline'
color='''white'''

	cta1_text = '''LATEST OFFER'''
	cta1_url = '''https://www.ford.com.au/cars/focus/'''
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
    With an eye-catching design and award-winning engine technology, the Teched-Up Ford Focus makes it easy. 
    <br/><br/>
    It all begins with a turbocharged, award-winning EcoBoost engine that is as powerful as it is fuel efficient. Top it off with voice-activated SYNC 3 technology that allows you to make calls, take calls and control the interior climate with the sound of your voice, and it’s an impressive package for any driver. 

    <br/><br/>
    Right now, the Ford Focus Trend Hatch with FREE AUTO is available at $24,490* 
    <br/><br/>'''

	cta_direction = '''vertical'''

	cta_1_copy = '''DISCOVER MORE'''
	cta_1_link_url = '''https://www.ford.com/1'''
	cta_1_link_name = '''link_1_name_here'''
	cta_1_icon = ''''''
	cta_1_type = '''block'''
	cta_1_width = '''240'''



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
	copy1 = '''Take your Focus to the next level with <a href="https://www.ford.com.au/cars/focus/accessories/focus-trend-hatch/" name="accessory1" style="text-decoration:underline; color:#2D96CD">Ford Genuine Accessories</a>, designed to seamlessly integrate with your Focus.'''
	image1 = '''au_edm1_everest02_20170629'''
	image1_link_url = '''https://www.ford.com.au/cars/focus/accessories/focus-trend-hatch/'''
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
