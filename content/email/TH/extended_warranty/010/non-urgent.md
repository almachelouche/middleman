+++
markets = ["th"]
title = '''TH Extended Warranty 010 non-Urgent'''
draft = true

[[module]]
path='email_modules/preheader'
color='''nothing'''

	preheader = '''ขยายการรับประกันเพื่อยืดระยะเวลาการบำรุงรักษารถฟอร์ดของคุณให้นานขึ้น'''

[[module]] #Header Logo
path='email_modules/header/logo'
color='white'

  image = '''white'''
  url_link = '''https://www.ford.co.th/'''

[[module]] #Cover 06
path='email_modules/cover/02'
color = '''white'''

  icon = '''ew'''
  title = '''<span style="font-family:Tahoma, Verdana, Sans-serif">Extend your peace of mind</span>'''
  copy = '''<span style="font-family:Tahoma, Verdana, Sans-serif">Hello <%InsertIf expression="${(user['FirstName'] == null || user['FirstName'] == '-')}" id="FirstName" %>ท่านลูกค้าฟอร์ด<%/InsertIf%> <%InsertElse%> <%${user['FirstName']}%> <%/InsertElse%></span><br /><br />Your <%${user.CustomAttribute['Model']}%>'s warranty will expire soon<sup>1</sup>.</span><br /><br /><span style="font-family:Tahoma, Verdana, Sans-serif">We'd like to offer you an opportunity to extend your warranty. Our customisable <span style="font-family:Tahoma, Verdana, Sans-serif"><strong>Premium Protection Plus Program (PPP)</strong></span><span style="font-family:Tahoma, Verdana, Sans-serif"> protects your vehicle for up to five years or 150,000 km. It covers major mechanical and electrical failures, guarantees expert service from Ford mechanics, and even improves your Ford's resale value.</span><br /><br /><span style="font-family:Tahoma, Verdana, Sans-serif">Get in touch today and extend your peace of mind.</span>'''
  cta1_text = '''<span style="font-family:Tahoma, Verdana, Sans-serif">SEE LATEST OFFERS</span>'''
  cta1_url = '''http://google.com'''
  cta1_link_name = '''link_name_here'''
  cta2_text = '''<span style="font-family:Tahoma, Verdana, Sans-serif">FIND A DEALER</span>'''
  cta2_url = '''http://google.com'''
  cta2_link_name = '''link_name_here'''

[[module]] #Banner Image No Link
path = '''email_modules/image/banner_nolink'''
color = '''white'''

  image = '''th_edm2_whyfordsvc_20160801'''

[[module]] #TH Social
path='email_modules/footer/th/social'
color='white'

[[module]] #Footer Disclaimer
path='email_modules/footer/disclaimer'
color='white'
text='''<span style="font-family:Tahoma, Verdana, Sans-serif">DISCLAIMERS<br /><br />[1] Ford vehicle warranties can only be extended within 35 months of purchase, or 100,000 km, whichever comes first.</span>'''

[[module]] #TH Online
path='email_modules/footer/th/online'
color='white'

+++