+++
markets = ["in"]
title = '''IN Lost Customer 004 Q2'''


[[module]]
path='email_modules/preheader'
color='''nothing'''

	preheader = '''We noticed that your Ford hasn't been serviced lately. You're an important member of the Ford family, so that's got us worried. <%${user.CustomAttribute['FullName']}%>, your Ford may need attention.'''

[[module]] #Header Logo
path='email_modules/header/logodesktop'
color='white_pb'

  image = '''white_pb'''
  url_link = '''https://www.india.ford.com/'''

[[module]] #Cover 07
path='email_modules/cover/02'
color='''white'''

   title='''<%${user.CustomAttribute['FullName']}%>, your Ford may need attention'''
   copy='''We noticed that your Ford hasn't been serviced lately. You're an important member of the Ford family, so that's got us worried.<br /><br />To stay safe on the road, it's important that you follow your <a href="https://www.india.ford.com/owner/scheduled-service-plan/" name="service_plan" style="text-decoration:underline; color:#2D96CD;" >service plan</a> and replace worn-out parts as soon as possible.<br /><br />We've got your back. Visit us at a Ford dealer soon. '''
   cta1_text='''BOOK A SERVICE'''
   cta1_url='''https://www.india.ford.com/#overlay/content/ford/in/en_in/site-wide-content/overlays/forms/service-booking.html/'''
   cta1_link_name = '''service_booking'''

[[module]] #Split 15
path='email_modules/split/11'
color='white'

  title = '''Limited time offer'''
  copy = '''When you come in for service between April 1 and June 31, you'll enjoy a massive 20% off all Ford parts and labour¹.''' 
  image_url = '''https://www.india.ford.com/locate-dealer/'''
  image_link_name = '''locate_dealer_image'''
  image = '''in_edm2_save20_20170105'''

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
		
  text='''1. Excludes accessories, tyres, body shop jobs covered by insurance, and VAS (accessory, exterior & interior cleaning).'''

[[module]] #Footer IN Online
path='email_modules/footer/in/online'
color='white'
+++
