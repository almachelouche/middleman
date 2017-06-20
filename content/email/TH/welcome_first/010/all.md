+++
markets = ["th"]
title = '''TH Welcome First 010 All'''
draft = true

[[module]]
path='email_modules/preheader'

	preheader = '''ฟอร์ดขอขอบคุณที่คุณเลือกเรา ให้เป็นเพื่อนร่วมทางของคุณ เราจะส่งข่าวสาร และข้อมูลกิจกรรมที่เป็นประโยชน์ ให้แก่คุณอย่างต่อเนื่อง เพราะคุณเป็นส่วนหนึ่ง ของครอบครัวฟอร์ด ขอให้คุณมีความสุขกับการขับขี่ Ranger ค่ะ '''

[[module]] #Header Logo
path='email_modules/header/logo'
color='white'

	image = '''white'''
	url_link = '''http://www.ford.co.th'''

[[module]] #Cover 01
path='email_modules/cover/01'
color='''white'''
 
	title = '''<span style="font-family:Tahoma, Verdana, Sans-serif"><strong>สวัสดีค่ะ คุณ <%InsertIf expression="${(user['FirstName'] == null || user['FirstName'] == '-')}" id="FirstName" %>ท่านลูกค้าฟอร์ด<%/InsertIf%> <%InsertElse%> <%${user['FirstName']}%> <%/InsertElse%></strong><br />ยินดีต้อนรับสู่ครอบครัวฟอร์ด</span>'''
	copy = '''<span style="font-family:Tahoma, Verdana, Sans-serif"><span style=" white-space:nowrap;">ฟอร์ดขอขอบคุณที่คุณเลือกเรา</span>
<span style=" white-space:nowrap;">ให้เป็นเพื่อนร่วมทางของคุณ</span>
<br /><br />
<span style=" white-space:nowrap;">เราจะส่งข่าวสาร</span>
<span style=" white-space:nowrap;">และข้อมูลกิจกรรมที่เป็นประโยชน์</span>
<span style=" white-space:nowrap;">ให้แก่คุณอย่างต่อเนื่อง</span> 
<span style=" white-space:nowrap;">เพราะคุณเป็นส่วนหนึ่ง</span>
<span style=" white-space:nowrap;">ของครอบครัวฟอร์ด</span>
<br /><br />
<span style=" white-space:nowrap;">ขอให้คุณมีความสุขกับการขับขี่</span> 
<span style=" white-space:nowrap;">Ranger ค่ะ </span></span>'''

[[module]] #Banner Image No Link
path = '''email_modules/image/banner_nolink'''
color = '''white'''

	image = '''th_edm1&4_np_newranger_20160801'''

[[module]] #Cover 01
path='email_modules/cover/01'
color='black'

	title = '''<span style="font-family:Tahoma, Verdana, Sans-serif"><span style="white-space:nowrap;">ทางยิ่งยาก </span>
										<span style="white-space:nowrap;"> ฟอร์ด เรนเจอร์ ก็ยิ่งฉลาด </span>
										<span style="white-space:nowrap;"> และกล้าแกร่ง </span></span>'''
	copy = '''<span style="font-family:Tahoma, Verdana, Sans-serif"><span style="white-space:nowrap;">เพื่อสาธิตความสามารถอันยอดเยี่ยมเหนือใคร</span>
<span style="white-space:nowrap;"> ในการลุยน้ำได้ลึกถึง 800 มิลลิเมตร</span><br />
<span style="white-space:nowrap;">และดีไซน์แบบแอโรไดนามิกของ</span>
<span style="white-space:nowrap;"> ฟอร์ด เรนเจอร์	</span>
<span style="white-space:nowrap;"> เราขอจัดเต็ม!</span></span>'''
	cta1_text = '''<span style="font-family:Tahoma, Verdana, Sans-serif">ชมวิดีโอที่นี่</span>'''
	cta1_url = '''http://www.ford.co.th/trucks/ranger/sot2/'''
	cta1_link_name = '''ranger_sot'''
	cta1_icon = '''more'''

[[module]] #Banner Image
path='email_modules/image/banner'
color='white'

	image = '''th_edm4a_smartranger_20161018'''
	url_link = '''http://www.ford.co.th/trucks/ranger/sot2/'''

[[module]] #Dual 04
path='email_modules/dual/04'
color='white'

title1 = '''<span style="font-family:Tahoma, Verdana, Sans-serif">ศูนย์ข้อมูลเพื่อเจ้าของรถฟอร์ด</span>'''
	copy1 = '''<span style="font-family:Tahoma, Verdana, Sans-serif"><span style=" white-space:nowrap;">รวมทุกเรื่องที่คุณต้องการในหนึ่งเดียว</span></span>'''
	cta1a_text = '''<span style="font-family:Tahoma, Verdana, Sans-serif"><br /><br />ดูศูนย์ข้อมูลเจ้าของรถฟอร์ด</span>'''
	cta1a_url = '''https://www.ford.co.th/owner'''
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
	cta2a_url = '''http://www.ford.co.th/engineering/sync/'''
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

title = '''<span style="font-family:Tahoma, Verdana, Sans-serif">ให้คุณขับขี่ด้วยความมั่นใจ<br /> <span style="white-space:nowrap;">ดาวน์โหลดแอพ</span><br />Ford Roadside Assistance</span>'''
	text1 = '''<span style="font-family:Tahoma, Verdana, Sans-serif"><span style="white-space:nowrap;">ฟังก์ชันต่าง ๆ ในแอพพลิเคชั่น</span><br /><span style="white-space:nowrap;">Ford Roadside Assistance</span><br /><span style="white-space:nowrap;">สามารถช่วยคุณได้มากมาย เช่น</span></span>'''
		text2 = '''<span style="font-family:Tahoma, Verdana, Sans-serif"><ul style="margin: 20px; padding: 0;"><li><span style=" white-space:nowrap;">แชร์โลเคชั่นของคุณอัตโนมัติ</span></li><li><span style=" white-space:nowrap;">ระบบติดตามรถช่วยเหลือฉุกเฉิน</span></li><li><span style=" white-space:nowrap;">ค้นหาศูนย์บริการฟอร์ดใกล้คุณ</span></li><li><span style=" white-space:nowrap;">หลีกเลี่ยงการจราจรติดขัดด้วย</span><br />"Live Traffic"</li></ul></span>'''
	cta1_text = '''iOS'''
	cta1_url = '''https://itunes.apple.com/th/app/ford-roadside-assistance/id834061377?mt=8'''
	cta1_link_name = '''rsa_iphone'''
	cta2_text = '''Android'''
	cta2_url = '''https://play.google.com/store/apps/details?id=com.aga.rsa.th.ford&hl=th'''
	cta2_link_name = '''rsa_andriod'''
	image = '''th_edm1&4_rsa_app_20161026'''

[[module]]
path='email_modules/cover/01'

color='slatescreen'
title='''<span style="font-family:Tahoma, Verdana, Sans-serif">ถาม ตอบ</span>'''
copy='''<span style="font-family:Tahoma, Verdana, Sans-serif"><span style=" white-space:nowrap;">Q: ทำไมจึงต้องมี</span>
<span style=" white-space:nowrap;">Ford Roadside Assistance</span>
<span style=" white-space:nowrap;">สำหรับรถใหม่</span><br /><br />
<span style=" white-space:nowrap;">A: เพราะระบบช่วยเหลือฉุกเฉินของเรา</span>
<span style=" white-space:nowrap;">ไม่เพียงครอบคลุมการคุ้มครองอะไหล่</span>
<span style=" white-space:nowrap;">และเครื่องยนต์ตลอดอายุการใช้งานเท่านั้น</span>
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