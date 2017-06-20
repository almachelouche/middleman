+++
markets = ["th"]
title = '''TH Sweet Spot 002 All'''
draft = true

[[module]]
path='email_modules/preheader'
color='''nothing'''

	preheader = '''พบส่วนลดมากมาย เพียงนัดหมายเช็คสภาพรถกับฟอร์ด'''

[[module]] #Header Logo
path='email_modules/header/logo'
color='white'

	image = '''white'''
	url_link = '''https://www.ford.co.th/'''

[[module]] #Cover 08
path='email_modules/cover/02'
color = '''white'''

	title = '''<span style="font-family:Tahoma, Verdana, Sans-serif">ต้องเปลี่ยนเมื่อถึงเวลา</span>'''
	copy = '''<span style="font-family:Tahoma, Verdana, Sans-serif">สวัสดีค่ะ คุณ <%InsertIf expression="${(user['FirstName'] == null || user['FirstName'] == '-')}" id="FirstName" %>ท่านลูกค้าฟอร์ด<%/InsertIf%> <%InsertElse%> <%${user['FirstName']}%> <%/InsertElse%><br /><br /><span style=" white-space:nowrap;">รถ <%${user.CustomAttribute['Model']}%></span> <span style=" white-space:nowrap;">ของท่านที่ผ่านการใช้งานมาพอสมควร </span><br />
<span style=" white-space:nowrap;">อาจถึงเวลาต้องเปลี่ยนชิ้นส่วนเมื่อถึงเวลา </span><br />
<span style=" white-space:nowrap;">ท่านสามารถนัดหมายกับศูนย์บริการฟอร์ดเพื่อทำการเปลี่ยนชิ้นส่วน</span>
<span style=" white-space:nowrap;">ด้วยอะไหล่แท้ของฟอร์ด เช่น แบตเตอรี่ ยาง เบรก หรือ ที่ปัดน้ำฝน</span> <br />
<span style=" white-space:nowrap;">เพื่อให้สมรรถนะของรถ</span>ยัง<span style=" white-space:nowrap;">ทำงานได้อย่างเต็มประสิทธิภาพ</span> 
<br /><br /> 
<span style=" white-space:nowrap;">ลงทะเบียนวันนี้เพื่อนัดหมายวันและเวลา</span><br />
<span style=" white-space:nowrap;">ในการพาฟอร์ดมาพบผู้เชี่ยวชาญจากเรา</span> <br />
<span style=" white-space:nowrap;">จะเปลี่ยนแบตเตอรี่ ยางรถยนต์ ผ้าเบรก</span> <br />
<span style=" white-space:nowrap;">หรือก้านปัดน้ำฝนก็ง่ายดาย</span> <span style=" white-space:nowrap;">แถมยังประหยัดกว่า</span> <br />
<span style=" white-space:nowrap;">ให้คุณมั่นใจในทุกเส้นทางไปกับเรา</span>
<br /><br />
<span style="white-space:nowrap;">นัดหมายล่วงหน้าเพื่อเข้ารับบริการได้ทันที</span> <br />
<span style="white-space:nowrap;">ติดต่อ <%${user.CustomAttribute['Dealer_Name']}%></span> <span style="white-space:nowrap;">(ระหว่างเวลาทำการ)</span><br />
<span style="white-space:nowrap;">หรือค้นหาตัวแทนจำหน่ายใกล้บ้านคุณ</span></span>'''

cta1_text='''<span style="font-family:Tahoma, Verdana, Sans-serif">โทร <%${user.CustomAttribute['Dealer_Phone']}%></span>'''
cta1_url='''tel:<%${user.CustomAttribute['Dealer_Phone']}%>'''
cta2_text='''<span style="font-family:Tahoma, Verdana, Sans-serif">ค้นหาตัวแทนจำหน่าย</span>'''
cta2_url='''https://www.ford.co.th/locate-a-dealer/'''
cta2_url_link_name='''find_dealer'''

[[module]] #Banner Image No Link
path = '''email_modules/image/banner_nolink'''
color = '''white'''

	image = '''th_edm2_whyfordsvc_20161115'''
	
	
	[[module]] #Split 04
path='email_modules/split/04'
color='green'

	title='''<span style="font-family:Tahoma, Verdana, Sans-serif">ลดสุดคุ้ม กับอะไหล่แท้ราคาพิเศษ</span></span>'''
	copy='''<span style="font-family:Tahoma, Verdana, Sans-serif;">
<span style="white-space:nowrap;">คุ้มเกินคาด</span>
<span style="white-space:nowrap;">กับชิ้นส่วนอะไหล่แท้จากฟอร์ด</span>
<span style="white-space:nowrap;">ทั้ง ผ้าเบรก แบตเตอรี่</span>
<span style="white-space:nowrap;">และก้านปัดน้ำฝน</span>
<span style="white-space:nowrap;"> พร้อมสิทธิพิเศษซื้อยาง 3 เส้น</span>
<span style="white-space:nowrap;"> ฟรี 1 เส้นทันที!</span>
<span style="white-space:nowrap;"> ตั้งแต่วันนี้</span>
<span style="white-space:nowrap;"> ถึง <span style="color:#FFF">31 ธันวาคม</span> นี้เท่านั้น</span>
</span>'''
	cta1_text='''<span style="font-family:Tahoma, Verdana, Sans-serif">คลิกเลย</span>'''
cta1_url='''https://www.ford.co.th/serviceq-3-2016/'''
cta1_icon='''more'''
cta1_link_name = '''commodity_offer'''
image = '''th_edm2d_savebigonoil25_20161207'''


[[module]] #TH Social
path='email_modules/footer/th/social'
color='white'


[[module]] #TH Online
path='email_modules/footer/th/online'
color='white'

+++