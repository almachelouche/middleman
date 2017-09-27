+++
markets = ["th"]
title = '''TH Service Campaign test'''

[[module]]
path='email_modules/preheader'


	preheader = '''พร้อมส่วนลดพิเศษอีกมากมาย ณ ศูนย์บริการฟอร์ด'''

[[module]] #Header Logo
path='email_modules/header/logo'
color='white'

	image = '''white'''
	url_link = '''https://www.ford.co.th/'''

[[module]]
path='email_modules/cover/02'

color='''white'''
title='''<span style="font-family:Tahoma, Verdana, Sans-serif">
						<span style="white-space:nowrap;">ฟอร์ดยกทีม</span>
						'''
copy='''
<span style="font-family:Tahoma, Verdana, Sans-serif">
						<span style="white-space:nowrap;">นำทีมโดยทีมช่างคุณภาพของฟอร์ดที่ช่วยดูแลรถของคุณ</span>
                        <br />
						<span style="white-space:nowrap;">พร้อมทีมสนับสนุนที่มาพร้อมส่วนลดพิเศษอีกมากมาย</span> 
                        <br />
						<span style="white-space:nowrap;">พบกับทีมฟอร์ดได้ที่ศูนย์บริการฟอร์ดทั่วประเทศ</span> 
                        <br />
						<span style="white-space:nowrap;">ตั้งแต่ 1 ตุลาคม – 31 ธันวาคม 2560 นี้เท่านั้น</span>
                        '''
cta1_text='''<span style="font-family:Tahoma, Verdana, Sans-serif">เรียนรู้เพิ่มเติม</span>'''
cta1_url='''https://www.ford.co.th/owner/servicecampaign/'''
cta1_link_name = '''learn_more'''

[[module]] #Banner Image
path='email_modules/image/banner'
color='white'

	image='''th_edm6_servicecampaign_20170925'''
	url_link='''https://www.ford.co.th/owner/servicecampaign/'''
	url_link_name='''service_campaign'''

[[module]]
path='email_modules/dual/03'
color='white'

title1='''<span style="font-family:Tahoma, Verdana, Sans-serif">นัดหมายเข้ารับบริการ</span>'''
	cta1a_text='''<span style="font-family:Tahoma, Verdana, Sans-serif">ติดต่อ <%${user.CustomAttribute['Dealer_Name']}%><br />ได้ที่ <% ${user.CustomAttribute['Dealer_Phone']} %></span>'''
	cta1a_url='''tel:<%${user.CustomAttribute['Dealer_Phone']}%>'''
	cta1_link_name = ''''''
	cta1b_text='''<span style="font-family:Tahoma, Verdana, Sans-serif">ค้นหาตัวแทนจำหน่ายใกล้บ้าน<br />คุณ</span>'''
	cta1b_url='''https://www.ford.co.th/locate-a-dealer/'''
	cta1b_link_name = '''find_dealer'''
	icon1='''th_edm2_call_20160801'''

	title2='''<span style="font-family:Tahoma, Verdana, Sans-serif">ศูนย์ข้อมูลเจ้าของรถ</span>'''
	copy2='''<span style="font-family:Tahoma, Verdana, Sans-serif"><span style="color:#616161; font-size:16px">ทุกความช่วยเหลือที่คุณต้องการง่ายๆ</span><br /> 
<span style="color:#616161; font-size:16px">ในที่เดียว</span> 
<span style="white-space:nowrap; color:#616161; font-size:16px"> สำหรับเจ้าของรถฟอร์ดเท่านั้น</span></span>'''
cta2a_text='''<span style="font-family:Tahoma, Verdana, Sans-serif">วิดีโอสาธิตวิธีการใช้งาน<br />คุณสมบัติต่างๆ</span>'''
	cta2a_url='''https://www.ford.co.th/owner/owner-unauthenticated/'''
	cta2a_link_name = '''owner_center'''
	cta2b_text='''<span style="font-family:Tahoma, Verdana, Sans-serif">ผลิตภัณฑ์และบริการของฟอร์ด</span>'''
	cta2b_url='''https://www.ford.co.th/owner/owner-unauthenticated/'''
	cta2b_link_name = '''owner_center'''
	icon2='''th_edm2_ownerprofile_20160801'''

[[module]] #TH Social
path='email_modules/footer/th/social'
color='white'

[[module]] #TH Online
path='email_modules/footer/th/online'
color='white'
+++