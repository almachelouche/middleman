+++
markets = ["th"]
title = '''EN Pre Delivery 001 Order'''

[[module]]
path='email_modules/preheader'

	preheader = '''โปรโมชั่นตรวจเช็คระยะสุดพิเศษ ที่มาพร้อมการบริการทันสมัยและมีประสิทธิภาพที่ศูนย์บริการมาตรฐานฟอร์ด'''

[[module]]
path='email_modules/header/logo'
color='white'

	image = '''white'''
	url_link = '''https://www.ford.co.th/'''

[[module]]
path = 'email_modules/image/banner_nolink'
color = 'white'

	image = '''FGE_KMI_EN_Ordered_20170906'''

[[module]]
path = 'email_modules/image/banner_nolink'
color = 'white'

	image = '''FGE_KMI_EN_Journey_Order_20170908'''

[[module]]
path='email_modules/cover/master'
color='white'
font='th'

	copy='''
		Dear [Name],
		<br/>
		<br/>
		Congratulations on booking your brand new Ford [Model]! We are so excited to welcome you to the Ford Family and have you as our valued customer.
		<br/>
		<br/>
		Before it arrives at [Company_Name] for your collection, we will let you know where it is at every step of its journey to you. Below are the details of your booking and expected delivery time:
		<br/>
		<br/>
		Expected Delivery Time: [Tentative_Date]
		<br/>
		Model Booked: [Market_Segment_Details]
		<br/>
		Purchased Price: [Total_Amount]
		<br/>
		<br/>
		If you have any questions or concerns about this booking, please don't hesitate to reach out. Here are your contacts:
		<br/>
		<br/>
		Sales Consultant: [SalesPerson_Code] <a href="tel:[SalesPerson_Phone_No]" style="text-decoration: none;">[SalesPerson_Phone_No]</a>
		<br/>
		Delivery Consultant: [Delivery_SalesPerson] <a href="tel:[Delivery_SalesPerson_Phone_No]" style="text-decoration: none;">[Delivery_SalesPerson_Phone_No]</a>
		<br/>
		And as a Ford Owner, you can visit the <a href="https://www.ford.co.th/en/owner/owner-unauthenticated/" style="color: #006fff; text-decoration: underline;">Ford Owner's Site</a> anytime to check out our maintenance, warranty and insurance services.
		<br/>
		<br/>
		Looking forward to take you on this exciting journey!
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
path='email_modules/footer/th/social'
color='white'

[[module]]
path='email_modules/footer/th/online'
color='white'
+++