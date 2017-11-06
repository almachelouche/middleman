+++
markets = ["th"]
title = '''TH Service Reminder Regular Past Due 008 UPC'''

[[module]]
path='email_modules/preheader'


	preheader = '''ดูแลเครื่องยนต์ของคุณด้วยโปรแกรมชุดน้ำมันเครื่องสุดคุ้ม Oil Save Packs'''

[[module]] #Header Logo
path='email_modules/header/logo'
color='white'

	image = '''white'''
	url_link = '''https://www.ford.co.th/'''

[[module]]
path='email_modules/cover/02'

color='''white'''
icon='''th_edm2_svc_wrench_urgent_20160801'''
title='''<span style="color:#ff6600;font-family:Tahoma, Verdana, Sans-serif">
					<span style="white-space:nowrap;">รถฟอร์ดของท่านถึงกำหนด</span><br />
					<span style="white-space:nowrap;">เข้าศูนย์บริการ</span>
					<span style="white-space:nowrap;">เพื่อตรวจเช็คระยะแล้ว</span>
					</span>'''
copy='''<span style="font-family:Tahoma, Verdana, Sans-serif">สวัสดีคุณ <%InsertIf expression="${(user['FirstName'] == null || user['FirstName'] == '-')}" id="FirstName" %>ท่านลูกค้าฟอร์ด<%/InsertIf%> <%InsertElse%> <%${user['FirstName']}%> <%/InsertElse%>
<br /><br />
		<span style="white-space:nowrap;">เพื่อรักษารถ <%${user.CustomAttribute['Model']}%>	ของคุณให้อยู่ในสภาพดี</span><br />
		<span style="white-space:nowrap;">และวิ่งได้อย่างเต็มประสิทธิภาพสม่ำเสมอ</span><br />
		<span style="white-space:nowrap;">อย่าลืมนำรถเข้าศูนย์บริการ</span><br />
		<span style="white-space:nowrap;">เพื่อตรวจเช็คระยะเมื่อครบกำหนด</span>
<br /><br />
<span style="white-space:nowrap;">นัดหมายเพื่อเข้ารับบริการได้ทันที</span> 
<span style="white-space:nowrap;">เพื่อการขับขี่อย่างมั่นใจไปกับฟอร์ด</span> <br>
<span style="white-space:nowrap;">ติดต่อ <%${user.CustomAttribute['Dealer_Name']}%></span> 
<span style="white-space:nowrap;">(ระหว่างเวลาทำการ)</span><br>
<span style="white-space:nowrap;">หรือค้นหาตัวแทนจำหน่ายใกล้บ้านคุณ</span></span>'''

cta1_text='''<span style="font-family:Tahoma, Verdana, Sans-serif">โทร <%${user.CustomAttribute['Dealer_Phone']}%></span>'''
cta1_url='''tel:<%${user.CustomAttribute['Dealer_Phone']}%>'''
cta2_text='''<span style="font-family:Tahoma, Verdana, Sans-serif">ค้นหาตัวแทนจำหน่าย</span>'''
cta2_url='''https://www.ford.co.th/locate-a-dealer/'''
cta2_url_link_name='''find_dealer'''

[[module]]
path='email_modules/cover/03'

color='''white'''
copy='''<span style="font-family:Tahoma, Verdana, Sans-serif"><span style="white-space:nowrap;"><span style="color:#b3b3b3;">หมายเลข VIN : <% ${user.CustomAttribute['VIN']} %><br />
				เข้ารับบริการครั้งล่าสุดวันที่ : <% ${user.CustomAttribute['Last_Reported_Service_Date']} %><br />
				ระยะทางล่าสุด : <% ${user.CustomAttribute['Mileage']} %></span></span></span>'''

[[module]]

	path='email_modules/split/04'
	color='green'
	title='''<span style="font-family:Tahoma, Verdana, Sans-serif">ประหยัดค่าน้ำมันเครื่อง<br />สูงสุด</span>'''
	copy='''
	<span style="font-family:Tahoma, Verdana, Sans-serif">
	<span style="white-space:nowrap;">เพิ่มความอุ่นใจในการขับขี่</span><br />
	<span style="white-space:nowrap;">พิเศษ!เมื่อซื้อโปรแกรมชุด</span>
	<span style="white-space:nowrap;">น้ำมันเครื่องสุดคุ้ม (OSP)</span>
	<span style="white-space:nowrap;">รับส่วนลดเพิ่ม 300 บาท</span> 
	<span style="white-space:nowrap;">สำหรับแพ็กเกจ 2 ครั้ง</span> 
	<span style="white-space:nowrap;">และรับส่วนลดเพิ่ม</span>
	<span style="white-space:nowrap;">500 บาท</span> 
	<span style="white-space:nowrap;">สำหรับแพ็กเกจ 3 ครั้ง</span></span>'''
	cta1_text='''<span style="font-family:Tahoma, Verdana, Sans-serif">คลิกเพื่อดูรายละเอียดและราคา</span>'''
	cta1_url='''https://www.ford.co.th/owner/servicecampaign/'''
	cta1_icon='''more'''
	cta1_link_name = '''OSP'''
	image = '''th_edm2_savebigonoil_20170122'''

	[[module]] #Cover 05
path='email_modules/cover/02'
color='''white'''

	title = '''<span style="font-family:Tahoma, Verdana, Sans-serif">
	<span style=" white-space:nowrap;">ข้อมูลของคุณมีการ<br />
	<span style=" white-space:nowrap;">เปลี่ยนแปลงหรือไม่</span></span>'''

	copy = '''<span style="font-family:Tahoma, Verdana, Sans-serif">
	<span style=" white-space:nowrap;">กรุณาอัพเดทข้อมูลของคุณ</span>
	<span style=" white-space:nowrap;">เพื่อให้คุณไม่พลาด</span><br />
	<span style=" white-space:nowrap;">ข้อเสนอพิเศษต่างๆ</span>
	<span style=" white-space:nowrap;">จากฟอร์ด</span></span>'''

	cta1_text = '''<span style="font-family:Tahoma, Verdana, Sans-serif">อัพเดทข้อมูล</span>'''
	cta1_url = '''https://www.ford.co.th/#/overlay/content/ford/th/th_th/site-wide-content/overlays/form-overlay/login/'''
	cta1_link_name = '''anything_changed'''
	icon = '''th_edm2_ownerprofile_20160801'''

[[module]] #TH Social
path='email_modules/footer/th/social'
color='white'

[[module]] #TH Online
path='email_modules/footer/th/online'
color='white'
+++