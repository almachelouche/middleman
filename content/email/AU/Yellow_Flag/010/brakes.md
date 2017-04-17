+++
markets = ["au"]
title = '''AU Yellow-Flag 010 Brakes'''

[[module]]
path='email_modules/preheader'
color='''nothing'''

   preheader='''Get your brakes factory-fitted by a Ford technician.'''

[[module]] #Header Logo
path='email_modules/header/logo'
color='white'

  image = '''white'''
  url_link = '''http://www.ford.com.au'''
	
[[module]] #Banner Image No Link
path = '''email_modules/image/banner_nolink'''
color = '''white'''

  image='''au_edm2d_brake_20161114'''


[[module]] #Cover 07
path='email_modules/cover/02'
color='''white'''

  title='''Reminder: Your Brakes May Need Attention'''
  copy='''Hi <%${user.CustomAttribute['FullName']}%><br /><br />When you last serviced your Ford <%${user.CustomAttribute['Model']}%> with us, our technician filled out a Vehicle Report Card. Your brakes were flagged as yellow, meaning they may require replacement before your next scheduled service.<br /><br />We know you are not yet due for a scheduled service, however it has been 6 months or more since we last checked your vehicle. If you would like your brakes inspected for peace of mind in the interim, please call <%${user.CustomAttribute['Dealer_Name']}%> on <%${user.CustomAttribute['Dealer_Phone']}%> to book an appointment. '''
  cta1_text='''BOOK A SERVICE'''
  cta1_url='''https://consumer.xtime.net.au/scheduling/?company=14745&store=#DealerCode#&VIN=#VIN#&provider=FORD_AU_THE_BLUE_HIVE&keyword=#Campaign_ID#&dest=&extid=#Campaign_ID#&extctxt=FORD_AU_THE_BLUE_HIVE&cfn=#FirstName#&cln=#LastName#&cpn=#CustomerPhoneT#&cem=#EmailAddr#'''
  cta1_link_name = '''link_name_here'''

[[module]] #AU Service Status Copy
path='email_modules/custom/au_svcstatus'
color='darkblue'

  toptitle='''Your current brakes status'''
  icon1='''au_edm2d_brake1_20170417'''
  title1='''Good <br />to go<br />'''
  copy1='''<br /><br />Brake Lining: <br />Over 5mm (Disc) <br />or over 2mm (Drum)'''
  icon2='''au_edm2d_brake3_20170417'''
  title2='''May need replacing <br />before next<br /> scheduled service '''
  copy2='''Brake Lining:<br /> 3mm to 5mm (Disc)<br /> or 1.01 to 2mm (Drum) '''
  icon3='''au_edm2d_brake2_20170417'''
  title3='''Replace <br />immediately <br /> '''
  copy3='''<br /><br />Brake Lining:<br /> Less than 3mm (Disc) <br />or less than 1mm (Drum)'''
	
[[module]] #Cover 01
path='email_modules/cover/01'
color='white'

  icon = '''in_edm2d_status_battery_black_20160801'''
  title = '''No one knows your Ford like we do'''
  copy = '''Our Ford technicians will expertly fit Genuine Ford Brake Pads. Specifically designed for your <%${user.CustomAttribute['Model']}%>'s braking system, they're fully tested to ensure long life and minimal fading and are covered under warranty for a period of 12 months or 20,000km&#185;.<br /><br />With our <a href="http://www.ford.com.au/owners/service/brakes" style="text-decoration:underline; color:#2D96CD">Service Price Promise for Brakes</a>&#178;, you won't pay more than the price published online for new Ford Genuine Fitted Brake Pads at <%${user.CustomAttribute['Dealer_Name']}%>.'''
  cta1_url = '''http://www.ford.com.au/owners/service/brakes'''
  cta1_text = '''FIND OUT MORE'''
  cta1_icon = '''more'''
  cta1_link_name = '''more1'''
	
[[module]] #Banner Image No Link
path = '''email_modules/image/banner_nolink'''
color = '''white'''

  image='''au_edm2d_brake2_20161114'''
  
[[module]] #Footer AU Social
path='email_modules/footer/au/social'
color='white'

[[module]] #Footer Disclaimer
path='email_modules/footer/disclaimer'
color='white'

  text = '''DISCLAIMERS 	
        <br /> <br />
        1. Conditions and exclusions apply. For more information, see <a href="http://www.ford.com.au/ownership/genuine-parts" style="text-decoration:underline; color:#91a4b1">www.ford.com.au/ownership/genuine-parts</a><br /><br />
        2. Available at participating Ford Dealers. Excludes Everest, Mustang, Focus RS, F-Series, FPV, ST, XR5 and Transit models. Customers will pay equal to or less than the current maximum price as published by Ford at <a href="http://www.ford.com.au/owners/service/brakes" style="text-decoration:underline; color:#91a4b1">ford.com.au/service/t-and-c</a>. Maximum prices are subject to change. See<a href="http://www.ford.com.au/service/brakes" style="text-decoration:underline; color:#91a4b1"> www.ford.com.au/service/t-and-c</a> for full terms.<br /><br />'''


[[module]] #Footer AU Online
path='email_modules/footer/au/online'
color='white'
+++