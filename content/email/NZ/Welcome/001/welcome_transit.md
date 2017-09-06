+++
markets = ["nz"]
title = '''NZ Welcome 001 transit'''

[[module]]
path='email_modules/preheaderbefore'

segmentif = ["(user.CustomAttribute['NewRepeat'] == 'R')"]

	preheader='''Dear <%${user.CustomAttribute['FullName']}%>, thank you for again choosing Ford.'''

[[module]]
path='email_modules/preheaderbefore'

segmentelse = ["(user.CustomAttribute['NewRepeat'] == 'N')"]

	preheader='''Dear <%${user.CustomAttribute['FullName']}%>, welcome to the Ford Family.'''

[[module]] #Banner Image
path='email_modules/image/banner'
color='white'

	image='''nz_edm1_transit_custom_20170612'''
	url_link='''https://www.ford.co.nz/'''
	url_link_name='''transit'''

[[module]]
path='email_modules/spacer/default'
color='white'

	height="30"
    
[[module]]
path='email_modules/singles/copy'
color='''white'''
segmentif = ["(user.CustomAttribute['NewRepeat'] == 'R')"]

	copy='''Dear <%${user.CustomAttribute['FullName']}%><br /><br />Thank you for again choosing Ford. We hope you are enjoying the experience of being part of the Ford family with your new Transit.<br/><br />'''

[[module]]
path='email_modules/singles/copy'
color='''white'''
segmentif = ["(user.CustomAttribute['NewRepeat'] == 'N')"]

    copy='''Dear <%${user.CustomAttribute['FullName']}%><br /><br />Welcome to the Ford Family. We would like to thank you for choosing Ford and hope that you are enjoying the experience.<br /><br />'''

[[module]]
path='email_modules/singles/copy'
color='''white'''


    copy='''Did you know your new <%${user.CustomAttribute['Model']}%> is as safe as it is smart? Not only does it deliver innovative driver assistance technologies, it also brings the latest in-car communication technologies to New Zealand drivers.'''

[[module]]
path='email_modules/spacer/default'
color='white'

	height="30"
    
 [[module]] #Banner Image No Link
path = '''email_modules/image/banner_nolink'''
color = '''white'''

	image = '''nz_edm2_svc2_20170612'''

[[module]] #Cover 01 
path='email_modules/cover/01'
color='white'

	title='''Stay connected. Everywhere.'''
	copy='''Your <%${user.CustomAttribute['Model']}%> is equipped with Ford’s <a href="https://www.ford.co.nz/technology/sync/" name="sync" style="text-decoration:underline; color:#2D96CD">SYNC® infotainment system</a>. Use simple voice commands for hands-free control of your phone, your music, and satellite navigation. Best of all, your hands stay safely on the wheel and your eyes stay on the road ahead.<br />'''

[[module]] #Banner Image
path='email_modules/image/banner'
color='white'

	image = '''nz_edm2_svc1_20170612'''
    url_link='''https://www.ford.co.nz/owners/service/?intcmp=bb-fnz-hp-fnz--return/'''
	url_link_name='''service'''


[[module]] #Cover 01 
path='email_modules/cover/01'
color='white'

 title='''Peace of mind comes standard'''
	copy='''Your new <%${user.CustomAttribute['Model']}%> includes a 3-year/100,000km warranty, 3-year roadside assistance, and 12-month/30,000km service intervals (whichever occurs first).<br /><br />You will also receive an email from us within the next two months reminding you to book your Peace of Mind checkup. This is a quick, complimentary inspection to ensure that you are happy with how your vehicle is running. It also provides an opportunity to discuss any questions or concerns you may have about your new <%${user.CustomAttribute['Model']}%>.'''

[[module]] #Cover 01
path='email_modules/cover/01'
color='''fordblue'''

	icon='''au_edm1_welcome_icon_20161019'''
	title='''Can we help?'''
	copy='''Our Ford Customer Assistance Team is always available to assist with any questions you may have. Contacted them on <br/><span style="color:#FFFFFF">0800 Ford NZ (0200 367 369)</span>.'''

[[module]] #Footer NZ Social
path='email_modules/footer/nz/social'
color='white'


[[module]] #Footer NZ Online
path='email_modules/footer/nz/online'
color='white'
+++
