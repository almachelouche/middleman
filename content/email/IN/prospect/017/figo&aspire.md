+++
markets = ["in"]
title = '''IN Prospect 017 Figo&Aspire All'''

[[module]]
path='email_modules/preheader'


	preheader = '''Enjoy a cash back among other benefits when you buy a new Ford this month.*'''

[[module]]
path='email_modules/header/logodesktop'
color='white_pb'

	image = '''white_pb'''
	url_link = '''https://www.india.ford.com/'''

[[module]]
path = '''email_modules/image/banner_nolink'''
color = '''white'''
segmentif = ["(user.CustomAttribute['Segment'] == 'A')"]

	image = '''in_edm6_east_figo_aspire_20170905'''
    
[[module]]
path = '''email_modules/image/banner_nolink'''
color = '''white'''
segmentelseif = ["(user.CustomAttribute['Segment'] == 'B')"]

	image = '''in_edm6_west_figo_aspire_20170905'''
    
[[module]]
path = '''email_modules/image/banner_nolink'''
color = '''white'''
segmentelseif = ["(user.CustomAttribute['Segment'] == 'C')"]

	image = '''in_edm6_north_figo_aspire_20170905'''

[[module]]
path = '''email_modules/image/banner_nolink'''
color = '''white'''
segmentelseif = ["(user.CustomAttribute['Segment'] == 'D')"]

	image = '''in_edm5_jandk_figo_aspire_20170906'''

[[module]]
path = '''email_modules/image/banner_nolink'''
color = '''white'''
segmentelseif = ["(user.CustomAttribute['Segment'] == 'O')"]

	image = '''in_edm5_tamilnadu_figo_aspire_20170906'''

[[module]]
path = '''email_modules/image/banner_nolink'''
color = '''white'''
segmentif = ["(user.CustomAttribute['Segment'] == 'K')"]

	image = '''in_edm5_dussehraap_figo_aspire_20170907'''
    
[[module]]
path = '''email_modules/image/banner_nolink'''
color = '''white'''
segmentelseif = ["(user.CustomAttribute['Segment'] == 'L')"]

	image = '''in_edm5_dussehrakarnataka_figo_aspire_20170907'''

[[module]]
path='email_modules/spacer/default'
color='white'

	height="20"

[[module]]
path='email_modules/singles/2ctablocksideoutline'
color='''white'''
	cta1_text = '''BOOK A TEST DRIVE'''
	cta1_url = '''https://www.india.ford.com/#/overlay/content/ford/in/en_in/site-wide-content/overlays/forms/test-drive-generic.html/'''
	cta1_link_name = '''test_drive'''
    cta2_text = '''&nbsp;&nbsp;&nbsp;&nbsp;FIND A DEALER&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'''
	cta2_url = '''https://www.india.ford.com/locate-dealer/'''
	cta2_link_name = '''locate_dealer'''

[[module]]
path='email_modules/spacer/default'
color='white'

	height="30"

[[module]]
path='email_modules/singles/copy'
color='''white'''
segmentif = ["(user.CustomAttribute['Segment'] == 'A')"]

	copy = '''This Durga Puja, make a new beginning with Ford. Drive home with the spirit of the festival season.
    <br /><br />
    <span style="font-weight:bold">Buy a Ford Aspire or Next-Gen Ford Figo, and get Cash Discount + Exchange Bonus + 7.99% Interest rate, and more.*
    </span>
    <br /> <br/>
    Don't wait too long because the offer ends September 30, 2017.*'''

[[module]]
path='email_modules/singles/copy'
color='''white'''
segmentelseif = ["(user.CustomAttribute['Segment'] == 'B')"]

	copy = '''This Navratri, make a new beginning with Ford. Drive home with the spirit of the festival season.
    <br /><br />
    <span style="font-weight:bold">Buy a Ford Aspire or Next-Gen Ford Figo, and get 3g Gold Coin + upto &#8377;10,000 Cash Discount + Exchange Bonus + 7.99% Interest rate, and more.* </span> 
    <br /> <br/>
    Don't wait too long because the offer ends September 30, 2017.'''

[[module]]
path='email_modules/singles/copy'
color='''white'''
segmentelseif = ["(user.CustomAttribute['Segment'] == 'C')"]

	copy = '''This Navratri, make a new beginning with Ford. Drive home with the spirit of the festival season.
    <br /><br />
    <span style="font-weight:bold">Buy a Ford Aspire or Next-Gen Ford Figo, and get a Gold Coin + upto &#8377;10,000 Cash Discount + Exchange Bonus + 7.99% Interest rate, and more.*
    </span>
    <br /> <br/>
    Don't wait too long because the offer ends September 20, 2017.*
    '''

[[module]]
path='email_modules/singles/copy'
color='''white'''
segmentelseif = ["(user.CustomAttribute['Segment'] == 'D')"]

	copy = '''This Navratri, make a new beginning with Ford. Drive home with the spirit of the festival season.
    <br /><br />
    <span style="font-weight:bold">Buy a Ford Aspire or Next-Gen Ford Figo, and get a Gold Coin + upto &#8377;10,000 Cash Discount Cash Discount + Exchange Bonus, and more. * </span>
    <br /> <br/>
    Don't wait too long because the offer ends September 20, 2017.*
    '''
    
[[module]]
path='email_modules/singles/copy'
color='''white'''
segmentelseif = ["(user.CustomAttribute['Segment'] == 'O')"]

	copy = '''With Ford's Super September Offers, now is the perfect time to get yourself a new Ford!
    <br/> 
    <br/>
    <span style="font-weight:bold">Buy a Ford Aspire or Next-Gen Ford Figo, and get a Gold Coin + upto &#8377;10,000 Cash Discount + Exchange Bonus + 7.99% Interest rate, and more.*</span>
    <br/> 
    <br/>
    Don't wait too long because the offer ends September 30, 2017.*
    '''
    
[[module]]
path='email_modules/singles/copy'
color='''white'''
segmentelseif = ["(user.CustomAttribute['Segment'] == 'K')"]

	copy = '''This Dussehra, make a new beginning with Ford. Drive home with the spirit of the festival season.
    <br /><br />
    <span style="font-weight:bold">Buy a Ford Aspire or Next-Gen Ford Figo, and get a Gold Coin + upto &#8377;10,000 Cash Discount + Exchange Bonus + 7.99% Interest rate, and more.*
    </span>
    <br /> <br/>
    Don't wait too long because the offer ends September 30, 2017.*'''
    
[[module]]
path='email_modules/singles/copy'
color='''white'''
segmentelseif = ["(user.CustomAttribute['Segment'] == 'L')"]

	copy = '''This Dussehra, make a new beginning with Ford. Drive home with the spirit of the festival season.
    <br /><br />
    <span style="font-weight:bold">Buy a Ford Aspire or Next-Gen Ford Figo, and get a Gold Coin + upto &#8377;10,000 Cash Discount + Exchange Bonus + 7.99% Interest rate, and more.*
    </span>
    <br /> <br/>
    Don't wait too long because the offer ends September 30, 2017.*'''

[[module]]
path='email_modules/dual/04'
color='white'

	title1 = '''Service Price Promise'''
	copy1 = '''We ensure that there are no surprises in your service cost. The price you see online is the price you pay.'''
	cta1a_text = '''<br /><br />KNOW MORE'''
	cta1a_url = '''https://www.fordservicepricepromise.com/'''
	cta1a_link_name = '''svc_price_promise'''
	cta1b_text = ''''''
	cta1b_url = ''''''
	cta1b_link_name = ''''''
	cta1c_text = ''''''
	cta1c_url = ''''''
	cta1c_link_name = ''''''
	icon1 = '''in_edm2_svc_wrench_20160801'''
	title2 = '''Ford Live Chat'''
	copy2 = '''Have a question now? We've got a team of advisors from 9am to 8pm on Ford chat, for you.'''
	cta2a_text = '''<br /><br /><br />CHAT NOW'''
	cta2a_url = '''https://ford-livechat.s3ae.com/in/chat.php?a=1e4b8&intgroup=c3VwcG9ydA__&hg=Pw__&hcgs=MQ__&htgs=MQ__'''
	cta2a_link_name = '''live_chat'''
	cta2b_text = ''''''
	cta2b_url = ''''''
	cta2b_link_name = ''''''
	cta2c_text = ''''''
	cta2c_url = ''''''
	cta2c_link_name = ''''''
	icon2 = '''in_edm5_livechat_darkblue_20170411'''

[[module]]
path='email_modules/footer/5icons'
color='white'

	icon1_url='''https://www.india.ford.com/locate-dealer/'''
	icon1_image='''in_dealers_20160414'''
	icon1_link_name = '''locate_dealer_footer'''
	icon2_url='''https://www.india.ford.com/finance/'''
	icon2_image='''in_ford_credit_20160401'''
	icon2_link_name = '''ford_credit'''
	icon3_url='''https://fordassured.in/'''
	icon3_image='''in_ford_assured_20160401'''
	icon3_link_name = '''ford_assured'''
	icon4_url='''tel:18004252500'''
	icon4_image='''in_customer_care_number_20160401'''
	icon4_link_name = '''tel_customer_care'''
	icon5_url='''tel:18004199000'''
	icon5_image='''in_lmc_no_20161018'''
	icon5_link_name = '''tel_toll_free'''

[[module]]
path='email_modules/footer/in/social'
color='white'

[[module]]
path='email_modules/footer/disclaimer'
color='white'
segmentif = ["(user.CustomAttribute['Segment'] == 'A')"]

	text = '''
		*Terms & conditions Apply.
        <br />
        <br />
        1. All Prices shown are ex-showroom for Next-Gen Figo Base Petrol and Ford Aspire Ambiente Petrol. The above shown models are Next-Gen Figo Titanium+ MT and Ford Aspire Titanium+ MT. 
        <br />
        <br />
        2. The Cash benefit upto &#8377;17,000/- is valid only on select Models and variants. 
        <br />
        <br />
        3. Exchange bonus will be &#8377;20,000/- on exchange of Ford Car and &#8377;15,000/- on exchange of non-Ford car. The valuation of the old car may differ and is by the independent valuers and at the sole discretion of exchange partners.
        <br />
        <br />
        4. Interest rate of 7.99% per annum is available at select dealership across India, if financed through Ford Credit India Private Limited ("Ford Credit") and cannot be exchanged for cash.
        <br />
        <br />
        5. The finance is at the sole discretion of Ford Credit. This offer is applicable for booking done between 1st September 2017 to 30th September 2017 with full payment on or before September 30, 2017. 
        <br />
        <br />
        6. Colors are indicative only and may vary due to printing constraints. Accessories shown may not be part of standard fitment.
        <br />
        <br />
        7. Ford India reserve the right to cancel, terminate or suspend this offer at any time during the campaign period without any prior notice. For more information, please contact a Ford dealer.
        '''

[[module]]
path='email_modules/footer/disclaimer'
color='white'
segmentelseif = ["(user.CustomAttribute['Segment'] == 'B')"]

	text = '''
		*Terms & conditions Apply.
        <br />
        <br />
        1. All Prices shown are ex-showroom for Next-Gen Figo Base Petrol and Ford Aspire Ambiente Petrol. The above shown models are Next-Gen Figo Titanium+ MT and Ford Aspire Titanium+ MT.
        <br />
        <br />
        2. The Cash benefit upto &#8377;10,000/- is valid only on select Models and variants .
        <br />
        <br />
        3.Exchange bonus will be &#8377;20,000/- on exchange of Ford Car and &#8377;15,000/- on exchange of non-Ford car. The valuation of the old car may differ and is by the independent valuers and at the sole discretion of exchange partners.
        <br />
        <br />
        4. Interest rate of 7.99% per annum is available at select dealership across India, if financed through Ford Credit India Private Limited ("Ford Credit") and cannot be exchanged for cash. The finance is at the sole discretion of Ford Credit.
        <br />
        <br />
        5. The 3g Gold Coin (22 carat) worth &#8377;8,688/- as on 1st September 2017 will be given on select Models and variants is applicable for booking done between 1st September 2017 to 30th September 2017 with full payment on or before September 30, 2017.
        <br />
        <br />
        6. This offer is applicable for booking done between 1st September 2017 to 30th September 2017 with full payment on or before September 30, 2017.
        <br />
        <br />
        7. Colors are indicative only and may vary due to printing constraints. Accessories shown may not be part of standard fitment.
        <br />
        <br />
        8. Ford India reserve the right to cancel, terminate or suspend this offer at any time during the campaign period without any prior notice. For more information, please contact a Ford dealer.        
       '''
        
    [[module]]
path='email_modules/footer/disclaimer'
color='white'
segmentelseif = ["(user.CustomAttribute['Segment'] == 'C')"]

	text = '''
		*Terms & conditions Apply.
        <br />
        <br />
        1. All Prices shown are ex-showroom for Next-Gen Figo Base Petrol and Ford Aspire Ambiente Petrol. The above shown models are Next-Gen Figo Titanium+ MT and Ford Aspire Titanium+ MT. 
        <br />
        <br />
        2. The Cash benefit upto &#8377;10,000/- is valid only on select Models and variants. 
        <br />
        <br />
        3. Exchange bonus will be &#8377;20,000/- on exchange of Ford Car and &#8377;15,000/- on exchange of non-Ford car. The valuation of the old car may differ and is by the independent valuers and at the sole discretion of exchange partners.
        <br />
        <br />
        4. Interest rate of 7.99% per annum is available at select dealership across India, if financed through Ford Credit India Private Limited ("Ford Credit") and cannot be exchanged for cash. The finance is at the sole discretion of Ford Credit.
        <br />
        <br />
        5. The 3g Gold Coin (22 carat) worth &#8377;8,688/- as on 1st September 2017 will be given on select Models and variants is applicable for booking done between 1st September 2017 to 20th September 2017 with full payment on or before September 30, 2017. 
        <br />
        <br />
        6. This offer is applicable for booking done between 1st September 2017 to 30th September 2017 with full payment on or before September 30, 2017. 
        <br />
        <br />
        7. Colors are indicative only and may vary due to printing constraints. Accessories shown may not be part of standard fitment. 
        <br />
        <br />
        8.  Ford India reserve the right to cancel, terminate or suspend this offer at any time during the campaign period without any prior notice. For more information, please contact a Ford dealer.          
      '''
    
    [[module]]
path='email_modules/footer/disclaimer'
color='white'
segmentelseif = ["(user.CustomAttribute['Segment'] == 'D')"]

	text = '''
		*Terms & conditions Apply.
        <br />
        <br />
        1. All Prices shown are ex-showroom for Next-Gen Figo Base Petrol and Ford Aspire Ambiente Petrol. The above shown models are Next-Gen Figo Titanium+ MT and Ford Aspire Titanium+ MT. 
        <br />
        <br />
        2.The Cash benefit upto  &#8377;10,000/- is valid only on select Models and variants. 
        <br />
        <br />
        
        3. Exchange bonus will be  &#8377;20,000/- on exchange of Ford Car and  &#8377;15,000/- on exchange of non-Ford car. The valuation of the old car may differ and is by the independent valuers and at the sole discretion of exchange partners. 
        <br />
        <br />
        4. The 3g Gold Coin (22 carat) worth &#8377;8,688/- as on 1st September 2017 will be given on select Models and variants is applicable for booking done between 1st September 2017 to 20th September 2017 with full payment on or before September 30, 2017. 
        <br />
        <br />
        5. This offer is applicable for booking done between 1st September 2017 to 30th September 2017 with full payment on or before September 30, 2017.
        <br />
        <br />
        6. Colors are indicative only and may vary due to printing constraints. Accessories shown may not be part of standard fitment.
        <br />
        <br />
        7. Ford India reserve the right to cancel, terminate or suspend this offer at any time during the campaign period without any prior notice. For more information, please contact a Ford dealer.       
       '''
       
        [[module]]
path='email_modules/footer/disclaimer'
color='white'
segmentelseif = ["(user.CustomAttribute['Segment'] == 'O')"]

	text = '''
    1. All Prices shown are ex-showroom for Next-Gen Figo Base Petrol and Ford Aspire Ambiente Petrol. The above shown models are Next-Gen Figo Titanium+ MT and Ford Aspire Titanium+ MT.
    <br/> 
    <br /> 
    2. The Cash benefit upto &#8377;10,000/- is valid only on select Models and variants.
    <br/> 
    <br /> 
    3. Exchange bonus will be &#8377;20,000/- on exchange of Ford Car and &#8377;15,000/- on exchange of non-Ford car. The valuation of the old car may differ and is by the independent valuers and at the sole discretion of exchange partners.
    <br/> 
    <br /> 
    4. Interest rate of 7.99% per annum is available at select dealership across India, if financed through Ford Credit India Private Limited ("Ford Credit") and cannot be exchanged for cash. The finance is at the sole discretion of Ford Credit.
    <br/> 
    <br /> 
    5. The 4g Gold Coin (22 carat) worth ₹11,584/- as on 1st September 2017 will be given on select Models and variants is applicable for booking done between 1st September 2017 to 30th September 2017 with full payment on or before September 30, 2017.
    <br/> 
    <br /> 
    6. This offer is applicable for booking done between 1st September 2017 to 30th September 2017 with full payment on or before September 30, 2017.
    <br/> 
    <br /> 
    7.  Colors are indicative only and may vary due to printing constraints. Accessories shown may not be part of standard fitment.
    <br/> 
    <br /> 
    8. Ford India reserve the right to cancel, terminate or suspend this offer at any time during the campaign period without any prior notice. For more information, please contact a Ford dealer.
    '''

[[module]]
path='email_modules/footer/disclaimer'
color='white'
segmentelseif = ["(user.CustomAttribute['Segment'] == 'K')"]
	text = '''
		*Terms & conditions Apply.
        <br />
        <br />
        1. All Prices shown are ex-showroom for Next-Gen Figo Base Petrol, Ford Aspire Ambiente Petrol. The above shown models are Next-Gen Figo Titanium+ MT,  Ford Aspire Titanium+ MT.
        <br />
        <br />
        2. The Cash benefit upto &#8377;10,000/- is valid only on select Models and variants. 
        <br />
        <br />
        3. Exchange bonus will be &#8377;20,000/- on exchange of Ford Car and &#8377;15,000/- on exchange of non-Ford car. The valuation of the old car may differ and is by the independent valuers and at the sole discretion of exchange partners.
        <br />
        <br />
        4. Interest rate of 7.99% per annum is available at select dealership across India, if financed through Ford Credit India Private Limited ("Ford Credit") and cannot be exchanged for cash. The finance is at the sole discretion of Ford Credit.
        <br />
        <br />
        5. The 4g Gold Coin (22 carat) worth &#8377;11,584/- as on 1st September 2017 will be given on select Models and variants is applicable for booking done between 1st September 2017 to 30th September 2017 with full payment on or before September 30, 2017. 
        <br />
        <br />
        6. This offer is applicable for booking done between 1st September 2017 to 30th September 2017 with full payment on or before September 30, 2017.
        <br />
        <br />
        7. Colors are indicative only and may vary due to printing constraints. Accessories shown may not be part of standard fitment.
        <br />
        <br />
        7.Ford India reserve the right to cancel, terminate or suspend this offer at any time during the campaign period without any prior notice. For more information, please contact a Ford dealer.           
       '''

[[module]]
path='email_modules/footer/disclaimer'
color='white'
segmentelseif = ["(user.CustomAttribute['Segment'] == 'L')"]

	text = '''
		*Terms & conditions Apply.
        <br />
        <br />
        1. All Prices shown are ex-showroom for Next-Gen Figo Base Petrol, Ford Aspire Ambiente Petrol. The above shown models are Next-Gen Figo Titanium+ MT,  Ford Aspire Titanium+ MT.
        <br />
        <br />
        2. The Cash benefit upto &#8377;10,000/- is valid only on select Models and variants. 
        <br />
        <br />
        3. Exchange bonus will be &#8377;20,000/- on exchange of Ford Car and &#8377;15,000/- on exchange of non-Ford car. The valuation of the old car may differ and is by the independent valuers and at the sole discretion of exchange partners.
        <br />
        <br />
        4. Interest rate of 7.99% per annum is available at select dealership across India, if financed through Ford Credit India Private Limited ("Ford Credit") and cannot be exchanged for cash. The finance is at the sole discretion of Ford Credit.
        <br />
        <br />
        5. The 4g Gold Coin (22 carat) worth &#8377;11,584/- as on 1st September 2017 will be given on select Models and variants is applicable for booking done between 1st September 2017 to 30th September 2017 with full payment on or before September 30, 2017. 
        <br />
        <br />
        6. This offer is applicable for booking done between 1st September 2017 to 30th September 2017 with full payment on or before September 30, 2017.
        <br />
        <br />
        7. Colors are indicative only and may vary due to printing constraints. Accessories shown may not be part of standard fitment.
        <br />
        <br />
        7.Ford India reserve the right to cancel, terminate or suspend this offer at any time during the campaign period without any prior notice. For more information, please contact a Ford dealer.           
       '''
       
[[module]]
path='email_modules/footer/in/online'
color='white'
+++