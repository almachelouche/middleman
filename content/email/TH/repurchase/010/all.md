+++
markets = ["th"]
title = '''TH Repurchase 010 All'''
draft = true

[[module]]
path='email_modules/preheader'
color='''nothing'''

preheader = '''<span style="font-family:Tahoma, Verdana, Sans-serif">สัมผัสประสบการณ์เหนือระดับ กับ ฟอร์ดเรนเจอร์ ใหม่ และ ฟอร์ด เอเวอเรสต์ ใหม่</span>'''

[[module]] #Header Logo
path='email_modules/header/logo'
color='white'

  image = '''white'''
  url_link = '''https://www.ford.co.th/'''

[[module]] #Cover 01
path='email_modules/cover/01'
color='''white'''

  title = '''<span style="font-family:Tahoma, Verdana, Sans-serif">พบยนตรกรรมใหม่ล่าสุดจากฟอร์ดได้แล้ว วันนี้</span>'''
  copy = '''<span style="font-family:Tahoma, Verdana, Sans-serif">

<span style="white-space:nowrap;">สวัสดีค่ะ คุณ <%InsertIf expression="${(user['FirstName'] == null || user['FirstName'] == '-')}" id="FirstName" %>ท่านลูกค้าฟอร์ด<%/InsertIf%> <%InsertElse%> <%${user['FirstName']}%> <%/InsertElse%></span><br /><br />
<span style="white-space:nowrap;">ฟอร์ด <%${user.CustomAttribute['Model']}%> ขอขอบพระคุณท่านเป็นอย่างสูง</span>ที่
<span style="white-space:nowrap;">ให้เกียรติ</span><br />
และเชื่อมั่นใน
<span style="white-space:nowrap;">ยนตรกรรมของฟอร์ด</span><br /> 
<span style="white-space:nowrap;">ทางเราหวังเป็นอย่างยิ่ง</span>ว่า
<span style="white-space:nowrap;">สมรรถนะของรถฟอร์ด</span>จะ
<span style="white-space:nowrap;">ตอบสนองความต้องการของท่าน</span><br />ได้
<span style="white-space:nowrap;">อย่างราบรื่นตลอดอายุการใช้งาน</span><br /><br />
<span style="white-space:nowrap;">อย่างไรก็ตาม</span>
<span style="white-space:nowrap;"> หากท่านกำลังมองหารถคันใหม่</span><br /> 
<span style="white-space:nowrap;"> ฟอร์ดขอเรียนเชิญท่านมาสัมผัส</span>และ
<span style="white-space:nowrap;">ทดลองขับรถรุ่นใหม่</span>ที่มา
<span style="white-space:nowrap;">พร้อมเทคโนโลยีอัจฉริยะจากฟอร์ด</span><br />
<span style="white-space:nowrap;">ที่เปิดตัวในเดือนนี้</span> 
<span style="white-space:nowrap;">ได้แก่</span> 
<span style="white-space:nowrap;">ฟอร์ด เรนเจอร์ 6  รุ่นใหม่</span> 
<span style="white-space:nowrap;">ซึ่งรวมถึงรุ่น XL+</span> 
<span style="white-space:nowrap;">โอเพ่นแคบยกสูงรุ่นใหม่ล่าสุด</span>ที่
<span style="white-space:nowrap;">พร้อมตอบโจทย์ความต้องการความสมบุกสมบัน</span><br />ใน
<span style="white-space:nowrap;">ทุกสภาพการใช้งานของท่าน</span> 
<span style="white-space:nowrap;">หรือหากท่านสนใจรถ SUV</span> <br />
<span style="white-space:nowrap;">ฟอร์ดขอแนะนำ ฟอร์ด เอเวอเรสต์ 2.2Lไทเทเนียมพลัส</span> 
<span style="white-space:nowrap;">ใหม่ล่าสุด</span> <br />
<span style="white-space:nowrap;">ที่มาพร้อมฟีเจอร์ครบถ้วนเช่นเดียวกับรุ่น 3.2L (รุ่นท๊อป)</span> 
<span style="white-space:nowrap;">รวมทั้งนวัตกรรมใหม่ล่าสุด</span> <a name="sync3" href="http://www.ford.co.th/engineering/sync/" style="color: #2d94cd; text-decoration: underline;">SYNC&trade;3</a><br /> 
<span style="white-space:nowrap;">แต่เครื่องยนต์เล็กกว่า</span> 
<span style="white-space:nowrap;">ซึ่งทำให้ท่านคล่องตัวและประหยัด</span> 
<span style="white-space:nowrap;">คุ้มค่ากว่า</span>

</span>'''

[[module]] # Custom Car 2 Column
path='email_modules/custom/2column_car'
color='black'

  image1 = '''th_edm5a_exploreranger_20160913'''
  cta1_text = '''<span style="font-family:Tahoma, Verdana, Sans-serif">ฟอร์ด เรนเจอร์ ใหม่</span>'''
  cta1_url = '''http://www.ford.co.th/trucks/ranger/compare-models/'''
  cta1_link_name = '''explore_ranger'''
  cta1_icon = '''more'''
  image2 = '''th_edm5a_exploreeverest_20160913'''
  cta2_text = '''<span style="font-family:Tahoma, Verdana, Sans-serif">ฟอร์ด เอเวอเรสต์ ใหม่</span>'''
  cta2_url = '''http://www.ford.co.th/suvs/everest/compare-models/'''
  cta2_link_name = '''explore_everest'''
  cta2_icon = '''more'''

[[module]] #Cover 01
path='email_modules/cover/01'
color='black'

  title = '''<span style="font-family:Tahoma, Verdana, Sans-serif">
  
  <span style="white-space:nowrap;">พลาดไม่ได้ กับแคมเปญ</span>
  <span style="white-space:nowrap;">เรนเจอร์ เดย์ เริ่ม 1 สิงหาคมนี้</span>
  
</span>'''
  copy = '''<span style="font-family:Tahoma, Verdana, Sans-serif">
  
<span style="white-space:nowrap;">เพียงท่านจองรถฟอร์ดเรนเจอร์</span> 
<span style="white-space:nowrap;">หรือฟอร์ดรุ่นใดก็ได้</span> <br />
<span style="white-space:nowrap;">ระหว่าง 1 สิงหาคม-30 กันยายน</span> 
<span style="white-space:nowrap;">และออกรถภายใน 31 ตุลาคมศกนี้</span> 
<span style="white-space:nowrap;">ลุ้นรางวัลสร้อยคอทองคำหนัก 1 บาท 50 รางวัล</span><br />
<span style="white-space:nowrap;">รวมทั้งรางวัลใหญ่</span> 
<span style="white-space:nowrap;">ทองคำแท่งมูลค่า 1 ล้านบาท</span><br />
<span style="white-space:nowrap;">สอบถามรายละเอียดเพิ่มเติม</span>ได้ที่
<span style="white-space:nowrap;">ศูนย์บริการฟอร์ดใกล้บ้านท่าน</span>

</span>'''
  cta1_text = '''<span style="font-family:Tahoma, Verdana, Sans-serif">ค้นหาศูนย์บริการ</span>'''
  cta1_url = '''http://www.ford.co.th/locate-a-dealer/'''
  cta1_link_name = '''find_dealer'''
  cta1_icon = '''more'''

[[module]] #Banner Image
path='email_modules/image/banner'
color='white'

  image = '''th_edm5a_rangertruckmonth_20160913'''
  url_link = '''http://www.google.com'''

[[module]]
path='email_modules/split/03'
color='green'

title='''<span style="font-family:Tahoma, Verdana, Sans-serif">

สิทธิพิเศษสำหรับ<br />ลูกค้าฟอร์ด

</span>'''
copy='''<span style="font-family:Tahoma, Verdana, Sans-serif">
  
ลูกค้าฟอร์ด รับทันที ส่วนลด 
<span style="color:#FFFFFF;">10,000 บาท</span><br /> 
<span style="white-space:nowrap;">เมื่อซื้อรถฟอร์ดคันต่อไปรุ่นใดก็ได้</span> <br />
<span style="white-space:nowrap;">พิเศษ รับส่วนลดเพิ่มเป็น <span style="color:#FFFFFF;">20,000 บาท</span></span> 
<span style="white-space:nowrap;">เมื่อซื้อรถฟอร์ด โฟกัส ใหม่</span> 
<span style="white-space:nowrap;">ข้อเสนอนี้มีถึงวันที่ 31 ธันวาคม 2559</span>
  
</span>'''
cta1_text='''<span style="font-family:Tahoma, Verdana, Sans-serif">ดูเพิ่มเติม</span></span>'''
cta1_url='''http://www.ford.co.th/loyaltyprogram2016'''
cta1_icon='''more'''
cta1_link_name = '''loyalty_program'''
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
<span style=" white-space:nowrap;">เพื่อให้คุณ</span>
<span style=" white-space:nowrap;">ไม่พลาด</span>
<span style=" white-space:nowrap;">ข้อเสนอ</span>
<span style=" white-space:nowrap;">พิเศษ</span>ต่างๆ <br />
<span style=" white-space:nowrap;">จากฟอร์ด
  
</span>'''
  cta1_text = '''<span style="font-family:Tahoma, Verdana, Sans-serif">ค้นหาตัวแทนจำหน่าย</span>'''
  cta1_url = '''http://www.ford.co.th/locate-a-dealer/'''
  cta1_link_name = '''find_dealer'''
  cta2_text = '''<span style="font-family:Tahoma, Verdana, Sans-serif">อัพเดทข้อมูล</span>'''
  cta2_url = '''https://www.ford.co.th/owner/login'''
  cta2_link_name = '''anything_changed'''


[[module]] #TH Social
path='email_modules/footer/th/social'
color='white'

[[module]] #TH Online
path='email_modules/footer/th/online'
color='white'

+++