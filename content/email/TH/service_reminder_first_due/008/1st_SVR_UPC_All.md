+++
markets = ["th"]
title = '''TH Service Reminder First Due 008 UPC'''

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
copy='''<span style="font-family:Tahoma, Verdana, Sans-serif">สวัสดีค่ะ คุณ <%InsertIf expression="${(user['FirstName'] == null || user['FirstName'] == '-')}" id="FirstName" %>ท่านลูกค้าฟอร์ด<%/InsertIf%> <%InsertElse%> <%${user['FirstName']}%> <%/InsertElse%></span>
<br />
<br />
 <span style="font-family:Tahoma, Verdana, Sans-serif">
						<span style="white-space:nowrap;">ฟอร์ดขอแจ้งให้คุณทราบ</span>ว่า<span style="white-space:nowrap;">รถคันใหม่ของคุณ</span>
                        <br />
						<span style="white-space:nowrap;">ถึงกำหนดตรวจเช็คระยะครั้งแรกแล้ว</span>
                        <br />
						<span style="white-space:nowrap;">เนื่องจากรถใหม่ทุกคัน</span>จะ<span style="white-space:nowrap;">มีระยะในการปรับสภาพ</span>
                        <br />
						<span style="white-space:nowrap;">การทำงานของรถ</span>
						<span style="white-space:nowrap;">เมื่อออกจากโชว์รูมไปวิ่งบนท้องถนน</span>
                        <br />
						<span style="white-space:nowrap;">เพื่อให้แน่ใจว่ารถของคุณ</span>
                        <br />
						<span style=" white-space:nowrap;">ทำงานอย่างเต็มสมรรถนะ</span>
					</span>
                    <br />
                    <br />
<span style="font-family:Tahoma, Verdana, Sans-serif"> 
						<span style="white-space:nowrap;">นัดหมายล่วงหน้า</span>เพื่อ<span style="white-space:nowrap;">เข้ารับบริการได้ทันที</span>
                        <br />
						<span style="white-space:nowrap;">ติดต่อ <%${user.CustomAttribute['Dealer_Name']}%></span> 
						<span style="white-space:nowrap;">(ระหว่างเวลาทำการ)</span>
                        <br />
						<span style="white-space:nowrap;">หรือค้นหาตัวแทนจำหน่ายใกล้บ้านคุณ</span>
                        <br />
                        <span style="white-space:nowrap;">ขออภัยหากคุณได้เข้ารับบริการที่ศูนย์บริการแล้ว</span>
					</span>'''

cta1_text='''<span style="font-family:Tahoma, Verdana, Sans-serif">โทร <%${user.CustomAttribute['Dealer_Phone']}%></span>'''
cta1_url='''tel:<%${user.CustomAttribute['Dealer_Phone']}%>'''
cta2_text='''<span style="font-family:Tahoma, Verdana, Sans-serif">ค้นหาตัวแทนจำหน่าย</span>'''
cta2_url='''https://www.ford.co.th/locate-a-dealer/'''
cta2_link_name='''find_dealer'''

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

	title='''
    <span style="font-family:Tahoma, Verdana, Sans-serif">ประหยัดและคุ้มค่ากว่า</span>
    '''
	copy='''<span style="font-family:Tahoma, Verdana, Sans-serif;">
<span style="white-space:nowrap;">โปรแกรมบำรุงรักษารถยนต์</span>
<br />
<span style="white-space:nowrap;">ตามระยะ (SSP)</span>
<br />
<span style="white-space:nowrap;">ประหยัดสูงสุดถึง 3,000 บาท</span> 
<br />
<span style="white-space:nowrap;">พิเศษรับสิทธิ์ผ่อน 0% นาน 10 เดือน</span>
<br />
<span style="white-space:nowrap;">เมื่อชำระผ่านบัตรเครดิตกสิกรไทย</span>
<br />
<span style="white-space:nowrap;">ตั้งแต่วันนี้ – วันที่ 31 ธันวาคม 2560</span>
'''
	cta1_text='''<span style="font-family:Tahoma, Verdana, Sans-serif">คลิกเพื่อดูรายละเอียดและราคา</span>'''
cta1_url='''https://www.ford.co.th/owner/servicecampaign/'''
cta1_icon='''more'''
cta1_link_name = '''SSP'''
image = '''th_edm5a_specialoffer_20160801'''

[[module]]
path='email_modules/cover/02'
color='''white'''

	icon='''th_edm3_extendedwarranty_20160921'''
	title='''<span style="font-family:Tahoma, Verdana, Sans-serif">โปรแกรมขับขี่อุ่นใจ</span>'''
	copy='''
		<span style="font-family:Tahoma, Verdana, Sans-serif">
			<span style="white-space:nowrap;">สบายใจ งบไม่บานปลาย</span>  
			<span style="white-space:nowrap;">เมื่อซื้อโปรแกรมขับขี่อุ่นใจ</span> 
			<span style="white-space:nowrap;">ก่อนรถฟอร์ดของคุณครบ 9 เดือน</span>
			<br /> 
			<span style="white-space:nowrap;">หรือ 15,000 กิโลเมตร</span>   
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
	cta1_url='''https://www.ford.co.th/buying/solutions/premium-protection-plus'''
	cta1_link_name = '''ppp'''

[[module]]
path='email_modules/dual/03'
color='white'

title1='''<span style="font-family:Tahoma, Verdana, Sans-serif">นัดหมายเข้ารับบริการ</span>'''
	cta1a_text='''<span style="font-family:Tahoma, Verdana, Sans-serif">ติดต่อ <%${user.CustomAttribute['Dealer_Name']}%><br />ได้ที่ <% ${user.CustomAttribute['Dealer_Phone']} %></span>'''
	cta1a_url='''tel:<%${user.CustomAttribute['Dealer_Phone']}%>'''
	cta1_link_name = ''''''
	cta1b_text='''<span style="font-family:Tahoma, Verdana, Sans-serif">ค้นหาตัวแทนจำหน่ายใกล้บ้านคุณ</span>'''
	cta1b_url='''https://www.ford.co.th/locate-a-dealer/'''
	cta1b_link_name = '''find_dealer'''
	icon1='''th_edm2_call_20160801'''

	title2='''<span style="font-family:Tahoma, Verdana, Sans-serif">ศูนย์ข้อมูลเจ้าของรถ</span>'''
	copy2=''''''
cta2a_text='''<span style="font-family:Tahoma, Verdana, Sans-serif">กรุณาอัพเดทข้อมูลของคุณ<br/>เพื่อให้คุณไม่พลาด<br/>ข้อเสนอพิเศษต่างๆ จากฟอร์ด</span>'''
	cta2a_url='''https://www.ford.co.th/#/overlay/content/ford/th/th_th/site-wide-content/overlays/form-overlay/login/'''
	cta2a_link_name = '''anything_changed''' 
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