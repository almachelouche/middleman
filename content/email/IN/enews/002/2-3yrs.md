+++
markets = ["in"]
title = '''IN Enews 002 2-3 Years'''

[[module]]
path='email_modules/preheader'
color='''white'''

	preheader = '''Welcome to the Insider from Ford. In this newsletter, see the latest promotions and tips tailored just for you. It will inspire you to Go Further.'''

[[module]] #Header Logo
path='email_modules/header/logodesktop'
color='white_pb'

	image = '''white_pb'''
	url_link = '''https://www.india.ford.com/'''

[[module]] #Header eNews
path='email_modules/header/enews'
color='black'

	title = '''Insider'''
	date = '''31 Jan 2017'''
	copy = '''IN THIS ISSUE:<br />The Trip | The Pocket Mustang Experience | Service Price Promise | Parts Calculator | <br />And more'''

[[module]] # eNews Top Story
path='email_modules/custom/enews_topstory'
color='white_pb'

title = ''''''
	copy = '''Welcome to the Insider from Ford. In this newsletter, see the latest promotions and tips tailored just for you. It will inspire you to Go Further.<br /><br /><span style="color:#000001; font-size: 24px; font-family: 'Arial','Helvetica','Sans-Serif'; line-height: 30px; font-weight: normal; font-style: normal;">To Thailand in an EcoSport</span><br /><br />Ten episodes, four friends and one amazing EcoSport on a journey of a lifetime.	Gear up to witness Lisa Haydon and the girls take on an epic road trip from India to Thailand in <span style="font-weight:bold">The Trip</span>. Will they make it? Tune in and watch the drama unfold.'''
	cta1_text = '''WATCH NOW'''
	cta1_url = '''http://bit.ly/2kartSg'''
	cta1_link_name = '''the_trip'''
	cta2_text = ''''''
	cta2_url = ''''''
	cta2_link_name = ''''''
	cta1_icon = '''play'''

[[module]] #Banner Image
path='email_modules/image/banner'
color='white'

	image='''in_edm6_ecosport_trip_20161223'''
	url_link='''http://bit.ly/2kartSg'''
	url_link_name='''the_trip_image'''

	[[module]] #Split 02
path='email_modules/split/02'
color='darkblue'

	title = '''The Pocket Mustang'''
	copy = '''Turn your mobile phone into a scale-model of the Mustang and maneuver it on any surface. Watch your pocket car skills get recreated with a real Mustang on a real track. Share the video and challenge your friends.'''
	cta1_text = '''EXPERIENCE NOW'''
	cta1_url = '''http://pocketmustang.india.ford.com/en/'''
	cta1_link_name = '''pocket_mustang'''
	cta1_icon = '''more'''
	image = '''in_edm6_pocket_mustang_20170106'''

[[module]] #Split 01
path='email_modules/split/01'
color='lightblue'

	title = '''Service Price Promise / <br />Parts Calculator'''
	copy = '''No surprises! Know exactly how much you'll pay for a service and spare parts, even before you visit a Ford service center. '''
	cta1_text = '''Service Price Promise'''
	cta1_url = '''https://www.fordservicepricepromise.com/?extcmp=serca_101115_105328_fordind/'''
	cta1_link_name = '''price_calculator'''
	cta2_text = '''Service Parts Calculator'''
	cta2_url = '''https://partscalculator.fordind.com:1443/Fill_Field?extcmp=hp_eb_nav/'''
	cta2_link_name = '''parts_calculator'''
	cta1_icon = '''more'''
	image = '''in_edm6_SvcScript_20170106'''

[[module]] #Split 02
path='email_modules/split/02'
color='green'

	title = '''Pothole Pain Points'''
	copy = '''Deep potholes are a big problem even for the deepest of pockets. But fast action can help save costly repaires down the road. Know the areas you'll need to examine, now.'''
	cta1_text = '''LEARN MORE'''
	cta1_url = '''https://social.ford.com/en_US/story/features/wheel/pothole-pain-points.html'''
	cta1_link_name = '''pothole_pain_points'''
	cta1_icon = '''more'''
	image = '''in_edm6_PainPoints_20161101'''

[[module]] # Owner App Image Right
path='email_modules/custom/ownerapp_imgr'
color='black'

	title = '''Ford Owners App'''
	text1 = '''Owning a Ford has never been easier, thanks to the Ford Owners App:'''
	text2 = '''<br />&nbsp;&#8226;&nbsp;&nbsp;&nbsp;Use the service checklist<br />&nbsp;&#8226;&nbsp;&nbsp;&nbsp;Access Roadside Assistance<br />&nbsp;&#8226;&nbsp;&nbsp;&nbsp;Watch "how-to" videos<br />&nbsp;&#8226;&nbsp;&nbsp;&nbsp;Find a dealer near you'''
	cta1_text = '''iOS'''
	cta1_url = '''https://itunes.apple.com/in/app/ford-owners/id990342351?mt=8/'''
	cta1_link_name = '''oa_ios'''
	cta2_text = '''Android'''
	cta2_url = '''https://play.google.com/store/apps/details?id=com.ford.fordowners&hl=en/'''
	cta2_link_name = '''oa_android'''
	image = '''owner_app_20160328'''

[[module]] #Cover 07
path='email_modules/cover/02'
color='''white'''

	title = '''Your Profile Details'''
	copy = '''Name&#58; <%${user['FirstName']}%> <%${user['LastName']}%><br />Email&#58; <%${user.CustomAttribute['RealEmail']}%><br />Phone&#58; <%${user.CustomAttribute['Mobile_Phone']}%><br />Address&#58; <%${user.CustomAttribute['Address_1']}%><br /><%${user.CustomAttribute['Address_2']}%><br /><br />Anything changed?'''
	cta1_text = '''UPDATE YOUR DETAILS'''
	cta1_url = '''https://www.india.ford.com/#/overlay/content/ford/in/en_in/site-wide-content/overlays/forms/profile-update-form.html?req_firstName=<%${user['FirstName']}%>&req_lastName=<%${user['LastName']}%>&req_mobileNumber=<%${user.CustomAttribute['Mobile_Phone']}%>&req_EmailID=<%${user.CustomAttribute['RealEmail']}%>&req_BuildingNo=<%${user.CustomAttribute['Address_1']}%>&req_StreetRoad=<%${user.CustomAttribute['Address_2']}%>&req_Area=<%${user.CustomAttribute['Area']}%>&req_Landmark=<%${user.CustomAttribute['Landmark']}%>&req_city=<%${user.CustomAttribute['City']}%>&req_State=<%${user.CustomAttribute['State']}%>&req_postCode=<%${user.CustomAttribute['Post_Code']}%>'''
	cta1_link_name = '''owner_log_in'''

[[module]] #Footer IN Social
path='email_modules/footer/in/social'
color='white'

[[module]] #Footer IN Online
path='email_modules/footer/in/online'
color='white'
+++