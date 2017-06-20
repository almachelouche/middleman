+++
markets = ["th"]
title = '''TH Lost Customer & PMS Missed 002 All'''

[[module]]
path='email_modules/preheader'


	preheader = '''โปรโมชั่นตรวจเช็คระยะสุดพิเศษ ที่มาพร้อมการบริการทันสมัยและมีประสิทธิภาพที่ศูนย์บริการมาตรฐานฟอร์ด'''

[[module]] #Header Logo
path='email_modules/header/logo'
color='white'

	image = '''white'''
	url_link = '''https://www.ford.co.th/'''

[[module]]
path='email_modules/cover/02'

color='''white'''
icon='''th_edm2_svc_wrench_20170306'''
title='''<span style="font-family:Tahoma, Verdana, Sans-serif">ถึงเวลาบำรุงรักษารถฟอร์ด<br/>ที่คุณรักอีกครั้ง</span>'''
copy='''<span style="font-family:Tahoma, Verdana, Sans-serif">สวัสดีค่ะ คุณ <%InsertIf expression="${(user['FirstName'] == null || user['FirstName'] == '-')}" id="FirstName" %>ท่านลูกค้าฟอร์ด<%/InsertIf%> <%InsertElse%> <%${user['FirstName']}%> <%/InsertElse%><br /><br />
<span style="white-space:nowrap;">ฟอร์ดขอเสนอ</span><span style="white-space:nowrap;">บริการบำรุงรักษา</span><span style="white-space:nowrap;">รถยนต์</span><br />
<span style="white-space:nowrap;"> ตามระยะที่</span><span style="white-space:nowrap;">ศูนย์บริการ</span><span style="white-space:nowrap;">มาตรฐานฟอร์ด</span><span style="white-space:nowrap;">อย่างเต็มรูปแบบ</span> <br />
<span style="white-space:nowrap;">เพื่อการเดินทาง</span><span style="white-space:nowrap;">ที่ราบรื่น</span><span style="white-space:nowrap;">และ</span>
<span style="white-space:nowrap;">มั่นใจ</span><span style="white-space:nowrap;">สำหรับคุณ</span>
<br /><br />
<span style="white-space:nowrap;">คุณสามารถมั่นใจ</span><span style="white-space:nowrap;">กับอะไหล่แท้ฟอร์ด</span><br />
<span style="white-space:nowrap;">ที่ช่วยยืดอายุ</span><span style="white-space:nowrap;">การใช้งาน</span>
<span style="white-space:nowrap;">ของรถฟอร์ด</span><span style="white-space:nowrap;">ที่คุณรักได้!</span>
<br /><br />
<span style="white-space:nowrap;">หมดกังวล</span><span style="white-space:nowrap;">กับทุกปัญหา </span><span style="white-space:nowrap;">ให้คุณอุ่นใจ</span><span style="white-space:nowrap;">ในทุกเส้นทาง</span>
<span style="white-space:nowrap;">รีบแวะเข้ามา</span><span style="white-space:nowrap;">หาเราวันนี้</span><br />
<span style="white-space:nowrap;">ที่ศูนย์บริการฟอร์ด</span><span style="white-space:nowrap;">ทั่วประเทศ!</span><br /><br />
<span style="white-space:nowrap;">นัดหมายล่วงหน้า</span><span style="white-space:nowrap;">เพื่อเข้ารับบริการ</span><span style="white-space:nowrap;">ได้ทันที</span>
<span style="white-space:nowrap;">ติดต่อ <%${user.CustomAttribute['Dealer_Name']}%></span> <span style="white-space:nowrap;">(ระหว่างเวลาทำการ)</span><br />
<span style="white-space:nowrap;">หรือค้นหา</span><span style="white-space:nowrap;">ตัวแทนจำหน่าย</span><br />
<span style="white-space:nowrap;">ใกล้บ้านคุณ</span></span>'''

cta1_text='''<span style="font-family:Tahoma, Verdana, Sans-serif">โทร <%${user.CustomAttribute['Dealer_Phone']}%></span>'''
cta1_url='''tel:<%${user.CustomAttribute['Dealer_Phone']}%>'''
cta2_text='''<span style="font-family:Tahoma, Verdana, Sans-serif">ค้นหาตัวแทนจำหน่าย</span>'''
cta2_url='''https://www.ford.co.th/locate-a-dealer/'''
cta2_link_name='''find_dealer'''


[[module]] #Split 04
path='email_modules/split/04'
color='green'

	title='''<span style="font-family:Tahoma, Verdana, Sans-serif">ประหยัดค่าน้ำมันเครื่อง<br />สูงสุด</span>'''
	copy='''<span style="font-family:Tahoma, Verdana, Sans-serif;">
																	<span style="white-space:nowrap;">เพิ่มความอุ่นใจ</span><span style="white-space:nowrap;">ในการขับขี่ </span><span style="white-space:nowrap;">พิเศษ!</span> 
																		<span style="white-space:nowrap;">รับส่วนลดเพิ่ม </span><span style="white-space:nowrap;">500 บาท</span> 
																		<span style="white-space:nowrap;">เมื่อซื้อโปรแกรม</span><span style="white-space:nowrap;">ชุดน้ำมันเครื่อง</span>
																		<span style="white-space:nowrap;">สุดคุ้ม (OSP)</span> 
																		<span style="white-space:nowrap;">แบบแพคเกจ 3 ครั้ง</span>
																</span>'''
	cta1_text='''<span style="font-family:Tahoma, Verdana, Sans-serif">คลิกเพื่อดูรายละเอียดและราคา</span>'''
cta1_url='''https://www.ford.co.th/owner/oil-save-pack/'''
cta1_icon='''more'''
cta1_link_name = '''OSP'''
image = '''th_edm2_savebigonoil_20170122'''


[[module]] #Custom 01
path='email_modules/custom/3columntitle3icons'
color='white'

	title = '''<span style="font-family:Tahoma, Verdana, Sans-serif">ทำไมต้องศูนย์บริการฟอร์ด?</span>'''
	icon1 = '''ico_2e_fordsvc_a'''
	text1 = '''<span style="font-family:Tahoma, Verdana, Sans-serif"><span style="white-space:nowrap;">มั่นใจอะไหล่แท้ฟอร์ด</span> 
										<span style="white-space:nowrap;">100%</span>
										<span style="white-space:nowrap;">พร้อมการบำรุง</span><span style="white-space:nowrap;">รักษารถยนต์</span>
										<span style="white-space:nowrap;">อย่างมีประสิทธิภาพ</span>เพื่อ
										<span style="white-space:nowrap;">สมรรถนะสูงสุด</span><span style="white-space:nowrap;">ของรถคุณ</span></span>'''
	icon2 = '''ico_2e_fordsvc_b'''
	text2 = '''<span style="font-family:Tahoma, Verdana, Sans-serif"><span style="white-space:nowrap;">ตรวจเช็คด้วย</span><span style="white-space:nowrap;">ช่างเทคนิค</span> 
										<span style="white-space:nowrap;">ฟอร์ด</span><span style="white-space:nowrap;">ที่ผ่านการอบรม</span> 
										<span style="white-space:nowrap;">รวมถึงเครื่องมือ</span><span style="white-space:nowrap;">และอุปกรณ์</span> 
										<span style="white-space:nowrap;">ทันสมัย</span><span style="white-space:nowrap;">ที่ออกแบบมาเพื่อ</span>
										<span style="white-space:nowrap;">รถฟอร์ด</span><span style="white-space:nowrap;">โดยเฉพาะ</span></span>'''
	icon3 = '''ico_2e_fordsvc_c_th'''
	text3 = '''<span style="font-family:Tahoma, Verdana, Sans-serif"><span style="white-space:nowrap;">เก็บบันทึกสถิติ</span><span style="white-space:nowrap;">รถฟอร์ด</span> 
										<span style="white-space:nowrap;">ของคุณอย่าง</span><span style="white-space:nowrap;">เป็นระบบ</span> 
										<span style="white-space:nowrap;">เพื่อเพิ่มมูลค่า</span><span style="white-space:nowrap;">ในการขายต่อ</span></span>'''

[[module]] #Banner Image No Link
path = '''email_modules/image/banner_nolink'''
color = '''white'''

	image = '''th_edm2_whyfordsvc_20161115'''


[[module]] #TH Social
path='email_modules/footer/th/social'
color='white'

[[module]] #TH Online
path='email_modules/footer/th/online'
color='white'
+++