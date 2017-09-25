+++
markets = ["th"]
title = '''TH Ford Ranger Raptor test'''

[[module]]
path='email_modules/preheader'
color='''white'''

preheader = '''Get ready for a wild ride.'''

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
path='email_modules/singles/copy'
color='''white'''

	copy = '''<span style="font-family:Tahoma, Verdana, Sans-serif">เรียน<%${user['FirstName']}%></span>'''

[[module]]
path='email_modules/spacer/default'
color='white'

	height="30"
    
[[module]]
path='email_modules/singles/title'
color='''white'''

	title = '''
    <span style="font-family:Tahoma, Verdana, Sans-serif">
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
	<span style=" white-space:nowrap;">โลกของการขับออฟโรดกำลังจะหฤโหดขึ้นอีกเล็กน้อย</span>
    <br />
    <span style=" white-space:nowrap;">เรนเจอร์ แร็พเตอร์ กระบะออฟโรดประสิทธิภาพแกร่งใกล้จะพร้อมเปิดตัวแล้ว</span>
    <br />
    <span style=" white-space:nowrap;">เรารู้ดีว่าคุณชื่นชอบใน <%${user.CustomAttribute['Model']}%> ของคุณ แต่เราคิดว่าคุณน่าจะได้เห็นรถรุ่นนี้ก่อน</span>
    <br />
    <br />
    <span style=" white-space:nowrap;">คลิกที่ลิงก์ด้านล่างเพื่อรับชมการทดสอบรถต้นแบบ</span>
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