+++
markets = ["th"]
title = '''TH Sweet Spot 010 All'''
draft = true

[[module]]
path='email_modules/preheader'
color='''nothing'''

	preheader = '''พบส่วนลดมากมาย เพียงนัดหมายเช็คสภาพรถกับฟอร์ด'''

[[module]] #Header Logo
path='email_modules/header/logo'
color='white'

	image = '''white'''
	url_link = '''https://www.ford.co.th/'''

[[module]] #Cover 08
path='email_modules/cover/02'
color = '''white'''

	title = '''Time for a change'''
	copy = '''We noticed that you may be driving your Ranger with old, worn-out parts. That’s got us worried.<br /><br />
Book a service appointment today and our Ford experts will replace your old battery, tires, brakes, or wiper blades. Together, let’s keep your Ford running at its absolute best. <br /><br />Just click below to contact <%${user.CustomAttribute['Dealer_Name']}%> (during business hours) or to find your nearest dealer.
'''

cta1_text='''<span style="font-family:Tahoma, Verdana, Sans-serif">Call <%${user.CustomAttribute['Dealer_Phone']}%></span>'''
cta1_url='''tel:<%${user.CustomAttribute['Dealer_Phone']}%>'''
cta2_text='''<span style="font-family:Tahoma, Verdana, Sans-serif">FIND A DEALER</span>'''
cta2_url='''https://www.ford.co.th/locate-a-dealer/'''
cta2_url_link_name='''find_dealer'''

[[module]] #Banner Image No Link
path = '''email_modules/image/banner_nolink'''
color = '''white'''

	image = '''th_edm2_whyfordsvc_20161115'''


	[[module]] #Split 04
path='email_modules/split/04'
color='green'

	title='''Big discounts on Ford genuine parts'''
	copy='''Enjoy big discounts on brakes, batteries and wiper blades. And when you buy three tyres, the fourth tyre will be free. Offer ends <span style="color:#FFF">December 31</span>.'''
	cta1_text='''CLICK NOW'''
cta1_url='''https://www.ford.co.th/serviceq-3-2016/'''
cta1_icon='''more'''
cta1_link_name = '''commodity_offer'''
image = '''th_edm2d_savebigonoil25_20160801'''


[[module]] #TH Social
path='email_modules/footer/th/social'
color='white'


[[module]] #TH Online
path='email_modules/footer/th/online'
color='white'

+++