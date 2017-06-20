+++
markets = ["th"]
title = '''TH Service Reminder First Due 010 Version B'''
draft = true

[[module]]
path='email_modules/preheader'


	preheader = '''ฟอร์ดขอแจ้งให้คุณทราบว่ารถคันใหม่ของคุณ ถึงกำหนดตรวจเช็คระยะครั้งแรกแล้ว เนื่องจากรถใหม่ทุกคันจะมีระยะในการปรับสภาพการทำงานของรถ เมื่อออกจากโชว์รูมไปวิ่งบนท้องถนน ซึ่งบริการนี้เป็นเพียงการตรวจสอบ เพื่อให้แน่ใจว่ารถของคุณ ทำงานอย่างเต็มสมรรถนะ'''

[[module]] #Header Logo
path='email_modules/header/logo'
color='white'

	image = '''white'''
	url_link = '''https://www.ford.co.th/'''

[[module]]
path='email_modules/cover/02'

color='''fordblue'''
icon='''th_edm2e_svcwrench_20160801'''
title='''Time flies when you’re having fun'''
copy='''Hello <%InsertIf expression="${(user['FirstName'] == null || user['FirstName'] == '-')}" id="FirstName" %>ท่านลูกค้าฟอร์ด<%/InsertIf%> <%InsertElse%> <%${user['FirstName']}%> <%/InsertElse%><br /><br />Just a quick reminder that your new Ranger is due for its first service. All new cars undergo a ‘settling in’ period once they leave the showroom for the open road. <br /><br />This service is just a quick check to ensure that your Ranger is operating at its optimum.<br /><br />It's important to book your service today. Just click below to contact <%${user.CustomAttribute['Dealer_Name']}%> (during business hours) or to find your nearest dealer.'''

cta1_text='''<span style="font-family:Tahoma, Verdana, Sans-serif">CALL <%${user.CustomAttribute['Dealer_Phone']}%></span>'''
cta1_url='''tel:<%${user.CustomAttribute['Dealer_Phone']}%>'''
cta2_text='''<span style="font-family:Tahoma, Verdana, Sans-serif">FIND A DEALER</span>'''
cta2_url='''https://www.ford.co.th/locate-a-dealer/'''
cta2_url_link_name='''find_dealer'''


[[module]] #Custom 01
path='email_modules/custom/3columntitle3icons'
color='white'

	title = '''<span style="font-family:Tahoma, Verdana, Sans-serif">ทำไมต้องศูนย์บริการฟอร์ด?</span>'''
	icon1 = '''ico_2e_fordsvc_a'''
	text1 = '''<span style="font-family:Tahoma, Verdana, Sans-serif"><span style="white-space:nowrap;">มั่นใจอะไหล่แท้ฟอร์ด</span> 
										<span style="white-space:nowrap;">100%</span>
										<span style="white-space:nowrap;">พร้อมการบำรุงรักษารถยนต์</span>
										<span style="white-space:nowrap;">อย่างมีประสิทธิภาพ</span>เพื่อ
										<span style="white-space:nowrap;">สมรรถนะสูงสุดของรถคุณ</span></span>'''
	icon2 = '''ico_2e_fordsvc_b'''
	text2 = '''<span style="font-family:Tahoma, Verdana, Sans-serif"><span style="white-space:nowrap;">ตรวจเช็คด้วยช่างเทคนิค</span> 
										<span style="white-space:nowrap;">ฟอร์ดที่ผ่านการอบรม</span> 
										<span style="white-space:nowrap;">รวมถึงเครื่องมือและอุปกรณ์</span> 
										<span style="white-space:nowrap;">ทันสมัยที่ออกแบบมาเพื่อ</span>
										<span style="white-space:nowrap;">รถฟอร์ดโดยเฉพาะ</span></span>'''
	icon3 = '''ico_2e_fordsvc_c_th'''
	text3 = '''<span style="font-family:Tahoma, Verdana, Sans-serif"><span style="white-space:nowrap;">เก็บบันทึกสถิติรถฟอร์ด</span> 
										<span style="white-space:nowrap;">ของคุณอย่างเป็นระบบ</span> 
										<span style="white-space:nowrap;">เพื่อเพิ่มมูลค่าในการขายต่อ</span></span>'''

[[module]] #Banner Image No Link
path = '''email_modules/image/banner_nolink'''
color = '''white'''

	image = '''th_edm2_whyfordsvc_20161115'''

[[module]] #Split 04
path='email_modules/split/04'
color='green'

	title='''<span style="font-family:Tahoma, Verdana, Sans-serif">ส่วนลดเพิ่มแพคเกจ<br />เช็คระยะ 8%</span>'''
	copy='''<span style="font-family:Tahoma, Verdana, Sans-serif;">
<span style="white-space:nowrap;">รับส่วนลดโปรแกรม SSP เพิ่ม	8%</span><br />
<span style="white-space:nowrap;">หรือสูงสุดถึง 3,000 บาท</span><br />
<span style="white-space:nowrap;">แถมคุณยังสามารถผ่อน 0%</span><br />
<span style="white-space:nowrap;">ได้นานถึง 10 เดือน</span><br />
<span style="white-space:nowrap;">เมื่อใช้บัตรเครดิต K Bank</span><br />
<span style="white-space:nowrap;">สิทธิพิเศษนี้ใช้ได้ถึง</span><br />
<span style="white-space:nowrap;">31 ธันวาคมนี้เท่านั้น</span><br />
</span>'''
	cta1_text='''<span style="font-family:Tahoma, Verdana, Sans-serif">รายละเอียดเพิ่มเติม</span>'''
cta1_url='''https://www.ford.co.th/owner/schedule-service/'''
cta1_icon='''more'''
cta1_link_name = '''SSP'''
image = '''th_edm2_8offssp_20161103'''

[[module]]
path='email_modules/dual/03'
color='white'

title1='''<span style="font-family:Tahoma, Verdana, Sans-serif">นัดหมายเข้ารับบริการ</span>'''
	cta1a_text='''<span style="font-family:Tahoma, Verdana, Sans-serif">ติดต่อ <%${user.CustomAttribute['Dealer_Name']}%><br />ได้ที่ <% ${user.CustomAttribute['Dealer_Phone']} %></span>'''
	cta1a_url='''tel:<%${user.CustomAttribute['Dealer_Phone']}%>'''
	cta1_link_name = ''''''
	cta1b_text='''<span style="font-family:Tahoma, Verdana, Sans-serif">ติค้นหาตัวแทนจำหน่ายใกล้บ้าน<br />คุณ</span>'''
	cta1b_url='''https://www.ford.co.th/locate-a-dealer/'''
	cta1b_link_name = '''find_dealer'''
	icon1='''th_edm2_call_20160801'''

	title2='''<span style="font-family:Tahoma, Verdana, Sans-serif">ศูนย์ข้อมูลเจ้าของรถ</span>'''
	copy2='''<span style="font-family:Tahoma, Verdana, Sans-serif"><span style="color:#616161; font-size:16px">ทุกความช่วยเหลือที่คุณต้องการง่ายๆ</span><br /> 
<span style="color:#616161; font-size:16px">ในที่เดียว</span> 
<span style="white-space:nowrap; color:#616161; font-size:16px"> สำหรับเจ้าของรถฟอร์ดเท่านั้น</span></span>'''
cta2a_text='''<span style="font-family:Tahoma, Verdana, Sans-serif">วิดีโอสาธิตวิธีการใช้งาน<br />คุณสมบัติต่างๆ</span>'''
	cta2a_url='''https://www.ford.co.th/owner/owner-unauthenticated/'''
	cta2a_link_name = '''owner_center'''
	cta2b_text='''<span style="font-family:Tahoma, Verdana, Sans-serif">ผลิตภัณฑ์และบริการของฟอร์ด</span>'''
	cta2b_url='''https://www.ford.co.th/owner/owner-unauthenticated/'''
	cta2b_link_name = '''owner_center'''
	icon2='''th_edm2_ownerprofile_20160801'''

[[module]] #TH Social
path='email_modules/footer/th/social'
color='white'

[[module]] #TH Online
path='email_modules/footer/th/online'
color='white'
+++