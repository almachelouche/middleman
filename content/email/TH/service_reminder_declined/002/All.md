+++
markets = ["th"]
title = '''TH Service Reminder Declined 002 All'''



[[module]]
path='email_modules/preheader'


		preheader = '''คุ้มสุดๆ! เปลี่ยนยางกู๊ดเยียร์ที่ศูนย์บริการฟอร์ดทั่วประเทศ'''

[[module]] #Header Logo
path='email_modules/header/logo'
color='white'

	image = '''white'''
	url_link = '''https://www.ford.co.th/'''

[[module]] #Cover 06
path='email_modules/cover/02'
color='''darkblue'''
icon='''th_edm2d_svcwrench_urgent_20160801'''

title = '''<span style="color:#ff6600;font-family:Tahoma, Verdana, Sans-serif"><span style=" white-space:nowrap;">ได้เวลาเปลี่ยนอะไหล่ </span><span style=" white-space:nowrap;"><%${user.CustomAttribute['Model']}%> ของคุณแล้ว</span></span>'''
	copy = '''<span style="font-family:Tahoma, Verdana, Sans-serif"><span style=" white-space:nowrap;">เราพบว่าเมื่อคุณเข้ามาตรวจสภาพรถ</span>กับ<span style=" white-space:nowrap;">ฟอร์ดคุณได้ปฏิเสธการเปลี่ยนอะไหล่ครั้งที่ผ่านมา</span> <br />
<span style=" white-space:nowrap;">ซึ่งอาจเป็นสาเหตุให้เกิด</span>ความ<span style=" white-space:nowrap;">ไม่ปลอดภัยในการขับขี่ </span>
	<br /><br />
<span style=" white-space:nowrap;">เพียงคุณพารถฟอร์ดของคุณ</span>กลับมา<span style=" white-space:nowrap;">ที่ศูนย์บริการมาตรฐานฟอร์ด</span> <br />
<span style=" white-space:nowrap;"> คุณจะมั่นใจได้ว่าคุณ</span>จะ<span style=" white-space:nowrap;">ได้รับการตรวจเช็ค</span>จาก<span style=" white-space:nowrap;">ช่างเทคนิคฟอร์ดที่ผ่านการอบรม</span><br />
<span style=" white-space:nowrap;"> พร้อมเครื่องมือตรวจสอบอันทันสมัย</span>กับ<span style=" white-space:nowrap;">คุณภาพอะไหล่แท้ของฟอร์ด</span> <br />
<span style=" white-space:nowrap;"> ให้คุณขับขี่รถฟอร์ด</span>ได้<span style=" white-space:nowrap;">อย่างเต็มประสิทธิภาพ </span><br /><br />
<span style="white-space:nowrap;">นัดหมายล่วงหน้าเพื่อเข้ารับบริการได้ทันที</span> <br />
<span style="white-space:nowrap;">ติดต่อ <%${user.CustomAttribute['Dealer_Name']}%></span> <span style="white-space:nowrap;">(ระหว่างเวลาทำการ)</span><br />
<span style="white-space:nowrap;">หรือค้นหาตัวแทนจำหน่ายใกล้บ้านคุณ</span></span>'''

cta1_text='''<span style="font-family:Tahoma, Verdana, Sans-serif">โทร <%${user.CustomAttribute['Dealer_Phone']}%></span>'''
cta1_url='''tel:<%${user.CustomAttribute['Dealer_Phone']}%>'''
cta2_text='''<span style="font-family:Tahoma, Verdana, Sans-serif">ค้นหาตัวแทนจำหน่าย</span>'''
cta2_url='''https://www.ford.co.th/locate-a-dealer/'''
cta2_link_name = '''find_dealer'''

[[module]] #Service Status No Copy
path='email_modules/custom/svcstatus_nocopy'
color='darkblue'

			toptitle='''<span style="font-family:Tahoma, Verdana, Sans-serif">ผลตรวจเช็ค <%${user.CustomAttribute['Model']}%> ของคุณ ครั้งหลังสุด</span>'''
	segmentAgreen = '''(user.CustomAttribute['Brake'] == null)'''
	segmentAyellow = '''(user.CustomAttribute['Brake'] == 'YBRAKE')'''
	segmentAred = '''(user.CustomAttribute['Brake'] == 'RBRAKE')'''
		icon1green = '''in_edm2d_status_brake_black_20160801'''
		title1green = '''<span style="font-family:Tahoma, Verdana, Sans-serif">เบรก</span>'''
		subtitle1green = '''<span style="font-family:Tahoma, Verdana, Sans-serif">อยู่ในสภาพดี</span>'''
		icon1yellow = '''in_edm2d_status_brake_black_20160801'''
		title1yellow = '''<span style="font-family:Tahoma, Verdana, Sans-serif">เบรก</span>'''
		subtitle1yellow = '''<span style="font-family:Tahoma, Verdana, Sans-serif">ใกล้ถึงเวลาเปลี่ยน</span>'''
		icon1red = '''in_edm2d_status_brake_white_20160801'''
		title1red = '''<span style="font-family:Tahoma, Verdana, Sans-serif">เบรก</span>'''
		subtitle1red = '''<span style="font-family:Tahoma, Verdana, Sans-serif">ควรเปลี่ยนทันที</span>'''
	segmentBgreen = '''(user.CustomAttribute['Tyre'] == null)'''
	segmentByellow = '''(user.CustomAttribute['Tyre'] == 'YTYRE')'''
	segmentBred = '''(user.CustomAttribute['Tyre'] == 'RTYRE')'''
		icon2green = '''in_edm2d_status_tyre_black_20160801'''
		title2green = '''<span style="font-family:Tahoma, Verdana, Sans-serif">ยาง</span>'''
		subtitle2green = '''<span style="font-family:Tahoma, Verdana, Sans-serif">อยู่ในสภาพดี</span>'''
		icon2yellow = '''in_edm2d_status_tyre_black_20160801'''
		title2yellow = '''<span style="font-family:Tahoma, Verdana, Sans-serif">ยาง</span>'''
		subtitle2yellow = '''<span style="font-family:Tahoma, Verdana, Sans-serif">ใกล้ถึงเวลาเปลี่ยน</span>'''
		icon2red = '''in_edm2d_status_tyre_white_20160801'''
		title2red = '''<span style="font-family:Tahoma, Verdana, Sans-serif">ยาง</span>'''
		subtitle2red = '''<span style="font-family:Tahoma, Verdana, Sans-serif">ควรเปลี่ยนทันที</span>'''
	segmentCgreen = '''(user.CustomAttribute['Battery'] == null)'''
	segmentCyellow = '''(user.CustomAttribute['Battery'] == 'YBATT')'''
	segmentCred = '''(user.CustomAttribute['Battery'] == 'RBATT')'''
		icon3green = '''in_edm2d_status_battery_black_20160801'''
		title3green = '''<span style="font-family:Tahoma, Verdana, Sans-serif">แบตเตอรี่</span>'''
		subtitle3green = '''<span style="font-family:Tahoma, Verdana, Sans-serif">อยู่ในสภาพดี</span>'''
		icon3yellow = '''in_edm2d_status_battery_black_20160801'''
		title3yellow = '''<span style="font-family:Tahoma, Verdana, Sans-serif">แบตเตอรี่</span>'''
		subtitle3yellow = '''<span style="font-family:Tahoma, Verdana, Sans-serif">ใกล้ถึงเวลาเปลี่ยน</span>'''
		icon3red = '''in_edm2d_status_battery_white_20160801'''
		title3red = '''<span style="font-family:Tahoma, Verdana, Sans-serif">แบตเตอรี่</span>'''
		subtitle3red = '''<span style="font-family:Tahoma, Verdana, Sans-serif">ควรเปลี่ยนทันที</span>'''

	[[module]] #Split 04
path='email_modules/split/04'
color='green'

	title='''<span style="font-family:Tahoma, Verdana, Sans-serif"><span style=" white-space:nowrap;">โปรยางสุดคุ้ม!</span> 
									<span style=" white-space:nowrap;">พร้อมรับสิทธิ์ </span> 
									<span style=" white-space:nowrap;">Worry Free</span>
									<span style=" white-space:nowrap;">อุ่นใจ 3 ต่อ</span> </span>'''
	copy='''<span style="font-family:Tahoma, Verdana, Sans-serif;"><span style=" white-space:nowrap;">ซื้อยางกู๊ดเยียร์ 3 เส้น</span> 
									<span style=" white-space:nowrap;">แถม 1 เส้น</span>
									<span style=" white-space:nowrap;">ฟรีทันที!</span> 
									<span style=" white-space:nowrap;">พร้อมฟรีค่าแรงถอดใส่</span>และ<span style=" white-space:nowrap;">ถ่วงล้อ 4 ล้อ</span>
									<span style=" white-space:nowrap;">และผ่อน 0% นาน 6 เดือน</span>
									<span style=" white-space:nowrap;">ด้วยบัตรเครดิตกสิกรไทย</span> 
									<span style=" white-space:nowrap;">ภายใน 31 มกราคมนี้เท่านั้น</span></span>'''

	cta1_text='''<span style="font-family:Tahoma, Verdana, Sans-serif">ค้นหาตัวแทนจำหน่าย</span>'''
cta1_url='''https://www.ford.co.th/locate-a-dealer/'''
cta1_icon='''more'''
cta1_link_name = '''tyre_promotion'''
image = '''th_edm5_tyreoffer_20161216'''


[[module]] #TH Social
path='email_modules/footer/th/social'
color='white'

[[module]] #TH Online
path='email_modules/footer/th/online'
color='white'

+++