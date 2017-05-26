+++
markets = ["th"]
title = '''TH Service Reminder First Past Due 004 UPC'''
draft = true



[[module]]
path='email_modules/preheader'
color='''nothing'''

	preheader = '''ฟอร์ดให้คุณสุขยิ่งกว่า กับบริการดีๆ พร้อมส่วนลดอะไหล่และค่าน้ำมันเครื่องสูงสุดถึง 18%'''

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
          	<span style="white-space:nowrap;">เพื่อรักษารถ &lt;%${user.CustomAttribute['Model']}%&gt;</span> 
            <span style="white-space:nowrap;">ของคุณให้อยู่ในสภาพดี</span>
            <span style="white-space:nowrap;">และวิ่งได้อย่างเต็มประสิทธิภาพสม่ำเสมอ</span> 
            <span style="white-space:nowrap;">อย่าลืมนำรถเข้าศูนย์บริการ</span>
            <span style="white-space:nowrap;">เพื่อตรวจเช็คระยะเมื่อครบกำหนด</span>
          </span>
<br /><br />
<span style="font-family:Tahoma, Verdana, Sans-serif">
    <span style="white-space:nowrap;">นัดหมายล่วงหน้าเพื่อเข้ารับบริการได้ทันที</span> <br />
    <span style="white-space:nowrap;">ติดต่อ <%${user.CustomAttribute['Dealer_Name']}%></span> <span style="white-space:nowrap;">(ระหว่างเวลาทำการ)</span><br />
    <span style="white-space:nowrap;">หรือค้นหาตัวแทนจำหน่ายใกล้บ้านคุณ</span>
 </span>'''

cta1_text='''<span style="font-family:Tahoma, Verdana, Sans-serif">โทร <%${user.CustomAttribute['Dealer_Phone']}%></span>'''
cta1_url='''tel:<%${user.CustomAttribute['Dealer_Phone']}%>'''
cta2_text='''<span style="font-family:Tahoma, Verdana, Sans-serif">ค้นหาตัวแทนจำหน่าย</span>'''
cta2_url='''https://www.ford.co.th/locate-a-dealer/'''
cta2_link_name='''find_dealer'''


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