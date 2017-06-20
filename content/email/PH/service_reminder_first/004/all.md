+++
markets = ["ph"]
title = '''PH Service Reminder First 004 All'''

[[module]]
path='email_modules/preheader'

	preheader = '''Here’s a quick reminder that your new <%${user.CustomAttribute['Model']}%> is due for its first service.'''

[[module]] #Header Logo
path='email_modules/header/logo'
color='white'

	image = '''white'''
	url_link = '''https://www.ford.com.ph/'''

[[module]]
path='email_modules/cover/02'

color='''white'''
icon='''ph_edm2_svc_wrench_20160801'''
title='''Time files when you're having fun'''
copy='''Hello <%${user['FirstName']}%><br /><br />Here’s a quick reminder that your new <%${user.CustomAttribute['Model']}%> is due for its first service. Our expert engineers will ensure it is running at its absolute best.<br /><br />When you book your first service appointment, you’ll receive a free 30-point inspection and a Vehicle Report Card that helps you track your Ford’s health status. 
<br /><br />It's important to book your service today. Just click below to contact <%${user.CustomAttribute['Dealer_Name']}%> (during business hours) or to find your nearest dealer.'''
cta1_text='''CALL <%${user.CustomAttribute['Work_Phone']}%>'''
cta1_url='''tel:<%${user.CustomAttribute['Home_Phone']}%>'''
cta2_text='''FIND A DEALER'''
cta2_url='''https://www.ford.com.ph/locate-a-dealer/'''
cta2_link_name='''find_dealer'''

[[module]] #Banner Image No Link
path = '''email_modules/image/banner_nolink'''
color = '''white'''

	image = '''ph_edm2a_tirechange_20160801'''

[[module]] #Split 02
path='email_modules/split/02'
color='green'

	title = '''Worry-free servicing'''
	copy = '''Keep your Ford running at its best, with our Scheduled Service Plan.<ul style="margin: 20px; padding: 0;"><li>Professional maintenance for up to five years</li><li>Protection against price increases on parts and labor</li><li>Service plans are fully transferrable</li></ul>'''
	cta1_text = '''LEARN MORE'''
	cta1_url = '''https://www.ford.com.ph/owner/service-schedule-plan/'''
	cta1_link_name = '''ssp'''
	cta1_icon = '''more'''
	image = '''ph_edm1_svcplan_20160801'''

[[module]] #Cover 05
path='email_modules/cover/02'
color='''fordblue'''

	title = '''We are there for you, anytime'''
	copy = '''Ford Emergency Roadside Assistance is on-call 24/7, and free of charge in your first year of ownership. So whenever you need a hand, <br />just give us a call at (02) 459-4723'''
	cta1_text = '''FIND OUT MORE'''
	cta1_url = '''https://www.ford.com.ph/owner/road-assistance/'''
	cta1_link_name = '''roadside_assistance'''
	icon = '''ph_edm1_roadsideassist_20160801'''

[[module]] #Cover 05
path='email_modules/cover/02'
color='''slatescreen'''

	title = '''Premium Extended Warranty'''
	copy = '''With quality service and genuine parts, a Premium Extended Warranty is the best choice for owners, like you, who want to go the distance with their vehicle. <br /><br />Warranties are available for up to 5 years, and save you money on servicing. They may also be fully transferrable to the next vehicle owner, helping improve re-sale value.'''
	cta1_text = '''GET COVERED'''
	cta1_url = '''https://www.ford.com.ph/owner/warranties/'''
	cta1_link_name = '''extended_warranty'''
	icon = '''ph_edm_extendedwarranty_20160801'''

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