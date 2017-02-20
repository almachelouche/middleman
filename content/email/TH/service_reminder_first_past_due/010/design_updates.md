+++
markets = ["th"]
title = '''TH Service Reminder First Past Due 010 Layout Updates'''
draft = true

[[module]]
path='email_modules/preheader'
color='''nothing'''

	preheader = '''ฟอร์ดให้คุณสุขยิ่งกว่า กับบริการดีๆ พร้อมส่วนลดอะไหล่และค่าน้ำมันเครื่องสูงสุดถึง 300 บาท'''

[[module]] #Header Logo
path='email_modules/header/logo'
color='white'

  image = '''white'''
  url_link = '''https://www.ford.co.th/'''

[[module]]
path='email_modules/cover/02'

color='''white'''
icon='''th_edm2_svc_wrench_urgent_20160801'''
title='''<span style="color:#ff6600;font-family:Tahoma, Verdana, Sans-serif">Your <%${user.CustomAttribute['Model']}%> missed important service</span>'''
copy='''We noticed your <%${user.CustomAttribute['Model']}%> is overdue for its first service. This service is just a quick check to make sure your Ford is still running at its absolute best.<br /><br />It's important to book your service today. Just click below to contact <%${user.CustomAttribute['Dealer_Name']}%> (during business hours) or to find your nearest dealer.'''

cta1_text='''CALL <%${user.CustomAttribute['Dealer_Phone']}%>'''
cta1_url='''tel:<%${user.CustomAttribute['Dealer_Phone']}%>'''
cta2_text='''FIND A DEALER'''
cta2_url='''https://www.ford.co.th/locate-a-dealer/'''
cta2_url_link_name='''find_dealer'''



[[module]] #Split 04
path='email_modules/split/04'
color='green'

  title='''Save big on oil'''
  copy='''Keep your engine running smoothly. Enjoy a 300 THB discount when you buy any of our Oil Save Packs! '''
  cta1_text='''FIND OUT MORE'''
cta1_url='''https://www.ford.co.th/owner/oil-save-pack/'''
cta1_icon='''more'''
cta1_link_name = '''OSP'''
image = '''th_edm2_savebigonoil_20160801'''

[[module]] #TH Social
path='email_modules/footer/th/social'
color='white'

[[module]] #TH Online
path='email_modules/footer/th/online'
color='white'
+++