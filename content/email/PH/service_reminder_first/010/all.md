+++
markets = ["ph"]
title = '''PH Service Reminder First 010 All'''

preheader = '''Your Ford Vehicle must be nearly ready for its 10,000km service.'''

[[module]] #Header Logo
path='email_modules/header/logo'
color='white'

	image = '''white'''
	url_link = '''http://www.ford.com.ph/'''

[[module]] #Cover 06
path='email_modules/cover/02'
color='''white'''

	title = '''Time flies when you're having fun'''
	copy = '''Hello <%${user['FirstName']}%><br /><br />Your Ford <%${user.CustomAttribute['Model']}%> must be nearly ready for its 10,000km service. This is the first service of the lifetime maintenance plan for your Ford <%${user.CustomAttribute['Model']}%>, designed to ensure that it always operates at its optimum.<br /><br />And while you're there, don't forget to pick up a weathershield, so you can enjoy fresh air anytime - even in a downpour.<br /><br />It's easy to book. Simple call <%${user.CustomAttribute['Dealer_Name']}%> at<br /><br /><%${user.CustomAttribute['Work_Phone']}%><br /><br />Or click below to find a dealer nearby'''
	cta1_text = '''CALL <%${user.CustomAttribute['Work_Phone']}%>'''
	cta1_url = '''tel:<%${user.CustomAttribute['Work_Phone']}%>'''
	cta1_link_name = '''link_name_here'''
	cta2_text = '''FIND A DEALER'''
	cta2_url = '''http://www.ford.com.ph/locate-a-dealer/'''
	cta2_link_name = '''find_dealer'''
	icon = '''ph_edm2_svc_wrench_20160801'''

[[module]] #Banner Image No Link
path = '''email_modules/image/banner_nolink'''
color = '''white'''

	image = '''ph_edm2a_tirechange_20160801'''

[[module]] #Cover 05
path='email_modules/cover/02'
color='''fordblue'''

	title = '''We're there for you, anytime'''
	copy = '''It's good to know that when you drive your Ford, we're ready to help when you need it. Our Emergency Roadside Assistance is on-call, 24 hours a day, 7 days a week, and free of charge, in yousership. Call us whenever you need a hand if you run out of fuel, have a flat tyre, need help with a vehicle emergency and more. Just remember this number:<br />(02) 459-4723'''
	cta1_text = '''FIND OUT MORE'''
	cta1_url = '''http://www.ford.com.ph/buying/assistance'''
	cta1_link_name = '''roadside_assistance'''
	icon = '''ph_edm1_roadsideassist_20160801'''

[[module]] #Cover 05
path='email_modules/cover/02'
color='''slatescreen'''

	title = '''Premium Extended Warranty'''
	copy = '''With quality service and genuine parts, a Premium Extended Warranty is the best choice for owners, like you, who want to go the distance with their vehicle. <br /><br />Warranties are available for up to 5 years, and save you money on servicing. They may also be fully transferrable to the next vehicle owner, helping improve re-sale value.'''
	cta1_text = '''GET COVERED'''
	cta1_url = '''http://www.ford.com.ph/buying/warranty'''
	cta1_link_name = '''extended_warranty'''
	icon = '''ph_edm_extendedwarranty_20160801'''

[[module]] #Split 02
path='email_modules/split/02'
color='green'

	title = '''Worry-free servicing'''
	copy = '''Keep your Ford running at its best, with our Scheduled Service Plan.<br /><br /> • 	Professional maintenance for up to five years<br />• 	Protection against price rises on parts and labor<br />• 	Service plans are customizable '''
	cta1_text = '''LEARN MORE'''
	cta1_url = '''http://www.ford.com.ph/buying/scheduledserviceplan'''
	cta1_link_name = '''ssp'''
	cta1_icon = '''more'''
	image = '''ph_edm1_svcplan_20160801'''

[[module]] #Dual 02
path='email_modules/dual/02'
color='white'

	icon1 = '''ph_edm2_call_20160801'''
	title1 = '''Book it now'''
	cta1_text = '''Call your Ford Dealer on<%${user.CustomAttribute['Work_Phone']}%>'''
	cta1_url = '''tel:<%${user.CustomAttribute['Home_Phone']}%>'''
	cta1_link_name = '''link_name_here'''
	cta2_text = '''Find your nearest Ford Dealer'''
	cta2_url = '''http://www.ford.com.ph/locate-a-dealer/'''
	cta2_link_name = '''find_dealer_button'''
	icon2 = '''ph_edm2_ownerprofile_20160801'''
	title2 = '''Anything changed? '''
	copy = '''Update your details now so you don't miss our latest offers.'''
	cta3_text = '''UPDATE NOW'''
	cta3_url = '''https://www.ford.com.ph/owner/login'''
	cta3_link_name = '''anything_changed'''

[[module]] #PH Social
path = 'email_modules/footer/ph/social'
color = 'white'

[[module]] #PH Online
path = 'email_modules/footer/ph/online'
color = 'white'
+++