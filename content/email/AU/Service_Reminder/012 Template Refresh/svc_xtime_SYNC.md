+++
markets = ["au"]
title = '''AU Service Reminder 003 xtime_SYNC '''

[[module]]
path='email_modules/preheader'

	preheader=''''''


[[module]] #Banner Image
path='email_modules/image/banner'
color='white'

	image = '''au_edm2_RSvc_Due_xtime_logo_20161014'''
	url_link = '''https://www.ford.com.au/owners/service/'''
    
[[module]]
path='email_modules/spacer/default'
color='white'

	height="30"
    
[[module]]
path='email_modules/singles/copy'
color='''white'''

	copy = '''Hi <%${user.CustomAttribute['FullName']}%>,<br /><br />This is just a friendly reminder that your Ford<span style="color:#2D96CD"><%${user.CustomAttribute['Model']}%></span> is nearly due for its <service interval> service.<br /><br />. 
    We know how important your <%${user.CustomAttribute['Model']}%></span> is to you, so we're sure you'll appreciate the many benefits of putting your <%${user.CustomAttribute['Model']}%></span> in the trusted hands of Ford trained technicians. You can even book a Free Loan Car&#185; for the day when you book your scheduled service.<br /><br />
    Book your service and Free Loan Car&#185; with <span style="color:#2D96CD"><%${user.CustomAttribute['Dealer_Name']}%></span> on <span style="color:#2D96CD"><%${user.CustomAttribute['Dealer_Phone']}%></span> today, or find your nearest dealer. You can even book online below.'''

[[module]]
path='email_modules/spacer/default'
color='white'

	height="30"

[[module]]
path='email_modules/singles/ctablock'
color='''white'''

	cta1_text = '''BOOK YOUR SERVICE'''
	cta1_url = '''https://www.ford.com.au/owners/service/book-service/'''
	cta1_link_name = '''service_booking'''
    
[[module]]
path='email_modules/spacer/default'
color='white'

	height="30"
    
 [[module]] #Split 13
path='email_modules/split/13'
color='white'

	title1='''Service Price Promise&#178;'''
	title2='''Free Loan Car&#185;'''
	copy1='''Know how much your standard service will cost before you even come in, with the <ahref="https://www.ford.com.au/owners/service/calculator/" name="calculator" style="text-decoration:underline; color:#2D96CD"> Service Price Promise Calculator</span>.<br/><br/>'''
	copy2='''Life shouldn’t stop when you service your vehicle. That’s why we offer a <a href="https://www.ford.com.au/owners/service/" name="freeloan" style="text-decoration:underline; color:#2D96CD">Free Loan Car&#185</a>  when you book a scheduled service.<br/><br/>'''
	image1='''au_edm2_service_price_promise_20170629'''
    image1_url='''https://www.ford.com.au/owners/service/calculator/'''
    image1_name='''Some'''
    image2='''au_edm2_free_loan_car_20170629'''
    image2_url='''https://www.ford.com.au/owners/service/'''
    image2_name='''Some'''

 [[module]] #Split 13
path='email_modules/split/13'
color='white'

	title1='''Auto Club Membership&#179;'''
	title2='''SAT NAV Updates&#8308;'''
	copy1='''Each time you complete your standard service at a participating Ford dealer you’ll receive State <a href="https://www.ford.com.au/owners/service/roadside-assistance/" style="text-decoration:underline; color:#2D96CD">Auto Club Roadside Assistance</a> and membership for up to 12 months.<br/><br/>'''
	copy2='''If you have SYNC®2 with SAT NAV, we’ll help you stay on track with yearly map updates for up to 7 years when you complete your service with a participating dealer.<br/><br/><a href="https://www.ford.com.au/owners/service/free-sat-nav-updates/" style="text-decoration:underline; color:#2D96CD">Learn More</a>'''
	image1='''au_edm2_auto_club_membership_20170629'''
    image1_url='''https://www.ford.com.au/owners/service/roadside-assistance/'''
    image1_name='''Some'''
    image2='''au_edm2_free_sat_nav_updates_20170629'''
    image2_url='''https://www.ford.com.au/owners/service/free-sat-nav-updates/'''
    image2_name='''Some'''


[[module]] #Footer Disclaimer 
path='email_modules/footer/disclaimer'
color='white'

	text = '''DISCLAIMERS:<br /><br />
				1) Available at participating dealers on scheduled services or overnight warranty repairs. Private and Blue, Silver and Gold Business Fleet customers only. Booking may be required. See www.ford.com.au/owners/service/t-and-c for full terms.<br /><br />
                2) Available at participating Ford dealers on vehicles built from 2007. Customers will pay equal to or less than the maximum price as published by Ford for the period of the web quote for standard items in the A and B logbook services. See www.ford.com.au/owners/service/t-and-c for full terms.<br /><br />
                3) Available to Private and Blue Business Fleet customers who have not reached 105,000km/7 years only at participating dealers. State Auto Club Roadside Assistance & Membership is included for 12 months or until your next eligible standard service (whichever occurs first). Customers must comply with scheduled servicing intervals to maintain continuity of membership. See www.ford.com.au/owners/service/t-and-c for full terms.<br /><br />
                4) Customers must comply with scheduled servicing intervals. See www.ford.com.au/owners/service/t-and-c for full terms.<br /><br />'''

[[module]] #Footer AU Online
path='email_modules/footer/au/online'
color='white'    
+++