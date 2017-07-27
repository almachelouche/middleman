+++
markets = ["th"]
title = '''TH Anniversary 008 New Ranger'''

[[module]]
path='email_modules/preheader'

	preheader = '''คุณคงไม่อยากเชื่อใช่ไหมว่าคุณขับรถฟอร์ด Ranger คันใหม่ของคุณมาครบ 1 ปีแล้ว ฟอร์ดอยากใช้โอกาสพิเศษนี้ กล่าวคำขอบคุณอีกครั้ง ที่คุณไว้วางใจ เลือกใช้รถยนต์ฟอร์ด สำหรับลูกค้าคนสำคัญเช่นคุณ ฟอร์ดจะแจ้งข่าวสาร'''

[[module]] #Header Logo
path = 'email_modules/header/logo'
color = 'white'

	image = '''white'''
	url_link = '''https://www.ford.co.th/'''

[[module]] #Cover 01
path='email_modules/cover/01'
color='''white'''
 
	title = '''<span style="font-family:Tahoma, Verdana, Sans-serif"><strong>เครบรอบ 1 ปีกับรถฟอร์ดคู่ใจของคุณ<span style=" white-space:nowrap;"></span></strong></span>'''
	copy = '''<span style="font-family:Tahoma, Verdana, Sans-serif">สวัสดี คุณ <%InsertIf expression="${(user['FirstName'] == null || user['FirstName'] == '-')}" id="FirstName" %>ท่านลูกค้าฟอร์ด<%/InsertIf%> <%InsertElse%> <%${user['FirstName']}%> <%/InsertElse%><br /><br />คุณคงไม่อยากเชื่อใช่ไหมว่าคุณขับรถ<span style=" white-space:nowrap;">ฟอร์ด</span> Ranger <span style=" white-space:nowrap;">คันใหม่</span>ของคุณ<span style=" white-space:nowrap;">มาครบ</span> <span style=" white-space:nowrap;">1 ปีแล้ว</span> <span style=" white-space:nowrap;">ฟอร์ด</span><span style=" white-space:nowrap;">อยากใช้</span><span style=" white-space:nowrap;">โอกาสพิเศษนี้</span> <span style=" white-space:nowrap;">กล่าวคำขอบคุณ</span><span style=" white-space:nowrap;">อีกครั้ง</span> <span style=" white-space:nowrap;">ที่คุณ</span><span style=" white-space:nowrap;">ไว้วางใจ</span> <span style=" white-space:nowrap;">เลือกใช้</span>รถยนต์<span style=" white-space:nowrap;">ฟอร์ด</span> สำหรับลูกค้า<span style=" white-space:nowrap;">คนสำคัญ</span><span style=" white-space:nowrap;">เช่นคุณ</span> <span style=" white-space:nowrap;">ฟอร์ด</span>จะแจ้ง<span style=" white-space:nowrap;">ข่าวสาร</span> <span style=" white-space:nowrap;">ข้อเสนอพิเศษ</span> <span style=" white-space:nowrap;">และข้อมูลที่เป็นประโยชน์</span> <span style=" white-space:nowrap;">เพื่อให้คุณ</span>ได้<span style=" white-space:nowrap;">รับทราบ</span><span style=" white-space:nowrap;">อย่าง</span><span style=" white-space:nowrap;">ต่อเนื่อง</span><span style=" white-space:nowrap;">ก่อนใคร</span></span>'''

[[module]] #Banner Image No Link
path = '''email_modules/image/banner_nolink'''
color = '''white'''

	image = '''th_edm1_wildtrak_2017420'''

[[module]] #Cover 01
path='email_modules/cover/01'
color='black'

	title = '''<span style="font-family:Tahoma, Verdana, Sans-serif; white-space:nowrap;">แกร่งแค่ไหน?</span> 
	<span style="font-family:Tahoma, Verdana, Sans-serif; white-space:nowrap;"> อึดแค่ไหน?</span> 
	<span style="font-family:Tahoma, Verdana, Sans-serif; white-space:nowrap;"> โหดได้แค่ไหน?</span>'''
	copy = '''<span style="font-family:Tahoma, Verdana, Sans-serif">
	<span style=" white-space:nowrap;">ดู!...และพิสูจน์ความแกร่งของ</span>
	<span style=" white-space:nowrap;">ฟอร์ด เรนเจอร์</span>
	<span style=" white-space:nowrap;">ด้วยตัวคุณเอง</span></span>'''
	cta1_text = '''<span style="font-family:Tahoma, Verdana, Sans-serif">ชมวิดีโอที่นี่</span>'''
	cta1_url = '''https://www.ford.co.th/trucks/ranger/sot2/'''
	cta1_link_name = '''ranger_sot'''
	cta1_icon = '''more'''

[[module]] #Banner Image GIF
path = '''email_modules/image/bannerGif'''
color = '''white'''

	image = '''th_edm1&4_np_sot_airmail_20161115'''
	url_link = '''https://www.ford.co.th/trucks/ranger/sot2/'''
	url_link_name = '''ranger_sot'''


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