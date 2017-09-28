+++
markets = ["au"]
title = '''AU Service Reminder 003 opt-out mock up nonxtime'''

[[module]]
path='email_modules/preheader'

	preheader='''Don't get stuck without wheels. Book a Free Loan Car with your <%${user.CustomAttribute['Model']}%>'s scheduled service.'''


[[module]]
path='email_modules/image/banner'
color='white'

	image = '''au_edm2_svc_new_banner_20170926'''
	url_link = '''https://www.ford.com.au/owners/service/'''

[[module]]
path='email_modules/spacer/default'
color='white'

	height="30"

[[module]]
path='email_modules/singles/copy'
color='''white'''

	copy = '''
		Hi <%${user.CustomAttribute['FullName']}%>,
		<br />
		<br />
		This is just a friendly reminder that your Ford <%${user.CustomAttribute['Model']}%> is nearly due for its <%${user.CustomAttribute['Service_Interval']}%>km service.
		<br />
		<br />
    	We know how important your <%${user.CustomAttribute['Model']}%></span> is to you, so we're sure you'll appreciate the many benefits of putting your <%${user.CustomAttribute['Model']}%></span> in the trusted hands of Ford trained technicians. 
    	<br />
    	<br />
    	Book your service with <span style="color:#2D96CD"><%${user.CustomAttribute['Dealer_Name']}%></span> on <span style="color:#2D96CD"><%${user.CustomAttribute['Dealer_Phone']}%></span> today, or find your <a href="https://www.ford.com.au/dealership/" style="text-decoration:underline; color:#2D96CD">nearest dealer</a>.
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

     text_box_height = '''240'''
	title1 = '''Genuine Service'''
	copy1 = '''We know how important your <Nameplate> is to you, so we're sure you'll appreciate that our factory-trained technicians only use Genuine Ford parts and equipment.'''
	cta1a_text = '''Learn More'''
	cta1a_url = '''http://genuineisbest.com.au/'''
	cta1a_link_name = '''LearnMore'''
	image1 = '''au_edm2_genuine_service_20170818'''
	image1_link_url = '''http://genuineisbest.com.au/'''
	image1_link_name = '''Some'''
	title2 = '''Vehicle Health Report'''
	copy2 = '''To help you better understand your vehicle's condition, you'll receive a comprehensive vehicle health report every time you service.'''
	image2 = '''au_edm2_vehicle_health_report_20170818'''
	image2_link_url = '''https://www.ford.com.au/owners/service/vehicle-report-card'''
	image2_link_name = '''Some'''
    cta2a_text = '''Learn More'''
	cta2a_url = '''https://www.ford.com.au/owners/service/vehicle-report-card'''
	cta2a_link_name = '''healthreport'''

[[module]]
path='email_modules/footer/au/social'
color='white'

[[module]]
path='email_modules/footer/disclaimer'
color='white'

	text = '''DISCLAIMERS:
                <br /> <br /> 
                '''

[[module]]
path='email_modules/footer/au/online'
color='white'

+++