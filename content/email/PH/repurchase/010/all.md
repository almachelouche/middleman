+++
markets = ["ph"]
title = '''PH Repurchase 010 All'''

[[module]]
path='email_modules/preheader'
color='''nothing'''

preheader = '''Hurry in before Dec 31. This deal can't last. Say YES to a new Ford. We just wanted to say 'thank you!' for being a Ford owner.'''

[[module]] #Header Logo
path='email_modules/header/logo'
color='white'

  image = '''white'''
  url_link = '''http://www.ford.com.ph'''

[[module]] #Cover 07
path='email_modules/cover/02'
color='''white'''

  title = '''Say YES to a new Ford'''
  copy = '''Hello <%${user['FirstName']}%>!<br /><br />We just wanted to say 'thank you!' for being a Ford owner. We hope you and your <%${user.CustomAttribute['Model']}%> continue your journey together for as long as possible.<br /><br />But if you're thinking about an upgrade, why not test drive an exciting new Ford? Before December 31, you can drive away with a Ford vehicle for as little as an All-In Low Down Payment of ₱48,000 or just ₱7,888 monthly.'''
  cta1_text = '''FIND OUT MORE'''
  cta1_url = '''www.ford.com.ph/shopping/hot-deals/2016/hot-deal-2/'''
  cta1_link_name = '''yes'''

[[module]] #Banner Image No Link
path = '''email_modules/image/banner_nolink'''
color = '''white'''

  image = ''''''
  
  [[module]]
path='email_modules/cover/02'

color='''white'''
title='''Right Ford Right Now!'''
copy='''Purchase a Ford Fiesta, Ford Focus or Ford Ranger for as low as an All-In Low Down Payment of ₱48,000 or just ₱7,888 monthly. Get in quick. Offer ends August 31. '''
cta1_text='''FIND OUT MORE'''
cta1_url='''http://www.ford.com.ph/shopping/hot-deals/2016/hot-deal-2/'''

[[module]] #Custom 3 Column Car
path='email_modules/custom/3column_car'
color='white'

  icon1 = ''''''
  icon2 = ''''''
  icon3 = ''''''
  cta1_text = '''EXPLORE FIESTA'''
  cta1_url = '''http://www.ford.com.ph/cars/fiesta/'''
  cta1_link_name = ''''''
  cta2_text = '''EXPLORE FOCUS'''
  cta2_url = '''www.ford.com.ph/cars/focus/'''
  cta2_link_name = ''''''
  cta3_text = '''EXPLORE RANGER'''
  cta3_url = '''www.ford.com.ph/trucks/ranger/'''
  cta3_link_name = ''''''
  cta1_icon = '''more''' 

[[module]] #Cover 01
path='email_modules/cover/01'
color='''black'''

  title = '''EcoSport Black Edition is here!'''
  copy = '''We're proud to present the new, bolder model of the Ford EcoSport. Contact your nearest Ford dealer to get behind the wheel today.'''
  cta1_text = '''BOOK A TEST DRIVE'''
  cta1_url = '''http://www.ford.com.ph/suvs/ecosport/'''
  cta1_link_name = '''ecosport'''
  cta1_icon = '''more'''

[[module]] #Banner Image No Link
path = '''email_modules/image/banner_nolink'''
color = '''white'''

  image = '''ph_edm5_blackecosport_20160801'''

[[module]] #Split 02
path='email_modules/split/02'
color='black'

  title = '''EcoBoost wins again!'''
  copy = '''Ford's most advanced engine ever – the 1.0L EcoBoost – has once again been voted world's best small engine. That's five wins in five years!'''
  cta1_text = '''FIND OUT MORE'''
  cta1_url = '''http://www.ford.com.ph/engineering/ecoboost/'''
  cta1_link_name = '''ecoboost'''
  cta1_icon = '''more'''
  image = '''ph_edm5_intlengine_20160801'''

[[module]] #Cover 05
path='email_modules/cover/02'
color='''white'''

  title = '''Anything changed?'''
  copy = '''Update your details now so you don't miss our latest offers. '''
  cta1_text = '''UPDATE NOW'''
  cta1_url = '''https://www.ford.com.ph/owner/login'''
  cta1_link_name = '''anything_changed'''
  icon = '''ph_edm2_ownerprofile_20160801'''

[[module]] #PH Social
path = 'email_modules/footer/ph/social'
color = 'white'

[[module]] #PH Online
path = 'email_modules/footer/ph/online'
color = 'white'
+++