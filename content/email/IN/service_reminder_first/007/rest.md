+++
markets = ["in"]
title = '''IN Service Reminder First Due/PDue 007 all'''
draft=true

[[module]]
path='email_modules/preheaderbefore'
color='''nothing'''
segmentif = ["(user.CustomAttribute['Esplit'] == 'Due')"]

	preheader = '''Here's a quick reminder that your new Ford <%${user.CustomAttribute['Model']}%> is due for its first service. Hello <%${user.CustomAttribute['FullName']}%>, here's a quick reminder that your new Ford <%${user.CustomAttribute['Model']}%> is due for its first service.'''

[[module]]
path='email_modules/preheaderbefore'
color='''nothing'''
segmentelseif = ["(user.CustomAttribute['Esplit'] == 'PastDue')"]

	preheader = '''We noticed your Ford <%${user.CustomAttribute['Model']}%> is overdue for its first service. This service is just a quick check to ensure your Ford is still running at its absolute best. Hello <%${user.CustomAttribute['FullName']}%>, we noticed your Ford <%${user.CustomAttribute['Model']}%> is overdue for its first service. This service is just a quick check to ensure your Ford is still running at its absolute best.'''

[[module]]
path='email_modules/body'
color='''nothing'''

[[module]]
path='email_modules/preheaderafter'
color='''nothing'''
segmentif = ["(user.CustomAttribute['Esplit'] == 'Due')"]

	preheader = '''Here's a quick reminder that your new Ford <%${user.CustomAttribute['Model']}%> is due for its first service. Hello <%${user.CustomAttribute['FullName']}%>, here's a quick reminder that your new Ford <%${user.CustomAttribute['Model']}%> is due for its first service.'''

[[module]]
path='email_modules/preheaderafter'
color='''nothing'''
segmentelseif = ["(user.CustomAttribute['Esplit'] == 'PastDue')"]

	preheader = '''We noticed your Ford <%${user.CustomAttribute['Model']}%> is overdue for its first service. This service is just a quick check to ensure your Ford is still running at its absolute best. Hello <%${user.CustomAttribute['FullName']}%>, we noticed your Ford <%${user.CustomAttribute['Model']}%> is overdue for its first service. This service is just a quick check to ensure your Ford is still running at its absolute best.'''

[[module]] #Header Logo
path='email_modules/header/logodesktop'
color='white_pb'

	image = '''white_pb'''
	url_link = '''https://www.india.ford.com/'''

[[module]] #Cover 06
path='email_modules/cover/02'
color='''white'''
segmentif = ["(user.CustomAttribute['ESplit'] == 'Due')"]

	title = '''It's time for your first visit'''
	copy = '''Hello <%${user.CustomAttribute['FullName']}%><br /><br />Here's a quick reminder that your new Ford <%${user.CustomAttribute['Model']}%> is due for its first service.<br /><br />All new cars undergo a "settling in" period after they leave the showroom and hit the road. Your first service is just a quick check to ensure that your Ford <%${user.CustomAttribute['Model']}%> is running at its absolute best.'''
	cta1_text = '''GET A CALLBACK'''
	cta1_url = '''https://www.india.ford.com/content/ford/in/en_in/site-wide-content/overlays/forms/service-booking/'''
	cta1_link_name = '''callback'''
	cta2_text = '''FIND A DEALER'''
	cta2_url = '''https://www.india.ford.com/locate-dealer/'''
	cta2_link_name = '''locate_dealer'''
	icon = '''in_edm2_svc_wrench_20160801'''

[[module]] #Cover 06
path='email_modules/cover/02'
color='''white_ot'''
segmentelseif = ["(user.CustomAttribute['ESplit'] == 'PastDue')"]

	title = '''Your Ford <%${user.CustomAttribute['Model']}%> missed important service'''
	copy = '''Hello <%${user.CustomAttribute['FullName']}%><br /><br />We noticed your Ford <%${user.CustomAttribute['Model']}%> is overdue for its first service. This service is just a quick check to ensure your Ford is still running at its absolute best.<br /><br />We've got your back. Book your service today.'''
	cta1_text = '''GET A CALLBACK'''
	cta1_url = '''https://www.india.ford.com/content/ford/in/en_in/site-wide-content/overlays/forms/service-booking/'''
	cta1_link_name = '''callback'''
	cta2_text = '''FIND A DEALER'''
	cta2_url = '''https://www.india.ford.com/locate-dealer/'''
	cta2_link_name = '''locate_dealer'''
	icon = '''in_edm2_svc_wrench_urgent_20160801'''

[[module]] #Banner Image No Link
path = '''email_modules/image/banner_nolink'''
color = '''white'''

	image = '''in_edm2_fordsvc_20160801'''

[[module]] #Custom 02
path='email_modules/custom/3columncolortexttitle'
color='white'

	title1 = '''Service Price Promise'''
	text1 = '''We ensure that there are no surprises in your service cost. The price you see online is the price you pay.'''
	textlink1_text = '''Check service price'''
	textlink1_url = '''https://www.fordservicepricepromise.com/?extcmp=serca_101115_105328_fordind'''
	textlink1_link_name = '''price_calculator'''
	title2 = '''Pick Up & Drop'''
	text2 = '''Stay home while we pick up, service, and return your vehicle to you. The easiest way to keep your Ford in top shape.'''
	title3 = '''Parts Cost Calculator'''
	text3 = '''We tell you exactly how much a replacement part will cost before you even visit the service centre.'''
	textlink2_text = '''Check parts price'''
	textlink2_url = '''https://partscalculator.fordind.com:1443/Fill_Field?extcmp=hp_eb_nav'''
	textlink2_link_name = '''parts_calculator'''
	cta1_text = '''FIND A DEALER'''
	cta1_url = '''https://www.india.ford.com/locate-dealer/'''
	cta1_link_name = '''locate_dealer_2'''

[[module]] #Cover 05
path='email_modules/cover/02'
color='''green_pb'''
segmentif = ["(user.CustomAttribute['SSPStatus'] == 'NO')"]

	title = '''Scheduled Service Plan'''
	copy = '''Our peace-of-mind service plans keep your Ford performing its best. Enjoy up to 5 years of capped pricing and save up to 10% on servicing. And coverage is 100% transferrable, increasing your Ford's resale value.'''
	cta1_text = '''VIEW PLANS'''
	cta1_url = '''https://www.india.ford.com/owner/scheduled-service-plan/'''
	cta1_link_name = '''ssp'''
	icon = '''in_edm1_extendedwarranty_20160801'''

[[module]] #Cover 05
path='email_modules/cover/02'
color='''green_pb'''
segmentif = ["((user.CustomAttribute['Model'] == 'Figo') || (user.CustomAttribute['Model'] == 'EcoSport') || (user.CustomAttribute['Model'] == 'Aspire')) && (user.CustomAttribute['EWStatus'] == 'NO') && (user.CustomAttribute['ESplit'] == 'Due')"]

	title = '''Extended Peace of Mind'''
	copy = '''Extend your Ford <%${user.CustomAttribute['Model']}%>'s warranty up to 5 years and enjoy worry-free driving. Your warranty protects your Ford against mechanical and electrical failures, and labour charges too. '''
	cta1_text = '''GET PEACE OF MIND'''
	cta1_url = '''https://www.india.ford.com/owner/extended-warranty/'''
	cta1_link_name = '''warranty_info'''
	icon = '''in_edm1_extendedwarranty_20160801'''

[[module]] #Cover 05
path='email_modules/cover/02'
color='''green_pb'''
segmentelseif = ["((user.CustomAttribute['Model'] == 'Classic') || (user.CustomAttribute['Model'] == 'Fiesta')) && (user.CustomAttribute['EWStatus'] == 'NO') && (user.CustomAttribute['ESplit'] == 'Due')"]

	title = '''Extended Peace of Mind'''
	copy = '''Extend your Ford <%${user.CustomAttribute['Model']}%>'s warranty up to 4 years and enjoy worry-free driving. Your warranty protects your Ford against mechanical and electrical failures, and labour charges too. '''
	cta1_text = '''GET PEACE OF MIND'''
	cta1_url = '''https://www.india.ford.com/owner/extended-warranty/'''
	cta1_link_name = '''warranty_info'''
	icon = '''in_edm1_extendedwarranty_20160801'''

[[module]] #Cover 05
path='email_modules/cover/02'
color='''green_pb'''
segmentelseif = ["((user.CustomAttribute['Model'] == 'Endeavour')) && (user.CustomAttribute['EWStatus'] == 'NO') && (user.CustomAttribute['ESplit'] == 'Due')"]

	title = '''Extended Peace of Mind'''
	copy = '''Extend your Ford <%${user.CustomAttribute['Model']}%>'s warranty up to 3 years and enjoy worry-free driving. Your warranty protects your Ford against mechanical and electrical failures, and labour charges too. '''
	cta1_text = '''GET PEACE OF MIND'''
	cta1_url = '''https://www.india.ford.com/owner/extended-warranty/'''
	cta1_link_name = '''warranty_info'''
	icon = '''in_edm1_extendedwarranty_20160801'''

[[module]] #Custom 01
path='email_modules/custom/3columntitle3icons'
color='white_ot'

	title = '''Great service is everything'''
	icon1 = '''in_edm2_fordsvc_a_20160801'''
	text1 = '''Your custom designed service plan keeps your vehicle performing at its best. '''
	icon2 = '''in_edm2_fordsvc_b_20160801'''
	text2 = '''Ford service centre equipment is built and calibrated specifically for your vehicle. '''
	icon3 = '''in_edm2_fordsvc_c_20160801'''
	text3 = '''A record of regular servicing improves your vehicle's re-sale value.'''

[[module]] #Banner Image No Link
path = '''email_modules/image/banner_nolink'''
color = '''white'''

	image = '''in_edm2_greatsvc_20160801'''

[[module]] #Footer 4 Icons
path='email_modules/footer/4icons'
color='white'

	icon1_url='''https://www.india.ford.com/locate-dealer/'''
	icon1_link_name = '''locate_dealer_footer'''
	icon1_image='''in_dealers_20160414'''
	icon2_url='''https://fordassured.in/'''
	icon2_link_name = '''Ford_Assured'''
	icon2_image='''in_ford_assured_20160401'''
	icon3_url='''tel:18004252500'''
	icon3_link_name = '''tel_Customer_Care'''
	icon3_image='''in_customer_care_number_20160401'''
	icon4_url='''tel:18002097400'''
	icon4_link_name = '''tel_RSA'''
	icon4_image='''in_rsa_no_20160615'''

[[module]] #Footer IN Social
path='email_modules/footer/in/social'
color='white'

[[module]] #Footer IN Online
path='email_modules/footer/in/online'
color='white'
+++
