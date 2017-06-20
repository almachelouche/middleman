+++
markets = ["th"]
title = '''TH Extended Warranty 001 Non-Urgent'''
draft = true

[[module]]
path='email_modules/preheader'
color='''nothing'''

	preheader = '''ขยายการรับประกันเพื่อยืดระยะเวลาการบำรุงรักษารถฟอร์ดของคุณให้นานขึ้น'''

[[module]] #Header Logo
path='email_modules/header/logo'
color='white'

	image = '''white'''
	url_link = '''https://www.ford.co.th/'''

[[module]] #Cover 06
path='email_modules/cover/02'
color = '''white'''

	icon = '''th_edm3_extendedwarranty_20160801'''
	title = '''<span style="font-family:Tahoma, Verdana, Sans-serif">ยืดระยะเวลา ให้คุณอุ่นใจได้นานขึ้น</span>'''
	copy = '''<span style="font-family:Tahoma, Verdana, Sans-serif"><span style=" white-space:nowrap;">สวัสดี คุณ <%InsertIf expression="${(user['FirstName'] == null || user['FirstName'] == '-')}" id="FirstName" %>ท่านลูกค้าฟอร์ด<%/InsertIf%> <%InsertElse%> <%${user['FirstName']}%> <%/InsertElse%></span>
<table cellpadding="0" cellspacing="0" height="20" style="line-height:20px"><tr><td>&nbsp;</td></tr></table>
<span style=" white-space:nowrap;">รถ <%${user.CustomAttribute['Model']}%> ของคุณ</span><br />
<span style=" white-space:nowrap;">ใกล้จะสิ้นสุดระยะเวลาการรับประกันแล้ว<sup>1</sup></span><br />
<span style=" white-space:nowrap;">และเพื่อเป็นการดูแลรถฟอร์ดของคุณอย่างต่อเนื่อง</span><br />
<span style=" white-space:nowrap;">เราขอเสนอการดูแลแบบครบวงจร</span>
<span style=" white-space:nowrap;">ด้วยโปรแกรมขับขี่อุ่นใจ (PPP)</span> <br />
<span style=" white-space:nowrap;">ที่พร้อมจะขยายเวลารับประกันให้นานขึ้น</span>
<table cellpadding="0" cellspacing="0" height="20" style="line-height:20px"><tr><td>&nbsp;</td></tr></table>
<span style=" white-space:nowrap;"><strong>โปรแกรมขับขี่อุ่นใจ (PPP)</strong></span> 
<span style=" white-space:nowrap;">ออกแบบมาเพื่อดูแลรถของคุณ</span><br />
<span style=" white-space:nowrap;">ด้วยการรับประกันรวมระยะเวลาสูงสุดถึง 5 ปี</span><br /> 
<span style=" white-space:nowrap;">หรือ รวมระยะทางสูงสุด 150,000 กิโลเมตร</span><br />
<span style=" white-space:nowrap;">คุ้มครองความเสียหาย</span>อันเกิด<span style=" white-space:nowrap;">จากข้อบกพร่องทางกลไก</span><br /> 
<span style=" white-space:nowrap;">และไฟฟ้าของรถยนต์</span>
<span style=" white-space:nowrap;">โดยช่างผู้ชำนาญที่ได้รับการฝึกอบรมจากฟอร์ด</span> <br />
<span style=" white-space:nowrap;">ให้คุณมั่นใจกับฟอร์ดคันเดิม</span> 
<span style=" white-space:nowrap;">พร้อมเพิ่มมูลค่าให้รถของคุณ</span>
<table cellpadding="0" cellspacing="0" height="20" style="line-height:20px"><tr><td>&nbsp;</td></tr></table>
<span style=" white-space:nowrap;">ยกระดับความอบอุ่นใจไปกับเรา</span> <span style=" white-space:nowrap;">ได้แล้ววันนี้</span></span>'''

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