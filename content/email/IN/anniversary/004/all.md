+++
markets = ["in"]
draft = true
title = '''IN Anniversary 004 All'''


[[module]]
path='email_modules/preheader'
color='''white'''

preheader = '''It has been nearly one year for you and your Ford <%${user.CustomAttribute['Model']}%>! We sincerely hope the drive has been smooth, rewarding, and - most of all - enjoyable. '''

[[module]] #Header Logo
path='email_modules/header/logodesktop'
color='white_pb'

  image = '''white_pb'''
  url_link = '''https://www.india.ford.com/'''
  
[[module]] #Banner Image No Link
path = '''email_modules/image/banner_nolink'''
color = '''white'''
segmentif = ["(user.CustomAttribute['Model'] == 'New Figo')"]

  image = '''in_edm1&4_np_figo_20160801'''
    
[[module]] #Banner Image No Link
path = '''email_modules/image/banner_nolink'''
color = '''white'''
segmentelseif = ["(user.CustomAttribute['Model'] == 'Aspire')"]

  image = '''in_edm1&4_np_aspire_20160801'''
   
[[module]] #Banner Image No Link
path = '''email_modules/image/banner_nolink'''
color = '''white'''
segmentelseif = ["(user.CustomAttribute['Model'] == 'Ecosport')"]

  image = '''in_edm1&4_np_ecosport_20160801'''

[[module]] #Banner Image No Link
path = '''email_modules/image/banner_nolink'''
color = '''white'''
segmentelseif = ["(user.CustomAttribute['Model'] == 'Endeavour')"]

  image = '''in_edm1&4_np_endeavour_20160801'''

[[module]] #Banner Image No Link
path = '''email_modules/image/banner_nolink'''
color = '''white'''
segmentelseif = ["(user.CustomAttribute['Model'] == 'Classic')"]

  image = '''in_edm4_np_classic_20160801'''
 
[[module]] #Banner Image No Link
path = '''email_modules/image/banner_nolink'''
color = '''white'''
segmentelseif = ["(user.CustomAttribute['Model'] == 'Fiesta')"]

  image = '''in_edm4_np_fiesta_20160801'''

[[module]] #Banner Image No Link
path = '''email_modules/image/banner_nolink'''
color = '''white'''
segmentelseif = ["(user.CustomAttribute['Model'] == 'Figo')"]

  image = '''in_edm4_np_oldfigo_20160801'''
  
[[module]] #Cover 01
path='email_modules/cover/01'
color='''white'''
 
  title = '''How are you celebrating?'''
  copy = '''Hello <%${user.CustomAttribute['FullName']}%><br /><br />It has been nearly one year for you and your Ford <%${user.CustomAttribute['Model']}%>! We sincerely hope the drive has been smooth, rewarding, and - most of all - enjoyable.<br /><br />As part of the Ford family, we'll continue to look out for you this coming year. That's why we created the Ford Owners App - to make owning a Ford easier than ever.  '''
  
[[module]] #Custom 05
path='email_modules/custom/4columnicon4titlescopy'
color='white'

  title1 = '''Service Checklist'''
  icon1 = '''in_edm1c_ownerapp_a_20160801'''
  text1 = '''Know what needs to be serviced, when.'''
  title2 = '''24h Roadside Assistance'''
  icon2 = '''in_edm1c_ownerapp_b_20160801'''
  text2 = '''Because we'll never leave you stranded. 	'''
  title3 = '''How-to<br /> Videos'''
  icon3 = '''in_edm1c_ownerapp_c_20160801'''
  text3 = '''Step-by-step guide to Ford tech. '''
  title4 = '''Dealer<br /> Locator'''
  icon4 = '''in_edm1c_ownerapp_d_20160801'''
  text4 = '''Because we're always here for you.'''

[[module]] #Cover 12
path='email_modules/cover/03'
color='''white'''

  copy = '''Download the app now, absolutely free, and have all of this important information and more at your fingertips, anywhere you and your Ford go.'''
  cta1_text = '''iOS'''
  cta1_url = '''https://itunes.apple.com/in/app/ford-owners/id990342351?mt=8/'''
  cta1_link_name = '''oa_ios'''
  cta2_text = '''ANDROID'''
  cta2_url = '''https://play.google.com/store/apps/details?id=com.ford.fordowners&hl=en/'''
  cta2_link_name = '''oa_android'''

[[module]] #Cover 05
path='email_modules/cover/02'
color='''white'''

  title = '''Your Profile Details'''
  copy = '''Name&#58; <%${user['FirstName']}%> <%${user['LastName']}%><br />Email&#58; <%${user.CustomAttribute['RealEmail']}%><br />Phone&#58; <%${user.CustomAttribute['Mobile_Phone']}%><br />Address&#58; <%${user.CustomAttribute['Address_1']}%> <%${user.CustomAttribute['Address_2']}%><br /><br />Anything changed?'''
  cta1_text = '''UPDATE YOUR DETAILS'''
  cta1_url = '''https://www.india.ford.com/#/overlay/content/ford/in/en_in/site-wide-content/overlays/forms/profile-update-form.html?req_firstName=<%${user['FirstName']}%>&req_lastName=<%${user['LastName']}%>&req_mobileNumber=<%${user.CustomAttribute['Mobile_Phone']}%>&req_EmailID=<%${user.CustomAttribute['RealEmail']}%>&req_BuildingNo=<%${user.CustomAttribute['Address_1']}%>&req_StreetRoad=<%${user.CustomAttribute['Address_2']}%>&req_Area=<%${user.CustomAttribute['Area']}%>&req_Landmark=<%${user.CustomAttribute['Landmark']}%>&req_city=<%${user.CustomAttribute['City']}%>&req_State=<%${user.CustomAttribute['State']}%>&req_postCode=<%${user.CustomAttribute['Post_Code']}%>'''
  cta1_link_name = '''profile_update'''
  icon = '''th_edm2_ownerprofile_20160801'''

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
  icon4_url='''https://partscalculator.fordind.com:1443/Fill_Field?extcmp=hp_eb_nav/'''
  icon4_link_name = '''parts_calculator'''
  icon4_image='''in_svc_parts_20160801'''
    
[[module]] #Footer IN Social
path='email_modules/footer/in/social'
color='white'

[[module]] #Footer IN Online
path='email_modules/footer/in/online'
color='white'
+++