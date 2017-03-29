+++
markets = ["th"]
title = '''TH Repurchase 005 All'''

[[module]]
path='email_modules/preheader'
color='''nothing'''

preheader = '''พบข้อเสนอสุดพิเศษได้ที่โชว์รูมฟอร์ดตลอดเดือนเมษายนนี้ ฟอร์ดขอขอบคุณที่เป็นส่วนหนึ่ง ของครอบครัวฟอร์ดมาโดยตลอด'''

[[module]] #Header Logo
path='email_modules/header/logo'
color='white'

  image = '''white'''
  url_link = '''https://www.ford.co.th/'''

[[module]] #Cover 01
path='email_modules/cover/01'
color='white'

  title = '''<span style="font-family:Tahoma, Verdana, Sans-serif;">ประหยัดสุดคุ้ม รับเดือนเมษายน</span>'''
  copy = '''<span style="font-family:Tahoma, Verdana, Sans-serif;">สวัสดีคุณ <%InsertIf expression="${(user['FirstName'] == null || user['FirstName'] == '-')}" id="FirstName" %>ท่านลูกค้าฟอร์ด<%/InsertIf%> <%InsertElse%> <%${user['FirstName']}%> <%/InsertElse%><br /><br />ฟอร์ดขอขอบคุณที่เป็นส่วนหนึ่ง ของครอบครัวฟอร์ดมาโดยตลอด หากคุณกำลังพิจารณามองหารถคันใหม่ เราอยากเชิญคุณมาพบกับข้อเสนอสุดพิเศษ เพียงลงทะเบียนทดลองขับที่โชว์รูมฟอร์ด<br /><br />ออกรถฟอร์ด เรนเจอร์ หรือ ฟอร์ด เอเวอร์เรส ภายในวันที่ 29 มีนาคม ถึง วันที่ 30 เมษายน 2560 รับดอกเบี้ยพิเศษ 0% พร้อมฟรีประกันภัยชั้นหนึ่ง<sup>*</sup><br /><br />และฟอร์ดยังมีข้อเสนอสุดพิเศษ สำหรับรถฟอร์ด เอคโคสปอร์ต หากคุณสนใจสามารถติดตามข้อเสนอราคาพิเศษบนเว็บไซต์ของเราได้ทันที</span>'''
  cta1_text='''<span style="font-family:Tahoma, Verdana, Sans-serif">ข้อเสนอพิเศษ</span>'''
  cta1_url = '''https://www.ford.co.th/buying/latest-offers/'''
  cta1_link_name = '''latest_offers'''
  cta1_icon = '''more'''

[[module]] #Banner Image No Link
path = '''email_modules/image/banner_nolink'''
color = '''white'''

  image = '''th_edm5a_retail_campaign_2017328'''

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
<span style="font-weight:bold">หมายเหตุ</span><br /><br />
1.สำหรับฟอร์ด เรนเจอร์ รุ่น Wildtrak (ยกเว้นฟอร์ด เรนเจอร์ รุ่นที่มีระบบแผนที่นำทาง) อัตราดอกเบี้ย 0% (งวดที่ 1-24) โดยต้องเช่าซื้อรวม 60 เดือนเท่านั้น และอัตราดอกเบี้ยงวดที่ 25-60 เป็นไปตามที่ธนาคารกำหนด ทั้งนี้อัตราดอกเบี้ยที่ระบุในสัญญาเช่าซื้อตลอด 5 ปี = 3.14% / ฟรีประกันภัยชั้นหนึ่ง มูลค่าประกันภัยต่ำสุดที่ 22,261 บาท จากประกันภัยคุ้มภัย / เมื่อจัดไฟแนนซ์ผ่านฟอร์ด ลีสซิ่ง เท่านั้น
2.คำนวณจากฟอร์ด เอคโค่ สปอร์ต รุ่น Trend ผ่อนต่อเดือนเพียง 5,999 บาท สำหรับค่างวดเดือนที่ 1-12 และ 9,027 บาท สำหรับ ค่างวดเดือนที่ 13-72  ที่ราคาพิเศษ 699,000 บาท 
3.สำหรับฟอร์ด เอเวอเรสต์ ทุกรุ่น ยกเว้นรุ่น 2.2 Titanium + (MY17  NAVI) และ 3.2 Titanium + (MY17  NAVI) 
อัตราดอกเบี้ย 0% (งวดที่ 1-24) โดยต้องเช่าซื้อรวม 60 เดือนเท่านั้น และอัตราดอกเบี้ยงวดที่ 25-60 เป็นไปตามที่ธนาคารกำหนด ทั้งนี้ อัตราดอกเบี้ยที่ระบุในสัญญาเช่าซื้อตลอด 5 ปี = 3.10% / ฟรีประกันภัยชั้นหนึ่ง เฉพาะบริษัทประกันภัยที่เข้าร่วมรายการ และเมื่อจัดไฟแนนซ์ผ่านฟอร์ด ลีสซิ่ง เท่านั้น 
</span>'''

[[module]] #TH Social
path='email_modules/footer/th/social'
color='white'

[[module]] #TH Online
path='email_modules/footer/th/online'
color='white'

+++