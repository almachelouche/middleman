+++
markets = ["th"]
title = '''TH Pre Delivery 001 Arrived'''

[[module]]
path='email_modules/header/logo'
color='white'

	image = '''white'''
	url_link = '''https://www.ford.co.th/'''

[[module]]
path = 'email_modules/image/banner_nolink'
color = 'white'

	image = '''FGE_KMI_TH_Arrived_20170906'''

[[module]]
path = 'email_modules/image/banner_nolink'
color = 'white'

	image = '''FGE_KMI_TH_Journey_Arrived_20170908'''

[[module]]
path='email_modules/cover/master'
color='white'
font='th'

	copy='''
		เรียน [Name]
		<br/>
		<br/>
		รถยนต์ฟอร์ด [Model] คันใหม่ของท่านมาถึงแล้ว และกำลังรอท่านอยู่ที่ [Company_Name] คุณได้กลิ่นสีและกลิ่นรถใหม่แล้วท่านหรือยัง
		<br/>
		<br/>
		เตรียมตัวให้พร้อมเพื่อต้อนรับรถยนต์ฟอร์ด [Model] คันใหม่เข้าไปในชีวิตท่านแต่ก่อนอื่นเราขอแนะนำให้ท่านเริ่มทำความรู้จักกับคุณสมบัติอันยอดเยี่ยมในรถของท่านด้วยการเข้าไปที่เว็บไซต์ผลิตภัณฑ์ของเรา
		<br/>
		<a href="https://www.ford.co.th/vehicles/" style="color: #006fff; text-decoration: underline;">https://www.ford.co.th/vehicles/</a>
		<br/>
		<br/>
		เราหวังว่าท่านจะรู้สึกตื่นเต้นกับการได้พบรถยนต์ฟอร์ด [Model] คันใหม่ของท่าน
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