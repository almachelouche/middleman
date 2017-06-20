+++
markets = ["au"]
title = '''AU Welcome 020 generic'''


[[module]] #Header Logo
path='email_modules/header/logo'
color='white'

	image = '''white'''
	url_link = '''https://www.ford.com.au/'''


[[module]] #Banner Image No Link
path = '''email_modules/image/banner_nolink'''
color = '''white'''

	image = '''au_edm1_cover_20161018'''

	[[module]] #Cover 11
path='email_modules/cover/03'
color='''white'''

	copy='''<br /><br />Celebrate new purchase and their new journey with Ford. Acknowledge new owners and repeat owners.<br /><br />Now that you’re on the road, we'd like to help you make the most out of your new <nameplate>'''

	[[module]] #Footer AU Online
path='email_modules/image/double_column_images_text'
color='white'

		title1 = '''Owners App'''
	copy1 = '''You can visit the Ford Owners Website online at any time or download the ford owner’s app to your mobile device for instant access on-the-go. Streamline your life with service reminders, instant access to Roadside Assistance, “how-to videos”, access your vehicle manuals and more.'''
	image1 = '''au_svc_icon1'''
	image1_url = '''https://www.ford.com.au/owners/vehicle-support/app-download/'''
	image1_link_name = '''owners'''


		title2 = '''Accessories'''
	copy2 = '''-	Ford Genuine Accessories are designed to fit perfectly and integrate seamlessly with <nameplate> safety systems. Get the most out of your new <nameplate> with our selection of accessories that will take your work or play to the next level.'''
	image2 = '''au_svc_icon1'''
	image2_url = '''https://www.ford.com.au/shopping/accessories/'''
	image2_link_name = '''accessories'''

		[[module]] #Footer AU Online
path='email_modules/image/double_column_images_text'
color='white'

		title1 = '''SYNC Support'''
	copy1 = '''Be a Sync expert, get to you know your Sync system on our Sync support portal.	Find out how to use your Satellite Navigation System, set up your Emergency assistance or familiarise yourself with popular voice demands and more.'''
	image1 = '''au_svc_icon1'''
	image1_url = '''https://www.ford.com.au/owners/technology/sync-support/sync1/'''
	image1_link_name = '''sync'''

		title2 = '''Service'''
	copy2 = '''Convenience. Reliability. And no nasty surprises. They’re what service should be. And they’re exactly what Ford promises when you have your car serviced.	Find out what makes Ford Service the best.'''
	image2 = '''au_svc_icon1'''
	image2_url = '''https://www.ford.com.au/owners/service/'''
	image2_link_name = '''service'''

		[[module]] #Cover 01
path='email_modules/cover/01'
color='''fordblue'''

	icon='''au_edm1_welcome_icon_20161019'''
	title='''Can we help?'''
	copy='''If you have any further questions, please don't hesitate to contact <br /><br /><span style="color:#FFFFFF"><%${user.CustomAttribute['Dealer_Name']}%> on <a href="tel:<%${user.CustomAttribute['Dealer_Phone']}%>" style="color:#FFFFFF; text-decoration:none"><%${user.CustomAttribute['Dealer_Phone']}%></a>	</span>or <a href="tel:133673" style="color:#FFFFFF; text-decoration:none"><span style="color:#FFFFFF">13 FORD (13 36 73)</span>'''


[[module]] #Footer AU Social
path='email_modules/footer/au/social'
color='white'

[[module]] #Footer Disclaimer
path='email_modules/footer/disclaimer'
color='white'

	text = '''DISCLAIMERS:
				<br /> <br />'''

+++
