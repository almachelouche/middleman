+++
markets = ["th"]
title = '''TH Anniversary DH_Test MailMerge-Tina'''

[[module]]
path='email_modules/preheader'

	preheader = '''คุณคงไม่อยากเชื่อใช่ไหมว่าคุณขับรถฟอร์ด Ranger <%${user.CustomAttribute['Model']}%> คันใหม่ของคุณมาครบ 1 ปีแล้ว ฟอร์ดอยากใช้โอกาสพิเศษนี้ กล่าวคำขอบคุณอีกครั้ง ที่คุณไว้วางใจ เลือกใช้รถยนต์ฟอร์ด สำหรับลูกค้าคนสำคัญเช่นคุณ ฟอร์ดจะแจ้งข่าวสาร'''

[[module]] #Header Logo
path = 'email_modules/header/logo'
color = 'white'

	image = '''white'''
	url_link = '''https://www.ford.co.th/'''

[[module]] #Cover 01
path='email_modules/cover/01'
color='''white'''
 
	title = '''<span style="font-family:Tahoma, Verdana, Sans-serif"><strong>ครบรอบ 1 ปีกับรถฟอร์ดคู่ใจของคุณ<span style=" white-space:nowrap;"></span></strong></span>'''
	copy = '''<span style="font-family:Tahoma, Verdana, Sans-serif">สวัสดี -test คุณ <%InsertIf expression="${(user['FirstName'] == null || user['FirstName'] == '-')}" id="FirstName" %>ท่านลูกค้าฟอร์ด<%/InsertIf%> <%InsertElse%> <%${user['FirstName']}%> <%/InsertElse%><br /><br />
    
    <span style=" white-space:nowrap;"> คุณคงไม่อยากเชื่อใช่ไหมว่าคุณขับรถฟอร์ด Ranger <%${user.CustomAttribute['Model']}%> คันใหม่ของคุณมาครบ1 ปีแล้ว</span><br />
    <span style=" white-space:nowrap;">ฟอร์ดอยากใช้อกาสพิเศษนี้กล่าวคำขอบคุณอีกครั้งที่คุณไว้วางใจเลือกใช้รถยนต์</span><br />
    <span style=" white-space:nowrap;">ฟอร์ดสำหรับลูกค้าคนสำคัญเช่นคุณฟอร์ดจะแจ้งข่าวสารข้อเสนอพิเศษ</span><br />
    <span style=" white-space:nowrap;">และข้อมูลที่เป็นประโยชน์เพื่อให้คุณได้รับทราบอย่างต่อเนื่องก่อนใคร</span></span>'''

[[module]] #Banner Image No Link DHTest
	path = '''email_modules/image/banner_nolink_DHTest'''
	color = '''white'''

	image_code = '''<%InsertIf expression="${(user.CustomAttribute['Model'] == 'Ford Ranger')}" id="Ranger" %>
<img class="img_R" align="left" src="https://s3-ap-southeast-1.amazonaws.com/edm-images/covers/th_edm1&4_np_ranger_20160801_desktop.jpg"alt="Image Banner" title="Image Banner" border="0" style="display:block;margin:0;"/>
<%/InsertIf%> 
		
<%InsertElse expression="${(user.CustomAttribute['Model'] == 'Ford Focus')}" id="Focus" %>
<img class="img_R" align="left" src="https://s3-ap-southeast-1.amazonaws.com/edm-images/covers/th_edm1&4_np_focus_20160801_desktop.jpg"alt="Image Banner" title="Image Banner" border="0" style="display:block;margin:0;"/>
<%/InsertElse%>
		
<%InsertElse%> 
<img class="img_R" align="left" src="https://s3-ap-southeast-1.amazonaws.com/edm-images/covers/no_img_desktop.jpg"alt="Image Banner" title="Image Banner" border="0" style="display:block;margin:0;"/>
<%/InsertElse%>'''


	[[module]] #Cover 05
path='email_modules/cover/02'
color='''white'''

	title = '''<span style="font-family:Tahoma, Verdana, Sans-serif">
	<span style=" white-space:nowrap;">ข้อมูลของคุณมีการ<br />
	<span style=" white-space:nowrap;">เปลี่ยนแปลงหรือไม่</span></span>'''

	copy = '''<span style="font-family:Tahoma, Verdana, Sans-serif">
	<span style=" white-space:nowrap;">กรุณาอัพเดทข้อมูลของคุณ</span>
	<span style=" white-space:nowrap;">เพื่อให้คุณไม่พลาด</span><br />
	<span style=" white-space:nowrap;">ข้อเสนอพิเศษต่างๆ</span>
	<span style=" white-space:nowrap;">จากฟอร์ด</span></span>'''

	cta1_text = '''<span style="font-family:Tahoma, Verdana, Sans-serif">อัพเดทข้อมูล</span>'''
	cta1_url = '''https://www.ford.co.th/#/overlay/content/ford/th/th_th/site-wide-content/overlays/form-overlay/login/'''
	cta1_link_name = '''anything_changed'''
	icon = '''th_edm2_ownerprofile_20160801'''



[[module]] #TH Social
path='email_modules/footer/th/social'
color='white'

[[module]] #TH Online
path='email_modules/footer/th/online'
color='white'

+++