+++
markets = ["th"]
title = '''EN Pre Delivery 001 Delay'''
draft = true

[[module]]
path='email_modules/header/logo'
color='white'

	image = '''white'''
	url_link = '''https://www.ford.co.th/en/'''

[[module]]
path = 'email_modules/image/banner_nolink'
color = 'white'

	image = '''FGE_KMI_EN_Delay_20170906'''

[[module]]
path='email_modules/cover/master'
color='white'
font='th'

	copy='''
		Dear [Name],
		<br/>
		<br/>
		We regret to inform you that the delivery of your new Ford [Model] has been a bit delayed due to an unexpected irregularity. We are doing our best to get your car to you at the earliest!
		<br/>
		<br/>
		Your Delivery Consultant will be in touch with you with regular updates.
		<br/>
		<br/>
		As a valued Ford customer, your satisfaction is of paramount importance to us, and we truly regret any inconvenience this delay may cause you. 
		<br/>
		<br/>
		In case if any queries, feel free to contact your Delivery Consultant [Delivery_SalesPerson] <a href="tel:[Delivery_SalesPerson_Phone_No]" style="text-decoration: none;">[Delivery_SalesPerson_Phone_No]</a>.
		<br/>
		<br/>
		Thank you so much for your understanding and patience.
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