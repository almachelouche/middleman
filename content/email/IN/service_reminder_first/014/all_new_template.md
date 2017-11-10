+++
markets = ["in"]
title = '''IN Service Reminder First Due/PDue 014 All'''

[[module]]
path='email_modules/preheaderbefore'

segmentif = ["(user.CustomAttribute['Esplit'] == 'Due')"]

	preheader = '''Here's a quick reminder that your new Ford <%${user.CustomAttribute['Model']}%> is due for its first service. Hello <%${user.CustomAttribute['FullName']}%>, here's a quick reminder that your new Ford <%${user.CustomAttribute['Model']}%> is due for its first service.'''

[[module]]
path='email_modules/preheaderbefore'

segmentelseif = ["(user.CustomAttribute['Esplit'] == 'PastDue')"]

	preheader = '''We noticed your Ford <%${user.CustomAttribute['Model']}%> is overdue for its first service. This service is just a quick check to ensure your Ford is still running at its absolute best. Hello <%${user.CustomAttribute['FullName']}%>, we noticed your Ford <%${user.CustomAttribute['Model']}%> is overdue for its first service. This service is just a quick check to ensure your Ford is still running at its absolute best.'''

[[module]]
path='email_modules/body'


[[module]]
path='email_modules/preheaderafter'

segmentif = ["(user.CustomAttribute['Esplit'] == 'Due')"]

	preheader = '''Here's a quick reminder that your new Ford <%${user.CustomAttribute['Model']}%> is due for its first service. Hello <%${user.CustomAttribute['FullName']}%>, here's a quick reminder that your new Ford <%${user.CustomAttribute['Model']}%> is due for its first service.'''

[[module]]
path='email_modules/preheaderafter'

segmentelseif = ["(user.CustomAttribute['Esplit'] == 'PastDue')"]

	preheader = '''We noticed your Ford <%${user.CustomAttribute['Model']}%> is overdue for its first service. This service is just a quick check to ensure your Ford is still running at its absolute best. Hello <%${user.CustomAttribute['FullName']}%>, we noticed your Ford <%${user.CustomAttribute['Model']}%> is overdue for its first service. This service is just a quick check to ensure your Ford is still running at its absolute best.'''

[[module]] #Banner Image No Link
path = '''email_modules/image/banner_nolink'''
color = '''white'''

	image = '''in_edm2_fordsvc_20160801'''

[[module]]
path='email_modules/singles/title'
color='''white'''
segmentif = ["(user.CustomAttribute['Esplit'] == 'Due')"]

	title = '''It's time for your first visit'''
    
[[module]]
path='email_modules/singles/title'
color='''white'''
segmentif = ["(user.CustomAttribute['ESplit'] == 'PastDue')"]

	title = '''<span style="color:#FF6600;">Your Ford <%${user.CustomAttribute['Model']}%> missed important service </span>'''    

[[module]]
path='email_modules/spacer/default'
color='white'

	height="30"

[[module]]
path='email_modules/singles/copy'
color='''white'''
segmentif = ["(user.CustomAttribute['Esplit'] == 'Due')"]

	copy = '''Hello <%${user.CustomAttribute['FullName']}%><br /><br />Here's a quick reminder that your new Ford <%${user.CustomAttribute['Model']}%> is due for its first service.<br /><br />All new cars undergo a "settling in" period after they leave the showroom and hit the road. Your first service is just a quick check to ensure that your Ford <%${user.CustomAttribute['Model']}%> is running at its absolute best.'''
    
[[module]]
path='email_modules/singles/copy'
color='''white'''
segmentif = ["(user.CustomAttribute['Esplit'] == 'PastDue')"]

	copy = '''Hello <%${user.CustomAttribute['FullName']}%><br /><br />We noticed your Ford <%${user.CustomAttribute['Model']}%> is overdue for its first service. This service is just a quick check to ensure your Ford is still running at its absolute best.<br /><br />We've got your back. Book your service today.'''    

[[module]]
path='email_modules/spacer/default'
color='white'

	height="30"
    
[[module]]
path='email_modules/singles/2ctablocksideoutline'
color='''white'''
	cta1_text = '''BOOK A SERVICE'''
	cta1_url = '''https://www.india.ford.com/#overlay/content/ford/in/en_in/site-wide-content/overlays/forms/service-booking.html/'''
	cta1_link_name = '''callback'''
	cta2_text = '''&nbsp;BOOK A PICK-UP'''
	cta2_url = '''https://www.india.ford.com/locate-dealer/'''
	cta2_link_name = '''locate_dealer'''    

[[module]]
path='email_modules/spacer/default'
color='white'

	height="30"

[[module]]
path='email_modules/spacer/platinum_20'
color='white'

[[module]]
path='email_modules/dual/05'
color='white'

	title1 = '''Service Price Promise'''
	text_box_height = '''350'''
	copy1 = '''Get an affordable service with Ford's Integrated Calculator. Be it scheduled maintenance, part change, or both; you can calculate the all-inclusive cost online, and pay the Ford dealer exactly what you see on the screen!'''
	cta1a_text = '''CHECK SERVICE PRICE'''
	cta1a_url = '''https://www.fordservicepricepromise.com/'''
	cta1a_link_name = '''spp'''
	image1 = '''in_edm2_spp_20171026'''
	image1_link_url = '''https://www.fordservicepricepromise.com/'''
	image1_link_name = '''spp_image'''
	title2 = '''Ford Genuine Parts'''
	copy2 = '''Don't take chances with your family's safety. Ford Genuine Parts are designed specifically for your Ford vehicle, to ensure it always performs like new. So stick with Ford Genuine Parts, available at Ford service centres nationwide.'''
	cta2a_text = '''CHECK HOW AFFORDABLE'''
	cta2a_url = '''https://www.india.ford.com/surprisingly-affordable/'''
	cta2a_link_name = '''surprisingly_affordable'''
	image2 = '''in_edm2_ford_parts_20171026'''
	image2_link_url = '''https://www.india.ford.com/surprisingly-affordable/'''
	image2_link_name = '''surprisingly_affordable_image'''

[[module]]
path='email_modules/spacer/platinum_20'
color='white'    
segmentif = ["((user.CustomAttribute['SSPStatus'] == 'NO') && (user.CustomAttribute['EWStatus'] != 'NO')) || ((user.CustomAttribute['SSPStatus'] == 'NO') && (user.CustomAttribute['EWStatus'] == 'NO') && (user.CustomAttribute['Esplit'] == 'PastDue'))"]

[[module]]
path='email_modules/spacer/platinum_20'
color='white'    
segmentif = ["((user.CustomAttribute['Model'] == 'Figo') || (user.CustomAttribute['Model'] == 'EcoSport') || (user.CustomAttribute['Model'] == 'Aspire')) && (user.CustomAttribute['EWStatus'] == 'NO') && (user.CustomAttribute['ESplit'] == 'Due')"]

[[module]]
path='email_modules/spacer/platinum_20'
color='white'    
segmentelseif = ["((user.CustomAttribute['Model'] == 'Classic') || (user.CustomAttribute['Model'] == 'Fiesta')) && (user.CustomAttribute['EWStatus'] == 'NO') && (user.CustomAttribute['ESplit'] == 'Due')"]

[[module]]
path='email_modules/spacer/platinum_20'
color='white'    
segmentelseif = ["((user.CustomAttribute['Model'] == 'Endeavour')) && (user.CustomAttribute['EWStatus'] == 'NO') && (user.CustomAttribute['ESplit'] == 'Due')"]

[[module]] #Cover 05
path='email_modules/cover/02'
color='''green_pb'''
segmentif = ["((user.CustomAttribute['SSPStatus'] == 'NO') && (user.CustomAttribute['EWStatus'] != 'NO')) || ((user.CustomAttribute['SSPStatus'] == 'NO') && (user.CustomAttribute['EWStatus'] == 'NO') && (user.CustomAttribute['Esplit'] == 'PastDue'))"]

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
