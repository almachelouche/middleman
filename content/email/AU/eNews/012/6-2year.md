+++
markets = ["au"]
title = '''AU Enews 012 6-2year'''


[[module]] 
path='email_modules/preheader'
color='''white'''

   preheader='''Which will arrive first: Autonomous cars or delivery drones?'''

[[module]]
path='email_modules/body'
color='''white'''

[[module]]
path='email_modules/preheader'
color='''white'''

   preheader='''Which arrives first: Autonomous cars or delivery drones?'''

  [[module]] #Header eNews 
path='email_modules/header/enews'
color='black'

  title = '''Insider'''
  date = '''June 2017'''
  copy = '''IN THIS ISSUE:<br />Future with Ford | Genuine Ford Accessories | VIDEO: Brake Tips | Watch Ranger vs Skydiver '''

[[module]] #Header Logo  
path='email_modules/header/logodesktop'
color='black'

  image = '''black'''
  url_link = '''https://www.ford.com.au/'''

[[module]] #eNews Top Story 
path='email_modules/custom/enews_topstory'
color='black'

 title = '''See into the future'''
  copy = '''Do parcel-delivering drones and autonomous cars sound like science fiction? According to the innovators who attended the Future with Ford event, these disruptive technologies are on their way and will change the way we move.'''
  cta1_text = '''LEARN MORE'''
  cta1_url = '''https://www.ford.com.au/about-ford/newsroom/2017/thought-leaders-and-innovators-define-the-mobility-revolution--u/'''
  cta1_link_name = '''innovation'''
  cta1_icon = '''more'''

  [[module]] #Banner Image #NON NSW
path='email_modules/image/banner'
color='white'

  image = '''AU_edm6_futurist_20170523'''
  url_link = '''https://www.ford.com.au/about-ford/newsroom/2017/thought-leaders-and-innovators-define-the-mobility-revolution--u/'''

[[module]] #Split 01 #RANGER AND EVEREST
path='email_modules/split/01'
color='lightblue'
segmentif = ["(user.CustomAttribute['Model'] == 'Ranger') || (user.CustomAttribute['Model'] == 'Everest')"]

title = '''Time to get personal'''
  copy = '''Are you ready to take your off roader to the next level? Get weekend-ready with Ford Genuine Accessories, designed to deliver the durability and safety you need. Learn why quality matters when it comes to accessories.'''
  cta1_text = '''WATCH NOW'''
  cta1_url = '''https://youtu.be/HBeICA1vMeI'''
  cta1_link_name = '''accessories1'''
  cta1_icon = '''play'''
  image = '''AU_edm6_accessories_20170614'''

[[module]] #Split 01 #NON RANGER AND EVEREST
path='email_modules/split/01'
color='lightblue'
segmentelse = ["(user.CustomAttribute['Model'] == 'non-Ranger or non-Everest')"]

title = '''Time to get personal'''
  copy = '''When it comes to personalising your Ford, nothing beats Ford Genuine Accessories. Genuine accessories undergo years of safety and durability testing, ensuring they integrate perfectly with your Ford.'''
  cta1_text = '''GET ACCESSORISED'''
  cta1_url = '''https://www.ford.com.au/forms/accessories/'''
  cta1_link_name = '''accessories1'''
  cta1_icon = '''more'''
  image = '''AU_edm6_accessories2_20170614'''

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

[[module]] #Footer AU Online
path='email_modules/footer/au/online'
color='white'
+++
