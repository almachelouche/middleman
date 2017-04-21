+++
markets = ["in"]
title = '''IN Enews 003 4yr+'''

[[module]]
path='email_modules/preheader'
color='''white'''

	preheader = '''Welcome to the Insider from Ford. In this newsletter, see the latest promotions and tips tailored just for you. We hope they will inspire you to Go Further.'''

[[module]] #Header Logo
path='email_modules/header/logodesktop'
color='white_pb'

  image = '''white_pb'''
  url_link = '''https://www.india.ford.com/'''

[[module]] #Header eNews
path='email_modules/header/enews'
color='black'

  title = '''Insider'''
  date = '''04 May 2017'''
  copy = '''IN THIS ISSUE:<br />Ford Safety | Figo & Aspire Sports | The Unstoppable Endeavour<br />And more'''

[[module]] # eNews Top Story
path='email_modules/custom/enews_topstory'
color='white_pb'

title = ''''''
  copy = '''Welcome to the Insider from Ford. In this newsletter, see the latest promotions and tips tailored just for you. We hope they will inspire you to Go Further.<br /><br /><span style="color:#000001; font-size: 24px; font-family: 'Arial','Helvetica','Sans-Serif'; line-height: 30px; font-weight: normal; font-style: regular;">Your safety. Our priority.</span><br /><br />Nothing is more important to us than your safety. That's why Ford go further to design high-quality vehicles and smart technology that keep you more secure and in control - in all kinds of real-world conditions. Want to see how? Just click below.  '''
  cta1_text = '''EXPLORE SAFETY'''
  cta1_url = '''https://www.india.ford.com/safety/'''
  cta1_link_name = '''ford_safety'''
  cta2_text = ''''''
  cta2_url = ''''''
  cta2_link_name = ''''''
  cta1_icon = '''more'''

[[module]] #Banner Image
path='email_modules/image/banner'
color='white'

  image='''in_edm6_airbag_20170420'''
  url_link='''https://www.india.ford.com/safety/'''
  url_link_name='''ford_safety_image'''

[[module]] #Split 02
path='email_modules/split/02'
color='lightblue'

  title = '''New Sports Editions'''
  copy = '''Introducing the new Ford Aspire Sport and Ford Figo Sport. Both exciting models feature a unique 'Sports Suspension', refreshed colour schemes, and a host of safety features. '''
  cta1_text = '''EXPLORE FIGO SPORT'''
  cta1_url = '''https://www.india.ford.com/cars/figo/features/sports-edition/'''
  cta1_link_name = '''figo_svp'''
  cta2_text = '''EXPLORE ASPIRE SPORT'''
  cta2_url = '''https://www.india.ford.com/cars/aspire/features/sports-edition/'''
  cta2_link_name = '''aspire_svp'''
  cta1_icon = '''more'''
  image = '''in_edm6_svp_20170421'''

[[module]] #Split 01
path='email_modules/split/01'
color='darkblue'

  title = '''Unstoppable Endeavour'''
  copy = '''The All-New Endeavour has conquered deserts, mountains and even podiums. Take a test drive to find out why this SUV's list of achievements never stops growing.'''
  cta1_text = '''WATCH NOW'''
  cta1_url = '''https://www.youtube.com/watch?v=UIB_qMtTU54'''
  cta1_link_name = '''endeavour_video'''
  cta1_icon = '''more'''
  cta2_text = '''BOOK A TEST DRIVE'''
  cta2_url = '''https://www.india.ford.com/suvs/endeavour/#overlay/content/ford/in/en_in/site-wide-content/overlays/forms/test-drive-endeavour.html?campaign=ENFWTDC&intModel=Endeavour&modelCode=EN/'''
  cta2_link_name = '''endeavour_test_drive'''
  image = '''in_edm6_endeavour_video_20170330'''

[[module]] #Split 02
path='email_modules/split/02'
color='green'

 title = '''Mustang sets hearts racing'''
  copy = '''Re-live the excitement of Mustang's Grand Tour of India. Icon meets icon as Mustang covers 12,000km and visits some of our Republic's most famous landmarks. '''
  cta1_text = '''WATCH NOW'''
  cta1_url = '''https://www.youtube.com/watch?v=HKLV0i5CQpo'''
  cta1_link_name = '''mustang_tour'''
  cta1_icon = '''play'''
  image = '''in_edm6_mustang_tour_20170406'''

[[module]] #Split 01
path='email_modules/split/01'
color='lightblue'

  title = '''Ford's Service Price Promise'''
  copy = '''You've heard about Ford's Service Price Promise. Now calculate the cost of your service even before it reaches the dealership. Follow Mr. Doodles as he takes you through the simple process.'''
  cta1_text = '''WATCH NOW'''
  cta1_url = '''https://www.youtube.com/watch?v=xxEWETfxOao'''
  cta1_link_name = '''spp_sms'''
  cta1_icon = '''play'''
  image = '''in_edm6_service_sms_20170330'''

[[module]] #Split 02
path='email_modules/split/02'
color='darkblue'

   title = '''Project Sujal'''
  copy = '''Scarcity of clean drinking water is one of the biggest issues facing children in rural India. Discover what Ford is doing to ensure these communities have access to life's most vital resource.'''
  cta1_text = '''WATCH NOW'''
  cta1_url = '''https://youtu.be/1pnin7wzbes'''
  cta1_link_name = '''sujal'''
  cta1_icon = '''play'''
  image = '''in_edm6_sujal_20170330'''

[[module]]
path='email_modules/spacer/default'
color='white'

	height="30"

[[module]]
path='email_modules/singles/title'
color='''white'''
	
	title = '''My Ford Profile'''
    
[[module]]
path='email_modules/spacer/default'
color='white'

	height="30"

[[module]]
path='email_modules/singles/copy'
color='''white'''
	
	copy = '''Name&#58; <%${user['FirstName']}%> <%${user['LastName']}%><br />Email&#58; <%${user.CustomAttribute['RealEmail']}%><br />Phone&#58; <%${user.CustomAttribute['Mobile_Phone']}%><br />Address&#58; <%${user.CustomAttribute['Address_1']}%> <%${user.CustomAttribute['Address_2']}%><br /><br />Anything changed?'''
    
[[module]]
path='email_modules/spacer/default'
color='white'

	height="30"        
  
[[module]]
path='email_modules/singles/2textcta'
color='''white'''
	
	cta1_text = '''UPDATE DETAILS'''
	cta1_url = '''https://www.india.ford.com/#/overlay/content/ford/in/en_in/site-wide-content/overlays/forms/profile-update-form.html?req_firstName=<%${user['FirstName']}%>&req_lastName=<%${user['LastName']}%>&req_mobileNumber=<%${user.CustomAttribute['Mobile_Phone']}%>&req_EmailID=<%${user.CustomAttribute['RealEmail']}%>&req_BuildingNo=<%${user.CustomAttribute['Address_1']}%>&req_StreetRoad=<%${user.CustomAttribute['Address_2']}%>&req_Area=<%${user.CustomAttribute['Area']}%>&req_Landmark=<%${user.CustomAttribute['Landmark']}%>&req_city=<%${user.CustomAttribute['City']}%>&req_State=<%${user.CustomAttribute['State']}%>&req_postCode=<%${user.CustomAttribute['Post_Code']}%>/'''
	cta1_link_name = '''profile_update'''
	cta2_text = '''VISIT OWNER SITE'''
	cta2_url = '''https://www.india.ford.com/owner/dashboard/'''
	cta2_link_name = '''owner_dashboard'''
    cta1_icon='''more'''


[[module]] #Footer IN Social
path='email_modules/footer/in/social'
color='white'

[[module]] #Footer Disclaimer
path='email_modules/footer/disclaimer'
color='white'

  text='''*Images and illustrations are for information purposes and are indicative only.'''

[[module]] #Footer IN Online
path='email_modules/footer/in/online'
color='white'
+++