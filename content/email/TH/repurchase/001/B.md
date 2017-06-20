+++
markets = ["th"]
title = '''TH Repurchase 001 Version B'''
draft = true



[[module]]
path='email_modules/preheader'
color='''nothing'''

preheader = '''สัมผัสประสบการณ์เหนือระดับ กับ ฟอร์ดเรนเจอร์ ใหม่ และ ฟอร์ด เอเวอเรสต์ ใหม่'''

[[module]] #Header Logo
path='email_modules/header/logo'
color='white'

	image = '''white'''
	url_link = '''https://www.ford.co.th/'''

[[module]] #Cover 01
path='email_modules/cover/01'
color='''white'''

	title = '''
		<span style="font-family:Tahoma, Verdana, Sans-serif;white-space:nowrap;">พบยนตรกรรมสุดล้ำ</span>
		<span style="font-family:Tahoma, Verdana, Sans-serif;white-space:nowrap;">รุ่นล่าสุดจากฟอร์ด</span>
	'''
	copy = '''<span style="font-family:Tahoma, Verdana, Sans-serif">
<span style="font-family:Tahoma, Verdana, Sans-serif;white-space:nowrap;">สวัสดีค่ะ คุณ <%InsertIf expression="${(user['FirstName'] == null || user['FirstName'] == '-')}" id="FirstName" %>ท่านลูกค้าฟอร์ด<%/InsertIf%> <%InsertElse%> <%${user['FirstName']}%> <%/InsertElse%></span><br /><br />
<span style="font-family:Tahoma, Verdana, Sans-serif;white-space:nowrap;">ฟอร์ดขอขอบคุณที่คุณเป็นส่วนหนึ่ง</span><br /><span style="font-family:Tahoma, Verdana, Sans-serif;">ของ</span><span style="font-family:Tahoma, Verdana, Sans-serif;white-space:nowrap;">ครอบครัวฟอร์ดมาโดยตลอด</span>
<span style="font-family:Tahoma, Verdana, Sans-serif;white-space:nowrap;">หากคุณกำลังพิจารณามองหารถคันใหม่</span>
<span style="font-family:Tahoma, Verdana, Sans-serif;white-space:nowrap;">ฟอร์ดขอเรียนเชิญคุณมาทดลอง</span><br />
<span style="font-family:Tahoma, Verdana, Sans-serif;white-space:nowrap;">ขับยนตรกรรมรุ่นล่าสุดจากฟอร์ด</span>
<span style="font-family:Tahoma, Verdana, Sans-serif;white-space:nowrap;">โดยเฉพาะ ฟอร์ด เรนเจอร์ 6 รุ่นใหม่</span>
<span style="font-family:Tahoma, Verdana, Sans-serif;white-space:nowrap;">และ เอเวอเรสต์ 2.2L ไททาเนี่ยม พลัส</span>
</span>'''

[[module]] # Custom Car 2 Column
path='email_modules/custom/2column_car'
color='black'

	image1 = '''th_edm5a_exploreranger_20160913'''
	cta1_text = '''<span style="font-family:Tahoma, Verdana, Sans-serif">ฟอร์ด เรนเจอร์ ใหม่</span>'''
	cta1_url = '''https://www.ford.co.th/trucks/ranger/compare-models/'''
	cta1_link_name = '''explore_ranger'''
	cta1_icon = '''more'''
	image2 = '''th_edm5a_exploreeverest_20160913'''
	cta2_text = '''<span style="font-family:Tahoma, Verdana, Sans-serif">ฟอร์ด เอเวอเรสต์ ใหม่</span>'''
	cta2_url = '''https://www.ford.co.th/suvs/everest/compare-models/'''
	cta2_link_name = '''explore_everest'''
	cta2_icon = '''more'''

[[module]] #Cover 01
path='email_modules/cover/01'
color='black'

	title = '''<span style="font-family:Tahoma, Verdana, Sans-serif; white-space:nowrap;">ข้อเสนอแรงแห่งปีที่</span><span style="font-family:Tahoma, Verdana, Sans-serif;">คุณ</span><span style="font-family:Tahoma, Verdana, Sans-serif; white-space:nowrap;">ไม่อยากให้ใครรู้</span>'''

	copy = '''<span style="font-family:Tahoma, Verdana, Sans-serif;white-space:nowrap;">เป็นเจ้าของรถฟอร์ดรุ่นใดก็ได้ภายในวันที่ 30 พฤศจิกายนนี้ </span><br />
	<span style="font-family:Tahoma, Verdana, Sans-serif;white-space:nowrap;">รับข้อเสนอแรงที่สุดแห่งปีพร้อมโปรโมชั่นมากมาย</span><br />
	<span style="font-family:Tahoma, Verdana, Sans-serif;white-space:nowrap;">คลิกด้านล่างเพื่อดูรายละเอียดเพิ่มเติม</span><br />
	<span style="font-family:Tahoma, Verdana, Sans-serif;white-space:nowrap;">ไม่ว่าจะเป็นฟอร์ด เฟียสต้า</span>
	<span style="font-family:Tahoma, Verdana, Sans-serif;white-space:nowrap;"> ฟอร์ด โฟกัส</span>
	<span style="font-family:Tahoma, Verdana, Sans-serif;white-space:nowrap;">ฟอร์ด เอเวอเรสต์</span><br />
	<span style="font-family:Tahoma, Verdana, Sans-serif;white-space:nowrap;">หรือ ฟอร์ด เรนเจอร์</span>'''

	cta1_text = '''<span style="font-family:Tahoma, Verdana, Sans-serif">ดูข้อเสนอทั้งหมด</span>'''
	cta1_url = '''https://www.ford.co.th/buying/latest-offers/'''
	cta1_link_name = '''yes_offer'''
	cta1_icon = '''more'''

[[module]] #Banner Image No Link
path = '''email_modules/image/banner_nolink'''
color = '''white'''

	image = '''th_edm5a_yesecosport_20161021'''

[[module]]
path='email_modules/split/03'
color='green'

title='''<span style="font-family:Tahoma, Verdana, Sans-serif">สิทธิพิเศษสำหรับ<br />ลูกค้าฟอร์ด</span>'''
copy='''<span style="font-family:Tahoma, Verdana, Sans-serif;white-space:nowrap;">ลูกค้าฟอร์ด รับทันที</span> 
<span style="color:#FFFFFF;white-space:nowrap;font-family:Tahoma, Verdana;">ส่วนลด 10,000 บาท</span>
<span style="font-family:Tahoma, Verdana, Sans-serif;white-space:nowrap;">เมื่อซื้อรถฟอร์ดคันต่อไปรุ่นใดก็ได้</span>
<span style="font-family:Tahoma, Verdana, Sans-serif;white-space:nowrap;">พิเศษ รับส่วนลดเพิ่มเป็น </span><span style="color:#FFFFFF;white-space:nowrap;font-family:Tahoma, Verdana;">20,000 บาท</span> 
<span style="font-family:Tahoma, Verdana, Sans-serif;white-space:nowrap;">เมื่อซื้อรถฟอร์ด โฟกัส ใหม่</span> 
<span style="font-family:Tahoma, Verdana, Sans-serif;white-space:nowrap;">ข้อเสนอนี้มีถึงวันที่ 31 ธันวาคม 2559</span>'''
cta1_text='''<span style="font-family:Tahoma, Verdana, Sans-serif">ดูเพิ่มเติม</span>'''
cta1_url='''https://www.ford.co.th/loyaltyprogram2016/'''
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