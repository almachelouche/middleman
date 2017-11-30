+++
markets = ["th"]
title = '''TH Ford Ranger Raptor KMI All'''

[[module]]
path='email_modules/preheader'
color='''white'''

preheader = ''''''

[[module]] #Header Logo
path='email_modules/header/logo'
color='white'

	image = '''white'''
	url_link = '''https://www.ford.co.th/'''

[[module]] #Banner Image
path='email_modules/image/banner'
color='white'

	image = '''th_edm6_rangerkmi_20171130'''
		url_link=''''''
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
	เรียน <%InsertIf expression="${(user['FirstName'] == null || user['FirstName'] == '-')}" id="FirstName" %></span>
    '''

[[module]]
path='email_modules/singles/title'
color='''white'''

	title = '''
    <span style="font-family:Tahoma, Verdana, Sans-serif">    
	<span style=" white-space:nowrap;">เรนเจอร์ แร็พเตอร์การมาถึงของความยิ่งใหญ่ที่คุณรอคอ</span>
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
    <br />
    <span style=" white-space:nowrap;">ก็แน่ล่ะ เพราะนี่คือที่สุดของเครื่องยนต์ความเร็วสูงแห่งวงการออฟโรดที่ยอดเยี่ยมสุดๆ</span> 
    <br/>
    <br/>
    <span style=" white-space:nowrap;">คลิกลิ้งค์ด้านล่างเพื่อพิสูจน์ว่า สาวกกระบะ ทั่วภูมิภาคเอเชียเค้าพูดถึงรถคันนี้ว่าอย่างไรบ้าง</span>
    <br/>
    <span style=" white-space:nowrap;">และเตรียมพร้อมรับการคำรามของสุดยอดรถกระบะออฟโรดฟอร์ด</span> 
    <br/>
    <span style=" white-space:nowrap;">เรนเจอร์ แร็พเตอร์ ที่จะวางจำหน่าย</span> 
    <br/>
    <span style=" white-space:nowrap;">ในปี 2018 นี้</span>
    '''
    
[[module]]
path='email_modules/spacer/default'
color='white'

	height="30"
    
[[module]]
path='email_modules/singles/ctablock'
color='''white'''

	cta1_text = '''รับชมวิดีโอที่นี่'''
	cta1_url = ''''''
	cta1_link_name = '''ranger_kmi'''

[[module]] #TH Social
path='email_modules/footer/th/social'
color='white'

[[module]] #TH Online
path='email_modules/footer/th/online'
color='white'

+++