+++
markets = ["th"]
title = '''TH Service Reminder First Past Due 004 BKK'''

[[module]]
path='email_modules/preheader'
color='''nothing'''

	preheader = '''ฟอร์ดให้คุณสุขยิ่งกว่า กับบริการดีๆ พร้อมส่วนลดอะไหล่และค่าน้ำมันเครื่องสูงสุดถึง 18%'''

[[module]] #Header Logo
path='email_modules/header/logo'
color='white'

  image = '''white'''
  url_link = '''https://www.ford.co.th/'''


[[module]]
path='email_modules/cover/02'

color='''white'''
icon='''th_edm2_svc_wrench_urgent_20160801'''
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
cta1_link_name = '''book_now'''


[[module]] #Split 04
path='email_modules/split/04'
color='green'

  title='''<span style="font-family:Tahoma, Verdana, Sans-serif"><span style="white-space:nowrap;">ประหยัดค่าน้ำมันเครื่อง</span><br /><span style="white-space:nowrap;">สูงสุด</span></span>'''
  copy='''<span style="font-family:Tahoma, Verdana, Sans-serif;">
<span style="white-space:nowrap;">ด้วยโปรแกรมชุดน้ำมันเครื่องสุดคุ้ม</span> <br />
<span style="white-space:nowrap;">(Oil Save Pack)</span>  <br />
<span style="white-space:nowrap;">ให้คุณประหยัดสูงสุดถึง 18%</span> <br />
<span style="white-space:nowrap;">ในการเปลี่ยนน้ำมันเครื่อง </span><br /> 
<span style="white-space:nowrap;">ไส้กรองน้ำมันเครื่อง </span> <br />
<span style="white-space:nowrap;">และโอริงน๊อตอ่างน้ำมันเครื่อง</span> 
</span>'''
  cta1_text='''<span style="font-family:Tahoma, Verdana, Sans-serif">คลิกเพื่อดูรายละเอียดและราคา</span>'''
cta1_url='''https://www.ford.co.th/owner/oil-save-pack/'''
cta1_icon='''more'''
cta1_link_name = '''OSP'''
image = '''th_edm2_savebigonoil18_20161221'''


[[module]] #TH Social
path='email_modules/footer/th/social'
color='white'

[[module]] #TH Online
path='email_modules/footer/th/online'
color='white'
+++