+++
markets = ["th"]
title = '''TH Pre Delivery 001 Welcome'''

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

	image = '''FGE_KMI_TH_Welcome_20170906'''

[[module]]
path='email_modules/cover/master'
color='white'
font='th'

	copy='''
		Dear [Name],
		<br/>
		<br/>
		Greetings from [Company_Name]. Thanks for stopping by our showroom on [Opportunity_Creation_Date]. It was great meeting you, and we're so happy to hear that you're interested in the Ford [Model]. 
		<br/>
		<br/>
		Your Sales Consultant for this exciting journey will be [SalesPerson_Code] <a href="tel:[SalesPerson_Phone_No]" style="text-decoration: none;">[SalesPerson_Phone_No]</a>.
		<br/>
		<br/>
		Please feel free to contact us if you need any further information or help as you make this purchase decision. 
		<br/>
		<br/>
		Hope to see you again soon!
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
path = 'email_modules/image/banner_nolink'
color = 'white'

	image = '''FGE_KMI_TH_Welcome_Car_20170911'''

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

	image='''FGE_KMI_TH_Contact_20170905'''

[[module]]
path='email_modules/footer/th/social'
color='white'

[[module]]
path='email_modules/footer/th/online'
color='white'
+++