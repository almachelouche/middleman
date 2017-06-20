+++
markets = ["ph"]
title = 'PH Service Reminder Seasonal 002 All'

[[module]]
path='email_modules/preheader'
color='''white'''

preheader = '''Find out why a Ford dealership is the best place to replace your tires.'''

[[module]] #Header Logo
path='email_modules/header/logo'
color='white'

	image = '''white'''
	url_link = '''https://www.ford.com.ph/'''

[[module]] #Banner Image No Link
path = '''email_modules/image/banner_nolink'''
color = '''white'''

	image = '''ph_edm2b_tirepromotion_20161221'''

[[module]] #Cover 07
path='email_modules/cover/02'
color='''white'''

	title = '''The smart way to replace tires'''
	copy = '''Hello <%${user['FirstName']}%><br /><br />When you need high-quality tires, look no further than your local Ford dealer. Our expert technicians know your Ford better than anyone, and will help you find the perfect fit for your vehicle.<br /><br />-	Wide selection of tires<br />-	Expert advice<br />-	Worry-free warranties<br /><br />Visit us today to keep your Ford in top condition.'''
	cta1_text = '''FIND OUT MORE'''
	cta1_url = '''https://www.ford.com.ph/owner/service/'''
	cta1_link_name = '''tire_promotion'''


[[module]] #Custom 01
path='email_modules/custom/3columntitle3icons'
color='white'

	title = '''Why Ford servicing?'''
	icon1 = '''ph_edm2_fordsvc_a_20160801'''
	text1 = '''Your custom designed service plan keeps your vehicle performing at its best.'''
	icon2 = '''ph_edm2_fordsvc_b_20160801'''
	text2 = '''Ford service centre equipment is built and calibrated specifically for your vehicle.'''
	icon3 = '''ph_edm2_fordsvc_c_20160801'''
	text3 = '''A record of regular servicing improves your vehicle's re-sale value.'''

[[module]] #Banner Image No Link
path = '''email_modules/image/banner_nolink'''
color = '''white'''

	image = '''ph_edm2a_tirechange_20160801'''

[[module]] #Dual 01
path='email_modules/dual/01'
color='white'

	icon1 = '''ph_edm2_call_20160801'''
	title1 = '''Book it now!'''
	copy1 = '''Call <%${user.CustomAttribute['Dealer_Name']}%> at <a style="color:#2D96CD" href="tel:<%${user.CustomAttribute['Home_Phone']}%>"><%${user.CustomAttribute['Work_Phone']}%></a><br /> or <br /> <a name="find_dealer" style="color:#2D96CD" href="https://www.ford.com.ph/locate-a-dealer/">Find your nearest Ford Dealer</a>'''
	icon2 = '''ph_edm2_ownerprofile_20160801'''
	title2 = '''Anything changed? '''
	copy2 = '''Update your details now so you are always up-to-date on our latest offers.'''
	cta1_text = ''''''
	cta1_url = ''''''
	cta1_link_name = ''''''
	cta2_text = '''UPDATE NOW'''
	cta2_url = '''https://www.ford.com.ph/owner/owner-unauthenticated/#overlay/content/ford/ph/en_ph/site-wide-content/overlays/form-overlay/login'''
	cta2_link_name = '''anything_changed'''

[[module]] #PH Social
path = 'email_modules/footer/ph/social'
color = 'white'

[[module]] #PH Online
path = 'email_modules/footer/ph/online'
color = 'white'
+++