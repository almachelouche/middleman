+++
markets = ["th"]
title = '''TH Welcome Follow Up_All'''

[[module]]
path='email_modules/preheader'
color='''white'''

preheader = '''Ford Owners App แอพพลิเคชั่นเพื่อเจ้าของรถฟอร์ด เพื่อการดูแลรถฟอร์ดที่ง่ายขึ้น รวมทุกเรื่องที่คุณต้องการในหนึ่งเดียว'''

[[module]] #Header Logo
path='email_modules/header/logo'
color='white'

  image = '''white'''
  url_link = '''https://www.ford.co.th/'''

[[module]] #Cover 01
path='email_modules/cover/01'
color='''white'''
 
 title = '''<span style="font-family:Tahoma, Verdana, Sans-serif">
 <span style=" white-space:nowrap;">คุณได้ลองใช้</span> 
 <span style=" white-space:nowrap;">Ford Owners App</span>
 <span style=" white-space:nowrap;">แล้วหรือยัง?</span></span>'''
  copy = '''<span style="font-family:Tahoma, Verdana, Sans-serif">
  <span style=" white-space:nowrap;">สวัสดีค่ะ คุณ <%InsertIf expression="${(user['FirstName'] == null || user['FirstName'] == '-')}" id="FirstName" %></span>
  <span style=" white-space:nowrap;">ท่านลูกค้าฟอร์ด<%/InsertIf%> <%InsertElse%> <%${user['FirstName']}%> <%/InsertElse%></span>
  <br /><br />
  <span style=" white-space:nowrap;">ถ้าคุณกำลังมองหาตัวช่วยดีๆ</span> 
  <span style=" white-space:nowrap;">ที่จะทำให้เจ้าของรถฟอร์ดอย่างคุณ</span><br />
  <span style=" white-space:nowrap;">สามารถดูแลรถได้ง่ายดายขึ้น </span>
  <span style=" white-space:nowrap;">เราขอแนะนำแอปพลิเคชัน Ford Owners</span><br />
  <span style=" white-space:nowrap;">ที่จะช่วยเชื่อมโยงคุณ</span>กับ<span style=" white-space:nowrap;">รถฟอร์ดของคุณได้ทุกที่ทุกเวลา</span>
  <span style=" white-space:nowrap;">ทดลองใช้งานได้แล้ววันนี้</span></span>'''
  
[[module]] #Custom 05
path='email_modules/custom/4columnicon4titlescopy'
color='white'

title1 = '''<span style="font-family:Tahoma, Verdana, Sans-serif"><a href="https://youtu.be/3r79gbfZdO8" name="Decoder_1" style="color:#5CB8B2; text-decoration:none;" >
รายละเอียดการ<span style=" white-space:nowrap;">บำรุงรักษา</span><br />
<span style=" white-space:nowrap;">รถยนต์ตามระยะ</span></a></span>'''
  icon1 = '''in_edm1c_ownerapp_a_20160801'''
  text1 = '''<span style="font-family:Tahoma, Verdana, Sans-serif"><a href="https://youtu.be/3r79gbfZdO8" name="Decoder_2" style="color:#5CB8B2; text-decoration:none;" >
 <span style=" white-space:nowrap;">รายการอะไหล่</span>
 <br>และ<span style=" white-space:nowrap;">ช่วงเวลา</span>
 <br>ที่<span style=" white-space:nowrap;">ต้องเปลี่ยนอะไหล่</span>
 <span style=" white-space:nowrap;">รถของคุณ</span></a></span>'''

  title2 = '''<span style="font-family:Tahoma, Verdana, Sans-serif"><a href="https://youtu.be/eudIAyg1xp0" name="rsa_1" style="color:#5CB8B2; text-decoration:none;" >ค้นหา<span style=" white-space:nowrap;">ตัวแทนจำหน่าย</span></a></span>'''
  icon2 = '''in_edm1c_ownerapp_d_20160801'''
  text2 = '''<span style="font-family:Tahoma, Verdana, Sans-serif"><a href="https://youtu.be/eudIAyg1xp0" name="rsa_2" style="color:#5CB8B2; text-decoration:none;" >
  <span style=" white-space:nowrap;">ค้นหาศูนย์บริการฟอร์ด</span>ที่
  <span style=" white-space:nowrap;">อยู่ใกล้ตำ</span>แหน่ง<span style=" white-space:nowrap;">ของคุณ</span></a></span>'''
  title3 = '''<span style="font-family:Tahoma, Verdana, Sans-serif"><a href="https://youtu.be/7FlXKGWiHYY" name="how-to_video_1" style="color:#5CB8B2; text-decoration:none;" >
  <span style=" white-space:nowrap;">รับชมวิดีโอ</span>
  <span style=" white-space:nowrap;">How-To</span></a></span>'''
  icon3 = '''in_edm1c_ownerapp_c_20160801'''
  text3 = '''<span style="font-family:Tahoma, Verdana, Sans-serif"><a href="https://youtu.be/7FlXKGWiHYY" name="how-to_video_2" style="color:#5CB8B2; text-decoration:none;" >
  คู่มือการเป็น<span style=" white-space:nowrap;">เจ้าของรถฟอร์ด</span> 
  <span style=" white-space:nowrap;">แบบครบครัน</span></a></span>'''
  title4 = '''<span style="font-family:Tahoma, Verdana, Sans-serif"><a href="https://youtu.be/kA0M4weGse0" name="dealer_locater_video_1" style="color:#5CB8B2; text-decoration:none;" >
  <span style=" white-space:nowrap;">สัญลักษณ์</span>บนแผง<span style=" white-space:nowrap;">หน้าปัด</span>ควบคุมรถ</a></span>'''
  icon4 = '''th_edm1c_ownerapp_dashboard_20170421'''
  text4 = '''<span style="font-family:Tahoma, Verdana, Sans-serif"><a href="https://youtu.be/kA0M4weGse0" name="dealer_locater_video_2" style="color:#5CB8B2; text-decoration:none;" >
  <span style=" white-space:nowrap;">ค้นหาความหมาย</span>ของ<br>
  <span style=" white-space:nowrap;">สัญลักษณ์ต่างๆ</span>
  <span style=" white-space:nowrap;">บนหน้าปัดรถยนต์</span></a></span>'''

[[module]] #Cover 12
path='email_modules/cover/03'
color='''white'''

copy = '''<span style="font-family:Tahoma, Verdana, Sans-serif">
เริ่มต้นดูแล<span style=" white-space:nowrap;">รถฟอร์ดของคุณ</span>
<span style=" white-space:nowrap;">ได้แล้ววันนี้</span><br />
<span style=" white-space:nowrap;">ด้วยข้อมูล</span>และ<span style=" white-space:nowrap;">บริการต่างๆ</span>
<span style=" white-space:nowrap;">บนปลายนิ้วของคุณ</span><br />
<span style=" white-space:nowrap;">ดาวน์โหลดฟรี</span>
<span style=" white-space:nowrap;">ได้ที่นี่เลย</span></span>'''
  cta1_text = '''iOS'''
  cta1_url = '''https://itunes.apple.com/TH/app/ford-owners/id990342351?mt=8'''
  cta1_link_name = '''oa_ios'''
  cta2_text = '''ANDROID'''
  cta2_url = '''https://play.google.com/store/apps/details?id=com.ford.fordowners&hl=th'''
  cta2_link_name = '''oa_android'''

[[module]] #Banner Image No Link
path = '''email_modules/image/banner_nolink'''
color = '''white'''
  
  image = '''in_edm1c_ownerapp_20160801'''

[[module]] #TH Social
path='email_modules/footer/th/social'
color='white'

[[module]] #TH Online
path='email_modules/footer/th/online'
color='white'

+++