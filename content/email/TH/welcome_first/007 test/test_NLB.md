+++
markets = ["th"]
title = '''TH Welcome First 007 New Ranger'''

[[module]]
path='email_modules/preheader'


		preheader = '''ฟอร์ดขอขอบคุณที่คุณเลือกเรา ให้เป็นเพื่อนร่วมทางของคุณ เราจะส่งข่าวสาร และข้อมูลกิจกรรมที่เป็นประโยชน์ ให้แก่คุณอย่างต่อเนื่อง เพราะคุณเป็นส่วนหนึ่ง ของครอบครัวฟอร์ด ขอให้คุณมีความสุขกับการขับขี่ Ranger ค่ะ '''

[[module]] #Header Logo
path='email_modules/header/logo'
color='white'

	image = '''white'''
	url_link = '''https://www.ford.co.th/'''

[[module]] #Cover 01
path='email_modules/cover/01'
color='''white'''

	title = '''<strong>สวัสดีค่ะ คุณ <%InsertIf expression="${(user['FirstName'] == null || user['FirstName'] == '-')}" id="FirstName" %>ท่านลูกค้าฟอร์ด<%/InsertIf%> <%InsertElse%> <%${user['FirstName']}%> <%/InsertElse%></strong><br />ยินดีต้อนรับสู่ครอบครัวฟอร์ด'''
	copy = '''
ฟอร์ดขอขอบคุณที่คุณเลือกเรา
ให้เป็นเพื่อนร่วมทางของคุณ
เราจะส่งข่าวสาร
และข้อมูลกิจกรรมที่เป็นประโยชน์
ให้แก่คุณอย่างต่อเนื่อง
เพราะคุณเป็นส่วนหนึ่ง
ของครอบครัวฟอร์ด
ขอให้คุณมีความสุขกับการขับขี่
Ranger ค่ะ '''

[[module]] #Banner Image No Link
path = '''email_modules/image/banner_nolink'''
color = '''white'''

	image = '''th_edm1_wildtrak_2017420'''

[[module]] #Cover 01
path='email_modules/cover/01'
color='black'

	title = '''แกร่งแค่ไหน?
    อึดแค่ไหน?
	โหดได้แค่ไหน?'''
	copy = '''ดู!...และพิสูจน์ความแกร่งของ
	ฟอร์ด เรนเจอร์
    ด้วยตัวคุณเอง'''
	cta1_text = '''ชมวิดีโอที่นี่'''
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

title1 = ''' ศูนย์ข้อมูลเพื่อเจ้าของ
รถฟอร์ด'''
	copy1 = '''รวมทุกเรื่องที่คุณต้องการในหนึ่งเดียว'''
	cta1a_text = '''ดูศูนย์ข้อมูลเจ้าของรถฟอร์ด'''
	cta1a_url = '''https://www.ford.co.th/owner/owner-unauthenticated/'''
	cta1a_link_name = '''owner_center'''
	cta1b_text = ''''''
	cta1b_url = ''''''
	cta1b_link_name = ''''''
	cta1c_text = ''''''
	cta1c_url = ''''''
	cta1c_link_name = ''''''
	icon1 = '''th_edm1_ownersite_20160801'''
	title2 = '''เรียนรู้การใช้งาน SYNC&trade;'''
	copy2 = '''รถยนต์ฟอร์ดของคุณมาพร้อมกับ<br />ระบบสั่งงานด้วยเสียง SYNC&trade;<br />เพื่อการสั่งงาน<br />โดยไม่ต้องปล่อยมือจากพวงมาลัย'''
	cta2a_text = '''เรียนรู้เพิ่มเติมเกี่ยวกับ SYNC&trade;'''
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

title='''อุปกรณ์ตกแต่งสำหรับคุณ</span>'''
copy='''ให้ฟอร์ด
เรนเจอร์ของคุณ
ล้ำหน้าไปอีกขั้น
ด้วยอุปกรณ์ตกแต่งล่าสุด
ฝาปิดกระบะท้าย
พร้อมชุดติดตั้งกุญแจล๊อค
ฝาปิดกระบะท้าย
มูลค่า 60,893.
ที่ทำ</span>จาก
อลูมิเนียมคุณภาพสูง<br />
น้ำหนักเบา
ปกป้องสัมภาระของคุณ<br />
ได้อย่างปลอดภัย'''
cta1_text='''คลิกเพื่อชมอุปกรณ์เสริมทั้งหมด'''
cta1_url='''https://www.ford.co.th/trucks/ranger/accessories/#overlay/content/ford/th/th_th/ranger-content/image-overlays/accessories/nudge-bar.html'''
cta1_link_name = '''acc_new_ranger'''
image='''TH_edm1a_wildtrak_roller_shutter_20170508'''

[[module]] #Split 04
path='email_modules/split/04'
color='green'

	title='''<span style="font-family:Tahoma, Verdana, Sans-serif">ประหยัดและคุ้มค่ากว่า</span>'''
	copy='''<span style="font-family:Tahoma, Verdana, Sans-serif;">
รับส่วนลดเพิ่มสูงสุด 10%
หรือ 3,700 บาท
กับโปรแกรมบำรุงรักษารถยนต์
ตามระยะ(SSP)
พิเศษรับสิทธิ์
ผ่อน 0% นาน 10 เดือน
เมื่อชำระผ่าน
บัตรเครดิตกสิกรไทย
ตั้งแต่วันนี้ - วันที่ 31 สิงหาคม 2560'''
	cta1_text='''<span style="font-family:Tahoma, Verdana, Sans-serif">คลิกเพื่อดูรายละเอียดและราคา ></span>'''
cta1_url='''https://www.ford.co.th/owner/schedule-service/'''
cta1_icon='''more'''
cta1_link_name = '''SSP'''
image = '''th_edm5a_specialoffer_20160801'''

[[module]]
path='email_modules/cover/01'

color='slatescreen'
title='''<span style="font-family:Tahoma, Verdana, Sans-serif">ถาม ตอบ</span>'''
copy='''<span style="font-family:Tahoma, Verdana, Sans-serif"><span style=" white-space:nowrap;">Q: ทำไมจึงต้องมี</span>
<span style=" white-space:nowrap;">Ford Roadside Assistance</span>
<span style=" white-space:nowrap;">สำหรับรถใหม่</span><br /><br />
<span style=" white-space:nowrap;">A: เพราะระบบช่วยเหลือฉุกเฉินของเรา</span>
<span style=" white-space:nowrap;">ไม่เพียงครอบคลุมการคุ้มครองอะไหล่</span>
<span style=" white-space:nowrap;">และเครื่องยนต์</span>
<span style="white-space:nowrap;">ตลอดอายุการใช้งานเท่านั้น</span>
<span style=" white-space:nowrap;">แต่ยังรวมถึงการช่วยเหลือ</span>
<span style=" white-space:nowrap;">ในกรณีเหตุฉุกเฉินอื่นๆ</span>
<span style=" white-space:nowrap;">เช่น</span>
<span style=" white-space:nowrap;">การลืมกุญแจไว้ในรถ</span><br />
<span style=" white-space:nowrap;">หรือเมื่อน้ำมันหมดกลางทาง เป็นต้น</span></span>'''
cta1_text='''<span style="font-family:Tahoma, Verdana, Sans-serif"><span style=" white-space:nowrap;">อ่านต่อ</span></span>'''
cta1_url='''http://on.fb.me/1utXwYz'''
cta1_link_name = '''QA'''
cta1_icon='''more'''


[[module]] #TH Social
path='email_modules/footer/th/social'
color='white'

[[module]] #TH Online
path='email_modules/footer/th/online'
color='white'

+++