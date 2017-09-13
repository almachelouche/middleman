+++
markets = ["th"]
title = '''EN Pre Delivery 001 Transit'''

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

	image = '''FGE_KMI_EN_Transit_20170906'''

[[module]]
path = 'email_modules/image/banner_nolink'
color = 'white'

	image = '''FGE_KMI_EN_Journey_Transit_20170908'''

[[module]]
path='email_modules/cover/master'
color='white'
font='th'

	copy='''
		Dear [Name],
		<br/>
		<br/>
		Your new Ford [Model] is on its way to you as we speak! Yes. You're not dreaming. It's really happening! 
		<br/>
		<br/>
		Remember, if you have any questions or concerns, don't hesitate to reach out. We are here to help you. Here are your contacts:
		<br/>
		<br/>
		Sales Consultant: [SalesPerson_Code] <a href="tel:[SalesPerson_Phone_No]" style="text-decoration: none;">[SalesPerson_Phone_No]</a>
		<br/>
		Delivery Consultant: [Delivery_SalesPerson] <a href="tel:[Delivery_SalesPerson_Phone_No]" style="text-decoration: none;">[Delivery_SalesPerson_Phone_No]</a>
		<br/>
		<br/>
		It's on its way and we can hardly contain our excitement!
		<br/>
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