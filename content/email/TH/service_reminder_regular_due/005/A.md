+++
markets = ["th"]
title = '''TH Service Reminder Regular Due 005 BKK'''

[[module]]
path='email_modules/preheader'
color='''nothing'''

	preheader = '''ดูแลเครื่องยนต์ของคุณด้วยโปรแกรมชุดน้ำมันเครื่องสุดคุ้ม Oil Save Packs'''

[[module]] #Header Logo
path='email_modules/header/logo'
color='white'

  image = '''white'''
  url_link = '''https://www.ford.co.th/'''


[[module]]
path='email_modules/cover/02'

color='''white'''
icon='''th_edm2_svc_wrench_20160801'''
title='''<span style="font-family:Tahoma, Verdana, Sans-serif"><span style="white-space:nowrap;">ได้เวลาเช็คสภาพรถของคุณแล้ว</span></span>'''
copy='''<span style="font-family:Tahoma, Verdana, Sans-serif">สวัสดีค่ะ คุณ <%InsertIf expression="${(user['FirstName'] == null || user['FirstName'] == '-')}" id="FirstName" %>ท่านลูกค้าฟอร์ด<%/InsertIf%> <%InsertElse%> <%${user['FirstName']}%> <%/InsertElse%>
<br /><br />
  <span style="white-space:nowrap;">รถ <%${user.CustomAttribute['Model']}%> ของคุณได้เวลาตรวจเช็คระยะแล้ว</span>
  <span style="white-space:nowrap;"> ที่ศูนย์บริการฟอร์ด</span>
  <span style="white-space:nowrap;">เรามีช่างผู้ชำนาญงานของฟอร์ด</span><br />
  <span style="white-space:nowrap;">ที่พร้อมดูแลรถยนต์ของคุณ</span>
  <span style="white-space:nowrap;">ให้อยู่ในสภาพสมบูรณ์ทุกเมื่อ</span>
<br /><br />
 <span style="white-space:nowrap;">เช็คระยะครั้งถัดไปวันที่ :  <strong><% ${user.CustomAttribute['NextServiceDate']} %></strong></span> 
<br /><br />
<span style="white-space:nowrap;">บริการใหม่!!</span>
<span style="white-space:nowrap;">ฟอร์ดเพิ่มความสะดวกสบาย</span><br />
<span style="white-space:nowrap;">ให้คุณสามารถนัดหมายเช็คระยะ</span>ที่<span style="white-space:nowrap;">ศูนย์บริการฟอร์ดง่ายๆ</span><br />
<span style="white-space:nowrap;">ผ่านระบบ Online Booking</span> 
<span style="white-space:nowrap;">ตลอด 7 วัน</span><br>
<span style="white-space:nowrap;">พร้อมการรับประกันเช็คระยะ</span>
<span style="white-space:nowrap;">ภายใน 60  นาที</span><br />
<span style="white-space:nowrap;">หากไม่ทัน</span>
<span style="white-space:nowrap;">คุณจะได้รับบริการเช็คระยะครั้งนั้น</span> 
<span style="white-space:nowrap;">"ฟรีทันที"</span></span>'''
cta1_text='''<span style="font-family:Tahoma, Verdana, Sans-serif">นัดหมายตอนนี้</span>'''
cta1_url='''https://onlinebooking.ford.co.th/'''

[[module]]
path='email_modules/cover/03'

color='''white'''
copy='''<span style="font-family:Tahoma, Verdana, Sans-serif"><span style="white-space:nowrap;"><span style="color:#b3b3b3;">หมายเลข VIN : <% ${user.CustomAttribute['VIN']} %><br />
        เข้ารับบริการครั้งล่าสุดวันที่ : <% ${user.CustomAttribute['Last_Reported_Service_Date']} %><br />
        ระยะทางล่าสุด : <% ${user.CustomAttribute['Mileage']} %></span></span></span>'''

[[module]] #Custom 01
path='email_modules/custom/3columntitle3icons'
color='white'

  title = '''<span style="font-family:Tahoma, Verdana, Sans-serif">ทำไมต้องศูนย์บริการฟอร์ด?</span>'''
  icon1 = '''ico_2e_fordsvc_a'''
  text1 = '''<span style="font-family:Tahoma, Verdana, Sans-serif">
                    <span style="white-space:nowrap;">มั่นใจอะไหล่แท้</span> 
                    <span style="white-space:nowrap;">ฟอร์ด 100%</span>  
                    <span style="white-space:nowrap;">พร้อมการบำรุงรักษารถยนต์</span>
                    <span style="white-space:nowrap;">อย่างมีประสิทธิภาพ</span>เพื่อ
                    <span style="white-space:nowrap;">สมรรถนะสูงสุดของรถคุณ</span></span>'''
  icon2 = '''ico_2e_fordsvc_b'''
  text2 = '''<span style="font-family:Tahoma, Verdana, Sans-serif">
                    <span style="white-space:nowrap;">ตรวจเช็คด้วยช่างเทคนิค</span> 
                    <span style="white-space:nowrap;">ฟอร์ดที่ผ่านการอบรม</span> 
                    <span style="white-space:nowrap;">รวมถึงเครื่องมือและอุปกรณ์</span> 
                    <span style="white-space:nowrap;">ทันสมัยที่ออกแบบมาเพื่อ</span>
                    <span style="white-space:nowrap;">รถฟอร์ดโดยเฉพาะ</span></span>'''
  icon3 = '''ico_2e_fordsvc_c_th'''
  text3 = '''<span style="font-family:Tahoma, Verdana, Sans-serif">
                    <span style="white-space:nowrap;">เก็บบันทึกสถิติรถฟอร์ด</span> 
                    <span style="white-space:nowrap;">ของคุณอย่างเป็นระบบ</span> 
                    <span style="white-space:nowrap;">เพื่อเพิ่มมูลค่าในการขายต่อ</span></span>'''

[[module]] #Banner Image No Link
path = '''email_modules/image/banner_nolink'''
color = '''white'''

  image = '''th_edm2_whyfordsvc_20161115'''


[[module]] #Split 04
path='email_modules/split/04'
color='green'

  title='''<span style="font-family:Tahoma, Verdana, Sans-serif">ประหยัดค่าน้ำมันเครื่อง<br />สูงสุด</span>'''
  copy='''<span style="font-family:Tahoma, Verdana, Sans-serif;">
                                  <span style="white-space:nowrap;">เพิ่มความอุ่นใจในการขับขี่ พิเศษ!</span> 
                                    <span style="white-space:nowrap;">รับส่วนลดเพิ่ม 500 บาท</span> 
                                    <span style="white-space:nowrap;">เมื่อซื้อโปรแกรมชุดน้ำมันเครื่อง</span>
                                    <span style="white-space:nowrap;">สุดคุ้ม (OSP)</span> 
                                    <span style="white-space:nowrap;">แบบแพคเกจ 3 ครั้ง</span>
                                </span>'''
  cta1_text='''<span style="font-family:Tahoma, Verdana, Sans-serif">คลิกเพื่อดูรายละเอียดและราคา</span>'''
cta1_url='''https://www.ford.co.th/owner/oil-save-pack/'''
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