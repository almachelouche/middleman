+++
markets = ["ph"]
title = '''PH Repurchase 017 All'''

[[module]]
path='email_modules/preheader'

	preheader = '''We hope you enjoy being a proud Ford owner just as much as we enjoy having you be a part of our Ford family!'''

[[module]] #Header Logo
path='email_modules/header/logo'
color='white'

	image = '''white'''
	url_link = '''https://www.ford.com.ph/'''
    
[[module]] #Banner Image
path='email_modules/image/banner'
color='white'

	image='''ph_edm6_yescampaign_20171011'''
	url_link='''https://www.ford.com.ph/shopping/hot-deals/2017/hot-deal-2/'''
	url_link_name='''yes_campaign'''

[[module]] #Cover 07
path='email_modules/cover/02'
color='''white''' 

	title = '''GET A FORD BEFORE THE YEAR ENDS!'''
	copy = '''Hello <%${user['FirstName']}%><br /><br />We hope you enjoy being a Ford owner just as much as we value you.<br /><br />But if you’re considering an upgrade, check out the great deals we’re unveiling for our Year-End Sale.<br /><br />Drive home in a brand new <b>EcoSport</b> for as low as <b>Php 48,000</b> all-in low down payment, or an <b>Everest</b>, the reliable family SUV for just <b>Php 88,000</b> all-in low down payment, or opt for Ford’s built tough <b>Ranger</b> for only <b>Php 68,000</b> all-in low down payment.<br /><br />So, hurry and visit your preferred Ford dealership before the year ends!'''
	cta1_text = '''FIND OUT MORE'''
	cta1_url = '''https://www.ford.com.ph/shopping/hot-deals/2017/hot-deal-2/'''
	cta1_link_name = '''yes_campaign'''

[[module]] #Split 02
path='email_modules/split/02'
color='darkblue'

	title = '''Explore with confidence'''
	copy = '''Big news. Ford Explorer now has <a href="https://www.ford.com.ph/engineering/sync/" name="sync3" style="text-decoration:underline; color:#2d96cd;">SYNC<sup>TM</sup> 3</a> with Navigation! Together with impressive engine options – Explorer offers 3.5L and 2.3L engines – it’s easier than ever to stay on track and on time.'''
	cta1_text = '''VIEW EXPLORER'''
	cta1_url = '''https://www.ford.com.ph/suvs/explorer/'''
	cta1_link_name = '''explorer'''
	cta1_icon = '''more'''
	image = '''PH_edm5_Explorer_20170911'''

[[module]]
path='email_modules/cover/01'
color='''green'''

title='''Stay covered like never before'''
copy='''Ford's Extended Warranty and exclusive Scheduled Service Plan are back! Enjoy greater coverage and better value than ever before when you buy a new Ford vehicle. Click below to see how our plans make owning a Ford even easier.'''

[[module]]
path='email_modules/singles/2textcta'
color='''green'''

cta1_text = '''SCHEDULE SERVICE PLAN'''
cta1_url = '''https://www.ford.com.ph/owner/service-schedule-plan/'''
cta1_link_name = '''ssp'''
cta2_text = '''EXTENDED WARRANTY'''
cta2_url = '''https://www.ford.com.ph/owner/warranties/'''
cta2_link_name = '''extended_warranty'''
cta1_icon='''more'''

[[module]] #Banner Image No Link
path = '''email_modules/image/banner_nolink'''
color = '''white'''

	image = '''ph_edm5_staycovered_20161024'''

[[module]] #Cover 05
path='email_modules/cover/02'
color='''white'''

	title = '''Anything changed?'''
	copy = '''Update your details now so you don't miss our latest offers.'''
	cta1_text = '''UPDATE NOW'''
	cta1_url = '''https://www.ford.com.ph/owner/owner-unauthenticated/#overlay/content/ford/ph/en_ph/site-wide-content/overlays/form-overlay/login'''
	cta1_link_name = '''anything_changed'''
	icon = '''ph_edm2_ownerprofile_20160801'''

[[module]] #PH Social
path = 'email_modules/footer/ph/social'
color = 'white'

[[module]] #PH Online
path = 'email_modules/footer/ph/online'
color = 'white'
+++