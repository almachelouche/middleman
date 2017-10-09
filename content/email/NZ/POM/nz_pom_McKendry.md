+++
markets = ["nz"]
title = '''NZ POM 001 McKendry Ford'''
draft = true 

[[module]]
path='email_modules/preheader'

	preheader='''Hi <%${user.CustomAttribute['FullName']}%>,<br/><br/>Here's a quick reminder that your new <%${user.CustomAttribute['Model']}%> is due for its complimentary 2-month/3,000 km Peace Of Mind Service Inspection.'''
    
[[module]] #Header Logo
path='email_modules/header/logo'
color='white'

	image = '''white'''
	url_link = '''https://www.ford.co.nz/'''

[[module]] #Banner Image
path='email_modules/image/banner'
color='white'

	image='''nz_edm2_pom_new_banner_20170920'''
	url_link='''https://www.ford.co.nz/owners/service/?intcmp=bb-fnz-hp-fnz--return/'''
	url_link_name='''pom'''

[[module]]
path='email_modules/spacer/default'
color='white'

	height="30"

[[module]]
path='email_modules/singles/copy'
color='''white'''

	copy='''Hi <%${user.CustomAttribute['FullName']}%>,<br/><br/>Here's a quick reminder that your new <%${user.CustomAttribute['Model']}%> is due for its complimentary 2-month/3,000 km Peace Of Mind Service Inspection.<br/><br/>Now that you’ve been on the road for a few months, our Ford-trained technicians will complete a quick inspection to ensure that your Ford <%${user.CustomAttribute['Model']}%> is running at its absolute best. It’s also a great time to bring up any queries or concerns you may have. <br/><br/>Book with <span style="color:#2D96CD"><%${user.CustomAttribute['Dealer_Name']}%></span> on <span style="color:#2D96CD"><%${user.CustomAttribute['Dealer_Phone']}%></span> or email <span style="color:#2D96CD"><% ${user.CustomAttribute['Dealer_Email']} %></span> today.'''

[[module]]
path='email_modules/spacer/default'
color='white'

	height="30"

[[module]]
path='email_modules/singles/ctablock'
color='''white'''
segmentelseif = ["(user.CustomAttribute['Segment'] == 'B')"]

	cta1_text = '''BOOK A SERVICE'''
	cta1_url = '''http://www.mckendryford.co.nz/Page/4/aftersales-mckendry-marlborough?of=/Contact/BookService'''
	cta1_link_name = '''service_booking'''

[[module]] #Footer NZ Social
path='email_modules/footer/nz/social'
color='white'


[[module]] #Footer NZ Online
path='email_modules/footer/nz/online'
color='white'
+++