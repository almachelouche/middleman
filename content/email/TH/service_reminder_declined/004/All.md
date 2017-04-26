+++
markets = ["th"]
title = '''TH Service Reminder Declined 004 All'''


[[module]]
path='email_modules/preheader'
color='''nothing'''

    preheader = '''คุ้มสุดๆ! กับยางกู๊ดเยียร์ พร้อมข้อเสนอระบบเบรกและแบตเตอรี่ชั้นเยี่ยม'''

[[module]] #Header Logo
path='email_modules/header/logo'
color='white'

  image = '''white'''
  url_link = '''https://www.ford.co.th/'''

[[module]] #Cover 06
path='email_modules/cover/02'
color='''white'''
icon='''th_edm2d_svcwrench_urgent_20160801'''

title = '''<span style="color:#ff6600;font-family:Tahoma, Verdana, Sans-serif"><span style=" white-space:nowrap;">ได้เวลาเปลี่ยนอะไหล่ </span><span style=" white-space:nowrap;"><%${user.CustomAttribute['Model']}%></span> <span style=" white-space:nowrap;">ของคุณแล้ว</span></span>'''
  copy = '''<span style="font-family:Tahoma, Verdana, Sans-serif">
            <span style=" white-space:nowrap;">เราพบว่าเมื่อคุณเข้ามาตรวจสภาพรถกับฟอร์ด</span><br>
            <span style=" white-space:nowrap;">คุณได้ปฏิเสธการเปลี่ยนอะไหล่ครั้งที่ผ่านมา</span><br>
      <span style=" white-space:nowrap;">ซึ่งอาจเป็นสาเหตุให้เกิด</span>ความ<span style=" white-space:nowrap;">ไม่ปลอดภัยในการขับขี่ </span>
  <br><br>
<span style=" white-space:nowrap;">เพียงคุณพารถฟอร์ดของคุณกลับมา</span> 
<span style=" white-space:nowrap;">ที่ศูนย์บริการมาตรฐานฟอร์ด</span><br>
<span style=" white-space:nowrap;">คุณจะมั่นใจได้ว่าคุณ</span>จะ<span style=" white-space:nowrap;">ได้รับการตรวจเช็ค</span><br />
<span style=" white-space:nowrap;">จากช่างเทคนิคฟอร์ดที่ผ่านการอบรม</span>
<span style=" white-space:nowrap;">พร้อมเครื่องมือตรวจสอบอันทันสมัย</span><br />
<span style=" white-space:nowrap;">กับคุณภาพอะไหล่แท้ของฟอร์ด</span><br />
<span style=" white-space:nowrap;"> ให้คุณขับขี่รถฟอร์ด</span>ได้<span style=" white-space:nowrap;">อย่างเต็มประสิทธิภาพ </span><br><br>
<span style="white-space:nowrap;">นัดหมายล่วงหน้าเพื่อเข้ารับบริการได้ทันที</span> <br>
<span style="white-space:nowrap;">ติดต่อ <%${user.CustomAttribute['Dealer_Name']}%></span> <span style="white-space:nowrap;">(ระหว่างเวลาทำการ)</span><br>
<span style="white-space:nowrap;">หรือค้นหาตัวแทนจำหน่ายใกล้บ้านคุณ</span></span>'''

cta1_text='''<span style="font-family:Tahoma, Verdana, Sans-serif">โทร <%${user.CustomAttribute['Dealer_Phone']}%></span>'''
cta1_url='''tel:<%${user.CustomAttribute['Dealer_Phone']}%>'''
cta2_text='''<span style="font-family:Tahoma, Verdana, Sans-serif">ค้นหาตัวแทนจำหน่าย</span>'''
cta2_url='''https://www.ford.co.th/locate-a-dealer/'''
cta2_url_link_name='''find_dealer'''

[[module]] #Service Status No Copy
path='email_modules/custom/svcstatus_nocopy'
color='white'
      
      toptitle='''<span style="font-family:Tahoma, Verdana, Sans-serif">ผลตรวจเช็ค <%${user.CustomAttribute['Model']}%> ของคุณ ครั้งหลังสุด</span>'''
  segmentAgreen = '''(user.CustomAttribute['Brake'] == null)'''
  segmentAyellow = '''(user.CustomAttribute['Brake'] == 'YBRAKE')'''
  segmentAred = '''(user.CustomAttribute['Brake'] == 'RBRAKE')'''
    icon1green = '''in_edm2d_status_brake_black_20160801'''
    title1green = '''<span style="font-family:Tahoma, Verdana, Sans-serif">เบรก</span>'''
    subtitle1green = '''<span style="font-family:Tahoma, Verdana, Sans-serif">อยู่ในสภาพดี</span>'''
    icon1yellow = '''in_edm2d_status_brake_black_20160801'''
    title1yellow = '''<span style="font-family:Tahoma, Verdana, Sans-serif">เบรก</span>'''
    subtitle1yellow = '''<span style="font-family:Tahoma, Verdana, Sans-serif">ใกล้ถึงเวลาเปลี่ยน</span>'''
    icon1red = '''in_edm2d_status_brake_white_20160801'''
    title1red = '''<span style="font-family:Tahoma, Verdana, Sans-serif">เบรก</span>'''
    subtitle1red = '''<span style="font-family:Tahoma, Verdana, Sans-serif">ควรเปลี่ยนทันที</span>'''
  segmentBgreen = '''(user.CustomAttribute['Tyre'] == null)'''
  segmentByellow = '''(user.CustomAttribute['Tyre'] == 'YTYRE')'''
  segmentBred = '''(user.CustomAttribute['Tyre'] == 'RTYRE')'''
    icon2green = '''in_edm2d_status_tyre_black_20160801'''
    title2green = '''<span style="font-family:Tahoma, Verdana, Sans-serif">ยาง</span>'''
    subtitle2green = '''<span style="font-family:Tahoma, Verdana, Sans-serif">อยู่ในสภาพดี</span>'''
    icon2yellow = '''in_edm2d_status_tyre_black_20160801'''
    title2yellow = '''<span style="font-family:Tahoma, Verdana, Sans-serif">ยาง</span>'''
    subtitle2yellow = '''<span style="font-family:Tahoma, Verdana, Sans-serif">ใกล้ถึงเวลาเปลี่ยน</span>'''
    icon2red = '''in_edm2d_status_tyre_white_20160801'''
    title2red = '''<span style="font-family:Tahoma, Verdana, Sans-serif">ยาง</span>'''
    subtitle2red = '''<span style="font-family:Tahoma, Verdana, Sans-serif">ควรเปลี่ยนทันที</span>'''
  segmentCgreen = '''(user.CustomAttribute['Battery'] == null)'''
  segmentCyellow = '''(user.CustomAttribute['Battery'] == 'YBATT')'''
  segmentCred = '''(user.CustomAttribute['Battery'] == 'RBATT')'''
    icon3green = '''in_edm2d_status_battery_black_20160801'''
    title3green = '''<span style="font-family:Tahoma, Verdana, Sans-serif">แบตเตอรี่</span>'''
    subtitle3green = '''<span style="font-family:Tahoma, Verdana, Sans-serif">อยู่ในสภาพดี</span>'''
    icon3yellow = '''in_edm2d_status_battery_black_20160801'''
    title3yellow = '''<span style="font-family:Tahoma, Verdana, Sans-serif">แบตเตอรี่</span>'''
    subtitle3yellow = '''<span style="font-family:Tahoma, Verdana, Sans-serif">ใกล้ถึงเวลาเปลี่ยน</span>'''
    icon3red = '''in_edm2d_status_battery_white_20160801'''
    title3red = '''<span style="font-family:Tahoma, Verdana, Sans-serif">แบตเตอรี่</span>'''
    subtitle3red = '''<span style="font-family:Tahoma, Verdana, Sans-serif">ควรเปลี่ยนทันที</span>'''
    
  
  
[[module]]
path='email_modules/singles/copy'
color='''white'''
	
    copy='''<br /><br /><span style="font-family:Tahoma, Verdana, Sans-serif"><span style="text-align:center; font-Size:24px; line-height: 30px; font-weight: normal; font-style: regular; color:#1B394E; font-family:Tahoma, Verdana, Sans-serif; padding-bottom:20px;">สุดคุ้มกับอะไหล่แท้จากฟอร์ด</span><br /><br />เพื่อให้สมรรถนะรถฟอร์ดของคุณ ทำงานได้อย่างเต็มประสิทธิภาพ ฟอร์ดมีข้อเสนอสุดคุ้มกับอะไหล่แท้จากฟอร์ด</span>'''

[[module]] #Custom 3 Icon Text
path='email_modules/custom/3icon_text'
color='white'

  title = ''''''
  icon1 = '''th_edm6_tyre_20170113'''
  text1 = '''<span style="font-family:Tahoma, Verdana, Sans-serif"><span style="font-weight:bold">โปรยางสุดคุ้ม</span><br /><br />ซื้อยางกู๊ดเยียร์ 3 เส้น แถม 1 เส้นฟรี รับสิทธิ์ผ่อน 0% นาน 6 เดือน ด้วยบัตรเครดิตกสิกรไทย</span>'''
  icon2 = '''th_edm6_battery_20170113'''
  text2 = '''<span style="font-family:Tahoma, Verdana, Sans-serif"><span style="font-weight:bold">แบตเตอรี่ฟอร์ดแท้สุดคุ้ม</span><br /><br />คุ้มค่า คุ้มราคากับแบตเตอรี่ฟอร์ดแท้ สำหรับรถฟอร์ดโดยเฉพาะ</span>'''
  icon3 = '''th_edm6_brake_20170113'''
  text3 = '''<span style="font-family:Tahoma, Verdana, Sans-serif"><span style="font-weight:bold">ผ้าเบรก Ford-Motorcraft สุดคุ้ม</span><br /><br />ผ้าเบรก Ford-Motorcraft คุณภาพสูงในราคาที่คุ้มค่า</span>'''

[[module]]
path='email_modules/singles/ctablock'
color='''white'''
	
    cta1_text = '''<span style="font-family:Tahoma, Verdana, Sans-serif">Find A Dealer</span>'''
	cta1_url = '''https://www.ford.co.th/locate-a-dealer/'''
	cta1_link_name = '''find_dealer'''

[[module]] #TH Social
path='email_modules/footer/th/social'
color='white'

[[module]] #TH Online
path='email_modules/footer/th/online'
color='white'

+++