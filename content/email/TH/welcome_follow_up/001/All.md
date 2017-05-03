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
 
 title = '''<span style="font-family:Tahoma, Verdana, Sans-serif">คุณได้ลองใช้ Ford Owners App แล้วหรือยัง?</span>'''
  copy = '''<span style="font-family:Tahoma, Verdana, Sans-serif">สวัสดีค่ะ คุณ <%InsertIf expression="${(user['FirstName'] == null || user['FirstName'] == '-')}" id="FirstName" %>ท่านลูกค้าฟอร์ด<%/InsertIf%> <%InsertElse%> <%${user['FirstName']}%> <%/InsertElse%><br /><br />ถ้าคุณกำลังมองหาตัวช่วยดีๆ ที่จะทำให้เจ้าของรถฟอร์ดอย่างคุณสามารถดูแลรถได้ง่ายดายขึ้น เราขอแนะนำแอปพลิเคชัน Ford Owners ที่จะช่วยเชื่อมโยงคุณกับรถฟอร์ดของคุณได้ทุกที่ทุกเวลา ทดลองใช้งานได้แล้ววันนี้</span>'''
  
[[module]] #Custom 05
path='email_modules/custom/4columnicon4titlescopy'
color='white'

title1 = '''<span style="font-family:Tahoma, Verdana, Sans-serif"><a href="https://youtu.be/3r79gbfZdO8" name="Decoder_1" style="color:#5CB8B2; text-decoration:none;" >รายละเอียดการบำรุงรักษารถยนต์ตามระยะ</a></span>'''
  icon1 = '''in_edm1c_ownerapp_a_20160801'''
  text1 = '''<span style="font-family:Tahoma, Verdana, Sans-serif"><a href="https://youtu.be/3r79gbfZdO8" name="Decoder_2" style="color:#5CB8B2; text-decoration:none;" >รายการอะไหล่และช่วงเวลาที่ต้องเปลี่ยนอะไหล่รถของคุณ</a>.</span>'''
  title2 = '''<span style="font-family:Tahoma, Verdana, Sans-serif"><a href="https://youtu.be/eudIAyg1xp0" name="rsa_1" style="color:#5CB8B2; text-decoration:none;" >ค้นหาตัวแทนจำหน่าย</a></span>'''
  icon2 = '''in_edm1c_ownerapp_d_20160801'''
  text2 = '''<span style="font-family:Tahoma, Verdana, Sans-serif"><a href="https://youtu.be/eudIAyg1xp0" name="rsa_2" style="color:#5CB8B2; text-decoration:none;" >ค้นหาศูนย์บริการฟอร์ดที่อยู่ใกล้ตำแหน่งของคุณ</a>.</span>'''
  title3 = '''<span style="font-family:Tahoma, Verdana, Sans-serif"><a href="https://youtu.be/7FlXKGWiHYY" name="how-to_video_1" style="color:#5CB8B2; text-decoration:none;" >รับชมวิดีโอ How-To</a></span>'''
  icon3 = '''in_edm1c_ownerapp_c_20160801'''
  text3 = '''<span style="font-family:Tahoma, Verdana, Sans-serif"><a href="https://youtu.be/7FlXKGWiHYY" name="how-to_video_2" style="color:#5CB8B2; text-decoration:none;" >คู่มือการเป็นเจ้าของรถฟอร์ด แบบครบครัน</a>.</span>'''
  title4 = '''<span style="font-family:Tahoma, Verdana, Sans-serif"><a href="https://youtu.be/kA0M4weGse0" name="dealer_locater_video_1" style="color:#5CB8B2; text-decoration:none;" >สัญลักษณ์บนแผงหน้าปัดควบคุมรถ</a>.</span>'''
  icon4 = '''th_edm1c_ownerapp_dashboard_20170421'''
  text4 = '''<span style="font-family:Tahoma, Verdana, Sans-serif"><a href="https://youtu.be/kA0M4weGse0" name="dealer_locater_video_2" style="color:#5CB8B2; text-decoration:none;" >ค้นหาความหมายของสัญลักษณ์ต่างๆ บนหน้าปัดรถยนต์</a>.</span>'''

[[module]] #Cover 12
path='email_modules/cover/03'
color='''white'''

copy = '''<span style="font-family:Tahoma, Verdana, Sans-serif">เริ่มต้นดูแลรถฟอร์ดของคุณได้แล้ววันนี้ ด้วยข้อมูลและบริการต่างๆ บนปลายนิ้วของคุณ ดาวน์โหลดฟรีได้ที่นี่เลย</span>'''
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