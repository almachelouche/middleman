+++
markets = ["th"]
title = '''TH Service Reminder First Past Due 001 Version A'''
draft = true

[[module]]
path='email_modules/preheader'
color='''nothing'''

	preheader = '''ฟอร์ดให้คุณสุขยิ่งกว่า กับบริการดีๆ พร้อมส่วนลดอะไหล่และค่าน้ำมันเครื่องสูงสุดถึง 300 บาท'''

[[module]] #Header Logo
path='email_modules/header/logo'
color='white'

  image = '''white'''
  url_link = '''https://www.ford.co.th/'''


[[module]]
path='email_modules/cover/02'

color='''darkblue'''
icon='''th_edm2d_svcwrench_urgent_20160801'''
title='''<span style="color:#ff6600;font-family:Tahoma, Verdana, Sans-serif"><span style="white-space:nowrap;">ถึงเวลาพา <%${user.CustomAttribute['Model']}%></span> <span style="white-space:nowrap;">ไปเข้าศูนย์แล้ว!</span></span>'''
copy='''<span style="font-family:Tahoma, Verdana, Sans-serif"><span style="white-space:nowrap;">พารถ <%${user.CustomAttribute['Model']}%> </span><span style="white-space:nowrap;">ของคุณไปตรวจเช็คระยะครั้งแรกดีกว่า</span> <span style="white-space:nowrap;">รับรองว่ารวดเร็วและครบครัน</span> <span style="white-space:nowrap;"> ให้คุณมั่นใจทุกการเดินทาง</span> <br /><span style="white-space:nowrap;">ไปกับศูนย์บริการฟอร์ดทั่วประเทศ</span>
<br /><br />
 <span style="white-space:nowrap;">อย่าลืม! จองคิวเช็คระยะเลยวันนี้</span> 
<br /><br />
<span style="white-space:nowrap;">บริการใหม่!! ฟอร์ดเพิ่มความสะดวกสบาย</span>
<span style="white-space:nowrap;">ให้คุณสามารถนัดหมายเช็คระยะที่ศูนย์บริการฟอร์ดง่ายๆ</span>
<span style="white-space:nowrap;">ผ่านระบบ Online Booking ตลอด 7 วัน</span><br />
<span style="white-space:nowrap;">พร้อมการรับประกันเช็คระยะภายใน 60  นาที</span>
<span style="white-space:nowrap;">หากไม่ทัน</span>
<span style="white-space:nowrap;">คุณจะได้รับบริการเช็คระยะครั้งนั้น "ฟรีทันที"</span></span>'''
cta1_text='''<span style="font-family:Tahoma, Verdana, Sans-serif">นัดหมายตอนนี้</span>'''
cta1_url='''https://onlinebooking.ford.co.th/'''

[[module]] #Custom 01
path='email_modules/custom/3columntitle3icons'
color='white'

  title = '''<span style="font-family:Tahoma, Verdana, Sans-serif">ทำไมต้องศูนย์บริการฟอร์ด?</span>'''
  icon1 = '''ico_2e_fordsvc_a'''
  text1 = '''<span style="font-family:Tahoma, Verdana, Sans-serif"><span style="white-space:nowrap;">มั่นใจอะไหล่แท้ฟอร์ด</span> 
                    <span style="white-space:nowrap;">100%</span>  
                    <span style="white-space:nowrap;">พร้อมการบำรุงรักษารถยนต์</span>
                    <span style="white-space:nowrap;">อย่างมีประสิทธิภาพ</span>เพื่อ
                    <span style="white-space:nowrap;">สมรรถนะสูงสุดของรถคุณ</span></span>'''
  icon2 = '''ico_2e_fordsvc_b'''
  text2 = '''<span style="font-family:Tahoma, Verdana, Sans-serif"><span style="white-space:nowrap;">ตรวจเช็คด้วยช่างเทคนิค</span> 
                    <span style="white-space:nowrap;">ฟอร์ดที่ผ่านการอบรม</span> 
                    <span style="white-space:nowrap;">รวมถึงเครื่องมือและอุปกรณ์</span> 
                    <span style="white-space:nowrap;">ทันสมัยที่ออกแบบมาเพื่อ</span>
                    <span style="white-space:nowrap;">รถฟอร์ดโดยเฉพาะ</span></span>'''
  icon3 = '''ico_2e_fordsvc_c_th'''
  text3 = '''<span style="font-family:Tahoma, Verdana, Sans-serif"><span style="white-space:nowrap;">เก็บบันทึกสถิติรถฟอร์ด</span> 
                    <span style="white-space:nowrap;">ของคุณอย่างเป็นระบบ</span> 
                    <span style="white-space:nowrap;">เพื่อเพิ่มมูลค่าในการขายต่อ</span></span>'''

[[module]] #Banner Image No Link
path = '''email_modules/image/banner_nolink'''
color = '''white'''

  image = '''th_edm2_whyfordsvc_20161115'''


[[module]] #Split 04
path='email_modules/split/04'
color='green'

  title='''<span style="font-family:Tahoma, Verdana, Sans-serif">ประหยัดกับชุดน้ำมันเครื่อง<br />สุดคุ้ม</span>'''
  copy='''<span style="font-family:Tahoma, Verdana, Sans-serif;">
<span style="white-space:nowrap">ฟอร์ดใจดีมอบส่วนลดมูลค่า 300 บาท</span>
<span style="white-space:nowrap">เมื่อซื้อโปรแกรมชุดน้ำมันเครื่องสุดคุ้ม</span>
<span style="white-space:nowrap">แพ็คเกจใดก็ได้</span>
<span style="white-space:nowrap">ซื้อวันนี้ประหยัดทันที</span>
</span>'''
  cta1_text='''<span style="font-family:Tahoma, Verdana, Sans-serif">คลิกเพื่อดูรายละเอียดและราคา</span>'''
cta1_url='''https://www.ford.co.th/owner/oil-save-pack/'''
cta1_icon='''more'''
cta1_link_name = '''OSP'''
image = '''th_edm2_savebigonoil_20160801'''


[[module]] #TH Social
path='email_modules/footer/th/social'
color='white'

[[module]] #TH Online
path='email_modules/footer/th/online'
color='white'
+++