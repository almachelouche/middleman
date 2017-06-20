+++
markets = ["th"]
title = '''TH Welcome First New Ranger 010_No Line Break'''

[[module]]
path='email_modules/preheader'
color='''nothing'''

preheader = '''ฟอร์ดขอขอบคุณที่คุณเลือกเรา ให้เป็นเพื่อนร่วมทางของคุณ เราจะส่งข่าวสาร และข้อมูลกิจกรรมที่เป็นประโยชน์ ให้แก่คุณอย่างต่อเนื่อง เพราะคุณเป็นส่วนหนึ่ง ของครอบครัวฟอร์ด ขอให้คุณมีความสุขกับการขับขี่ Ranger ค่ะ '''

[[module]] #Header Logo
path='email_modules/header/logo'
color='white'

	image = '''white'''
	url_link = '''https://www.ford.co.th/'''

[[module]] #Cover 01
path='email_modules/cover/01'
color='''white'''
 
	title = '''<span style="font-family:Tahoma, Verdana, Sans-serif"><strong>สวัสดีค่ะ คุณ <%InsertIf expression="${(user['FirstName'] == null || user['FirstName'] == '-')}" id="FirstName" %>ท่านลูกค้าฟอร์ด<%/InsertIf%> <%InsertElse%> <%${user['FirstName']}%> <%/InsertElse%></strong><br />ยินดีต้อนรับสู่ครอบครัวฟอร์ด</span>'''
	copy = '''<span style="font-family:Tahoma, Verdana, Sans-serif">ฟอร์ดขอขอบคุณที่คุณเลือกเรา ให้เป็นเพื่อนร่วมทางของคุณ<br /><br />เราจะส่งข่าวสาร และข้อมูลกิจกรรมที่เป็นประโยชน์ ให้แก่คุณอย่างต่อเนื่อง เพราะคุณเป็นส่วนหนึ่ง ของครอบครัวฟอร์ด<br /><br />ขอให้คุณมีความสุขกับการขับขี่ Ranger ค่ะ</span>'''

[[module]] #Banner Image No Link
path = '''email_modules/image/banner_nolink'''
color = '''white'''

	image = '''th_edm1_wildtrak_2017420'''

[[module]] #Cover 01
path='email_modules/cover/01'
color='black'

	title = '''<span style="font-family:Tahoma, Verdana, Sans-serif;">แกร่งแค่ไหน? อึดแค่ไหน? โหดได้แค่ไหน?</span>'''
	copy = '''<span style="font-family:Tahoma, Verdana, Sans-serif">ดู!...และพิสูจน์ความแกร่งของ ฟอร์ด เรนเจอร์ ด้วยตัวคุณเอง</span>'''
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

title1 = '''<span style="font-family:Tahoma, Verdana, Sans-serif">ศูนย์ข้อมูลเพื่อเจ้าของ<br />รถฟอร์ด</span>'''
	copy1 = '''<span style="font-family:Tahoma, Verdana, Sans-serif">รวมทุกเรื่องที่คุณต้องการในหนึ่งเดียว</span>'''
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
	copy2 = '''<span style="font-family:Tahoma, Verdana, Sans-serif"><span style="color:#616161; font-size:16px">รถยนต์ฟอร์ดของคุณมาพร้อมกับ ระบบสั่งงานด้วยเสียง SYNC&trade; เพื่อการสั่งงาน โดยไม่ต้องปล่อยมือจากพวงมาลัย</span></span>'''
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
text1 = '''<span style="font-family:Tahoma, Verdana, Sans-serif">แอพพลิเคชั่นเพื่อเจ้าของรถฟอร์ด เพื่อการดูแลรถฟอร์ดที่ง่ายขึ้น</span>'''
text2 = '''<span style="font-family:Tahoma, Verdana, Sans-serif; font-Size: 14px">
<ul style="margin: 20px; padding: 0;">
<li>ข้อมูลการบริการดูแล รักษารถยนต์ตามระยะ</li>
<li>ค้นหาตัวแทนจำหน่ายใกล้เคียง</li>
<li>รับชมวิดีโอ How-To คู่มือการเป็นเจ้าของรถฟอร์ด แบบครบครัน</li>
<li>รู้จักกับสัญลักษณ์ บนแผงหน้าปัดควบคุมรถ</li>
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
copy='''<span style="font-family:Tahoma, Verdana, Sans-serif">ให้ฟอร์ด เรนเจอร์ของคุณ ล้ำหน้าไปอีกขั้น ด้วยอุปกรณ์ตกแต่งล่าสุด ฝาปิดกระบะท้าย พร้อมชุดติดตั้งกุญแจล๊อค ฝาปิดกระบะท้าย มูลค่า 60,893.- ที่ทำ จาก อลูมิเนียมคุณภาพสูง น้ำหนักเบา ปกป้องสัมภาระของคุณ ได้อย่างปลอดภัย</span>'''
cta1_text='''<span style="font-family:Tahoma, Verdana, Sans-serif">คลิกเพื่อชมอุปกรณ์เสริมทั้งหมด</span>'''
cta1_url='''https://www.ford.co.th/trucks/ranger/accessories/#overlay/content/ford/th/th_th/ranger-content/image-overlays/accessories/nudge-bar.html'''
cta1_link_name = '''acc_new_ranger'''
image='''TH_edm1a_wildtrak_roller_shutter_20170508'''

[[module]]
path='email_modules/cover/01'

color='slatescreen'
title='''<span style="font-family:Tahoma, Verdana, Sans-serif">ถาม ตอบ</span>'''
copy='''<span style="font-family:Tahoma, Verdana, Sans-serif">Q: ทำไมจึงต้องมี Ford Roadside Assistance สำหรับรถใหม่<br /><br />A: เพราะระบบช่วยเหลือฉุกเฉินของเรา ไม่เพียงครอบคลุมการคุ้มครองอะไหล่ และเครื่องยนต์ตลอดอายุการใช้งานเท่านั้น แต่ยังรวมถึงการช่วยเหลือ ในกรณีเหตุฉุกเฉินอื่นๆ เช่น การลืมกุญแจไว้ในรถ หรือเมื่อน้ำมันหมดกลางทาง เป็นต้น</span>'''
cta1_text='''<span style="font-family:Tahoma, Verdana, Sans-serif">อ่านต่อ</span>'''
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