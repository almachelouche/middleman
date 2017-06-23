+++
markets = ["in"]
title = '''IN Service Reminder Regular Due/Pdue 018 Monsoon West 5yrs-'''

[[module]]
path='email_modules/preheaderbefore'

segmentif = ["(user.CustomAttribute['Esplit'] == 'Due')"]

	 preheader = '''Your Ford <%${user.CustomAttribute['Model']}%> is due for service, and our experts can't wait to make sure it's running at its absolute best. Hello <%${user.CustomAttribute['FullName']}%>, long time, no see! Your Ford <%${user.CustomAttribute['Model']}%> is due for service, and our experts can't wait to make sure it's running at its absolute best.'''

[[module]]
path='email_modules/preheaderbefore'

segmentelseif = ["(user.CustomAttribute['Esplit'] == 'PastDue')"]

	 preheader = '''Your Ford <%${user.CustomAttribute['Model']}%>'s service is overdue. For the wellbeing of you and your Ford, it's important that you visit a Ford service centre soon. Hello <%${user.CustomAttribute['FullName']}%>Your Ford <%${user.CustomAttribute['Model']}%>'s service is overdue. For the wellbeing of you and your Ford, it's important that you visit a Ford service centre soon.'''

[[module]]
path='email_modules/body'


[[module]]
path='email_modules/preheaderafter'

segmentif = ["(user.CustomAttribute['Esplit'] == 'Due')"]

	 preheader = '''Your Ford <%${user.CustomAttribute['Model']}%> is due for service, and our experts can't wait to make sure it's running at its absolute best. Hello <%${user.CustomAttribute['FullName']}%>, long time, no see! Your Ford <%${user.CustomAttribute['Model']}%> is due for service, and our experts can't wait to make sure it's running at its absolute best.'''

[[module]]
path='email_modules/preheaderafter'

segmentelseif = ["(user.CustomAttribute['Esplit'] == 'PastDue')"]

    preheader = '''Your Ford <%${user.CustomAttribute['Model']}%>'s service is overdue. For the wellbeing of you and your Ford, it's important that you visit a Ford service centre soon. Hello <%${user.CustomAttribute['FullName']}%>Your Ford <%${user.CustomAttribute['Model']}%>'s service is overdue. For the wellbeing of you and your Ford, it's important that you visit a Ford service centre soon.'''
 
[[module]] #Header Logo
path='email_modules/header/logodesktop'
color='white_pb'

    image = '''white_pb'''
    url_link = '''https://www.india.ford.com/'''
  
[[module]]
path='email_modules/spacer/default'
color='white'

	height="30"

[[module]]
path='email_modules/singles/icon'
color='''white'''
segmentif = ["(user.CustomAttribute['Esplit'] == 'Due')"]

	icon = '''in_edm2_svc_wrench_20160801'''

[[module]]
path='email_modules/singles/icon'
color='''white'''
segmentif = ["(user.CustomAttribute['Esplit'] == 'PastDue')"]

	icon = '''in_edm2_svc_wrench_urgent_20160801'''
    
[[module]]
path='email_modules/spacer/default'
color='white'

	height="30"

[[module]]
path='email_modules/singles/title'
color='''white'''
segmentif = ["(user.CustomAttribute['Esplit'] == 'Due')"]

	title = '''It's time for a visit'''
    
[[module]]
path='email_modules/singles/title'
color='''white'''
segmentif = ["(user.CustomAttribute['Esplit'] == 'PastDue')"]

	title = '''<span style="color:#FF6600;">Your service is now past due</span>'''    

[[module]]
path='email_modules/spacer/default'
color='white'

	height="30"

[[module]]
path='email_modules/singles/copy'
color='''white'''
segmentif = ["(user.CustomAttribute['Esplit'] == 'Due')"]

	copy = '''Hello <%${user.CustomAttribute['FullName']}%><br /><br />Long time, no see! Your Ford <%${user.CustomAttribute['Model']}%> is due for service, and our experts can't wait to make sure it's running at its absolute best.<br /><br />Your next service is due on: <% ${user.CustomAttribute['NextServiceDate']} %> '''
    
[[module]]
path='email_modules/singles/copy'
color='''white'''
segmentif = ["(user.CustomAttribute['Esplit'] == 'PastDue')"]

	copy = '''Hello <%${user.CustomAttribute['FullName']}%><br /><br />Your Ford <%${user.CustomAttribute['Model']}%>'s service is overdue. For the wellbeing of you and your Ford, it's important that you visit a Ford service centre soon.<br /><br />We've got your back. Contact us today and continue to enjoy carefree driving.'''    

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
	cta2_text = '''&nbsp;&nbsp;FIND A DEALER&nbsp;&nbsp;'''
	cta2_url = '''https://www.india.ford.com/locate-dealer/'''
	cta2_link_name = '''locate_dealer'''    

[[module]]
path='email_modules/spacer/default'
color='white'

	height="30"

[[module]] #Cover 11
path='email_modules/cover/03'
color='white'

  copy = '''VIN No: <% ${user.CustomAttribute['VIN']}%><br />Last reported service date: <%${user.CustomAttribute['Last_Reported_Service_Date']}%><br />Last reported mileage (Kms): <% ${user.CustomAttribute['Mileage']}%>'''

[[module]] #Banner Image
path='email_modules/image/banner'
color='white'

	image = '''in_edm2_monsoon_5yr-_20170526'''
    url_link='''https://www.india.ford.com/owner/monsoon-service-camp/'''
    url_link_name='''monsoon'''
  
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

	copy = '''Get your car geared up for Monsoon Season. Drive into any Ford Service Centre and enjoy great deals, including a free 50+ point check-up and discounts up to 50%. Offers valid from 3rd to 9th July.*'''

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
	icon2_text = '''<span style="font-weight:bold">Tyres</span><br />Buy 4, receive a gift*'''
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
	icon1_text = '''<span style="font-weight:bold">Oil Filters</span><br />50%* off'''
	icon2_url='''tel:18004252500'''
	icon2_link_name = '''locate_dealer2'''
	icon2_image='''in_edm2_monsoon_battery_20170526'''
	icon2_text = '''<span style="font-weight:bold">Batteries</span><br />&#8377;1000* off'''
	icon3_url='''tel:18002097400'''
	icon3_link_name = '''locate_dealer3'''
	icon3_image='''in_edm2_monsoon_wiper_blades_20170526'''
	icon3_text = '''<span style="font-weight:bold">Wipers</span><br />50%* off blades and inserts'''
	icon4_url='''https://partscalculator.fordind.com:1443/Fill_Field'''
	icon4_link_name = '''locate_dealer4'''
	icon4_image='''in_edm2_monsoon_body_paint_20170526'''
	icon4_text = '''<span style="font-weight:bold">Full Body Paint</span><br />20%* off labour'''
  
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
color='''white'''
segmentif = ["(user.CustomAttribute['SSPStatus'] == 'NO')"]

  title = '''Scheduled Service Plan'''
  copy = '''Our peace-of-mind service plans keep your Ford performing its best. Enjoy up to 5 years of capped pricing and save up to 10% on servicing. And coverage is 100% transferrable, increasing your Ford's resale value.'''
  cta1_text = '''FIND OUT MORE'''
  cta1_url = '''https://www.india.ford.com/owner/scheduled-service-plan/'''
  cta1_link_name = '''SSP'''
  icon = '''in_edm1_extendedwarranty_20160801'''

[[module]] #Footer 4 Icons
path='email_modules/footer/4icons'
color='white'

  icon1_url='''https://www.india.ford.com/locate-dealer/'''
  icon1_link_name = '''locate_dealer_footer'''
  icon1_image='''in_dealers_20160414'''
  icon2_url='''https://fordassured.in/'''
  icon2_link_name = '''ford_assured'''
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

  text='''*Tearms and conditions apply. Offers only valid in Gujarat, Madhya Pradesh, Chhattisgarh. '''

[[module]] #Footer IN Online
path='email_modules/footer/in/online'
color='white'
+++