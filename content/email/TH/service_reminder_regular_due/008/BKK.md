+++
markets = ["th"]
title = '''TH Service Reminder Regular Due 008 BKK'''

[[module]]
path='email_modules/preheader'

	preheader = '''ดูแลเครื่องยนต์ของคุณด้วยโปรแกรมชุดน้ำมันเครื่องสุดคุ้ม Oil Save Packs'''

[[module]]
path='email_modules/header/logo'
color='white'

	image='''white'''
	url_link='''https://www.ford.co.th/'''

[[module]]
path='email_modules/cover/02'
color='''white'''

	icon='''th_edm2_svc_wrench_20160801'''
	title='''<span style="font-family:Tahoma, Verdana, Sans-serif"><span style="white-space:nowrap;">ได้เวลาเช็คสภาพรถ<span style="white-space:nowrap;">ของคุณแล้ว</span>'''
	copy='''
		<span style="font-family:Tahoma, Verdana, Sans-serif">สวัสดีค่ะ คุณ <%InsertIf expression="${(user['FirstName'] == null || user['FirstName'] == '-')}" id="FirstName" %>ท่านลูกค้าฟอร์ด<%/InsertIf%> <%InsertElse%> <%${user['FirstName']}%> <%/InsertElse%>
			<br />
			<br />
			<span style="white-space:nowrap;">รถ <%${user.CustomAttribute['Model']}%> ของคุณได้เวลาตรวจเช็คระยะแล้ว</span>
			<br />
			<span style="white-space:nowrap;"> ที่ศูนย์บริการฟอร์ด</span>
			<span style="white-space:nowrap;">เรามีช่างผู้ชำนาญงานของฟอร์ด</span>
			<br />
			<span style="white-space:nowrap;">ที่พร้อมดูแลรถยนต์ของคุณ</span>
			<span style="white-space:nowrap;">ให้อยู่ในสภาพสมบูรณ์ทุกเมื่อ</span>
			<br />
			<br />
			<span style="white-space:nowrap;">เช็คระยะครั้งถัดไปวันที่ : </span> 
			<span style="white-space:nowrap;"><strong><% ${user.CustomAttribute['NextServiceDate']} %></strong></span> 
			<br /
			><br />
			<span style="white-space:nowrap;">บริการใหม่!!</span>
			<span style="white-space:nowrap;">ฟอร์ดเพิ่มความสะดวกสบาย</span>
			<br />
			<span style="white-space:nowrap;">ให้คุณสามารถนัดหมายเช็คระยะ</span>ที่<span style="white-space:nowrap;">ศูนย์บริการฟอร์ดง่ายๆ</span>
			<br />
			<span style="white-space:nowrap;">ผ่านระบบ Online Booking</span> 
			<span style="white-space:nowrap;">ตลอด 7 วัน</span>
			<br>
			<span style="white-space:nowrap;">พร้อมการรับประกันเช็คระยะ</span>
			<span style="white-space:nowrap;">ภายใน 60	นาที</span>
			<br />
			<span style="white-space:nowrap;">หากไม่ทัน</span>
			<span style="white-space:nowrap;">คุณจะได้รับบริการเช็คระยะครั้งนั้น</span> 
			<span style="white-space:nowrap;">"ฟรีทันที"</span>
		</span>
	'''
	cta1_text='''<span style="font-family:Tahoma, Verdana, Sans-serif">นัดหมายตอนนี้</span>'''
	cta1_url='''https://onlinebooking.ford.co.th/'''

[[module]]
path='email_modules/cover/03'
color='''white'''

	copy='''
	<span style="font-family:Tahoma, Verdana, Sans-serif;color:#b3b3b3;">
		<span style="white-space:nowrap;">หมายเลข VIN :</span> 
		<span style="white-space:nowrap;"><% ${user.CustomAttribute['VIN']} %></span>
		<br />
		<span style="white-space:nowrap;">เข้ารับบริการครั้งล่าสุดวันที่ :</span> 
		<span style="white-space:nowrap;"><% ${user.CustomAttribute['Last_Reported_Service_Date']} %></span>
		<br />
		<span style="white-space:nowrap;">ระยะทางล่าสุด :</span> 
		<span style="white-space:nowrap;"><% ${user.CustomAttribute['Mileage']} %></span>
	</span>'''

[[module]] #Banner Image
path='email_modules/image/banner'
color='white'

	image='''th_60min_express_service_20170829'''
	url_link='''https://www.ford.co.th/ford-owner/60mins-express-service/'''
	url_link_name='''60min_express_service'''

[[module]]

	path='email_modules/custom/3columntitle3icons'
	color='white'
	title = '''<span style="font-family:Tahoma, Verdana, Sans-serif">ทำไมต้องศูนย์บริการฟอร์ด?</span>'''
	icon1 = '''ico_2e_fordsvc_a'''
	text1 = '''
		<span style="font-family:Tahoma, Verdana, Sans-serif">
			<span style="white-space:nowrap;">มั่นใจอะไหล่แท้</span> 
			<span style="white-space:nowrap;">ฟอร์ด 100%</span>
			<span style="white-space:nowrap;">พร้อมการบำรุงรักษารถยนต์</span>
			<span style="white-space:nowrap;">อย่างมีประสิทธิภาพเพื่อ</span>
			<span style="white-space:nowrap;">สมรรถนะสูงสุดของรถคุณ</span>
		</span>
	'''
	icon2 = '''ico_2e_fordsvc_b'''
	text2 = '''
		<span style="font-family:Tahoma, Verdana, Sans-serif">
			<span style="white-space:nowrap;">ตรวจเช็คด้วยช่างเทคนิค</span> 
			<span style="white-space:nowrap;">ฟอร์ดที่ผ่านการอบรม</span> 
			<span style="white-space:nowrap;">รวมถึงเครื่องมือและอุปกรณ์</span> 
			<span style="white-space:nowrap;">ทันสมัยที่ออกแบบมาเพื่อ</span>
			<span style="white-space:nowrap;">รถฟอร์ดโดยเฉพาะ</span>
		</span>
	'''
	icon3 = '''ico_2e_fordsvc_c_th'''
	text3 = '''
		<span style="font-family:Tahoma, Verdana, Sans-serif">
			<span style="white-space:nowrap;">เก็บบันทึกสถิติรถฟอร์ด</span> 
			<span style="white-space:nowrap;">ของคุณอย่างเป็นระบบ</span> 
			<span style="white-space:nowrap;">เพื่อเพิ่มมูลค่าในการขายต่อ</span>
		</span>
	'''

[[module]]
path = '''email_modules/image/banner_nolink'''
color = '''white'''

	image = '''th_edm2_whyfordsvc_20161115'''

[[module]]

	path='email_modules/split/04'
	color='green'
	title='''<span style="font-family:Tahoma, Verdana, Sans-serif">ประหยัดค่าน้ำมันเครื่อง<br />สูงสุด</span>'''
	copy='''
		<span style="font-family:Tahoma, Verdana, Sans-serif">
			<span style="white-space:nowrap;">เพิ่มความอุ่นใจในการขับขี่</span>
			<br />
			<span style="white-space:nowrap;">พิเศษ!เมื่อซื้อโปรแกรมชุด</span>
			<span style="white-space:nowrap;">น้ำมันเครื่องสุดคุ้ม (OSP)</span>
			<span style="white-space:nowrap;">รับส่วนลดเพิ่ม 300 บาท</span> 
			<span style="white-space:nowrap;">สำหรับแพ็กเกจ 2 ครั้ง</span> 
			<span style="white-space:nowrap;">และรับส่วนลดเพิ่ม</span>
			<span style="white-space:nowrap;">500 บาท</span> 
			<span style="white-space:nowrap;">สำหรับแพ็กเกจ 3 ครั้ง</span>
		</span>
	'''
	cta1_text='''<span style="font-family:Tahoma, Verdana, Sans-serif">คลิกเพื่อดูรายละเอียดและราคา</span>'''
	cta1_url='''https://www.ford.co.th/owner/servicecampaign/'''
	cta1_icon='''more'''
	cta1_link_name = '''OSP'''
	image = '''th_edm2_savebigonoil_20170122'''

[[module]]
path='email_modules/cover/02'
color='''white'''

	icon='''th_edm3_extendedwarranty_20160921'''
	title='''<span style="font-family:Tahoma, Verdana, Sans-serif">โปรแกรมขับขี่อุ่นใจ</span>'''
	copy='''
		<span style="font-family:Tahoma, Verdana, Sans-serif">
			<span style="white-space:nowrap;">สบายใจ งบไม่บานปลาย</span>  
			<span style="white-space:nowrap;">เมื่อซื้อโปรแกรมขับขี่อุ่นใจ</span> 
			<span style="white-space:nowrap;">ก่อนรถฟอร์ดของคุณครบ 35 เดือน</span>
			<br /> 
			<span style="white-space:nowrap;">หรือ 100,000 กิโลเมตร</span>   
			<span style="white-space:nowrap;">(แล้วแต่อย่างหนึ่งอย่างใดถึงก่อน)</span><br />  
			<span style="white-space:nowrap;">โปรแกรมนี้ช่วยเพิ่มความอุ่นใจ</span>
			<span style="white-space:nowrap;">ในการขับขี่รถยนต์ให้คุณทุกเส้นทาง</span><br />  
			<span style="white-space:nowrap;">โดยไม่ต้องกังวลกับค่าใช้จ่าย</span>  
			<span style="white-space:nowrap;">หรือ</span> 
			<span style="white-space:nowrap;">การซ่อมแซมที่ไม่คาดคิด</span>
			<span style="white-space:nowrap;">ที่อาจเกิดขึ้นในอนาคต</span><br />   
			<span style="white-space:nowrap;">และยังช่วยเพิ่มมูลค่า</span> 
			<span style="white-space:nowrap;">ในการขายรถต่อในอนาคตอีกด้วย</span>
		</span>
	'''
	cta1_text='''<span style="font-family:Tahoma, Verdana, Sans-serif">ศึกษารายละเอียดเพิ่มเติม</span>'''
	cta1_url='''http://www.ford.co.th/buying/solutions/premium-protection-plus'''
	cta1_link_name = '''ppp'''

[[module]]

	path='email_modules/footer/th/social'
	color='white'

[[module]]

	path='email_modules/footer/th/online'
	color='white'
+++