+++
markets = ["th"]
title = '''TH Service Reminder First Past Due 007 NLB UPC'''


[[module]]
path='email_modules/preheader'


	preheader = '''พบข้อเสนอสุดพิเศษกับโปรแกรมบำรุงรักษารถยนต์ตามระยะ (SSP)'''

[[module]] #Header Logo
path='email_modules/header/logo'
color='white'

	image = '''white'''
	url_link = '''https://www.ford.co.th/'''

[[module]]
path='email_modules/cover/02'

color='''white'''
icon='''th_edm2_svc_wrench_urgent_20160801'''
title='''รถ <%${user.CustomAttribute['Model']}%> ของคุณ เลยเวลาเช็คระยะแล้ว'''
copy='''สวัสดีคุณ <%InsertIf expression="${(user['FirstName'] == null || user['FirstName'] == '-')}" id="FirstName" %>ท่านลูกค้าฟอร์ด 
<%/InsertIf%> <%InsertElse%> <%${user['FirstName']}%> <%/InsertElse%>เพื่อรักษารถ &lt;%${user.CustomAttribute['Model']}%&gt; 
					ของคุณให้อยู่ในสภาพดี
						และวิ่งได้อย่างเต็มประสิทธิภาพสม่ำเสมอ
						อย่าลืมนำรถเข้าศูนย์บริการ
						เพื่อตรวจเช็คระยะเมื่อครบกำหนด
					นัดหมายล่วงหน้าเพื่อเข้ารับบริการได้ทันที
		ติดต่อ <%${user.CustomAttribute['Dealer_Name']}%>(ระหว่างเวลาทำการ)
		หรือค้นหาตัวแทนจำหน่ายใกล้บ้านคุณ'''

cta1_text='''โทร <%${user.CustomAttribute['Dealer_Phone']}%>'''
cta1_url='''tel:<%${user.CustomAttribute['Dealer_Phone']}%>'''
cta2_text='''ค้นหาตัวแทนจำหน่าย'''
cta2_url='''https://www.ford.co.th/locate-a-dealer/'''
cta2_link_name='''find_dealer'''


[[module]] #Split 04
path='email_modules/split/04'
color='green'

	title='''ประหยัดและคุ้มค่ากว่า '''
	copy='''รับส่วนลดเพิ่มสูงสุด 10% หรือ 3,700 บาท กับโปรแกรมบำรุงรักษารถยนต์ ตามระยะ(SSP)พิเศษรับสิทธิ์ผ่อน 0%	นาน 10 เดือน เมื่อชำระผ่านบัตรเครดิตกสิกรไทย ตั้งแต่วันนี้ - วันที่ 31 สิงหาคม 2560'''
	cta1_text='''คลิกเพื่อดูรายละเอียดและราคา'''
cta1_url='''https://www.ford.co.th/owner/schedule-service/'''
cta1_icon='''more'''
cta1_link_name = '''SSP'''
image = '''th_edm5a_specialoffer_20160801'''


[[module]] #TH Social
path='email_modules/footer/th/social'
color='white'

[[module]] #TH Online
path='email_modules/footer/th/online'
color='white'
+++