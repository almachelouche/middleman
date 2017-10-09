+++
markets = ["th"]
title = '''TH Pre Delivery 001 Delay'''

[[module]]
path='email_modules/header/logo'
color='white'

	image = '''white'''
	url_link = '''https://www.ford.co.th/'''

[[module]]
path = 'email_modules/image/banner_nolink'
color = 'white'

	image = '''FGE_KMI_TH_Delay_20170906'''

[[module]]
path='email_modules/cover/master'
color='white'
font='th'

	copy='''
		เรียน [Name]
		<br/>
		<br/>
		เราเสียใจเป็นอย่างยิ่งที่ต้องแจ้งให้ท่านทราบว่ารถยนต์ฟอร์ด [Model] คันใหม่ของท่านเกิดความล่าช้าเล็กน้อยอันเนื่องมาจากเหตุการณ์ที่ไม่คาดคิด เรากำลังพยายามอย่างสุดความสามารถที่จะส่งมอบรถยนต์ให้ท่านโดยเร็วที่สุด
		<br/>
		<br/>
		พนักงานส่งมอบรถยนต์จะติดต่อท่านเพื่อแจ้งความคืบหน้าอย่างสม่ำเสมอ
		<br/>
		<br/>
		ในฐานะลูกค้าผู้มีอุปการะคุณของฟอร์ด ความพึงพอใจของท่านมีความสำคัญอย่างสูงสุดต่อเรา และเราเสียใจอย่างสุดซึ้งหากความล่าช้านี้ก่อให้เกิดความยุ่งยากแก่ท่าน 
		<br/>
		<br/>
		หากมีคำถามหรือข้อสงสัยใด ๆ คุณสามารถติดต่อสอบถามพนักงานส่งมอบรถยนต์ของท่านได้ที่ [Delivery_SalesPerson] <a href="tel:[Delivery_SalesPerson_Phone_No]" style="text-decoration: none;">[Delivery_SalesPerson_Phone_No]</a>.
		<br/>
		<br/>
		ขอขอบคุณเป็นอย่างสูงสำหรับความเข้าใจจากท่าน
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