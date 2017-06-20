+++
markets = ["th"]
title = '''TH Repurchase 003 Follow Up V2'''
draft = true


[[module]]
path='email_modules/preheader'
color='''white'''

preheader = '''พบข้อเสนอสุดพิเศษจากฟอร์ด ขออภัยสำหรับการแจ้งข้อมูลผิดพลาดในอีเมลล์ที่ส่งไปก่อนหน้านี้ค่ะ'''

[[module]] #Header Logo
path='email_modules/header/logo'
color='white'

	image = '''white'''
	url_link = '''https://www.ford.co.th/'''

[[module]]
path='email_modules/singles/copy'
color='''white'''
	
	copy = '''<span style="font-family:Tahoma, Verdana, Sans-serif;">สวัสดีคุณ <%InsertIf expression="${(user['FirstName'] == null || user['FirstName'] == '-')}" id="FirstName" %>
	ท่านลูกค้าฟอร์ด<%/InsertIf%> <%InsertElse%> <%${user['FirstName']}%> <%/InsertElse%><br /><br />
	<span style="white-space:nowrap;">ขออภัยสำหรับการแจ้งข้อมูลผิดพลาด</span>
	<span style="white-space:nowrap;">ในอีเมลล์ที่ส่งไปก่อนหน้านี้ค่ะ</span>
	<span style="white-space:nowrap;">ข้อเสนอในอีเมลล์ก่อนหน้านี้ได้ถูกยกเลิกแล้วค่ะ</span>
	<span style="white-space:nowrap;">ฟอร์ด ขออัพเดทข้อเสนอพิเศษใหม่</span>
	<span style="white-space:nowrap;">ในอีเมลล์ฉบับนี้แทน</span> 
	<span style="white-space:nowrap;">ตามรายละเอียดด้านล่างค่ะ</span>
	<br /><br /></span>'''
		

		
[[module]] #Cover 01
path='email_modules/cover/01'
color='black'

	title = '''<span style="font-family:Tahoma, Verdana, Sans-serif;">ข้อเสนอพิเศษสุดคุ้มรับปี 2017</span>'''
	copy = '''<span style="font-family:Tahoma, Verdana, Sans-serif;">
	<span style="white-space:nowrap;">ออกรถฟอร์ด เรนเจอร์</span>
	<span style="white-space:nowrap;">รับดอกเบี้ยต่ำพิเศษเพียง 0.99%</span>
	<span style="white-space:nowrap;">พร้อมฟรีประกันภัยชั้นหนึ่ง</span>
	<span style="white-space:nowrap;">ดาวน์ 25% ผ่อนนาน 48 เดือน</span></span>'''
	cta1_text='''<span style="font-family:Tahoma, Verdana, Sans-serif">ข้อเสนอพิเศษ</span>'''
	cta1_url = '''https://www.ford.co.th/buying/latest-offers/'''
	cta1_link_name = '''latest_offer'''
	cta1_icon = '''more'''

[[module]] #Banner Image No Link
path = '''email_modules/image/banner_nolink'''
color = '''white'''

	image = '''th_edm5a_rangerfx4_20170113'''
	
[[module]] #Footer Disclaimer
path='email_modules/footer/disclaimer'
color='white'
text='''<span style="font-family:Tahoma, Verdana, Sans-serif"><span style="font-weight:bold">หมายเหตุ</span><br /><br />
<ul>
<li>
	<span style="white-space:nowrap;">โปรโมชั่นพิเศษนี้</span>
	<span style="white-space:nowrap;">สำหรับฟอร์ด เรนเจอร์</span>
	<span style="white-space:nowrap;">รุ่น FX4</span> 
	<span style="white-space:nowrap;">และ XLT ดับเบิ้ลแค็บ</span>
</li>
<li>
	<span style="white-space:nowrap;">เงื่อนไขฟรีประกันชั้นหนึ่ง</span>
	<span style="white-space:nowrap;">เฉพาะบริษัทประกันที่เข้าร่วมรายการ</span>
	<span style="white-space:nowrap;">มูลค่าต่ำสุดที่ 20,758 บาท</span></li>
<li>เมื่อจัดไฟแนนซ์ผ่านฟอร์ด ลีสซิ่งเท่านั้น</li>
<li>ตั้งแต่วันที่ 1-28 กุมภาพันธ์ 2560</li></ul></span>'''

[[module]] #TH Social
path='email_modules/footer/th/social'
color='white'

[[module]] #TH Online
path='email_modules/footer/th/online'
color='white'


+++