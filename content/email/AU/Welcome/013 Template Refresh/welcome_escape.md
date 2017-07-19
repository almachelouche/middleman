+++
markets = ["au"]
title = '''AU Welcome 020 Escape'''

[[module]]
path='email_modules/preheaderbefore'

segmentif = ["(user.CustomAttribute['NewRepeat'] == 'R')"]

	preheader='''The adventure goes on! From all of us at Ford, we’d like to say a big thank you for choosing another Ford – we are so excited to continue to be a part of your journey!'''

[[module]]
path='email_modules/preheaderbefore'

segmentelse = ["(user.CustomAttribute['NewRepeat'] == 'N')"]

	preheader='''We hope your new Ford is everything you wanted it to be! From all of us at Ford, we’d like to say a big thank you for choosing a Ford <%${user.CustomAttribute['Model']}%> <%${user.CustomAttribute['Series']}%>, and welcome you to the family.'''

[[module]]
path='email_modules/body'

[[module]]
path='email_modules/preheaderafter'

segmentif = ["(user.CustomAttribute['NewRepeat'] == 'R')"]

	preheader='''The adventure goes on! From all of us at Ford, we’d like to say a big thank you for choosing another Ford – we are so excited to continue to be a part of your journey!'''

[[module]]
path='email_modules/preheaderafter'

segmentelse = ["(user.CustomAttribute['NewRepeat'] == 'N')"]

	preheader='''We hope your new Ford is everything you wanted it to be! From all of us at Ford, we’d like to say a big thank you for choosing a Ford <%${user.CustomAttribute['Model']}%> <%${user.CustomAttribute['Series']}%>, and welcome you to the family.'''

[[module]]
path='email_modules/header/logo'
color='white'

	image = '''white'''
	url_link = '''https://www.ford.com.au/'''


[[module]]
path = '''email_modules/image/banner_nolink'''
color = '''white'''

	image = '''au_edm1_escape_20170629'''

[[module]]
path='email_modules/cover/03'
color='''white'''
segmentif = ["(user.CustomAttribute['NewRepeat'] == 'R')"]

	copy='''<br /><%${user.CustomAttribute['FullName']}%><br />.<br />There’s nothing quite like a new car. Thank you for choosing another Ford and hope you’ve enjoyed the ride so far.<br /><br />Throughout your ownership experience with Ford you will hear from us occasionally with useful tips, service reminders and information to help you make the most of your new <%${user.CustomAttribute['Model']}%> <%${user.CustomAttribute['Series']}%>.'''

[[module]]
path='email_modules/cover/03'
color='''white'''
segmentelse = ["(user.CustomAttribute['NewRepeat'] == 'N')"]

	copy='''<br /><%${user.CustomAttribute['FullName']}%><br />.<br />There’s nothing quite like a new car. We are excited to have you as part of the Ford family and hope you’ve enjoyed the ride so far.<br /><br />Throughout your ownership experience with Ford you will hear from us occasionally with useful tips, service reminders and information to help you make the most of your new <%${user.CustomAttribute['Model']}%> <%${user.CustomAttribute['Series']}%>.'''

[[module]]
path='email_modules/cover/03'
color='''white'''

	copy='''<br /><br /><span style="font-weight: bold;">‘Peace of Mind’ Service Inspection</span><br /><br />To ensure your <%${user.CustomAttribute['Model']}%> <%${user.CustomAttribute['Series']}%> is running at its absolute best, you are entitled to a  complimentary 2-month/3,000km <span style="text-decoration:underline; color:#2D96CD">Peace of Mind Service Inspection</span>&#185;. You’ll receive a reminder from us again when you get closer to your 2 month anniversary.<br /><br />If there is anything we can help you with in the meantime please don’t hesitate to contact your Dealer <%${user.CustomAttribute['Dealer_Name']}%> on <%${user.CustomAttribute['Dealer_Phone']}%> today. You can also speak to our consultants at our Customer Relationship Centre on <a href="tel:133673" style="text-decoration:underline; color:#2D96CD">13 FORD</a> (13 36 73) or via email <a href="mailto:foacust1@ford.com" style="text-decoration:underline; color:#2D96CD">foacust1@ford.com</a>.<br /><br />''' 

[[module]]
path='email_modules/split/13'
color='white'

	title1='''Ford Owners App'''
	title2='''Get Accessorised'''
	copy1='''Download the <a href="https://www.ford.com.au/owners/vehicle-support/app-download/" name="accessory1" style="text-decoration:underline; color:#2D96CD">Ford Owners App</a> for instant access to “how-to” videos, roadside assistance information, service reminders, vehicle owner manuals, and more.<br /><br /><a href="https://www.ford.com.au/owners/vehicle-support/app-download/" name="oa" style="text-decoration:underline; color:#2D96CD">Download App Now</a><br /><br />'''
	copy2='''Take your Escape to the next level with Ford Genuine Accessories, designed to seamlessly integrate with your Escape.<br /><br /><br /><a href="https://www.ford.com.au/suv/escape/accessories/ambiente-ecoboost-petrol-awd/" name="accessory" style="text-decoration:underline; color:#2D96CD">Discover Accessories</span><br /><br />'''
	image1='''au_edm1_owner-app2_20170629'''
    image1_url='''https://www.ford.com.au/owners/vehicle-support/app-download/'''
    image1_name='''Some'''
    image2='''au_edm1_escape02_20170629'''
    image2_url='''https://www.ford.com.au/suv/escape/accessories/ambiente-ecoboost-petrol-awd/'''
    image2_name='''Some'''

[[module]]
path='email_modules/dual/05'
color='white'

	title1 = '''Ford Owners App'''
	copy1 = '''Download the <a href="https://www.ford.com.au/owners/vehicle-support/app-download/" name="accessory1" style="text-decoration:underline; color:#2D96CD">Ford Owners App</a> for instant access to “how-to” videos, roadside assistance information, service reminders, vehicle owner manuals, and more.'''
	cta1a_text = '''Download App Now'''
	cta1a_url = '''https://www.ford.com.au/owners/vehicle-support/app-download/'''
	cta1a_link_name = '''oa'''
	image1 = '''au_edm1_owner-app2_20170629'''

	title2 = '''Get Accessorised'''
	copy2 = '''Take your Escape to the next level with Ford Genuine Accessories, designed to seamlessly integrate with your Escape.<br />&nbsp;'''
	cta2a_text = '''Discover Accessories'''
	cta2a_url = '''https://www.ford.com.au/suv/escape/accessories/ambiente-ecoboost-petrol-awd/'''
	cta2a_link_name = '''accessory'''
	image2 = '''au_edm1_escape02_20170629'''

[[module]]
path='email_modules/split/13'
color='white'

	title1='''SYNC® Support'''
	title2='''Ford Service'''
	copy1='''Become a SYNC® expert. Learn how to use SAT NAV, set up Emergency Assistance and familiarise yourself with common voice commands and more on the <a href="https://www.ford.com.au/owners/technology/sync-support/sync1/" name="sync" style="text-decoration:underline; color:#2D96CD">SYNC® Support Portal</span>.<br /><br />'''
	copy2='''Enjoy the convenience of a Free Loan Car² when you book your next scheduled service. That’s what service should be.<br /><br /><a href="https://www.ford.com.au/owners/service/" name="service" style="text-decoration:underline; color:#2D96CD">Find Out More</span><br /><br />'''
	image1='''au_edm1_support_20170629'''
    image1_url='''https://www.ford.com.au/owners/technology/sync-support/sync1/'''
    image1_name='''Some'''
    image2='''au_edm1_service_20170629'''
    image2_url='''https://www.ford.com.au/owners/service/'''
    image2_name='''Some'''

[[module]]
path='email_modules/dual/05'
color='white'

	title1 = '''SYNC® Support'''
	copy1 = '''Become a SYNC® expert. Learn how to use SAT NAV, set up Emergency Assistance and familiarise yourself with common voice commands and more on the <a href="https://www.ford.com.au/owners/technology/sync-support/sync1/" name="sync" style="text-decoration:underline; color:#2D96CD">SYNC® Support Portal</a>'''
	image1 = '''au_edm1_support_20170629'''

	title2 = '''Ford Service'''
	copy2 = '''Enjoy the convenience of a Free Loan Car² when you book your next scheduled service. That’s what service should be.'''
	cta2a_text = '''Find Out More'''
	cta2a_url = '''https://www.ford.com.au/owners/service/'''
	cta2a_link_name = '''service'''
	image2 = '''au_edm1_service_20170629'''

[[module]]
path='email_modules/footer/au/social'
color='white'

[[module]]
path='email_modules/footer/disclaimer'
color='white'

	text = '''DISCLAIMERS:
				<br /> <br />
                1. ‘Peace of Mind’ Service Inspection expires after 5,000km’s or 4 months after delivery of your new Ford (whichever is first). <br /><br />
                2. Available at participating dealers on scheduled services or overnight warranty repairs. Private and Blue, Silver and Gold Business Fleet customers only. Booking required. See <a href="https://www.ford.com.au/owners/service/t-and-c/" name="terms3" style="text-decoration:underline; color:#91a4b1">www.ford.com.au/owners/service/t-and-c</a> for full terms.<br /><br />'''

[[module]]
path='email_modules/footer/au/online'
color='white'
+++
