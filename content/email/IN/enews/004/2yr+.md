+++
markets = ["in"]
title = '''IN Enews 004 2yr+'''

[[module]]
path='email_modules/preheader'
color='''white'''

	preheader = ''''''

[[module]] #Header Logo
path='email_modules/header/logodesktop'
color='white_pb'

	image = '''white_pb'''
	url_link = '''https://www.india.ford.com/'''

[[module]] #Header eNews
path='email_modules/header/enews'
color='black'

	title = '''Insider'''
	date = '''August 2017'''
	copy = '''IN THIS ISSUE:<br /> |  |  | And more'''

[[module]] # eNews Top Story
path='email_modules/custom/enews_topstory'
color='white_pb'

title = ''''''
	copy = '''This is latest edition of the Insider from Ford, where you can check out some of the latest happenings at Ford and smart servicing tips tailored just for you. We hope this continues to inspire you to Go Further!<br /><br /><span style="color:#000001; font-size: 24px; font-family: 'Arial','Helvetica','Sans-Serif'; line-height: 30px; font-weight: normal; font-style: regular;">Road Trip Tunes</span><br /><br />We know there's nothing better than pairing a nice long drive with your favorite tunes blasting from the stereo. So, Ford collaborated with Hungama music app to put together a collection of playlists you can listen to on your next road trip. The best part: both Ford and non-Ford drivers can access these playlists.'''

[[module]] #2 Images
path = '''email_modules/image/2images'''
color = '''white'''

image1 = '''in_edm6_BarbedWire_20161101'''
image1_url = '''https://www.india.ford.com/#overlay/content/ford/in/en_in/site-wide-content/video-overlays/overview-videos/video-10.html/'''
image1_link_name = '''video_barbed_wire'''
image2 = '''in_edm6_DustStorm_20161101'''
image2_url = '''https://www.india.ford.com/#overlay/content/ford/in/en_in/site-wide-content/video-overlays/overview-videos/video-9.html/'''
image2_link_name = '''video_dust_storm'''

[[module]] #Split 02
path='email_modules/split/02'
color='darkblue'

	title = '''Road Safety Report Cards'''
	copy = '''We are always thinking about how to keep you and your family safe on the road. That's why we partnered with 550 schools across India to hand out Safety Report Cards to students, where they can learn about road safety and rate their parents' driving. Students can then drop the filled out cards into boxes at their school to enter in to a lucky draw where 10 lucky winners can land themselves a cool Mustang toy car. Lucky draw winners will be notified by October 30, 2017. '''
	cta1_text = '''LEARN MORE'''
	cta1_url = '''https://www.youtube.com/watch?time_continue=7&v=PgWbOLKw8IY'''
	cta1_link_name = '''unskippable_video'''
	cta1_icon = '''play'''
	image = '''in_edm6_spp_20170330'''
    
[[module]] #Split 01
path='email_modules/split/01'
color='lightblue'

	title = '''Cardekho Safety Month'''
	copy = '''India has the highest number of road deaths in the world, yet many don’t consider safety when buying a car. To combat this, Ford partnered with Cardekho to initiate a safety month, and created safety-related content to raise awareness of the importance of safety when driving.'''
	cta1_text = '''LEARN MORE'''
	cta1_url = '''http://safetymonth.cardekho.com/'''
	cta1_link_name = '''unskippable_video'''
	cta1_icon = '''play'''
	image = '''in_edm6_spp_20170330'''

[[module]] #Split 02
path='email_modules/split/02'
color='green'

	title = '''Air Con Tips & Tricks'''
	copy = '''Everyone loves air conditioners, everyone except your fuel gauge – the air conditioner just eats up so much fuel! But we came up with some super handy tricks and tips for staying cool this summer, while still saving on fuel.'''
	cta1_text = '''WATCH NOW'''
	cta1_url = '''https://www.youtube.com/watch?time_continue=7&v=PgWbOLKw8IY'''
	cta1_link_name = '''unskippable_video'''
	cta1_icon = '''play'''
	image = '''in_edm6_spp_20170330'''

[[module]] #Split 01
path='email_modules/split/01'
color='darkblue'

	title = '''Happy & healthy tyres'''
	copy = '''Regularly rotating your tyres can help elongate their lifespan, and can save you money in the long run. Find out what’s involved in rotating your tyres, and why it’s important for overall tyre health and even your safety.'''
	cta1_text = '''WATCH NOW'''
	cta1_url = '''https://www.youtube.com/watch?v=CGmNMMUfIZw&feature=youtu.be'''
	cta1_link_name = '''clever_cot'''
	cta1_icon = '''more'''
	image = '''in_edm6_ode_video_20170420'''

[[module]] #Split 02
path='email_modules/split/02'
color='lightblue'

	title = '''Keep your brakes safe'''
	copy = '''Brakes don’t last forever. Over time, they wear down and can become a safety hazard for your daily commute. Learn how to keep your brakes in good health for a longer period of time, and how to identify warning signs when they might need some attention.'''
	cta1_text = '''WATCH NOW'''
	cta1_url = '''https://www.youtube.com/watch?v=DsYDmFpf-_8&feature=youtu.be'''
	cta1_link_name = '''unskippable_video'''
	cta1_icon = '''play'''
	image = '''in_edm6_spp_20170330'''
    
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
	cta2_url = '''https://www.india.ford.com/owner/dashboard/#/overlay/content/ford/in/en_in/site-wide-content/overlays/form-overlay/login.html'''
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