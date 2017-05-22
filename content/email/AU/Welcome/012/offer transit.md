+++
markets = ["au"]
title = '''AU Welcome 012 Offer Transit sd'''

[[module]]
path='email_modules/preheaderbefore'
color='''nothing'''
segmentif = ["(user.CustomAttribute['NewRepeat'] == 'R')"]

   preheader='''The journey continues! From all the team at Ford, we'd like to say a big THANK YOU for choosing another Ford.'''

[[module]]
path='email_modules/preheaderbefore'
color='''nothing'''
segmentelse = ["(user.CustomAttribute['NewRepeat'] == 'N')"]

   preheader='''We hope you're enjoying the ride. From all the team at Ford, we'd like to say a big THANK YOU for choosing a Ford <%${user.CustomAttribute['Model']}%> <%${user.CustomAttribute['Series']}%>.'''

[[module]]
path='email_modules/body'
color='''nothing'''

[[module]]
path='email_modules/preheaderafter'
color='''nothing'''
segmentif = ["(user.CustomAttribute['NewRepeat'] == 'R')"]

   preheader='''The journey continues! From all the team at Ford, we'd like to say a big THANK YOU for choosing another Ford.'''

[[module]]
path='email_modules/preheaderafter'
color='''nothing'''
segmentelse = ["(user.CustomAttribute['NewRepeat'] == 'N')"]

   preheader='''We hope you're enjoying the ride. From all the team at Ford, we'd like to say a big THANK YOU for choosing a Ford <%${user.CustomAttribute['Model']}%> <%${user.CustomAttribute['Series']}%>.'''


[[module]] #Header Logo
path='email_modules/header/logo'
color='white'

  image = '''white'''
  url_link = '''https://www.ford.com.au/'''



 
[[module]] #Cover 01 - Repeat Buyer
path='email_modules/cover/01'
color='''slatescreen'''
segmentif = ["(user.CustomAttribute['NewRepeat'] == 'R')"]
 
  title='''Hi <%${user.CustomAttribute['FullName']}%><br />The journey continues'''
  copy='''From all the team at Ford, we'd like to say a big THANK YOU for choosing another Ford.'''
  
[[module]] #Cover 01 - New Buyer
path='email_modules/cover/01'
color='''slatescreen'''
segmentelse = ["(user.CustomAttribute['NewRepeat'] == 'N')"]
 
  title='''Hi <%${user.CustomAttribute['FullName']}%><br />We hope you're enjoying the ride.'''
  copy='''From all the team at Ford, we'd like to say a big THANK YOU for choosing a Ford <%${user.CustomAttribute['Model']}%> <%${user.CustomAttribute['Series']}%>.'''
  
[[module]] #Banner Image No Link
path = '''email_modules/image/banner_nolink'''
color = '''white'''

  image = '''au_edm1_cover_20161018'''
  
  
  
[[module]] #Cover 11
path='email_modules/cover/03'
color='''white'''
  
  copy='''<br /><br />But our job isn't done now that you're on the road. At Ford we like to look after our owners, so we provide our Service Guarantee for added peace of mind.<br /><br /><span style="font-weight: bold;">Roadside Assistance</span><br /><br />Get help when you need it most with State Auto Club membership for up to 7 years&#185;.<br /><br /><span style="font-weight: bold;">Service Price Promise</span><br /><br />Know what you’ll pay for standard service before you even come in.<br /><br /><span style="font-weight: bold;">
  Loan Car</span><br /><br />Don’t get stuck without wheels. Available when you book a service&#178;.<br /><br />
  <span style="font-weight: bold;">Extended Warranty</span><br /><br />Your Transit includes a complimentary extended warranty that covers your vehicle for 3 years or 200,000km – whichever comes first&#179;. Simply follow your vehicle’s servicing requirements outlined in your owner’s literature to stay fully protected. For your convenience, this warranty information is recorded at all Ford Dealerships nationwide and you will also have received a letter confirming the extended warranty period from your Dealer.<br /><br />Call us anytime on: 1300 80 10 80''' 
  
 [[module]] #3 Images
path = '''email_modules/image/3images'''
color = '''white'''

  image1 = '''au_svc_icon_20170517'''
	image1_url = '''https://www.ford.com.au/owners/service/roadside-assistance/'''
	image1_link_name = '''icon1'''
  image2 = '''au_svc_icon2'''
	image2_url = '''https://www.ford.com.au/owners/service/calculator?edm'''
	image2_link_name = '''icon2'''
  image3 = '''au_svc_icon1A'''
	image3_url = '''https://www.ford.com.au/owners/service/'''
	image3_link_name = '''icon3'''
    

[[module]] #Banner Image No Link
path = '''email_modules/image/banner_nolink'''
color = '''white'''
  image='''au_edm1_cover2_20161018'''

[[module]] #AU FordOwner Resources
path='email_modules/custom/au_fordowner_resources'
color='white'

	title = '''Ford Owner Resources'''
	copy1 = '''Ford offers two ways to access helpful resources and information anywhere you go. <br /><br />You can visit the <span style="font-weight: bold;">Ford Owners Website</span> online at any time to view videos, check for vehicle updates, or find your closest service centre. Register quickly and easily: Assign a nickname to your Ford <%${user.CustomAttribute['Model']}%> <%${user.CustomAttribute['Series']}%> and enter your Vehicle Identification Number <%${user.CustomAttribute['VIN']}%>'''
    copy2 = '''You can also download the <span style="font-weight: bold;">Ford Owners App</span> to your mobile device for instant access on-the-go. <br /><br />'''
	cta1_text='''Visit Ford Owners Website'''
	cta1_url='''https://www.ford.com.au/owners/'''
	cta2_text='''iOS'''
	cta2_url='''https://itunes.apple.com/au/app/ford-owners/id990342351?mt=8'''
	cta3_text='''Android'''
	cta3_url='''https://play.google.com/store/apps/details?id=com.ford.fordowners&hl=en'''
	cta1_icon='''more'''

[[module]] #Cover 01
path='email_modules/cover/01'
color='''fordblue'''

  icon='''au_edm1_welcome_icon_20161019'''
  title='''Can we help?'''
  copy='''
If you have any further questions, please don't hesitate to contact <br /><br /><span style="color:#FFFFFF"><%${user.CustomAttribute['Dealer_Name']}%> on <a href="tel:<%${user.CustomAttribute['Dealer_Phone']}%>" style="color:#FFFFFF; text-decoration:none"><%${user.CustomAttribute['Dealer_Phone']}%></a>   </span>or <a href="tel:133673" style="color:#FFFFFF; text-decoration:none"><span style="color:#FFFFFF">13 FORD (13 36 73)</span>'''

  
[[module]] #Footer AU Social
path='email_modules/footer/au/social'
color='white'

[[module]] #Footer Disclaimer
path='email_modules/footer/disclaimer'
color='white'

  text = '''DISCLAIMERS:	
        <br /> <br />
        1) Private and Blue Business Fleet customers only at participating Dealers who have not reached 7 years or 105,000 kms. State Auto Club Roadside Assistance & Membership is included with the first seven standard services for 12 months or until your next eligible standard service (whichever occurs first). Standard services include all A and B logbook services. Customers must comply with scheduled servicing intervals to maintain continuity of membership. See <a href="https://www.ford.com.au/owners/service/t-and-c/"  name="terms2" style="text-decoration:underline; color:#91a4b1">www.ford.com.au/owners/service/t-and-c</a> for full terms.<br /><br />
        2) Available at participating dealers on scheduled services or overnight warranty repairs. Private and Blue, Silver and Gold Business Fleet customers only. Booking may be required. See <a href="https://www.ford.com.au/"  name="ford1" style="text-decoration:underline; color:#91a4b1">www.ford.com.au</a>.<br /><br />
        3) The Factory Warranty will operate under the terms and conditions of the Ford Express New Vehicle Warranty. Commences upon delivery to the customers or upon first registration of the vehicle for on-sold demonstrator vehicles and ends after 3 years or 200,000kms, whichever occurs first.<br /><br /> '''
       


[[module]] #Footer AU Online
path='email_modules/footer/au/online'
color='white'
+++