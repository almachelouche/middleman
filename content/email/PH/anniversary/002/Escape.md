+++
markets = ["ph"]
title = '''PH Anniversary 002 Escape'''

[[module]]
path='email_modules/preheader'
color='''white'''

preheader = '''Can you believe it's been 12 months since you drove away in your new Ford Escape? We couldn't let this special date pass without saying thank you, once again, for choosing Ford.'''

[[module]] #Header Logo
path='email_modules/header/logo'
color='white'

  image = '''white'''
  url_link = '''https://www.ford.com.ph/'''

[[module]] #Cover 01
path='email_modules/cover/01'
color='''white'''
 
  title = '''It seems like only yesterday'''
  copy = '''Hello <%${user['FirstName']}%><br /><br />Can you believe it's been 12 months since you drove away in your new Ford Escape? We couldn't let this special date pass without saying thank you, once again, for choosing Ford. We'll continue to stay in touch so you're always the first to know of any special offers and other helpful information.<br />You can count on it.'''

[[module]] #Banner Image No Link
path = '''email_modules/image/banner_nolink'''
color = '''white'''

  image = '''ph_edm1&4_np_escape_20160801'''

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