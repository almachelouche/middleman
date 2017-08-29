+++
markets = ["th"]
title = '''TH Welcome Repeat 007 New Ranger'''
draft = true

[[module]]
path='email_modules/preheader'


		preheader = '''ไม่ว่าคุณจะเป็นลูกค้าเก่าหรือลูกค้าใหม่ ฟอร์ดขอขอบคุณที่คุณเลือกเราให้เป็นเพื่อนร่วมทางไปกับคุณ ด้วยการเป็นส่วนหนึ่งของครอบครัวฟอร์ด เราจะส่งข่าวสารและข้อมูลกิจกรรมที่เป็นประโยชน์ให้แก่คุณอย่างต่อเนื่อง ขอให้คุณมีความสุขกับการขับขี่ Ranger ะ'''

[[module]] #Header Logo
path='email_modules/header/logo'
color='white'

	image = '''white'''
	url_link = '''https://www.ford.co.th/'''

[[module]] #Cover 01
path='email_modules/cover/01'
color='''white'''
 
	title = '''<span style="font-family:Tahoma, Verdana, Sans-serif"><strong>สวัสดีค่ะ คุณ <%InsertIf expression="${(user['FirstName'] == null || user['FirstName'] == '-')}" id="FirstName" %>ท่านลูกค้าฟอร์ด<%/InsertIf%> <%InsertElse%> <%${user['FirstName']}%> <%/InsertElse%></strong><br />การเดินทางยังคงดำเนินต่อไป</span>'''
	copy = '''<span style="font-family:Tahoma, Verdana, Sans-serif">
<span style=" white-space:nowrap;">ไม่ว่าคุณจะเป็นลูกค้าเก่าหรือลูกค้าใหม่</span> <br />
						<span style=" white-space:nowrap;">ฟอร์ดขอขอบคุณที่คุณเลือกเรา</span> <br />
						<span style=" white-space:nowrap;">ให้เป็นเพื่อนร่วมทางไปกับคุณ </span>
<br /><br />
<span style=" white-space:nowrap;">ด้วยการเป็นส่วนหนึ่งของครอบครัวฟอร์ด</span> <br />
<span style=" white-space:nowrap;">เราจะส่งข่าวสารและข้อมูลกิจกรรม</span> <br />
<span style=" white-space:nowrap;">ที่เป็นประโยชน์ให้แก่คุณอย่างต่อเนื่อง</span> 
<br /><br />
<span style=" white-space:nowrap;">ขอให้คุณมีความสุข</span>กับการ<span style=" white-space:nowrap;">ขับขี่ Ranger ค่ะ</span></span>'''

[[module]] #Banner Image No Link
path = '''email_modules/image/banner_nolink'''
color = '''white'''

	image = '''th_edm1_wildtrak_20170309'''

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

[[module]] #Dual 04
path='email_modules/dual/04'
color='white'

title1 = ''' <span style="font-family:Tahoma, Verdana, Sans-serif">ศูนย์ข้อมูลเพื่อเจ้าของ</span><br />
							<span style="font-family:Tahoma, Verdana, Sans-serif">รถฟอร์ด</span>'''
	copy1 = '''<span style="font-family:Tahoma, Verdana, Sans-serif"><span style=" white-space:nowrap;">รวมทุกเรื่องที่คุณต้องการในหนึ่งเดียว</span></span>'''
	cta1a_text = '''<span style="font-family:Tahoma, Verdana, Sans-serif"><br /><br />ดูศูนย์ข้อมูลเจ้าของรถฟอร์ด</span>'''
	cta1a_url = '''https://www.ford.co.th/owner/owner-unauthenticated/'''
	cta1a_link_name = '''owner_center'''
	cta1b_text = ''''''
	cta1b_url = ''''''
	cta1b_link_name = ''''''
	cta1c_text = ''''''
	cta1c_url = ''''''
	cta1c_link_name = ''''''
	icon1 = '''th_edm1_ownersite_20160801'''
	title2 = '''<span style="font-family:Tahoma, Verdana, Sans-serif">เรียนรู้การใช้งาน SYNC&trade;</span>'''
	copy2 = '''<span style="font-family:Tahoma, Verdana, Sans-serif"><span style="color:#616161; font-size:16px">รถยนต์ฟอร์ดของคุณมาพร้อมกับ<br />ระบบสั่งงานด้วยเสียง SYNC&trade;<br />เพื่อการสั่งงาน<br />โดยไม่ต้องปล่อยมือจากพวงมาลัย</span></span>'''
	cta2a_text = '''<span style="font-family:Tahoma, Verdana, Sans-serif"><br /><br />เรียนรู้เพิ่มเติมเกี่ยวกับ SYNC&trade;</span>'''
	cta2a_url = '''https://www.ford.co.th/engineering/sync/'''
	cta2a_link_name = '''sync'''
	cta2b_text = ''''''
	cta2b_url = ''''''
	cta2b_link_name = ''''''
	cta2c_text = ''''''
	cta2c_url = ''''''
	cta2c_link_name = ''''''
	icon2 = '''th_edm1_sync_20160801'''
 
[[module]] # Owner App Image Right
path='email_modules/custom/ownerapp_imgr'
color='black'

title = '''<span style="font-family:Tahoma, Verdana, Sans-serif">Ford Owners App</span>'''
text1 = '''<span style="font-family:Tahoma, Verdana, Sans-serif">
<span style=" white-space:nowrap;">แอพพลิเคชั่นเพื่อเจ้าของรถฟอร์ด</span><br> 
<span style=" white-space:nowrap;">เพื่อการดูแลรถฟอร์ดที่ง่ายขึ้น</span></span>'''
text2 = '''<span style="font-family:Tahoma, Verdana, Sans-serif; font-Size: 14px">
<ul style="margin: 20px; padding: 0;">
<li><span style=" white-space:nowrap;">ข้อมูลการบริการดูแล<br>รักษารถยนต์ตามระยะ</span></li>
<li><span style=" white-space:nowrap;">ค้นหาตัวแทนจำหน่ายใกล้เคียง</span></li>
<li><span style=" white-space:nowrap;">รับชมวิดีโอ How-To <br>คู่มือการเป็นเจ้าของรถฟอร์ด<br>แบบครบครัน</span></li>
<li><span style=" white-space:nowrap;">รู้จักกับสัญลักษณ์<br>บนแผงหน้าปัดควบคุมรถ</span></li>
</ul>
</span>'''
	cta1_text = '''iPhone'''
	cta1_url = '''https://itunes.apple.com/TH/app/ford-owners/id990342351?mt=8'''
	cta1_link_name = '''oa_iphone'''
	cta2_text = '''Android'''
	cta2_url = '''https://play.google.com/store/apps/details?id=com.ford.fordowners&hl=th'''
	cta2_link_name = '''oa_andriod'''
	image = '''th_edm6_ownerapp_20160921'''

[[module]]
path='email_modules/split/07'
color='white'

title='''<span style="font-family:Tahoma, Verdana, Sans-serif">อุปกรณ์ตกแต่งสำหรับคุณ</span>'''
copy='''<span style="font-family:Tahoma, Verdana, Sans-serif">
<span style="white-space:nowrap;">ให้ฟอร์ด</span>
<span style="white-space:nowrap;">เรนเจอร์ของคุณ</span> 
<span style="white-space:nowrap;">ล้ำหน้าไปอีกขั้น</span> <br />
<span style="white-space:nowrap;">ด้วยอุปกรณ์ตกแต่งล่าสุด</span>
<span style="white-space:nowrap;">ฝาปิดกระบะท้าย</span> <br />
<span style="white-space:nowrap;">พร้อมชุดติดตั้งกุญแจล๊อค</span><br />
<span style="white-space:nowrap;">ฝาปิดกระบะท้าย</span>
<span style="white-space:nowrap;">มูลค่า 60,893.-</span> <br />
<span style="white-space:nowrap;">ที่ทำ</span>จาก<span style="white-space:nowrap;">อลูมิเนียมคุณภาพสูง</span> <br />
<span style="white-space:nowrap;">น้ำหนักเบา</span>
<span style="white-space:nowrap;">ปกป้องสัมภาระของคุณ</span><br />
<span style="white-space:nowrap;">ได้อย่างปลอดภัย</span></span>'''
cta1_text='''<span style="font-family:Tahoma, Verdana, Sans-serif">คลิกเพื่อชมอุปกรณ์เสริมทั้งหมด</span>'''
cta1_url='''https://www.ford.co.th/trucks/ranger/accessories/#overlay/content/ford/th/th_th/ranger-content/image-overlays/accessories/nudge-bar.html'''
cta1_link_name = '''acc_new_ranger'''
image='''TH_edm1a_wildtrak_roller_shutter_20170508'''

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