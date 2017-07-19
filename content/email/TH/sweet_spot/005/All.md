+++
markets = ["th"]
title = '''TH Sweet Spot 005 All'''

[[module]]
path='email_modules/preheader'

	preheader = '''พบกับข้อเสนอสุดพิเศษมากมาย ณ ศูนย์บริการฟอร์ด'''

[[module]]
path='email_modules/header/logo'
color='white'

	image = '''white'''
	url_link = '''https://www.ford.co.th/'''

[[module]]
path='email_modules/cover/02'
color = '''white'''

	title = '''<span style="font-family:Tahoma, Verdana, Sans-serif">ต้องเปลี่ยนเมื่อถึงเวลา</span>'''
	copy = '''
		<span style="font-family:Tahoma, Verdana, Sans-serif">
			สวัสดีค่ะ คุณ <%InsertIf expression="${(user['FirstName'] == null || user['FirstName'] == '-')}" id="FirstName" %>ท่านลูกค้าฟอร์ด<%/InsertIf%> <%InsertElse%> <%${user['FirstName']}%> <%/InsertElse%>
			<br />
			<br />
			<span style=" white-space:nowrap;">รถ <%${user.CustomAttribute['Model']}%></span>
			<span style=" white-space:nowrap;">ของท่าน</span>
			<br />
			<span style=" white-space:nowrap;">ที่ผ่านการใช้งานมาพอสมควร </span>
			<br />
			<span style=" white-space:nowrap;">อาจถึงเวลา</span>
			<span style=" white-space:nowrap;">ต้องเปลี่ยนชิ้นส่วน</span>
			<br />
			<span style=" white-space:nowrap;">เมื่อถึงเวลา</span>
			<span style=" white-space:nowrap;">ท่านสามารถนัดหมาย</span>
			<span style=" white-space:nowrap;">กับศูนย์บริการฟอร์ด</span>
			<br />
			<span style=" white-space:nowrap;">เพื่อทำการเปลี่ยนชิ้นส่วน</span>
			<br />
			<span style=" white-space:nowrap;">ด้วยอะไหล่แท้ของฟอร์ด</span> 
			<span style=" white-space:nowrap;">เช่น </span>
			<span style=" white-space:nowrap;">แบตเตอรี่</span>
			<span style=" white-space:nowrap;">ยาง</span>
			<span style=" white-space:nowrap;">เบรก</span>
			<br />
			<span style=" white-space:nowrap;">หรือ</span> 
			<span style=" white-space:nowrap;">ที่ปัดน้ำฝน </span>
			<span style=" white-space:nowrap;">เพื่อให้สมรรถนะ</span>
			<span style=" white-space:nowrap;">ของรถยังทำงาน</span>
			<br />
			<span style=" white-space:nowrap;">ได้อย่างเต็มประสิทธิภาพ</span> 
			<br />
			<br /> 
			<span style=" white-space:nowrap;">ลงทะเบียนวันนี้</span>
			<span style=" white-space:nowrap;">เพื่อนัดหมาย</span>
			<span style=" white-space:nowrap;">วันและเวลา</span>
			<br />
			<span style=" white-space:nowrap;">ในการพาฟอร์ดมา</span>
			พบ
			<span style=" white-space:nowrap;">ผู้เชี่ยวชาญ</span>
			<span style=" white-space:nowrap;">จากเรา</span>
			<br />
			<span style=" white-space:nowrap;">จะเปลี่ยนแบตเตอรี่</span>
			<span style=" white-space:nowrap;">ยางรถยนต์</span>
			<span style=" white-space:nowrap;">ผ้าเบรก</span>
			<br />
			<span style=" white-space:nowrap;">หรือ</span>
			<span style=" white-space:nowrap;">ก้านปัดน้ำฝน</span>
			<span style=" white-space:nowrap;">ก็ง่ายดาย</span>
			<br /> 
			<span style=" white-space:nowrap;">แถมยังประหยัดกว่า</span>
			<br />
			<span style=" white-space:nowrap;">ให้คุณมั่นใจ</span>
			<span style=" white-space:nowrap;">ในทุกเส้นทาง</span>
			<span style=" white-space:nowrap;">ไปกับเรา</span>
			<br />
			<br />
			<span style="white-space:nowrap;">นัดหมายล่วงหน้า</span>
			<span style=" white-space:nowrap;">เพื่อเข้ารับบริการ</span>
			<span style=" white-space:nowrap;">ได้ทันที</span>
			<br />
			<span style="white-space:nowrap;">ติดต่อ</span>
			<span style=" white-space:nowrap;"><%${user.CustomAttribute['Dealer_Name']}%></span>
			<span style="white-space:nowrap;">(ระหว่างเวลาทำการ)</span>
			<br />
			<span style="white-space:nowrap;">หรือค้นหา</span>
			<span style=" white-space:nowrap;">ตัวแทนจำหน่าย</span>
			<br />
			<span style=" white-space:nowrap;">ใกล้บ้านคุณ</span>
		</span>
	'''

cta1_text='''<span style="font-family:Tahoma, Verdana, Sans-serif">โทร <%${user.CustomAttribute['Dealer_Phone']}%></span>'''
cta1_url='''tel:<%${user.CustomAttribute['Dealer_Phone']}%>'''
cta2_text='''<span style="font-family:Tahoma, Verdana, Sans-serif">ค้นหาตัวแทนจำหน่าย</span>'''
cta2_url='''https://www.ford.co.th/locate-a-dealer/'''
cta2_link_name='''find_dealer'''

[[module]]
path = '''email_modules/image/banner_nolink'''
color = '''white'''

	image = '''th_edm2_whyfordsvc_20161115'''

[[module]]
path='email_modules/spacer/default'
color='white'

	height="30"

[[module]]
path='email_modules/singles/title'
color='''white'''

		title='''<span style="font-family:Tahoma, Verdana, Sans-serif">สุดคุ้มกับอะไหล่แท้<br />จากฟอร์ด</span>'''

[[module]]
path='email_modules/spacer/default'
color='white'

	height="20"

[[module]]
path='email_modules/singles/copy'
color='''white'''

		copy='''
			<span style="font-family:Tahoma, Verdana, Sans-serif">
				<span style="white-space:nowrap;">เพื่อให้สมรรถนะรถฟอร์ดของคุณ</span> 
				<span style="white-space:nowrap;">ทำงานได้อย่างเต็มประสิทธิภาพ</span>
				<br /> 
				<span style="white-space:nowrap;">ฟอร์ดมีข้อเสนอสุดคุ้ม</span> 
				<span style="white-space:nowrap;">เมื่อคุณซื้ออะไหล่แท้จากฟอร์ด</span>
				<br /> 
				<span style="white-space:nowrap;">คุณจะได้มีสิทธิ์ร่วมลุ้นรับสิทธิพิเศษ</span>
				<span style="white-space:nowrap;">หรือได้รับน้ำยาทำความสะอาดหัวฉีดฟรี</span>
				<span style="white-space:nowrap;">ข้อเสนอนี้ถึงวันที่ 31 สิงหาคม 2560</span> 
				<span style="white-space:nowrap;">เท่านั้น</span>
			</span>
		'''

[[module]]
path='email_modules/custom/3icon_text'
color='white'

	icon1 = '''th_edm6_brake_20170113'''
	text1 = '''
		<span style="font-family:Tahoma, Verdana, Sans-serif">
			<span style="font-weight:bold">ผ้าเบรกสุดคุ้ม</span>
			<br />
			<br />
		    <span style="white-space:nowrap;">ซื้อผ้าเบรก</span>
		    <span style="white-space:nowrap;">Ford-Motorcraft รับฟรี</span>
		    <span style="white-space:nowrap;">น้ำยาทำความสะอาดหัวฉีด</span>
		</span>
	'''
	icon2 = '''th_edm6_tyre_20170113'''
	text2 = '''
		<span style="font-family:Tahoma, Verdana, Sans-serif">
			<span style="font-weight:bold">โปรยางสุดคุ้ม</span>
			<br />
			<br />
    		<span style="white-space:nowrap;">ซื้อยางกู๊ดเยียร์ 3 เส้น แถม</span> 
    		<span style="white-space:nowrap;">1 เส้นฟรี<sup>1</sup>	รับสิทธิ์ผ่อน 0% </span><br/>
    		<span style="white-space:nowrap;">นาน 6 เดือน ด้วยบัตร</span>
    		<span style="white-space:nowrap;">เครดิตกสิกรไทย<sup>2</sup></span>
    	</span>
    '''
    icon3 = '''th_edm6_battery_20170113'''
	text3 = '''
		<span style="font-family:Tahoma, Verdana, Sans-serif">
			<span style="font-weight:bold">แบตเตอรี่ฟอร์ดแท้สุดคุ้ม</span>
			<br />
			<br />
		    <span style="white-space:nowrap;">รับฟรี น้ำยาทำความสะอาด</span> 
		    <span style="white-space:nowrap;">หัวฉีดเมื่อซื้อแบตเตอรี่</span>
		    <span style="white-space:nowrap;">ฟอร์ดแท้ สำหรับรถฟอร์ด</span>
		    <span style="white-space:nowrap;">โดยเฉพาะ</span>
		</span>
	'''


[[module]]
path='email_modules/singles/ctablock'
color='''white'''

	cta1_text = '''<span style="font-family:Tahoma, Verdana, Sans-serif">ดูข้อเสนอเพิ่มเติม</span>'''
	cta1_url = '''https://www.ford.co.th/owner/servicecampaign/'''
	cta1_link_name = '''commodity_offer'''


[[module]]
path='email_modules/footer/th/social'
color='white'


[[module]]
path='email_modules/footer/disclaimer'
color='white'

	text='''
		<span style="font-family:Tahoma, Verdana, Sans-serif">
			หมายเหตุ:
			<br />
			<span style="white-space:nowrap;">[1] สิทธิพิเศษสำหรับยางรถยนต์กู๊ดเยียร์,</span> 
			<span style="white-space:nowrap;">ยางรถยนต์มิชลิน</span> 
			<span style="white-space:nowrap;">และยางรถยนต์บีเอฟกู๊ดริช</span> 
			<span style="white-space:nowrap;">เท่านั้น</span>
			<br />
			<span style="white-space:nowrap;">[2]สิทธิพิเศษสำหรับยางรถยนต์กู๊ดเยียร์เท่านั้น</span>
		</span>
	'''


[[module]]
path='email_modules/footer/th/online'
color='white'

+++