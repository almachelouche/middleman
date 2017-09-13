+++
markets = ["th"]
title = '''TH Service Reminder Declined 005 All'''
draft = true

[[module]]
path='email_modules/preheader'


		preheader = '''พบข้อเสนอสุดพิเศษสำหรับยางรถยนต์ เบรก แบตเตอรี่และอะไหล่ต่างๆ อีกมากมาย'''

[[module]] #Header Logo
path='email_modules/header/logo'
color='white'

	image = '''white'''
	url_link = '''https://www.ford.co.th/'''

[[module]] #Cover 06
path='email_modules/cover/02'
color='''white'''
icon='''th_edm2_svc_wrench_urgent_20160801'''

title = '''<span style="color:#ff6600;font-family:Tahoma, Verdana, Sans-serif"><span style=" white-space:nowrap;">ได้เวลาเปลี่ยนอะไหล่ </span><span style=" white-space:nowrap;"><%${user.CustomAttribute['Model']}%></span> <span style=" white-space:nowrap;">ของคุณแล้ว</span></span>'''
	copy = '''<span style="font-family:Tahoma, Verdana, Sans-serif">
						<span style=" white-space:nowrap;">เราพบว่าเมื่อคุณเข้า</span>มา<span style=" white-space:nowrap;">ตรวจสภาพรถกับฟอร์ด</span><br>
						<span style=" white-space:nowrap;">คุณได้ปฏิเสธการเปลี่ยนอะไหล่</span>
						<span style=" white-space:nowrap;">ครั้งที่ผ่านมา</span><br>
			<span style=" white-space:nowrap;">ซึ่งอาจเป็นสาเหตุให้เกิด</span>ความ<span style=" white-space:nowrap;">ไม่ปลอดภัยในการขับขี่ </span>
	<br><br>
<span style=" white-space:nowrap;">เพียงคุณพารถฟอร์ดของคุณกลับมา</span> 
<span style=" white-space:nowrap;">ที่ศูนย์บริการมาตรฐานฟอร์ด</span><br>
<span style=" white-space:nowrap;">คุณจะมั่นใจได้ว่าคุณ</span>จะ<span style=" white-space:nowrap;">ได้รับการตรวจเช็ค</span><br />
<span style=" white-space:nowrap;">จากช่างเทคนิคฟอร์ดที่ผ่านการอบรม</span>
<span style=" white-space:nowrap;">พร้อมเครื่องมือตรวจสอบอันทันสมัย</span><br />
<span style=" white-space:nowrap;">กับคุณภาพอะไหล่แท้ของฟอร์ด</span><br />
<span style=" white-space:nowrap;"> ให้คุณขับขี่รถฟอร์ด</span>ได้<span style=" white-space:nowrap;">อย่างเต็มประสิทธิภาพ </span><br><br>
<span style="white-space:nowrap;">นัดหมายล่วงหน้า</span>เพื่อ<span style="white-space:nowrap;">เข้ารับบริการได้ทันที</span> <br>
<span style="white-space:nowrap;">ติดต่อ <%${user.CustomAttribute['Dealer_Name']}%></span> <span style="white-space:nowrap;">(ระหว่างเวลาทำการ)</span><br>
<span style="white-space:nowrap;">หรือค้นหาตัวแทนจำหน่าย</span>
<span style="white-space:nowrap;">ใกล้บ้านคุณ</span></span>'''

cta1_text='''<span style="font-family:Tahoma, Verdana, Sans-serif">โทร <%${user.CustomAttribute['Dealer_Phone']}%></span>'''
cta1_url='''tel:<%${user.CustomAttribute['Dealer_Phone']}%>'''
cta2_text='''<span style="font-family:Tahoma, Verdana, Sans-serif">ค้นหาตัวแทนจำหน่าย</span>'''
cta2_url='''https://www.ford.co.th/locate-a-dealer/'''
cta2_link_name='''find_dealer'''

[[module]] #Service Status No Copy
path='email_modules/custom/svcstatus_nocopy'
color='white'

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



[[module]]
path='email_modules/singles/copy'
color='''white'''

		copy='''<br /><br /><span style="font-family:Tahoma, Verdana, Sans-serif">
		<span style="text-align:center; font-size:24px; line-height: 30px; font-weight: normal; font-style: normal; color:#1B394E; font-family:Tahoma, Verdana, Sans-serif; padding-bottom:20px;">สุดคุ้มกับอะไหล่แท้<br />จากฟอร์ด</span><br /><br />
		<span style="white-space:nowrap;">เพื่อให้สมรรถนะรถฟอร์ดของคุณ</span> 
		<span style="white-space:nowrap;">ทำงานได้อย่างเต็มประสิทธิภาพ</span><br /> 
		<span style="white-space:nowrap;">ฟอร์ดมีข้อเสนอสุดคุ้ม</span> 
		<span style="white-space:nowrap;">เมื่อคุณซื้ออะไหล่แท้จากฟอร์ด</span><br /> 
		<span style="white-space:nowrap;">คุณจะได้มีสิทธิ์ร่วมลุ้นรับสิทธิพิเศษ</span>
		<span style="white-space:nowrap;">หรือได้รับน้ำยาทำความสะอาดหัวฉีดฟรี</span>
		<span style="white-space:nowrap;">ข้อเสนอนี้ถึงวันที่ 31 สิงหาคม 2560</span> 
		<span style="white-space:nowrap;">เท่านั้น</span></span>'''

[[module]] #Custom 3 Icon Text
path='email_modules/custom/3icon_text'
color='white'

	title = ''''''
	icon1 = '''th_edm6_brake_20170113'''
	text1 = '''<span style="font-family:Tahoma, Verdana, Sans-serif"><span style="font-weight:bold">ผ้าเบรกสุดคุ้ม</span><br /><br />
	<span style="white-space:nowrap;">ซื้อผ้าเบรก</span> 
	<span style="white-space:nowrap;">Ford-Motorcraft</span> 
	<span style="white-space:nowrap;">รับฟรี</span> 
	<span style="white-space:nowrap;">น้ำยาทำความสะอาดหัวฉีด</span></span>'''
	icon2 = '''th_edm6_tyre_20170113'''
	text2 = '''<span style="font-family:Tahoma, Verdana, Sans-serif"><span style="font-weight:bold">โปรยางสุดคุ้ม</span><br /><br />
	<span style="white-space:nowrap;">ซื้อยางกู๊ดเยียร์ 3 เส้น</span> 
	<span style="white-space:nowrap;">แถม 1 เส้นฟรี<sup>1</sup></span>
	<span style="white-space:nowrap;">รับสิทธิ์ผ่อน 0%</span>
	<span style="white-space:nowrap;">นาน 6 เดือน</span> 
	<span style="white-space:nowrap;">ด้วยบัตรเครดิตกสิกรไทย<sup>2</sup></span></span>'''
	icon3 = '''th_edm6_battery_20170113'''
	text3 = '''<span style="font-family:Tahoma, Verdana, Sans-serif"><span style="font-weight:bold">แบตเตอรี่ฟอร์ดแท้สุดคุ้ม</span><br /><br />
	<span style="white-space:nowrap;">รับฟรี</span> 
	<span style="white-space:nowrap;">น้ำยาทำความสะอาดหัวฉีด</span>
	<span style="white-space:nowrap;">เมื่อซื้อแบตเตอรี่ฟอร์ดแท้</span> 
	<span style="white-space:nowrap;">สำหรับรถฟอร์ดโดยเฉพาะ</span></span>'''


[[module]]
path='email_modules/singles/ctablock'
color='''white'''

		cta1_text = '''<span style="font-family:Tahoma, Verdana, Sans-serif">ดูข้อเสนอเพิ่มเติม</span>'''
	cta1_url = '''https://www.ford.co.th/'''
	cta1_link_name = '''commodity_offer'''

[[module]] #TH Social
path='email_modules/footer/th/social'
color='white'

[[module]] #Footer Disclaimer
path='email_modules/footer/disclaimer'
color='white'
text='''<span style="font-family:Tahoma, Verdana, Sans-serif">หมายเหตุ:<br />
<span style="white-space:nowrap;">[1] สิทธิพิเศษสำหรับยางรถยนต์กู๊ดเยียร์,</span> 
<span style="white-space:nowrap;">ยางรถยนต์มิชลิน</span> 
<span style="white-space:nowrap;">และยางรถยนต์บีเอฟกู๊ดริช</span> 
<span style="white-space:nowrap;">เท่านั้น</span><br />

<span style="white-space:nowrap;">[2]สิทธิพิเศษสำหรับยางรถยนต์กู๊ดเยียร์เท่านั้น</span></span>'''

[[module]] #TH Online
path='email_modules/footer/th/online'
color='white'

+++