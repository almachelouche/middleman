+++
markets = ["in"]
title = '''IN Repurchase 005 EcoSport ICA'''

[[module]]
path='email_modules/preheader'
color='''white'''

	preheader = '''We noticed you've been driving your Ford <%${user.CustomAttribute['Model']}%> for a while now and might be thinking about purchasing a new Ford.'''

[[module]] #Header Logo
path='email_modules/header/logodesktop'
color='white_pb'

  image = '''white_pb'''
  url_link = '''https://www.india.ford.com/'''

[[module]] #Banner Image
path = '''email_modules/image/banner'''
color = '''white'''

  image = '''in_edm5_EcoSport_ICA_20170125'''
    url_link='''https://www.india.ford.com/suvs/ecosport/features/platinum-edition/'''

[[module]]
path='email_modules/spacer/default'
color='white'

	height="30"

[[module]]
path='email_modules/singles/title'
color='''white'''
	
	title = '''Meet the EcoSport Platinum'''

[[module]]
path='email_modules/spacer/default'
color='white'

	height="30"

[[module]]
path='email_modules/singles/copy'
color='''white'''
	
	copy = '''We noticed you've been driving your Ford <%${user.CustomAttribute['Model']}%> for a while now and might be thinking about purchasing a new Ford.<br /><br />We believe life shouldn't be limited to the weekends. That's why we bring you the Ford EcoSport Platinum with more style, richer features and bigger alloy wheels that make it the perfect companion for your quest to 'live it up!'*<br /><br />Check out the Platinum Edition today, because we want you to live more every day.'''
    
[[module]]
path='email_modules/spacer/default'
color='white'

	height="30"    
    
[[module]]
path='email_modules/singles/2ctablocksideoutline'
color='''white'''    
	cta1_text = '''&nbsp;&nbsp;LOCATE A DEALER&nbsp;&nbsp;'''
	cta1_url = '''https://www.india.ford.com/locate-dealer/'''
	cta1_link_name = '''locate_dealer'''
	cta2_text = '''BOOK A TEST DRIVE'''
	cta2_url = '''https://www.india.ford.com/suvs/ecosport/features/platinum-edition/#overlay/content/ford/in/en_in/site-wide-content/overlays/forms/test-drive-ecosport.html'''
	cta2_link_name = '''test_drive'''
  
[[module]]
path='email_modules/spacer/default'
color='white'

	height="30"  
  
[[module]]
path='email_modules/singles/icon'
color='''white'''
	
	icon = '''in_edm5_livechat_blue_20161018'''

[[module]] #Cover 07
path='email_modules/cover/02'
color='''white'''

  title = '''Ford Live Chat'''
  copy = '''Have a question now? We've got a team of advisors from 9am to 8pm on Ford chat, for you.'''
  cta1_text = '''CHAT NOW'''
  cta1_url = '''https://ford-livechat.s3ae.com/in/chat.php?a=1e4b8&intgroup=c3VwcG9ydA__&hg=Pw__&hcgs=MQ__&htgs=MQ__'''
  cta1_link_name = '''live_chat'''

[[module]]
path='email_modules/singles/icon'
color='''white'''
	
	icon = '''th_edm2_ownerprofile_20160801'''
    
[[module]]
path='email_modules/spacer/default'
color='white'

	height="30"

[[module]]
path='email_modules/singles/title'
color='''white'''
	
	title = '''Meet the EcoSport Platinum'''
    
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
	cta2_url = '''https://www.india.ford.com/surprisingly-affordable/#overlay/content/ford/in/en_in/site-wide-content/overlays/form-overlay/login.html/'''
	cta2_link_name = '''owner_login'''
    cta1_icon='''more'''

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

[[module]] #Footer Disclaimer
path='email_modules/footer/disclaimer'
color='white'

  text = '''*Terms and conditions apply. Images are for visual representation only. Accessories may not be a part of standard equipment. Features may differ by variants. Colors are indicative only and may vary in actual. Always consult an authorized Ford dealer for the latest information with respect to accessories, features, specification, prices, optional equipment and availability before deciding to place an order. Operating DVD player and Navigation System while driving can distract your attention and is prohibited by laws. Ford does not recommend playing DVD player and change navigation settings while driving. Stop the vehicle in a safe and legal manner before attempting these operations. If the speed of the vehicle exceeds 8 km/hr the video will not play. Navigation destination function will not work while the vehicle is running. Please contact Ford dealership or Ford customer relationship center for further details.'''

[[module]] #Footer IN Social
path='email_modules/footer/in/social'
color='white'

[[module]] #Footer IN Online
path='email_modules/footer/in/online'
color='white'


+++