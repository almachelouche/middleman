+++
markets = ["au"]
title = '''AU Enews 012 0-6 month'''

[[module]]
path='email_modules/preheader'
color='''white'''

   preheader='''Check out the latest and greatest Ford accessories'''

[[module]] #Header eNews #NSW
path='email_modules/header/enews'
color='black'
segmentif = ["(user.CustomAttribute['Area'] == 'NSW')"]

  title = '''Insider'''
  date = '''June 2017'''
  copy = '''IN THIS ISSUE:<br />Genuine Ford Accessories | Vivid Sydney | VIDEO: Brake Tips |Ford Owners App'''

  [[module]] #Header eNews #non NSW
path='email_modules/header/enews'
color='black'
segmentelse = ["(user.CustomAttribute['Area'] == 'non-NSW')"]

  title = '''Insider'''
  date = '''June 2017'''
  copy = '''IN THIS ISSUE:<br />Genuine Ford Accessories | Future with Ford | VIDEO: Brake Tips |Ford Owners App'''

[[module]] #Header Logo
path='email_modules/header/logodesktop'
color='black'

  image = '''black'''
  url_link = '''https://www.ford.com.au/'''

[[module]] # eNews Top Story  #Ranger &Everest version
path='email_modules/custom/enews_topstory'
color='black'
segmentif = ["(user.CustomAttribute['Model'] == 'Ranger') || (user.CustomAttribute['Model'] == 'Everest')"]

  title = '''Time to get personal'''
  copy = '''Are you ready to take your off roader to the next level? Get weekend ready with Ford Genuine Accessories, they’re waiting to help you take your vehicle to the limit. Learn why quality matters when it comes to accessories.'''
  cta1_text = '''WATCH NOW'''
  cta1_url = '''https://www.ford.com.au/forms/accessories/'''
  cta1_link_name = '''accessories2'''
  cta1_icon = '''more'''

[[module]] # eNews Top Story #Non Ranger &Everest version
path='email_modules/custom/enews_topstory'
color='black'
segmentelse = ["(user.CustomAttribute['Area'] == 'non-ranger/everest')"]

  title = '''Time to get personal'''
  copy = '''When it comes to personalising your Ford, nothing beats Ford Genuine Accessories. Genuine accessories undergo years of safety and durability testing, ensuring they integrate perfectly with your Ford.'''
  cta1_text = '''GET ACCESSORISED'''
  cta1_url = '''https://www.ford.com.au/forms/accessories/'''
  cta1_link_name = '''accessories1'''
  cta1_icon = '''more'''

[[module]] #Banner Image  #Ranger &Everest version
path='email_modules/image/banner'
color='white'
segmentif = ["(user.CustomAttribute['Model'] == 'Ranger') || (user.CustomAttribute['Model'] == 'Everest')"]

  image = '''AU_edm6_accessories_20170602'''
  url_link = '''https://www.ford.com.au/forms/accessories/'''

[[module]] #Banner Image  #Non Ranger &Everest version
path='email_modules/image/banner'
color='white'
segmentelse = ["(user.CustomAttribute['Area'] == 'non-ranger/everest')"]

  image = '''AU_edm6_everest_20170510'''
  url_link = '''https://www.ford.com.au/forms/accessories/'''

[[module]] #Split 01 #NSW
path='email_modules/split/01'
color='green'
segmentif = ["(user.CustomAttribute['Area'] == 'NSW')"]

title = '''Let’s Get Vivid'''
  copy = '''Ford have joined forces with Vivid Sydney to bring you a stunning festival of art, technology, light, music and ideas. Come and see Sydney at its brightest until June 17, and be sure to check out Ford’s #movefreely installation.'''
  cta1_text = '''LEARN MORE'''
  cta1_url = '''https://www.vividsydney.com'''
  cta1_link_name = '''VIVID'''
  cta1_icon = '''play'''
  image = '''AU_edm6_vivid_20170606'''

  [[module]] #Split 01 #non NSW
path='email_modules/split/01'
color='green'
segmentelse = ["(user.CustomAttribute['Area'] == 'non-NSW')"]

 title = '''See into the future'''
  copy = '''Do parcel-delivering drones and autonomous cars sound like science fiction? According to the innovators who attended the Future with Ford event, these life-changing technologies will arrive sooner than you may think. Are you ready?'''
  cta1_text = '''LEARN MORE'''
  cta1_url = '''https://www.ford.com.au/about-ford/newsroom/2017/thought-leaders-and-innovators-define-the-mobility-revolution--u/'''
  cta1_link_name = '''innovation'''
  cta1_icon = '''more'''
  image = '''AU_edm6_futurist_20170523'''


  [[module]] #Split 02
path='email_modules/split/02'
color='lightblue'

  title = '''Are your brakes safe?'''
  copy = '''Brakes don’t last forever. And when they wear out, it can spell danger for your daily commute. Discover how to keep your brakes in top shape for longer, and learn the warning signs of brakes needing attention.'''
  cta1_text = '''WATCH VIDEO'''
  cta1_url = '''https://www.youtube.com/watch?v=ZbiQXL4e5WQ'''
  cta1_link_name = '''brakes'''
  cta1_icon = '''play'''
  image = '''AU_edm6_brakes_20170427'''


[[module]] # Owner App Image Right
path='email_modules/custom/ownerapp_imgr'
color='black'

  title = '''Ford Owners App'''
  text1 = '''Want more information, tools, and tips right at your fingertips? Try the Ford Owners App.'''
  text2 = '''<br />&nbsp;&#8226;&nbsp;&nbsp;&nbsp;Streamline service reminders<br />&nbsp;&#8226;&nbsp;&nbsp;&nbsp;Locate a dealer/service centre<br />&nbsp;&#8226;&nbsp;&nbsp;&nbsp;View "how-to" videos<br />'''
  cta1_text = '''iOS'''
  cta1_url = '''https://itunes.apple.com/au/app/ford-owners/id990342351?mt=8'''
  cta1_link_name = '''ios1'''
  cta2_text = '''ANDROID'''
  cta2_url = '''https://play.google.com/store/apps/details?id=com.ford.fordowners&hl=en/'''
  cta2_link_name = '''android1'''
  image = '''owner_app_20160328'''

[[module]] #Footer AU Social
path='email_modules/footer/au/social'
color='white'

[[module]] #Footer Disclaimer
path='email_modules/footer/disclaimer'
color='white'
segmentif = ["(user.CustomAttribute['Model'] == 'Ranger') || (user.CustomAttribute['Model'] == 'Everest')"]

text='''Disclaimers:<br /><br />
* Everest Titanium shown with optional Ford snorkel and bull bar accessories.<br/><br/>'''


[[module]] #Footer Disclaimer
path='email_modules/footer/disclaimer'
color='white'
segmentelse = ["(user.CustomAttribute['Area'] == 'non-ranger/everest')"]

text='''Disclaimers:<br /><br />
* Escape Titanium shown with optional Ford carry bars and ski/snowboard carrier accessories.<br/><br/>'''

[[module]] #Footer AU Online
path='email_modules/footer/au/online'
color='white'
+++
