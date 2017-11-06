
+++
markets = ["in"]
title = '''IN Prospect 018 Figo&Aspire'''

[[module]]
path='email_modules/preheader'


	preheader = '''Get great benefits this month only, when you drive away in a new Ford.'''

[[module]]
path='email_modules/header/logodesktop'
color='white_pb'

	image = '''white_pb'''
	url_link = '''https://www.india.ford.com/'''

[[module]]
path = '''email_modules/image/banner_nolink'''
color = '''white'''
segmentif = ["(user.CustomAttribute['Segment'] == 'A')"]

	image = '''in_edm5_MegaExchange_20171103'''

[[module]]
path = '''email_modules/image/banner_nolink'''
color = '''white'''
segmentelseif = ["(user.CustomAttribute['Segment'] == 'B')"]

	image = '''in_edm5_699_20171103'''
    
[[module]]
path='email_modules/singles/2ctablocksideoutline'
color='''white'''
	cta1_text = '''BOOK A TEST DRIVE'''
	cta1_url = '''https://www.india.ford.com/#/overlay/content/ford/in/en_in/site-wide-content/overlays/forms/test-drive-generic.html/'''
	cta1_link_name = '''test_drive'''
    cta2_text = '''&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;FIND A DEALER&nbsp;&nbsp;&nbsp;&nbsp;'''
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

	copy = '''When you purchase a Ford, you aren't just buying a great vehicle - you become part of our family. And family always gets the best deals.
    <br /><br />Buy a Ford Figo and get a cash benefit up to &#8377;6,000, plus an exchange bonus up to &#8377;15,000.
    <br /> <br/>Buy a Ford Aspire and receive a cash benefit up to &#8377;10,000, and an exchange bonus of &#8377;15,000.
    <br /> <br/>Make your move fast. These deals end November 30, 2017.*'''

[[module]]
path='email_modules/singles/copy'
color='''white'''
segmentelseif = ["(user.CustomAttribute['Segment'] == 'B')"]

	copy = '''When you purchase a Ford, you aren't just buying a great vehicle - you become part of our family. And family always gets the best deals.
    <br /><br />Buy a Ford Figo or Ford Aspire and we'll give you a 6.99% interest rate, plus an exchange bonus of &#8377;15,000.
    <br /> <br/>Make your move fast. These deals end November 30, 2017.*'''

[[module]]
path='email_modules/spacer/default'
color='white'

	height="30"

[[module]]
path='email_modules/spacer/platinum_20'
color='white'

	height="20"

[[module]]
path='email_modules/dual/05'
color='white'

	title1 = '''No-Stress Service'''
	text_box_height = '''180'''
	copy1 = '''We make service simple from day one. Discover how.'''
	image1 = '''in_edm5_service_journey_20170927'''
	image1_link_url = '''https://www.youtube.com/watch?v=EpUVjpuhxEE&t=133s/'''
	image1_link_name = '''service_journey_image'''
	title2 = '''We've Got Your Back'''
	copy2 = '''Ford don't skip on safety. Would you? Find out for yourself.'''
	image2 = '''in_edm6_safety_tvc_20170927'''
	image2_link_url = '''https://www.youtube.com/watch?v=oLJOVLqzHys'''
	image2_link_name = '''safety_video_image'''

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
path='email_modules/footer/disclaimer'
color='white'
segmentif = ["(user.CustomAttribute['Segment'] == 'A')"]

	text = '''
		*Terms & conditions Apply.
        <br />
        <br />
        1. All Prices shown are ex-showroom for Next-Gen Figo Base Petrol and Ford Aspire Ambiente Petrol.
        <br />
        <br />
        2. The Cash benefit upto &#8377;10,000/- is valid only on select Models and variants.
        <br />
        <br />
        3. Exchange bonus will be &#8377;20,000/- on exchange of Ford Car and &#8377;15,000/- on exchange of non-Ford car. The valuation of the old car may differ and is by the independent valuers and at the sole discretion of exchange partners.
        <br />
        <br />
        4. Colors are indicative only and may vary due to printing constraints.
        <br />
        <br />
        5. Accessories shown may not be part of standard fitment. 
        <br />
        <br />
        6. Mentioned offers are valid from 1st November to 30th November 2017.
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
        1. All Prices shown are ex-showroom for Next-Gen Figo Base Petrol and Ford Aspire Ambiente Petrol.
        <br />
        <br />
        2. Interest rate of 6.99% per annum is available at select dealership across India, if financed through Ford Credit India Private Limited (“Ford Credit”). The finance is at the sole discretion of Ford Credit. Interest rate of 6.99% per annum can be exchanged for cash.
        <br />
        <br />
        3. Exchange bonus will be &#8377;20,000/- on exchange of Ford Car and &#8377;15,000/- on exchange of non-Ford car. The valuation of the old car may differ and is by the independent valuers and at the sole discretion of exchange partners.
        <br />
        <br />
        4. Colors are indicative only and may vary due to printing constraints.
        <br />
        <br />
        5. Accessories shown may not be part of standard fitment. 
        <br />
        <br />
        6. Mentioned offers are valid from 1st November to 30th November 2017.
        <br />
        <br />
        7. Ford India reserve the right to cancel, terminate or suspend this offer at any time during the campaign period without any prior notice. For more information, please contact a Ford dealer.
        '''

[[module]]
path='email_modules/footer/in/online'
color='white'
+++