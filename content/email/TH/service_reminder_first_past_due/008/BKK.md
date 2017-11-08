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
คุณจะได้รับบริการเช็คระยะครั้งนั้น "ฟรีทันที"<br />
ขออภัยหากคุณได้เข้ารับบริการที่ศูนย์บริการแล้ว
</span>'''
cta1_text='''<span style="font-family:Tahoma, Verdana, Sans-serif">นัดหมายตอนนี้</span>'''
cta1_url='''https://onlinebooking.ford.co.th/'''
cta1_link_name = '''book_now'''

[[module]] #Banner Image
path='email_modules/image/banner'
color='white'

	image='''th_60min_express_service_20170829'''
	url_link='''https://www.ford.co.th/ford-owner/60mins-express-service/'''
	url_link_name='''60min_express_service'''

[[module]] #Split 04
path='email_modules/split/04'
color='green'

	title='''
    <span style="font-family:Tahoma, Verdana, Sans-serif">ประหยัดและคุ้มค่ากว่า</span>
    '''
	copy='''<span style="font-family:Tahoma, Verdana, Sans-serif;">
<span style="white-space:nowrap;">โปรแกรมบำรุงรักษารถยนต์</span>
<br />
<span style="white-space:nowrap;">ตามระยะ (SSP)</span>
<br />
<span style="white-space:nowrap;">ประหยัดสูงสุดถึง 3,000 บาท</span> 
<br />
<span style="white-space:nowrap;">พิเศษรับสิทธิ์ผ่อน 0% นาน 10 เดือน</span>
<br />
<span style="white-space:nowrap;">เมื่อชำระผ่านบัตรเครดิตกสิกรไทย</span>
<br />
<span style="white-space:nowrap;">ตั้งแต่วันนี้ – วันที่ 31 ธันวาคม 2560</span>
<br />
<span style="white-space:nowrap;">คลิกเพื่อดูรายละเอียดราคา</span>
'''
	cta1_text='''<span style="font-family:Tahoma, Verdana, Sans-serif">คลิกเพื่อดูรายละเอียดและราคา</span>'''
cta1_url='''https://www.ford.co.th/owner/servicecampaign/'''
cta1_icon='''more'''
cta1_link_name = '''SSP'''
image = '''th_edm5a_specialoffer_20160801'''
 
	[[module]] #Cover 05
path='email_modules/cover/02'
color='''white'''

	title = '''<span style="font-family:Tahoma, Verdana, Sans-serif">
	<span style=" white-space:nowrap;">ข้อมูลของคุณมีการ<br />
	<span style=" white-space:nowrap;">เปลี่ยนแปลงหรือไม่</span></span>'''

	copy = '''<span style="font-family:Tahoma, Verdana, Sans-serif">
	<span style=" white-space:nowrap;">กรุณาอัพเดทข้อมูลของคุณ</span>
	<span style=" white-space:nowrap;">เพื่อให้คุณไม่พลาด</span><br />
	<span style=" white-space:nowrap;">ข้อเสนอพิเศษต่างๆ</span>
	<span style=" white-space:nowrap;">จากฟอร์ด</span></span>'''

	cta1_text = '''<span style="font-family:Tahoma, Verdana, Sans-serif">อัพเดทข้อมูล</span>'''
	cta1_url = '''https://www.ford.co.th/#/overlay/content/ford/th/th_th/site-wide-content/overlays/form-overlay/login/'''
	cta1_link_name = '''anything_changed'''
	icon = '''th_edm2_ownerprofile_20160801''' 
 
[[module]] #TH Social
path='email_modules/footer/th/social'
color='white'

[[module]] #TH Online
path='email_modules/footer/th/online'
color='white'

+++