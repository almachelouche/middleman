+++
markets = ["th"]
title = '''TH Pre Delivery 001 Transit'''

[[module]]
path='email_modules/split/master/right'
color='white'
font='th'

	copy='''
		<span style="color: #425968; font-weight:800; font-size: 12px;">ช่วงเวลาที่คาดว่าจะมีการส่งมอบ</span>
		<br/>
		<span style="color: #ff6600; font-weight:800;">[Tentative_Date]</span>
	'''
	copy_align='right'
	vertical_align='top'

	image='''white_logo'''
	image_link_url='''https://www.ford.co.th/'''
	image_link_name='''Ford Logo'''

[[module]]
path = 'email_modules/image/banner_nolink'
color = 'white'

	image = '''FGE_KMI_TH_Transit_20170906'''

[[module]]
path = 'email_modules/image/mobile_cover_nolink'
color = 'white'

	image = '''FGE_KMI_TH_Journey_Transit_20170908'''

[[module]]
path='email_modules/cover/master'
color='white'
font='th'

	copy='''
		เรียน [Name]
		<br/>
		<br/>
		รถยนต์ฟอร์ด [Model] คันใหม่ของท่านกำลังเดินทางมาถึงแล้วในขณะนี้คุณไม่ได้กำลังฝันไปแต่กำลังเกิดขึ้นจริง 
		<br/>
		<br/>
		อย่าลืม หากท่านมีคำถามหรือข้อสงสัยใดๆคุณสามารถติดต่อเราได้ทันทีเราอยู่ที่นี่เพื่อคอยช่วยเหลือท่านข้อมูลสำหรับการติดต่อ:
		<br/>
		<br/>
		พนักงานขาย: [SalesPerson] <a href="tel:[SalesPerson_Phone_No]" style="text-decoration: none;">[SalesPerson_Phone_No]</a>
		<br/>
		พนักงานส่งมอบรถ: [Delivery_SalesPerson] <a href="tel:[Delivery_SalesPerson_Phone_No]" style="text-decoration: none;">[Delivery_SalesPerson_Phone_No]</a>
		<br/>
		<br/>
		รถของท่านกำลังจัดส่งมาและเราแทบจะเก็บความตื่นเต้นไว้ไม่ได้
		<br/>
		<br/>
		ขอแสดงความนับถือ
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
path='email_modules/footer/th/social'
color='white'

[[module]]
path='email_modules/footer/th/online'
color='white'
+++