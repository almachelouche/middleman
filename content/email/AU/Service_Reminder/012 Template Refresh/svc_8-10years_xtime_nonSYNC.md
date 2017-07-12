+++
markets = ["au"]
title = '''AU Service Reminder 003 xtime_nonSYNC '''

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

	cta1_text = '''BOOK YOUR Service'''
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


[[module]] #Footer Disclaimer 
path='email_modules/footer/disclaimer'
color='white'

	text = '''DISCLAIMERS:<br /><br />
				1) Available at participating dealers on scheduled services or overnight warranty repairs. Private and Blue, Silver and Gold Business Fleet customers only. Booking may be required. See www.ford.com.au/owners/service/t-and-c for full terms.<br /><br />
                2) Available at participating Ford dealers on vehicles built from 2007. Customers will pay equal to or less than the maximum price as published by Ford for the period of the web quote for standard items in the A and B logbook services. See www.ford.com.au/owners/service/t-and-c for full terms.<br /><br />
                

[[module]] #Footer AU Online
path='email_modules/footer/au/online'
color='white'    
+++