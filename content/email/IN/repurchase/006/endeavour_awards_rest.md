+++
markets = ["in"]
title = '''IN Repurchase 006 rest'''
		
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
	
	title = '''Ready for your new drive? All-New Endeavour is here.'''

[[module]]
path='email_modules/spacer/default'
color='white'

	height="30"

[[module]]
path='email_modules/singles/copy'
color='''white'''
	
	copy = '''We noticed you've been driving your Ford <%${user.CustomAttribute['Model']}%> for a while now and might be thinking about purchasing a new Ford. <br /><br />We believe in engineering vehicles that can conquer any terrain - like the All-New Endeavour. This year, Endeavour conquered the podiums too, winning India's most prestigious vehicle awards. <br /><br />Check out Endeavour today. '''

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
	cta2_url = '''https://www.india.ford.com/suvs/endeavour/?intcmp=in-hp-bb-xt-namplateexp-fordendeavour-en#overlay/content/ford/in/en_in/site-wide-content/overlays/forms/test-drive-endeavour.html?campaign=ENFWTDC&intModel=Endeavour&modelCode=EN/'''
	cta2_link_name = '''test_drive'''

[[module]]
path='email_modules/spacer/default'
color='white'

	height="30"

[[module]] #Custom 01
path='email_modules/custom/3columntitle3icons'
color='white'

	title = '''Smart. Safe. Totally Capable.'''
	icon1 = '''au_edm5_sync2_20161107'''
	text1 = '''<span style="font-weight:bold">SYNC<sup>&#174;</sup>3</span><br />New and improved voice-activated technology.'''
	icon2 = '''au_edm5_tms_20161013'''
	text2 = '''<span style="font-weight:bold">TMS</span><br />Tackle any terrain with the Terrain Management System.'''
	icon3 = '''in_edm5_airbags_20161122'''
	text3 = '''<span style="font-weight:bold">7 Airbags</span><br />360 degrees of protection for the whole family.'''
	
[[module]]
path='email_modules/singles/ctablock'
color='''white'''
	
	cta1_text = '''EXPLORE FEATURES'''
	cta1_url = '''https://www.india.ford.com/suvs/endeavour/'''
	cta1_link_name = '''endeavour_features'''	

[[module]] #Banner Image No Link
path = '''email_modules/image/banner_nolink'''
color = '''white'''
	
	image = '''in_edm5_edn_model_compare_20170619'''

[[module]]
path='email_modules/spacer/default'
color='white'

	height="30"
	
 [[module]]
path='email_modules/singles/title'
color='''white'''
	
	title = '''It's going to be a tough choice''' 
		
[[module]]
path='email_modules/spacer/default'
color='white'

	height="30"
		
[[module]]
path='email_modules/singles/ctablock'
color='''white'''
	
	cta1_text = '''MODEL COMPARE'''
	cta1_url = '''https://www.india.ford.com/suvs/endeavour/endeavour-modelcompare/'''
	cta1_link_name = '''model_compare'''	

[[module]]
path='email_modules/spacer/default'
color='white'

	height="30"

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
	icon5_url='''tel:18004199000'''
	icon5_image='''in_lmc_no_20161018'''
	icon5_link_name = '''tel_toll_free'''

[[module]] #Footer IN Social
path='email_modules/footer/in/social'
color='white'

[[module]] #Footer Disclaimer
path='email_modules/footer/disclaimer'
color='white'

  text = '''*Terms and conditions apply.<br /><br />1. As per awards given by leading Indian auto magazines and television networks in the year 2016-17. The model shown in the letter/mailer is the Titanium 3.2L Diesel variant. Colors are indicative only. Features and specifications may vary from model to model. Features mentioned and Accessories shown may not be part of standard fitment. Before placing, an order and booking the vehicle always consult a Ford authorized dealer for the latest information with respect to features, specifications, price, optional equipment and availability of the vehicle. Ford India Private Limited ("Ford") reserves the right, subject to all applicable laws, at any time, at its discretion, and without notice, to discontinue or change the features, designs, materials, colors and other specifications and the prices of its products. <br /><br />2. 7 Airbags are available in Endeavour 3.2L Titanium AT variant. Dual airbags are standard on all Ford vehicles. Airbags does not guarantee safety. The airbag will deploy during significant lateral collisions. The airbag will not deploy in minor lateral and frontal collisions, rear collisions, or overturns.'''

[[module]] #Footer IN Online
path='email_modules/footer/in/online'
color='white'


+++