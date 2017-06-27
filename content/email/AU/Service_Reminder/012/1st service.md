+++
markets = ["au"]
title = '''AU Service Reminder first'''

[[module]]
path='email_modules/preheader'
color='''white'''

	preheader='''Our Ford-trained technicians are ready to ensure your Ford is in top shape.'''

[[module]] #Banner Image
path='email_modules/image/banner'
color='white'

	image = '''AU_edm2_svc_banner_20160615'''
	url_link = '''https://www.ford.com.au/owners/service/'''

	[[module]]
path='email_modules/cover/03'
color='''white'''

	copy='''<br />Hi <%${user.CustomAttribute['FullName']}%><br /><br />We hope you’re enjoying your new Ford <nameplate>. Now that you’ve been on the road for a few months your <Nameplate> is due for its complimentary 2-month/3,000km ‘Peace of Mind’	<br /><br />Service Inspection. <br /><br />Our Ford-trained technicians will inspect your vehicle and ensure it	is running at its absolute best. <br /><br />Book your ‘Peace of Mind Service Inspection	with <Dealer Name> on <Dealer Phone> today, or find your nearest dealer here. '''

		[[module]]
path='email_modules/singles/ctablock'
color='''white'''

	cta1_text = '''BOOK YOUR INSPECTION'''
	cta1_url = '''https://consumer.xtime.net.au/scheduling/?company=14745&store=<%${user.CustomAttribute['DealerCode']}%>&VIN=<%${user.CustomAttribute['VIN']}%>&provider=FORD_AU_THE_BLUE_HIVE&keyword=<%${user.CustomAttribute['CampaignID']}%>&dest=&extid=<%${user.CustomAttribute['CampaignID']}%>&extctxt=FORD_AU_THE_BLUE_HIVE&cfn=<%${user.CustomAttribute['FullName']}%>&cln=<%${user['LastName']}%>&cpn=<%${user.CustomAttribute['Mobile_Phone']}%>&cem=<%${user.CustomAttribute['RealEmail']}%>&button=blue'''
	cta1_link_name = '''BOOK YOUR INSPECTION'''

[[module]]
path='email_modules/cover/03'
color='''white'''

	copy='''<br />When looking to personalise your Ford <nameplate> there are no better accessories than Ford Genuine Accessories. Click here to see the full range.'''

 
[[module]] # Owner App Image Right
path='email_modules/custom/ownerapp_imgr'
color='white'

	title = '''Know your Ford'''
	text1 = '''Did you know with the Ford Owner app, you can accesss the entire SYNC Phrasebok, read your vehicle's Owner Manual and watch useful 'How To' videos?<br/><br/>Download the Ford Owner app and get started today.<br/><br/>Just search Ford Owners in your app store.'''
	text2 = '''Put some text here as well'''
	cta1_text = '''iOS'''
	cta1_url = '''https://itunes.apple.com/au/app/ford-owners/id990342351?mt=8'''
	cta1_link_name = '''ios1'''
	cta2_text = '''ANDROID'''
	cta2_url = '''https://play.google.com/store/apps/details?id=com.ford.fordowners&hl=en/'''
	cta2_link_name = '''android1'''
	image = '''AU_edm2_owner_app2_20160615'''

[[module]] #Footer AU Social
path='email_modules/footer/au/social'
color='white'

[[module]] #Footer AU Online
path='email_modules/footer/au/online'
color='white'
+++
