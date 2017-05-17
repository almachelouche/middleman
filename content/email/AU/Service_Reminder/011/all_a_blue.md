+++
markets = ["au"]
title = '''AU Service Reminder 011 All Blue back up'''

[[module]]
path='email_modules/preheaderbefore'
color='''nothing'''
segmentif = ["(user.CustomAttribute['Model'] == 'Mustang')"]

   preheader='''Book a scheduled service for your Mustang and you'll drive away in a loan car.'''

[[module]]
path='email_modules/preheaderbefore'
color='''nothing'''
segmentelse = ["yes"]

   preheader='''Don't get stuck without wheels. Book a Loan Car with every scheduled service.'''

[[module]]
path='email_modules/body'
color='''nothing'''

[[module]]
path='email_modules/preheaderafter'
color='''nothing'''
segmentif = ["(user.CustomAttribute['Model'] == 'Mustang')"]

   preheader='''Book a scheduled service for your Mustang and you'll drive away in a loan car.'''

[[module]]
path='email_modules/preheaderafter'
color='''nothing'''
segmentelse = ["yes"]

   preheader='''Don't get stuck without wheels. Book a Loan Car with every scheduled service.'''

[[module]] #Header Logo
path='email_modules/header/logo'
color='white'
segmentif = ["(user.CustomAttribute['Model'] == 'Mustang')"]

  image = '''white'''
  url_link = '''https://www.ford.com.au/'''

[[module]] #Banner Image BLACK
path='email_modules/image/banner'
color='white'
segmentif = ["(user.CustomAttribute['Model'] == 'Mustang') && (user.CustomAttribute['Series'] == 'I4') && (user.CustomAttribute['BODYSTLE'] == '2 DOOR CONVERTIBLE') && (user.CustomAttribute['Entity_Color'] == 'SHADOW BLACK')"]

  image = '''AU_edm2_ECO_Conv_BLK_20161024'''
  url_link = '''https://www.ford.com.au/owners/service/'''
  
  [[module]] #Banner Image COMPETITION ORANGE
path='email_modules/image/banner'
color='white'
segmentelseif = ["(user.CustomAttribute['Model'] == 'Mustang') && (user.CustomAttribute['Series'] == 'I4') && (user.CustomAttribute['BODYSTLE'] == '2 DOOR CONVERTIBLE') && (user.CustomAttribute['Entity_Color'] == 'COMPETITION ORANGE')"]

  image = '''AU_edm2_ECO_Conv_COM_20161024'''
  url_link = '''https://www.ford.com.au/owners/service/'''
  
  
  [[module]] #Banner Image DEEP IMPACT BLUE
path='email_modules/image/banner'
color='white'
segmentelseif = ["(user.CustomAttribute['Model'] == 'Mustang') && (user.CustomAttribute['Series'] == 'I4') && (user.CustomAttribute['BODYSTLE'] == '2 DOOR CONVERTIBLE') && (user.CustomAttribute['Entity_Color'] == 'DEEP IMPACT BLUE')"]

  image = '''AU_edm2_ECO_Conv_DIB_20161024'''
  url_link = '''https://www.ford.com.au/owners/service/'''
  
  [[module]] #Banner Image GRABBER BLUE
path='email_modules/image/banner'
color='white'
segmentelseif = ["(user.CustomAttribute['Model'] == 'Mustang') && (user.CustomAttribute['Series'] == 'I4') && (user.CustomAttribute['BODYSTLE'] == '2 DOOR CONVERTIBLE') && (user.CustomAttribute['Entity_Color'] == 'GRABBER BLUE')"]

  image = '''AU_edm2_ECO_Conv_GRB_20161024'''
  url_link = '''https://www.ford.com.au/owners/service/'''
  
  [[module]] #Banner Image GUARD
path='email_modules/image/banner'
color='white'
segmentelseif = ["(user.CustomAttribute['Model'] == 'Mustang') && (user.CustomAttribute['Series'] == 'I4') && (user.CustomAttribute['BODYSTLE'] == '2 DOOR CONVERTIBLE') && (user.CustomAttribute['Entity_Color'] == 'GUARD')"]

  image = '''AU_edm2_ECO_Conv_GUA_20161024'''
  url_link = '''https://www.ford.com.au/owners/service/'''
  
  
  [[module]] #Banner Image  INGOT SILVER 
path='email_modules/image/banner'
color='white'
segmentelseif = ["(user.CustomAttribute['Model'] == 'Mustang') && (user.CustomAttribute['Series'] == 'I4') && (user.CustomAttribute['BODYSTLE'] == '2 DOOR CONVERTIBLE') && (user.CustomAttribute['Entity_Color'] == 'INGOT SILVER')"]

  image = '''AU_edm2_ECO_Conv_IGS_20161024'''
  url_link = '''https://www.ford.com.au/owners/service/'''
  
  
  [[module]] #Banner Image MAGNETIC
path='email_modules/image/banner'
color='white'
segmentelseif = ["(user.CustomAttribute['Model'] == 'Mustang') && (user.CustomAttribute['Series'] == 'I4') && (user.CustomAttribute['BODYSTLE'] == '2 DOOR CONVERTIBLE') && (user.CustomAttribute['Entity_Color'] == 'MAGNETIC')"]

  image = '''AU_edm2_ECO_Conv_MAG_20161024'''
  url_link = '''https://www.ford.com.au/owners/service/'''
  
  [[module]] #Banner Image OXFORD WHITE
path='email_modules/image/banner'
color='white'
segmentelseif = ["(user.CustomAttribute['Model'] == 'Mustang') && (user.CustomAttribute['Series'] == 'I4') && (user.CustomAttribute['BODYSTLE'] == '2 DOOR CONVERTIBLE') && (user.CustomAttribute['Entity_Color'] == 'OXFORD WHITE')"]

  image = '''AU_edm2_ECO_Conv_OWH_20161024'''
  url_link = '''https://www.ford.com.au/owners/service/'''

  [[module]] #Banner Image RACE RED
path='email_modules/image/banner'
color='white'
segmentelseif = ["(user.CustomAttribute['Model'] == 'Mustang') && (user.CustomAttribute['Series'] == 'I4') && (user.CustomAttribute['BODYSTLE'] == '2 DOOR CONVERTIBLE') && (user.CustomAttribute['Entity_Color'] == 'RACE RED')"]

  image = '''AU_edm2_ECO_Conv_RRD_20161024'''
  url_link = '''https://www.ford.com.au/owners/service/'''
  
  [[module]] #Banner Image RUBY RED
path='email_modules/image/banner'
color='white'
segmentelseif = ["(user.CustomAttribute['Model'] == 'Mustang') && (user.CustomAttribute['Series'] == 'I4') && (user.CustomAttribute['BODYSTLE'] == '2 DOOR CONVERTIBLE') && (user.CustomAttribute['Entity_Color'] == 'RUBY RED')"]

  image = '''AU_edm2_ECO_Conv_RUB_20161024'''
  url_link = '''https://www.ford.com.au/owners/service/'''
  
  
  [[module]] #Banner Image TRIPLE YELLOW
path='email_modules/image/banner'
color='white'
segmentelseif = ["(user.CustomAttribute['Model'] == 'Mustang') && (user.CustomAttribute['Series'] == 'I4') && (user.CustomAttribute['BODYSTLE'] == '2 DOOR CONVERTIBLE') && (user.CustomAttribute['Entity_Color'] == 'TRIPLE YELLOW')"]

  image = '''AU_edm2_ECO_Conv_TRY_20161024'''
  url_link = '''https://www.ford.com.au/owners/service/'''
  
  [[module]] #Banner Image LIGHTENING BLUE
path='email_modules/image/banner'
color='white'
segmentelseif = ["(user.CustomAttribute['Model'] == 'Mustang') && (user.CustomAttribute['Series'] == 'I4') && (user.CustomAttribute['BODYSTLE'] == '2 DOOR CONVERTIBLE') && (user.CustomAttribute['Entity_Color'] == 'BLUE LIGHTNING')"]

  image = '''AU_edm2_Eco_Conv_LTB_20161026'''
  url_link = '''https://www.ford.com.au/owners/service/'''
  
  [[module]] #Banner Image WHITE PLATINUM
path='email_modules/image/banner'
color='white'
segmentelseif = ["(user.CustomAttribute['Model'] == 'Mustang') && (user.CustomAttribute['Series'] == 'I4') && (user.CustomAttribute['BODYSTLE'] == '2 DOOR CONVERTIBLE') && (user.CustomAttribute['Entity_Color'] == 'WHITE PLATM TRICOTE')"]

  image = '''AU_edm2_Eco_Conv_WPL_20161026'''
  url_link = '''https://www.ford.com.au/owners/service/'''
  
  
  [[module]] #Banner Image BLACK
path='email_modules/image/banner'
color='white'
segmentelseif = ["(user.CustomAttribute['Model'] == 'Mustang') && (user.CustomAttribute['Series'] == 'I4') && (user.CustomAttribute['BODYSTLE'] == '2 DOOR FASTBACK') && (user.CustomAttribute['Entity_Color'] == 'SHADOW BLACK')"]

  image = '''AU_edm2_ECO_FTB_BLK_20161024'''
  url_link = '''https://www.ford.com.au/owners/service/'''
  
  [[module]] #Banner Image COMPETITION ORANGE
path='email_modules/image/banner'
color='white'
segmentelseif = ["(user.CustomAttribute['Model'] == 'Mustang') && (user.CustomAttribute['Series'] == 'I4') && (user.CustomAttribute['BODYSTLE'] == '2 DOOR FASTBACK') && (user.CustomAttribute['Entity_Color'] == 'COMPETITION ORANGE')"]

  image = '''AU_edm2_ECO_FTB_COM_20161024'''
  url_link = '''https://www.ford.com.au/owners/service/'''
  
   
  [[module]] #Banner Image DEEP IMPACT BLUE
path='email_modules/image/banner'
color='white'
segmentelseif = ["(user.CustomAttribute['Model'] == 'Mustang') && (user.CustomAttribute['Series'] == 'I4') && (user.CustomAttribute['BODYSTLE'] == '2 DOOR FASTBACK') && (user.CustomAttribute['Entity_Color'] == 'DEEP IMPACT BLUE')"]

  image = '''AU_edm2_ECO_FTB_DIB_20161024'''
  url_link = '''https://www.ford.com.au/owners/service/'''
  
  [[module]] #Banner Image  GRABBER BLUE
path='email_modules/image/banner'
color='white'
segmentelseif = ["(user.CustomAttribute['Model'] == 'Mustang') && (user.CustomAttribute['Series'] == 'I4') && (user.CustomAttribute['BODYSTLE'] == '2 DOOR FASTBACK') && (user.CustomAttribute['Entity_Color'] == 'GRABBER BLUE')"]

  image = '''AU_edm2_ECO_FTB_GRB_20161024'''
  url_link = '''https://www.ford.com.au/owners/service/'''
  
  [[module]] #Banner Image GUARD
path='email_modules/image/banner'
color='white'
segmentelseif = ["(user.CustomAttribute['Model'] == 'Mustang') && (user.CustomAttribute['Series'] == 'I4') && (user.CustomAttribute['BODYSTLE'] == '2 DOOR FASTBACK') && (user.CustomAttribute['Entity_Color'] == 'GUARD')"]

  image = '''AU_edm2_ECO_FTB_GUA_20161024'''
  url_link = '''https://www.ford.com.au/owners/service/'''
  
  
  [[module]] #Banner Image INGOT SILVER
path='email_modules/image/banner'
color='white'
segmentelseif = ["(user.CustomAttribute['Model'] == 'Mustang') && (user.CustomAttribute['Series'] == 'I4') && (user.CustomAttribute['BODYSTLE'] == '2 DOOR FASTBACK') && (user.CustomAttribute['Entity_Color'] == 'INGOT SILVER')"]

  image = '''AU_edm2_ECO_FTB_IGS_20161024'''
  url_link = '''https://www.ford.com.au/owners/service/'''
  
  [[module]] #Banner Image MAGNETIC
path='email_modules/image/banner'
color='white'
segmentelseif = ["(user.CustomAttribute['Model'] == 'Mustang') && (user.CustomAttribute['Series'] == 'I4') && (user.CustomAttribute['BODYSTLE'] == '2 DOOR FASTBACK') && (user.CustomAttribute['Entity_Color'] == 'MAGNETIC')"]

  image = '''AU_edm2_ECO_FTB_MAG_20161024'''
  url_link = '''https://www.ford.com.au/owners/service/'''
  
  [[module]] #Banner Image RACE RED
path='email_modules/image/banner'
color='white'
segmentelseif = ["(user.CustomAttribute['Model'] == 'Mustang') && (user.CustomAttribute['Series'] == 'I4') && (user.CustomAttribute['BODYSTLE'] == '2 DOOR FASTBACK') && (user.CustomAttribute['Entity_Color'] == 'RACE RED')"]

  image = '''AU_edm2_ECO_FTB_RRD_20161024'''
  url_link = '''https://www.ford.com.au/owners/service/'''
  
  [[module]] #Banner Image OXFORD WHITE
path='email_modules/image/banner'
color='white'
segmentelseif = ["(user.CustomAttribute['Model'] == 'Mustang') && (user.CustomAttribute['Series'] == 'I4') && (user.CustomAttribute['BODYSTLE'] == '2 DOOR FASTBACK') && (user.CustomAttribute['Entity_Color'] == 'OXFORD WHITE')"]

  image = '''AU_edm2_ECO_FTB_OWH_20161024'''
  url_link = '''https://www.ford.com.au/owners/service/'''
  
  [[module]] #Banner Image TRIPLE YELLOW
path='email_modules/image/banner'
color='white'
segmentelseif = ["(user.CustomAttribute['Model'] == 'Mustang') && (user.CustomAttribute['Series'] == 'I4') && (user.CustomAttribute['BODYSTLE'] == '2 DOOR FASTBACK') && (user.CustomAttribute['Entity_Color'] == 'TRIPLE YELLOW')"]

  image = '''AU_edm2_ECO_FTB_TRY_20161024'''
  url_link = '''https://www.ford.com.au/owners/service/'''
  
  
  [[module]] #Banner Image LIGHTENING BLUE
path='email_modules/image/banner'
color='white'
segmentelseif = ["(user.CustomAttribute['Model'] == 'Mustang') && (user.CustomAttribute['Series'] == 'I4') && (user.CustomAttribute['BODYSTLE'] == '2 DOOR FASTBACK') && (user.CustomAttribute['Entity_Color'] == 'BLUE LIGHTNING')"]

  image = '''AU_edm2_Eco_FTB_LTB_20161026'''
  url_link = '''https://www.ford.com.au/owners/service/'''
  
  [[module]] #Banner Image RUBY RED
path='email_modules/image/banner'
color='white'
segmentelseif = ["(user.CustomAttribute['Model'] == 'Mustang') && (user.CustomAttribute['Series'] == 'I4') && (user.CustomAttribute['BODYSTLE'] == '2 DOOR FASTBACK') && (user.CustomAttribute['Entity_Color'] == 'RUBY RED')"]

  image = '''AU_edm2_Eco_FTB_RUB_20161026'''
  url_link = '''https://www.ford.com.au/owners/service/'''
  
  
  [[module]] #Banner Image WHITE PLATINUM
path='email_modules/image/banner'
color='white'
segmentelseif = ["(user.CustomAttribute['Model'] == 'Mustang') && (user.CustomAttribute['Series'] == 'I4') && (user.CustomAttribute['BODYSTLE'] == '2 DOOR FASTBACK') && (user.CustomAttribute['Entity_Color'] == 'WHITE PLATM TRICOTE')"]

  image = '''AU_edm2_Eco_FTB_WPL_20161026'''
  url_link = '''https://www.ford.com.au/owners/service/'''
  
  
  [[module]] #Banner Image BLACK
path='email_modules/image/banner'
color='white'
segmentelseif = ["(user.CustomAttribute['Model'] == 'Mustang') && (user.CustomAttribute['Series'] == 'GT') && (user.CustomAttribute['BODYSTLE'] == '2 DOOR CONVERTIBLE') && (user.CustomAttribute['Entity_Color'] == 'SHADOW BLACK')"]

  image = '''AU_edm2_GT_Conv_BLK_20161024'''
  url_link = '''https://www.ford.com.au/owners/service/'''
  
  [[module]] #Banner Image COMPETITION ORANGE
path='email_modules/image/banner'
color='white'
segmentelseif = ["(user.CustomAttribute['Model'] == 'Mustang') && (user.CustomAttribute['Series'] == 'GT') && (user.CustomAttribute['BODYSTLE'] == '2 DOOR CONVERTIBLE') && (user.CustomAttribute['Entity_Color'] == 'COMPETITION ORANGE')"]

  image = '''AU_edm2_GT_Conv_COM_20161024'''
  url_link = '''https://www.ford.com.au/owners/service/'''
  
  
  [[module]] #Banner Image DEEP IMPACT BLUE
path='email_modules/image/banner'
color='white'
segmentelseif = ["(user.CustomAttribute['Model'] == 'Mustang') && (user.CustomAttribute['Series'] == 'GT') && (user.CustomAttribute['BODYSTLE'] == '2 DOOR CONVERTIBLE') && (user.CustomAttribute['Entity_Color'] == 'DEEP IMPACT BLUE')"]

  image = '''AU_edm2_GT_Conv_DIB_20161024'''
  url_link = '''https://www.ford.com.au/owners/service/'''
  
  [[module]] #Banner Image GRABBER BLUE
path='email_modules/image/banner'
color='white'
segmentelseif = ["(user.CustomAttribute['Model'] == 'Mustang') && (user.CustomAttribute['Series'] == 'GT') && (user.CustomAttribute['BODYSTLE'] == '2 DOOR CONVERTIBLE') && (user.CustomAttribute['Entity_Color'] == 'GRABBER BLUE')"]

  image = '''AU_edm2_GT_Conv_GRB_20161024'''
  url_link = '''https://www.ford.com.au/owners/service/'''
  
  [[module]] #Banner Image GUARD
path='email_modules/image/banner'
color='white'
segmentelseif = ["(user.CustomAttribute['Model'] == 'Mustang') && (user.CustomAttribute['Series'] == 'GT') && (user.CustomAttribute['BODYSTLE'] == '2 DOOR CONVERTIBLE') && (user.CustomAttribute['Entity_Color'] == 'GUARD')"]

  image = '''AU_edm2_GT_Conv_GUA_20161024'''
  url_link = '''https://www.ford.com.au/owners/service/'''
  
  
  [[module]] #Banner Image INGOT SILVER
path='email_modules/image/banner'
color='white'
segmentelseif = ["(user.CustomAttribute['Model'] == 'Mustang') && (user.CustomAttribute['Series'] == 'GT') && (user.CustomAttribute['BODYSTLE'] == '2 DOOR CONVERTIBLE') && (user.CustomAttribute['Entity_Color'] == 'INGOT SILVER')"]

  image = '''AU_edm2_GT_Conv_IGS_20161024'''
  url_link = '''https://www.ford.com.au/owners/service/'''
  
  
  [[module]] #Banner Image MAGNETIC
path='email_modules/image/banner'
color='white'
segmentelseif = ["(user.CustomAttribute['Model'] == 'Mustang') && (user.CustomAttribute['Series'] == 'GT') && (user.CustomAttribute['BODYSTLE'] == '2 DOOR CONVERTIBLE') && (user.CustomAttribute['Entity_Color'] == 'MAGNETIC')"]

  image = '''AU_edm2_GT_Conv_MAG_20161024'''
  url_link = '''https://www.ford.com.au/owners/service/'''
  
  [[module]] #Banner Image OXFORD WHITE
path='email_modules/image/banner'
color='white'
segmentelseif = ["(user.CustomAttribute['Model'] == 'Mustang') && (user.CustomAttribute['Series'] == 'GT') && (user.CustomAttribute['BODYSTLE'] == '2 DOOR CONVERTIBLE') && (user.CustomAttribute['Entity_Color'] == 'OXFORD WHITE')"]

  image = '''AU_edm2_GT_Conv_OWH_20161024'''
  url_link = '''https://www.ford.com.au/owners/service/'''
  
  [[module]] #Banner Image RACE RED
path='email_modules/image/banner'
color='white'
segmentelseif = ["(user.CustomAttribute['Model'] == 'Mustang') && (user.CustomAttribute['Series'] == 'GT') && (user.CustomAttribute['BODYSTLE'] == '2 DOOR CONVERTIBLE') && (user.CustomAttribute['Entity_Color'] == 'RACE RED')"]

  image = '''AU_edm2_GT_Conv_RRD_20161024'''
  url_link = '''https://www.ford.com.au/owners/service/'''
  
  [[module]] #Banner Image RUBY RED
path='email_modules/image/banner'
color='white'
segmentelseif = ["(user.CustomAttribute['Model'] == 'Mustang') && (user.CustomAttribute['Series'] == 'GT') && (user.CustomAttribute['BODYSTLE'] == '2 DOOR CONVERTIBLE') && (user.CustomAttribute['Entity_Color'] == 'RUBY RED')"]

  image = '''AU_edm2_GT_Conv_RUB_20161024'''
  url_link = '''https://www.ford.com.au/owners/service/'''
  
  
  [[module]] #Banner Image TRIPLE YELLOW
path='email_modules/image/banner'
color='white'
segmentelseif = ["(user.CustomAttribute['Model'] == 'Mustang') && (user.CustomAttribute['Series'] == 'GT') && (user.CustomAttribute['BODYSTLE'] == '2 DOOR CONVERTIBLE') && (user.CustomAttribute['Entity_Color'] == 'TRIPLE YELLOW')"]

  image = '''AU_edm2_GT_Conv_TRY_20161024'''
  url_link = '''https://www.ford.com.au/owners/service/'''
  
  [[module]] #Banner Image LIGHTENING BLUE
path='email_modules/image/banner'
color='white'
segmentelseif = ["(user.CustomAttribute['Model'] == 'Mustang') && (user.CustomAttribute['Series'] == 'GT') && (user.CustomAttribute['BODYSTLE'] == '2 DOOR CONVERTIBLE') && (user.CustomAttribute['Entity_Color'] == 'BLUE LIGHTNING')"]

  image = '''AU_edm2_GT_Conv_LTB_20161026'''
  url_link = '''https://www.ford.com.au/owners/service/'''
  
  [[module]] #Banner Image WHITE PLATINUM
path='email_modules/image/banner'
color='white'
segmentelseif = ["(user.CustomAttribute['Model'] == 'Mustang') && (user.CustomAttribute['Series'] == 'GT') && (user.CustomAttribute['BODYSTLE'] == '2 DOOR CONVERTIBLE') && (user.CustomAttribute['Entity_Color'] == 'WHITE PLATM TRICOTE')"]

  image = '''AU_edm2_GT_Conv_WPL_20161026'''
  url_link = '''https://www.ford.com.au/owners/service/'''
  
  [[module]] #Banner Image BLACK
path='email_modules/image/banner'
color='white'
segmentelseif = ["(user.CustomAttribute['Model'] == 'Mustang') && (user.CustomAttribute['Series'] == 'GT') && (user.CustomAttribute['BODYSTLE'] == '2 DOOR FASTBACK') && (user.CustomAttribute['Entity_Color'] == 'SHADOW BLACK')"]

  image = '''AU_edm2_GT_FTB_BLK_20161024'''
  url_link = '''https://www.ford.com.au/owners/service/'''
  
  [[module]] #Banner Image COMPETITION ORANGE
path='email_modules/image/banner'
color='white'
segmentelseif = ["(user.CustomAttribute['Model'] == 'Mustang') && (user.CustomAttribute['Series'] == 'GT') && (user.CustomAttribute['BODYSTLE'] == '2 DOOR FASTBACK') && (user.CustomAttribute['Entity_Color'] == 'COMPETITION ORANGE')"]

  image = '''AU_edm2_GT_FTB_COM_20161024'''
  url_link = '''https://www.ford.com.au/owners/service/'''
  
  
  [[module]] #Banner Image DEEP IMPACT BLUE
path='email_modules/image/banner'
color='white'
segmentelseif = ["(user.CustomAttribute['Model'] == 'Mustang') && (user.CustomAttribute['Series'] == 'GT') && (user.CustomAttribute['BODYSTLE'] == '2 DOOR FASTBACK') && (user.CustomAttribute['Entity_Color'] == 'DEEP IMPACT BLUE')"]

  image = '''AU_edm2_GT_FTB_DIB_20161024'''
  url_link = '''https://www.ford.com.au/owners/service/'''
  
  [[module]] #Banner Image GRABBER BLUE
path='email_modules/image/banner'
color='white'
segmentelseif = ["(user.CustomAttribute['Model'] == 'Mustang') && (user.CustomAttribute['Series'] == 'GT') && (user.CustomAttribute['BODYSTLE'] == '2 DOOR FASTBACK') && (user.CustomAttribute['Entity_Color'] == 'GRABBER BLUE')"]

  image = '''AU_edm2_GT_FTB_GRB_20161024'''
  url_link = '''https://www.ford.com.au/owners/service/'''
  
  [[module]] #Banner Image GUARD
path='email_modules/image/banner'
color='white'
segmentelseif = ["(user.CustomAttribute['Model'] == 'Mustang') && (user.CustomAttribute['Series'] == 'GT') && (user.CustomAttribute['BODYSTLE'] == '2 DOOR FASTBACK') && (user.CustomAttribute['Entity_Color'] == 'GUARD')"]

  image = '''AU_edm2_GT_FTB_GUA_20161024'''
  url_link = '''https://www.ford.com.au/owners/service/'''
  
  
  [[module]] #Banner Image INGOT SILVER
path='email_modules/image/banner'
color='white'
segmentelseif = ["(user.CustomAttribute['Model'] == 'Mustang') && (user.CustomAttribute['Series'] == 'GT') && (user.CustomAttribute['BODYSTLE'] == '2 DOOR FASTBACK') && (user.CustomAttribute['Entity_Color'] == 'INGOT SILVER')"]

  image = '''AU_edm2_GT_FTB_IGS_20161024'''
  url_link = '''https://www.ford.com.au/owners/service/'''
  
  [[module]] #Banner Image MAGNETIC
path='email_modules/image/banner'
color='white'
segmentelseif = ["(user.CustomAttribute['Model'] == 'Mustang') && (user.CustomAttribute['Series'] == 'GT') && (user.CustomAttribute['BODYSTLE'] == '2 DOOR FASTBACK') && (user.CustomAttribute['Entity_Color'] == 'MAGNETIC')"]

  image = '''AU_edm2_GT_FTB_MAG_20161024'''
  url_link = '''https://www.ford.com.au/owners/service/'''
  
  [[module]] #Banner Image RACE RED
path='email_modules/image/banner'
color='white'
segmentelseif = ["(user.CustomAttribute['Model'] == 'Mustang') && (user.CustomAttribute['Series'] == 'GT') && (user.CustomAttribute['BODYSTLE'] == '2 DOOR FASTBACK') && (user.CustomAttribute['Entity_Color'] == 'RACE RED')"]

  image = '''AU_edm2_GT_FTB_RRD_20161024'''
  url_link = '''https://www.ford.com.au/owners/service/'''
  
  [[module]] #Banner Image RUBY RED
path='email_modules/image/banner'
color='white'
segmentelseif = ["(user.CustomAttribute['Model'] == 'Mustang') && (user.CustomAttribute['Series'] == 'GT') && (user.CustomAttribute['BODYSTLE'] == '2 DOOR FASTBACK') && (user.CustomAttribute['Entity_Color'] == 'RUBY RED')"]

  image = '''AU_edm2_GT_FTB_RUB_20161024'''
  url_link = '''https://www.ford.com.au/owners/service/'''
  
  [[module]] #Banner Image TRIPLE YELLOW
path='email_modules/image/banner'
color='white'
segmentelseif = ["(user.CustomAttribute['Model'] == 'Mustang') && (user.CustomAttribute['Series'] == 'GT') && (user.CustomAttribute['BODYSTLE'] == '2 DOOR FASTBACK') && (user.CustomAttribute['Entity_Color'] == 'TRIPLE YELLOW')"]

  image = '''AU_edm2_GT_FTB_TRY_20161024'''
  url_link = '''https://www.ford.com.au/owners/service/'''
  
  
  [[module]] #Banner Image LIGHTENING BLUE
path='email_modules/image/banner'
color='white'
segmentelseif = ["(user.CustomAttribute['Model'] == 'Mustang') && (user.CustomAttribute['Series'] == 'GT') && (user.CustomAttribute['BODYSTLE'] == '2 DOOR FASTBACK') && (user.CustomAttribute['Entity_Color'] == 'BLUE LIGHTNING')"]

  image = '''AU_edm2_GT_FTB_LTB_20161026'''
  url_link = '''https://www.ford.com.au/owners/service/'''
  
  [[module]] #Banner Image OXFORD WHITE
path='email_modules/image/banner'
color='white'
segmentelseif = ["(user.CustomAttribute['Model'] == 'Mustang') && (user.CustomAttribute['Series'] == 'GT') && (user.CustomAttribute['BODYSTLE'] == '2 DOOR FASTBACK') && (user.CustomAttribute['Entity_Color'] == 'OXFORD WHITE')"]

  image = '''AU_edm2_GT_FTB_OWH_20161026'''
  url_link = '''https://www.ford.com.au/owners/service/'''
  
  
  [[module]] #Banner Image WHITE PLATINUM
path='email_modules/image/banner'
color='white'
segmentelseif = ["(user.CustomAttribute['Model'] == 'Mustang') && (user.CustomAttribute['Series'] == 'GT') && (user.CustomAttribute['BODYSTLE'] == '2 DOOR FASTBACK') && (user.CustomAttribute['Entity_Color'] == 'WHITE PLATM TRICOTE')"]

  image = '''AU_edm2_GT_FTB_WPL_20161026'''
  url_link = '''https://www.ford.com.au/owners/service/'''
  
[[module]] #Banner Image
path='email_modules/image/banner'
color='white'
segmentelse = ["yes"]

  image = '''au_edm2_svc_20170515'''
  url_link = '''https://www.ford.com.au/owners/service/'''

  
  
[[module]]
path='email_modules/cover/03'
color='''white'''

	copy='''<br />Hi <%${user.CustomAttribute['FullName']}%><br /><br />This is just a friendly reminder that your Ford <%${user.CustomAttribute['Model']}%> is nearly due for a service. <br /><br />Book with <%${user.CustomAttribute['Dealer_Name']}%> on <%${user.CustomAttribute['Dealer_Phone']}%> today.'''

[[module]]
path='email_modules/singles/ctablock'
color='''white'''
segmentif = ["(user.CustomAttribute['SERVAPPT'] == 'YES')"]
	
	cta1_text = '''BOOK A SERVICE'''
	cta1_url = '''https://consumer.xtime.net.au/scheduling/?company=14745&store=<%${user.CustomAttribute['DealerCode']}%>&VIN=<%${user.CustomAttribute['VIN']}%>&provider=FORD_AU_THE_BLUE_HIVE&keyword=<%${user.CustomAttribute['CampaignID']}%>&dest=&extid=<%${user.CustomAttribute['CampaignID']}%>&extctxt=FORD_AU_THE_BLUE_HIVE&cfn=<%${user.CustomAttribute['FullName']}%>&cln=<%${user['LastName']}%>&cpn=<%${user.CustomAttribute['Mobile_Phone']}%>&cem=<%${user.CustomAttribute['RealEmail']}%>&button=blue'''
	cta1_link_name = '''SERVICE'''

[[module]] #4 Images  #Mustang+ROUTINE SYNC
path = '''email_modules/image/4images'''
color = '''white'''
segmentif = ["(user.CustomAttribute['SYNC_Available'] == 'YES')"]

  image1 = '''au_svc_icon1A'''
	image1_url = '''https://www.ford.com.au/owners/service/'''
	image1_link_name = '''icon4'''
  image2 = '''au_svc_icon2'''
	image2_url = '''https://www.ford.com.au/owners/service/calculator?edm'''
	image2_link_name = '''icon5'''
  image3 = '''au_svc_icon_20170517'''
	image3_url = '''https://www.ford.com.au/owners/service/roadside-assistance/'''
	image3_link_name = '''icon6'''
  image4 = '''au_svc_icon4A'''
	image4_url = '''https://www.ford.com.au/owners/vehicle-support/sat-nav-map/'''
	image4_link_name = '''icon7'''

[[module]] #3 Images #ROUTINE NO SYNC
path = '''email_modules/image/3images'''
color = '''white'''
segmentelse = ["(user.CustomAttribute['SYNC_Available'] == 'NO') && (user.CustomAttribute['Model'] != 'Mustang')"]

  image1 = '''au_svc_icon1A'''
	image1_url = '''https://www.ford.com.au/owners/service/'''
	image1_link_name = '''icon1'''
  image2 = '''au_svc_icon2'''
	image2_url = '''https://www.ford.com.au/owners/service/calculator?edm'''
	image2_link_name = '''icon2'''
  image3 = '''au_svc_icon_20170517'''
	image3_url = '''https://www.ford.com.au/owners/service/roadside-assistance/'''
	image3_link_name = '''icon3'''

[[module]] #Cover 13   #Mustang
path='email_modules/cover/04'
color='white'
segmentif = ["(user.CustomAttribute['Model'] == 'Mustang')"]

  title = '''Cover 13'''
  copy = ''' As someone with a genuine passion for performance, we're sure you'll appreciate the many benefits of putting your pony in the trusted hands of Ford factory trained technicians who use diagnostic equipment specifically designed for Fords.<br /><br />You'll also receive <%${user.CustomAttribute['StateAutoClub']}%> Roadside Assistance and Membership¹ for up to 12 months, map updates for your SYNC® 2 Satellite Navigation System² when required, and you can even book a loan car³ so we can keep you on the road.<br /><br /> '''
  cta1_url = '''https://www.ford.com.au/owners/service/'''
  cta1_text = '''FIND OUT MORE'''
  cta1_icon = '''more'''  
  
  
  
  [[module]] #Cover 13  #ROUTINE SYNC
path='email_modules/cover/04'
color='white'
segmentelseif = ["(user.CustomAttribute['SYNC_Available'] == 'YES')"]

  title = '''Cover 13'''
  copy = '''We know how important your <%${user.CustomAttribute['Model']}%> is to you, so we're sure you'll appreciate the many benefits of putting your <%${user.CustomAttribute['Model']}%> in the trusted hands of Ford trained technicians who use diagnostic equipment specifically designed for Fords.<br /><br />You'll also receive <%${user.CustomAttribute['StateAutoClub']}%> Roadside Assistance and Membership¹ for up to 12 months, map updates for your SYNC® 2 Satellite Navigation System² when required, and you can even book a loan car³ so we can keep you on the road.<br /><br /> '''
  cta1_url = '''https://www.ford.com.au/owners/service/'''
  cta1_text = '''FIND OUT MORE'''
  cta1_icon = '''more'''  
  
[[module]] #Cover 13  #ROUTINE NO SYNC
path='email_modules/cover/04'
color='white'
segmentelse = ["(user.CustomAttribute['SYNC_Available'] == 'NO') && (user.CustomAttribute['Model'] != 'Mustang')"]

  title = '''Cover 13'''
  copy = '''We know how important your <%${user.CustomAttribute['Model']}%> is to you, so we're sure you'll appreciate the many benefits of putting your <%${user.CustomAttribute['Model']}%> in the trusted hands of Ford trained technicians who use diagnostic equipment specifically designed for Fords.<br /><br />You'll also receive <%${user.CustomAttribute['StateAutoClub']}%> Roadside Assistance and Membership¹ for up to 12 months and you can even book a loan car² so we can keep you on the road.'''
  cta1_url = '''https://www.ford.com.au/owners/service/'''
  cta1_text = '''FIND OUT MORE'''
  cta1_icon = '''more'''

[[module]] #Mustang+ROUTINE SYNC
path='email_modules/cover/01'
color='''white'''
segmentif = ["(user.CustomAttribute['SYNC_Available'] == 'YES')"]

	icon='''au_edm2_calculator_20161014'''
	title='''Ford's Service Price Promise&#8308;'''
	copy='''Find out the most your standard service will cost before you drive in, try our <a href="https://www.ford.com.au/owners/service/calculator?edm" name="calculator1" style="text-decoration:underline; color:#2D96CD">service calculator.</a>'''
[[module]] #ROUTINE NO SYNC
path='email_modules/cover/01'
color='''white''' 
segmentelse = ["(user.CustomAttribute['SYNC_Available'] == 'YES') && (user.CustomAttribute['Model'] != 'Mustang')"]

	icon='''au_edm2_calculator_20161014'''
	title='''Ford's Service Price Promise&#179;'''
	copy='''Find out the most your standard service will cost before you drive in, try our <a href="https://www.ford.com.au/owners/service/calculator?edm" name="calculator2" style="text-decoration:underline; color:#2D96CD">service calculator.</a>'''


[[module]] #Footer AU Social
path='email_modules/footer/au/social'
color='white'

[[module]] #Footer Disclaimer #Mustang
path='email_modules/footer/disclaimer'
color='white'
segmentif = ["(user.CustomAttribute['Model'] == 'Mustang')"]

  text = '''DISCLAIMERS:<br /><br />
        1) Available to Private and Blue Business Fleet customers who have not reached 105,000km/7 years only at participating Dealers. State Auto Club Roadside Assistance & Membership is included for 12 months or until your next eligible standard service (whichever occurs first). Customers must comply with scheduled servicing intervals to maintain continuity of membership. See <a href="https://www.ford.com.au/owners/service/t-and-c/" name="terms1" style="text-decoration:underline; color:#91a4b1">www.ford.com.au/owners/service/t-and-c</a> for full terms.<br /><br /> 
        2) SYNC Gen2 (SYNC® 2) customers who complete their scheduled servicing with participating Ford Dealers will receive yearly map updates for up to 7 years (but no later than 30 September 2024). Customers must comply with scheduled servicing intervals. See <a href="https://www.ford.com.au/owners/service/t-and-c/" name="terms2" style="text-decoration:underline; color:#91a4b1">www.ford.com.au/owners/service/t-and-c</a> for full terms.<br /><br />
        3) Available at participating dealers on scheduled services or overnight warranty repairs. Private and Blue, Silver and Gold Business Fleet customers only. Booking may be required. See <a href="https://www.ford.com.au/owners/service/t-and-c/" name="terms3" style="text-decoration:underline; color:#91a4b1">www.ford.com.au/owners/service/t-and-c</a> for full terms.<br /><br /> 
        4) Available at participating Ford Dealers on vehicles built from 2007. Customers will pay equal to or less than the maximum price as published by Ford for the period of the web quote for standard items in the A and B logbook services. See <a href="https://www.ford.com.au/owners/service/t-and-c/" name="terms4" style="text-decoration:underline; color:#91a4b1"> www.ford.com.au/owners/service/t-and-c</a> for full terms.<br /><br />'''



[[module]] #Footer Disclaimer #ROUTINE SYNC
path='email_modules/footer/disclaimer'
color='white'
segmentelseif = ["(user.CustomAttribute['SYNC_Available'] == 'YES')"]

  text = '''DISCLAIMERS:<br /><br />
        1) Available to Private and Blue Business Fleet customers who have not reached 105,000km/7 years only at participating Dealers. State Auto Club Roadside Assistance & Membership is included for 12 months or until your next eligible standard service (whichever occurs first). Customers must comply with scheduled servicing intervals to maintain continuity of membership. See <a href="https://www.ford.com.au/owners/service/t-and-c/" name="terms5" style="text-decoration:underline; color:#91a4b1">www.ford.com.au/owners/service/t-and-c</a> for full terms.<br /><br /> 
        2) Customers must comply with scheduled servicing intervals. See <a href="https://www.ford.com.au/owners/service/t-and-c/" name="terms6" style="text-decoration:underline; color:#91a4b1">www.ford.com.au/owners/service/t-and-c</a> for full terms.<br /><br />
        3) Available at participating dealers on scheduled services or overnight warranty repairs. Private and Blue, Silver and Gold Business Fleet customers only. Booking may be required. See  <a href="https://www.ford.com.au/owners/service/t-and-c/" name="terms7" style="text-decoration:underline; color:#91a4b1">www.ford.com.au/owners/service/t-and-c</a> for full terms.<br /><br />
        4) Available at participating Ford Dealers on vehicles built from 2007. Customers will pay equal to or less than the maximum price as published by Ford for the period of the web quote for standard items in the A and B logbook services. See <a href="https://www.ford.com.au/owners/service/t-and-c/" name="terms8" style="text-decoration:underline; color:#91a4b1"> www.ford.com.au/owners/service/t-and-c</a> for full terms.<br /><br />'''


[[module]] #Footer Disclaimer #ROUTINE NO SYNC
path='email_modules/footer/disclaimer'
color='white'
segmentelse = ["(user.CustomAttribute['Model'] != 'Mustang') && (user.CustomAttribute['SYNC_Available'] == 'NO')"]

  text = '''DISCLAIMERS:<br /><br />
        1) Available to Private and Blue Business Fleet customers who have not reached 105,000km/7 years only at participating Dealers. State Auto Club Roadside Assistance & Membership is included for 12 months or until your next eligible standard service (whichever occurs first). Customers must comply with scheduled servicing intervals to maintain continuity of membership. See <a href="https://www.ford.com.au/owners/service/t-and-c/" name="terms9" style="text-decoration:underline; color:#91a4b1">www.ford.com.au/owners/service/t-and-c</a> for full terms.<br /><br />
        2) Available at participating dealers on scheduled services or overnight warranty repairs. Private and Blue, Silver and Gold Business Fleet customers only. Booking may be required. See <a href="https://www.ford.com.au/owners/service/t-and-c/" name="terms10" style="text-decoration:underline; color:#91a4b1">www.ford.com.au/owners/service/t-and-c</a> for full terms.<br /><br /> 
        3) Available at participating Ford Dealers on vehicles built from 2007. Customers will pay equal to or less than the maximum price as published by Ford for the period of the web quote for standard items in the A and B logbook services. See <a href="https://www.ford.com.au/owners/service/t-and-c/" name="terms11" style="text-decoration:underline; color:#91a4b1"> www.ford.com.au/owners/service/t-and-c</a> for full terms.<br /><br />'''
    

[[module]] #Footer AU Online
path='email_modules/footer/au/online'
color='white'
+++