+++
markets = ["th"]
title = '''TH Ford Ranger Raptor stand alone version 1'''

[[module]]
path='email_modules/preheader'
color='''white'''

preheader = '''คุณพร้อมสำหรับออฟโรดพันธุ์แกร่งหรือยัง'''

[[module]] #Header Logo
path='email_modules/header/logo'
color='white'

	image = '''white'''
	url_link = '''https://www.ford.co.th/'''

[[module]] #Banner Image
path='email_modules/image/banner'
color='white'

	image = '''AU_edm6_raptor_20170920'''
		url_link='''https://www.ford.co.th/trucks/ranger/raptor/?intcmp=hp-none-brand-gallery#overlay/content/ford/th/th_th/ranger-content/video-overlays/raptor-videos/video1.html'''
	url_link_name='''raptor'''

[[module]]
path='email_modules/spacer/default'
color='white'

	height="30"
    
[[module]]
path='email_modules/singles/title'
color='''white'''

	title = '''
    <span style="font-family:Tahoma, Verdana, Sans-serif"><strong>สวัสดีค่ะ คุณ <%InsertIf expression="${(user['FirstName'] == null || user['FirstName'] == '-')}" id="FirstName" %>    
	<span style=" white-space:nowrap;">คุณพร้อมสำหรับออฟโรดพันธุ์แกร่งหรือยัง</span>
    '''

[[module]]
path='email_modules/spacer/default'
color='white'

	height="30"

[[module]]
path='email_modules/singles/copy'
color='''white'''

	copy = '''
    <span style="font-family:Tahoma, Verdana, Sans-serif">
	<span style=" white-space:nowrap;">โลกของการขับออฟโรดกำลังจะหฤโหดขึ้นอีก</span>
    <br />
    <span style=" white-space:nowrap;">“ฟอร์ด เรนเจอร์ แร็พเตอร์” กระบะออฟโรดสมรรถนะสูง</span> 
    <br />
    <span style=" white-space:nowrap;">จะเปิดตัวในภูมิภาคเอเชีย แปซิฟิกในปี 2561 นี้</span>
    <br />
    <span style=" white-space:nowrap;">เพื่อขอบคุณที่ท่านร่วมเป็นส่วนหนึ่งของครอบครัว ฟอร์ด เสมอมา</span> 
    <br />
    <span style=" white-space:nowrap;">เราจึงส่งมอบข่าวสารอัพเดทแบบเอ็กซ์คลูซีฟ</span>
    <br />
    <span style=" white-space:nowrap;">เกี่ยวกับฟอร์ด เรนเจอร์ แร็พเตอร์ ให้กับคุณก่อนใคร</span>
    <br />
    <br />
    <span style=" white-space:nowrap;">คลิกที่ลิงก์ด้านล่างเพื่อชมวีดีโอการทดสอบความสามารถในการขับขี่</span>
    <br />
    <span style=" white-space:nowrap;">แบบออฟโรดด้วยความเร็วสูงของรถต้นแบบ ฟอร์ด เรนเจอร์ แร็พเตอร์</span>
    '''
    
[[module]]
path='email_modules/spacer/default'
color='white'

	height="30"
    
[[module]]
path='email_modules/singles/ctablock'
color='''white'''

	cta1_text = '''<span style="font-family:Tahoma, Verdana, Sans-serif">ชมการทดสอบรถต้นแบบ</span>'''
	cta1_url = '''https://www.ford.co.th/trucks/ranger/raptor/?intcmp=hp-none-brand-gallery#overlay/content/ford/th/th_th/ranger-content/video-overlays/raptor-videos/video1.html'''
	cta1_link_name = '''raptor'''

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