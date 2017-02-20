+++
markets = ["th"]
title = '''TH Service Reminder Declined 010 All'''
draft = true

[[module]]
path='email_modules/preheader'
color='''nothing'''

	preheader = '''พบกับส่วนลดพิเศษมากมาย เพียงนัดหมายเช็คสภาพรถกับฟอร์ด'''

[[module]] #Header Logo
path='email_modules/header/logo'
color='white'

  image = '''white'''
  url_link = '''https://www.ford.co.th/'''

[[module]] #Cover 06
path='email_modules/cover/02'
color='''darkblue'''
icon='''th_edm2d_svcwrench_urgent_20160801'''

title = '''Your <%${user.CustomAttribute['Model']}%> needs attention'''
  copy = '''We noticed that you declined an important part of your servicing at your last appointment. Your <%${user.CustomAttribute['Model']}%> may now be unsafe to drive, and that’s got us worried.<br /><br />When you come into a Ford service centre, you’re putting your vehicle into the best hands possible. Our trained technicians know the specifics of your Ford vehicle and only use genuine Ford parts. No one else can guarantee that.<br /><br />It's important to book your service today. Just click below to contact <Ford Dealership> (during business hours) or to find your nearest dealer.'''

cta1_text='''<span style="font-family:Tahoma, Verdana, Sans-serif">CALL <%${user.CustomAttribute['Dealer_Phone']}%></span>'''
cta1_url='''tel:<%${user.CustomAttribute['Dealer_Phone']}%>'''
cta2_text='''<span style="font-family:Tahoma, Verdana, Sans-serif">FIND A DEALER</span>'''
cta2_url='''https://www.ford.co.th/locate-a-dealer/'''
cta2_url_link_name='''find_dealer'''

[[module]] #Service Status No Copy
path='email_modules/custom/svcstatus_nocopy'
color='darkblue'
      
      toptitle='''<span style="font-family:Tahoma, Verdana, Sans-serif">ผลตรวจเช็ค <%${user.CustomAttribute['Model']}%> ของคุณ ครั้งหลังสุด</span>'''
  segmentAgreen = '''(user.CustomAttribute['Brake'] == 'G')'''
  segmentAyellow = '''(user.CustomAttribute['Brake'] == 'Y')'''
  segmentAred = '''(user.CustomAttribute['Brake'] == 'R')'''
    icon1green = '''in_edm2d_status_brake_black_20160801'''
    title1green = '''<span style="font-family:Tahoma, Verdana, Sans-serif">เบรก</span>'''
    subtitle1green = '''<span style="font-family:Tahoma, Verdana, Sans-serif">อยู่ในสภาพดี</span>'''
    icon1yellow = '''in_edm2d_status_brake_black_20160801'''
    title1yellow = '''<span style="font-family:Tahoma, Verdana, Sans-serif">เบรก</span>'''
    subtitle1yellow = '''<span style="font-family:Tahoma, Verdana, Sans-serif">ใกล้ถึงเวลาเปลี่ยน</span>'''
    icon1red = '''in_edm2d_status_brake_white_20160801'''
    title1red = '''<span style="font-family:Tahoma, Verdana, Sans-serif">เบรก</span>'''
    subtitle1red = '''<span style="font-family:Tahoma, Verdana, Sans-serif">ควรเปลี่ยนทันที</span>'''
  segmentBgreen = '''(user.CustomAttribute['Tyre'] == 'G')'''
  segmentByellow = '''(user.CustomAttribute['Tyre'] == 'Y')'''
  segmentBred = '''(user.CustomAttribute['Tyre'] == 'R')'''
    icon2green = '''in_edm2d_status_tyre_black_20160801'''
    title2green = '''<span style="font-family:Tahoma, Verdana, Sans-serif">ยาง</span>'''
    subtitle2green = '''<span style="font-family:Tahoma, Verdana, Sans-serif">อยู่ในสภาพดี</span>'''
    icon2yellow = '''in_edm2d_status_tyre_black_20160801'''
    title2yellow = '''<span style="font-family:Tahoma, Verdana, Sans-serif">ยาง</span>'''
    subtitle2yellow = '''<span style="font-family:Tahoma, Verdana, Sans-serif">ใกล้ถึงเวลาเปลี่ยน</span>'''
    icon2red = '''in_edm2d_status_tyre_white_20160801'''
    title2red = '''<span style="font-family:Tahoma, Verdana, Sans-serif">ยาง</span>'''
    subtitle2red = '''<span style="font-family:Tahoma, Verdana, Sans-serif">ควรเปลี่ยนทันที</span>'''
  segmentCgreen = '''(user.CustomAttribute['Battery'] == 'G')'''
  segmentCyellow = '''(user.CustomAttribute['Battery'] == 'Y')'''
  segmentCred = '''(user.CustomAttribute['Battery'] == 'R')'''
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
	
    copy='''<br /><br /><span style="font-family:Tahoma, Verdana, Sans-serif"><span style="text-align:center; font-Size:24px; line-height: 30px; font-weight: normal; font-style: regular; color:#1B394E; font-family:Tahoma, Verdana, Sans-serif; padding-bottom:20px;">Great deals on parts</span><br /><br />Keep your Ford in top condition with the latest offers on tyres, batteries and brake pads. </span>'''

[[module]] #Custom 3 Icon Text
path='email_modules/custom/3icon_text'
color='white'

  title = ''''''
  icon1 = '''th_edm6_tyre_20170113'''
  text1 = '''<span style="font-weight:bold">Goodyear tyres</span><br /><br />But 3 tyres, get 1 free. Plus, pay 0% interest for six months with a K Bank credit card.'''
  icon2 = '''th_edm6_battery_20170113'''
  text2 = '''<span style="font-weight:bold">Genuine Ford batteries</span><br /><br />Get a free pair of Motorcraft wiper blades with every Ford battery replacement.'''
  icon3 = '''th_edm6_brake_20170113'''
  text3 = '''<span style="font-weight:bold">Motorcraft brake pads</span><br /><br />Get a free pair of Motorcraft wiper blades with every Motorcraft brake pad replacement.'''

[[module]]
path='email_modules/singles/ctablock'
color='''white'''
	
    cta1_text = '''SEE MORE OFFERS'''
	cta1_url = '''https://www.ford.co.th/owner/service-1-2017'''
	cta1_link_name = '''commodity_offers'''


[[module]] #TH Social
path='email_modules/footer/th/social'
color='white'

[[module]] #TH Online
path='email_modules/footer/th/online'
color='white'

+++