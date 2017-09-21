+++
markets = ["in"]
title = '''IN Prospect 007 all'''
draft = true

[[module]]
path='email_modules/preheader'


	preheader = '''Everyone loves a welcome gift. And when you join the Ford family now, we are happy to show our appreciation with just that. '''

[[module]] #Header Logo
path='email_modules/header/logo'
color='white'

	image = '''white'''
	url_link = '''http://www.india.ford.com/'''

[[module]] #Banner Image No Link
path='email_modules/image/banner_nolink'
color='white'

	image = '''in_edm5_price_drop_20161011'''

[[module]] #Cover 07
path='email_modules/cover/02'
color='''white'''
segmentif = ["(user.CustomAttribute['Segment'] == 'A')","(user.CustomAttribute['Segment'] == 'B')"]
segmentifdelimit=" || "

	title='''Won't you join us?'''
	copy='''Everyone loves a welcome gift. And when you join the Ford family now, we are happy to show our appreciation with just that.<br /><br />Get interest rates as low as 8.4% p.a. and assured gifts worth &#8377;10,000 on purchase of Ford Figo Aspire or the next-gen Ford Figo. Come over today! This offer only lasts until October 31.'''
	cta1_text='''FIND A DEALER'''
	cta1_url='''http://www.india.ford.com/locate-dealer?emailid=EDM_<%${user.CustomAttribute['DMCDATE']}%>_APMKTC4L_<%${user.CustomAttribute['DMCCAMPAIGN']}%>_locate-dealer'''
	cta1_link_name = ''''''

[[module]] #Cover 07
path='email_modules/cover/02'
color='''white'''
segmentelseif = ["(user.CustomAttribute['Segment'] == 'C')"]

	title='''Won't you join us?'''
	copy='''Everyone loves a welcome gift. And when you join the Ford family now, we are happy to show our appreciation with just that.<br /><br />Get interest rates as low as 8.4% p.a. and assured gifts worth &#8377;15,000 on purchase of Ford Figo Aspire or the next-gen Ford Figo. Come over today! This offer only lasts until October 31.'''
	cta1_text='''FIND A DEALER'''
	cta1_url='''http://www.india.ford.com/locate-dealer?emailid=EDM_<%${user.CustomAttribute['DMCDATE']}%>_APMKTC4L_<%${user.CustomAttribute['DMCCAMPAIGN']}%>_locate-dealer'''
	cta1_link_name = ''''''

[[module]] #Cover 07
path='email_modules/cover/02'
color='''white'''
segmentelseif = ["(user.CustomAttribute['Segment'] == 'D')"]

	title='''Won't you join us?'''
	copy='''Everyone loves a welcome gift. And when you join the Ford family now, we are happy to show our appreciation with just that.<br /><br />Get interest rates as low as 8.4% p.a. and an assured 3g gold coin on purchase of Ford Figo Aspire or the next-gen Ford Figo. Come over today! This offer only lasts until October 31.'''
	cta1_text='''FIND A DEALER'''
	cta1_url='''http://www.india.ford.com/locate-dealer?emailid=EDM_<%${user.CustomAttribute['DMCDATE']}%>_APMKTC4L_<%${user.CustomAttribute['DMCCAMPAIGN']}%>_locate-dealer'''
	cta1_link_name = ''''''

[[module]] #Cover 07
path='email_modules/cover/02'
color='''white'''
segmentelseif = ["(user.CustomAttribute['Segment'] == 'E')"]

	title='''Won't you join us?'''
	copy='''Everyone loves a welcome gift. And when you join the Ford family now, we are happy to show our appreciation with just that.<br /><br />Get interest rates as low as 8.4% p.a. on purchase of Ford Figo Aspire or the next-gen Ford Figo. Come over today!'''
	cta1_text='''FIND A DEALER'''
	cta1_url='''http://www.india.ford.com/locate-dealer?emailid=EDM_<%${user.CustomAttribute['DMCDATE']}%>_APMKTC4L_<%${user.CustomAttribute['DMCCAMPAIGN']}%>_locate-dealer'''
	cta1_link_name = ''''''

[[module]] #Cover 11
path='email_modules/cover/03'
color='''white'''

	copy='''The Next-Gen Ford Figo Titanium and Ford Aspire Titanium both deliver superior peace of mind with best-in-class 6 airbags, and first-in-class Ford MyKey<sup>&reg;</sup>.'''

[[module]]
path='email_modules/dual/04'
color='white'

	title1=''''''
	copy1='''<span style="font-weight:bold;">Next-Gen Ford Figo Titanium</span><br /><br />&#8377;5.66 Lakh (Petrol)<br />&#8377;6.54 Lakh (Diesel)'''
	cta1a_text=''''''
	cta1a_url=''''''
	cta1a_link_name = ''''''
	cta1b_text=''''''
	cta1b_url=''''''
	cta1b_link_name = ''''''
	cta1c_text=''''''
	cta1c_url=''''''
	cta1c_link_name = ''''''
	icon1=''''''
	title2=''''''
	copy2='''<span style="font-weight:bold;">Ford Aspire Titanium</span><br /><br />&#8377;5.99 Lakh (Petrol)<br />&#8377;7.09 Lakh (Diesel)'''
	cta2a_text=''''''
	cta2a_url=''''''
	cta2a_link_name = ''''''
	cta2b_text=''''''
	cta2b_url=''''''
	cta2b_link_name = ''''''
	cta2c_text=''''''
	cta2c_url=''''''
	cta2c_link_name = ''''''
	icon2=''''''

[[module]] # Custom Car 2 Column
path='email_modules/custom/2column_car'
color='black'

	image1 = '''in_edm5_2vehicle_F_Figo_20160818'''
	cta1_text = '''Explore Ford Figo'''
	cta1_url = '''http://www.india.ford.com/cars/newfigo?emailid=EDM_<%${user.CustomAttribute['DMCDATE']}%>_APMKTC4L_<%${user.CustomAttribute['DMCCAMPAIGN']}%>_new-figo'''
	cta1_icon = '''more'''
	image2 = '''in_edm5_2vehicle_F_Aspire_20160818'''
	cta2_text = '''Explore Ford Aspire'''
	cta2_url = '''http://www.india.ford.com/cars/figoaspire?emailid=EDM_<%${user.CustomAttribute['DMCDATE']}%>_APMKTC4L_<%${user.CustomAttribute['DMCCAMPAIGN']}%>_explore-Aspire'''
	cta2_icon = '''more'''

[[module]] #Cover 05
path='email_modules/cover/02'
color='''lightblue'''

	title = '''Ford Live Chat'''
	copy = '''Ford Live Chat is now online! Get real-time answers from our team of Ford Advisors between 9am to 8pm.'''
	cta1_text = '''START CHATTING'''
	cta1_url = '''https://ford-livechat.s3ae.com/in/chat.php?a=1e4b8&intgroup=c3VwcG9ydA__&hg=Pw__&hcgs=MQ__&htgs=MQ__'''
	icon = '''live_chat'''

[[module]] #Footer 5 Icons
path='email_modules/footer/5icons'
color='white'

	icon1_url='''http://www.india.ford.com/locate-dealer?emailid=EDM_<%${user.CustomAttribute['DMCDATE']}%>_APMKTC4L_<%${user.CustomAttribute['DMCCAMPAIGN']}%>_locate-dealer'''
	icon1_image='''in_dealers_20160414'''
	icon1_link_name = ''''''
	icon2_url='''http://www.india.ford.com/buying/ford-credit?emailid=EDM_<%${user.CustomAttribute['DMCDATE']}%>_APMKTC4L_<%${user.CustomAttribute['DMCCAMPAIGN']}%>_ford-credit'''
	icon2_image='''in_ford_credit_20160401'''
	icon2_link_name = ''''''
	icon3_url='''http://www.india.ford.com/buying/ford-assured?emailid=EDM_<%${user.CustomAttribute['DMCDATE']}%>_APMKTC4L_<%${user.CustomAttribute['DMCCAMPAIGN']}%>_Ford-Assured'''
	icon3_image='''in_ford_assured_20160401'''
	icon3_link_name = ''''''
	icon4_url='''tel:18004252500'''
	icon4_image='''in_customer_care_number_20160401'''
	icon4_link_name = ''''''
	icon5_url='''tel:18004199000'''
	icon5_image='''in_lmc_no_20161018'''
	icon5_link_name = ''''''

[[module]] #Footer IN Social
path='email_modules/footer/in/social'
color='white'

[[module]] #Footer Disclaimer
path='email_modules/footer/disclaimer'
color='white'
segmentif = ["(user.CustomAttribute['Segment'] == 'A')","(user.CustomAttribute['Segment'] == 'C')"]
segmentifdelimit=" || "

	text = '''Terms and conditions <br /><br />[1] Interest rate of 8.4% is applicable only at select dealership across India, if financed through Ford Credit India Private Limited ("Ford Credit") and cannot be exchanged for cash. The finance is at the sole discretion of Ford Credit.<br /><br />[2] Assured gift is applicable for select variants for bookings between 1st October to 31st October with full payment done before 31st October 2016. Please contact nearest dealer for further details. <br /><br />[3] 6 Airbags & Ford MyKey<sup>&reg;</sup> are available on Ford Aspire & Next-Gen Ford Figo Titanium+ variants only.<br /><br />[4] Prices shown are ex-showroom Delhi & have been truncated to 2 decimal points. Ex-showroom prices may differ by city.<br /><br />[5] Starting price mentioned is for Ford Aspire Titanium Petrol (Solid), Ford Aspire Titanium Diesel (Solid), Next-Gen Ford Figo Titanium Petrol and Next-Gen Ford Figo Titanium diesel variants.'''

[[module]] #Footer Disclaimer
path='email_modules/footer/disclaimer'
color='white'
segmentelseif = ["(user.CustomAttribute['Segment'] == 'B')"]

	text = '''Terms and conditions <br /><br />[1] Interest rate of 8.4% is applicable only at select dealership across India, if financed through Ford Credit India Private Limited ("Ford Credit") and cannot be exchanged for cash. The finance is at the sole discretion of Ford Credit.<br /><br />[2] Offer applicable only in Maharashtra and Goa. Assured gift is applicable for select variants for bookings between 1st October to 31st October with full payment done before 31st October 2016. Please contact nearest dealer for further details. <br /><br />[3] 6 Airbags & Ford MyKey<sup>&reg;</sup> are available on Ford Aspire & Next-Gen Ford Figo Titanium+ variants only.<br /><br />[4] Prices shown are ex-showroom Delhi & have been truncated to 2 decimal points. Ex-showroom prices may differ by city.<br /><br />[5] Starting price mentioned is for Ford Aspire Titanium Petrol (Solid), Ford Aspire Titanium Diesel (Solid), Next-Gen Ford Figo Titanium Petrol and Next-Gen Ford Figo Titanium diesel variants.'''

[[module]] #Footer Disclaimer
path='email_modules/footer/disclaimer'
color='white'
segmentelseif = ["(user.CustomAttribute['Segment'] == 'D')"]

	text = '''Terms and conditions <br /><br />[1] Interest rate of 8.4% is applicable only at select dealership across India, if financed through Ford Credit India Private Limited ("Ford Credit") and cannot be exchanged for cash. The finance is at the sole discretion of Ford Credit.<br /><br />[2] Offer applicable only in Madhya Pradesh, Chhattisgarh and Gujarat. 3g Gold Coin is worth around &#8377;10,000 and is applicable for select variants for bookings between 1st October to 31st October with full payment done before 31st October 2016. Please contact nearest dealer for further details. <br /><br />[3] 6 Airbags & Ford MyKey<sup>&reg;</sup> are available on Ford Aspire & Next-Gen Ford Figo Titanium+ variants only.<br /><br />[4] Prices shown are ex-showroom Delhi & have been truncated to 2 decimal points. Ex-showroom prices may differ by city.<br /><br />[5] Starting price mentioned is for Ford Aspire Titanium Petrol (Solid), Ford Aspire Titanium Diesel (Solid), Next-Gen Ford Figo Titanium Petrol and Next-Gen Ford Figo Titanium diesel variants.'''

[[module]] #Footer Disclaimer
path='email_modules/footer/disclaimer'
color='white'
segmentelseif = ["(user.CustomAttribute['Segment'] == 'E')"]

	text = '''Terms and conditions <br /><br />[1] Interest rate of 8.4% is applicable only at select dealership across India, if financed through Ford Credit India Private Limited ("Ford Credit") and cannot be exchanged for cash. The finance is at the sole discretion of Ford Credit. Please contact nearest dealer for further details. <br /><br />[2] 6 Airbags & Ford MyKey<sup>&reg;</sup> are available on Ford Aspire & Next-Gen Ford Figo Titanium+ variants only.<br /><br />[3] Prices shown are ex-showroom Delhi & have been truncated to 2 decimal points. Ex-showroom prices may differ by city.<br /><br />[4] Starting price mentioned is for Ford Aspire Titanium Petrol (Solid), Ford Aspire Titanium Diesel (Solid), Next-Gen Ford Figo Titanium Petrol and Next-Gen Ford Figo Titanium diesel variants.'''

[[module]] #Footer IN Online
path='email_modules/footer/in/online'
color='white'
+++