+++
markets = ["th"]
title = '''TH Service Reminder First Past Due 005 BKK'''
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
copy='''<span style="font-family:Tahoma, Verdana, Sans-serif">สวัสดีคุณ <%InsertIf expression="${(user['FirstName'] == null || user['FirstName'] == '-')}" id="FirstName" %>ท่านลูกค้าฟอร์ด<%/InsertIf%> <%InsertElse%> <%${user['FirstName']}%> <%/InsertElse%></span><br /><br />
<span style="font-family:Tahoma, Verdana, Sans-serif">
						<span style="white-space:nowrap;">เพื่อรักษารถ <%${user.CustomAttribute['Model']}%></span> 
						<span style="white-space:nowrap;">ของคุณให้อยู่ในสภาพดี</span>
						<span style="white-space:nowrap;">และวิ่งได้อย่าง</span>เต็ม<span style="white-space:nowrap;">ประสิทธิภาพสม่ำเสมอ</span> 
						<span style="white-space:nowrap;">อย่าลืมนำรถเข้าศูนย์บริการ</span>
						<span style="white-space:nowrap;">เพื่อตรวจเช็คระยะเมื่อครบกำหนด</span>
					</span>
<br /><br />
 <span style="white-space:nowrap;font-family:Tahoma, Verdana, Sans-serif">อย่าลืม! จองคิวเช็คระยะเลยวันนี้</span> 
<br /><br />
<span style="font-family:Tahoma, Verdana, Sans-serif">
<span style="white-space:nowrap;">บริการใหม่!!</span> 
<span style="white-space:nowrap;">ฟอร์ดเพิ่มความสะดวกสบาย</span>
<span style="white-space:nowrap;">ให้คุณสามารถนัดหมายเช็คระยะ</span>ที่<span style="white-space:nowrap;">ศูนย์บริการฟอร์ดง่ายๆ</span>
<span style="white-space:nowrap;">ผ่านระบบ</span> 
<span style="white-space:nowrap;">Online Booking</span> 
<span style="white-space:nowrap;">ตลอด 7 วัน</span><br />
<span style="white-space:nowrap;">พร้อมการรับประกันเช็ค</span>
</span>ระยะภายใน 60	นาที</span>
<span style="white-space:nowrap;">หากไม่ทัน</span><br />
<span style="white-space:nowrap;">คุณจะได้รับบริการเช็คระยะครั้งนั้น</span> 
<span style="white-space:nowrap;">"ฟรีทันที"</span>
</span>'''
cta1_text='''<span style="font-family:Tahoma, Verdana, Sans-serif">นัดหมายตอนนี้</span>'''
cta1_url='''https://onlinebooking.ford.co.th/'''
cta1_link_name = '''book_now'''


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
<span style="white-space:nowrap;">ตั้งแต่วันนี้ - วันที่ 31 สิงหาคม 2560</span></span>'''
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