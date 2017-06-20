+++
markets = ["in"]
title = '''IN Repurchase offer 001'''
draft = true

[[module]]
path='email_modules/preheader'
color='''nothing'''

	preheader = '''We noticed you've been driving your Ford <%${user.CustomAttribute['Selected_Vehicle']}%> for a while now and might be thinking about purchasing a new Ford.'''

[[module]] #Header Logo
path='email_modules/header/logo'
color='white'

	image = '''white'''
	url_link = '''https://www.india.ford.com'''

[[module]]
path='email_modules/cover/01'

color='''white'''
title='''Top-end cars. All-new prices.'''
copy='''We noticed you've been driving your Ford <%${user.CustomAttribute['Selected_Vehicle']}%> for a while now and might be thinking about purchasing a new Ford.<br /><br />At Ford, we look out for family. That's why we offer a range of <span style="font-weight:bold">fully loaded cars at all-new starting prices</span>. The Next-Gen Ford Figo Titanium and Ford Aspire Titanium both deliver superior peace of mind with best-in-class 6 airbags, and first-in-class Ford MyKey<sup>®</sup>.'''

[[module]]
path='email_modules/dual/04'
color='white'

	title1=''''''
	copy1='''<span style="font-weight:bold;">Next-Gen Ford Figo Titanium</span><br /><br />&#8377;5.66 Lakh (Petrol)<br />&#8377;6.54 Lakh (Diesel)'''
	cta1a_text=''''''
	cta1a_url=''''''
	cta1a_link_name = ''''''
	cta1b_text=''''''
	cta1b_url=''''''
	cta1b_link_name = ''''''
	cta1c_text=''''''
	cta1c_url=''''''
	cta1c_link_name = ''''''
	icon1=''''''
	title2=''''''
	copy2='''<span style="font-weight:bold;">Ford Aspire Titanium</span><br /><br />&#8377;5.99 Lakh (Petrol)<br />&#8377;7.09 Lakh (Diesel)'''
	cta2a_text=''''''
	cta2a_url=''''''
	cta2a_link_name = ''''''
	cta2b_text=''''''
	cta2b_url=''''''
	cta2b_link_name = ''''''
	cta2c_text=''''''
	cta2c_url=''''''
	cta2c_link_name = ''''''
	icon2=''''''

[[module]]
path='email_modules/cover/02'
color='''white'''

	title=''''''
	copy='''Why not book a test drive? Click below to locate a nearby dealer today.'''
	cta1_text='''FIND A DEALER'''
	cta1_url='''http://www.india.ford.com/locate-dealer?emailid=EDM_<%${user.CustomAttribute['DMCDATE']}%>_APMKTC4L_<%${user.CustomAttribute['DMCCAMPAIGN']}%>_locate-dealer'''

[[module]] # Custom Car 2 Column
path='email_modules/custom/2column_car'
color='black'

	image1 = '''in_edm5_2vehicle_F_Figo_20160818'''
	cta1_text = '''Explore Ford Figo'''
	cta1_url = '''http://www.india.ford.com/cars/figo'''
	cta1_icon = '''more'''
	image2 = '''in_edm5_2vehicle_F_Aspire_20160818'''
	cta2_text = '''Explore Ford Aspire'''
	cta2_url = '''http://www.india.ford.com/cars/aspire'''
	cta2_icon = '''more'''

[[module]] #Cover 05
path='email_modules/cover/02'
color='''lightblue'''

	title = '''Ford Live Chat'''
	copy = '''Ford Live Chat is now online! Get real-time answers from our team of Ford Advisors between 9am to 8pm. '''
	cta1_text = '''START CHATTING'''
	cta1_url = '''https://ford-livechat.s3ae.com/in/chat.php?a=1e4b8&intgroup=c3VwcG9ydA__&hg=Pw__&hcgs=MQ__&htgs=MQ__'''
	cta1_link_name = ''''''
	icon = '''live_chat'''

[[module]] #Cover 07
path='email_modules/cover/02'
color='''white'''

	title = '''Your Profile Details'''
	copy = '''Name&#58; <%${user['FirstName']}%> <%${user['LastName']}%><br />Email&#58; <%${user.CustomAttribute['RealEmail']}%><br />Phone&#58; <%${user.CustomAttribute['Mobile_Phone']}%><br />Address&#58; <%${user.CustomAttribute['Address_1']}%> <%${user.CustomAttribute['Address_2']}%><br /><br />Anything changed?'''
	cta1_text = '''UPDATE YOUR DETAILS'''
	cta1_url = '''https://www.india.ford.com/profile-update-form?fbdata=req_firstName=<% ${user['FirstName']} %>||req_lastName=<% ${user['LastName']} %>||req_mobileNumber=<%${user.CustomAttribute['Mobile_Phone']}%>||req_EmailID=<% ${user.CustomAttribute['RealEmail']} %>||req_BuildingNo=<% ${user.CustomAttribute['Address_1']} %>||req_StreetRoad=<%${user.CustomAttribute['Address_2']}%>||req_Area=<% ${user.CustomAttribute['Area']} %>||req_Landmark=<% ${user.CustomAttribute['Landmark']} %>||req_city=<% ${user.CustomAttribute['City']} %>||req_State=<% ${user.CustomAttribute['State']} %>||req_postCode=<% ${user.CustomAttribute['Post_Code']} %>'''
	cta1_link_name = ''''''

[[module]]
path='email_modules/footer/5icons'
color='white'

	icon1_url='''http://www.india.ford.com/locate-dealer?emailid=EDM_<%${user.CustomAttribute['DMCDATE']}%>_APMKTC4L_<%${user.CustomAttribute['DMCCAMPAIGN']}%>_locate-dealer'''
	icon1_image='''in_dealers_20160414'''
	icon1_link_name = ''''''
	icon2_url='''http://www/india.ford.com/cars/aspire'''
	icon2_image='''in_ford_credit_20160401'''
	icon2_link_name = ''''''
	icon3_url='''http://www.india.ford.com/buying/ford-assured?emailid=EDM_<%${user.CustomAttribute['DMCDATE']}%>_APMKTC4L_<%${user.CustomAttribute['DMCCAMPAIGN']}%>_Ford-Assured'''
	icon3_image='''in_ford_assured_20160401'''
	icon3_link_name = ''''''
	icon4_url='''tel:1800-425-2500'''
	icon4_image='''in_customer_care_number_20160401'''
	icon4_link_name = ''''''
	icon5_url='''tel:1800-209-7400'''
	icon5_image='''in_rsa_no_20160615'''
	icon5_link_name = ''''''
		
[[module]] #Footer IN Social
path='email_modules/footer/in/social'
color='white'

[[module]] #Footer Disclaimer
path='email_modules/footer/disclaimer'
color='white'

	text='''Terms & conditions apply.<br /><br />[1] Prices shown are ex-showroom Delhi & have been truncated to 2 decimal points. Ex-showroom prices may differ by city.<br /><br />[2] Starting price mentioned is for Ford Aspire Petrol Ambiente variant & Next-Gen Ford Figo Petrol Base variant.<br /><br />[3] 6 Airbags and Ford MyKey<sup>®</sup> are available on Ford Aspire & Next-Gen Ford Figo Titanium+ variants only. <br /><br />[4] Colours are indicative only and may vary due to printing constraints. For more information please contact your nearest Ford dealer.'''

[[module]] #Footer IN Online
path='email_modules/footer/in/online'
color='white'
+++