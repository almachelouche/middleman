+++
markets = ["th"]
title = '''EN Pre Delivery 001 Pick Up'''

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

	image = '''FGE_KMI_EN_Pick_Up_20170905'''

[[module]]
path = 'email_modules/image/mobile_cover_nolink'
color = 'white'

	image = '''FGE_KMI_EN_Journey_Pick_Up_20170908'''

[[module]]
path='email_modules/cover/master'
color='white'
font='th'

	copy='''
		Dear [Name],
		<br/>
		<br/>
		The day has finally come. You can come to the dealership to pick up your new Ford [Model]. Just swing by and hop into your new ride.
		<br/>
		<br/>
		If you want to customize your new [Model] to fit the way you work and play, all you have to do is contact your Ford Dealer [Branch_Description] and they can teach you how to personalize your new car. 
		<br/>
		<br/>
		Visit the <a href="[DFYURL]" style="color: #006fff; text-decoration: underline;">Pre-Delivery Website</a> to select a convenient time for you to come and collect your [Model], and you can also personalize your vehicle settings and learn about your car's cool features. Please contact your Delivery Consultant [Delivery_SalesPerson] at <a href="tel:[Delivery_SalesPerson_Phone_No]" style="text-decoration: none;">[Delivery_SalesPerson_Phone_No]</a> and arrange a convenient time for you to come and collect your [Model]. 
		<br/>
		<br/>
		We hope you enjoy your drive!
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
color='darkblue'
font='th'

	title='''[Branch_Description]'''
	title_align='left'
	copy='''
		[Location_Address]
		<br/>
		<a href="tel:[Location_Contact]" style="color: #ffffff; text-decoration: underline;">[Location_Contact]</a>
	'''
	copy_align='left'
	vertical_align='middle'

	image='''FGE_KMI_TH_Contact_20170906'''

[[module]]
path='email_modules/footer/th/en_social'
color='white'

[[module]]
path='email_modules/footer/th/en_online'
color='white'
+++