+++
markets = ["in"]
title = '''IN Extended Warranty 004 urgent'''
draft = true

[[module]]
path='email_modules/preheader'
color='''white'''

	preheader = '''Your Ford <%${user.CustomAttribute['Model']}%>'s warranty will expire on <%${user.CustomAttribute['EWDate']}%>. Once it expires, it can't be extended.'''

[[module]] #Header Logo
path='email_modules/header/logodesktop'
color='white_pb'

  image = '''white_pb'''
  url_link = '''https://www.india.ford.com/'''

[[module]] #Cover 06
path='email_modules/cover/02'
color='''white_ot'''

  title = '''Last chance to extend your warranty'''
  copy = '''Hello <%${user.CustomAttribute['FullName']}%><br /><br />Your Ford <%${user.CustomAttribute['Model']}%>'s warranty will expire on <%${user.CustomAttribute['EWDate']}%>. Once it expires, it can't be extended.<br /><br />Our Extended Warranty Plans are designed specifically for your vehicle, and protect you from out-of-pocket bills. They cover major mechanical and electric failures, and are even transferrable - improving your vehicle's resale value.<br /><br />We've got your back. Get in touch today and stay protected.'''
  cta1_text = '''STAY COVERED'''
  cta1_url = '''https://www.india.ford.com/content/ford/in/en_in/site-wide-content/overlays/forms/buy-extended-warranty/'''
  cta1_link_name = '''buy_warranty'''
  cta2_text = '''FIND OUT MORE'''
  cta2_url = '''https://www.india.ford.com/owner/extended-warranty/'''
  cta2_link_name = '''warranty_info'''
  icon = '''in_edm3_extendedwarranty_20160801'''

[[module]] #Banner Image No Link
path = '''email_modules/image/banner_nolink'''
color = '''white'''

  image = '''in_edm3_extendedwarranty_20160801'''

[[module]] #Footer 5 Icons
path='email_modules/footer/5icons'
color='white'

  icon1_url='''https://www.india.ford.com/locate-dealer/'''
  icon1_image='''in_dealers_20160414'''
  icon1_link_name = '''locate_dealer_footer'''
  icon2_url='''https://fordassured.in/'''
  icon2_image='''in_ford_assured_20160401'''
  icon2_link_name = '''Ford_Assured'''
  icon3_url='''tel:18004252500'''
  icon3_image='''in_customer_care_number_20160401'''
  icon3_link_name = '''tel_Customer_Care'''
  icon4_url='''tel:18002097400'''
  icon4_image='''in_rsa_no_20160615'''
  icon4_link_name = '''tel_RSA'''
  icon5_url='''https://partscalculator.fordind.com:1443/Fill_Field?extcmp=hp_eb_nav'''
  icon5_image='''in_svc_parts_20160801'''
  icon5_link_name = '''parts_calculator'''
    
[[module]] #Footer IN Social
path='email_modules/footer/in/social'
color='white'

[[module]] #Footer IN Online
path='email_modules/footer/in/online'
color='white'
+++