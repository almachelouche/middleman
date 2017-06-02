+++
markets = ["th"]
title = '''TH Service Reminder First Past Due 005 BKK'''

[[module]]
path='email_modules/preheader'
color='''nothing'''

	preheader = '''Discover how much you can save with a Scheduled Service Pack.'''

[[module]] #Header Logo
path='email_modules/header/logo'
color='white'

  image = '''white'''
  url_link = '''https://www.ford.co.th/'''


[[module]]
path='email_modules/cover/02'

color='''white'''
icon='''th_edm2_svc_wrench_urgent_20160801'''
title='''<span style="color:#ff6600;font-family:Tahoma, Verdana, Sans-serif">รถ <%${user.CustomAttribute['Model']}%> ของคุณ เลยเวลาเช็คระยะแล้ว</span>'''
copy='''<span style="font-family:Tahoma, Verdana, Sans-serif">สวัสดีคุณ <%InsertIf expression="${(user['FirstName'] == null || user['FirstName'] == '-')}" id="FirstName" %>ท่านลูกค้าฟอร์ด<%/InsertIf%> <%InsertElse%> <%${user['FirstName']}%> <%/InsertElse%></span><br /><br />
<span style="font-family:Tahoma, Verdana, Sans-serif">
          	<span style="white-space:nowrap;">เพื่อรักษารถ <%${user.CustomAttribute['Model']}%></span> 
            <span style="white-space:nowrap;">ของคุณให้อยู่ในสภาพดี</span>
            <span style="white-space:nowrap;">และวิ่งได้อย่างเต็มประสิทธิภาพสม่ำเสมอ</span> 
            <span style="white-space:nowrap;">อย่าลืมนำรถเข้าศูนย์บริการ</span>
            <span style="white-space:nowrap;">เพื่อตรวจเช็คระยะเมื่อครบกำหนด</span>
          </span>
<br /><br />
 <span style="white-space:nowrap;font-family:Tahoma, Verdana, Sans-serif">อย่าลืม! จองคิวเช็คระยะเลยวันนี้</span> 
<br /><br />
<span style="font-family:Tahoma, Verdana, Sans-serif">
<span style="white-space:nowrap;">บริการใหม่!! ฟอร์ดเพิ่มความสะดวกสบาย</span>
<span style="white-space:nowrap;">ให้คุณสามารถนัดหมายเช็คระยะ</span>ที่<span style="white-space:nowrap;">ศูนย์บริการฟอร์ดง่ายๆ</span>
<span style="white-space:nowrap;">ผ่านระบบ Online Booking ตลอด 7 วัน</span><br />
<span style="white-space:nowrap;">พร้อมการรับประกันเช็คระยะภายใน 60  นาที</span>
<span style="white-space:nowrap;">หากไม่ทัน</span><br />
<span style="white-space:nowrap;">คุณจะได้รับบริการเช็คระยะครั้งนั้น</span> 
<span style="white-space:nowrap;">"ฟรีทันที"</span>
</span>'''
cta1_text='''<span style="font-family:Tahoma, Verdana, Sans-serif">นัดหมายตอนนี้</span>'''
cta1_url='''https://onlinebooking.ford.co.th/'''
cta1_link_name = '''book_now'''


[[module]] #Split 04
path='email_modules/split/04'
color='green'

  title='''<span style="font-family:Tahoma, Verdana, Sans-serif">Save on service</span>'''
  copy='''<span style="font-family:Tahoma, Verdana, Sans-serif;">Save up to 10% or 3,700 THB on maintenance with Ford’s Scheduled Service Packs. Plus, you’ll enjoy a 0% interest rate for 10 months when you use a K Bank credit card. Offer ends August 31, 2017.</span>'''
  cta1_text='''<span style="font-family:Tahoma, Verdana, Sans-serif">FIND OUT MORE ></span>'''
cta1_url='''https://www.ford.co.th/owner/schedule-service/'''
cta1_icon='''more'''
cta1_link_name = '''SSP'''
image = '''th_edm5a_specialoffer_20160801'''


[[module]] #TH Social
path='email_modules/footer/th/social'
color='white'

[[module]] #TH Online
path='email_modules/footer/th/online'
color='white'
+++