+++
markets = ["th"]
title = '''TH Pre Delivery 001 Production'''

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

	image = '''FGE_KMI_TH_Production_20170906'''

[[module]]
path = 'email_modules/image/mobile_cover_nolink'
color = 'white'

	image = '''FGE_KMI_TH_Journey_Production_20170908'''

[[module]]
path='email_modules/cover/master'
color='white'
font='th'

	copy='''
		เรียน [Name]
		<br/>
		<br/>
		รถยนต์ฟอร์ด [Model] ของท่านกำลังอยู่ในขั้นตอนการผลิตนั่นหมายความว่าท่านใกล้จะได้ขับขี่และได้เริ่มออกเดินทางกับรถยนต์คันใหม่ของท่าน 
		<br/>
		<br/>
		ในระหว่างนี้ท่านควรทำความรู้จักกับคุณสมบัติอันชาญฉลาดและเป็นเลิศของรถยนต์คันใหม่ของท่านด้วยการเข้าไปที่เว็บไซต์ผลิตภัณฑ์ของเรา
		<br/>
		<a href="https://www.ford.co.th/vehicles/" style="color: #006fff; text-decoration: underline;">https://www.ford.co.th/vehicles/</a>
		<br/>
		<br/>
		ท่านกำลังเริ่มรู้สึกตื่นเต้นเพราะตอนนี้เราก็รู้สึกเช่นกัน
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

	title='''[Dealer_NAME]'''
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