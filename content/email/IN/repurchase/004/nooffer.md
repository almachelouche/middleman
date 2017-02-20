+++
markets = ["in"]
title = '''IN Repurchase 004 No Offer'''

[[module]]
path='email_modules/preheader'
color='''white'''

	preheader = '''We noticed you've been driving your Ford <%${user.CustomAttribute['Model']}%> for a while now and might be thinking about purchasing a new Ford.'''

[[module]] #Header Logo
path='email_modules/header/logodesktop'
color='white_pb'

  image = '''white_pb'''
  url_link = '''https://www.india.ford.com/'''

[[module]] #Banner Image No Link
path = '''email_modules/image/banner_nolink'''
color = '''white'''

  image = '''in_edm5_syncvehicles_20160801'''

[[module]] #Cover 08
path='email_modules/cover/02'
color='''white'''
  
  title = '''Meet the latest Ford vehicles'''
  copy = '''We noticed you've been driving your Ford <%${user.CustomAttribute['Model']}%> for a while now and might be thinking about purchasing a new Ford.<br /><br />At Ford, we design vehicles around you. That's why many new Ford vehicles - like EcoSport, Next-Gen Figo and Aspire - come with the SYNC<sup>®</sup> voice-activation system.<br /><br />Just pair your smartphone and use simple voice commands to make calls, listen to text messages, and play your favourite music.<br /><br />How smart is that? Come take a test drive and find out for yourself.'''
  cta1_text = '''FIND A DEALER'''
  cta1_url = '''https://www.india.ford.com/locate-dealer/'''
  cta1_link_name = '''locate_dealer'''
  cta2_text = '''LEARN MORE'''
  cta2_url = '''https://www.india.ford.com/sync/'''
  cta2_link_name = '''sync'''

[[module]] #Custom 3 Column Car
path='email_modules/custom/3column_car'
color='white'

  icon1 = '''in_edm5_3vehicle_figo_20160801'''
  icon2 = '''in_edm5_3vehicle_ecosport_20160801'''
  icon3 = '''in_edm5_3vehicle_aspire_20160801'''
  cta1_text = '''Explore Next-Gen Figo'''
  cta1_url = '''https://www.india.ford.com/cars/figo/'''
  cta2_text = '''Explore EcoSport'''
  cta2_url = '''https://www.india.ford.com/suvs/ecosport/'''
  cta3_text = '''Explore Aspire'''
  cta3_url = '''https://www.india.ford.com/cars/aspire/'''
  cta1_icon = '''play'''

[[module]] #Cover 05
path='email_modules/cover/02'
color='''white'''

  title = '''Ford Live Chat'''
  copy = '''Ford Live Chat is now online! Get real-time answers from our team of Ford Advisors between 9am to 8pm. Just another way to show how much we care.'''
  cta1_text = '''START CHATTING'''
  cta1_url = '''https://ford-livechat.s3ae.com/in/chat.php?a=1e4b8&intgroup=c3VwcG9ydA__&hg=Pw__&hcgs=MQ__&htgs=MQ__'''
  cta1_link_name = '''live_chat'''
  icon = '''in_edm5_livechat_blue_20161018'''

[[module]] #Cover 05
path='email_modules/cover/02'
color='''white'''

  title = '''Your Profile Details'''
  copy = '''Name&#58; <%${user['FirstName']}%> <%${user['LastName']}%><br />Email&#58; <%${user.CustomAttribute['RealEmail']}%><br />Phone&#58; <%${user.CustomAttribute['Mobile_Phone']}%><br />Address&#58; <%${user.CustomAttribute['Address_1']}%> <%${user.CustomAttribute['Address_2']}%><br /><br />Anything changed?'''
  cta1_text = '''UPDATE YOUR DETAILS'''
  cta1_url = '''https://www.india.ford.com/profile-update-form?fbdata=req_firstName=<% ${user['FirstName']} %>||req_lastName=<% ${user['LastName']} %>||req_mobileNumber=<%${user.CustomAttribute['Mobile_Phone']}%>||req_EmailID=<% ${user.CustomAttribute['RealEmail']} %>||req_BuildingNo=<% ${user.CustomAttribute['Address_1']} %>||req_StreetRoad=<%${user.CustomAttribute['Address_2']}%>||req_Area=<% ${user.CustomAttribute['Area']} %>||req_Landmark=<% ${user.CustomAttribute['Landmark']} %>||req_city=<% ${user.CustomAttribute['City']} %>||req_State=<% ${user.CustomAttribute['State']} %>||req_postCode=<% ${user.CustomAttribute['Post_Code']} %>'''
  cta1_link_name = '''profile_update'''
  icon = '''th_edm2_ownerprofile_20160801'''

[[module]]
path='email_modules/footer/5icons'
color='white'

  icon1_url='''https://www.india.ford.com/locate-dealer/'''
  icon1_image='''in_dealers_20160414'''
  icon1_link_name = '''locate_dealer_footer'''
  icon2_url='''https://www.india.ford.com/finance/'''
  icon2_image='''in_ford_credit_20160401'''
  icon2_link_name = '''ford_credit'''
  icon3_url='''https://fordassured.in/'''
  icon3_image='''in_ford_assured_20160401'''
  icon3_link_name = '''ford_assured'''
  icon4_url='''tel:18004252500'''
  icon4_image='''in_customer_care_number_20160401'''
  icon4_link_name = ''''''
  icon5_url='''tel:18002097400'''
  icon5_image='''in_rsa_no_20160615'''
  icon5_link_name = ''''''
    
[[module]] #Footer IN Social
path='email_modules/footer/in/social'
color='white'

[[module]] #Footer IN Online
path='email_modules/footer/in/online'
color='white'


+++