+++
markets = ["au"]
title = '''AU Prospect 011 Transit_merged'''

[[module]]
path='email_modules/preheaderbefore'
color='''nothing'''
segmentif = ["(user.CustomAttribute['IMD'] == 'P2')"]

   preheader='''The Ford Transit is waiting for you at a nearby dealership!'''

[[module]]
path='email_modules/preheaderbefore'
color='''nothing'''
segmentelse = ["(user.CustomAttribute['IMD'] == 'P1')"]

   preheader='''Click through to see the latest offers on the business ready Ford Transit'''

[[module]]
path='email_modules/body'
color='''nothing'''

[[module]]
path='email_modules/preheaderbefore'
color='''nothing'''
segmentif = ["(user.CustomAttribute['IMD'] == 'P2')"]

   preheader='''The Ford Transit is waiting for you at a nearby dealership!'''

[[module]]
path='email_modules/preheaderbefore'
color='''nothing'''
segmentelse = ["(user.CustomAttribute['IMD'] == 'P1')"]

   preheader='''Click through to see the latest offers on the business ready Ford Transit'''

[[module]] #Header Logo
path='email_modules/header/logo'
color='white'

  image = '''white'''
  url_link = '''https://www.ford.com.au/'''

[[module]] #Banner Image
path = '''email_modules/image/banner_nolink'''
color = '''white'''
segmentif = ["(user.CustomAttribute['IMD'] == 'P2')"]

  image = '''au_edm5_transit3_20161013'''

[[module]] #Banner Image
path = '''email_modules/image/banner_nolink'''
color = '''white'''
segmentelse = ["(user.CustomAttribute['IMD'] == 'P1')"]

  image = '''au_edm5_transit2_20161013'''

[[module]]
path='email_modules/cover/02'
color='''white'''
segmentif = ["(user.CustomAttribute['IMD'] == 'P2')"]

    title='''The right fit for the job.'''
    copy=''''''
    cta1_text='''BOOK A TEST DRIVE'''
    cta1_url='''https://www.ford.com.au/test-drive/'''
  	cta1_link_name = '''test1'''
    cta2_text='''LATEST OFFER'''
    cta2_url='''https://www.ford.com.au/latest-offers/national?offer=transit-custom-swb'''
		cta2_link_name = '''latestoffer1'''

[[module]]
path='email_modules/cover/02'
color='''white'''
segmentelse = ["(user.CustomAttribute['IMD'] == 'P1')"]

    title='''The pleasure of getting the job done. '''
    copy=''''''
    cta1_text='''LATEST OFFER'''
    cta1_url='''https://www.ford.com.au/latest-offers/national?offer=transit-custom-swb'''
		cta1_link_name = '''latestoffer1'''
    cta2_text='''BOOK A TEST DRIVE'''
    cta2_url='''https://www.ford.com.au/test-drive/'''
  	cta2_link_name = '''test1'''
		
[[module]] #Cover 11
path='email_modules/cover/03'
color='''slatescreen'''
segmentif = ["(user.CustomAttribute['IMD'] == 'P2')"]

  copy='''<br />Hi <%${user.CustomAttribute['FullName']}%>,<br /><br />
	The Ford Transit delivers efficiency without compromising its famously generous loadspace. <br />It's hardly surprising that it was awarded International Van of the Year when it was first introduced in 2013. </span><br /><br />
	<span style="font-size:16px; color:#FFFFFF; font-family:Arial, Helvetica, sans-serif ;">
	Right now, the Transit Custom 290S SWB Van is available at $38,990.*</span>'''


[[module]] #Cover 11
path='email_modules/cover/03'
color='''slatescreen'''
segmentelse = ["(user.CustomAttribute['IMD'] == 'P1')"]

  copy='''<br />Hi <%${user.CustomAttribute['FullName']}%>,<br /><br />
	The Ford Transit delivers efficiency without compromising its famously generous loadspace. <br />It's hardly surprising that it was awarded International Van of the Year when it was first introduced in 2013. </span><br /><br />
	<span style="font-size:16px; color:#FFFFFF; font-family:Arial, Helvetica, sans-serif ;">
	Right now, the Transit Custom 290S SWB Van is available at $38,990.*</span>'''

[[module]] #Banner Image
path = '''email_modules/image/banner_nolink'''
color = '''white'''

  image = '''au_edm5_transit1_20161013'''

[[module]] #Custom 4 Icons
path='email_modules/custom/4icons'
color='white'

	title = '''Featuring:'''
  icon1_url='''http://www.india.ford.com/locate-dealer'''
  icon1_link_name = '''locate_dealer'''
  icon1_image='''au_edm5_transmission_20161013 '''
  icon1_text = '''2.2L TDCi Diesel engine with 6-speed manual transmission'''

  icon2_url='''tel:18004252500'''
  icon2_link_name = '''locate_dealer2'''
  icon2_image='''au_edm5_sync2_20161107'''
  icon2_text = '''Ford SYNC® connectivity system&#185;'''

  icon3_url='''tel:18002097400'''
  icon3_link_name = '''locate_dealer3'''
  icon3_image='''au_edm5_cruisecontrol_20161013'''
  icon3_text = '''Cruise control'''

  icon4_url='''https://partscalculator.fordind.com:1443/Fill_Field'''
  icon4_link_name = '''locate_dealer4'''
  icon4_image='''au_edm5_airbags_20161013'''
  icon4_text = '''Driver and front passenger airbags'''

[[module]] #Cover 13
path='email_modules/cover/04'
color='white'

  title = '''Cover 13'''
  copy = '''<br />All this and more is available to you now in the Ford Transit.'''
  cta1_url = '''https://www.ford.com.au/commercial/transit-custom/'''
  cta1_text = '''FIND OUT MORE'''
  cta1_icon = '''more'''
  cta1_link_name = '''moreinfo'''

[[module]] #Banner Image
path = '''email_modules/image/banner'''
color = '''white'''

  image = '''au_edm5_RSvc_Due_xtime_20161013'''
	url_link = '''https://www.ford.com.au/owners/service/'''

[[module]] #Cover 07
path='email_modules/cover/02'
color='''white'''
segmentif = ["(user.CustomAttribute['IMD'] == 'P2')"]

  title='''The service you'll love, guaranteed'''
  copy='''We know that a new car is a big decision <%${user.CustomAttribute['FullName']}%>, so our job isn't done once you pick up your car.<br /><br />
	With <a href="https://www.ford.com.au/owners/service/calculator?edm" name="calculator" style="text-decoration:underline; color:#2d96cd">Ford's Service Price Promise</a>&#178;, you'll know what you're going to pay
	for a standard service before you go in. But the service doesn't stop there.
	You can get State Auto Club Roadside Assistance and Membership&#179; for up to 7 years from Autoclub participating dealers. Ford also has a Free Loan Car program&#8308;, so we can keep you on the road whilst your car is being serviced. After all, that's what service should be. <br /><br />So don't wait. Book a test drive to experience the Ford Transit today.'''
	cta1_text='''BOOK A TEST DRIVE'''
	cta1_url='''https://www.ford.com.au/test-drive/'''
	cta1_link_name = '''test2'''

[[module]] #Cover 07
path='email_modules/cover/02'
color='''white'''
segmentelse = ["(user.CustomAttribute['IMD'] == 'P1')"]

  title='''The service you'll love, guaranteed'''
  copy='''We know that a new car is a big decision <%${user.CustomAttribute['FullName']}%>, so our job isn't done once you pick up your car.<br /><br />
	With <a href="https://www.ford.com.au/owners/service/calculator?edm" name="calculator" style="text-decoration:underline; color:#2d96cd">Ford's Service Price Promise</a>&#178;, you'll know what you're going to pay
	for a standard service before you go in. But the service doesn't stop there.
	You can get State Auto Club Roadside Assistance and Membership&#179; for up to 7 years from Autoclub participating dealers. Ford also has a Free Loan Car program&#8308;, so we can keep you on the road whilst your car is being serviced. After all, that's what service should be. <br /><br />So don't wait. Check out the latest offers on the Ford Transit today.'''
  cta1_text='''LATEST OFFER'''
  cta1_url='''https://www.ford.com.au/latest-offers/national?offer=transit-custom-swb'''
  cta1_link_name = '''latestoffer2'''

[[module]] #Footer AU Social
path='email_modules/footer/au/social'
color='white'

[[module]] #Footer Disclaimer
path='email_modules/footer/disclaimer'
color='white'

text = '''Terms & Conditions<br /> <br />
	* Limited offers available at participating Dealers while stocks last. Private and Blue, Silver and Gold Business Fleet customers only. Stock may vary between Dealers. All prices are recommended. See <a href="https://www.ford.com.au/latest-offers/" name="latest_offer2" style="text-decoration:underline; color:#91a4b1">www.ford.com.au/latest-offers</a> for full details.<br /><br />
	1. For SYNC® compatibility visit <a href="https://www.ford.com.au/technology/sync/" style="text-decoration:underline; color:#91a4b1">www.ford.com.au/technology/sync</a>.<br /><br />
	2. Available at participating Ford Dealers on vehicles built from 2007. Customers will pay equal to or less than the maximum price as published by Ford for the period of the web quote for standard items in the A and B logbook service together with selected routine maintenance items. See <a href="https://www.ford.com.au/owners/service/t-and-c/" name="terms1" style="text-decoration:underline; color:#91a4b1">www.ford.com.au/owners/service/t-and-c</a> for full terms.<br /><br />
	3. Available to Private and Blue Business Fleet customers who have not reached 105,000km/7 years only at participating Dealers. State Auto Club Roadside Assistance & Membership is provided at no cost for 12 months or until your next eligible standard service (whichever occurs first). Customers must comply with scheduled servicing intervals to maintain continuity of membership. See <a href="https://www.ford.com.au/owners/service/t-and-c/" name="terms2" style="text-decoration:underline; color:#91a4b1">www.ford.com.au/owners/service/t-and-c</a> for full terms.<br /><br />
	4. Available at participating dealers on scheduled services or overnight warranty repairs. Private and Blue, Silver and Gold Business Fleet customers only. Booking may be required. See <a href="https://www.ford.com.au/owners/service/t-and-c/" name="terms3" style="text-decoration:underline; color:#91a4b1">www.ford.com.au/owners/service/t-and-c</a> for full terms.<br /><br />'''


[[module]] #Footer AU Online
path='email_modules/footer/au/online'
color='white'
+++
