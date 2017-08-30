+++
markets = ["th"]
title = '''TH Service Reminder First Past Due 008 UPC'''


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
title='''<span style="color:#ff6600;font-family:Tahoma, Verdana, Sans-serif">รถ <%${user.CustomAttribute['Model']}%> ของคุณ เลยเวลาเช็คระยะแล้ว</span>'''
copy='''<span style="font-family:Tahoma, Verdana, Sans-serif">สวัสดีคุณ <%InsertIf expression="${(user['FirstName'] == null || user['FirstName'] == '-')}" id="FirstName" %>ท่านลูกค้าฟอร์ด <%/InsertIf%> <%InsertElse%> <%${user['FirstName']}%> <%/InsertElse%></span><br /><br />

 <span style="font-family:Tahoma, Verdana, Sans-serif">
						เพื่อรักษารถ &lt;%${user.CustomAttribute['Model']}%&gt; 
					ของคุณให้อยู่ในสภาพดี
						และวิ่งได้อย่างเต็มประสิทธิภาพสม่ำเสมอ
						อย่าลืมนำรถเข้าศูนย์บริการ
						เพื่อตรวจเช็คระยะเมื่อครบกำหนด
					</span>
<br /><br />
<span style="font-family:Tahoma, Verdana, Sans-serif">
		นัดหมายล่วงหน้าเพื่อเข้ารับบริการได้ทันที<br />
		ติดต่อ <%${user.CustomAttribute['Dealer_Name']}%>(ระหว่างเวลาทำการ)<br />
		หรือค้นหาตัวแทนจำหน่ายใกล้บ้านคุณ<br />
        ขออภัยหากคุณได้เข้ารับบริการที่ศูนย์บริการแล้ว
 </span>'''

cta1_text='''<span style="font-family:Tahoma, Verdana, Sans-serif">โทร <%${user.CustomAttribute['Dealer_Phone']}%></span>'''
cta1_url='''tel:<%${user.CustomAttribute['Dealer_Phone']}%>'''
cta2_text='''<span style="font-family:Tahoma, Verdana, Sans-serif">ค้นหาตัวแทนจำหน่าย</span>'''
cta2_url='''https://www.ford.co.th/locate-a-dealer/'''
cta2_link_name='''find_dealer'''

[[module]] #TH Social
path='email_modules/footer/th/social'
color='white'

[[module]] #TH Online
path='email_modules/footer/th/online'
color='white'
+++