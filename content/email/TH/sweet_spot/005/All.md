+++
markets = ["th"]
title = '''TH Sweet Spot 005 All'''

[[module]]
path='email_modules/preheader'
color='''nothing'''

	preheader = '''พบกับข้อเสนอสุดพิเศษ เมื่อนัดหมายเข้ารับบริการกับฟอร์ด'''

[[module]] #Header Logo
path='email_modules/header/logo'
color='white'

  image = '''white'''
  url_link = '''https://www.ford.co.th/'''

[[module]]
path='email_modules/cover/02'
color = '''white'''

  title = '''<span style="font-family:Tahoma, Verdana, Sans-serif">ต้องเปลี่ยนเมื่อถึงเวลา</span>'''
  copy = '''<span style="font-family:Tahoma, Verdana, Sans-serif">สวัสดีค่ะ คุณ <%InsertIf expression="${(user['FirstName'] == null || user['FirstName'] == '-')}" id="FirstName" %>ท่านลูกค้าฟอร์ด<%/InsertIf%> <%InsertElse%> <%${user['FirstName']}%> <%/InsertElse%><br /><br />
<span style=" white-space:nowrap;">รถ <%${user.CustomAttribute['Model']}%></span> <span style=" white-space:nowrap;">ของท่าน</span><br />
<span style=" white-space:nowrap;">ที่ผ่านการใช้งานมาพอสมควร </span><br />
<span style=" white-space:nowrap;">อาจถึงเวลา</span><span style=" white-space:nowrap;">ต้องเปลี่ยนชิ้นส่วน</span><br />
<span style=" white-space:nowrap;">เมื่อถึงเวลา</span>
<span style=" white-space:nowrap;">ท่านสามารถนัดหมาย</span>
<span style=" white-space:nowrap;">กับศูนย์บริการฟอร์ด</span><br />
<span style=" white-space:nowrap;">เพื่อทำการเปลี่ยนชิ้นส่วน</span><br />
<span style=" white-space:nowrap;">ด้วยอะไหล่แท้ของฟอร์ด</span> 
<span style=" white-space:nowrap;">เช่น </span>
<span style=" white-space:nowrap;">แบตเตอรี่</span>
<span style=" white-space:nowrap;">ยาง</span>
<span style=" white-space:nowrap;">เบรก</span><br />
<span style=" white-space:nowrap;">หรือ</span> 
<span style=" white-space:nowrap;">ที่ปัดน้ำฝน </span>
<span style=" white-space:nowrap;">เพื่อให้สมรรถนะ</span><span style=" white-space:nowrap;">ของรถยังทำงาน</span><br />
<span style=" white-space:nowrap;">ได้อย่างเต็มประสิทธิภาพ</span> 
<br /><br /> 
<span style=" white-space:nowrap;">ลงทะเบียนวันนี้</span>
<span style=" white-space:nowrap;">เพื่อนัดหมาย</span><span style=" white-space:nowrap;">วันและเวลา</span><br />
<span style=" white-space:nowrap;">ในการพาฟอร์ดมา</span>พบ<span style=" white-space:nowrap;">ผู้เชี่ยวชาญ</span><span style=" white-space:nowrap;">จากเรา</span><br />
<span style=" white-space:nowrap;">จะเปลี่ยนแบตเตอรี่</span>
<span style=" white-space:nowrap;">ยางรถยนต์</span>
<span style=" white-space:nowrap;">ผ้าเบรก</span><br />
<span style=" white-space:nowrap;">หรือ</span><span style=" white-space:nowrap;">ก้านปัดน้ำฝน</span>
<span style=" white-space:nowrap;">ก็ง่ายดาย</span><br /> 
<span style=" white-space:nowrap;">แถมยังประหยัดกว่า</span> <br />
<span style=" white-space:nowrap;">ให้คุณมั่นใจ</span><span style=" white-space:nowrap;">ในทุกเส้นทาง</span><span style=" white-space:nowrap;">ไปกับเรา</span>
<br /><br />
<span style="white-space:nowrap;">นัดหมายล่วงหน้า</span>
<span style=" white-space:nowrap;">เพื่อเข้ารับบริการ</span>
<span style=" white-space:nowrap;">ได้ทันที</span> <br />
<span style="white-space:nowrap;">ติดต่อ</span><span style=" white-space:nowrap;"><%${user.CustomAttribute['Dealer_Name']}%></span> <span style="white-space:nowrap;">(ระหว่างเวลาทำการ)</span><br />
<span style="white-space:nowrap;">หรือค้นหา</span><span style=" white-space:nowrap;">ตัวแทนจำหน่าย</span><br />
<span style=" white-space:nowrap;">ใกล้บ้านคุณ</span></span>'''

cta1_text='''<span style="font-family:Tahoma, Verdana, Sans-serif">โทร <%${user.CustomAttribute['Dealer_Phone']}%></span>'''
cta1_url='''tel:<%${user.CustomAttribute['Dealer_Phone']}%>'''
cta2_text='''<span style="font-family:Tahoma, Verdana, Sans-serif">ค้นหาตัวแทนจำหน่าย</span>'''
cta2_url='''https://www.ford.co.th/locate-a-dealer/'''
cta2_link_name='''find_dealer'''

[[module]] #Banner Image No Link
path = '''email_modules/image/banner_nolink'''
color = '''white'''

  image = '''th_edm2_whyfordsvc_20161115'''
  
  

[[module]]
path='email_modules/singles/copy'
color='''white'''
	
    copy='''<br /><br /><span style="font-family:Tahoma, Verdana, Sans-serif">
    <span style="text-align:center; font-Size:24px; line-height: 30px; font-weight: normal; font-style: regular; color:#1B394E; font-family:Tahoma, Verdana, Sans-serif; padding-bottom:20px;">
    สุดคุ้มกับอะไหล่แท้จากฟอร์ด</span><br /><br />
      <span style="white-space:nowrap;">เพื่อให้สมรรถนะรถฟอร์ดของคุณ </span>
      <span style="white-space:nowrap;">ทำงานได้อย่างเต็มประสิทธิภาพ </span><br />
      <span style="white-space:nowrap;">ฟอร์ดมีข้อเสนอสุดคุ้ม</span>กับ<span style="white-space:nowrap;">อะไหล่แท้จากฟอร์ด</span>
    </span>'''

[[module]]
path='email_modules/singles/copy'
color='''white'''
	
    copy='''<br /><br /><span style="font-family:Tahoma, Verdana, Sans-serif">
    <span style="text-align:center; font-Size:24px; line-height: 30px; font-weight: normal; font-style: regular; color:#1B394E; font-family:Tahoma, Verdana, Sans-serif; padding-bottom:20px;">สุดคุ้มกับอะไหล่แท้จากฟอร์ด</span><br /><br />เพื่อให้สมรรถนะรถฟอร์ดของคุณ ทำงานได้อย่างเต็มประสิทธิภาพ ฟอร์ดมีข้อเสนอสุดคุ้มเมื่อคุณซื้ออะไหล่แท้จากฟอร์ด คุณจะได้มีสิทธิ์ร่วมลุ้นรับสิทธิพิเศษ หรือได้รับน้ำยาทำความสะอาดหัวฉีดฟรี ข้อเสนอนี้ถึงวันที่ 31 สิงหาคม 2560 เท่านั้น</span>'''

[[module]] #Custom 3 Icon Text
path='email_modules/custom/3icon_text'
color='white'

  title = ''''''
  icon1 = '''th_edm6_brake_20170113'''
  text1 = '''<span style="font-family:Tahoma, Verdana, Sans-serif"><span style="font-weight:bold">ผ้าเบรกสุดคุ้ม</span><br /><br />ซื้อผ้าเบรก Ford-Motorcraft รับฟรี น้ำยาทำความสะอาดหัวฉีด</span>'''
  icon2 = '''th_edm6_tyre_20170113'''
  text2 = '''<span style="font-family:Tahoma, Verdana, Sans-serif"><span style="font-weight:bold">โปรยางสุดคุ้ม</span><br /><br />ซื้อยางกู๊ดเยียร์ 3 เส้น แถม 1 เส้นฟรี<sup>1</sup>.  รับสิทธิ์ผ่อน 0% นาน 6 เดือน ด้วยบัตรเครดิตกสิกรไทย<sup>2</sup>.</span>'''
  icon3 = '''th_edm6_battery_20170113'''
  text3 = '''<span style="font-family:Tahoma, Verdana, Sans-serif"><span style="font-weight:bold">แบตเตอรี่ฟอร์ดแท้สุดคุ้ม</span><br /><br />รับฟรี น้ำยาทำความสะอาดหัวฉีดเมื่อซื้อแบตเตอรี่ฟอร์แท้ สำหรับรถฟอร์ดโดยเฉพาะ</span>'''


[[module]]
path='email_modules/singles/ctablock'
color='''white'''
	
    cta1_text = '''<span style="font-family:Tahoma, Verdana, Sans-serif">ดูข้อเสนอเพิ่มเติม</span>'''
	cta1_url = '''https://www.ford.co.th/'''
	cta1_link_name = '''commodity_offer'''


[[module]] #TH Social
path='email_modules/footer/th/social'
color='white'


[[module]] #Footer Disclaimer
path='email_modules/footer/disclaimer'
color='white'
text='''<span style="font-family:Tahoma, Verdana, Sans-serif">หมายเหตุ:<br />[1] สิทธิพิเศษสำหรับยางรถยนต์กู๊ดเยียร์, ยางรถยนต์มิชลิน และยางรถยนต์บีเอฟกู๊ดริช เท่านั้น<br />[2]สิทธิพิเศษสำหรับยางรถยนต์กู๊ดเยียร์เท่านั้น</span>'''


[[module]] #TH Online
path='email_modules/footer/th/online'
color='white'

+++