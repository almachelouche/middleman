+++
markets = ["nz"]
title = '''NZ Service Reminder 001 1st-year'''

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
	url_link_name='''svc'''

[[module]]
path='email_modules/spacer/default'
color='white'

	height="30"

[[module]]
path='email_modules/singles/copy'
color='''white'''

	copy='''Hi <%${user.CustomAttribute['FullName']}%>,<br/><br/>Your next service is due on <%${user.CustomAttribute['NextServiceDate']}%><br/><br/>Book with <span style="color:#2D96CD"><%${user.CustomAttribute['Dealer_Name']}%></span> on <span style="color:#2D96CD"><%${user.CustomAttribute['Dealer_Phone']}%></span> or email <span style="color:#2D96CD"><% ${user.CustomAttribute['Dealer_Email']} %></span> today.'''
    
[[module]]
path='email_modules/singles/ctablock'
color='''white'''
segmentif = ["(user.CustomAttribute['SERVAPPT'] == 'YES')"]

	cta1_text = '''BOOK A SERVICE'''
	cta1_url = '''https://www.ford.com.au/owners/service/book-service/'''
	cta1_link_name = '''booking'''
    cta1_text1 = '''aaa'''
	cta1_url1 = '''https://www.ford.com.au/owners/service/book-service'''
	cta2_link_name1 = '''test'''

[[module]] #4 Images
path = '''email_modules/image/4images'''
color = '''white'''

	image1 = '''nz_edm2_loancar_20170803'''
	image1_url = '''https://www.ford.co.nz/owners/service/?intcmp=bb-fnz-hp-fnz--return/'''
	image1_link_name = '''icon4'''
	image2 = '''nz_edm2_costestimates_20170803'''
	image2_url = '''https://www.ford.co.nz/owners/service/service-estimate/'''
	image2_link_name = '''icon5'''
	image3 = '''nz_edm2_vehiclereport_20170728'''
	image3_url = '''https://www.ford.co.nz/owners/service/?intcmp=bb-fnz-hp-fnz--return/'''
	image3_link_name = '''icon6'''
	image4 = '''nz_edm2_genuine_20170728'''
	image4_url = '''https://www.ford.co.nz/owners/service/genuine-ford-parts/'''
	image4_link_name = '''icon7'''

[[module]]
path='email_modules/spacer/default'
color='white'

	height="30"

[[module]]
path='email_modules/singles/copy'
color='''white'''

    copy='''We know how important your <%${user.CustomAttribute['Model']}%> is to you, so we're sure you'll appreciate the many benefits of putting your <%${user.CustomAttribute['Model']}%> in the trusted hands of Ford trained technicians who use diagnostic equipment specifically designed for Fords. With Genuine Ford Parts you can be assured of the highest standards of quality, fit and finish.<br/><br/>When you book or bring your vehicle in for a scheduled service you will be provided with an estimate of the cost. We will perform a vehicle report card - a comprehensive health check of your vehicle. You can even book a free loan car² so we can keep you on the road.'''

[[module]]
path='email_modules/spacer/default'
color='white'

	height="30"

[[module]] #Footer AU Social
path='email_modules/footer/au/social'
color='white'


[[module]] #Footer AU Online
path='email_modules/footer/au/online'
color='white'
+++