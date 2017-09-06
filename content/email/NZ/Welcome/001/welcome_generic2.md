+++
markets = ["nz"]
title = '''NZ Welcome 001 generic2'''

[[module]] #Header Logo
path='email_modules/header/logo'
color='white'

	image = '''white'''
	url_link = '''https://www.ford.com.au/'''


[[module]] #Banner Image No Link
path = '''email_modules/image/banner_nolink'''
color = '''white'''

	image = '''au_edm1_cover_20161018'''

	[[module]] #Cover 11
path='email_modules/cover/03'
color='''white'''

	copy='''<br /><br />Welcome to the Ford family. We would like to thank you for choosing Ford and hope that you are enjoying the experience.<br /><br />Along with driver assistance technologies that enable a 5-Star safety rating, Ford brings the latest communications technology to New Zealand drivers. Not only is your vehicle safe, it’s also smart!'''



 [[module]] #Banner Image No Link
path = '''email_modules/image/banner_nolink'''
color = '''white'''

	image = '''au_edm1_cover4_20161018'''


[[module]] #AU FordOwner Resources
path='email_modules/custom/fordowner_resources'
color='white'

	title = '''Ford Owner Resources'''
	copy1 = '''Ford offers two ways to access helpful resources and information anywhere you go. <br /><br />You can visit the Ford Owners Website online at any time to view videos, check for vehicle updates, learn about the <a href="https://www.ford.co.nz/technology/sync/" name="sync" style="text-decoration:underline; color:#2D96CD">SYNC&#174; infotainment system</a>, or find your closest service centre. Register quickly and easily: Assign a nickname to your Ford <%${user.CustomAttribute['Model']}%> <%${user.CustomAttribute['Series']}%> and enter your Vehicle Identification Number <%${user.CustomAttribute['VIN']}%>.'''
		copy2 = '''You can also download the <span style="font-weight: bold;">Ford Owners App</span> to your mobile device for instant access on-the-go. <br /><br />'''
	cta1_text='''Visit Ford Owners Website'''
	cta1_url='''https://www.ford.co.nz/owners/'''
	cta2_text='''iOS'''
	cta2_url='''https://itunes.apple.com/in/app/ford-owners/id990342351?mt=8'''
	cta3_text='''Android'''
	cta3_url='''https://play.google.com/store/apps/details?id=com.ford.fordowners&hl=en'''
	cta1_icon='''more'''

[[module]] #Banner Image No Link
path = '''email_modules/image/banner_nolink'''
color = '''white'''

	image = '''au_edm1_cover4_20161018'''

[[module]] #Cover 01 
path='email_modules/cover/01'
color='white'
	copy='''Included with your new <%${user.CustomAttribute['Model']}%> is a 3 year/100,000km Warranty, 3 Year Roadside Assistance along with a 20,000km/12 Month Service intervals (whichever occurs first).<br /><br /> Within the next two months you will also receive from us an email to remind you to book in a Peace of Mind checkup. This complimentary check will ensure that you are happy with how your vehicle is running. It also provides the opportunity discuss any questions or concerns you may have around your new <%${user.CustomAttribute['Model']}%>.'''
 

[[module]] #Cover 01
path='email_modules/cover/01'
color='''fordblue'''

	icon='''au_edm1_welcome_icon_20161019'''
	title='''Can we help?'''
	copy='''Our Ford Customer Assistance Team is always available to assist with any questions you may have. They can be contacted on <span style="color:#FFFFFF">0800 Ford NZ (0200 367 369)</span>.'''


[[module]] #Footer NZ Social
path='email_modules/footer/nz/social'
color='white'


[[module]] #Footer NZ Online
path='email_modules/footer/nz/online'
color='white'
+++
