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
    Have you been seeing someone else? Our records show that it’s been a while since we’ve seen your Ford <%${user.CustomAttribute['Model']}%> at one of our Service Departments.
    <br /> <br />

    It’s important that your <%${user.CustomAttribute['Model']}%> is serviced regularly by our Ford trained technicians to ensure you car is running at it’s absolute best.
    <br /> <br />
    To book a service for your <%${user.CustomAttribute['Model']}%> you can find your local Ford Dealer  <a href="https://www.ford.com.au/dealership/" name="here" style="text-decoration:underline; color:#2D96CD">here</a>. Don’t forget to also book a free loan car&#185;  so we can keep you on the road during your service.
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