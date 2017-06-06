+++
markets = ["au"]
title = '''AU Enews 012 prospect 2'''

[[module]]
path='email_modules/preheader'
color='''white'''

   preheader='''The super-capable Everest Ambiente RWD has arrived. Want to take a ride? '''

[[module]] #Header eNews #NSW
path='email_modules/header/enews'
color='black'
segmentif = ["(user.CustomAttribute['Area'] == 'NSW')"]

  title = '''Insider'''
  date = '''June 2017'''
  copy = '''IN THIS ISSUE:<br />New Everest Ambiente | Vivid Sydney | EOFY Deals | Watch Ranger vs Skydiver'''

  [[module]] #Header eNews #NON NSW
path='email_modules/header/enews'
color='black'
segmentelse = ["(user.CustomAttribute['Area'] == 'non-NSW')"]

  title = '''Insider'''
  date = '''June 2017'''
  copy = '''IN THIS ISSUE:<br />New Everest Ambiente | Future with Ford | EOFY Deals | Watch Ranger vs Skydiver'''

[[module]] #Header Logo
path='email_modules/header/logodesktop'
color='black'

  image = '''black'''
  url_link = '''https://www.ford.com.au/'''

[[module]] # eNews Top Story
path='email_modules/custom/enews_topstory'
color='black'

  title = '''The most affordable Everest ever'''
	copy = ''' Join us in welcoming the Ford Everest Ambiente RWD to our SUV range. This capable 7-seater boasts the same 3.2L Diesel engine and 3,000&#185;kg towing capacity as its 4WD sibling. Plus with SYNC<sup>®</sup>3 connectivity system, with 8” colour touchscreen, it’s amazing value with the lowest price tag we’ve ever seen on an Everest – from $49,990&#178;!'''
  cta1_text = '''FIND OUT MORE'''
  cta1_url = '''https://www.ford.com.au/suv/everest/models/ambiente-rwd/?intcmp=vhp-return-model'''
  cta1_link_name = '''everest'''
  cta1_icon = '''more'''


  [[module]] #Banner Image
path='email_modules/image/banner'
color='white'

  image = '''AU_edm6_everest_20170601'''
  url_link = '''https://www.ford.com.au/suv/everest/models/ambiente-rwd/?intcmp=vhp-return-model'''


[[module]] #Split 01 #NSW
path='email_modules/split/01'
color='darkblue'
segmentif = ["(user.CustomAttribute['Area'] == 'NSW')"]

  title = '''Let’s Get Vivid'''
  copy = '''Ford have joined forces with Vivid Sydney to bring you a stunning festival of art, technology, light, music and ideas. Come and see Sydney at its brightest until June 17, and be sure to check out Ford’s Freedom of Movement installation. #MoveFreely.'''
  cta1_text = '''LEARN MORE'''
  cta1_url = '''https://www.vividsydney.com'''
  cta1_link_name = '''vivid'''
  cta1_icon = '''more'''
  image = '''AU_edm6_vivid_20170606'''

  [[module]] #Split 01 #NON NSW
path='email_modules/split/01'
color='darkblue'
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

  title = '''It pays to look closer'''
  copy = '''From great savings on select SUVs to Free Auto on one of Australia’s best trucks, Ford has some unbelievable deals this End of Financial Year&#179;. Spot these deals and others now, before they disappear!'''
  cta1_text = '''EXPLORE OFFERS'''
  cta1_url = '''http://www.ford.com.au/latest-offers/national/'''
  cta1_link_name = '''offer'''
  cta1_icon = '''more'''
  image = '''AU_edm6_offer2_20170531'''


  [[module]] #Split 01
path='email_modules/split/01'
color='green'

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

text='''Disclaimers:<br /><br />
  1. Maximum towing capacity when using a Genuine Ford tow pack. Subject to State and Territory regulations.<br /><br />
  2. Price is recommended, stock may vary between Dealers.<br /><br />
  3. Vehicles must be purchased by 30/06/17 and delivered by 2/07/17. Participating Dealers only. Stock may vary between Dealers. Private and Blue, Silver and Gold Business Fleet customers only.<br /><br />'''

[[module]] #Footer AU Online
path='email_modules/footer/au/online'
color='white'
+++
