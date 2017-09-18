+++
markets = ["au"]
title = '''AU Apology 020 Ranger'''


[[module]]
path='email_modules/preheaderbefore'

	preheader='''ABCD'''


[[module]]
path='email_modules/body'


[[module]]
path='email_modules/preheaderafter'


	preheader='''EFGH'''



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
