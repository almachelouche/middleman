+++
markets = ["in"]
title = '''Event Save Test'''

[[module]]
path='email_modules/preheader'

	 preheader = '''Your Ford <%${user.CustomAttribute['Model']}%> is due for service, and our experts can't wait to make sure it's running at its absolute best. Hello <%${user.CustomAttribute['FullName']}%>, long time, no see! Your Ford <%${user.CustomAttribute['Model']}%> is due for service, and our experts can't wait to make sure it's running at its absolute best.'''

[[module]] #Header Logo
path='email_modules/header/logodesktop'
color='white_pb'

    image = '''white_pb'''
    url_link = '''https://www.india.ford.com/'''
    
[[module]] #Banner Image No Link
path = '''email_modules/image/banner_nolink'''
color = '''white'''

  image = '''in_edm2_reunion_season2_20170814'''
    
[[module]]
path='email_modules/spacer/default'
color='white'

	height="20"

[[module]]
path='email_modules/singles/title'
color='''white'''

	title = '''Get ready for a reunion for Ford!'''

[[module]]
path='email_modules/spacer/default'
color='white'

	height="30"

[[module]]
path='email_modules/singles/copy'
color='''white'''

	copy = '''Reunions are a great opportunity to reconnect with friends and family. This Reunion season, reunite with Ford and enjoy some great service offers, exclusively for you.<br /><br />If you purchased a Ford between 2007 and 2012, go to your nearest Ford Service Centre and enjoy a 25% discount on brakes, suspension and clutch parts, labour and VAS, and get a free oil filter replacement, too! Hurry, this offer is only available from September 2-17 and you don't want to miss it.*'''

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
    
[[module]]
path='email_modules/singles/copy'
color='''white'''

	copy = '''<a href="https://calendar.google.com/calendar/event?action=TEMPLATE&tmeid=MzBodjZucWhnMWR1Z2FrZzJpanUybWdyZXUgYmguc2guZWRtLnVhdEBt&tmsrc=bh.sh.edm.uat%40gmail.com" style="text-decoration:underline; color:#2D96CD;" >Add to Calendar (Gmail)</a>
    <br />
    <a href="https://s3-ap-southeast-1.amazonaws.com/edm-images/events/test/Event_Save_Test.ics" style="text-decoration:underline; color:#2D96CD;" >Add to Calendar (iCal/Outlook)</a>'''

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

  text='''*Terms & conditions apply. Offer applicable for Ford owners of 2007-2012 and servicing their cars  between 2nd September to 17th September 2017. Given offers are applicable only in Haryana, Chandigarh, Delhi NCR, Rajasthan, Jammu & Kashmir, Andhra Pradesh, Telangana, Gujarat, Goa, West Bengal & Assam and cannot be clubbed with other offers. Offer not applicable on accidental jobs and body repair.'''

[[module]] #Footer IN Online
path='email_modules/footer/in/online'
color='white'
+++