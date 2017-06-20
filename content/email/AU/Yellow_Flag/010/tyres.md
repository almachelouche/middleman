+++
markets = ["au"]
title = '''AU Yellow-Flag 010 Tyres'''

[[module]]
path='email_modules/preheader'
color='''nothing'''

	preheader=''''''

[[module]] #Header Logo
path='email_modules/header/logo'
color='white'

	image = '''white'''
	url_link = '''http://google.com'''
	
[[module]] #Banner Image
path='email_modules/image/banner'
color='white'

	image='''in_edm1&4_np_figo_20160801'''
	url_link='''http://google.com'''

[[module]] #Cover 07
path='email_modules/cover/02'
color='''black'''

	title='''Cover 07'''
	copy='''Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.<br /><br />Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum'''
	cta1_text='''Click Here!'''
	cta1_url='''http://google.com'''
	cta1_link_name = '''link_name_here'''

[[module]] #Service Status No Copy
path='email_modules/custom/svcstatus_nocopy'
color='white'
			
			toptitle='''Your Ford <%${user.CustomAttribute['Selected_Vehicle']}%>'s Health Status'''
	segmentAgreen = '''(user.CustomAttribute['Brake'] == 'G')'''
	segmentAyellow = '''(user.CustomAttribute['Brake'] == 'Y')'''
	segmentAred = '''(user.CustomAttribute['Brake'] == 'R')'''
		icon1green = '''in_edm2d_status_brake_black_20160801'''
		title1green = '''Brakes'''
		subtitle1green = '''Good to go'''
		icon1yellow = '''in_edm2d_status_brake_black_20160801'''
		title1yellow = '''Brakes'''
		subtitle1yellow = '''Service soon'''
		icon1red = '''in_edm2d_status_brake_white_20160801'''
		title1red = '''Brakes'''
		subtitle1red = '''Service immediately'''
	segmentBgreen = '''(user.CustomAttribute['Tyre'] == 'G')'''
	segmentByellow = '''(user.CustomAttribute['Tyre'] == 'Y')'''
	segmentBred = '''(user.CustomAttribute['Tyre'] == 'R')'''
		icon2green = '''in_edm2d_status_tyre_black_20160801'''
		title2green = '''Tyres'''
		subtitle2green = '''Good to go'''
		icon2yellow = '''in_edm2d_status_tyre_black_20160801'''
		title2yellow = '''Tyres'''
		subtitle2yellow = '''Service soon'''
		icon2red = '''in_edm2d_status_tyre_white_20160801'''
		title2red = '''Tyres'''
		subtitle2red = '''Service immediately'''
	segmentCgreen = '''(user.CustomAttribute['Battery'] == 'G')'''
	segmentCyellow = '''(user.CustomAttribute['Battery'] == 'Y')'''
	segmentCred = '''(user.CustomAttribute['Battery'] == 'R')'''
		icon3green = '''in_edm2d_status_battery_black_20160801'''
		title3green = '''Batteries'''
		subtitle3green = '''Good to go'''
		icon3yellow = '''in_edm2d_status_battery_black_20160801'''
		title3yellow = '''Batteries'''
		subtitle3yellow = '''Service soon'''
		icon3red = '''in_edm2d_status_battery_white_20160801'''
		title3red = '''Batteries'''
		subtitle3red = '''Service immediately'''
		
[[module]] #Cover 01
path='email_modules/cover/01'
color='black'

	icon = '''in_edm2d_status_battery_black_20160801'''
	title = '''Cover 01'''
	copy = '''Your Ford <%${user.CustomAttribute['Selected_Vehicle']}%> needs attention'''
	cta1_url = '''https://google.com'''
	cta1_text = '''blah blah blah'''
	cta1_icon = '''play'''
	cta1_link_name = '''link_name_here'''
	
[[module]] #Banner Image
path='email_modules/image/banner'
color='white'

	image='''in_edm1&4_np_figo_20160801'''
	url_link='''http://google.com'''

[[module]] #Footer AU Social
path='email_modules/footer/au/social'
color='white'

[[module]] #Footer Disclaimer
path='email_modules/footer/disclaimer'
color='white'

	text = '''Terms & Conditions	
				<br /> <br />*Limited offers available at participating Dealers while stocks last. Private and Blue, Silver and Gold Business Fleet customers only. Stock may vary between Dealers. All prices are recommended. See <a href="http://www.ford.com.au" style="text-decoration:underline; color:#91a4b1">ford.com.au</a> for full details.<br /><br />
				1. For SYNC&trade; compatibility visit <a href="http://www.fordsync.com" style="text-decoration:underline; color:#91a4b1">www.fordsync.com</a><br /><br />
				2. Bluetooth® is a registered trademark of Bluetooth SIG Inc., and is used under licence. Some phones not compatible.<br /><br />
				3. iPod is a trademark of Apple Inc. Requires connection cable, sold separately. Please refer to <a href="http://www.ford.com.au" style="text-decoration:underline; color:#91a4b1">ford.com.au</a> for compatibility.<br /><br />
				4. Available at participating Ford Dealers on vehicles built from 2007. Customers will pay equal to or less than the maximum price as published by Ford for the period of the web quote for standard items in the A and B logbook service together with selected routine maintenance items. See <a href="http://www.ford.com.au/service/t-and-c?emailid=20150918-0103_DisclaimerTC__Generic_0_FOA" style="text-decoration:underline; color:#91a4b1">www.ford.com.au/service/t-and-c</a> for full terms. <br /><br />
				5. Available to Private and Blue Business Fleet customers who have not reached 105,000km/7 years only at participating Dealers. State Auto Club Roadside Assistance & Membership is provided at no cost for 12 months or until your next eligible standard service (whichever occurs first). Customers must comply with scheduled servicing intervals to maintain continuity of membership. See <a href="http://www.ford.com.au/service/t-and-c?emailid=20150918-0103_DisclaimerTC__Generic_0_FOA" style="text-decoration:underline; color:#91a4b1">www.ford.com.au/service/t-and-c</a> for full terms. <br /><br />
				6. Available at participating dealers on scheduled services or overnight warranty repairs. Private and Blue, Silver and Gold Business Fleet customers only. Booking may be required. See <a href="http://www.ford.com.au/service/t-and-c?emailid=20150918-0103_DisclaimerTC__Generic_0_FOA" style="text-decoration:underline; color:#91a4b1">www.ford.com.au/service/t-and-c</a> for full terms.'''


[[module]] #Footer AU Online
path='email_modules/footer/au/online'
color='white'
+++