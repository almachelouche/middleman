+++
markets = ["ph"]
title = '''PH Repurchase 007 All'''

[[module]]
path='email_modules/preheader'
color='''nothing'''

preheader = '''Hurry in before Dec 31. This deal can't last. Say YES to a new Ford. We just wanted to say 'thank you!' for being a Ford owner.'''

[[module]] #Header Logo
path='email_modules/header/logo'
color='white'

  image = '''white'''
  url_link = '''https://www.ford.com.ph/'''

[[module]] #Cover 07
path='email_modules/cover/02'
color='''white''' 

  title = '''Say YES to a new Ford'''
  copy = '''Hello <%${user['FirstName']}%><br /><br />We just wanted to say 'thank you!' for being a Ford owner. We hope you and your <%${user.CustomAttribute['Model']}%> continue your journey together for as long as possible.<br /><br />But if you're thinking about an upgrade, why not test drive an exciting new Ford? Before December 31, you can drive away with a Ford vehicle for as little as an All-In Low Down Payment of ₱48,000 or just ₱7,888 monthly.'''
  cta1_text = '''FIND OUT MORE'''
  cta1_url = '''https://www.ford.com.ph/shopping/hot-deals/2016/hot-deal-2/'''
  cta1_link_name = '''yes'''

[[module]] #Banner Image No Link
path = '''email_modules/image/banner_nolink'''
color = '''white'''

  image = '''ph_edm5_yes_20161024'''
  
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