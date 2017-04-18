+++
markets = ["th"]
title = '''TH Service Reminder Regular Past Due 004 BKK'''


[[module]]
path='email_modules/preheader'
color='''nothing'''

	preheader = '''ดูฟอร์ดให้คุณสุขยิ่งกว่า กับบริการดีๆ พร้อมส่วนลดอะไหล่และค่าน้ำมันเครื่องสูงสุดถึง 18%'''

[[module]] #Header Logo
path='email_modules/header/logo'
color='white'

  image = '''white'''
  url_link = '''https://www.ford.co.th/'''


[[module]]
path='email_modules/cover/02'

color='''white'''
icon='''th_edm2_svc_wrench_urgent_20160801'''
title='''<span style="color:#ff6600;font-family:Tahoma, Verdana, Sans-serif"><span style="white-space:nowrap;">อย่าพลาดนัดเช็คระยะของคุณ</span></span>'''
copy='''<span style="font-family:Tahoma, Verdana, Sans-serif"><span style="white-space:nowrap;">สวัสดีค่ะ คุณ <%InsertIf expression="${(user['FirstName'] == null || user['FirstName'] == '-')}" id="FirstName" %>ท่านลูกค้าฟอร์ด<%/InsertIf%> <%InsertElse%> <%${user['FirstName']}%> <%/InsertElse%></span>
<br /><br />
<span style="white-space:nowrap;"><strong>รถ <%${user.CustomAttribute['Model']}%> ของคุณเลยระยะเวลา</strong></span><br />
<span style="white-space:nowrap;"><strong>การรับบริการตรวจเช็คสภาพทั่วไปแล้ว</strong></span> 
<br /><br />
<span style="white-space:nowrap;">บริการใหม่!! ฟอร์ดเพิ่มความสะดวกสบาย</span>
<span style="white-space:nowrap;">ให้คุณสามารถนัดหมายเช็คระยะที่ศูนย์บริการฟอร์ดง่ายๆ</span>
<span style="white-space:nowrap;">ผ่านระบบ Online Booking ตลอด 7 วัน</span><br />
<span style="white-space:nowrap;">พร้อมการรับประกันเช็คระยะภายใน 60  นาที</span>
<span style="white-space:nowrap;">หากไม่ทัน</span>
<span style="white-space:nowrap;">คุณจะได้รับบริการเช็คระยะครั้งนั้น "ฟรีทันที"</span></span>'''
cta1_text='''<span style="font-family:Tahoma, Verdana, Sans-serif">นัดหมายตอนนี้</span>'''
cta1_url='''https://onlinebooking.ford.co.th/'''

[[module]]
path='email_modules/cover/03'

color='''white'''
copy='''<span style="font-family:Tahoma, Verdana, Sans-serif"><span style="white-space:nowrap;"><span style="color:#b3b3b3;">หมายเลข VIN : <% ${user.CustomAttribute['VIN']} %><br />
        เข้ารับบริการครั้งล่าสุดวันที่ : <% ${user.CustomAttribute['Last_Reported_Service_Date']} %><br />
        ระยะทางล่าสุด : <% ${user.CustomAttribute['Mileage']} %></span></span></span>'''


[[module]] #Split 04
path='email_modules/split/04'
color='green'

  title='''<span style="font-family:Tahoma, Verdana, Sans-serif"><span style="white-space:nowrap;">ประหยัดค่าน้ำมันเครื่อง</span><br /><span style="white-space:nowrap;">สูงสุด</span></span>'''
  copy='''<span style="font-family:Tahoma, Verdana, Sans-serif;">
<span style="white-space:nowrap;">ด้วยโปรแกรมชุดน้ำมันเครื่องสุดคุ้ม</span> <br />
<span style="white-space:nowrap;">(Oil Save Pack)</span>  <br />
<span style="white-space:nowrap;">ให้คุณประหยัดสูงสุดถึง 18%</span> <br />
<span style="white-space:nowrap;">ในการเปลี่ยนน้ำมันเครื่อง </span><br /> 
<span style="white-space:nowrap;">ไส้กรองน้ำมันเครื่อง </span> <br />
<span style="white-space:nowrap;">และโอริงน๊อตอ่างน้ำมันเครื่อง</span> 
</span>'''
  cta1_text='''<span style="font-family:Tahoma, Verdana, Sans-serif">คลิกเพื่อดูรายละเอียดและราคา</span>'''
cta1_url='''https://www.ford.co.th/owner/oil-save-pack/'''
cta1_icon='''more'''
cta1_link_name = '''OSP'''
image = '''th_edm2_savebigonoil18_20161221'''




[[module]] #TH Social
path='email_modules/footer/th/social'
color='white'

[[module]] #TH Online
path='email_modules/footer/th/online'
color='white'
+++