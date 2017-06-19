+++
markets = ["in"]
title = '''IN Service Reminder First Due/PDue 011 Monsoon SouthWest 5yrs-'''

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
	cta1_url = '''https://www.india.ford.com/#overlay/content/ford/in/en_in/site-wide-content/overlays/forms/service-booking.html/'''
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
	cta1_url = '''https://www.india.ford.com/#overlay/content/ford/in/en_in/site-wide-content/overlays/forms/service-booking.html/'''
	cta1_link_name = '''callback'''
	cta2_text = '''FIND A DEALER'''
	cta2_url = '''https://www.india.ford.com/locate-dealer/'''
	cta2_link_name = '''locate_dealer'''
	icon = '''in_edm2_svc_wrench_urgent_20160801'''



[[module]] #Banner Image No Link
path = '''email_modules/image/banner_nolink'''
color = '''white'''
  
  image = '''in_edm2_monsoon_5yr-_20170526'''

[[module]]
path='email_modules/spacer/default'
color='white'

	height="20"

[[module]]
path='email_modules/singles/title'
color='''white'''
	
	title = '''It's that time of the year!'''

[[module]]
path='email_modules/spacer/default'
color='white'

	height="30"

[[module]]
path='email_modules/singles/copy'
color='''white'''
	
	copy = '''Get your car geared up for Monsoon Season. Drive into any Ford Service Centre and enjoy great deals, including a free 50+ point check-up and discounts up to 50%. Offers valid from June 12th to June 18th.*'''

[[module]] #Custom 4 Icons
path='email_modules/custom/4icons'
color='white'

	title = ''''''
  icon1_url='''http://www.india.ford.com/locate-dealer'''
  icon1_link_name = '''locate_dealer'''
  icon1_image='''in_edm2_monsoon_brake_pads_20170526'''
  icon1_text = '''<span style="font-weight:bold">Brake Pads</span><br />10%* off'''
  icon2_url='''tel:18004252500'''
  icon2_link_name = '''locate_dealer2'''
  icon2_image='''in_edm2_monsoon_tyres_20170526'''
  icon2_text = '''<span style="font-weight:bold">Tyres</span><br />Buy 4, receive a gift'''
  icon3_url='''tel:18002097400'''
  icon3_link_name = '''locate_dealer3'''
  icon3_image='''in_edm2_monsoon_shoch_absorber_20170526'''
  icon3_text = '''<span style="font-weight:bold">Shock Absorbers</span><br />10%* off'''
  icon4_url='''https://partscalculator.fordind.com:1443/Fill_Field'''
  icon4_link_name = '''locate_dealer4'''
  icon4_image='''in_edm2_monsoon_add_value_svc_20170526'''
  icon4_text = '''<span style="font-weight:bold">Value Added Services</span><br />10%* off'''
  
  [[module]] #Custom 4 Icons
path='email_modules/custom/4icons'
color='white'

	title = ''''''
  icon1_url='''http://www.india.ford.com/locate-dealer'''
  icon1_link_name = '''locate_dealer'''
  icon1_image='''in_edm2_monsoon_oil_filter_20170526'''
  icon1_text = '''<span style="font-weight:bold">Oil Filters</span><br />50% off'''
  icon2_url='''tel:18004252500'''
  icon2_link_name = '''locate_dealer2'''
  icon2_image='''in_edm2_monsoon_battery_20170526'''
  icon2_text = '''<span style="font-weight:bold">Batteries</span><br />&#8377;1000* off'''
  icon3_url='''tel:18002097400'''
  icon3_link_name = '''locate_dealer3'''
  icon3_image='''in_edm2_monsoon_wiper_blades_20170526'''
  icon3_text = '''<span style="font-weight:bold">Wipers</span><br />50% off blades and inserts'''
  icon4_url='''https://partscalculator.fordind.com:1443/Fill_Field'''
  icon4_link_name = '''locate_dealer4'''
  icon4_image='''in_edm2_monsoon_body_paint_20170526'''
  icon4_text = '''<span style="font-weight:bold">Full Body Paint</span><br />20% off labour'''

[[module]]
path='email_modules/spacer/default'
color='white'

	height="30"

[[module]]
path='email_modules/singles/ctablock'
color='''white'''
	
	cta1_text = '''BOOK A SERVICE'''
	cta1_url = '''https://www.india.ford.com/#overlay/content/ford/in/en_in/site-wide-content/overlays/forms/service-booking.html/'''
	cta1_link_name = '''book_service'''

[[module]] #Banner Image No Link
path = '''email_modules/image/banner_nolink'''
color = '''white'''

  image = '''in_edm2_fordsvc_20170321'''

[[module]] #Custom 02
path='email_modules/custom/3columncolortexttitle'
color='white'

  title1 = '''Service Price Promise'''
  text1 = '''Calculate your service cost online and pay just that.'''
  textlink1_text = '''<br />Check service price'''
  textlink1_url = '''https://www.fordservicepricepromise.com/'''
  textlink1_link_name = '''price_calculator'''
  title2 = '''Pick Up & Drop'''
  text2 = '''When it's time to service your Ford, get it done from home.'''
  title3 = '''Ford Genuine Parts'''
  text3 = '''Buy Ford genuine parts and drive your car without any worries.'''
  textlink2_text = '''Check how affordable'''
  textlink2_url = '''https://www.india.ford.com/surprisingly-affordable/'''
  textlink2_link_name = '''surprisingly_affordable'''
  cta1_text = '''FIND A DEALER'''
  cta1_url = '''https://www.india.ford.com/locate-dealer/'''
  cta1_link_name = '''locate_dealer_2'''

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

[[module]] #Footer Disclaimer
path='email_modules/footer/disclaimer'
color='white'
		
  text='''Tearms and conditions apply. Offers only valid in Kerala, Andhra, Telengana, Karnataka, Nagerkoil, Maharashtra and Goa. '''

[[module]] #Footer IN Online
path='email_modules/footer/in/online'
color='white'
+++
