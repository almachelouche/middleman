+++
markets = ["th"]
title = '''TH Service Reminder First Past Due 005 UPC'''
draft = true

[[module]]
path='email_modules/preheader'


	preheader = '''พบข้อเสนอสุดพิเศษกับโปรแกรมบำรุงรักษารถยนต์ตามระยะ (SSP)'''

[[module]] #Header Logo
path='email_modules/header/logo'
color='white'

	image = '''white'''
	url_link = '''https://www.ford.co.th/'''

[[module]]
path='email_modules/cover/02'

color='''white'''
icon='''th_edm2_svc_wrench_urgent_20160801'''
title='''<span style="color:#ff6600;font-family:Tahoma, Verdana, Sans-serif">รถ <%${user.CustomAttribute['Model']}%> ของคุณ เลยเวลาเช็คระยะแล้ว</span>'''
copy='''<span style="font-family:Tahoma, Verdana, Sans-serif">สวัสดีคุณ <%InsertIf expression="${(user['FirstName'] == null || user['FirstName'] == '-')}" id="FirstName" %>ท่านลูกค้าฟอร์ด <%/InsertIf%> <%InsertElse%> <%${user['FirstName']}%> <%/InsertElse%></span><br /><br />

 <span style="font-family:Tahoma, Verdana, Sans-serif">
						<span style="white-space:nowrap;">เพื่อรักษารถ &lt;%${user.CustomAttribute['Model']}%&gt;</span> 
						<span style="white-space:nowrap;">ของคุณให้อยู่ในสภาพดี</span>
						<span style="white-space:nowrap;">และวิ่งได้อย่าง</span>เต็ม<span style="white-space:nowrap;">ประสิทธิภาพสม่ำเสมอ</span> 
						<span style="white-space:nowrap;">อย่าลืมนำรถเข้าศูนย์บริการ</span>
						<span style="white-space:nowrap;">เพื่อตรวจเช็คระยะเมื่อครบกำหนด</span>
					</span>
<br /><br />
<span style="font-family:Tahoma, Verdana, Sans-serif">
		<span style="white-space:nowrap;">นัดหมายล่วงหน้า</span>เพื่อ<span style="white-space:nowrap;">เข้ารับบริการได้ทันที</span> <br />
		<span style="white-space:nowrap;">ติดต่อ <%${user.CustomAttribute['Dealer_Name']}%></span> <span style="white-space:nowrap;">(ระหว่างเวลาทำการ)</span><br />
		<span style="white-space:nowrap;">หรือค้นหาตัวแทนจำหน่าย</span><br />
		<span style="white-space:nowrap;">ใกล้บ้านคุณ</span>
 </span>'''

cta1_text='''<span style="font-family:Tahoma, Verdana, Sans-serif">โทร <%${user.CustomAttribute['Dealer_Phone']}%></span>'''
cta1_url='''tel:<%${user.CustomAttribute['Dealer_Phone']}%>'''
cta2_text='''<span style="font-family:Tahoma, Verdana, Sans-serif">ค้นหาตัวแทนจำหน่าย</span>'''
cta2_url='''https://www.ford.co.th/locate-a-dealer/'''
cta2_link_name='''find_dealer'''


[[module]] #Split 04
path='email_modules/split/04'
color='green'

	title='''<span style="font-family:Tahoma, Verdana, Sans-serif">ประหยัดและคุ้มค่ากว่า </span>'''
	copy='''<span style="font-family:Tahoma, Verdana, Sans-serif;">
<span style="white-space:nowrap;">รับส่วนลดเพิ่มสูงสุด 10%</span>
<span style="white-space:nowrap;">หรือ 3,700 บาท</span> 
<span style="white-space:nowrap;">กับโปรแกรมบำรุงรักษารถยนต์</span>
<span style="white-space:nowrap;">ตามระยะ(SSP)</span>
<span style="white-space:nowrap;">พิเศษรับสิทธิ์</span>
<span style="white-space:nowrap;">ผ่อน 0% นาน 10 เดือน</span> 
<span style="white-space:nowrap;">เมื่อชำระผ่าน</span>
<span style="white-space:nowrap;">บัตรเครดิตกสิกรไทย</span> 
<span style="white-space:nowrap;">ตั้งแต่วันนี้ - วันที่ 31 สิงหาคม 2560</span>
</span>'''
	cta1_text='''<span style="font-family:Tahoma, Verdana, Sans-serif">คลิกเพื่อดูรายละเอียดและราคา ></span>'''
cta1_url='''https://www.ford.co.th/owner/schedule-service/'''
cta1_icon='''more'''
cta1_link_name = '''SSP'''
image = '''th_edm5a_specialoffer_20160801'''


[[module]] #TH Social
path='email_modules/footer/th/social'
color='white'

[[module]] #TH Online
path='email_modules/footer/th/online'
color='white'
+++