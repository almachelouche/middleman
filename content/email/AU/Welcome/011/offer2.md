+++
markets = ["au"]
title = '''AU Welcome 011 Offer 2'''

[[module]]
path='email_modules/preheader'
color='''nothing'''
segmentif = ["(user.CustomAttribute['NewRepeat'] == 'R')"]

	preheader='''The journey continues! From all the team at Ford, we'd like to say a big THANK YOU for choosing another Ford.'''

[[module]]
path='email_modules/preheader'
color='''nothing'''
segmentelse = ["(user.CustomAttribute['NewRepeat'] == 'N')"]

	preheader='''We hope you're enjoying the ride. From all the team at Ford, we'd like to say a big THANK YOU for choosing a Ford <%${user.CustomAttribute['Model']}%> <%${user.CustomAttribute['Series']}%>.'''


[[module]] #Header Logo
path='email_modules/header/logo'
color='white'

	image = '''white'''
	url_link = '''https://www.ford.com.au/'''



 
[[module]] #Cover 01 - Repeat Buyer
path='email_modules/cover/01'
color='''slatescreen'''
segmentif = ["(user.CustomAttribute['NewRepeat'] == 'R')"]
 
	title='''Hi <%${user.CustomAttribute['FullName']}%><br />The journey continues'''
	copy='''From all the team at Ford, we'd like to say a big THANK YOU for choosing another Ford.'''

[[module]] #Cover 01 - New Buyer
path='email_modules/cover/01'
color='''slatescreen'''
segmentelse = ["(user.CustomAttribute['NewRepeat'] == 'N')"]
 
	title='''Hi <%${user.CustomAttribute['FullName']}%><br />We hope you're enjoying the ride.'''
	copy='''From all the team at Ford, we'd like to say a big THANK YOU for choosing a Ford <%${user.CustomAttribute['Model']}%> <%${user.CustomAttribute['Series']}%>.'''

[[module]] #Banner Image No Link
path = '''email_modules/image/banner_nolink'''
color = '''white'''

	image = '''au_edm1_cover_20161018'''


[[module]] #Cover 11
path='email_modules/cover/03'
color='''white'''


	copy='''<br /><br />But our job isn't done now that you're on the road. At Ford we like to look after our owners, so we provide our Service Guarantee for added peace-of-mind.<br /><br />You get State Auto Club Roadside Assistance and Membership¹ for up to 7 years from Autoclub participating dealers. But the service doesn't stop there. Ford also has a Free Loan Car program², so we can keep you on the road whilst your car is being serviced.<br /><br />Best of all, you secured up to 5 years/100,000km warranty, plus five $100 scheduled service discounts³. Simply book an appointment with your local participating Ford Dealership by the date your Ford <%${user.CustomAttribute['Model']}%> <%${user.CustomAttribute['Series']}%> is due for a service, and the team will have the discount noted in the system. Just a reminder, each discount is valid only within its respective designated service interval, so to ensure your discount doesn't expire please keep on top of your service due dates/km.'''




 [[module]] #3 Images
path = '''email_modules/image/3images'''
color = '''white'''

	image1 = '''au_svc_icon3'''
	image1_url = '''https://www.ford.com.au/owners/service/roadside-assistance/'''
	image1_link_name = '''icon1'''
	image2 = '''au_svc_icon2'''
	image2_url = '''https://www.ford.com.au/owners/service/calculator?edm'''
	image2_link_name = '''icon2'''
	image3 = '''au_svc_icon1'''
	image3_url = '''https://www.ford.com.au/owners/service/'''
	image3_link_name = '''icon3'''

	[[module]] #Banner Image No Link
path = '''email_modules/image/banner_nolink'''
color = '''white'''
segmentif = ["(user.CustomAttribute['Model'] == 'Ranger')"]

	image = '''au_edm1_cover4_20161018'''

[[module]] #Cover 01 - Ranger
path='email_modules/cover/01'
color='white'
segmentif = ["(user.CustomAttribute['Model'] == 'Ranger')"]

	title='''Ranger Accessories '''
	copy='''Now that you have your Ranger, we'd like to help you make the most out of your new truck. <br /><br /><a href="https://www.ford.com.au/commercial/ranger/smart-accessories/" name="accessory1" style="text-decoration:underline; color:#2D96CD"> Ford Genuine Accessories</a> are designed to fit perfectly and integrate seamlessly with Ranger's safety systems. So whether you need a soft tonneau cover to protect your cargo or a towpack for your weekend adventure, check out our range of extras that will help take your Ranger to the next level.'''
	cta1_text='''Find Out More'''
	cta1_url='''https://www.ford.com.au/commercial/ranger/smart-accessories/'''
	cta1_link_name = '''accessory2'''
	cta1_icon='''more'''

[[module]] #Banner Image No Link
path = '''email_modules/image/banner_nolink'''
color = '''white'''
	image='''au_edm1_cover2_20161018'''

[[module]] #AU FordOwner Resources
path='email_modules/custom/fordowner_resources'
color='white'

	title = '''Ford Owner Resources'''
	copy1 = '''Ford offers two ways to access helpful resources and information anywhere you go. <br /><br />You can visit the <span style="font-weight: bold;">Ford Owners Website</span> online at any time to view videos, check for vehicle updates, or find your closest service centre. Register quickly and easily: Assign a nickname to your Ford <%${user.CustomAttribute['Model']}%> <%${user.CustomAttribute['Series']}%> and enter your Vehicle Identification Number <%${user.CustomAttribute['VIN']}%>'''
		copy2 = '''You can also download the <span style="font-weight: bold;">Ford Owners App</span> to your mobile device for instant access on-the-go. <br /><br />'''
	cta1_text='''Visit Ford Owners Website'''
	cta1_url='''https://www.ford.com.au/owners/'''
	cta2_text='''iOS'''
	cta2_url='''https://itunes.apple.com/in/app/ford-owners/id990342351?mt=8'''
	cta3_text='''Android'''
	cta3_url='''https://play.google.com/store/apps/details?id=com.ford.fordowners&hl=en'''
	cta1_icon='''more'''

[[module]] #Cover 01
path='email_modules/cover/01'
color='''fordblue'''

	icon='''au_edm1_welcome_icon_20161019'''
	title='''Can we help?'''
	copy='''
If you have any further questions, please don't hesitate to contact <br /><br /><span style="color:#FFFFFF"><%${user.CustomAttribute['Dealer_Name']}%> on <a href="tel:<%${user.CustomAttribute['Dealer_Phone']}%>" style="color:#FFFFFF; text-decoration:none"><%${user.CustomAttribute['Dealer_Phone']}%></a>	</span>or <a href="tel:133673" style="color:#FFFFFF; text-decoration:none"><span style="color:#FFFFFF">13 FORD (13 36 73)</span>'''


[[module]] #Footer AU Social
path='email_modules/footer/au/social'
color='white'

[[module]] #Footer Disclaimer
path='email_modules/footer/disclaimer'
color='white'

	text = '''DISCLAIMERS:
				<br /> <br />
				1) Private and Blue Business Fleet customers only at participating Dealers who have not reached 7 years or 105,000 kms. State Auto Club Roadside Assistance & Membership is provided at no cost with the first seven standard services for 12 months or until your next eligible standard service (whichever occurs first). Standard services include all A and B logbook services. Customers must comply with scheduled servicing intervals to maintain continuity of membership. See <a href="https://www.ford.com.au/owners/service/t-and-c/" name="terms1" style="text-decoration:underline; color:#91a4b1">www.ford.com.au/owners/service/t-and-c</a> for full terms.<br /><br />
				2) Available at participating dealers on scheduled services or overnight warranty repairs. Private and Blue, Silver and Gold Business Fleet customers only. Booking may be required. See <a href="https://www.ford.com.au/owners/service/t-and-c/"	name="terms2" style="text-decoration:underline; color:#91a4b1">www.ford.com.au/owners/service/t-and-c</a> for full terms.<br /><br />
				3) Extended warranty covers 5 years/100,000km from date of registration, whichever occurs first. Service discounts must be used across the first five scheduled services. Customers must comply with recommended servicing intervals or discount will expire. Discount entitlements are transferable with the nominated vehicle and remain visible in the Ford service system. Conditions apply. See <a href="https://www.ford.com.au/"	name="ford1" style="text-decoration:underline; color:#91a4b1">www.ford.com.au</a>.'''



[[module]] #Footer AU Online
path='email_modules/footer/au/online'
color='white'
+++