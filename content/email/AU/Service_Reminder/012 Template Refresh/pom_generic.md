+++

markets = ["au"]
title = '''AU Service Reminder 012 All Blue'''

[[module]]
path='email_modules/preheader'


	preheader=''''''
    
    [[module]] #Header Logo
path='email_modules/header/logo'
color='white'

	image = '''white'''
	url_link = '''https://www.ford.com.au/'''


[[module]] #Banner Image
path='email_modules/image/banner'
color='white'

	image = '''AU_edm2_svc_banner_20160615'''
	url_link = '''https://www.ford.com.au/owners/service/'''
    
    [[module]]
path='email_modules/spacer/default'
color='white'

	height="30"
    
  [[module]]
path='email_modules/singles/copy'
color='''white'''

	copy = '''Hi Name, <br /><br />We hope you're enjoying your new Ford <span style="color:#2D96CD"><%${user.CustomAttribute['Model']}%></span>. Now that you've been on the road for a few months your <%${user.CustomAttribute['Model']}%> is due for its complimentary 2-month/3,000km <span style="text-decoration:underline; color:#2D96CD">Peace of Mind Service Inspection</span>&#185;. Our Ford trained technicians will inspect your vehicle and ensure it’s running at its absolute best. Book your 'Peace of Mind' Service Inspection with <%${user.CustomAttribute['Dealer_Name']}%> on <%${user.CustomAttribute['Dealer_Phone']}%> today, or locate your nearest dealer.'''
  
  +++