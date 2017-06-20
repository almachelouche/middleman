+++
markets = ["th"]
title = '''TH Anniversary 010 All'''

[[module]]
path='email_modules/preheader'
color='''nothing'''

preheader = '''คุณคงไม่อยากเชื่อใช่ไหมว่าคุณขับรถฟอร์ด Ranger คันใหม่ของคุณมาครบ 1 ปีแล้ว ฟอร์ดอยากใช้โอกาสพิเศษนี้ กล่าวคำขอบคุณอีกครั้ง ที่คุณไว้วางใจ เลือกใช้รถยนต์ฟอร์ด สำหรับลูกค้าคนสำคัญเช่นคุณ ฟอร์ดจะแจ้งข่าวสาร'''

[[module]] #Header Logo
path = 'email_modules/header/logo'
color = 'white'

	image = '''white'''
	url_link = '''http://www.ford.co.th'''

[[module]] #Cover 01
path='email_modules/cover/01'
color='''white'''
 
	title = '''<span style="font-family:Tahoma, Verdana, Sans-serif">เหมือนเพิ่งผ่านไป
	<span style=" white-space:nowrap;">เมื่อวานนี้</span></span>'''
	copy = '''<span style="font-family:Tahoma, Verdana, Sans-serif">สวัสดี คุณ <%InsertIf expression="${(user['FirstName'] == null || user['FirstName'] == '-')}" id="FirstName" %>ท่านลูกค้าฟอร์ด<%/InsertIf%> <%InsertElse%> <%${user['FirstName']}%> <%/InsertElse%><br /><br />คุณคงไม่อยากเชื่อใช่ไหมว่าคุณขับรถ<span style=" white-space:nowrap;">ฟอร์ด</span> Ranger <span style=" white-space:nowrap;">คันใหม่</span>ของคุณ<span style=" white-space:nowrap;">มาครบ</span> <span style=" white-space:nowrap;">1 ปีแล้ว</span> <span style=" white-space:nowrap;">ฟอร์ด</span><span style=" white-space:nowrap;">อยากใช้</span><span style=" white-space:nowrap;">โอกาสพิเศษนี้</span> <span style=" white-space:nowrap;">กล่าวคำขอบคุณ</span><span style=" white-space:nowrap;">อีกครั้ง</span> <span style=" white-space:nowrap;">ที่คุณ</span><span style=" white-space:nowrap;">ไว้วางใจ</span> <span style=" white-space:nowrap;">เลือกใช้</span>รถยนต์<span style=" white-space:nowrap;">ฟอร์ด</span> สำหรับลูกค้า<span style=" white-space:nowrap;">คนสำคัญ</span><span style=" white-space:nowrap;">เช่นคุณ</span> <span style=" white-space:nowrap;">ฟอร์ด</span>จะแจ้ง<span style=" white-space:nowrap;">ข่าวสาร</span> <span style=" white-space:nowrap;">ข้อเสนอพิเศษ</span> <span style=" white-space:nowrap;">และข้อมูลที่เป็นประโยชน์</span> <span style=" white-space:nowrap;">เพื่อให้คุณ</span>ได้<span style=" white-space:nowrap;">รับทราบ</span><span style=" white-space:nowrap;">อย่าง</span><span style=" white-space:nowrap;">ต่อเนื่อง</span><span style=" white-space:nowrap;">ก่อนใคร</span></span>'''

[[module]] #Banner Image No Link
path = '''email_modules/image/banner_nolink'''
color = '''white'''

	image = '''th_edm1&4_np_newranger_20160801'''

[[module]]
path='email_modules/cover/01'

color='black'
title='''<span style="font-family:Tahoma, Verdana, Sans-serif"><span style="white-space:nowrap;">ทางยิ่งยาก </span>
										<span style="white-space:nowrap;"> ฟอร์ด เรนเจอร์ ก็ยิ่งฉลาด </span>
										<span style="white-space:nowrap;"> และกล้าแกร่ง </span></span>'''
copy='''<span style="font-family:Tahoma, Verdana, Sans-serif"><span style="white-space:nowrap;">เพื่อสาธิตความสามารถอันยอดเยี่ยมเหนือใคร</span>
<span style="white-space:nowrap;"> ในการลุยน้ำได้ลึกถึง 800 มิลลิเมตร</span><br />
<span style="white-space:nowrap;">และดีไซน์แบบแอโรไดนามิกของ</span>
<span style="white-space:nowrap;"> ฟอร์ด เรนเจอร์	</span>
<span style="white-space:nowrap;"> เราขอจัดเต็ม!</span></span>'''
cta1_text='''<span style="font-family:Tahoma, Verdana, Sans-serif">ชมวิดีโอที่นี่</span>'''
cta1_url='''http://www.ford.co.th/trucks/ranger/sot2/'''
cta1_link_name = '''ranger_sot'''
cta1_icon='''play'''

	[[module]] #Banner Image
path='email_modules/image/banner'
color='white'

	image = '''th_edm4a_smartranger_20161018'''
	url_link = '''http://www.ford.co.th/trucks/ranger/sot2/'''

[[module]] #Cover 05
path='email_modules/cover/02'
color='''white'''

	title = '''<span style="font-family:Tahoma, Verdana, Sans-serif">ข้อมูลของคุณมีการ<span style=" white-space:nowrap;">เปลี่ยนแปลง</span><span style=" white-space:nowrap;">หรือไม่</span></span>'''
	copy = '''<span style="font-family:Tahoma, Verdana, Sans-serif">กรุณาอัพเดทข้อมูลของคุณ <span style=" white-space:nowrap;">เพื่อให้คุณ</span><span style=" white-space:nowrap;"></span><span style=" white-space:nowrap;">ไม่พลาด</span><span style=" white-space:nowrap;">ข้อเสนอ</span><span style=" white-space:nowrap;">พิเศษต่างๆ</span> <span style=" white-space:nowrap;">จากฟอร์ด</span></span>'''
	cta1_text = '''<span style="font-family:Tahoma, Verdana, Sans-serif">อัพเดทข้อมูล</span>'''
	cta1_url = '''https://www.ford.co.th/owner/login'''
	cta1_link_name = '''anything_changed'''
	icon = '''th_edm2_ownerprofile_20160801'''

[[module]] #TH Social
path='email_modules/footer/th/social'
color='white'

[[module]] #TH Online
path='email_modules/footer/th/online'
color='white'

+++