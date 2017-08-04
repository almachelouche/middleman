+++
markets = ["th"]
title = '''TH Service Reminder First Due 008 New Ranger BKK'''

[[module]]
path='email_modules/preheader'


	preheader = '''พบข้อเสนอสุดพิเศษกับโปรแกรมบำรุงรักษารถยนต์ตามระยะ (SSP)'''

[[module]] #Header Logo
path='email_modules/header/logo'
color='white'

	image = '''white'''
	url_link = '''https://www.ford.co.th/'''


[[module]]
path='email_modules/cover/02'

color='''white'''
icon='''th_edm2_svc_wrench_20160801'''
title='''<span style="font-family:Tahoma, Verdana, Sans-serif">
						<span style="white-space:nowrap;">เวลาที่คุณเพลิดเพลิน</span>
						<span style="white-space:nowrap;">ผ่านไปเร็วเสมอ</span>
					</span>'''
copy='''<span style="font-family:Tahoma, Verdana, Sans-serif">สวัสดีค่ะ คุณ <%InsertIf expression="${(user['FirstName'] == null || user['FirstName'] == '-')}" id="FirstName" %>ท่านลูกค้าฟอร์ด<%/InsertIf%> <%InsertElse%> <%${user['FirstName']}%> <%/InsertElse%></span><br /><br />

<span style="font-family:Tahoma, Verdana, Sans-serif">
						<span style="white-space:nowrap;">ถึงเวลาพารถ <%${user.CustomAttribute['Model']}%></span> 
						<span style="white-space:nowrap;">ของคุณไปตรวจเช็คระยะครั้งแรกแล้ว</span> 
						<span style="white-space:nowrap;">รับรองว่ารวดเร็วและครบครัน</span> 
						<span style="white-space:nowrap;">ให้คุณมั่นใจว่ารถ <%${user.CustomAttribute['Model']}%></span> 
						<span style="white-space:nowrap;">ของคุณจะพร้อมสำหรับทุกการเดินทาง</span> 
						<span style="white-space:nowrap;">ไปกับศูนย์บริการฟอร์ดทั่วประเทศ</span>
</span>
<br /><br />
<span style="font-family:Tahoma, Verdana, Sans-serif">
<span style="white-space:nowrap;">บริการใหม่!!</span> 
<span style="white-space:nowrap;">ฟอร์ดเพิ่มความสะดวกสบาย</span>
<span style="white-space:nowrap;">ให้คุณสามารถนัดหมายเช็คระยะ</span>ที่<span style="white-space:nowrap;">ศูนย์บริการฟอร์ดง่ายๆ</span>
<span style="white-space:nowrap;">ผ่านระบบ</span> 
<span style="white-space:nowrap;">Online Booking</span> 
<span style="white-space:nowrap;">ตลอด 7 วัน</span><br />
<span style="white-space:nowrap;">พร้อมการรับประกันเช็คระยะภายใน 60	นาที</span>
<span style="white-space:nowrap;">หากไม่ทัน</span><br />
<span style="white-space:nowrap;">คุณจะได้รับบริการเช็คระยะครั้งนั้น</span> 
<span style="white-space:nowrap;">"ฟรีทันที"</span>
</span>'''
cta1_text='''<span style="font-family:Tahoma, Verdana, Sans-serif">นัดหมายตอนนี้</span>'''
cta1_url='''https://onlinebooking.ford.co.th/'''
cta1_link_name = '''book_now'''

[[module]] #Banner Image
path='email_modules/image/banner'
color='white'

 image='''TH_edm2_ServiceCampaign_20170726'''
	url_link='''https://www.ford.co.th/owner/servicecampaign/'''
	url_link_name='''servicecampaign'''
    

[[module]] #Custom 01
path='email_modules/custom/3columntitle3icons'
color='white'

	title = '''<span style="font-family:Tahoma, Verdana, Sans-serif">ทำไมต้องศูนย์บริการฟอร์ด?</span>'''
	icon1 = '''ico_2e_fordsvc_a'''
	text1 = '''<span style="font-family:Tahoma, Verdana, Sans-serif"><span style="white-space:nowrap;">มั่นใจอะไหล่แท้ฟอร์ด</span> 
										<span style="white-space:nowrap;">100%</span>
										<span style="white-space:nowrap;">พร้อมการบำรุงรักษารถยนต์</span>
										<span style="white-space:nowrap;">อย่างมีประสิทธิภาพ</span>เพื่อ
										<span style="white-space:nowrap;">สมรรถนะสูงสุดของรถคุณ</span></span>'''
	icon2 = '''ico_2e_fordsvc_b'''
	text2 = '''<span style="font-family:Tahoma, Verdana, Sans-serif"><span style="white-space:nowrap;">ตรวจเช็คด้วยช่างเทคนิค</span> 
										<span style="white-space:nowrap;">ฟอร์ดที่ผ่านการอบรม</span> 
										<span style="white-space:nowrap;">รวมถึงเครื่องมือและอุปกรณ์</span> 
										<span style="white-space:nowrap;">ทันสมัยที่ออกแบบมาเพื่อ</span>
										<span style="white-space:nowrap;">รถฟอร์ดโดยเฉพาะ</span></span>'''
	icon3 = '''ico_2e_fordsvc_c_th'''
	text3 = '''<span style="font-family:Tahoma, Verdana, Sans-serif"><span style="white-space:nowrap;">เก็บบันทึกสถิติรถฟอร์ด</span> 
										<span style="white-space:nowrap;">ของคุณอย่างเป็นระบบ</span> 
										<span style="white-space:nowrap;">เพื่อเพิ่มมูลค่าในการขายต่อ</span></span>'''

[[module]] #Banner Image No Link
path = '''email_modules/image/banner_nolink'''
color = '''white'''

	image = '''th_edm2_whyfordsvc_20161115'''


[[module]] #Split 04
path='email_modules/split/04'
color='green'

	title='''<span style="font-family:Tahoma, Verdana, Sans-serif">ประหยัดและคุ้มค่ากว่า </span>'''
	copy='''<span style="font-family:Tahoma, Verdana, Sans-serif;">
<span style="white-space:nowrap;">รับส่วนลดเพิ่มสูงสุด 10%</span>
<span style="white-space:nowrap;">หรือ 3,700 บาท</span> 
<span style="white-space:nowrap;">กับโปรแกรมบำรุงรักษารถยนต์</span>
<span style="white-space:nowrap;">ตามระยะ(SSP)</span>
<span style="white-space:nowrap;">พิเศษรับสิทธิ์</span>
<span style="white-space:nowrap;">ผ่อน 0% นาน 10 เดือน</span> 
<span style="white-space:nowrap;">เมื่อชำระผ่าน</span>
<span style="white-space:nowrap;">บัตรเครดิตกสิกรไทย</span> 
<span style="white-space:nowrap;">ตั้งแต่วันนี้ - วันที่ 31 สิงหาคม 2560</span></span>'''
	cta1_text='''<span style="font-family:Tahoma, Verdana, Sans-serif">คลิกเพื่อดูรายละเอียดและราคา ></span>'''
cta1_url='''https://www.ford.co.th/owner/servicecampaign/'''
cta1_icon='''more'''
cta1_link_name = '''SSP'''
image = '''th_edm5a_specialoffer_20160801'''

[[module]]
path='email_modules/cover/02'

color='''white'''
icon='''th_edm3_extendedwarranty_20160921'''
title='''<span style="font-family:Tahoma, Verdana, Sans-serif">โปรแกรมขับขี่อุ่นใจ</span>'''
copy='''<span style="font-family:Tahoma, Verdana, Sans-serif">
<span style="white-space:nowrap;">สบายใจ งบไม่บานปลาย</span>  
<span style="white-space:nowrap;">เมื่อซื้อโปรแกรมขับขี่อุ่นใจ</span> 
<span style="white-space:nowrap;">ก่อนรถฟอร์ดของคุณครบ 35 เดือน</span><br /> 
<span style="white-space:nowrap;">หรือ 100,000 กิโลเมตร</span>   
<span style="white-space:nowrap;">(แล้วแต่อย่างหนึ่งอย่างใดถึงก่อน)</span>  
<span style="white-space:nowrap;">โปรแกรมนี้ช่วยเพิ่มความอบอุ่นใจ</span>
<span style="white-space:nowrap;">ในการขับขี่รถยนต์ให้คุณทุกเส้นทาง</span> 
<span style="white-space:nowrap;">โดยไม่ต้องกังวลกับค่าใช้จ่าย</span>  
<span style="white-space:nowrap;">หรือ</span> 
<span style="white-space:nowrap;">การซ่อมแซมที่ไม่ได้คาดคิด</span>ที่<span style="white-space:nowrap;">อาจเกิดขึ้นในอนาคต</span>  
<span style="white-space:nowrap;">และยังช่วยเพิ่มมูลค่า</span>
<span style="white-space:nowrap;">ในการขายรถต่อในอนาคตอีกด้วย</span></span>'''
cta1_text='''<span style="font-family:Tahoma, Verdana, Sans-serif">ศึกษารายละเอียดเพิ่มเติม</span>'''
cta1_url='''http://www.ford.co.th/buying/solutions/premium-protection-plus'''
cta1_link_name = '''ppp'''


[[module]]
path='email_modules/split/07'
color='white'

title='''<span style="font-family:Tahoma, Verdana, Sans-serif">อุปกรณ์ตกแต่งสำหรับคุณ</span>'''
copy='''<span style="font-family:Tahoma, Verdana, Sans-serif">
<span style="white-space:nowrap;">ให้ฟอร์ด</span>
<span style="white-space:nowrap;">เรนเจอร์ของคุณ</span> 
<span style="white-space:nowrap;">ล้ำหน้าไปอีกขั้น</span> <br />
<span style="white-space:nowrap;">ด้วยอุปกรณ์ตกแต่งล่าสุด</span>
<span style="white-space:nowrap;">ฝาปิดกระบะท้าย</span> <br />
<span style="white-space:nowrap;">พร้อมชุดติดตั้งกุญแจล๊อค</span><br />
<span style="white-space:nowrap;">ฝาปิดกระบะท้าย</span>
<span style="white-space:nowrap;">มูลค่า 60,893.-</span> <br />
<span style="white-space:nowrap;">ที่ทำ</span>จาก<span style="white-space:nowrap;">อลูมิเนียมคุณภาพสูง</span> <br />
<span style="white-space:nowrap;">น้ำหนักเบา</span>
<span style="white-space:nowrap;">ปกป้องสัมภาระของคุณ</span><br />
<span style="white-space:nowrap;">ได้อย่างปลอดภัย</span></span>'''
cta1_text='''<span style="font-family:Tahoma, Verdana, Sans-serif">คลิกเพื่อชมอุปกรณ์เสริมทั้งหมด</span>'''
cta1_url='''https://www.ford.co.th/trucks/ranger/accessories/#overlay/content/ford/th/th_th/ranger-content/image-overlays/accessories/nudge-bar.html'''
cta1_link_name = '''acc_new_ranger'''
image='''TH_edm1a_wildtrak_roller_shutter_20170508'''

[[module]]
path='email_modules/dual/03'
color='white'

title1='''<span style="font-family:Tahoma, Verdana, Sans-serif">นัดหมายเข้ารับบริการ</span>'''
	cta1a_text='''<span style="font-family:Tahoma, Verdana, Sans-serif">ติดต่อ <%${user.CustomAttribute['Dealer_Name']}%><br />ได้ที่ <% ${user.CustomAttribute['Dealer_Phone']} %></span>'''
	cta1a_url='''tel:<%${user.CustomAttribute['Dealer_Phone']}%>'''
	cta1_link_name = ''''''
	cta1b_text='''<span style="font-family:Tahoma, Verdana, Sans-serif">ค้นหาตัวแทนจำหน่ายใกล้บ้าน<br />คุณ</span>'''
	cta1b_url='''https://www.ford.co.th/locate-a-dealer/'''
	cta1b_link_name = '''find_dealer'''
	icon1='''th_edm2_call_20160801'''

	title2='''<span style="font-family:Tahoma, Verdana, Sans-serif">ศูนย์ข้อมูลเจ้าของรถ</span>'''
	copy2='''<span style="font-family:Tahoma, Verdana, Sans-serif"><span style="color:#616161; font-size:16px">ทุกความช่วยเหลือที่คุณต้องการง่ายๆ</span><br /> 
<span style="color:#616161; font-size:16px">ในที่เดียว</span> 
<span style="white-space:nowrap; color:#616161; font-size:16px"> สำหรับเจ้าของรถฟอร์ดเท่านั้น</span></span>'''
cta2a_text='''<span style="font-family:Tahoma, Verdana, Sans-serif">วิดีโอสาธิตวิธีการใช้งาน<br />คุณสมบัติต่างๆ</span>'''
	cta2a_url='''https://www.ford.co.th/owner/owner-unauthenticated/'''
	cta2a_link_name = '''owner_center'''
	cta2b_text='''<span style="font-family:Tahoma, Verdana, Sans-serif">ผลิตภัณฑ์และบริการของฟอร์ด</span>'''
	cta2b_url='''https://www.ford.co.th/owner/owner-unauthenticated/'''
	cta2b_link_name = '''owner_center'''
	icon2='''th_edm2_ownerprofile_20160801'''

[[module]] #TH Social
path='email_modules/footer/th/social'
color='white'

[[module]] #TH Online
path='email_modules/footer/th/online'
color='white'
+++