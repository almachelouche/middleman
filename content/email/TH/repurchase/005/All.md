+++
markets = ["th"]
title = '''TH Repurchase 005 All'''

[[module]]
path='email_modules/preheader'
color='''nothing'''

preheader = '''พบข้อเสนอสุดพิเศษได้ที่โชว์รูมฟอร์ดตลอดเดือนเมษายนนี้ ฟอร์ดขอขอบคุณที่เป็นส่วนหนึ่ง ของครอบครัวฟอร์ดมาโดยตลอด'''

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
	<span style="white-space:nowrap;">รับเดือนเมษายน</span></span>'''
	copy = '''<span style="font-family:Tahoma, Verdana, Sans-serif;">
	สวัสดีคุณ <%InsertIf expression="${(user['FirstName'] == null || user['FirstName'] == '-')}" id="FirstName" %>
	<br />ท่านลูกค้าฟอร์ด<%/InsertIf%> <%InsertElse%> <%${user['FirstName']}%> <%/InsertElse%><br /><br />

	<span style="white-space:nowrap;">ฟอร์ดขอขอบคุณที่เป็นส่วนหนึ่ง</span>
	<span style="white-space:nowrap;">ของครอบครัวฟอร์ดมาโดยตลอด</span> 
	<span style="white-space:nowrap;">หากคุณกำลังพิจารณา</span>
	<span style="white-space:nowrap;">มองหารถคันใหม่</span> 
	<span style="white-space:nowrap;">เราอยากเชิญคุณ</span>
	<span style="white-space:nowrap;">มาพบกับข้อเสนอสุดพิเศษ</span> 
	<span style="white-space:nowrap;">เพียงลงทะเบียนทดลองขับ</span>ที่
	<span style="white-space:nowrap;">โชว์รูมฟอร์ด</span><br /><br />
	<span style="white-space:nowrap;">ออกรถฟอร์ด เรนเจอร์</span> 
	<span style="white-space:nowrap;">หรือ</span> 
	<span style="white-space:nowrap;">ฟอร์ด เอเวอร์เรส</span> 
	<span style="white-space:nowrap;">ภายในวันที่ 29 มีนาคม</span>
	<span style="white-space:nowrap;">ถึง</span> 
	<span style="white-space:nowrap;">วันที่ 30 เมษายน 2560</span> 
	<span style="white-space:nowrap;">รับดอกเบี้ยพิเศษ 0%</span> 
	<span style="white-space:nowrap;">พร้อมฟรี</span>
	<span style="white-space:nowrap;">ประกันภัยชั้นหนึ่ง<sup>*</sup></span><br /><br />
	<span style="white-space:nowrap;">และฟอร์ดยังมีข้อเสนอสุดพิเศษ</span>
	<span style="white-space:nowrap;">สำหรับรถฟอร์ด เอคโคสปอร์ต</span>
	<span style="white-space:nowrap;">หากคุณสนใจ</span> 
	<span style="white-space:nowrap;">สามารถติดตามข้อเสนอราคาพิเศษ</span><br />
	<span style="white-space:nowrap;">บนเว็บไซต์ของเราได้ทันที</span>
</span>'''
	cta1_text='''<span style="font-family:Tahoma, Verdana, Sans-serif">ข้อเสนอพิเศษ</span>'''
	cta1_url = '''https://www.ford.co.th/buying/latest-offers/'''
	cta1_link_name = '''latest_offers'''
	cta1_icon = '''more'''

[[module]] #Banner Image No Link
path = '''email_modules/image/banner_nolink'''
color = '''white'''

	image = '''th_edm5a_retail_campaign_2017328'''

[[module]]
path='email_modules/split/03'
color='green'

title='''<span style="font-family:Tahoma, Verdana, Sans-serif">สิทธิพิเศษสำหรับ<br />ลูกค้าฟอร์ด</span>'''
copy='''<span style="font-family:Tahoma, Verdana, Sans-serif;">
	<span style="white-space:nowrap;">เมื่อซื้อรถยนต์ฟอร์ดคันต่อไปทุกรุ่น</span> 
	<span style="white-space:nowrap;">(ยกเว้นฟอร์ด โฟกัส)</span> 
	<span style="white-space:nowrap;">รับส่วนลดเพิ่ม 10,000 บาททันที</span> 
	<span style="white-space:nowrap;">ข้อเสนอสุดพิเศษนี้</span> 
	<span style="white-space:nowrap;">สำหรับวันที่ 1 – 30 เมษายน พ.ศ. 2560</span> 
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

[[module]] #Footer Disclaimer
path='email_modules/footer/disclaimer'
color='white'
text='''<span style="font-family:Tahoma, Verdana, Sans-serif">
<span style="font-weight:bold">หมายเหตุ</span><br /><br />
1.
<span style=" white-space:nowrap;">สำหรับฟอร์ด เรนเจอร์</span> 
<span style=" white-space:nowrap;">รุ่น Wildtrak</span>
<span style=" white-space:nowrap;">(ยกเว้นฟอร์ด เรนเจอร์</span>
<span style=" white-space:nowrap;">รุ่นที่มีระบบแผนที่นำทาง)</span> 
<span style=" white-space:nowrap;">อัตราดอกเบี้ย 0% (งวดที่ 1-24)</span><br /> 
<span style=" white-space:nowrap;">โดยต้องเช่าซื้อรวม</span>
<span style=" white-space:nowrap;">60 เดือนเท่านั้น</span> 
<span style=" white-space:nowrap;">และอัตราดอกเบี้ยงวดที่ 25-60</span> 
<span style=" white-space:nowrap;">เป็นไปตามที่ธนาคารกำหนด</span> 
<span style=" white-space:nowrap;">ทั้งนี้อัตราดอกเบี้ย</span><br />
<span style=" white-space:nowrap;">ที่ระบุในสัญญาเช่าซื้อ</span> 
<span style=" white-space:nowrap;">ตลอด 5 ปี = 3.14% /</span> 
<span style=" white-space:nowrap;">ฟรีประกันภัยชั้นหนึ่ง</span>
<span style=" white-space:nowrap;">มูลค่าประกันภัยต่ำสุด</span>
<span style=" white-space:nowrap;">ที่ 22,261 บาท</span>
<span style=" white-space:nowrap;">จากประกันภัยคุ้มภัย /</span><br />
<span style=" white-space:nowrap;">เมื่อจัดไฟแนนซ์ผ่านฟอร์ด ลีสซิ่ง</span>
<span style=" white-space:nowrap;">เท่า1นั้น</span> 
<br />
<span style=" white-space:nowrap;">2.คำนวณจากฟอร์ด เอคโค่ สปอร์ต</span>
<span style=" white-space:nowrap;">รุ่น Trend</span>
<span style=" white-space:nowrap;">ผ่อนต่อเดือนเพียง 5,999 บาท</span>
<span style=" white-space:nowrap;">สำหรับค่างวดเดือนที่ 1-12</span>
<span style=" white-space:nowrap;">และ 9,027 บาท</span>
<span style=" white-space:nowrap;">สำหรับ ค่างวดเดือนที่ 13-72</span>
<span style=" white-space:nowrap;">ที่ราคาพิเศษ 699,000 บาท </span> 
<br />
<span style=" white-space:nowrap;">3.สำหรับฟอร์ด เอเวอเรสต์</span> 
<span style=" white-space:nowrap;">ทุกรุ่น</span>
<span style=" white-space:nowrap;">ยกเว้นรุ่น 2.2 Titanium + (MY17	NAVI)</span>
<span style=" white-space:nowrap;">และ 3.2 Titanium + (MY17	NAVI)</span> <br /> 
<span style=" white-space:nowrap;">อัตราดอกเบี้ย 0%</span>
<span style=" white-space:nowrap;">(งวดที่ 1-24)</span>
<span style=" white-space:nowrap;">โดยต้องเช่าซื้อรวม</span>
<span style=" white-space:nowrap;">60 เดือนเท่านั้น</span>
<span style=" white-space:nowrap;">และอัตราดอกเบี้ยงวดที่ 25-60</span>
<span style=" white-space:nowrap;">เป็นไปตามที่ธนาคารกำหนด</span><br />
<span style=" white-space:nowrap;">ทั้งนี้อัตราดอกเบี้ย</span> 
<span style=" white-space:nowrap;">ที่ระบุในสัญญาเช่าซื้อ</span> 
<span style=" white-space:nowrap;">ตลอด 5 ปี = 3.10% /</span>
<span style=" white-space:nowrap;">ฟรีประกันภัยชั้นหนึ่ง</span><br />
<span style=" white-space:nowrap;">เฉพาะบริษัทประกันภัย</span>ที่<span style=" white-space:nowrap;">เข้าร่วมรายการ</span> 
<span style=" white-space:nowrap;">และเมื่อจัดไฟแนนซ์ผ่านฟอร์ด ลีสซิ่ง </span> 
<span style=" white-space:nowrap;">เท่านั้น</span> 
</span>'''

[[module]] #TH Social
path='email_modules/footer/th/social'
color='white'

[[module]] #TH Online
path='email_modules/footer/th/online'
color='white'

+++