+++
markets = ["in"]
title = '''IN Welcome 002 Mustang'''


[[module]]
path='email_modules/preheader'
color='''nothing'''

   preheader='''You are now in the driver's seat of the world's best-selling coupe. It's time to conjure up images of freedom and raw performance, while you burn the roads with unbridled power. '''

[[module]] #Header Logo
path='email_modules/header/logodesktop'
color='white_pb'

  image = '''white_pb'''
  url_link = '''https://www.india.ford.com/'''

[[module]] #Cover 01
path='email_modules/cover/01'
color='''white'''
 
  title = '''Welcome to the ride of your life,<br /><%${user.CustomAttribute['FullName']}%>'''
  copy = '''You are now in the driver's seat of a true legend. It's time to conjure up images of freedom and raw performance while you unleash its unbridled power. The iconic Ford Mustang has arrived. And you are one of the elite few to own this moment. <br /><br /><span style="font-weight:bold">GET YOUR HEART RACING. UNLEASH YOUR TRUE SELF.</span> '''

[[module]] #Banner Image No Link
path = '''email_modules/image/banner_nolink'''
color = '''white'''
  image = '''in_edm1&4_np_mustang_20170116'''

[[module]] #Cover 01
path='email_modules/cover/01'
color='''white_gt'''
 
  title = '''Your first and second service is on the house'''
  copy = '''Keep your Ford Mustang in top shape with us. Enjoy two free inspections and car washes - on us - within the first 2 months or 3000 kilometers and within the first 12 months or 15,000 kilometers. <br /><br />Contact <%${user.CustomAttribute['Dealer_Name']}%> on <a href="tel:<%${user.CustomAttribute['Dealer_Phone']}%>" style="text-decoration:underline; color:#2D96CD;" ><%${user.CustomAttribute['Dealer_Phone']}%></a> for more information.'''

[[module]]
path='email_modules/singles/ctablock'
color='''white'''
	
	cta1_text = '''FIND A DEALER'''
	cta1_url = '''https://www.india.ford.com/cars/mustang/locate-a-dealer/?intcmp=bb-fin-vhp-ford%20mustang-fin-lad-ford%20mustang-return/'''
	cta1_link_name = '''locate_dealer'''

[[module]] #Dual 04
path='email_modules/dual/04'
color='white'

  title1 = '''Owner Manual'''
  copy1 = '''Download your Owner Manual on your device for access anytime anywhere. '''
  cta1a_text = '''<br /><br />DOWNLOAD NOW'''
  cta1a_url = '''https://www.india.ford.com/owner/owner-manual/'''
  cta1a_link_name = '''owner_manual'''
  cta1b_text = ''''''
  cta1b_url = ''''''
  cta1b_link_name = ''''''
  cta1c_text = ''''''
  cta1c_url = ''''''
  cta1c_link_name = ''''''
  icon1 = '''in_edm1_ownermannual_20160801'''
  title2 = '''Get In SYNC<sup style="font-size: 75%; line-height: 0; position: relative; vertical-align: baseline; top: -0.5em;">®</sup>'''
  copy2 = '''Your Ford Mustang comes with Ford SYNC<sup style="font-size: 75%; line-height: 0; position: relative; vertical-align: baseline; top: -0.5em;">®</sup> for hands-free control while you drive. '''
  cta2a_text = '''<br /><br />LEARN ABOUT SYNC</a><sup style="font-size: 75%; line-height: 0; position: relative; vertical-align: baseline; color:#2d96cd; top: -0.5em;text-decoration:none">®</sup>'''
  cta2a_url = '''https://www.india.ford.com/owner/sync-support/2/'''
  cta2a_link_name = '''sync'''
  cta2b_text = ''''''
  cta2b_url = ''''''
  cta2b_link_name = ''''''
  cta2c_text = ''''''
  cta2c_url = ''''''
  cta2c_link_name = ''''''
  icon2 = '''in_edm1_sync_20160801'''

[[module]] #Banner Image No Link
path = '''email_modules/image/banner_nolink'''
color = '''white'''

  image = '''in_edm1_pocket_mustang_20161222'''

[[module]]
path='email_modules/singles/copy'
color='''white'''

copy='''<br /><br /><span style="text-align:center; font-Size:24px; line-height: 30px; font-weight: normal; font-style: regular; color:#1B394E; font-family: 'Arial','Helvetica','Sans-Serif'; padding-bottom:20px;">The Pocket Mustang Experience</span><br /><br />Turn your mobile phone into a scale-model of the Ford Mustang and maneuver it on any surface. Watch your pocket car skills get recreated with a real Ford Mustang on a real track. Share the video and challenge your friends. Get this digital experience at <a href="http://pocketmustang.india.ford.com/en/" name="pocket_mustang" style="text-decoration:underline; color:#2D96CD;" >http://pocketmustang.india.ford.com/en/</a> '''

[[module]] #Cover 05
path='email_modules/cover/02'
color='''white'''

  title = '''Your Profile Details'''
  copy = '''Name&#58; <%${user['FirstName']}%> <%${user['LastName']}%><br />Email&#58; <%${user.CustomAttribute['RealEmail']}%><br />Phone&#58; <%${user.CustomAttribute['Mobile_Phone']}%><br />Address&#58; <%${user.CustomAttribute['Address_1']}%> <%${user.CustomAttribute['Address_2']}%><br /><br />Anything changed?'''
  cta1_text = '''UPDATE YOUR DETAILS'''
  cta1_url = '''https://www.india.ford.com/'''
  cta1_link_name = '''profile_update'''
  icon = '''th_edm2_ownerprofile_20160801'''

[[module]] #Footer 4 Icons
path='email_modules/footer/4icons'
color='white'

  icon1_url='''tel:18004252500'''
  icon1_link_name = '''tel_customer_care'''
  icon1_image='''in_customer_care_number_20160401'''
  icon2_url='''tel:18002097400'''
  icon2_link_name = '''tel_RSA'''
  icon2_image='''in_rsa_no_20160615'''
  icon3_url=''''''
  icon3_link_name = ''''''
  icon3_image=''''''
  icon4_url=''''''
  icon4_link_name = ''''''
  icon4_image=''''''
  
[[module]] #Footer IN Social
path='email_modules/footer/in/social'
color='white'

[[module]] #Footer IN Online
path='email_modules/footer/in/online'
color='white'

+++