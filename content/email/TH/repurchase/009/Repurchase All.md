+++
markets = ["th"]
title = '''TH Repurchase All'''

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
	<span style="white-space:nowrap;">ในเดือนพฤศจิกายน</span>
    '''
	copy = '''
    <span style="font-family:Tahoma, Verdana, Sans-serif;">
	สวัสดีคุณ <%InsertIf expression="${(user['FirstName'] == null || user['FirstName'] == '-')}" id="FirstName" %>
	<br />ท่านลูกค้าฟอร์ด<%/InsertIf%> <%InsertElse%> <%${user['FirstName']}%> <%/InsertElse%>
    <br />
    <br />
	<span style="white-space:nowrap;">เราหวังว่าคุณจะได้รับความพึงพอใจ</span>
	<span style="white-space:nowrap;">จากการเป็นเจ้าของรถฟอร์ด</span> 
	<span style="white-space:nowrap;"><%${user.CustomAttribute['Model']}%> </span>
    <br />
	<span style="white-space:nowrap;">และได้เข้ามาร่วมเป็นส่วนหนึ่ง</span>
	<span style="white-space:nowrap;">ในครอบครัวของเรา!</span>
    <br />
    <br />
	<span style="white-space:nowrap;">หากคุณกำลังพิจาร</spam>ณา<span style="white-space:nowrap;">มองหารถคันใหม่</span>
    <br />
    <br />
    <span style="white-space:nowrap;">เราขอมอบข้อเสนอสุดพิเศษให้กับคุณ</span>
    <br />
	<span style="white-space:nowrap;">ดอกเบี้ย 0% พร้อมฟรีประกันชั้น 1</span>
    <br />
	<span style="white-space:nowrap;">สำหรับรถฟอร์ดเรนเจอร์ ฟอร์ดเอเวอเรสต์ ฟอร์ดเอคโค่สปอร์ต</span>
    <br />
	<span style="white-space:nowrap;">ตั้งแต่วันนี้ ถึง 31 ธันวาคม 2560</span>
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
<span style="white-space:nowrap;">เมื่อซื้อรถฟอร์ดทุกรุ่น</span> 
<br />
<span style="white-space:nowrap;">ยกเว้นฟอร์ด โฟกัส ใหม่</span>
<br />
<span style="white-space:nowrap;">ตั้งแต่ วันที่1-30 พฤศจิกายน 2560 เท่านั้น</span>
'''
cta1_text='''<span style="font-family:Tahoma, Verdana, Sans-serif">ดูเพิ่มเติม</span>'''
cta1_url='''https://www.ford.co.th/loyaltyprogram2017/'''
cta1_icon='''more'''
cta1_link_name = '''special_offer'''
image = '''th_edm5a_specialoffer_20160801'''


[[module]] #Banner Image
path='email_modules/image/banner'
color='white'

	image='''th_edm5_yescampaign_20171108'''
	url_link='''https://www.ford.co.th/buying/latest-offers/'''
	url_link_name='''latest_offer'''

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
<span style=" white-space:nowrap;">1 สำหรับฟอร์ดเอคโค่ สปอร์ต ทุกรุ่น • เมื่อจัดไฟแนนซ์ ผ่านฟอร์ด ลีสซิ่ง เท่านั้น • เงื่อนไขฟรีประกันภัยชั้นหนึ่ง Ford Ensure</span>
<br />
<span style=" white-space:nowrap;">เฉพาะบริษัทประกันภัยที่เข้าร่วมรายการ ดังนี้ วิริยะประกันภัย ประกันภัยคุ้มภัย และแอลเอ็มจีประกันภัย</span>
<br />
<span style=" white-space:nowrap;">มูลค่าประกันภัยขึ้นอยู่กับรุ่นรถและบริษัทประกันภัยที่เลือก • มูลค่าประกันภัยต่ำสุดเท่ากับ 18,501 บาท</span>
<br />
<span style=" white-space:nowrap;">จาก วิริยะประกันภัย ประกันภัยคุ้มภัย และแอลเอ็มจีประกันภัย</span>
<br />
<span style=" white-space:nowrap;">2 สำหรับฟอร์ด เรนเจอร์ Open Cab & Double Cab XLT ทุกรุ่น • เมื่อจัดไฟแนนซ์ ผ่านฟอร์ด ลีสซิ่ง เท่านั้น</span>
<br />
<span style=" white-space:nowrap;">เงื่อนไขฟรีประกันภัยชั้นหนึ่ง Ford Ensure เฉพาะบริษัทประกันภัยที่เข้าร่วมรายการ ดังนี้ วิริยะประกันภัย ประกันภัยคุ้มภัย</span>
<br />
<span style=" white-space:nowrap;">และแอลเอ็มจีประกันภัย • มูลค่าประกันภัยขึ้นอยู่กับรุ่นรถและบริษัทประกันภัยที่เลือก</span>
<br />
<span style=" white-space:nowrap;">• มูลค่าประกันภัยต่ำสุดเท่ากับ 18,800 บาท จาก วิริยะประกันภัย ประกันภัยคุ้มภัย และแอลเอ็มจีประกันภัย</span>
<br />
<span style=" white-space:nowrap;">3 สำหรับฟอร์ด เอเวอเรสต์ รุ่น 2.2L Titanium 4x2 AT • ชำระค่างวดงวดแรก พร้อมวันที่รับรถยนต์</span> 
<br />
<span style=" white-space:nowrap;">• เมื่อจัดไฟแนนซ์ ผ่านฟอร์ด ลีสซิ่ง เท่านั้น • เงื่อนไขฟรีประกันภัยชั้นหนึ่ง Ford Ensure</span> 
<br />
<span style=" white-space:nowrap;">เฉพาะบริษัทประกันภัยที่เข้าร่วมรายการ ดังนี้ วิริยะประกันภัย ประกันภัยคุ้มภัย และ แอลเอ็มจีประกันภัย</span> 
<br />
<span style=" white-space:nowrap;">มูลค่าประกันภัยขึ้นอยู่กับรุ่นรถและบริษัทประกันภัยที่เลือก • มูลค่าประกันภัยต่ำสุดเท่ากับ</span> 
<br />
<span style=" white-space:nowrap;">22,001 บาท จาก วิริยะประกันภัย ประกันภัยคุ้มภัย และแอลเอ็มจีประกันภัย</span>
'''

[[module]] #TH Online
path='email_modules/footer/th/online'
color='white'


+++