+++
markets = ["in"]
title = '''IN Welcome 005 Old Figo All'''
draft = true

[[module]]
path='email_modules/preheaderbefore'
color='''nothing'''
segmentif = ["(user.CustomAttribute['NewRepeat'] == 'R')"]

  preheader='''There's nothing quite like a new car. So it really means a lot to us that you chose another Ford.'''

[[module]]
path='email_modules/preheaderbefore'
color='''nothing'''
segmentelse = ["(user.CustomAttribute['NewRepeat'] == 'N')"]

  preheader='''There's nothing quite like a new car. And we want to thank you for making yours a Ford.'''

[[module]]
path='email_modules/body'
color='''nothing'''

[[module]]
path='email_modules/preheaderafter'
color='''nothing'''
segmentif = ["(user.CustomAttribute['NewRepeat'] == 'R')"]

  preheader='''There's nothing quite like a new car. So it really means a lot to us that you chose another Ford.'''

[[module]]
path='email_modules/preheaderafter'
color='''nothing'''
segmentelse = ["(user.CustomAttribute['NewRepeat'] == 'N')"]

  preheader='''There's nothing quite like a new car. And we want to thank you for making yours a Ford.'''

[[module]] #Header Logo
path='email_modules/header/logodesktop'
color='white_pb'

  image = '''white_pb'''
  url_link = '''https://www.india.ford.com/'''

[[module]] #Cover 01
path='email_modules/cover/01'
color='''white'''
segmentif = ["(user.CustomAttribute['NewRepeat'] == 'R')"]

  title = '''We love having you in the family'''
  copy = '''There's nothing quite like a new car. So it really means a lot to us that you chose another Ford. <br /><br />You're part of the Ford family, and we want to be sure you always enjoy the ride. So you can rest assured that we'll continue to be here for you. Just like you have been for us. '''

[[module]] #Cover 01
path='email_modules/cover/01'
color='''white'''
segmentelse = ["(user.CustomAttribute['NewRepeat'] == 'N')"]

  title = '''Hope you're enjoying the ride'''
  copy = '''There's nothing quite like a new car. And we want to thank you for making yours a Ford. <br /><br />As part of the Ford family, you'll be hearing from us from time to time, but only with information we think you'd find helpful. And that's a promise.'''

[[module]] #Banner Image No Link
path = '''email_modules/image/banner_nolink'''
color = '''white'''

  image = '''in_edm4_np_oldfigo_20160801'''

[[module]] #Cover 01
path='email_modules/cover/01'
color='''white_gt'''

  title = '''Your Free First Service '''
  copy = '''Keep your vehicle in top shape with us. Enjoy a free inspection and a car wash - on us - within the first 3 months or 2500 kilometers, whichever comes first. <br /><br />Contact <%${user.CustomAttribute['Dealer_Name']}%> on <a href="tel:<%${user.CustomAttribute['Dealer_Phone']}%>" style="text-decoration:underline; color:#2D96CD;" ><%${user.CustomAttribute['Dealer_Phone']}%></a> for more information.'''

[[module]] #Cover 05
path='email_modules/cover/02'
color='''green_pb'''
segmentif = ["(user.CustomAttribute['EWStatus'] == 'NO')"]


  title = '''Extended Peace of Mind'''
  copy = '''Extend your Ford Figo's warranty up to 5 years and enjoy worry-free driving. Your warranty protects your Ford against mechanical and electrical failures, and labour charges too¹.'''
  cta1_text = '''GET PEACE OF MIND'''
  cta1_url = '''https://www.india.ford.com/owner/extended-warranty/'''
  cta1_link_name = '''warranty_info'''
  icon = '''in_edm1_extendedwarranty_20160801'''

[[module]] # Owner App Image Right
path='email_modules/custom/ownerapp_imgr'
color='black'

  title = '''Ford Owners App'''
  text1 = '''Owning a Ford has never been easier, thanks to the Ford Owners App:'''
  text2 = '''<br />&nbsp;&#8226;&nbsp;&nbsp;&nbsp;<a href="https://youtu.be/3r79gbfZdO8" name="Decoder" style="text-decoration:underline; color:#B3B3B3">Decode your dashboard's icons</a><br />&nbsp;&#8226;&nbsp;&nbsp;&nbsp;<a href="https://youtu.be/eudIAyg1xp0" name="oa_rsa" style="text-decoration:underline; color:#B3B3B3">Access Roadside Assistance</a><br />&nbsp;&#8226;&nbsp;&nbsp;&nbsp;<a href="https://youtu.be/7FlXKGWiHYY" name="how-to_video" style="text-decoration:underline; color:#B3B3B3">Watch videos about your Ford</a><br />&nbsp;&#8226;&nbsp;&nbsp;&nbsp;<a href="https://youtu.be/kA0M4weGse0" name="dealer_locater_video" style="text-decoration:underline; color:#B3B3B3">Find a dealer near you</a>'''
  cta1_text = '''iOS'''
  cta1_url = '''https://itunes.apple.com/in/app/ford-owners/id990342351?mt=8'''
  cta1_link_name = '''oa_ios'''
  cta2_text = '''Android'''
  cta2_url = '''https://play.google.com/store/apps/details?id=com.ford.fordowners&hl=en'''
  cta2_link_name = '''oa_android'''
  image = '''owner_app_20160328'''

[[module]]
path='email_modules/cover/01'
color='white'

  icon='''in_edm1_ownermannual_20160801'''
  title='''Owner Manual'''
  copy='''Download your Owner Manual on your device for access anytime anywhere. '''
  cta1_url='''https://www.india.ford.com/owner/owner-manual/'''
  cta1_link_name = '''owner_manual'''
  cta1_text='''DOWNLOAD NOW'''
  cta1_icon='''more'''

[[module]] #Footer 4 Icons
path='email_modules/footer/4icons'
color='white'

  icon1_url='''https://www.india.ford.com/locate-dealer/'''
  icon1_link_name = '''locate_dealer'''
  icon1_image='''in_dealers_20160414'''
  icon2_url='''tel:18004252500'''
  icon2_link_name = '''tel_Customer_Care'''
  icon2_image='''in_customer_care_number_20160401'''
  icon3_url='''tel:18002097400'''
  icon3_link_name = '''tel_RSA'''
  icon3_image='''in_rsa_no_20160615'''
  icon4_url='''https://www.fordservicepricepromise.com/?extcmp=serca_101115_105328_fordind'''
  icon4_link_name = '''price_calculator'''
  icon4_image='''in_svc_price_20160801'''

[[module]] #Footer IN Social
path='email_modules/footer/in/social'
color='white'

[[module]] #Footer Disclaimer
path='email_modules/footer/disclaimer'
color='white'
segmentif = ["(user.CustomAttribute['EWStatus'] == 'NO')"]


  text='''1. Second year factory warranty is applicable for all Ford vehicles manufactured after 1st January 2008.'''

[[module]] #Footer IN Online
path='email_modules/footer/in/online'
color='white'

+++
