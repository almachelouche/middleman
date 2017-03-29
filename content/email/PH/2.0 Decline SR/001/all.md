+++
markets = ["ph"]
title = '''PH 2.0 Decline SR'''


[[module]]
path='email_modules/preheader'
color='''nothing'''

preheader = '''xxx'''

[[module]] #Header Logo
path='email_modules/header/logo'
color='white'

  image = '''white'''
  url_link = '''https://www.ford.co.ph/'''

[[module]] #Cover 06
path='email_modules/cover/02'
color='''darkblue'''
icon='''ph_edm2d_svcwrench_urgent_20170328'''

title = '''Your #Nameplate# needs attention'''
copy = '''We noticed that you declined an important part of your servicing at your last appointment. Your #Nameplate# may now be unsafe to drive, and that’s got us worried.<br /><br />When you come into a Ford service center, you’re putting your vehicle into the best hands possible. Our trained technicians know the specifics of your Ford vehicle, only use genuine Ford parts and state-of-the-art diagnostic tools. No one else can guarantee that.<br /><br />It's important to book your service today. Just click below to contact #Ford Dealership# (during business hours) or to find your nearest dealer.'''
cta1_text='''CALL #Dealer Phone Number#'''
cta1_url='''tel:<%${user.CustomAttribute['Dealer_Phone']}%>'''
cta2_text='''FIND A DEALER'''
cta2_url='''https://www.ford.co.th/locate-a-dealer/'''
cta2_url_link_name='''find_dealer'''

[[module]] #Service Status No Copy
path='email_modules/custom/svcstatus_nocopy'
color='darkblue'
      
toptitle='''Your #Nameplate#’s Health Status'''
  segmentAgreen = '''(user.CustomAttribute['Brake'] == null)'''
  segmentAyellow = '''(user.CustomAttribute['Brake'] == 'YBRAKE')'''
  segmentAred = '''(user.CustomAttribute['Brake'] == 'RBRAKE')'''
    icon1green = '''in_edm2d_status_brake_black_20160801'''
    title1green = '''<span style="font-family:Tahoma, Verdana, Sans-serif">Good to go</span>'''
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

[[module]] #PH Social
path = 'email_modules/footer/ph/social'
color = 'white'

[[module]] #PH Online
path = 'email_modules/footer/ph/online'
color = 'white'
+++