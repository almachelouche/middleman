+++
markets = ["th"]
title = '''TH Pre Delivery 001 Pick Up'''

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

	image = '''FGE_KMI_EN_Pick_Up_20170905'''

[[module]]
path = 'email_modules/image/banner_nolink'
color = 'white'

	image = '''FGE_KMI_EN_Journey_Pick_Up_20170905'''

[[module]]
path='email_modules/cover/master'
color='white'
font='th'

	copy='''
		เรียน [Customer_NAME]
		<br/>
		<br/>
		ในที่สุดวันนี้ก็มาถึง คุณสามารถมาที่ตัวแทนจำหน่ายเพื่อรับมอบรถยนต์ Ford [NAMEPLATE] คันใหม่ของคุณ
		<br/>
		เพียงแค่แวะมาแล้วขึ้นขับรถยนต์คันใหม่ของคุณ
		<br/>
		<br/>
		หากคุณต้องการปรับแต่ง [NAMEPLATE] คันใหม่ของคุณให้เหมาะสมกับวิธีการทำงานและการใช้ชีวิตส่วนตัวของคุณ
		<br/>
		สิ่งที่คุณต้องทำ คือ ติดต่อตัวแทนจำหน่ายฟอร์ดของคุณที่ [DEALERSHIP_Name]
		<br/>
		เพื่อให้เจ้าหน้าที่สอนวิธีการกำหนดรูปแบบเฉพาะเพื่อให้รถคันใหม่เหมาะกับคุณ
		<br/>
		<br/>
		กรุณาเข้าไปที่<a href="" style="color: #006fff; text-decoration: underline;">เว็บไซต์ก่อนการส่งมอบ</a>เพื่อเลือกเวลาที่คุณสะดวกรับมอบรถยนต์ [NAMEPLATE] ของคุณ
		<br/>
		และคุณยังสามารถกำหนดรูปแบบเฉพาะสำหรับรถยนต์ของคุณรวมถึงเรียนรู้เกี่ยวกับคุณสมบัติอันยอดเยี่ยมในรถยนต์ของคุณ
		<br/>
		กรุณาติดต่อพนักงานส่งมอบรถชื่อ [Delivery_Consultant_NAME] ที่หมายเลข [DC_NUMBER]
		<br/>
		เพื่อตกลงเวลาที่คุณสะดวกในการมารับมอบรถยนต์ [NAMEPLATE] ของคุณ
		<br/>
		<br/>
		เราหวังว่าคุณจะสนุกกับการขับขี่
		<br/>
		ขอแสดงความนับถือ
		<br/>
		<br/>
		[GM_NAME]
		<br/>
		<a href="tel:[GM_Mobile_No.]" style="text-decoration: none;">[GM_Mobile_No.]</a>
	'''
	copy_align='left'

[[module]]
path='email_modules/split/master/right'
color='green'
font='th'

	title='''[Dealer_NAME]'''
	title_align='left'
	copy='''
		[Outlet_Address]
		<br/>
		<a href="tel:[Dealer_Phone_No.]" style="color: #ffffff; text-decoration: underline;">[Dealer_Phone_No.]</a>
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