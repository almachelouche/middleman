+++
markets = ["th"]
title = '''TH Repurchase BKK'''

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
<span style="white-space:nowrap;">รับเพิ่ม ส่วนลด 10,000 บาท</span>
<br />
<span style="white-space:nowrap;">สำหรับลูกค้ารถยนต์ฟอร์ด</span> 
<br />
<span style="white-space:nowrap;">และสมาชิกในครอบครัว</span>
<br />
<span style="white-space:nowrap;">เมื่อซื้อรถยนต์ฟอร์ดคันต่อไปทุกรุ่น</span>
<br />
<span style="white-space:nowrap;">(บิดามารดา, คู่สมรส,</span> 
<br />
<span style="white-space:nowrap;">พี่น้องร่วมบิดามารดา และบุตร)</span>
<br /> 
<span style="white-space:nowrap;">เมื่อซื้อรถฟอร์ดทุกรุ่น ยกเว้นฟอร์ด โฟกัส ใหม่</span>
<br />
<span style="white-space:nowrap;">ตั้งแต่ วันที่1-30 พฤศจิกายน 2560 เท่านั้น</span>
'''
cta1_text='''<span style="font-family:Tahoma, Verdana, Sans-serif">ดูเพิ่มเติม</span>'''
cta1_url='''https://www.ford.co.th/loyaltyprogram2017/'''
cta1_icon='''more'''
cta1_link_name = '''special_offer'''
image = '''th_edm5a_specialoffer_20160801'''

[[module]] #Banner Image No Link
path = '''email_modules/image/banner_nolink'''
color = '''white'''

	image=''''''

[[module]] #Cover 01
path='email_modules/cover/01'
color='white'

	title = '''<span style="font-family:Tahoma, Verdana, Sans-serif;">
	<span style="white-space:nowrap;"></span> 
	<span style="white-space:nowrap;"></span></span>'''
	copy = '''
	<span style="white-space:nowrap;">เราขอมอบข้อเสนอสุดพิเศษให้กับคุณ</span>
    <br />
	<span style="white-space:nowrap;">ดอกเบี้ย 0% พร้อมฟรีประกันชั้น 1</span>
    <br />
	<span style="white-space:nowrap;">สำหรับรถฟอร์ดเรนเจอร์ ฟอร์ดเอเวอเรสต์ ฟอร์ดเอคโค่สปอร์ต</span>
    <br />
	<span style="white-space:nowrap;">ตั้งแต่วันนี้ ถึง 31 ธันวาคม 2560</span>
	'''

[[module]] #Dual 01
path='email_modules/dual/01'
color='white'

	icon1 = '''th_edm2_svc_wrench_20160801'''
	title1 = '''<span style="font-family:Tahoma, Verdana, Sans-serif">ฟรีค่าแรงซ่อมบำรุง<br />5 ครั้ง</span>'''
	copy1 = '''<span style="font-family:Tahoma, Verdana, Sans-serif">

<span style="white-space:nowrap;">เพียงคุณตัดสินใจเป็นเจ้าของฟอร์ดรุ่นใหม่</span> 
<span style="white-space:nowrap;">ฟรีค่าแรงเช็คระยะ 5 ครั้ง</span> 
<span style="white-space:nowrap;">คลิกเพื่อดูรายละเอียดเพิ่มเติมที่นี่</span>

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
* คำนวณจากฟอร์ด เรนเจอร์ รุ่น 2.2L Wildtrak 4x2 HR MT รุ่นที่มีระบบแผนที่นำทาง ที่ดาวน์ 25% ผ่อนต่อเดือน 8,999 บาท
สำหรับงวดที่ 1-57 และ 362,900 บาท สำหรับงวดที่ 58 ดอกเบี้ยที่ระบุในสัญญาเช่าซื้อเท่ากับ 4.6% และรับรถ
ตั้งแต่ 15 สิงหาคม 2560 เป็นต้นไป โดยชำระค่างวดงวดแรกในเดือน มกราคม 2561 • เมื่อจัดไฟแนนซ์ผ่านฟอร์ด ลีสซิ่งเท่านั้น 
** เงื่อนไขฟรีประกันภัยชั้นหนึ่ง เฉพาะบริษัทประกันภัย ที่เข้าร่วมรายการดังนี้ กรุงเทพประกันภัย ประกันภัยคุ้มภัย วิริยะประกันภัย 
แอกซ่าประกันภัย และแอลเอ็มจีประกันภัย มูลค่าประกันภัยขึ้นอยู่กับรถและบริษัทประกันภัยที่เลือก 
มูลค่าประกันภัยต่ำสุด 22,401 บาท จากแอลเอ็มจีประกันภัย โปรโมชั่นนี้ตั้งแต่ วันที่ 1 สิงหาคม 2560 – 30 กันยายน 2560 
'''

[[module]] #TH Online
path='email_modules/footer/th/online'
color='white'


+++