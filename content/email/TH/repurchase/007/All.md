+++
markets = ["th"]
title = '''TH Repurchase 007 All'''

[[module]]
path='email_modules/preheader'
color='''nothing'''

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
	<span style="white-space:nowrap;">ประหยัดสุดคุ้ม</span> 
	<span style="white-space:nowrap;">ในเดือนพฤษภาคม</span> 
	<span style="white-space:nowrap;">และ มิถุนายน</span></span>'''
	copy = '''<span style="font-family:Tahoma, Verdana, Sans-serif;">
	สวัสดีคุณ <%InsertIf expression="${(user['FirstName'] == null || user['FirstName'] == '-')}" id="FirstName" %>
	<br />ท่านลูกค้าฟอร์ด<%/InsertIf%> <%InsertElse%> <%${user['FirstName']}%> <%/InsertElse%><br /><br />

	<span style="white-space:nowrap;">เราหวังว่าคุณจะได้รับความพึงพอใจ</span>
	<span style="white-space:nowrap;">จากการเป็นเจ้าของรถฟอร์ด <%${user.CustomAttribute['Model']}%> </span><br />
	<span style="white-space:nowrap;">และได้เข้ามาร่วมเป็นส่วนหนึ่ง</span>
	<span style="white-space:nowrap;">ในครอบครัวของเรา!</span><br /><br />

	<span style="white-space:nowrap;">หากคุณกำลังพิจารณามองหารถคันใหม่</span><br />
	<span style="white-space:nowrap;">เราอยากเชิญคุณ</span>
	<span style="white-space:nowrap;">มาพบกับข้อเสนอสุดพิเศษ</span><br />
	<span style="white-space:nowrap;">เพียงลงทะเบียนทดลองขับ</span><br />
	<span style="white-space:nowrap;">ที่โชว์รูมฟอร์ด</span><br /><br />

	<span style="white-space:nowrap;">ออกรถฟอร์ด เรนเจอร์ Wildtrak</span>
	<span style="white-space:nowrap;">รุ่นที่มีระบบแผนที่นำทาง</span><br /> 
	<span style="white-space:nowrap;">ภายในวันที่ 30 มิถุนายน 2560</span>
	<span style="white-space:nowrap;">รับฟรีประกันภัยชั้นหนึ่ง</span><br />
	<span style="white-space:nowrap;">พร้อมสิทธิ์ผ่อนขั้นต่ำ</span>
	<span style="white-space:nowrap;">เพียงเดือนละ 8,999 บาท</span><br />
	<span style="white-space:nowrap;">และฟอร์ดยังมีข้อเสนอสุดพิเศษ</span>
	<span style="white-space:nowrap;">สำหรับรถฟอร์ด เอเวอร์เรส</span><br /> 
	<span style="white-space:nowrap;">และ ฟอร์ด เอคโคสปอร์ต</span><br /><br />

	<span style="white-space:nowrap;">หากคุณสนใจ</span>
	<span style="white-space:nowrap;">สามารถติดตามข้อเสนอราคาพิเศษ</span></span>'''
	cta1_text='''<span style="font-family:Tahoma, Verdana, Sans-serif">ข้อเสนอพิเศษ</span>'''
	cta1_url = '''https://www.ford.co.th/buying/latest-offers/'''
	cta1_link_name = '''latest_offers'''
	cta1_icon = '''more'''

[[module]] #Banner Image No Link
path = '''email_modules/image/banner_nolink'''
color = '''white'''

	image = '''th_edm1_wildtrak_2017420'''

[[module]]
path='email_modules/split/03'
color='green'

title='''<span style="font-family:Tahoma, Verdana, Sans-serif">สิทธิพิเศษสำหรับ<br />ลูกค้าฟอร์ด</span>'''
copy='''<span style="font-family:Tahoma, Verdana, Sans-serif;">
	<span style="white-space:nowrap;">เมื่อซื้อรถยนต์ฟอร์ดคันต่อไปทุกรุ่น</span> 
	<span style="white-space:nowrap;">(ยกเว้นฟอร์ด โฟกัส)</span> 
	<span style="white-space:nowrap;">รับส่วนลดเพิ่ม 10,000 บาททันที</span> 
	<span style="white-space:nowrap;">ข้อเสนอสุดพิเศษนี้</span> 
	<span style="white-space:nowrap;">สำหรับ</span>
	<span style="white-space:nowrap;">ริการ 1-30 มิถุนายน พ.ศ. 2560</span> 
	<span style="white-space:nowrap;">นี้เท่านั้น</span> 
</span>'''
cta1_text='''<span style="font-family:Tahoma, Verdana, Sans-serif">ดูเพิ่มเติม</span>'''
cta1_url='''https://www.ford.co.th/loyaltyprogram2017/'''
cta1_icon='''more'''
cta1_link_name = '''special_offer'''
image = '''th_edm5a_specialoffer_20160801'''

[[module]] #Dual 01
path='email_modules/dual/01'
color='white'

	icon1 = '''th_edm2_svc_wrench_20160801'''
	title1 = '''<span style="font-family:Tahoma, Verdana, Sans-serif">ฟรีค่าแรงซ่อมบำรุง<br />5 ครั้ง</span>'''
	copy1 = '''<span style="font-family:Tahoma, Verdana, Sans-serif">

<span style=" white-space:nowrap;">เพียงคุณตัดสินใจเป็นเจ้าของฟอร์ดรุ่นใหม่</span> 
<span style=" white-space:nowrap;">ฟรีค่าแรงเช็คระยะ 5 ครั้ง</span> 
<span style=" white-space:nowrap;">คลิกเพื่อดูรายละเอียดเพิ่มเติมที่นี่</span>

</span>'''
	icon2 = '''th_edm2_ownerprofile_20160801'''
	title2 = '''<span style="font-family:Tahoma, Verdana, Sans-serif">ข้อมูลของคุณมีการ<br />เปลี่ยนแปลงหรือไม่</span>'''
	copy2 = '''<span style="font-family:Tahoma, Verdana, Sans-serif">

กรุณาอัพเดทข้อมูลของคุณ <br />
<span style=" white-space:nowrap;">เพื่อให้คุณ</span><span style=" white-space:nowrap;">ไม่พลาด</span><span style=" white-space:nowrap;">ข้อเสนอ</span><span style=" white-space:nowrap;">พิเศษ</span>ต่างๆ <br />
<span style=" white-space:nowrap;">จากฟอร์ด</span>

</span>'''
	cta1_text = '''<span style="font-family:Tahoma, Verdana, Sans-serif">ค้นหาตัวแทนจำหน่าย</span>'''
	cta1_url = '''https://www.ford.co.th/locate-a-dealer/'''
	cta1_link_name = '''find_dealer'''
	cta2_text = '''<span style="font-family:Tahoma, Verdana, Sans-serif">อัพเดทข้อมูล</span>'''
	cta2_url = '''https://www.ford.co.th/#/overlay/content/ford/th/th_th/site-wide-content/overlays/form-overlay/login'''
	cta2_link_name = '''anything_changed'''


[[module]] #TH Social
path='email_modules/footer/th/social'
color='white'

[[module]] #TH Online
path='email_modules/footer/th/online'
color='white'

+++