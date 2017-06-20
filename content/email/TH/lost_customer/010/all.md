+++
markets = ["th"]
title = '''TH Lost Customer & PMS Missed 010 All'''

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
title='''Your Ford may need attention'''
copy='''Hi <%InsertIf expression="${(user['FirstName'] == null || user['FirstName'] == '-')}" id="FirstName" %>ท่านลูกค้าฟอร์ด<%/InsertIf%> <%InsertElse%> <%${user['FirstName']}%> <%/InsertElse%><br /><br />We noticed that your Ford hasn’t been fully serviced lately. To stay safe on the road, it’s important that you follow your service plan and replace worn-out parts as soon as possible.<br /><br />Replacing old parts – like oil filters – helps prolong the life of your Ford.<br /><br />Ensure the road ahead is smooth and worry-free. Visit a Ford dealer for service and maintenance soon.<br /><br />It's important to book your service today. Just click below to contact <%${user.CustomAttribute['Dealer_Name']}%> (during business hours) or to find your nearest dealer.'''

cta1_text='''<span style="font-family:Tahoma, Verdana, Sans-serif">CALL <%${user.CustomAttribute['Dealer_Phone']}%></span>'''
cta1_url='''tel:<%${user.CustomAttribute['Dealer_Phone']}%>'''
cta2_text='''FIND A DEALER'''
cta2_url='''https://www.ford.co.th/locate-a-dealer/'''
cta2_url_link_name='''find_dealer'''


[[module]] #Split 04
path='email_modules/split/04'
color='green'

	title='''<span style="font-family:Tahoma, Verdana, Sans-serif">ประหยัดกับชุดน้ำมันเครื่อง<br />สุดคุ้ม</span>'''
	copy='''<span style="font-family:Tahoma, Verdana, Sans-serif;">
<span style="white-space:nowrap">ฟอร์ดใจดีมอบส่วนลดมูลค่า 300 บาท</span>
<span style="white-space:nowrap">เมื่อซื้อโปรแกรมชุดน้ำมันเครื่องสุดคุ้ม</span>
<span style="white-space:nowrap">แพ็คเกจใดก็ได้</span>
<span style="white-space:nowrap">ซื้อวันนี้ประหยัดทันที</span>
</span>'''
	cta1_text='''<span style="font-family:Tahoma, Verdana, Sans-serif">คลิกเพื่อดูรายละเอียดและราคา</span>'''
cta1_url='''https://www.ford.co.th/owner/oil-save-pack/'''
cta1_icon='''more'''
cta1_link_name = '''OSP'''
image = '''th_edm2_savebigonoil_20160801'''


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


[[module]] #TH Social
path='email_modules/footer/th/social'
color='white'

[[module]] #TH Online
path='email_modules/footer/th/online'
color='white'
+++