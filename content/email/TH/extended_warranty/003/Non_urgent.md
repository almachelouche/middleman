+++
markets = ["th"]
title = '''TH Extended Warranty 003 Non-Urgent'''

[[module]]
path='email_modules/preheader'
color='''nothing'''

	preheader = '''คุ้มกว่า เมื่อขยายเวลารับประกันความคุ้มครองรถฟอร์ดของคุณภายในวันที่ 31 สิงหาคมนี้'''

[[module]] #Header Logo
path='email_modules/header/logo'
color='white'

	image = '''white'''
	url_link = '''https://www.ford.co.th/'''

[[module]] #Cover 06
path='email_modules/cover/02'
color = '''white'''

	icon = '''th_edm3_extendedwarranty_20160801'''
	title = '''<span style="font-family:Tahoma, Verdana, Sans-serif">
	<span style=" white-space:nowrap;">ยืดระยะเวลา</span>
	<span style=" white-space:nowrap;">ให้คุณอุ่นใจได้นานขึ้น</span>
	</span>'''
	copy = '''<span style="font-family:Tahoma, Verdana, Sans-serif">
		<span style="white-space:nowrap;">สวัสดี คุณ <%InsertIf expression="${(user['FirstName'] == null || user['FirstName'] == '-')}" id="FirstName" %></span>
		<span style="white-space:nowrap;">ท่านลูกค้าฟอร์ด<%/InsertIf%> <%InsertElse%> <%${user['FirstName']}%> <%/InsertElse%></span>
	<br /><br /> 
 <span style=" white-space:nowrap;">รถ <%${user.CustomAttribute['Model']}%> ของคุณ</span>
 <span style=" white-space:nowrap;">ใกล้จะสิ้นสุดการรับประกันแล้ว<sup>1</sup></span><br> 
 <span style=" white-space:nowrap;">เราขอเสนอการดูแลแบบครบวงจร</span><br>
 <span style=" white-space:nowrap;">ที่พร้อมจะขยายเวลา</span>
 <span style=" white-space:nowrap;">รับประกันให้นานขึ้น</span><br><br>
								
 <span style=" white-space:nowrap;">ด้วยโปรแกรมขับขี่อุ่นใจ (PPP)</span>
 <span style=" white-space:nowrap;">จะช่วยเพิ่มความอบอุ่นใจ</span><br>
 <span style=" white-space:nowrap;">ในการขับขี่รถยนต์ให้คุณทุกเส้นทาง</span><br>
 <span style=" white-space:nowrap;">คุ้มครองความเสียหาย</span>
 <span style=" white-space:nowrap;">อันเกิดจากข้อบกพร่อง</span><br>
 <span style=" white-space:nowrap;">ทางกลไกและไฟฟ้าของรถยนต์</span> <br>
 <span style=" white-space:nowrap;">รับประกันรวมระยะเวลาสูงสุดถึง 5 ปี</span><br>
 <span style=" white-space:nowrap;">หรือรวมระยะทางสูงสุด 150,000 กิโลเมตร</span> <br>
 <span style=" white-space:nowrap;">ให้คุณมั่นใจได้เลย</span>ว่า<span style=" white-space:nowrap;">คุณจะได้รับอะไหล่แท้</span><br>	
 <span style=" white-space:nowrap;">ที่มีคุณภาพจากฟอร์ด</span><br>
 <span style=" white-space:nowrap;">ด้วยบริการจากช่างผู้ชำนาญ</span>
 <span style=" white-space:nowrap;">ที่ได้รับการฝึกอบรมจากฟอร์ด</span><br> 
 <span style=" white-space:nowrap;">ทั้งหมดนี้จะช่วยให้คุณ</span> 
 <span style=" white-space:nowrap;">สามารถประหยัดค่าใช้จ่าย</span><br>
 <span style=" white-space:nowrap;">ในการดูแลฟอร์ดของคุณในระยะยาว</span><br><br>
 <span style=" white-space:nowrap;">ยกระดับความอบอุ่นใจไปกับเรา</span>
 <span style=" white-space:nowrap;">ได้แล้ววันนี้</span></span>'''

	cta1_text = '''<span style="font-family:Tahoma, Verdana, Sans-serif">ดูข้อเสนอล่าสุดได้ที่นี่</span>'''
	cta1_url = '''https://www.ford.co.th/owner/premium-protection-plus/'''
	cta1_link_name = '''ppp'''
	cta2_text = '''<span style="font-family:Tahoma, Verdana, Sans-serif">ค้นหาตัวแทนจำหน่าย</span>'''
	cta2_url = '''https://www.ford.co.th/locate-a-dealer/'''
	cta2_link_name = '''find_dealer'''

[[module]] #Banner Image No Link
path = '''email_modules/image/banner_nolink'''
color = '''white'''

	image = '''th_edm2_whyfordsvc_20161115'''
	
	[[module]] #Split 04
path='email_modules/split/04'
color='green'

	title='''<span style="font-family:Tahoma, Verdana, Sans-serif">ข้อเสนอสุดพิเศษ</span>'''
	copy='''<span style="font-family:Tahoma, Verdana, Sans-serif;">
<span style="white-space:nowrap;">สมัครโปรแกรมขับขี่อุ่นใจ (PPP)</span>
<span style="white-space:nowrap;">รับส่วนลดเพิ่มสูงสุด 30% </span> 
<span style="white-space:nowrap;">หรือ 7,800 บาท </span>
<span style="white-space:nowrap;">พิเศษรับสิทธิ์</span>
<span style="white-space:nowrap;">ผ่อน 0% นาน 10 เดือน</span> 
<span style="white-space:nowrap;">เมื่อชำระผ่าน</span>
<span style="white-space:nowrap;">บัตรเครดิตกสิกรไทย</span> 
<span style="white-space:nowrap;">ตั้งแต่วันนี้ - วันที่ 31 สิงหาคม 2560</span></span>'''
	cta1_text='''<span style="font-family:Tahoma, Verdana, Sans-serif">คลิกเพื่อดูรายละเอียด ></span>'''
cta1_url='''https://www.ford.co.th/'''
cta1_icon='''more'''
cta1_link_name = '''PPP'''
image = '''th_edm5a_specialoffer_20160801'''


[[module]] #TH Social
path='email_modules/footer/th/social'
color='white'

[[module]] #Footer Disclaimer
path='email_modules/footer/disclaimer'
color='white'
text='''<span style="font-family:Tahoma, Verdana, Sans-serif">หมายเหตุ:<br />
<span style=" white-space:nowrap;">[1] คุณสามารถขยายการรับประกันด้วยโปรแกรม PPP นี้ </span>
<span style=" white-space:nowrap;">สำหรับรถที่มีอายุการใช้งานไม่เกิน 35 เดือน </span><br />
<span style=" white-space:nowrap;">หรือระยะทางไม่เกิน 100,000 กิโลเมตร </span>
<span style=" white-space:nowrap;">แล้วแต่อย่างใดอย่างหนึ่งจะถึงก่อน</span></span>'''

[[module]] #TH Online
path='email_modules/footer/th/online'
color='white'

+++