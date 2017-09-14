+++
markets = ["au"]
title = '''AU Welcome 020 Ranger'''


[[module]]
path='email_modules/preheaderbefore'

segmentif = ["(user.CustomAttribute['NewRepeat'] == 'R')"]

	preheader='''The adventure goes on! From all of us at Ford, we'd like to say a big thank you for choosing another Ford – we are so excited to continue to be a part of your journey!'''

[[module]]
path='email_modules/preheaderbefore'

segmentelse = ["(user.CustomAttribute['NewRepeat'] == 'N')"]

	preheader='''We hope your new Ford is everything you wanted it to be! From all of us at Ford, we'd like to say a big thank you for choosing a Ford <%${user.CustomAttribute['Model']}%> <%${user.CustomAttribute['Series']}%>, and welcome you to the family.'''

[[module]]
path='email_modules/body'


[[module]]
path='email_modules/preheaderafter'

segmentif = ["(user.CustomAttribute['NewRepeat'] == 'R')"]

	preheader='''The adventure goes on! From all of us at Ford, we'd like to say a big thank you for choosing another Ford – we are so excited to continue to be a part of your journey!'''

[[module]]
path='email_modules/preheaderafter'

segmentelse = ["(user.CustomAttribute['NewRepeat'] == 'N')"]

	preheader='''We hope your new Ford is everything you wanted it to be! From all of us at Ford, we'd like to say a big thank you for choosing a Ford <%${user.CustomAttribute['Model']}%> <%${user.CustomAttribute['Series']}%>, and welcome you to the family.'''


[[module]] #Header Logo
path='email_modules/header/logo'
color='white'

	image = '''white'''
	url_link = '''https://www.ford.com.au/'''


[[module]] #Banner Image No Link
path = '''email_modules/image/banner_nolink'''
color = '''white'''

	image = '''au_edm1_ranger_20170629'''
    
[[module]]
path='email_modules/spacer/default'
color='white'

	height="30"

[[module]]
path='email_modules/singles/copy'
color='''white'''
segmentif = ["(user.CustomAttribute['NewRepeat'] == 'R')"]

	copy='''Hi <%${user.CustomAttribute['FullName']}%><br /><br />There's nothing quite like a new car. Thank you for choosing another Ford and hope you've enjoyed the ride so far.<br /><br />Throughout your ownership experience with Ford you will hear from us occasionally with useful tips, service reminders and information to help you make the most of your new <%${user.CustomAttribute['Model']}%> <%${user.CustomAttribute['Series']}%>.'''
    
[[module]]
path='email_modules/singles/copy'
color='''white'''
segmentelse = ["(user.CustomAttribute['NewRepeat'] == 'N')"]

	copy='''Hi <%${user.CustomAttribute['FullName']}%><br /><br />There's nothing quite like a new car. We are excited to have you as part of the Ford family and hope you've enjoyed the ride so far.<br /><br />Throughout your ownership experience with Ford you will hear from us occasionally with useful tips, service reminders and information to help you make the most of your new <%${user.CustomAttribute['Model']}%> <%${user.CustomAttribute['Series']}%>.'''
 
 [[module]]
path='email_modules/spacer/default'
color='white'

	height="30"
    
[[module]]
path='email_modules/singles/copy'
color='''white'''

    copy = '''<span style="font-weight: bold;">'Peace of Mind' Service Inspection</span><br /><br />To ensure your <%${user.CustomAttribute['Model']}%> <%${user.CustomAttribute['Series']}%> is running at its absolute best, you are entitled to a  complimentary 2-month/3,000km <a href="https://www.ford.com.au/owners/service/peace-of-mind-inspection/" name="accessory1" style="text-decoration:underline; color:#2D96CD">Peace of Mind Service Inspection</a>&#185;. You'll receive a reminder from us again when you get closer to your 2 month anniversary.<br /><br />If there is anything we can help you with in the meantime please don't hesitate to contact your Dealer <span style="color:#2D96CD"> <%${user.CustomAttribute['Dealer_Name']}%></span> on <span style="color:#2D96CD"><%${user.CustomAttribute['Dealer_Phone']}%></span> today. You can also speak to our consultants at our Customer Relationship Centre on <a href="tel:133673" style="text-decoration:underline; color:#2D96CD">13 FORD</a> (13 36 73) or via email <a href="mailto:foacust1@ford.com" style="text-decoration:underline; color:#2D96CD">foacust1@ford.com</a>.''' 

[[module]]
path='email_modules/spacer/default'
color='white'

	height="30"
    
[[module]]
path='email_modules/spacer/platinum_20'
color='white'

	height="20"


[[module]]
path='email_modules/dual/05'
color='white'

	title1 = '''Ford Owners App'''
	text_box_height = '''310'''
	copy1 = '''Download the <a href="https://www.ford.com.au/owners/vehicle-support/app-download/" name="accessory1" style="text-decoration:underline; color:#2D96CD">Ford Owners App</a> for instant access to “how-to” videos, roadside assistance information, service reminders, vehicle owner manuals, and more.'''
	cta1a_text = '''Download App Now'''
	cta1a_url = '''https://www.ford.com.au/owners/vehicle-support/app-download/'''
	cta1a_link_name = '''link_name_here'''
	image1 = '''au_edm1_owner-app2_20170629'''
	image1_link_url = '''https://www.ford.com.au/owners/vehicle-support/app-download/'''
	image1_link_name = '''link_name_here'''
	title2 = '''Get Accessorised'''
	copy2 = '''Whether you need a tonneau cover to protect your cargo, or a tow pack for your weekend adventure, only <a href="https://www.ford.com.au/commercial/ranger/smart-accessories/" name="accessory1" style="text-decoration:underline; color:#2D96CD">Ford Genuine Accessories</a> perfectly integrate with your Ranger.'''
	cta2a_text = '''Discover Accessories'''
	cta2a_url = '''https://www.ford.com.au/commercial/ranger/smart-accessories/'''
	cta2a_link_name = '''link_name_here'''
	image2 = '''au_edm1_ranger02_20170629'''
	image2_link_url = '''https://www.ford.com.au/commercial/ranger/smart-accessories/'''
	image2_link_name = '''link_name_here'''

[[module]]
path='email_modules/spacer/platinum_20'
color='white'

	height="20"

[[module]]
path='email_modules/dual/05'
color='white'

	title1 = '''SYNC® Support'''
	text_box_height = '''310'''
	copy1 = '''Learn how to set up Emergency Assistance, familiarise yourself with common voice commands and more on the SYNC® Support Portal.'''
	cta1a_text = '''Become a SYNC® Expert'''
	cta1a_url = '''https://www.ford.com.au/owners/technology/sync-support/sync1/'''
	cta1a_link_name = '''link_name_here'''
	image1 = '''au_edm1_support_20170629'''
	image1_link_url = '''https://www.ford.com.au/owners/technology/sync-support/sync1/'''
	image1_link_name = '''link_name_here'''
	title2 = '''Ford Service'''
	copy2 = '''Enjoy the convenience of a Free Loan Car&#178 when you book your next scheduled service. That's what service should be.'''
	cta2a_text = '''Find Out More'''
	cta2a_url = '''https://www.ford.com.au/owners/service/'''
	cta2a_link_name = '''link_name_here'''
	image2 = '''au_edm1_service_20170629'''
	image2_link_url = '''https://www.ford.com.au/owners/service/'''
	image2_link_name = '''link_name_here'''

[[module]] #Footer AU Social
path='email_modules/footer/au/social'
color='white'

[[module]] #Footer Disclaimer
path='email_modules/footer/disclaimer'
color='white'

	text = '''DISCLAIMERS:
				<br /> <br />
                1. 'Peace of Mind' Service Inspection expires after 5,000km's or 4 months after delivery of your new Ford (whichever is first). <br /><br />
                2. Available at participating dealers on scheduled services or overnight warranty repairs. Private and Blue, Silver and Gold Business Fleet customers only. Booking may be required. See <a href="https://www.ford.com.au/owners/service/t-and-c/" name="terms3" style="text-decoration:underline; color:#91a4b1">www.ford.com.au/owners/service/t-and-c</a> for full terms.<br /><br />'''
                
[[module]] #Footer AU Online
path='email_modules/footer/au/online'
color='white'
+++
