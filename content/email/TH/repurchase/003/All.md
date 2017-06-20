+++
markets = ["th"]
title = '''TH Repurchase 003 All'''


[[module]]
path='email_modules/preheader'

	preheader = '''พบข้อเสนอสุดพิเศษได้ที่โชว์รูมฟอร์ด 13-19 ก.พ.นี้ ฟอร์ดขอขอบคุณที่เป็นส่วนหนึ่ง ของครอบครัวฟอร์ดมาโดยตลอด'''

[[module]] #Header Logo
path='email_modules/header/logo'
color='white'

	image = '''white'''
	url_link = '''https://www.ford.co.th/'''

[[module]] #Banner Image No Link
path = '''email_modules/image/banner_nolink'''
color = '''white'''

	image = '''th_edm5a_showroom_20170120'''

[[module]] #Cover 01
path='email_modules/cover/01'
color='white'

	title = '''<span style="font-family:Tahoma, Verdana, Sans-serif;">
	<span style="white-space:nowrap;">ข้อเสนอสุดพิเศษ</span><br>
		<span style="white-space:nowrap;">จากแคมเปญ Deal Search</span></span>'''
	copy = ''' <span style="font-family:Tahoma, Verdana, Sans-serif;">สวัสดีคุณ <%InsertIf expression="${(user['FirstName'] == null || user['FirstName'] == '-')}" id="FirstName" %>ท่านลูกค้าฟอร์ด<%/InsertIf%> <%InsertElse%> <%${user['FirstName']}%> <%/InsertElse%><br /><br /></span>

<span style="font-family:Tahoma, Verdana, Sans-serif;">
						<span style="white-space:nowrap;">ฟอร์ดขอขอบคุณ</span>ที่<span style="white-space:nowrap;">เป็นส่วนหนึ่ง</span> ของ<span style="white-space:nowrap;">ครอบครัวฟอร์ดมาโดยตลอด</span> 
						<span style="white-space:nowrap;">หากคุณกำลังพิจารณามองหารถคันใหม่</span>
						<span style="white-space:nowrap;">เราอยากเชิญคุณ</span>มา<span style="white-space:nowrap;">พบกับข้อเสนอสุดพิเศษ</span>
						<span style="white-space:nowrap;">ที่โชว์รูมฟอร์ดทั่วประเทศ</span>
						<span style="white-space:nowrap;">ในวันที่ 13-19 กุมภาพันธ์นี้</span><br><br>

						<span style="white-space:nowrap;">พบข้อเสนอสุดพิเศษต่าง ๆ</span> 
						<span style="white-space:nowrap;">มากมายจากฟอร์ด</span>
						<span style="white-space:nowrap;">เช่น</span> 
						<span style="white-space:nowrap;">รับบัตรกำนัลเทสโก้ โลตัส</span>
						<span style="white-space:nowrap;">มูลค่า 200 บาท</span> 
						<span style="white-space:nowrap;">เมื่อทดลองขับฟอร์ดรุ่นใดก็ได้</span> 
						<span style="white-space:nowrap;">ข้อเสนอดอกเบี้ย 0%</span> 
						<span style="white-space:nowrap;">พร้อมฟรีประกันภัยชั้นหนึ่ง</span> 
						<span style="white-space:nowrap;">(เฉพาะรุ่น)</span> 
						<span style="white-space:nowrap;">หรือลุ้นรับส่วนลด 1 แสนบาท</span>
						<span style="white-space:nowrap;">เมื่อจองรถในช่วง</span> 
						<span style="white-space:nowrap;">13-19 กุมภาพันธ์นี้</span> 
						<span style="white-space:nowrap;">เป็นต้น</span>
					</span>'''
	cta1_text='''<span style="font-family:Tahoma, Verdana, Sans-serif">ดูเพิ่มเติม</span>'''
	cta1_url = '''https://www.ford.co.th/buying/latest-offers/'''
	cta1_link_name = '''showroom_event'''
	cta1_icon = '''more'''

[[module]] #Cover 01
path='email_modules/cover/01'
color='black'

	title = '''<span style="font-family:Tahoma, Verdana, Sans-serif;">ข้อเสนอพิเศษสุดคุ้มรับปี 2017</span>'''
	copy = '''<span style="font-family:Tahoma, Verdana, Sans-serif;">
						<span style="white-space:nowrap;">ออกรถฟอร์ดภายในวันที่ 28 กุมภาพันธ์นี้</span>
						<span style="white-space:nowrap;">รับดอกเบี้ยต่ำพิเศษเพียง 0.99%</span>
						<span style="white-space:nowrap;">พร้อมฟรีประกันภัยชั้นหนึ่ง</span>
						<span style="white-space:nowrap;">ดาวน์ 25% ผ่อนนาน 48 เดือน</span>
					</span>'''
	cta1_text='''<span style="font-family:Tahoma, Verdana, Sans-serif">ข้อเสนอพิเศษ</span>'''
	cta1_url = '''https://www.ford.co.th/buying/latest-offers/'''
	cta1_link_name = '''latest_offer'''
	cta1_icon = '''more'''

[[module]] #Banner Image No Link
path = '''email_modules/image/banner_nolink'''
color = '''white'''

	image = '''th_edm5a_rangerfx4_20170113'''

[[module]]
path='email_modules/split/03'
color='green'

title='''<span style="font-family:Tahoma, Verdana, Sans-serif">สิทธิพิเศษสำหรับ<br />ลูกค้าฟอร์ด</span>'''
copy='''<span style="font-family:Tahoma, Verdana, Sans-serif;">
									<span style="white-space:nowrap;">เมื่อซื้อรถยนต์ฟอร์ดคันต่อไปทุกรุ่น</span> 
									<span style="white-space:nowrap;">(ยกเว้นฟอร์ด โฟกัส)</span> 
									<span style="white-space:nowrap;">รับส่วนลดเพิ่ม 10,000 บาททันที</span> 
									<span style="white-space:nowrap;">ข้อเสนอสุดพิเศษนี้มีถึง</span> 
									<span style="white-space:nowrap;">วันที่ 28 กุมภาพันธ์ พ.ศ. 2560</span> 
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