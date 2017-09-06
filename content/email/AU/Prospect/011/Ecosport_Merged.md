+++
markets = ["au"]
title = '''AU Prospect 011 EcoSport-Merged'''

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

[[module]] #Banner Image
path = '''email_modules/image/banner_nolink'''
color = '''white'''
segmentif = ["(user.CustomAttribute['IMD'] == 'P2')"]

	image = '''au_edm5_ecosport2_20161013'''

[[module]] #Banner Image
path = '''email_modules/image/banner_nolink'''
color = '''white'''
segmentelse = ["(user.CustomAttribute['IMD'] == 'P1')"]

	image = '''au_edm5_ecosport1_20161013'''

[[module]]
path='email_modules/cover/02'
color='''white'''
segmentif = ["(user.CustomAttribute['IMD'] == 'P2')"]

		title='''The SUV built for the city.'''
		copy=''''''
		cta1_text='''BOOK A TEST DRIVE'''
		cta1_url='''https://www.ford.com.au/#overlay/content/ford/au/en_au/site-wide-content/overlays/forms/test-drive.html/'''
		cta1_link_name = '''test1'''
		cta2_text='''LATEST OFFER'''
		cta2_url='''https://www.ford.com.au/latest-offer/ecosport-ambiente/'''
		cta2_link_name = '''latestoffer1'''

[[module]]
path='email_modules/cover/02'
color='''white'''
segmentelse = ["(user.CustomAttribute['IMD'] == 'P1')"]

	title='''See more of your city.'''
	copy=''''''
	cta1_text='''LATEST OFFER'''
	cta1_url='''https://www.ford.com.au/latest-offer/ecosport-ambiente/'''
	cta1_link_name = '''latestoffer1'''
	cta2_text='''BOOK A TEST DRIVE'''
	cta2_url='''https://www.ford.com.au/#overlay/content/ford/au/en_au/site-wide-content/overlays/forms/test-drive.html/'''
	cta2_link_name = '''test1'''

[[module]] #Cover 11
path='email_modules/cover/03'
color='''slatescreen'''
segmentif = ["(user.CustomAttribute['IMD'] == 'P2')"]

	copy='''<br />Hi <%${user.CustomAttribute['FullName']}%>, <br /><br />The rhythm of the metropolis pumps through every fibre of the Ford EcoSport. Combining sleek design with advanced technology, this SUV is the hottest ticket in town. <br /><br /><span style="color:#FFFFFF">Right now, the Ford EcoSport Ambiente Manual is available at $19,990* Driveaway.</span>'''

[[module]] #Cover 11
path='email_modules/cover/03'
color='''slatescreen'''
segmentelse = ["(user.CustomAttribute['IMD'] == 'P1')"]

	copy='''<br />Hi <%${user.CustomAttribute['FullName']}%>, <br /><br />Built for urban discoveries, this smart SUV makes city driving a breeze. So if you live for hustle, bustle and bright lights, the Ford EcoSport is the perfect match for you. <br /><br /><span style="color:#FFFFFF">Right now, the Ford EcoSport Ambiente Manual is available at $19,990* Driveaway.</span>'''


[[module]] #Banner Image
path = '''email_modules/image/banner_nolink'''
color = '''white'''

	image = '''au_edm5_ecosport3_20161013'''

[[module]] #Custom 4 Icons
path='email_modules/custom/4icons'
color='white'

	title = '''Featuring:'''
	icon1_url='''http://www.india.ford.com/locate-dealer'''
	icon1_link_name = '''locate_dealer'''
	icon1_image='''au_edm5_sync2_20161107'''
	icon1_text = '''Ford SYNC® connectivity system¹'''
	icon2_url='''tel:18004252500'''
	icon2_link_name = '''locate_dealer2'''
	icon2_image='''au_edm5_voicecontrol_20161013'''
	icon2_text = '''Bluetooth® with Voice Control²'''
	icon3_url='''tel:18002097400'''
	icon3_link_name = '''locate_dealer3'''
	icon3_image='''au_edm5_ipodusb_20161013'''
	icon3_text = '''iPod and USB integration³'''
	icon4_url='''https://partscalculator.fordind.com:1443/Fill_Field'''
	icon4_link_name = '''locate_dealer4'''
	icon4_image='''au_edm5_airbags_20161013'''
	icon4_text = '''7 Airbags'''

[[module]] #Cover 13
path='email_modules/cover/04'
color='white'

	title = '''Cover 13'''
	copy = '''<br />All this and more is available to you now in the Ford EcoSport Ambiente Manual.'''
	cta1_url = '''https://www.ford.com.au/suv/ecosport/'''
	cta1_text = '''FIND OUT MORE'''
	cta1_icon = '''more'''
	cta1_link_name = '''moreinfo'''

[[module]] #Banner Image
path='email_modules/image/banner'
color='white'

	image='''au_edm5_prospect_new_banner_20170905'''
	url_link='''https://www.ford.com.au/owners/service/'''
	url_link_name="servicebanner"

[[module]] #Cover 07
path='email_modules/cover/02'
color='''white'''
segmentif = ["(user.CustomAttribute['IMD'] == 'P2')"]

	title='''The service you'll love, guaranteed'''
	copy='''We know that a new car is a big decision <%${user.CustomAttribute['FullName']}%>, so our job isn't done once you pick up your car.<br /><br />With <a href="https://www.ford.com.au/owners/service/calculator?edm" name="calculator1" style="text-decoration:underline; color:#2d96cd">Ford's Service Price Promise</a>&#8308;, you'll know what you're going to pay for a standard service before you go in. But the service doesn't stop there. You can get State Auto Club Roadside Assistance and Membership&#8309; for up to 7 years from Autoclub participating dealers. Ford also has a Free Loan Car program&#8310;, so we can keep you on the road whilst your car is being serviced. After all, that's what service should be.<br /><br />So don't wait. Book a test drive to experience the Ford EcoSport Ambiente Manual today.'''
	cta1_text='''BOOK A TEST DRIVE'''
	cta1_url='''https://www.ford.com.au/#overlay/content/ford/au/en_au/site-wide-content/overlays/forms/test-drive.html/'''
	cta1_link_name = '''testdrive1'''

[[module]] #Cover 07
path='email_modules/cover/02'
color='''white'''
segmentelse = ["(user.CustomAttribute['IMD'] == 'P1')"]

	title='''The service you'll love, guaranteed'''
	copy='''We know that a new car is a big decision <%${user.CustomAttribute['FullName']}%>, so our job isn't done once you pick up your car.<br /><br />With <a href="https://www.ford.com.au/owners/service/calculator?edm" name="calculator1" style="text-decoration:underline; color:#2d96cd">Ford's Service Price Promise</a>&#8308;, you'll know what you're going to pay for a standard service before you go in. But the service doesn't stop there. You can get State Auto Club Roadside Assistance and Membership&#8309; for up to 7 years from Autoclub participating dealers. Ford also has a Free Loan Car program&#8310;, so we can keep you on the road whilst your car is being serviced. After all, that's what service should be.<br /><br />So don't wait. Check out the latest offers on Ford EcoSport Ambiente Manual here.'''
	cta1_text='''LATEST OFFER'''
	cta1_url='''https://www.ford.com.au/latest-offer/ecosport-ambiente/'''
	cta1_link_name = '''latest_offer1'''

[[module]] #Footer AU Social
path='email_modules/footer/au/social'
color='white'

[[module]] #Footer Disclaimer
path='email_modules/footer/disclaimer'
color='white'

	text = '''Terms & Conditions
				<br /> <br />*Recommended driveaway price for 2017 plate models at participating Dealers. Private and Blue, Silver and Gold Business Fleet customers only. Ford reserves the right to further reduce recommended price, or otherwise change or extend offer.<br /><br />
				1. For SYNC® compatibility visit <a href="https://www.ford.com.au/technology/sync/"	name="sync1" style="text-decoration:underline; color:#91a4b1">www.ford.com.au/technology/sync</a>.<br /><br />
				2. Bluetooth® is a registered trademark of Bluetooth SIG Inc., and is used under licence. Some phones not compatible.<br /><br />
				3. iPod is a trademark of Apple Inc. Requires connection cable, sold separately. Please refer to <a href="https://www.ford.com.au/" name="ford1" style="text-decoration:underline; color:#91a4b1">ford.com.au</a> for compatibility.<br /><br />
				4. Available at participating Ford Dealers on vehicles built from 2007. Customers will pay equal to or less than the maximum price as published by Ford for the period of the web quote for standard items in the A and B logbook service together with selected routine maintenance items. See <a href="https://www.ford.com.au/owners/service/t-and-c/" name="term1" style="text-decoration:underline; color:#91a4b1">www.ford.com.au/owners/service/t-and-c</a> for full terms. <br /><br />
				5. Available to Private and Blue Business Fleet customers who have not reached earlier of 7 years or 105,000km, only at participating Dealers. State Auto Club Roadside Assistance & Membership is included for 12 months or until your next eligible standard service (whichever occurs first). Standard services include all A and B logbook services. Customers must comply with scheduled servicing intervals to maintain continuity of membership. See  <a href="www.ford.com.au/owners/service/t-and-c" name="term2" style="text-decoration:underline; color:#91a4b1">www.ford.com.au/owners/service/t-and-c</a> for full terms. <br /><br />
				6. Available at participating dealers on scheduled services or overnight warranty repairs. Private and Blue, Silver and Gold Business Fleet customers only. Booking may be required. See <a href="https://www.ford.com.au/owners/service/t-and-c/" name="term3"	style="text-decoration:underline; color:#91a4b1">www.ford.com.au/owners/service/t-and-c</a> for full terms.'''

[[module]] #Footer AU Online
path='email_modules/footer/au/online'
color='white'
+++
