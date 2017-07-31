+++
markets = ["nz"]
title = '''NZ POM 001'''

[[module]] #Header Logo
path='email_modules/header/logo'
color='white'

	image = '''white'''
	url_link = '''https://www.ford.co.nz/'''

[[module]] #Banner Image
path='email_modules/image/banner'
color='white'

	image='''nz_edm2_pom_20170728'''
	url_link='''https://www.ford.co.nz/owners/service/?intcmp=bb-fnz-hp-fnz--return/'''
	url_link_name='''pom'''

[[module]]
path='email_modules/spacer/default'
color='white'

	height="30"

[[module]]
path='email_modules/singles/copy'
color='''white'''

	copy='''Hi <%${user.CustomAttribute['FullName']}%>,<br/><br/>Here's a quick reminder that your new <%${user.CustomAttribute['Model']}%> is due for its complimentary 2-month/3,000 km Peace Of Mind Service Inspection.<br/><br/>Now that you’ve been on the road for a few months, our Ford-trained technicians will complete a quick inspection to ensure that your Ford <%${user.CustomAttribute['Model']}%> is running at its absolute best. It’s also a great time to talk about any queries or concern you may have.<br/><br/>Book with <span style="color:#2D96CD"><%${user.CustomAttribute['Dealer_Name']}%></span> on <span style="color:#2D96CD"><%${user.CustomAttribute['Dealer_Phone']}%></span> or email <span style="color:#2D96CD"><% ${user.CustomAttribute['Dealer_Email']} %></span> today.'''

[[module]]
path='email_modules/spacer/default'
color='white'

	height="30"

[[module]]
path='email_modules/singles/ctablock'
color='''white'''

	cta1_text = '''BOOK A SERVICE'''
	cta1_url = '''https://www.ford.com.au/owners/service/book-service/'''
	cta1_link_name = '''service_booking'''

[[module]] #Footer AU Social
path='email_modules/footer/au/social'
color='white'


[[module]] #Footer AU Online
path='email_modules/footer/au/online'
color='white'
+++