+++
markets = ["au"]
title = '''AU Prospect 011 Focus_merged'''

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

[[module]] #Banner Image
path = '''email_modules/image/banner_nolink'''
color = '''white'''
segmentif = ["(user.CustomAttribute['IMD'] == 'P2')"]

	image = '''au_edm5_focus1_20161013'''

[[module]] #Banner Image
path = '''email_modules/image/banner_nolink'''
color = '''white'''
segmentelse = ["(user.CustomAttribute['IMD'] == 'P1')"]

	image = '''au_edm5_focus1_20161013'''

[[module]]
path='email_modules/cover/02'
color='''white'''
segmentif = ["(user.CustomAttribute['IMD'] == 'P2')"]

		title='''You can't deny the power of attraction.'''
		copy=''''''
		cta1_text='''BOOK A TEST DRIVE'''
		cta1_url='''https://www.ford.com.au/#overlay/content/ford/au/en_au/site-wide-content/overlays/forms/test-drive.html/'''
		cta1_link_name = '''test1'''
		cta2_text='''LATEST OFFER'''
		cta2_url='''https://www.ford.com.au/latest-offer/focus-trend-hatch/'''
		cta2_link_name = '''latestoffer1'''

[[module]]
path='email_modules/cover/02'
color='''white'''
segmentelse = ["(user.CustomAttribute['IMD'] == 'P1')"]

		title='''The Ford Focus Trend has been named the Drive small car of 2016!'''
		copy=''''''
		cta1_text='''LATEST OFFER'''
		cta1_url='''https://www.ford.com.au/latest-offer/focus-trend-hatch/'''
		cta1_link_name = '''latestoffer1'''
		cta2_text='''BOOK A TEST DRIVE'''
		cta2_url='''https://www.ford.com.au/#overlay/content/ford/au/en_au/site-wide-content/overlays/forms/test-drive.html/'''
		cta2_link_name = '''test1'''

[[module]] #Cover 11
path='email_modules/cover/03'
color='''slatescreen'''
segmentif = ["(user.CustomAttribute['IMD'] == 'P2')"]

	copy='''<br />Hi <%${user.CustomAttribute['FullName']}%>,<br /><br />
	Athletic and toned, the Ford Focus is a distinctive presence wherever it goes. And once you get behind the wheel, you'll be hooked for life. </span><br /><br /><span style="font-size:16px; color:#FFFFFF; font-family:Arial, Helvetica, sans-serif ;">Right now, the Ford Focus Trend Hatch Auto is available at $24,490* Driveaway</span>'''

[[module]] #Cover 11
path='email_modules/cover/03'
color='''slatescreen'''
segmentelse = ["(user.CustomAttribute['IMD'] == 'P1')"]

	copy='''<br />Hi <%${user.CustomAttribute['FullName']}%>,	<br /><br />
	Combining innovative technology, with a sleek and sporty design, the Ford Focus is the car built for pleasure seekers.</span><br /><br /><span style="font-size:16px; color:#FFFFFF; font-family:Arial, Helvetica, sans-serif ;">Right now, the Ford Focus Trend Hatch Auto is available at $24,490* Driveaway</span>'''

	[[module]] #Banner Image
path = '''email_modules/image/banner_nolink'''
color = '''white'''

	image = '''au_edm5_focus2_20161013'''

		[[module]] #Banner Image
path = '''email_modules/image/banner_nolink'''
color = '''white'''

	image = '''au_edm5_focus_trend_award_20161215'''


[[module]] #Custom 4 Icons
path='email_modules/custom/4icons'
color='white'

	title = '''Featuring:'''
	icon1_url='''https://www.india.ford.com/locate-dealer/'''
	icon1_link_name = '''locate_dealer'''
	icon1_image='''au_edm5_ecoboost_20161013'''
	icon1_text = '''Eco Boost Engine'''

	icon2_url='''tel:18004252500'''
	icon2_link_name = '''locate_dealer2'''
	icon2_image='''au_edm5_nav_20161013'''
	icon2_text = '''Sat Nav System'''

	icon3_url='''tel:18002097400'''
	icon3_link_name = '''locate_dealer3'''
	icon3_image='''au_edm5_sync2_20161107'''
	icon3_text = '''Ford SYNC® Connectivity System&#185;'''

	icon4_url='''https://partscalculator.fordind.com:1443/Fill_Field/'''
	icon4_link_name = '''locate_dealer4'''
	icon4_image='''au_edm5_park_20161013'''
	icon4_text = '''Rear Parking Sensors'''

[[module]] #Cover 13
path='email_modules/cover/04'
color='white'
segmentif = ["(user.CustomAttribute['IMD'] == 'P2')"]

	title = '''Cover 13'''
	copy = '''<br />The Ford Focus has it all. And it's available now.'''
	cta1_url = '''https://www.ford.com.au/cars/focus/'''
	cta1_text = '''FIND OUT MORE'''
	cta1_icon = '''more'''
	cta1_link_name = '''moreinfo'''

[[module]] #Cover 13
path='email_modules/cover/04'
color='white'
segmentelse = ["(user.CustomAttribute['IMD'] == 'P1')"]

title = '''Cover 13'''
	copy = '''<br />All this and more is available to you now in the Ford Focus Trend Hatch Auto.'''
	cta1_url = '''https://www.ford.com.au/cars/focus/'''
	cta1_text = '''FIND OUT MORE'''
	cta1_icon = '''more'''
	cta1_link_name = '''moreinfo'''

[[module]] #Banner Image
path='email_modules/image/banner'
color='white'

	image='''au_edm2_svc_new_banner_20170926'''
	url_link='''https://www.ford.com.au/owners/service/'''
	url_link_name="servicebanner"

[[module]] #Cover 07
path='email_modules/cover/02'
color='''white'''
segmentif = ["(user.CustomAttribute['IMD'] == 'P2')"]

	title='''The service you'll love, guaranteed'''
	copy='''We know that a new car is a big decision <%${user.CustomAttribute['FullName']}%>, so our job isn't done once you pick up your car.<br /><br />
	With <a href="https://www.ford.com.au/owners/service/calculator?edm" name="calculator" style="text-decoration:underline; color:#2d96cd">Ford's Service Price Promise</a>&#178;, you'll know what you're going to pay for a standard service before you go in. But the service doesn't stop there. You can get State Auto Club Roadside Assistance and Membership&#179; for up to 7 years from Autoclub participating dealers. Ford also has a Free Loan Car program&#8308;, so we can keep you on the road whilst your car is being serviced. After all, that's what service should be.<br /><br />
	So don't wait. Book a test drive to experience the Ford Focus Trend Hatch Auto today.'''
	cta1_text='''BOOK A TEST DRIVE'''
	cta1_url='''https://www.ford.com.au/#overlay/content/ford/au/en_au/site-wide-content/overlays/forms/test-drive.html/'''
	cta1_link_name = '''TEST'''

[[module]] #Cover 07
path='email_modules/cover/02'
color='''white'''
segmentelse = ["(user.CustomAttribute['IMD'] == 'P1')"]

	title='''The service you'll love, guaranteed'''
	copy='''We know that a new car is a big decision <%${user.CustomAttribute['FullName']}%>, so our job isn't done once you pick up your car.<br /><br />
	With <a href="https://www.ford.com.au/owners/service/calculator?edm" name="calculator" style="text-decoration:underline; color:#2d96cd">Ford's Service Price Promise</a>&#178;, you'll know what you're going to pay for a standard service before you go in. But the service doesn't stop there. You can get State Auto Club Roadside Assistance and Membership&#179; for up to 7 years from Autoclub participating dealers. Ford also has a Free Loan Car program&#8308;, so we can keep you on the road whilst your car is being serviced. After all, that's what service should be.<br /><br />
	So don't wait. Check out the latest offers on the Ford Focus Trend Hatch Auto today.'''
	cta1_text='''LATEST OFFER'''
	cta1_url='''https://www.ford.com.au/latest-offer/focus-trend-hatch/'''
	cta1_link_name = '''moreinfo2'''


[[module]] #Footer AU Social
path='email_modules/footer/au/social'
color='white'

[[module]] #Footer Disclaimer
path='email_modules/footer/disclaimer'
color='white'

    text = '''* Recommended driveaway price for 2017 plate models at participating Dealers. Private and Blue, Silver and Gold Business Fleet customers only. Ford reserves the right to further reduce recommended price, or otherwise change or extend offer.<br /><br />
	1. For SYNC® compatibility visit <a href="https://www.ford.com.au/technology/sync/" name="sync" style="text-decoration:underline; color:#91a4b1">www.ford.com.au/technology/sync</a>.<br /><br />
	2. Available at participating Ford Dealers on vehicles built from 2007. Customers will pay equal to or less than the maximum price as published by Ford for the period of the web quote for standard items in the A and B logbook service together with selected routine maintenance items. See <a href="https://www.ford.com.au/owners/service/t-and-c/" name="term1" style="text-decoration:underline; color:#91a4b1">www.ford.com.au/owners/service/t-and-c</a> for full terms.<br /><br />
	3. Available to Private and Blue Business Fleet customers who have not reached earlier of 7 years or 105,000km, only at participating Dealers. State Auto Club Roadside Assistance & Membership is included for 12 months or until your next eligible standard service (whichever occurs first).  Standard services include all A and B logbook services. Customers must comply with scheduled servicing intervals to maintain continuity of membership. See  <a href="www.ford.com.au/owners/service/t-and-c" name="term2" style="text-decoration:underline; color:#91a4b1">www.ford.com.au/owners/service/t-and-c</a> for full terms. <br /><br />
	4. Available at participating dealers on scheduled services or overnight warranty repairs. Private and Blue, Silver and Gold Business Fleet customers only. Booking may be required. See <a href="https://www.ford.com.au/owners/service/t-and-c/" name="term3" style="text-decoration:underline; color:#91a4b1">www.ford.com.au/owners/service/t-and-c</a> for full terms.<br /><br />'''

[[module]] #Footer AU Online
path='email_modules/footer/au/online'
color='white'
+++
