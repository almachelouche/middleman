+++
markets = ["th"]
title = '''TH Anniversary 008 EcoSport'''

[[module]]
path='email_modules/preheader'

	preheader = '''คุณคงไม่อยากเชื่อใช่ไหมว่าคุณขับรถฟอร์ด EcoSport คันใหม่ของคุณมาครบ 1 ปีแล้ว ฟอร์ดอยากใช้โอกาสพิเศษนี้ กล่าวคำขอบคุณอีกครั้ง ที่คุณไว้วางใจ เลือกใช้รถยนต์ฟอร์ด สำหรับลูกค้าคนสำคัญเช่นคุณ ฟอร์ดจะแจ้งข่าวสาร'''

[[module]] #Header Logo
path = 'email_modules/header/logo'
color = 'white'

	image = '''white'''
	url_link = '''https://www.ford.co.th/'''

[[module]] #Cover 01
path='email_modules/cover/01'
color='''white'''

	title = '''<span style="font-family:Tahoma, Verdana, Sans-serif"><strong>ครบรอบ 1 ปีกับรถฟอร์ดคู่ใจของคุณ<span style=" white-space:nowrap;"></span></strong></span>'''
	copy = '''<span style="font-family:Tahoma, Verdana, Sans-serif">สวัสดี คุณ <%InsertIf expression="${(user['FirstName'] == null || user['FirstName'] == '-')}" id="FirstName" %>ท่านลูกค้าฟอร์ด<%/InsertIf%> <%InsertElse%> <%${user['FirstName']}%> <%/InsertElse%><br /><br />
    
    <span style=" white-space:nowrap;"> คุณคงไม่อยากเชื่อใช่ไหมว่าคุณขับรถฟอร์ด EcoSport คันใหม่ของคุณมาครบ1 ปีแล้ว</span><br />
    <span style=" white-space:nowrap;">ฟอร์ดอยากใช้โอกาสพิเศษนี้กล่าวคำขอบคุณอีกครั้งที่คุณไว้วางใจเลือกใช้รถยนต์</span><br />
    <span style=" white-space:nowrap;">ฟอร์ดสำหรับลูกค้าคนสำคัญเช่นคุณฟอร์ดจะแจ้งข่าวสารข้อเสนอพิเศษ</span><br />
    <span style=" white-space:nowrap;">และข้อมูลที่เป็นประโยชน์เพื่อให้คุณได้รับทราบอย่างต่อเนื่องก่อนใคร</span></span>'''

[[module]] #Banner Image No Link
path = '''email_modules/image/banner_nolink'''
color = '''white'''

	image = '''th_edm1&4_np_ecosport_20160801'''


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