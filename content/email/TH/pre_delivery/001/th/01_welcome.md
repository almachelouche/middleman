+++
markets = ["th"]
title = '''TH Pre Delivery 001 Welcome'''

[[module]]
path='email_modules/header/logo'
color='white'

	image = '''white'''
	url_link = '''https://www.ford.co.th/'''

[[module]]
path = 'email_modules/image/banner_nolink'
color = 'white'

	image = '''FGE_KMI_TH_Welcome_20170906'''

[[module]]
path='email_modules/cover/master'
color='white'
font='th'

	copy='''
		เรียน [Name]
		<br/>
		<br/>
		[Branch_Description] ขอขอบพระคุณเป็นอย่างสูงที่ท่านแวะมาเยี่ยมชมโชว์รูมของเราในวันที่ [Opportunity_Creation_Date] นับเป็นเกียรติอย่างยิ่งที่มีโอกาสได้ต้อนรับและให้บริการและเรายินดีเป็นอย่างยิ่งที่ทราบว่าท่านมีความสนใจในรถยนต์ฟอร์ด [Model]
		<br/>
		<br/>
		พนักงานขายที่จะให้บริการท่านในการเดินทางอันน่าตื่นเต้นนี้คือ [SalesPerson] <a href="tel:[SalesPerson_Phone_No]" style="text-decoration: none;">[SalesPerson_Phone_No]</a>.
		<br/>
		<br/>
		หากท่านต้องการข้อมูลหรือความช่วยเหลือเพิ่มเติมใดๆในขณะตัดสินใจซื้อรถยนต์คันนี้ท่านสามารถติดต่อเราได้ทุกเมื่อโดยไม่ต้องกังวล
		<br/>
		<br/>
		หวังเป็นอย่างยิ่งว่าจะได้พบท่านอีกครั้งในเร็วๆนี้
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
path = 'email_modules/image/banner_nolink'
color = 'white'

	image = '''FGE_KMI_TH_Welcome_Car_20170911'''

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