+++
markets = ["nz"]
title = '''NZ Service Reminder 001 1st-year past due'''

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

	copy='''Hi <%${user.CustomAttribute['FullName']}%>,<br/><br/>This is friendly reminder that you have missed your first annual service. Regular maintenance is essential for the reliability, roadworthiness, and warranty of your vehicle. Keep your Ford running smoothly & hassle free by visiting an authorized Ford Dealership.<br/><br/>Contact us today to arange your service appointment.<br/><br/>Book with <span style="color:#2D96CD"><%${user.CustomAttribute['Dealer_Name']}%></span> on <span style="color:#2D96CD"><%${user.CustomAttribute['Dealer_Phone']}%></span> or email <span style="color:#2D96CD"><% ${user.CustomAttribute['Dealer_Email']} %></span> today.'''
    
[[module]]
path='email_modules/singles/ctablock'
color='''white'''
segmentif = ["(user.CustomAttribute['SERVAPPT'] == 'YES')"]

	cta1_text = '''BOOK A SERVICE'''
	cta1_url = '''https://www.ford.com.au/owners/service/book-service/'''
	cta1_link_name = '''booking'''

[[module]] #4 Images
path = '''email_modules/image/4images'''
color = '''white'''

	image1 = '''nz_edm2_loancar_20170728'''
	image1_url = '''https://www.ford.co.nz/owners/service/?intcmp=bb-fnz-hp-fnz--return/'''
	image1_link_name = '''icon4'''
	image2 = '''nz_edm2_costestimates_20170728'''
	image2_url = '''https://www.ford.co.nz/owners/service/service-estimate/'''
	image2_link_name = '''icon5'''
	image3 = '''nz_edm2_vehiclereport_20170728.jpg'''
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

    copy='''We know how important your <Nameplate> is to you, so we're sure you'll appreciate the many benefits of putting your <Nameplate> in the trusted hands of Ford trained technicians who use diagnostic equipment specifically designed for Fords.<br/>When you book or bring your vehicle in for a scheduled service you will be provided with an estimate1 of the cost. We will perform a vehicle report card - a comprehensive health check of your vehicle. You can even book a free loan car² so we can keep you on the road.'''

[[module]] #AU FordOwner Resources
path='email_modules/custom/fordowner_resources'
color='white'

	cta1_text='''FIND OUT MORE'''
	cta1_url='''https://www.ford.com.au/owner?emailid=20150918-0102_CTAVisitFordOwners_WelcomeNewSep_Generic_0_FOA'''
	cta1_link_name = '''link_name_here'''
	cta1_icon='''more'''

[[module]] #Footer AU Social
path='email_modules/footer/au/social'
color='white'


[[module]] #Footer AU Online
path='email_modules/footer/au/online'
color='white'
+++