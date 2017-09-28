+++
markets = ["au"]
title = '''AU Service Reminder winback 003 21-36months '''

[[module]]
path='email_modules/preheader'

	preheader='''A reminder that your Ford is overdue for it’s next scheduled service.'''


[[module]] #Banner Image
path='email_modules/image/banner'
color='white'

	image = '''AU_edm2_winback_21_36_20170928'''
	url_link = '''https://www.ford.com.au/owners/service/'''
    
[[module]]
path='email_modules/spacer/default'
color='white'

	height="30"
    
[[module]]
path='email_modules/singles/copy'
color='''white'''

	copy = '''Hi <%${user.CustomAttribute['FullName']}%>,<br /><br />
    Have you been seeing some one else? Our records show that it’s been a while since we’ve seen your Ford <nampelate> at one of our Service Departments.
    <br /> <br />

    It’s important that your <%${user.CustomAttribute['Model']}%> is serviced regularly by our Ford trained technicians to ensure you car is running at it’s absolute best.
    <br /> <br />
    To book a service you can find your local Ford Dealer  <a href="https://www.ford.com.au/dealership/" name="here" style="text-decoration:underline; color:#2D96CD">here</a>. Don’t forget to also book a free loan car&#185;  so we can keep you on the road during your service.
    '''

[[module]]
path='email_modules/spacer/default'
color='white'

	height="30"
    
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


	title1 = '''Service Price Promise&#178;'''
	text_box_height = '''240'''
	copy1 = '''Know how much your standard service will cost before you even come in, with the <a href="https://www.ford.com.au/owners/service/calculator/" name="calculator" style="text-decoration:underline; color:#2D96CD"> Service Price Promise Calculator</span>.'''
	image1 = '''au_edm2_service_price_promise_20170818'''
	image1_link_url = '''https://www.ford.com.au/owners/service/calculator/'''
	image1_link_name = '''Some'''
	title2 = '''Free Loan Car&#185;'''
	copy2 = '''Life shouldn't stop when you service your vehicle. That's why we offer a <a href="https://www.ford.com.au/owners/service/" name="freeloan" style="text-decoration:underline; color:#2D96CD">Free Loan Car&#185</a>  when you book a scheduled service.'''
	image2 = '''au_edm2_free_loan_car_20170818'''
	image2_link_url = '''https://www.ford.com.au/owners/service/'''
	image2_link_name = '''Some'''

[[module]]
path='email_modules/spacer/platinum_20'
color='white'

	height="20"
    

[[module]] #Footer AU Social
path='email_modules/footer/au/social'
color='white'

[[module]] #Footer Disclaimer 
path='email_modules/footer/disclaimer'
color='white'

	text = '''DISCLAIMERS:<br /><br />
				1) Available at participating dealers on scheduled services or overnight warranty repairs. Private and Blue, Silver and Gold Business Fleet customers only. Booking may be required. See <a href="https://www.ford.com.au/owners/service/t-and-c/" name="terms11" style="text-decoration:underline; color:#91a4b1"> www.ford.com.au/owners/service/t-and-c</a> for full terms.<br /><br />
                '''

[[module]] #Footer AU Online
path='email_modules/footer/au/online'
color='white'    
+++