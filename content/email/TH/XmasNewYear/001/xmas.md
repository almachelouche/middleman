+++
markets = ["th"]
title = '''TH New Year-Xmas Greeting 001'''

[[module]]
path='email_modules/preheader'


		preheader = '''ฟอร์ดขอร่วมส่งท้ายปีเก่า ส่งความสุขต้อนรับปีใหม่ 2560 ในช่วงเวลาของความรื่นเริงแห่งปี ฟอร์ดขอมอบคำอวยพรจากใจให้คุณและครอบครัวมีความสุข สุขภาพแข็งแรงในเทศกาลคริสมาสต์และตลอดปีใหม่ที่จะมาถึงนี้ '''

[[module]] #Header Logo
path='email_modules/header/logo'
color='white'

	image = '''white'''
	url_link = '''https://www.ford.co.th/'''

[[module]] #Banner Image No Link
path = '''email_modules/image/banner_nolink'''
color = '''white'''

	image = '''th_edm6_xmas_banner_20161212'''

[[module]] #Cover 11
path='email_modules/cover/03'
color='''white'''

	copy='''<span style="font-family:Tahoma, Verdana, Sans-serif"><br /><br />สวัสดีค่ะ คุณ <%InsertIf expression="${(user['FirstName'] == null || user['FirstName'] == '-')}" id="FirstName" %>ท่านลูกค้าฟอร์ด<%/InsertIf%> <%InsertElse%> <%${user['FirstName']}%> <%/InsertElse%><br /><br /></span>
<span style="font-family:Tahoma, Verdana, Sans-serif">
	<span style="white-space:nowrap;">ในช่วงเวลาของความรื่นเริงแห่งปี</span>
	<span style="white-space:nowrap;">ฟอร์ดขอมอบคำอวยพรจากใจ</span><br />
	<span style="white-space:nowrap;">ให้คุณและครอบครัวมีความสุข</span> 
	<span style="white-space:nowrap;">สุขภาพแข็งแรงในเทศกาลคริสต์มาส</span><br />
	<span style="white-space:nowrap;">และตลอดปีใหม่ที่จะมาถึงนี้</span><br /><br />
	<span style="white-space:nowrap;">ฟอร์ดมุ่งมั่นมอบประสบการณ์</span>แห่ง<span style="white-space:nowrap;">การขับขี่ที่ดี</span><br />
	<span style="white-space:nowrap;">เพื่อการเดินทางสุดประทับใจ</span>
	<span style="white-space:nowrap;">ให้กับคุณมาอย่างยาวนาน </span><br />
	<span style="white-space:nowrap;">และหวังเป็นอย่างยิ่งว่า</span>
		<span style="white-space:nowrap;">เราจะได้ร่วมเดินทาง</span><br />
	<span style="white-space:nowrap;">และสร้างความทรงจำดีๆต่อไป</span>
	<span style="white-space:nowrap;">ด้วยกันในอนาคตอันใกล้</span><br /><br />
	<span style="white-space:nowrap;">เราสัญญาว่าจะอยู่เคียงข้างคุณ</span>ใน<span style="white-space:nowrap;">ทุกเส้นทาง</span><br />
	<span style="white-space:nowrap;">เช่นเดียวกับที่คุณ</span>อยู่<span style="white-space:nowrap;">เคียงข้างฟอร์ดเสมอมา</span>
</span></span>'''

[[module]] #TH Social
path='email_modules/footer/th/social'
color='white'

[[module]] #TH Online
path='email_modules/footer/th/online'
color='white'

+++