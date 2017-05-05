+++
markets = ["au"]
title = '''service'''

[[module]] #Banner Image
path='email_modules/image/banner'
color='white'

image = '''au_edm2_RSvc_Due_xtime_logo_20161014'''
url_link = '''https://www.ford.com.au/owners/service/'''

[[module]]
path='email_modules/cover/03'
color='''white'''
copy='''Hi ZZZChennaiGTB <br /><br />This is just a friendly reminder that your Ford Transit is nearly due for a service. <br /><br />Book with ZZZMetro Ford on 1300 756 926 today.'''

[[module]]
path='email_modules/singles/ctablock'
color='''white'''	
cta1_text = '''BOOK A SERVICE'''
cta1_url = '''https://consumer.xtime.net.au/scheduling/?company=14745&store=<%${user.CustomAttribute['DealerCode']}%>&VIN=<%${user.CustomAttribute['VIN']}%>&provider=FORD_AU_THE_BLUE_HIVE&keyword=<%${user.CustomAttribute['CampaignID']}%>&dest=&extid=<%${user.CustomAttribute['CampaignID']}%>&extctxt=FORD_AU_THE_BLUE_HIVE&cfn=<%${user.CustomAttribute['FullName']}%>&cln=<%${user['LastName']}%>&cpn=<%${user.CustomAttribute['Mobile_Phone']}%>&cem=<%${user.CustomAttribute['RealEmail']}%>&button=blue'''
cta1_link_name = '''SERVICE'''

+++