+++
markets = ["ph"]
title = '''PH Repurchase 016 All'''

[[module]]
path='email_modules/preheader'

	preheader = '''Join Ford as we come to your city and take you on an epic test drive!'''

[[module]] #Header Logo
path='email_modules/header/logo'
color='white'

	image = '''white'''
	url_link = '''https://www.ford.com.ph/'''

[[module]] #Cover 07
path='email_modules/cover/02'
color='''white''' 

	title = '''We want to celebrate with you!'''
	copy = '''Hello <%${user['FirstName']}%><br /><br />We hope that you’re still loving your <%${user.CustomAttribute['Model']}%> as much as we love having you be a part of our Ford family!<br /><br />This month, we at Ford Philippines are celebrating our 20th year anniversary, and we couldn't think of any other way to celebrate than with you! For the entire month of September, you can drive away with an EcSport for an All-In Low Down Payment of ₱68,000 or just ₱7,698 monthly or a large cash discount of ₱35,000 <br /><br />This deal ends September 30, 2017, so hurry to your nearest Ford dealer today.'''
	cta1_text = '''FIND OUT MORE'''
	cta1_url = '''https://www.ford.com.ph/shopping/hot-deals/2016/hot-deal-2/'''
	cta1_link_name = '''deal_search'''

[[module]] #Banner Image No Link
path = '''email_modules/image/banner_nolink'''
color = '''white'''

	image = '''ph_edm5_anniversary_20170907'''

[[module]] #Cover 07
path='email_modules/cover/02'
color='''white''' 

	title = '''Ford tests drives coming to you'''
	copy = '''Ford Island Conquest is not your ordinary test drive. Join us as Ford travels to your city this year with Ford Rangers, Everests and EcoSports geared and ready for you to hop in and take for a spin.<br /><br />You’ll also be able to enjoy giveaways and have a chance to win exclusive discounts – there’s as much as Php 100,000 cash discounts up for grabs!'''
	cta1_text = '''DATES & LOCATIONS'''
	cta1_url = '''https://www.ford.com.ph/ford-island-conquest/'''
	cta1_link_name = '''fic'''
    
[[module]] #Banner Image
path='email_modules/image/banner'
color='white'

	image='''ph_edm5_fic_20170327'''
	url_link='''https://www.ford.com.ph/ford-island-conquest/'''
	url_link_name='''fic'''

[[module]] #Split 02
path='email_modules/split/02'
color='fordblue'

	title = '''Explore with confidence'''
	copy = '''Big news. Ford Explorer now has <a href="https://www.ford.com.ph/engineering/sync/" name="sync3" style="text-decoration:underline; color:#2d96cd;">SYNC<sup>TM</sup> 3</a> with Navigation! Together with impressive engine options – Explorer offers 3.5L and 2.3L engines – it’s easier than ever to stay on track and on time.'''
	cta1_text = '''VIEW EXPLORER'''
	cta1_url = '''https://www.ford.com.ph/suvs/explorer/'''
	cta1_link_name = '''explorer'''
	cta1_icon = '''more'''
	image = '''PH_edm5_Explorer_20170526'''

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