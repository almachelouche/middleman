+++
markets = ["au"]
title = '''AU Prospect 012 Ranger_merged'''


[[module]]
path='email_modules/preheaderbefore'

segmentif = ["(user.CustomAttribute['IMD'] == 'P2')"]

	preheader='''The Ford Ranger is waiting for you at a nearby dealership!'''

[[module]]
path='email_modules/preheaderbefore'

segmentelse = ["(user.CustomAttribute['IMD'] == 'P1')"]

	preheader='''Click through to see the latest offers on the tough and smart Ranger'''

[[module]]
path='email_modules/body'


[[module]] #Header Logo
path='email_modules/header/logo'
color='white'

	image = '''white'''
	url_link = '''https://www.ford.com.au/'''

[[module]] #Banner Image No Link
path = '''email_modules/image/banner_nolink'''
color = '''white'''
segmentif = ["(user.CustomAttribute['IMD'] == 'P2')"]

	image = '''au_edm5_ranger2_20161013'''

[[module]] #Banner Image No Link
path = '''email_modules/image/banner_nolink'''
color = '''white'''
segmentelse = ["(user.CustomAttribute['IMD'] == 'P1')"]

	image = '''au_edm5_ranger1_20161013'''

[[module]]
path='email_modules/cover/02'
color='''white'''
segmentif = ["(user.CustomAttribute['IMD'] == 'P2')"]

		title='''Stick with the winners.'''
		copy=''''''
		cta1_text='''BOOK A TEST DRIVE'''
		cta1_url='''https://www.ford.com.au/#overlay/content/ford/au/en_au/site-wide-content/overlays/forms/test-drive.html/'''
		cta1_link_name = '''test1'''
		cta2_text='''LATEST OFFER'''
		cta2_url='''https://www.ford.com.au/latest-offer/4x4-xlt-double-cab-pick-up-3-2l-diesel/'''
		cta2_link_name = '''latestoffer1'''

[[module]]
path='email_modules/cover/02'
color='''white'''
segmentelse = ["(user.CustomAttribute['IMD'] == 'P1')"]

		title='''Taking you above and beyond.'''
		copy=''''''
		cta1_text='''LATEST OFFER'''
		cta1_url='''https://www.ford.com.au/latest-offer/4x4-xlt-double-cab-pick-up-3-2l-diesel/'''
		cta1_link_name = '''latestoffer1'''
		cta2_text='''BOOK A TEST DRIVE'''
		cta2_url='''https://www.ford.com.au/#overlay/content/ford/au/en_au/site-wide-content/overlays/forms/test-drive.html/'''
		cta2_link_name = '''test1'''

[[module]] #Cover 11
path='email_modules/cover/03'
color='''slatescreen'''
segmentif = ["(user.CustomAttribute['IMD'] == 'P2')"]

	copy='''<br />Hi <%${user.CustomAttribute['FullName']}%>, <br /><br />Plenty of trucks can boast brute strength. But it's the technology behind the muscle that makes the Ford Ranger a real hero. <br /><br /><span style="color:#FFFFFF">Right now, the Ford Ranger 4x4 XLT Double Cab Pick-up 3.2L Diesel with FREE AUTO is available at $55,490* Driveaway.</span>'''

[[module]] #Cover 11
path='email_modules/cover/03'
color='''slatescreen'''
segmentelse = ["(user.CustomAttribute['IMD'] == 'P1')"]

	copy='''<br />Hi <%${user.CustomAttribute['FullName']}%>, <br /><br />The Ford Ranger has been tested to the limits to give you a truck that's in its element wherever you are. So when the going gets tough, the tough can get going.<br /><br /><span style="color:#FFFFFF">Right now, the Ford Ranger 4x4 XLT Double Cab Pick-up 3.2L Diesel with FREE AUTO is available at $55,490* Driveaway.</span>'''

[[module]] #Banner Image No Link
path = '''email_modules/image/banner_nolink'''
color = '''white'''
	image = '''au_edm5_ranger3_20161013'''



[[module]] #Custom 4 Icons
path='email_modules/custom/4icons'
color='white'

	title = '''Featuring:'''
	icon1_url='''http://www.india.ford.com/locate-dealer'''
	icon1_link_name = '''locate_dealer'''
	icon1_image='''au_edm5_engine_20161013'''
	icon1_text = '''3.2 TDCi Diesel'''
	icon2_url='''tel:18004252500'''
	icon2_link_name = '''locate_dealer2'''
	icon2_image='''au_edm5_towing_20161013'''
	icon2_text = '''Towing Capacity of 3,500kg¹'''
	icon3_url='''tel:18002097400'''
	icon3_link_name = '''locate_dealer3'''
	icon3_image='''au_edm5_voicecontrol_20161013'''
	icon3_text = '''Bluetooth® with Voice Control³'''
	icon4_url='''https://partscalculator.fordind.com:1443/Fill_Field'''
	icon4_link_name = '''parts_calculator'''
	icon4_image='''au_edm5_waterwanding_20161013'''
	icon4_text = '''800mm Water Wading²'''

[[module]] #Cover 13
path='email_modules/cover/04'
color='white'

	title = '''Cover 13'''
	copy = ''''''
	cta1_url = '''https://www.ford.com.au/commercial/ranger/'''
	cta1_text = '''FIND OUT MORE'''
	cta1_icon = '''more'''
	cta1_link_name = '''more1'''

[[module]]
path='email_modules/cover/01'
color='''black'''
segmentif = ["(user.CustomAttribute['IMD'] == 'P2')"]

	title='''The Science of Truck'''
	copy='''<span style="color:#FFFFFF">See how we put the smart Ranger to the test in these larger-than-life torture trials built to bring out the tough in this truck.</span>'''

[[module]] #2 Images
path = '''email_modules/image/2images'''
color = '''white'''
segmentif = ["(user.CustomAttribute['IMD'] == 'P2')"]

	image1 = '''au_edm5_ranger2_20161107'''
	image1_url = '''https://www.ford.com.au/commercial/ranger/science-of-truck/#overlay/content/ford/au/en_au/ranger-content/overlay-videos/the-science-truck-overlays/overlaY4.html'''
	image1_link_name = '''ranger1'''
	image2 = '''au_edm5_ranger_20161107'''
	image2_url = '''https://www.ford.com.au/commercial/ranger/science-of-truck/?bannerid=SoTNovDec_39965218_Xaxis_InMarket_Optimisedline_FOA#overlay/content/ford/au/en_au/ranger-content/overlay-videos/the-science-truck-overlays/overlaY5.html'''
	image2_link_name = '''ranger2'''

[[module]] #Cover 13
path='email_modules/cover/04'
color='black'
segmentif = ["(user.CustomAttribute['IMD'] == 'P2')"]

	title = '''Cover 13'''
	copy = ''''''
	cta1_url = '''https://www.ford.com.au/commercial/ranger/science-of-truck/'''
	cta1_text = '''SEE ALL OF THE SCIENCE OF TRUCK'''
	cta1_icon = '''more'''
	cta1_link_name = '''scienceoftruck'''

[[module]] #Banner Image No Link
path = '''email_modules/image/banner_nolink'''
color = '''white'''

	image = '''au_edm1_cover4_20161018'''


[[module]] #Cover 07
path='email_modules/cover/02'
color='''white'''
segmentif = ["(user.CustomAttribute['IMD'] == 'P2')"]

	title='''Ranger Accessories'''
	copy='''<a href="https://www.ford.com.au/commercial/ranger/smart-accessories/" name="accessories" style="text-decoration:underline; color:#2d96cd">Ford Genuine Accessories</a> are designed to fit perfectly and integrate seamlessly with Ranger's safety systems. So whether you need a soft tonneau cover to protect your cargo or a towpack for your weekend adventure, check out our range of extras that will help take your Ranger to the next level.<br /><br />So don't wait. Book a test drive to experience the Ford Ranger 4x4 XLT Double Cab Pick-Up 3.2L Diesel Manual today.'''
	cta1_text='''BOOK A TEST DRIVE'''
	cta1_url='''https://www.ford.com.au/#overlay/content/ford/au/en_au/site-wide-content/overlays/forms/test-drive.html/'''
	cta1_link_name = '''test2'''

[[module]]
path='email_modules/cover/01'
color='white'
segmentif = ["(user.CustomAttribute['IMD'] == 'P1')"]

	title='''Ranger Accessories'''
	copy='''<a href="https://www.ford.com.au/commercial/ranger/smart-accessories/" name="accessories1" style="text-decoration:underline; color:#2d96cd">Ford Genuine Accessories</a> are designed to fit perfectly and integrate seamlessly with Ranger's safety systems. So whether you need a soft tonneau cover to protect your cargo or a towpack for your weekend adventure, check out our range of extras that will help take your Ranger to the next level.<br /><br />'''
	cta1_text='''FIND OUT MORE'''
	cta1_url='''https://www.ford.com.au/commercial/ranger/smart-accessories/'''
	cta1_icon='''more'''

[[module]] #Banner Image
path='email_modules/image/banner'
color='white'
segmentif = ["(user.CustomAttribute['IMD'] == 'P1')"]

	image='''au_edm2_svc_new_banner_20170926'''
	url_link='''https://www.ford.com.au/owners/service/'''
	url_link_name="servicebanner"


[[module]] #Cover 07
path='email_modules/cover/02'
color='''white'''
segmentif = ["(user.CustomAttribute['IMD'] == 'P1')"]

	title='''The service you'll love, guaranteed'''
	copy='''We know that a new car is a big decision <%${user.CustomAttribute['FullName']}%>, so our job isn't done once you pick up your car.<br /><br />With <a href="https://www.ford.com.au/owners/service/calculator?edm/" name="calculator1"	style="text-decoration:underline; color:#2d96cd">Ford's Service Price Promise</a>&#8308;, you'll know what you're going to pay for a standard service before you go in. But the service doesn't stop there. You can get State Auto Club Roadside Assistance and Membership&#8309; for up to 7 years from Autoclub participating dealers. Ford also has a Free Loan Car program&#8310;, so we can keep you on the road whilst your car is being serviced. After all, that's what service should be.<br /><br />So don't wait. Check out the latest offers on the Ford Ranger 4x4 XLT Double Cab Pick-Up 3.2L Diesel Manual today.'''
	cta1_text='''LATEST OFFER'''
	cta1_url='''https://www.ford.com.au/latest-offer/4x4-xlt-double-cab-pick-up-3-2l-diesel/'''
	cta1_link_name = '''moreinfo2'''

[[module]] #Footer AU Social
path='email_modules/footer/au/social'
color='white'

[[module]] #Footer Disclaimer
path='email_modules/footer/disclaimer'
color='white'
segmentif = ["(user.CustomAttribute['IMD'] == 'P2')"]

	text = '''Terms & Conditions
				<br /> <br />*Recommended Price for private and small business buyers only at participating dealers. Ford Australia reserves the right to change or extend offers.<br /><br />
				1. Braked towing capacity when fitted with a genuine Ford towpack and towball. Subject to State and Territory regulations.<br /><br />
				2. Achieved when maintaining a steady speed of not more than 7km per hour.<br /><br />
				3. Bluetooth® is a registered trademark of Bluetooth SIG Inc., and is used under licence. Some phones not compatible.'''

[[module]] #Footer Disclaimer
path='email_modules/footer/disclaimer'
color='white'
segmentelse = ["(user.CustomAttribute['IMD'] == 'P1')"]

	text = '''Terms & Conditions
				<br /> <br /> * Recommended offer available at participating dealers. Stock may vary between dealers. Private and Blue, Silver and Gold Fleet buyers only. Eligible Free Auto vehicles must be purchased by 31/12/17 and delivered by 3/01/18. Ford Dealers and Ford Australia can reduce or otherwise change these offers.
                <br /><br />
                1. Braked towing capacity when fitted with a genuine Ford towpack and towball. Subject to State and Territory regulations.<br /><br />
				2. Achieved when maintaining a steady speed of not more than 7km per hour.<br /><br />
				3. Bluetooth® is a registered trademark of Bluetooth SIG Inc., and is used under licence. Some phones not compatible.<br /><br />
				4. Available at participating Ford Dealers on vehicles built from 2007. Customers will pay equal to or less than the maximum price as published by Ford for the period of the web quote for standard items in the A and B logbook services. See <a href="https://www.ford.com.au/owners/service/t-and-c/" name="terms1"	style="text-decoration:underline; color:#91a4b1">www.ford.com.au/owners/service/t-and-c</a> for full terms.<br /><br />
				5. Available to Private and Blue Business Fleet customers who have not reached earlier of 7 years or 105,000km, only at participating Dealers. State Auto Club Roadside Assistance & Membership is included for 12 months or until your next eligible standard service (whichever occurs first). Standard services include all A and B logbook services. Customers must comply with scheduled servicing intervals to maintain continuity of membership. See  <a href="www.ford.com.au/owners/service/t-and-c/" name="term2" style="text-decoration:underline; color:#91a4b1">www.ford.com.au/owners/service/t-and-c</a> for full terms. <br /><br />
				6. Available at participating dealers on scheduled services or overnight warranty repairs. Private and Blue, Silver and Gold Business Fleet customers only. Booking may be required. See <a href="http://www.ford.com.au/owners/service/t-and-c/" name="terms3" style="text-decoration:underline; color:#91a4b1">www.ford.com.au/owners/service/t-and-c</a> for full terms.<br /><br />'''


[[module]] #Footer AU Online
path='email_modules/footer/au/online'
color='white'
+++
