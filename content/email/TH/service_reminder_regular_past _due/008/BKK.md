+++
markets = ["th"]
title = '''TH Service Reminder Regular Past Due 008 BKK'''

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
							<span style="white-space:nowrap;">อย่าพลาดการนำ</span>รถ<span style="white-space:nowrap;">เข้าศูนย์บริการ</span><br />
								<span style="white-space:nowrap;">เพื่อตรวจเช็คระยะ</span>
						</span>'''
copy='''<span style="font-family:Tahoma, Verdana, Sans-serif">สวัสดีคุณ <%InsertIf expression="${(user['FirstName'] == null || user['FirstName'] == '-')}" id="FirstName" %>ท่านลูกค้าฟอร์ด<%/InsertIf%> <%InsertElse%> <%${user['FirstName']}%> <%/InsertElse%>
<br /><br />
<span style="white-space:nowrap;">เพื่อรักษารถ <%${user.CustomAttribute['Model']}%> </span> 
<span style="white-space:nowrap;">ของคุณให้อยู่ในสภาพดี</span><br />
		<span style="white-space:nowrap;">และวิ่งได้อย่าง</span>เต็ม<span style="white-space:nowrap;">ประสิทธิภาพสม่ำเสมอ</span><br />
		<span style="white-space:nowrap;">อย่าลืมนำรถเข้าศูนย์บริการ</span><br />
		<span style="white-space:nowrap;">เพื่อตรวจเช็คระยะเมื่อครบกำหนด</span>
<br /><br />
อย่าลืม! นัดหมายศูนย์บริการวันนี้
<br /><br />
<span style="white-space:nowrap;">บริการใหม่!!</span>
<span style="white-space:nowrap;">ฟอร์ดเพิ่มความสะดวกสบาย</span><br />
<span style="white-space:nowrap;">ให้คุณสามารถนัดหมายเช็คระยะ</span>ที่<span style="white-space:nowrap;">ศูนย์บริการฟอร์ดง่ายๆ</span><br />
<span style="white-space:nowrap;">ผ่านระบบ Online Booking</span> 
<span style="white-space:nowrap;">ตลอด 7 วัน</span><br>
<span style="white-space:nowrap;">พร้อมการรับประกันเช็คระยะ</span>
<span style="white-space:nowrap;">ภายใน 60	นาที</span><br />
<span style="white-space:nowrap;">หากไม่ทัน</span>
<span style="white-space:nowrap;">คุณจะได้รับบริการเช็คระยะครั้งนั้น</span> 
<span style="white-space:nowrap;">"ฟรีทันที"</span></span>'''
cta1_text='''<span style="font-family:Tahoma, Verdana, Sans-serif">นัดหมายตอนนี้</span>'''
cta1_url='''https://onlinebooking.ford.co.th/'''

[[module]]
path='email_modules/cover/03'

color='''white'''
copy='''<span style="font-family:Tahoma, Verdana, Sans-serif;color:#b3b3b3;">
<span style="white-space:nowrap;">หมายเลข VIN :</span> 
<span style="white-space:nowrap;"><% ${user.CustomAttribute['VIN']} %></span><br />
<span style="white-space:nowrap;">เข้ารับบริการครั้งล่าสุดวันที่ :</span> 
<span style="white-space:nowrap;"><% ${user.CustomAttribute['Last_Reported_Service_Date']} %></span><br />
<span style="white-space:nowrap;">ระยะทางล่าสุด :</span> 
<span style="white-space:nowrap;"><% ${user.CustomAttribute['Mileage']} %></span></span>'''

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


[[module]] #TH Social
path='email_modules/footer/th/social'
color='white'

[[module]] #TH Online
path='email_modules/footer/th/online'
color='white'
+++