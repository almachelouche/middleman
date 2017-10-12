+++
markets = ["th"]
title = '''TH Pre Delivery 001 Finished'''

[[module]]
path='email_modules/header/logo'
color='white'

	image = '''white'''
	url_link = '''https://www.ford.co.th/'''

[[module]]
path = 'email_modules/image/banner_nolink'
color = 'white'

	image = '''FGE_KMI_TH_Finished_20170906'''

[[module]]
path = 'email_modules/image/mobile_cover_nolink'
color = 'white'

	image = '''FGE_KMI_TH_Journey_Finished_20170908'''

[[module]]
path='email_modules/cover/master'
color='white'
font='th'

	copy='''
		เรียน [Name]
		<br/>
		<br/>
		ก่อนอื่น ขอแสดงความยินดีครั้งสำคัญสำหรับการซื้อรถยนต์ฟอร์ด [Model] คันใหม่ของท่าน เราเชื่อว่าท่าน ครอบครัว และเพื่อนของท่านจะสนุกกับปีแห่งการเดินทางและการได้เป็นเจ้าของรถยนต์ฟอร์ดอย่างมีความสุขในฐานะสมาชิกคนสำคัญของครอบครัวฟอร์ด 
		<br/>
		<br/>
		ในโอกาสนี้พวกเราทุกคนที่ [Branch_Description] ต่างมุ่งมั่นอย่างเต็มที่ที่จะให้บริการท่านอย่างใกล้ชิด และมอบประสบการณ์ในแบบที่ท่านต้องการ  และจะได้รับจากแบรนด์ฟอร์ดและจากบริการของโชว์รูมผู้จำหน่ายของเรา
		<br/>
		<br/>
		เราหวังเป็นอย่างยิ่งว่าจะได้มอบบริการอันสุดพิเศษ แด่ลูกค้าคนสำคัญของเรา
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
path='email_modules/footer/th/social'
color='white'

[[module]]
path='email_modules/footer/th/online'
color='white'
+++