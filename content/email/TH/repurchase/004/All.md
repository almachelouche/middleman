+++
markets = ["th"]
title = '''TH Repurchase 004 All'''

[[module]]
path='email_modules/preheader'
color='''nothing'''

preheader = '''พบข้อเสนอสุดพิเศษได้ที่โชว์รูมฟอร์ดตลอดเดือนมีนาคมนี้'''

[[module]] #Header Logo
path='email_modules/header/logo'
color='white'

  image = '''white'''
  url_link = '''https://www.ford.co.th/'''

[[module]] #Cover 01
path='email_modules/cover/01'
color='white'

  title = '''<span style="font-family:Tahoma, Verdana, Sans-serif;">ประหยัดสุดคุ้ม รับมีนาคม</span>'''
  copy = '''<span style="font-family:Tahoma, Verdana, Sans-serif;">
  <span style=" white-space:nowrap;">สวัสดีคุณ <%InsertIf expression="${(user['FirstName'] == null || user['FirstName'] == '-')}" id="FirstName" %></span>
  <span style=" white-space:nowrap;">ท่านลูกค้าฟอร์ด<%/InsertIf%> <%InsertElse%> <%${user['FirstName']}%> <%/InsertElse%></span>
  <br /><br /></span>

<span style="font-family:Tahoma, Verdana, Sans-serif;">
 <span style="white-space:nowrap;">ฟอร์ดขอขอบคุณที่เป็นส่วนหนึ่ง</span><br>
 <span style="white-space:nowrap;">ของครอบครัวฟอร์ดมาโดยตลอด</span> <br>
    <span style="white-space:nowrap;">หากคุณกำลังพิจารณามองหารถคันใหม่</span> <br>
    <span style="white-space:nowrap;">เราอยากเชิญคุณมาพบกับข้อเสนอสุดพิเศษ</span><br>  
    <span style="white-space:nowrap;">เพียงลงทะเบียนทดลองขับที่โชว์รูมฟอร์ด</span><br><br>
    <span style="white-space:nowrap;">ออกรถฟอร์ด เรนเจอร์</span>  
    <span style="white-space:nowrap;">ภายในวันที่ 1-31 มีนาคม 2560</span><br> 
    <span style="white-space:nowrap;">รับดอกเบี้ยต่ำพิเศษเพียง 0.99%</span>  
    <span style="white-space:nowrap;">พร้อมฟรีประกันภัยชั้นหนึ่ง</span><br>  
    <span style="white-space:nowrap;">ดาวน์ 25% ผ่อนนาน 48 เดือน<sup>1</sup></span> 
</span>'''
  cta1_text='''<span style="font-family:Tahoma, Verdana, Sans-serif">ข้อเสนอพิเศษ</span>'''
  cta1_url = '''https://www.ford.co.th/buying/latest-offers/'''
  cta1_link_name = '''latest_offers'''
  cta1_icon = '''more'''

[[module]] #Banner Image No Link
path = '''email_modules/image/banner_nolink'''
color = '''white'''

  image = '''th_edm5a_rangerfx4_20170113'''

[[module]]
path='email_modules/split/03'
color='green'

title='''<span style="font-family:Tahoma, Verdana, Sans-serif">สิทธิพิเศษสำหรับ<br />ลูกค้าฟอร์ด</span>'''
copy='''<span style="font-family:Tahoma, Verdana, Sans-serif;">
  <span style="white-space:nowrap;">เมื่อซื้อรถยนต์ฟอร์ดคันต่อไปทุกรุ่น</span> 
  <span style="white-space:nowrap;">(ยกเว้นฟอร์ด โฟกัส)</span> 
  <span style="white-space:nowrap;">รับส่วนลดเพิ่ม 10,000 บาททันที</span> 
  <span style="white-space:nowrap;">ข้อเสนอสุดพิเศษนี้</span> 
  <span style="white-space:nowrap;">สำหรับวันที่ 1-31 มีนาคม พ.ศ. 2560</span> 
  <span style="white-space:nowrap;">นี้เท่านั้น</span> 
</span>'''
cta1_text='''<span style="font-family:Tahoma, Verdana, Sans-serif">ดูเพิ่มเติม</span>'''
cta1_url='''https://www.ford.co.th/loyaltyprogram2017/'''
cta1_icon='''more'''
cta1_link_name = '''special_offer'''
image = '''th_edm5a_specialoffer_20160801'''

[[module]] #Dual 01
path='email_modules/dual/01'
color='white'

  icon1 = '''th_edm2_svc_wrench_20160801'''
  title1 = '''<span style="font-family:Tahoma, Verdana, Sans-serif">ฟรีค่าแรงซ่อมบำรุง<br />5 ครั้ง</span>'''
  copy1 = '''<span style="font-family:Tahoma, Verdana, Sans-serif">
  
<span style=" white-space:nowrap;">เพียงคุณตัดสินใจเป็นเจ้าของฟอร์ดรุ่นใหม่</span> 
<span style=" white-space:nowrap;">ฟรีค่าแรงเช็คระยะ 5 ครั้ง</span> 
<span style=" white-space:nowrap;">คลิกเพื่อดูรายละเอียดเพิ่มเติมที่นี่</span>

</span>'''
  icon2 = '''th_edm2_ownerprofile_20160801'''
  title2 = '''<span style="font-family:Tahoma, Verdana, Sans-serif">ข้อมูลของคุณมีการ<br />เปลี่ยนแปลงหรือไม่</span>'''
  copy2 = '''<span style="font-family:Tahoma, Verdana, Sans-serif">
  
กรุณาอัพเดทข้อมูลของคุณ <br />
<span style=" white-space:nowrap;">เพื่อให้คุณ</span><span style=" white-space:nowrap;">ไม่พลาด</span><span style=" white-space:nowrap;">ข้อเสนอ</span><span style=" white-space:nowrap;">พิเศษ</span>ต่างๆ <br />
<span style=" white-space:nowrap;">จากฟอร์ด</span>
  
</span>'''
  cta1_text = '''<span style="font-family:Tahoma, Verdana, Sans-serif">ค้นหาตัวแทนจำหน่าย</span>'''
  cta1_url = '''https://www.ford.co.th/locate-a-dealer/'''
  cta1_link_name = '''find_dealer'''
  cta2_text = '''<span style="font-family:Tahoma, Verdana, Sans-serif">อัพเดทข้อมูล</span>'''
  cta2_url = '''https://www.ford.co.th/#/overlay/content/ford/th/th_th/site-wide-content/overlays/form-overlay/login'''
  cta2_link_name = '''anything_changed'''

[[module]] #Footer Disclaimer
path='email_modules/footer/disclaimer'
color='white'
text='''<span style="font-family:Tahoma, Verdana, Sans-serif">
<span style="font-weight:bold">หมายเหตุ</span><br /><br />[1]<br />
<ul>
<li>โปรโมชั่นพิเศษนี้ สำหรับฟอร์ด เรนเจอร์ รุ่น FX4 และ XLT ดับเบิ้ลแค็บ</li>
<li>เงื่อนไขฟรีประกันชั้นหนึ่ง เฉพาะบริษัทประกันที่เข้าร่วมรายการ มูลค่าต่ำสุดที่ 20,758 บาท</li>
<li>เมื่อจัดไฟแนนซ์ผ่านฟอร์ด ลีสซิ่งเท่านั้น</li><li>ตั้งแต่วันที่ 1-31 มีนาคม 2560</li>
</ul>
</span>'''

[[module]] #TH Social
path='email_modules/footer/th/social'
color='white'

[[module]] #TH Online
path='email_modules/footer/th/online'
color='white'

+++