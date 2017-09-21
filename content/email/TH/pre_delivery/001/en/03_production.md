+++
markets = ["th"]
title = '''EN Pre Delivery 001 Production'''
draft = true

[[module]]
path='email_modules/split/master/right'
color='white'
font='th'

	copy='''
		<span style="color: #425968; font-weight:800; font-size: 12px;">Estimated Delivery Time</span>
		<br/>
		<span style="color: #ff6600; font-weight:800;">[Tentative_Date]</span>
	'''
	copy_align='right'
	vertical_align='top'

	image='''white_logo'''
	image_link_url='''https://www.ford.co.th/en/'''
	image_link_name='''Ford Logo'''

[[module]]
path = 'email_modules/image/banner_nolink'
color = 'white'

	image = '''FGE_KMI_EN_Production_20170906'''

[[module]]
path = 'email_modules/image/mobile_cover_nolink'
color = 'white'

	image = '''FGE_KMI_EN_Journey_Production_20170908'''

[[module]]
path='email_modules/cover/master'
color='white'
font='th'

	copy='''
		Dear [Name],
		<br/>
		<br/>
		Your Ford [Model] is under production, which means you're a step closer to getting behind the wheel and hitting the open road. 
		<br/>
		<br/>
		In the meantime, why not get acquainted with your new car's smart and cool features by visiting our product website.
		<br/>
		<a href="https://www.ford.co.th/en/vehicles/" style="color: #006fff; text-decoration: underline;">https://www.ford.co.th/en/vehicles/</a>
		<br/>
		<br/>
		We hope you're getting excited, because we know we are!
		<br/>
		Sincerely,
		<br/>
		[GMEmployeeName]
		<br/>
		<a href="tel:[GMEmployeeMobile_Phone_No]" style="text-decoration: none;">[GMEmployeeMobile_Phone_No]</a>
	'''
	copy_align='left'

[[module]]
path='email_modules/split/master/right'
color='green'
font='th'

	title='''[Dealer_NAME]'''
	title_align='left'
	copy='''
		[Location_Address]
		<br/>
		<a href="tel:[Location_Contact]" style="color: #ffffff; text-decoration: underline;">[Location_Contact]</a>
	'''
	copy_align='left'
	vertical_align='middle'

	image='''FGE_KMI_EN_Contact_20170905'''

[[module]]
path='email_modules/footer/th/en_social'
color='white'

[[module]]
path='email_modules/footer/th/en_online'
color='white'
+++