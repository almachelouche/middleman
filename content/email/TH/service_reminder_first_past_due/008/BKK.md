+++
markets = ["th"]
title = '''TH Service Reminder First Past Due 008 BKK'''

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
						เพื่อรักษารถ <%${user.CustomAttribute['Model']}%>
						ของคุณให้อยู่ในสภาพดี
						และวิ่งได้อย่างเต็มประสิทธิภาพสม่ำเสมอ
					อย่าลืมนำรถเข้าศูนย์บริการ
						เพื่อตรวจเช็คระยะเมื่อครบกำหนด
                    </span>
<br /><br />
 <span style="font-family:Tahoma, Verdana, Sans-serif">อย่าลืม! จองคิวเช็คระยะเลยวันนี้</span> 
<br /><br />
<span style="font-family:Tahoma, Verdana, Sans-serif">
บริการใหม่!! ฟอร์ดเพิ่มความสะดวกสบาย
ให้คุณสามารถนัดหมายเช็คระยะที่ศูนย์บริการ<br />
ฟอร์ดง่ายๆ ผ่านระบบ Online Booking ตลอด 7 วัน<br />
พร้อมการรับประกันเช็คระยะภายใน 60	นาที
หากไม่ทัน<br />
ขออภัยหากคุณได้เข้ารับบริการที่ศูนย์บริการแล้ว
</span>'''
cta1_text='''<span style="font-family:Tahoma, Verdana, Sans-serif">นัดหมายตอนนี้</span>'''
cta1_url='''https://onlinebooking.ford.co.th/'''
cta1_link_name = '''book_now'''

[[module]] #Banner Image
path='email_modules/image/banner'
color='white'

 image='''TH_edm2_ServiceCampaign_20170726'''
	url_link='''https://www.ford.co.th/owner/servicecampaign/'''
	url_link_name='''servicecampaign'''

[[module]] #Split 04
path='email_modules/split/04'
color='green'

	title='''<span style="font-family:Tahoma, Verdana, Sans-serif">ประหยัดและคุ้มค่ากว่า </span>'''
	copy='''<span style="font-family:Tahoma, Verdana, Sans-serif;">รับส่วนลดเพิ่มสูงสุด 10% หรือ 3,700 บาท กับโปรแกรมบำรุงรักษารถยนต์ ตามระยะ(SSP)พิเศษรับสิทธิ์ผ่อน 0%	นาน 10 เดือน เมื่อชำระผ่านบัตรเครดิตกสิกรไทย ตั้งแต่วันนี้ - วันที่ 31 สิงหาคม 2560</span>'''
	cta1_text='''<span style="font-family:Tahoma, Verdana, Sans-serif">คลิกเพื่อดูรายละเอียดและราคา ></span>'''
cta1_url='''https://www.ford.co.th/owner/servicecampaign/'''
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