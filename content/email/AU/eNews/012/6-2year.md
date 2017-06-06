+++
markets = ["au"]
title = '''AU Enews 012 6-2year'''

[[module]] #NSW
path='email_modules/preheader'
color='''white'''
segmentif = ["(user.CustomAttribute['Area'] == 'NSW')"]

   preheader='''Are you ready to join the most breathtaking Vivid event ever?'''

[[module]] #NON NSW
path='email_modules/preheader'
color='''white'''
segmentelse = ["(user.CustomAttribute['Area'] == 'non-NSW')"]

   preheader='''Which will arrive first: Autonomous cars or delivery drones?'''

[[module]]
path='email_modules/body'
color='''white'''

[[module]] #NSW
path='email_modules/preheader'
color='''white'''
segmentif = ["(user.CustomAttribute['Area'] == 'NSW')"]

   preheader='''Are you ready to join the most breathtaking Vivid event ever?'''

[[module]] #NON NSW
path='email_modules/preheader'
color='''white'''
segmentelse = ["(user.CustomAttribute['Area'] == 'non-NSW')"]

   preheader='''Which arrives first: Autonomous cars or delivery drones?'''

[[module]] #Header eNews #NSW
path='email_modules/header/enews'
color='black'
segmentif = ["(user.CustomAttribute['Area'] == 'NSW')"]

  title = '''Insider'''
  date = '''June 2017'''
  copy = '''IN THIS ISSUE:<br />Vivid Sydney | Genuine Ford Accessories | VIDEO: Brake Tips | Watch Ranger vs Skydiver '''

  [[module]] #Header eNews #NON NSW
path='email_modules/header/enews'
color='black'
segmentelse = ["(user.CustomAttribute['Area'] == 'non-NSW')"]

  title = '''Insider'''
  date = '''June 2017'''
  copy = '''IN THIS ISSUE:<br />Future with Ford | Genuine Ford Accessories | VIDEO: Brake Tips | Watch Ranger vs Skydiver '''

[[module]] #Header Logo  #NSW
path='email_modules/header/logodesktop'
color='black'

  image = '''black'''
  url_link = '''https://www.ford.com.au/'''

[[module]] # eNews Top Story #NSW
path='email_modules/custom/enews_topstory'
color='black'
segmentif = ["(user.CustomAttribute['Area'] == 'NSW')"]

  title = '''Let’s Get Vivid'''
  copy = '''Ford have joined forces with Vivid Sydney to bring you a stunning festival of art, technology, light, music and ideas. Come and see Sydney at its brightest until June 17, and be sure to check out Ford’s Freedom of Movement installation. #MoveFreely.'''
  cta1_text = '''LEARN MORE'''
  cta1_url = '''https://www.vividsydney.com'''
  cta1_link_name = ''''award1'''
  cta1_icon = '''more'''

[[module]] #eNews Top Story #NON NSW
path='email_modules/custom/enews_topstory'
color='black'
segmentelse = ["(user.CustomAttribute['Area'] == 'non-NSW')"]

 title = '''See into the future'''
  copy = '''Do parcel-delivering drones and autonomous cars sound like science fiction? According to the innovators who attended the Future with Ford event, these life-changing technologies will arrive sooner than you may think. Are you ready?'''
  cta1_text = '''LEARN MORE'''
  cta1_url = '''https://www.ford.com.au/about-ford/newsroom/2017/thought-leaders-and-innovators-define-the-mobility-revolution--u/'''
  cta1_link_name = '''innovation'''
  cta1_icon = '''more'''

  [[module]] #Banner Image #NSW
path='email_modules/image/banner'
color='white'
segmentif = ["(user.CustomAttribute['Area'] == 'NSW')"]

  image = '''AU_edm6_vivid_20170523'''
  url_link = '''https://www.vividsydney.com'''

  [[module]] #Banner Image #NON NSW
path='email_modules/image/banner'
color='white'
segmentelse = ["(user.CustomAttribute['Area'] == 'non-NSW')"]

  image = '''AU_edm6_futurist_20170523'''
  url_link = '''https://www.ford.com.au/about-ford/newsroom/2017/thought-leaders-and-innovators-define-the-mobility-revolution--u/'''

[[module]] #Split 01 #RANGER AND EVEREST
path='email_modules/split/01'
color='lightblue'
segmentif = ["(user.CustomAttribute['Model'] == 'Ranger') || (user.CustomAttribute['Model'] == 'Everest')"]

title = '''Time to get personal'''
  copy = '''Are you ready to take your off roader to the next level? Get weekend-ready with Ford Genuine Accessories, designed to deliver the durability and safety you need. Learn why quality matters when it comes to accessories.'''
  cta1_text = '''WATCH NOW'''
  cta1_url = '''https://www.ford.com.au/forms/accessories/'''
  cta1_link_name = '''accessories1'''
  cta1_icon = '''more'''
  image = '''AU_edm6_accessories_20170602'''

[[module]] #Split 01 #NON RANGER AND EVEREST
path='email_modules/split/01'
color='lightblue'
segmentelse = ["(user.CustomAttribute['Area'] == 'non-Ranger or non-Everest')"]

title = '''Time to get personal'''
  copy = '''When it comes to personalising your Ford, nothing beats Ford Genuine Accessories. Genuine accessories undergo years of safety and durability testing, ensuring they integrate perfectly with your Ford.'''
  cta1_text = '''GET ACCESSORISED'''
  cta1_url = '''https://www.ford.com.au/forms/accessories/'''
  cta1_link_name = '''accessories1'''
  cta1_icon = '''more'''
  image = '''AU_edm6_ranger_20170427'''

  [[module]] #Split 02
path='email_modules/split/02'
color='green'

  title = '''Are your brakes safe?'''
  copy = '''Brakes don’t last forever. And when they wear out, it can spell danger for your daily commute. Discover how to keep your brakes in top shape for longer, and learn the warning signs of brakes needing attention.'''
  cta1_text = '''WATCH VIDEO'''
  cta1_url = '''https://www.youtube.com/watch?v=ZbiQXL4e5WQ'''
  cta1_link_name = '''brakes'''
  cta1_icon = '''play'''
  image = '''AU_edm6_brakes_20170427'''

  [[module]] #Split 01
path='email_modules/split/01'
color='darkblue'

title = '''Ranger vs Skydiver'''
  copy = '''You’ve probably never seen a skydiver land in a pickup truck, right? Well, we found someone crazy enough to try. Thankfully for him, Ranger’s next-level precision handling is up to the challenge.'''
  cta1_text = '''WATCH VIDEO'''
  cta1_url = '''https://www.youtube.com/watch?v=zZdPmyVz_Es'''
  cta1_link_name = '''ranger1'''
  cta1_icon = '''play'''
  image = '''AU_edm6_ranger_20170427'''


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
* Escape Titanium shown with optional Ford carry bars and ski/snowboard carrier accessories.<br/><br/>'''

[[module]] #Footer AU Online
path='email_modules/footer/au/online'
color='white'
+++
