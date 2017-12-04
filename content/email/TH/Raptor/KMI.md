+++
markets = ["th"]
title = '''TH Ford Ranger Raptor KMI All'''

[[module]]
path='email_modules/preheader'
color='''white'''

preheader = '''สุดยอดยนตรกรรมแห่งวงการกระบะออฟโรดฟอร์ด เรนเจอร์ แร็พเตอร์'''

[[module]] #Header Logo
path='email_modules/header/logo'
color='white'

	image = '''white'''
	url_link = '''https://www.ford.co.th/'''

[[module]] #Banner Image
path='email_modules/image/banner'
color='white'

	image = '''th_edm6_rangerkmi_20171201'''
		url_link='''https://youtu.be/iiImuy6F0fs'''
	url_link_name='''ranger_kmi'''

[[module]]
path='email_modules/spacer/default'
color='white'

	height="30"

[[module]]
path='email_modules/singles/copy'
color='''white'''

	copy = '''
    <span style="font-family:Tahoma, Verdana, Sans-serif">
	เรียน คุณ <%InsertIf expression="${(user['FirstName'] == null || user['FirstName'] == '-')}" id="FirstName" %></span>
    '''

[[module]]
path='email_modules/singles/title'
color='''white'''

	title = '''
    <span style="font-family:Tahoma, Verdana, Sans-serif">    
	<span style=" white-space:nowrap;">เรนเจอร์ แร็พเตอร์</span>
    <br/>
    <span style=" white-space:nowrap;">การมาถึงของความยิ่งใหญ่ที่คุณรอคอย</span>
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
	<span style=" white-space:nowrap;">ตั้งแต่เราเปิดตัว เรนเจอร์ แร็พเตอร์ ทั้งโลกก็จับตามอง!  ทุกคนก็ต่างพูดถึง!</span>
    <br/>
    <span style=" white-space:nowrap;">ก็แน่ล่ะ เพราะนี่คือที่สุดของเครื่องยนต์ความเร็วสูง</span>
    <br/>
    <span style=" white-space:nowrap;">แห่งวงการออฟโรดที่ยอดเยี่ยมสุดๆ</span> 
    <br/>
    <br/>
    <span style=" white-space:nowrap;">คลิกลิ้งค์ด้านล่างเพื่อพิสูจน์ว่า</span> 
    <br/>
    <span style=" white-space:nowrap;">สาวกกระบะ ทั่วภูมิภาคเอเชียเค้าพูดถึงรถคันนี้ว่าอย่างไรบ้าง</span>
    <br/>
    <span style=" white-space:nowrap;">และเตรียมพร้อมรับการคำรามของสุดยอดรถกระบะออฟโรด</span> 
    <br/>
    <span style=" white-space:nowrap;">ฟอร์ด เรนเจอร์ แร็พเตอร์ ที่จะวางจำหน่าย ในปี 2018 นี้</span> 
    '''
    
[[module]]
path='email_modules/spacer/default'
color='white'

	height="30"
    
[[module]]
path='email_modules/singles/ctablock'
color='''white'''

	cta1_text = '''รับชมวิดีโอที่นี่'''
	cta1_url = '''https://youtu.be/iiImuy6F0fs'''
	cta1_link_name = '''ranger_kmi'''

[[module]] #TH Social
path='email_modules/footer/th/social'
color='white'

[[module]] #TH Online
path='email_modules/footer/th/online'
color='white'

+++