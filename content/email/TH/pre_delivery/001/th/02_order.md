+++
markets = ["th"]
title = '''TH Pre Delivery 001 Order'''

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

	image = '''FGE_KMI_TH_Ordered_20170906'''

[[module]]
path = 'email_modules/image/mobile_cover_nolink'
color = 'white'

	image = '''FGE_KMI_TH_Journey_Ordered_20170908'''

[[module]]
path='email_modules/cover/master'
color='white'
font='th'

	copy='''
		เรียน [Name]
		<br/>
		<br/>
		ขอแสดงความยินดีกับการจองรถยนต์ฟอร์ด [Model] คันใหม่ของท่านเราตื่นเต้นมากที่จะได้ต้อนรับท่านเข้าสู่ครอบครัวฟอร์ดและเป็นลูกค้าคนสำคัญของเรา
		<br/>
		<br/>
		ก่อนที่รถยนต์จะมาถึง [Company_Name] เพื่อส่งมอบแก่ท่านเราจะแจ้งการจัดส่งของรถยนต์คันนี้ให้ท่านทราบในทุกขั้นตอนด้านล่างนี้เป็นข้อมูลการจองของท่านและช่วงเวลาที่คาดว่าจะมีการส่งมอบ:
		<br/>
		<br/>
		ช่วงเวลาที่คาดว่าจะมีการส่งมอบ: [Tentative_Date]
		<br/>
		รุ่นที่จอง: [Market_Segment_Details]
		<br/>
		ราคาซื้อ: [Total_Amount]
		<br/>
		<br/>
		หากท่านมีคำถามหรือข้อสงสัยใดๆเกี่ยวกับการจองนี้ท่านสามารถติดต่อเราได้ทันทีข้อมูลสำหรับการติดต่อ:
		<br/>
		<br/>
		พนักงานขาย: [SalesPerson_Code] <a href="tel:[SalesPerson_Phone_No]" style="text-decoration: none;">[SalesPerson_Phone_No]</a>
		<br/>
		พนักงานส่งมอบรถ: [Delivery_SalesPerson] <a href="tel:[Delivery_SalesPerson_Phone_No]" style="text-decoration: none;">[Delivery_SalesPerson_Phone_No]</a>
		<br/>
		และในฐานะเจ้าของรถยนต์ฟอร์ดท่านสามารถเข้าไปที่เว็บไซต์ <a href="https://www.ford.co.th/owner/owner-unauthenticated/" style="color: #006fff; text-decoration: underline;">Ford Owner's Site</a> ได้ทุกเมื่อเพื่อตรวจสอบบริการการซ่อมบำรุงการรับประกัน และการประกันภัยของเรา
		<br/>
		<br/>
		หวังเป็นอย่างยิ่งว่าจะได้นำท่านไปสู่การเดินทางอันน่าตื่นเต้นนี้
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