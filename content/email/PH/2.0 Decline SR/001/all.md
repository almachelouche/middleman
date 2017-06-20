+++
markets = ["ph"]
title = '''PH 2.0 Decline SR 001'''


[[module]]
path='email_modules/preheader'

	preheader = '''Did you decline important maintenance? Book an appointment now.'''

[[module]] #Header Logo
path='email_modules/header/logo'
color='white'

	image = '''white'''
	url_link = '''https://www.ford.com.ph/'''

[[module]] #Cover 06
path='email_modules/cover/02'
color='''darkblue'''
icon='''ph_edm2d_svcwrench_urgent_20170328'''

title = '''Your <%${user.CustomAttribute['Model']}%> needs attention'''
copy = '''We noticed that you declined an important part of your servicing at your last appointment. Your <%${user.CustomAttribute['Model']}%> may now be unsafe to drive, and that’s got us worried.<br /><br />When you come into a Ford service center, you’re putting your vehicle into the best hands possible. Our trained technicians know the specifics of your Ford vehicle, and only use genuine Ford parts and state-of-the-art diagnostic tools. No one else can guarantee that.<br /><br />It's important to book your service today. Just click below to contact <%${user.CustomAttribute['Dealer_Name']}%> (during business hours) or to find your nearest dealer.'''
cta1_text='''FIND A DEALER'''
cta1_url='''https://www.ford.com.ph/locate-a-dealer/'''
cta1_link_name='''find_dealer'''
cta2_text='''CALL <%${user.CustomAttribute['Dealer_Phone']}%>'''
cta2_url='''tel:<%${user.CustomAttribute['Dealer_Phone']}%>'''

[[module]] #Service Status No Copy
path='email_modules/custom/svcstatus_nocopy'
color='darkblue'

toptitle='''Your <%${user.CustomAttribute['Model']}%>’s Health Status'''
	segmentAgreen = '''(user.CustomAttribute['Brake'] == null)'''
	segmentAyellow = '''(user.CustomAttribute['Brake'] == 'YBRAKE')'''
	segmentAred = '''(user.CustomAttribute['Brake'] == 'RBRAKE')'''
		icon1green = '''in_edm2d_status_brake_black_20160801'''
		title1green = '''Brakes'''
		subtitle1green = '''Good to go'''
		icon1yellow = '''in_edm2d_status_brake_black_20160801'''
		title1yellow = '''Brakes'''
		subtitle1yellow = '''Service soon'''
		icon1red = '''in_edm2d_status_brake_white_20160801'''
		title1red = '''Brakes'''
		subtitle1red = '''Service immediately'''
	segmentBgreen = '''(user.CustomAttribute['Tyre'] == null)'''
	segmentByellow = '''(user.CustomAttribute['Tyre'] == 'YTYRE')'''
	segmentBred = '''(user.CustomAttribute['Tyre'] == 'RTYRE')'''
		icon2green = '''in_edm2d_status_tyre_black_20160801'''
		title2green = '''Tires'''
		subtitle2green = '''Good to go'''
		icon2yellow = '''in_edm2d_status_tyre_black_20160801'''
		title2yellow = '''Tires'''
		subtitle2yellow = '''Service soon'''
		icon2red = '''in_edm2d_status_tyre_white_20160801'''
		title2red = '''Tires'''
		subtitle2red = '''Service immediately'''
	segmentCgreen = '''(user.CustomAttribute['Battery'] == null)'''
	segmentCyellow = '''(user.CustomAttribute['Battery'] == 'YBATT')'''
	segmentCred = '''(user.CustomAttribute['Battery'] == 'RBATT')'''
		icon3green = '''in_edm2d_status_battery_black_20160801'''
		title3green = '''Batteries'''
		subtitle3green = '''Good to go'''
		icon3yellow = '''in_edm2d_status_battery_black_20160801'''
		title3yellow = '''Batteries'''
		subtitle3yellow = '''Service soon'''
		icon3red = '''in_edm2d_status_battery_white_20160801'''
		title3red = '''Batteries'''
		subtitle3red = '''Service immediately'''

[[module]] #PH Social
path = 'email_modules/footer/ph/social'
color = 'white'

[[module]] #PH Online
path = 'email_modules/footer/ph/online'
color = 'white'
+++