+++
markets = ["in"]
title = '''IN Repurchase 006 Endeavour'''

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
path='email_modules/image/banner'
color='white'

  image = '''in_edm5_endeavour_awards_20170223'''
    url_link='''https://www.india.ford.com/suvs/endeavour/'''
	url_link_name='''endeavour'''

[[module]]
path='email_modules/spacer/default'
color='white'

	height="30"

[[module]]
path='email_modules/singles/title'
color='''white'''
	
	title = '''Meet the new, award-winning Endeavour'''

[[module]]
path='email_modules/spacer/default'
color='white'

	height="30"

[[module]]
path='email_modules/singles/copy'
color='''white'''
	
	copy = '''We wanted to say 'thank you!' for being an Endeavour owner. We hope you continue to love your SUV as much as we enjoy having you as part of our Ford family. <br /><br />But if you're already thinking about an upgrade, we invite you to experience the All-New Endeavour. <br /><br />Not only is Endeavour smarter and more capable than ever, it also conquered the podiums this year, winning India's most prestigious vehicle awards.<br /><br />Check out the All-New Endeavour today, because we want you to drive a winner. '''
    
[[module]] #Custom 3 Icon Text
path='email_modules/custom/3icon_text'
color='white'

  title = ''''''
  icon1 = '''au_edm5_sync2_20161107'''
  text1 = '''<span style="font-weight:bold">SYNC&#174;3</span>'''
  icon2 = '''au_edm5_tms_20161013'''
  text2 = '''<span style="font-weight:bold">Terrain Management System</span>'''
  icon3 = '''in_edm5_airbags_20161122'''
  text3 = '''<span style="font-weight:bold">7 Airbags</span>'''
    
[[module]]
path='email_modules/singles/2ctablocksideoutline'
color='''white'''    
	cta1_text = '''&nbsp;&nbsp;LOCATE A DEALER&nbsp;&nbsp;'''
	cta1_url = '''https://www.india.ford.com/locate-dealer/'''
	cta1_link_name = '''locate_dealer'''
	cta2_text = '''BOOK A TEST DRIVE'''
	cta2_url = '''https://www.india.ford.com/suvs/endeavour/?intcmp=in-hp-bb-xt-namplateexp-fordendeavour-en#overlay/content/ford/in/en_in/site-wide-content/overlays/forms/test-drive-endeavour.html?campaign=ENFWTDC&intModel=Endeavour&modelCode=EN/'''
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
	cta2_url = '''https://www.india.ford.com/owner/dashboard/#overlay/content/ford/in/en_in/site-wide-content/overlays/form-overlay/login.html/'''
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

[[module]] #Footer IN Social
path='email_modules/footer/in/social'
color='white'

[[module]] #Footer Disclaimer
path='email_modules/footer/disclaimer'
color='white'

  text = '''*As per awards given by leading Indian auto magazines and television networks in the year 2016-17. The model shown in the letter/mailer is the Titanium 3.2L Diesel variant. Colors are indicative only. Features and specifications may vary from model to model. Features mentioned and Accessories shown may not be part of standard fitment. Before placing, an order and booking the vehicle always consult a Ford authorized dealer for the latest information with respect to features, specifications, price, optional equipment and availability of the vehicle. Ford India Private Limited ("Ford") reserves the right, subject to all applicable laws, at any time, at its discretion, and without notice, to discontinue or change the features, designs, materials, colors and other specifications and the prices of its products. You can reach us on 1800-419-9000 for any product information or reach our Customer Care on 1800-425-2500. visit: <a href="https://www.india.ford.com/suvs/endeavour/" style="text-decoration:underline; color:#2D96CD;" >www.india.ford.com/suvs/endeavour</a> '''

[[module]] #Footer IN Online
path='email_modules/footer/in/online'
color='white'


+++