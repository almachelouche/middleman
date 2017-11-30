+++
markets = ["in"]
title = '''IN Repurchase 007 All'''

[[module]]
path='email_modules/preheader'
color='''white'''

	preheader = '''We noticed you've been driving your Ford <%${user.CustomAttribute['Model']}%> for a while now and might be thinking about purchasing a new Ford.'''

[[module]] #Header Logo
path='email_modules/header/logodesktop'
color='white_pb'

	image = '''white_pb'''
	url_link = '''https://www.india.ford.com/'''

[[module]]
path = '''email_modules/image/bannerGif'''
color = '''white'''

	image = '''in_edm5_newecosport_20171130'''
	url_link='''https://www.india.ford.com/suvs/ecosport/'''
	url_link_name='''banner_gif'''
    
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

[[module]]
path='email_modules/singles/title'
color='''white'''

	title = '''The All-New EcoSport is on your side'''

[[module]]
path='email_modules/spacer/default'
color='white'

	height="30"

[[module]]
path='email_modules/singles/copy'
color='''white'''

	copy = '''We noticed you've been driving your Ford <%${user.CustomAttribute['Model']}%> for a while now and might be thinking about purchasing a new Ford. <br /><br />The All-New EcoSport makes every drive a fun drive, thanks to its powerful new engine, sporty design, and smart technology. Take it for a spin and discover why EcoSport is always on your side.'''

[[module]]
path='email_modules/spacer/default'
color='white'

	height="30"
    
[[module]] # Custom Car 2 Column
path='email_modules/custom/2column_car'
color='black'

	image1 = '''in_edm5_sync3_20171130'''
	cta1_text = '''SYNC&#174; 3'''
	cta1_url = '''https://www.india.ford.com/suvs/ecosport/features/technology/'''
	cta1_link_name = '''sync'''
	cta1_icon = '''more'''
	image2 = '''in_edm5_engine_20171130'''
	cta2_text = '''123PS (90.5kW) Engine'''
	cta2_url = '''https://www.india.ford.com/1-5l-petrol-engine/'''
	cta2_link_name = '''engine'''
	cta2_icon = '''more'''    

[[module]] # Custom Car 2 Column
path='email_modules/custom/2column_car'
color='black'

	image1 = '''in_edm5_6speed_20171130'''
	cta1_text = '''6-Speed AT with Paddle Shift'''
	cta1_url = '''https://www.india.ford.com/suvs/ecosport/features/fun/'''
	cta1_link_name = '''6speed'''
	cta1_icon = '''more'''
	image2 = '''in_edm5_dtrl_20171130'''
	cta2_text = '''Projector Headlamps with DTRL's'''
	cta2_url = '''https://www.india.ford.com/suvs/ecosport/features/style/'''
	cta2_link_name = '''headlamps_dtrl'''
	cta2_icon = '''more'''

[[module]] #Banner Image No Link
path = '''email_modules/image/banner_nolink'''
color = '''white'''

	image = '''in_edm5_newecosport_model_compare_20171130'''

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
	cta1_url = ''''''
	cta1_link_name = '''model_compare'''

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
	icon5_url='''tel:18004199000'''
	icon5_image='''in_lmc_no_20161018'''
	icon5_link_name = '''tel_toll_free'''

[[module]] #Footer IN Social
path='email_modules/footer/in/social'
color='white'

[[module]] #Footer Disclaimer
path='email_modules/footer/disclaimer'
color='white'

  text = '''*DTRL refers to Daytime Running Lights.'''

[[module]] #Footer IN Online
path='email_modules/footer/in/online'
color='white'


+++