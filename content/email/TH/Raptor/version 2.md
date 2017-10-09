+++
markets = ["th"]
title = '''TH Ford Ranger Raptor stand alone version 2'''

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
	<span style=" white-space:nowrap;">จากข่าวลือที่คุณได้ยิน</span>
    <br />
    <span style=" white-space:nowrap;">มาเตรียมตัวให้พร้อมสำหรับการพุ่งทะยานของออฟโรด 4x4 พันธุ์แกร่ง</span> 
    <br />
    <span style=" white-space:nowrap;">เรนเจอร์</span>
    <br />
    <span style=" white-space:nowrap;">แร็พเตอร์รุ่นใหม่จะเปิดตัวสู่ความโลดโผนเร็วๆ นี้</span> 
    <br />
    <span style=" white-space:nowrap;">เรารู้ดีว่าคุณชื่นชอบใน<%${user.CustomAttribute['Model']}%>ของคุณ</span>
    <br />
    <span style=" white-space:nowrap;">แต่เราคิดว่าคุณน่าจะได้เห็นรถรุ่นนี้ก่อน</span>
    <br />
    <br />
    <span style=" white-space:nowrap;">ดังนั้น สูดหายใจให้ลึกๆ แล้วกดเพื่อรับชมรถกระบะ 4x4 ที่ทั่วโลกกำลังพูดถึง</span>
    '''
    
[[module]]
path='email_modules/spacer/default'
color='white'

	height="30"
    
[[module]]
path='email_modules/singles/ctablock'
color='''white'''

	cta1_text = '''ชมการทดสอบรถต้นแบบ'''
	cta1_url = '''https://www.ford.co.th/trucks/ranger/raptor/?intcmp=hp-none-brand-gallery#overlay/content/ford/th/th_th/ranger-content/video-overlays/raptor-videos/video1.html'''
	cta1_link_name = '''raptor'''

[[module]] #TH Social
path='email_modules/footer/th/social'
color='white'

[[module]] #TH Online
path='email_modules/footer/th/online'
color='white'

+++