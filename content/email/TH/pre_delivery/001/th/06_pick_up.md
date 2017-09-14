+++
markets = ["th"]
title = '''TH Pre Delivery 001 Pick Up'''

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

	image = '''FGE_KMI_TH_Pick_Up_20170905'''

[[module]]
path = 'email_modules/image/banner_nolink'
color = 'white'

	image = '''FGE_KMI_TH_Journey_Pick_Up_20170908'''

[[module]]
path='email_modules/cover/master'
color='white'
font='th'

	copy='''
		เรียน [Name]
		<br/>
		<br/>
		ท่านสามารถมาที่โชว์รูมจำหน่ายฟอร์ดเพื่อรับมอบรถยนต์ Ford [Model] คันใหม่   เพียงแค่แวะมาแล้วขับรถยนต์คันใหม่ของท่าน
		<br/>
		<br/>
		หากท่านต้องการการจัดเตรียมรถยนต์ [Model] คันใหม่ของท่านให้เหมาะสมกับวิธีการใช้ชีวิตของท่าน สิ่งที่ท่านต้องทำ คือ ติดต่อโชว์รูมจำหน่ายฟอร์ดของท่านที่ [Company_Name] เพื่อให้เจ้าหน้าที่สอนวิธีการระบุความต้องการของท่านเพื่อเตรียมพร้อมของรถ ก่อนส่งมอบให้แด่ท่าน 
		<br/>
		<br/>
		กรุณาเข้าไปที่ <a href="[DFYURL]" style="color: #006fff; text-decoration: underline;">เว็บไซต์ก่อนการส่งมอบ</a> เพื่อเลือกเวลาที่ท่านสะดวกรับมอบรถยนต์ [Model] ของท่าน  และท่านยังสามารถกำหนดรูปแบบเฉพาะสำหรับรถยนต์ของท่านรวมถึงเรียนรู้เกี่ยวกับคุณสมบัติอันยอดเยี่ยมในรถยนต์ของท่าน กรุณาติดต่อพนักงานส่งมอบรถชื่อ [Delivery_SalesPerson] ที่หมายเลข <a href="tel:[Delivery_SalesPerson_Phone_No]" style="text-decoration: none;">[Delivery_SalesPerson_Phone_No]</a> เพื่อตกลงเวลาที่คุณสะดวกในการมารับมอบรถยนต์ [Model] ของท่าน 
		<br/>
		<br/>
		เราหวังว่าท่านจะสนุกกับการขับขี่
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

	image='''FGE_KMI_TH_Contact_20170906'''

[[module]]
path='email_modules/footer/th/social'
color='white'

[[module]]
path='email_modules/footer/th/online'
color='white'
+++