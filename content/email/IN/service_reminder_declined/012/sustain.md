+++
markets = ["in"]
title = '''IN Service Reminder Declined 012 nooffer '''
draft = true

[[module]]
path='email_modules/preheader'
color='''nothing'''

	preheader = '''We noticed that you declined an important part of your servicing at your last appointment. That's got us worried.'''

[[module]] #Header Logo
path='email_modules/header/logodesktop'
color='white_pb'

  image = '''white_pb'''
  url_link = '''https://www.india.ford.com/'''

[[module]] #Cover 06
path='email_modules/cover/02'
color='''white_ot'''

  title = '''Your Ford <%${user.CustomAttribute['Model']}%> needs attention'''
  copy = '''We noticed that you declined an important part of your servicing at your last appointment. That's got us worried.<br /><br />When you come into a Ford service centre, you're putting your vehicle into the best hands possible. Our trained technicians know the specifics of your Ford vehicle and only use genuine Ford parts.<br /><br />As part of the Ford family, we've got your back. Visit us at a Ford dealer soon.'''
  cta1_text = '''GET A CALLBACK'''
  cta1_url = '''https://www.india.ford.com/content/ford/in/en_in/site-wide-content/overlays/forms/service-booking/'''
  cta1_link_name = '''callback'''
  cta2_text = '''FIND A DEALER'''
  cta2_url = '''https://www.india.ford.com/locate-dealer/'''
  cta2_link_name = '''locate_dealer'''
  icon = '''in_edm2_svc_wrench_20160801'''
  
[[module]] #Cover 11
path='email_modules/cover/03'
color='white'

  copy = '''VIN No: <% ${user.CustomAttribute['VIN']}%><br />Last reported service date: <%${user.CustomAttribute['Last_Reported_Service_Date']}%><br />Last reported mileage: <% ${user.CustomAttribute['Mileage']}%>'''

[[module]] #Service Status No Copy
path='email_modules/custom/svcstatus_nocopy'
color='white'
      
      toptitle='''Your Ford <%${user.CustomAttribute['Model']}%>'s Health Status'''
  segmentAgreen = '''(user.CustomAttribute['Brake'] == 'G')'''
  segmentAyellow = '''(user.CustomAttribute['Brake'] == 'Y')'''
  segmentAred = '''(user.CustomAttribute['Brake'] == 'R')'''
    icon1green = '''in_edm2d_status_brake_black_20160801'''
    title1green = '''Brakes'''
    subtitle1green = '''Good to go'''
    icon1yellow = '''in_edm2d_status_brake_black_20160801'''
    title1yellow = '''Brakes'''
    subtitle1yellow = '''Service soon'''
    icon1red = '''in_edm2d_status_brake_white_20160801'''
    title1red = '''Brakes'''
    subtitle1red = '''Service immediately'''
  segmentBgreen = '''(user.CustomAttribute['Tyre'] == 'G')'''
  segmentByellow = '''(user.CustomAttribute['Tyre'] == 'Y')'''
  segmentBred = '''(user.CustomAttribute['Tyre'] == 'R')'''
    icon2green = '''in_edm2d_status_tyre_black_20160801'''
    title2green = '''Tyres'''
    subtitle2green = '''Good to go'''
    icon2yellow = '''in_edm2d_status_tyre_black_20160801'''
    title2yellow = '''Tyres'''
    subtitle2yellow = '''Service soon'''
    icon2red = '''in_edm2d_status_tyre_white_20160801'''
    title2red = '''Tyres'''
    subtitle2red = '''Service immediately'''
  segmentCgreen = '''(user.CustomAttribute['Battery'] == 'G')'''
  segmentCyellow = '''(user.CustomAttribute['Battery'] == 'Y')'''
  segmentCred = '''(user.CustomAttribute['Battery'] == 'R')'''
    icon3green = '''in_edm2d_status_battery_black_20160801'''
    title3green = '''Batteries'''
    subtitle3green = '''Good to go'''
    icon3yellow = '''in_edm2d_status_battery_black_20160801'''
    title3yellow = '''Batteries'''
    subtitle3yellow = '''Service soon'''
    icon3red = '''in_edm2d_status_battery_white_20160801'''
    title3red = '''Batteries'''
    subtitle3red = '''Service immediately'''
  
[[module]] #Banner Image No Link
path = '''email_modules/image/banner_nolink'''
color = '''white'''
  
  image = '''in_edm2_fordsvc_20160801'''

[[module]] #Custom 02
path='email_modules/custom/3columncolortexttitle'
color='white'

  title1 = '''Service Price Promise'''
  text1 = '''Get an affordable service with Ford's Integrated Calculator. Be it scheduled maintenance, part change, or both; you can calculate the all-inclusive cost online, and pay the Ford dealer exactly what you see on the screen!'''
  textlink1_text = '''Check service price.'''
  textlink1_url = '''https://www.fordservicepricepromise.com/'''
  textlink1_link_name = '''price_calculator'''
  title2 = '''Pick Up & Drop'''
  text2 = '''When it's time to service your Ford - stay home! If you've signed up for Ford's Periodic Maintenance Schedule, Ford will pick up your vehicle, service it and drop it off at your home. It's that easy. '''
  title3 = '''Ford Genuine Parts'''
  text3 = '''Don't take chances with your family's safety. Fake parts have no guarantees, whereas Ford ensures that our parts meet every quality standard, and work together to give the best results. So, stick to Ford genuine parts from authorised Service Centers, and drive your car without any worries.'''
  textlink2_text = '''Check how affordable.'''
  textlink2_url = '''https://www.india.ford.com/surprisingly-affordable/'''
  textlink2_link_name = '''surprisingly_affordable'''
  cta1_text = '''FIND A DEALER'''
  cta1_url = '''https://www.india.ford.com/locate-dealer/'''
  cta1_link_name = '''locate_dealer_2'''

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

[[module]] #Footer IN Online
path='email_modules/footer/in/online'
color='white'
+++