+++
markets = ["au"]
title = '''AU Test only copy'''

[[module]]
path='email_modules/preheader'

	preheader='''The adventure goes on! From all of us at Ford, we’d like to say a big thank you for choosing another Ford – we are so excited to continue to be a part of your journey!'''

[[module]]
path='email_modules/header/logo'
color='white'

	image = '''white'''
	url_link = '''https://www.ford.com.au/'''

[[module]]
path = '''email_modules/image/banner_nolink'''
color = '''white'''

	image = '''au_edm1_focus_20170629'''

[[module]]
path='email_modules/spacer/default'
color='white'

	height="30"

[[module]]
path='email_modules/singles/copy'
color='''white'''

	copy='''Hi <%${user.CustomAttribute['FullName']}%><br /><br />There's nothing quite like a new car. Thank you for choosing another Ford and hope you've enjoyed the ride so far.<br /><br />Throughout your ownership experience with Ford you will hear from us occasionally with useful tips, service reminders and information to help you make the most of your new <%${user.CustomAttribute['Model']}%> <%${user.CustomAttribute['Series']}%>.'''

[[module]]
path='email_modules/spacer/default'
color='white'

	height="30"

[[module]]
path='email_modules/singles/copy'
color='''white'''

	copy='''<span style="font-weight: bold;">'Peace of Mind' Service Inspection</span><br /><br />To ensure your <%${user.CustomAttribute['Model']}%> <%${user.CustomAttribute['Series']}%> is running at its absolute best, you are entitled to a  complimentary 2-month/3,000km <span style="text-decoration:underline; color:#2D96CD">Peace of Mind Service Inspection</span>&#185;. You’ll receive a reminder from us again when you get closer to your 2 month anniversary.<br /><br />If there is anything we can help you with in the meantime please don’t hesitate to contact your Dealer <%${user.CustomAttribute['Dealer_Name']}%> on <%${user.CustomAttribute['Dealer_Phone']}%> today. You can also speak to our consultants at our Customer Relationship Centre on <a href="tel:133673" style="text-decoration:underline; color:#2D96CD">13 FORD</a> (13 36 73) or via email <a href="mailto:foacust1@ford.com" style="text-decoration:underline; color:#2D96CD">foacust1@ford.com</a>.'''

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

	title1='''Ford Owners App'''
	title2='''Get Accessorised'''
	copy1='''Download the <a href="https://www.ford.com.au/owners/vehicle-support/app-download/" name="accessory1" style="text-decoration:underline; color:#2D96CD">Ford Owners App</a> for instant access to “how-to” videos, roadside assistance information, service reminders, vehicle owner manuals, and more.<br /><br /><a href="https://www.ford.com.au/owners/vehicle-support/app-download/" name="oa" style="text-decoration:underline; color:#2D96CD">Download App Now</a><br /><br />'''
	copy2='''Take your Focus to the next level with Ford Genuine Accessories, designed to seamlessly integrate with your Focus.<br /><br /><br /><a href="https://www.ford.com.au/cars/focus/accessories/focus-trend-hatch/" name="accessory" style="text-decoration:underline; color:#2D96CD">Discover Accessories</span><br /><br />'''
	image1='''au_edm1_owner-app2_20170629'''
    image1_url='''https://www.ford.com.au/owners/vehicle-support/app-download/'''
    image1_name='''Some'''
    image2='''au_edm1_focus02_20170629'''
    image2_url='''https://www.ford.com.au/cars/focus/accessories/focus-trend-hatch/'''
    image2_name='''Some'''

[[module]]
path='email_modules/spacer/platinum_20'
color='white'

	height="20"

[[module]]
path='email_modules/dual/05'
color='white'

	title1 = '''SYNC® Support'''
	copy1 = '''Become a SYNC® expert. Learn how to use SAT NAV, set up Emergency Assistance and familiarise yourself with common voice commands and more on the <a href="https://www.ford.com.au/owners/technology/sync-support/sync1/" name="sync" style="text-decoration:underline; color:#2D96CD">SYNC® Support Portal</a>'''
	image1 = '''au_edm1_support_20170629'''
	image1_url = '''https://www.ford.com.au/owners/technology/sync-support/sync1/'''
	image1_link_name = '''sync'''
	title2 = '''Ford Service'''
	copy2 = '''Enjoy the convenience of a Free Loan Car² when you book your next scheduled service. That's what service should be.<br/><br/><a href="https://www.ford.com.au/owners/service/" name="service" style="text-decoration:underline; color:#2D96CD">Find Out More</span><br />'''
	image2 = '''au_edm1_service_20170629'''
    image2_url = '''https://www.ford.com.au/owners/service/'''
	image2_link_name = '''service'''


[[module]]
path='email_modules/spacer/platinum_20'
color='white'

	height="20"

[[module]]
path='email_modules/dual/05'
color='white'

	title1 = '''Auto Club Membership&#179;'''
	copy1 = '''Each time you complete your standard service at a participating Ford dealer you'll receive State <a href="https://www.ford.com.au/owners/service/roadside-assistance/" style="text-decoration:underline; color:#2D96CD">Auto Club Roadside Assistance</a> and membership for up to 12 months.'''
	image1 = '''au_edm2_auto_club_membership_20170629'''

	title2 = '''SAT NAV <br/>Updates&#8308;'''
	copy2 = '''If you have SYNC®2 with SAT NAV, we'll help you stay on track with yearly map updates for up to 7 years when you complete your service with a participating dealer.<br/><br/><a href="https://www.ford.com.au/owners/service/free-sat-nav-updates/" style="text-decoration:underline; color:#2D96CD">Learn More</a>'''
	image2 = '''au_edm2_free_sat_nav_updates_20170629'''

[[module]]
path='email_modules/spacer/platinum_20'
color='white'

	height="20"
    
[[module]]
path='email_modules/dual/05'
color='white'

	title1='''Service Price Promise&#178;'''
	title2='''Free Loan Car&#185;'''
	copy1='''Know how much your standard service will cost before you even come in, with the <ahref="https://www.ford.com.au/owners/service/calculator/" name="calculator" style="text-decoration:underline; color:#2D96CD"> Service Price Promise Calculator</span>.<br/>'''
	copy2='''Life shouldn't stop when you service your vehicle. That's why we offer a <a href="https://www.ford.com.au/owners/service/" name="freeloan" style="text-decoration:underline; color:#2D96CD">Free Loan Car&#185</a>  when you book a scheduled service.<br/>'''
    image1='''au_edm2_service_price_promise_20170629'''
    image2='''au_edm2_free_loan_car_20170629'''

[[module]]
path='email_modules/footer/au/social'
color='white'

[[module]]
path='email_modules/footer/disclaimer'
color='white'

	text = '''DISCLAIMERS:
				<br /> <br />
                1. 'Peace of Mind' Service Inspection expires after 5,000km's or 4 months after delivery of your new Ford (whichever is first). <br /><br />
                2. Available at participating dealers on scheduled services or overnight warranty repairs. Private and Blue, Silver and Gold Business Fleet customers only. Booking required. See <a href="https://www.ford.com.au/owners/service/t-and-c/" name="terms3" style="text-decoration:underline; color:#91a4b1">www.ford.com.au/owners/service/t-and-c</a> for full terms.<br /><br />'''

[[module]]
path='email_modules/footer/au/online'
color='white'
+++
