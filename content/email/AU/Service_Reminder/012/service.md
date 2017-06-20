+++
markets = ["au"]
title = '''AU Service Reminder 011 All Blue back up'''

[[module]]
path='email_modules/preheader'


	preheader=''''''

[[module]]
path='email_modules/preheader'


	preheader=''''''

[[module]] #Header Logo
path='email_modules/header/logo'
color='white'

	image = '''white'''
	url_link = '''http://google.com'''

[[module]] #Banner Image
path='email_modules/image/banner'
color='white'

	image = '''au_edm2_1st_service_20170310'''
	url_link = '''https://www.ford.com.au/owners/service/'''

	[[module]]
path='email_modules/cover/03'
color='''white'''

	copy='''<br />Hi <%${user.CustomAttribute['FullName']}%><br /><br />Here’s a quick reminder that your new <%${user.CustomAttribute['Model']}%> is due for its complimentary 2-month/3,000 km Peace Of Mind Service Inspection. <br /><br />Now that you’ve been on the road for a few months, our Ford-trained technicians will complete a quick inspection to ensure that your Ford <%${user.CustomAttribute['Model']}%> is running at its absolute best. <br /><br />Book with <%${user.CustomAttribute['Dealer_Name']}%> on <%${user.CustomAttribute['Dealer_Phone']}%> today.'''

		[[module]]
path='email_modules/singles/ctablock'
color='''white'''

	cta1_text = '''BOOK A SERVICE'''
	cta1_url = '''https://consumer.xtime.net.au/scheduling/?company=14745&store=<%${user.CustomAttribute['DealerCode']}%>&VIN=<%${user.CustomAttribute['VIN']}%>&provider=FORD_AU_THE_BLUE_HIVE&keyword=<%${user.CustomAttribute['CampaignID']}%>&dest=&extid=<%${user.CustomAttribute['CampaignID']}%>&extctxt=FORD_AU_THE_BLUE_HIVE&cfn=<%${user.CustomAttribute['FullName']}%>&cln=<%${user['LastName']}%>&cpn=<%${user.CustomAttribute['Mobile_Phone']}%>&cem=<%${user.CustomAttribute['RealEmail']}%>&button=blue'''
	cta1_link_name = '''SERVICE'''

[[module]] # Owner App Image Right
path='email_modules/custom/ownerapp_imgr'
color='black'

	title = '''Ford Owners App'''
	text1 = '''Want more information, tools, and tips right at your fingertips? Try the Ford Owners App.'''
	text2 = '''<br />&nbsp;&#8226;&nbsp;&nbsp;&nbsp;Streamline service reminders<br />&nbsp;&#8226;&nbsp;&nbsp;&nbsp;Locate a dealer/service centre<br />&nbsp;&#8226;&nbsp;&nbsp;&nbsp;View "how-to" videos<br />'''
	cta1_text = '''iOS'''
	cta1_url = '''https://itunes.apple.com/au/app/ford-owners/id990342351?mt=8'''
	cta1_link_name = '''ios1'''
	cta2_text = '''ANDROID'''
	cta2_url = '''https://play.google.com/store/apps/details?id=com.ford.fordowners&hl=en/'''
	cta2_link_name = '''android1'''
	image = '''owner_app_20160328'''

[[module]] #Footer AU Social
path='email_modules/footer/au/social'
color='white'

[[module]] #Footer AU Online
path='email_modules/footer/au/online'
color='white'
+++
