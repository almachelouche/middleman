+++
markets = ["au"]
title = '''AU Service Reminder 011 All Blue back up'''

[[module]]
path='email_modules/preheader'
color='''nothing'''

   preheader=''''''

[[module]]
path='email_modules/preheader'
color='''nothing'''

   preheader=''''''

[[module]] #Header Logo
path='email_modules/header/logo'
color='white'

  image = '''white'''
  url_link = '''http://google.com'''

[[module]] #Banner Image
path='email_modules/image/banner'
color='white'

  image = '''au_edm2_RSvc_Due_xtime_logo_20161014'''
  url_link = '''http://www.ford.com.au/owners/service'''

[[module]] #Banner Image
path='email_modules/image/banner'
color='white'

  image = '''au_edm2_mustang15_logo_20161014'''
  url_link = '''http://www.ford.com.au/owners/service'''

[[module]]
path='email_modules/cover/03'
color='''white'''

	copy='''<br />Hi #Personalisation#<br /><br />his is just a friendly reminder that your Ford #PersonalisedVehicleName# is nearly due for a service. <br /><br />Book with #DealerName# on #DealerPhone# today.'''

[[module]]
path='email_modules/singles/ctablock'
color='''white'''
	
	cta1_text = '''BOOK A SERVICE'''
	cta1_url = '''https://consumer.xtime.net.au/scheduling/?company=14745&store=%3C%${user.CustomAttribute[%27DealerCode%27]}%%3E&VIN=%3C%${user.CustomAttribute[%27Vin%27]}%%3E&provider=FORD_AU_THE_BLUE_HIVE&keyword=%3C%${user.CustomAttribute[%27CampaignID%27]}%%3E&dest=&extid=%3C%${user.CustomAttribute[%27CampaignID%27]}%%3E&extctxt=FORD_AU_THE_BLUE_HIVE&cfn=%3C%${user[%27FirstName%27]}%%3E&cln=%3C%${user[%27LastName%27]}%%3E&cpn=%3C%${user.CustomAttribute[%27Mobile_Phone%27]}%%3E&cem=%3C%${user[%27Email%27]}%%3E&button=blue'''
	cta1_link_name = '''SERVICE'''

[[module]] #3 Images
path = '''email_modules/image/3images'''
color = '''white'''

  image1 = '''au_svc_icon1'''
	image1_url = ''''''
	image1_link_name = '''icon1'''
  image2 = '''au_svc_icon2'''
	image2_url = ''''''
	image2_link_name = '''icon2'''
  image3 = '''au_svc_icon3'''
	image3_url = ''''''
	image3_link_name = '''icon3'''

[[module]] #4 Images
path = '''email_modules/image/4images'''
color = '''white'''

  image1 = '''au_svc_icon1'''
	image1_url = ''''''
	image1_link_name = '''icon4'''
  image2 = '''au_svc_icon2'''
	image2_url = ''''''
	image2_link_name = '''icon5'''
  image3 = '''au_svc_icon3'''
	image3_url = ''''''
	image3_link_name = '''icon6'''
  image4 = '''au_svc_icon4'''
	image4_url = ''''''
	image4_link_name = '''icon7'''

[[module]] #Cover 13
path='email_modules/cover/04'
color='white'

  title = '''Cover 13'''
  copy = ''' As someone with a genuine passion for performance, we’re sure you’ll appreciate the many benefits of putting your pony in the trusted hands of Ford factory trained technicians who use diagnostic equipment specifically designed for Fords.<br /><br />You’ll also receive free #StateAutoClub# Roadside Assistance and Membership¹ for up to 12 months, free map updates for your SYNC® 2 Satellite Navigation System² when required, and you can even book a free loan car³ so we can keep you on the road.<br /><br /> '''
  cta1_url = '''http://www.ford.com.au/owners/service?emailid=20150918-0102_CTAVisitFordOwners__service'''
  cta1_text = '''FIND OUT MORE'''
  cta1_icon = '''more'''  
  
  
[[module]] #Cover 13
path='email_modules/cover/04'
color='white'

  title = '''Cover 13'''
  copy = ''' As someone with a genuine passion for performance, we’re sure you’ll appreciate the many benefits of putting your nameplate in the trusted hands of Ford factory trained technicians who use diagnostic equipment specifically designed for Fords.<br /><br />You’ll also receive free #StateAutoClub# Roadside Assistance and Membership¹ for up to 12 months. You can even book a free loan car³ so we can keep you on the road.'''
  cta1_url = '''http://www.ford.com.au/owners/service?emailid=20150918-0102_CTAVisitFordOwners__service'''
  cta1_text = '''FIND OUT MORE'''
  cta1_icon = '''more'''

[[module]]
path='email_modules/cover/01'

color='''white'''
icon='''au_edm2_calculator_20161014'''
title='''Ford’s Service Price Promise⁴'''
copy='''Find out the most your standard service will cost before you drive in, try our service calculator.'''

[[module]] #Footer AU Social
path='email_modules/footer/au/social'
color='white'

[[module]] #Footer Disclaimer
path='email_modules/footer/disclaimer'
color='white'

  text = '''DISCLAIMERS:<br /><br />
        1) Available to Private and Blue Business Fleet customers who have not reached 105,000km/7 years only at participating Dealers. State Auto Club Roadside Assistance & Membership is provided at no cost for 12 months or until your next eligible standard service (whichever occurs first). Customers must comply with scheduled servicing intervals to maintain continuity of membership. See www.ford.com.au/service/t-and-c</a> for full terms.<br /><br />
        2) SYNC Gen2 (SYNC® 2) customers who complete their scheduled servicing with participating Ford Dealers will receive free yearly map updates for up to 7 years (but no later than 30 September 2024). Customers must comply with scheduled servicing intervals. See www.ford.com.au/service/t-and-c</a> for full terms.<br /><br />
        3)  Available at participating dealers on scheduled services or overnight warranty repairs. Private and Blue, Silver and Gold Business Fleet customers only. Booking may be required. See www.ford.com.au/service/t-and-c</a> for full terms.<br /><br />
        4） Available at participating Ford Dealers on vehicles built from 2007. Customers will pay equal to or less than the maximum price as published by Ford for the period of the web quote for standard items in the A and B logbook services. See www.ford.com.au/service/t-and-c</a> for full terms.<br /><br />'''



[[module]] #Footer Disclaimer
path='email_modules/footer/disclaimer'
color='white'

  text = '''DISCLAIMERS:<br /><br />
        1) Available at participating dealers on scheduled services or overnight warranty repairs. Private and Blue, Silver and Gold Business Fleet customers only. Booking may be required. See www.ford.com.au/service/t-and-c</a> for full terms.<br /><br />
        2) Available at participating Ford Dealers on vehicles built from 2007. Customers will pay equal to or less than the maximum price as published by Ford for the period of the web quote for standard items in the A and B logbook services. See www.ford.com.au/service/t-and-c</a> for full terms. <br /><br />
        3) Available to Private and Blue Business Fleet customers who have not reached 105,000km/7 years only at participating Dealers. State Auto Club Roadside Assistance & Membership is provided at no cost for 12 months or until your next eligible standard service (whichever occurs first). Customers must comply with scheduled servicing intervals to maintain continuity of membership. See www.ford.com.au/service/t-and-c</a> for full terms.<br /><br />
        4) Customers must comply with scheduled servicing intervals. See www.ford.com.au/service/t-and-c</a> for full terms. <br /><br />'''


[[module]] #Footer Disclaimer
path='email_modules/footer/disclaimer'
color='white'

  text = '''DISCLAIMERS:<br /><br />
        1) Available at participating Ford Dealers on vehicles built from 2007. Customers will pay equal to or less than the maximum price as published by Ford for the period of the web quote for standard items in the A and B logbook services. See www.ford.com.au/service/t-and-c</a> for full terms.<br /><br />
        2) Available at participating dealers on scheduled services or overnight warranty repairs. Private and Blue, Silver and Gold Business Fleet customers only. Booking may be required. See www.ford.com.au/service/t-and-c</a> for full terms. <br /><br />
        3) Available to Private and Blue Business Fleet customers who have not reached 105,000km/7 years only at participating Dealers. State Auto Club Roadside Assistance & Membership is provided at no cost for 12 months or until your next eligible standard service (whichever occurs first). Customers must comply with scheduled servicing intervals to maintain continuity of membership. See www.ford.com.au/service/t-and-c</a> for full terms.<br /><br />'''
    

[[module]] #Footer AU Online
path='email_modules/footer/au/online'
color='white'
+++