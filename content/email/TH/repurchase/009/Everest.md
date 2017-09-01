+++
markets = ["th"]
title = '''TH Repurchase 009 All Everest'''

[[module]]
path='email_modules/preheader'

	preheader = '''พบสุดยอดข้อเสนอสุดพิเศษ สำหรับฟอร์ดคันใหม่ของคุณ'''

[[module]] #Header Logo
path='email_modules/header/logo'
color='white'

	image = '''white'''
	url_link = '''https://www.ford.co.th/'''

[[module]] #Cover 01
path='email_modules/cover/01'
color='white'

	title = '''<span style="font-family:Tahoma, Verdana, Sans-serif;">
	<span style="white-space:nowrap;">พิเศษสำหรับคุณ</span> 
	<span style="white-space:nowrap;">ในเดือนกันยายน</span></span>'''
	copy = '''<span style="font-family:Tahoma, Verdana, Sans-serif;">
	สวัสดีคุณ <%InsertIf expression="${(user['FirstName'] == null || user['FirstName'] == '-')}" id="FirstName" %>
	<br />ท่านลูกค้าฟอร์ด<%/InsertIf%> <%InsertElse%> <%${user['FirstName']}%> <%/InsertElse%><br /><br />

	<span style="white-space:nowrap;">เราหวังว่าคุณจะได้รับความพึงพอใจ</span>
	<span style="white-space:nowrap;">จากการเป็นเจ้าของรถฟอร์ด</span> 
	<span style="white-space:nowrap;"><%${user.CustomAttribute['Model']}%> </span><br />
	<span style="white-space:nowrap;">และได้เข้ามาร่วมเป็นส่วนหนึ่ง</span>
	<span style="white-space:nowrap;">ในครอบครัวของเรา!</span><br /><br />

	<span style="white-space:nowrap;">หากคุณกำลังพิจาร</spam>ณา<span style="white-space:nowrap;">มองหารถคันใหม่</span><br />
	<span style="white-space:nowrap;">เราอยากเชิญคุณ</span>
	<span style="white-space:nowrap;">มาพบกับข้อเสนอสุดพิเศษ</span><br />
    <span style="white-space:nowrap;">เพียงลงทะเบียนทดลองขับ ที่โชว์รูมฟอร์ด</span>
    <br />
    <br />
	<span style="white-space:nowrap;">ออกรถฟอร์ด เรนเจอร์ Wildtrak รุ่นที่มีระบบแผนที่นำทาง</span><br />
	<span style="white-space:nowrap;">ภายในวันที่ 30 ก.ย. 60 ดาวน์เพียง 89,999 บาท</span><br /> 
	<span style="white-space:nowrap;">หรือผ่อนเพียง 8,999 บาท พร้อมรับฟรีประกันภัยชั้นหนึ่ง</span><br />
	<span style="white-space:nowrap;">และฟอร์ดยังมีข้อเสนอสุดพิเศษ สำหรับรถฟอร์ดเอเวอเรสต์</span><br />
	<span style="white-space:nowrap;">ฟอร์ดเอคโค่สปอร์ต และฟอร์ดเฟียสต้า</span>
    <br />
    <br />
	<span style="white-space:nowrap;">หากคุณสนใจ</span>
	<span style="white-space:nowrap;">สามารถติดตามข้อเสนอราคาพิเศษ</span></span>'''
	cta1_text='''<span style="font-family:Tahoma, Verdana, Sans-serif">ข้อเสนอพิเศษ</span>'''
	cta1_url = '''https://www.ford.co.th/buying/latest-offers/'''
	cta1_link_name = '''latest_offers'''
	cta1_icon = '''more'''


[[module]]
path='email_modules/split/03'
color='green'

title='''<span style="font-family:Tahoma, Verdana, Sans-serif">สิทธิพิเศษสำหรับ<br />ลูกค้าฟอร์ด</span>'''
copy='''<span style="font-family:Tahoma, Verdana, Sans-serif;">
<span style="white-space:nowrap;">รับส่วนลดเพิ่มทันที</span> 
<span style="white-space:nowrap;">10,000 บาท</span> 
<span style="white-space:nowrap;">เมื่อซื้อรถยนต์ฟอร์ดคันต่อไปทุกรุ่น</span> 
<span style="white-space:nowrap;">(ยกเว้นฟอร์ด โฟกัส)</span><br /> 
<span style="white-space:nowrap;">ตั้งแต่</span> 
<span style="white-space:nowrap;">วันที่ 1 สิงหาคม</span> 
<span style="white-space:nowrap;">ถึง 30 กันยายน 2560</span>
<span style="white-space:nowrap;">นี้เท่านั้น</span></span>'''
cta1_text='''<span style="font-family:Tahoma, Verdana, Sans-serif">ดูเพิ่มเติม</span>'''
cta1_url='''https://www.ford.co.th/loyaltyprogram2017/'''
cta1_icon='''more'''
cta1_link_name = '''special_offer'''
image = '''th_edm5a_specialoffer_20160801'''

[[module]] #Banner Image No Link
path = '''email_modules/image/banner_nolink'''
color = '''white'''

	image='''th_edm6_Rangerday_Everest_20170804'''

[[module]] #Dual 01
path='email_modules/dual/01'
color='white'

	icon1 = '''th_edm2_svc_wrench_20160801'''
	title1 = '''<span style="font-family:Tahoma, Verdana, Sans-serif">ฟรีค่าแรงซ่อมบำรุง<br />5 ครั้ง</span>'''
	copy1 = '''<span style="font-family:Tahoma, Verdana, Sans-serif">

<span style="white-space:nowrap;">เพียงคุณตัดสินใจเป็นเจ้าของฟอร์ดรุ่นใหม่</span> 
<span style="white-space:nowrap;">ฟรีค่าแรงเช็คระยะ 5 ครั้ง</span>

</span>'''
	icon2 = '''th_edm2_ownerprofile_20160801'''
	title2 = '''<span style="font-family:Tahoma, Verdana, Sans-serif">ข้อมูลของคุณมีการ<br />เปลี่ยนแปลงหรือไม่</span>'''
	copy2 = '''<span style="font-family:Tahoma, Verdana, Sans-serif">

กรุณาอัพเดทข้อมูลของคุณ <br />
<span style=" white-space:nowrap;">เพื่อให้คุณ</span><span style=" white-space:nowrap;">ไม่พลาด</span><span style=" white-space:nowrap;">ข้อเสนอ</span><span style=" white-space:nowrap;">พิเศษ</span>ต่างๆ <br />
<span style=" white-space:nowrap;">จากฟอร์ด</span>

</span>'''
	cta1_text = '''<span style="font-family:Tahoma, Verdana, Sans-serif">คลิกเพื่อดูรายละเอียดเพิ่มเติม</span>'''
	cta1_url = '''https://www.ford.co.th/owner/maintenance/'''
	cta1_link_name = '''find_dealer'''
	cta2_text = '''<span style="font-family:Tahoma, Verdana, Sans-serif">อัพเดทข้อมูล</span>'''
	cta2_url = '''https://www.ford.co.th/#/overlay/content/ford/th/th_th/site-wide-content/overlays/form-overlay/login'''
	cta2_link_name = '''anything_changed'''


[[module]] #TH Social
path='email_modules/footer/th/social'
color='white'

[[module]] #Footer Disclaimer
path='email_modules/footer/disclaimer'
color='white'

	text='''
* คำนวณจากฟอร์ด Everest 2.2L Titanium 4x2 AT ที่ดาวน์ 30% ผ่อนนาน 60 เดือน, ผ่อนต่อเดือน 9,999 บาท 
งวดที่ 1-12 และ 19,501 บาท สำหรับงวดที่ 13-60 • เมื่อจัดไฟแนนซ์ผ่านฟอร์ด ลีสซิ่งเท่านั้น • เงื่อนไขฟรีประกันภัยชั้นหนึ่ง
เฉพาะบริษัทประกันภัย ที่เข้าร่วมรายการดังนี้ กรุงเทพประกันภัย ประกันภัยคุ้มภัย วิริยะประกันภัย 
แอกซ่าประกันภัย และแอลเอ็มจีประกันภัย • มูลค่าประกันภัยขึ้นอยู่กับรถและบริษัทประกันภัยที่เลือก 
 '''


[[module]] #TH Online
path='email_modules/footer/th/online'
color='white'

+++