+++
markets = ["in"]
title = '''IN Prospect 017 Figo&Aspire'''

[[module]]
path='email_modules/preheader'


	preheader = ''''''

[[module]]
path='email_modules/header/logodesktop'
color='white_pb'

	image = '''white_pb'''
	url_link = '''https://www.india.ford.com/'''

[[module]]
path = '''email_modules/image/banner_nolink'''
color = '''white'''
segmentif = ["(user.CustomAttribute['Segment'] == 'A')"]

	image = '''in_edm2_reunion_season2_20170814'''
    
[[module]]
path = '''email_modules/image/banner_nolink'''
color = '''white'''
segmentelseif = ["(user.CustomAttribute['Segment'] == 'B')"]

	image = '''in_edm2_reunion_season2_20170814'''
    
[[module]]
path = '''email_modules/image/banner_nolink'''
color = '''white'''
segmentelseif = ["(user.CustomAttribute['Segment'] == 'C')"]

	image = '''in_edm2_reunion_season2_20170814'''

[[module]]
path = '''email_modules/image/banner_nolink'''
color = '''white'''
segmentelseif = ["(user.CustomAttribute['Segment'] == 'D')"]

	image = '''in_edm2_reunion_season2_20170814'''

[[module]]
path='email_modules/spacer/default'
color='white'

	height="30"

[[module]]
path='email_modules/singles/2ctablocksideoutline'
color='''white'''
	cta1_text = '''BOOK A TEST DRIVE'''
	cta1_url = '''https://www.india.ford.com/#/overlay/content/ford/in/en_in/site-wide-content/overlays/forms/test-drive-generic.html/'''
	cta1_link_name = '''test_drive'''
		cta2_text = '''&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;FIND A DEALER&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'''
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

	copy = '''Keep the spirit of Ganesh Chaturthi high with Ford's Test Drive Challenge. Buy a <span style="font-weight:bold">Ford Aspire</span>, get Cash benefit* upto <span style="font-weight:bold">&#8377;10,000 + Exchange Bonus of &#8377;15,000* + 8.15% Interest Rate*</span>
    <br /><br />
    Put your thoughts about buying that new car into action Now. You also get an <span style="font-weight:bold">Assured Gift*</span> on your car purchase. Don't wait because the <span style="font-weight:bold">offer ends August 31, 2017</span>.'''

[[module]]
path='email_modules/singles/copy'
color='''white'''
segmentelseif = ["(user.CustomAttribute['Segment'] == 'B')"]

	copy = '''Keep the spirit of Ganesh Chaturthi high with Ford's Test Drive Challenge. Buy a <span style="font-weight:bold">Ford Aspire</span>, get Cash benefit* upto <span style="font-weight:bold">&#8377;10,000 + Exchange Bonus of &#8377;15,000* + 8.15% Interest Rate*</span>
    <br /><br />
    Put your thoughts about buying that new car into action Now. You also get an <span style="font-weight:bold">Assured Gift*</span> on your car purchase. Don't wait because the <span style="font-weight:bold">offer ends August 31, 2017</span>.'''

[[module]]
path='email_modules/singles/copy'
color='''white'''
segmentelseif = ["(user.CustomAttribute['Segment'] == 'C')"]

	copy = '''Keep the spirit of Ganesh Chaturthi high with Ford's Test Drive Challenge. Buy a <span style="font-weight:bold">Ford Aspire</span>, get Cash benefit* upto <span style="font-weight:bold">&#8377;10,000 + Exchange Bonus of &#8377;15,000* + 8.15% Interest Rate*</span>
    <br /><br />
    Put your thoughts about buying that new car into action Now. You also get an <span style="font-weight:bold">Assured Gift*</span> on your car purchase. Don't wait because the <span style="font-weight:bold">offer ends August 31, 2017</span>.'''

[[module]]
path='email_modules/singles/copy'
color='''white'''
segmentelseif = ["(user.CustomAttribute['Segment'] == 'D')"]

	copy = '''Keep the spirit of Ganesh Chaturthi high with Ford's Test Drive Challenge. Buy a <span style="font-weight:bold">Ford Aspire</span>, get Cash benefit* upto <span style="font-weight:bold">&#8377;10,000 + Exchange Bonus of &#8377;15,000* + 8.15% Interest Rate*</span>
    <br /><br />
    Put your thoughts about buying that new car into action Now. You also get an <span style="font-weight:bold">Assured Gift*</span> on your car purchase. Don't wait because the <span style="font-weight:bold">offer ends August 31, 2017</span>.'''

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
        1. All Prices shown are ex-showroom Mumbai for Next-Gen Ford Figo Base Petrol and Ford Aspire Ambiente Petrol. The above shown vehicle models are Next-Gen Figo 1.5D Sports Edition MT and Ford Aspire 1.5D Sports Edition MT.
        <br />
        <br />
        2. The Gift voucher can be availed by customer only if he has taken a test drive of Ford Figo and/or Ford Aspire at any Ford authorized dealership, and bought any other competition brand vehicle after taking test drive of above mentioned Ford car/s.
        <br />
        <br />
        3. To avail gift, it is mandatory to have met the following conditions within 01-31 August, herein referred to as "campaign period"-
        <br />
        <span style="padding-left: 10px; display: block;">1. Test drive taken within campaign period / Other brand vehicle purchased between campaign period / proof of other vehicle purchase to be submitted between campaign period.</span>
        <br />
        <br />
        4. The Cash benefit upto &#8377;6,000 on Ford Figo and upto &#8377;10,000 on Ford Aspire, is valid only on select variants of the models on offer.
        <br />
        <br />
        5. Exchange bonus will be &#8377;20,000/- on exchange of any Ford Car and &#8377;15,000/- on exchange of a non-Ford car. The valuation of the old car may differ and is by the independent valuers and at the sole discretion of exchange partners.
        <br />
        <br />
        6. Interest rate of 8.15% per annum is available at select dealership across India, if financed through Ford Credit India Private Limited ("Ford Credit") and cannot be exchanged for cash. The finance is at the sole discretion of Ford Credit.
        <br />
        <br />
        7. The assured gift is worth &#8377;8,000/- and is applicable on purchase select Models and/or variants and for booking done between 01-31 August, with full payment on or before 31 August, 2017. 
        <br />
        <br />
        8. This offer is only available in Maharashtra and Goa and is applicable for booking done between 1st August 2017 to 31st August 2017 with full payment on or before 31st August, 2017.
        <br />
        <br />
        9. Colors are indicative only and may vary due to printing constraints. Accessories shown may not be part of standard fitment. 
        <br />
        <br />
        10. Ford India reserve the right to cancel, terminate or suspend this offer at any time during the campaign period without any prior notice. For more information, please contact an Ford authorized dealer.'''

[[module]]
path='email_modules/footer/disclaimer'
color='white'
segmentelseif = ["(user.CustomAttribute['Segment'] == 'B')"]

	text = '''
		*Terms & conditions Apply.
        <br />
        <br />
        1. All Prices shown are ex-showroom Mumbai for Next-Gen Ford Figo Base Petrol and Ford Aspire Ambiente Petrol. The above shown vehicle models are Next-Gen Figo 1.5D Sports Edition MT and Ford Aspire 1.5D Sports Edition MT.
        <br />
        <br />
        2. The Gift voucher can be availed by customer only if he has taken a test drive of Ford Figo and/or Ford Aspire at any Ford authorized dealership, and bought any other competition brand vehicle after taking test drive of above mentioned Ford car/s.
        <br />
        <br />
        3. To avail gift, it is mandatory to have met the following conditions within 01-31 August, herein referred to as "campaign period"-
        <br />
        <span style="padding-left: 10px; display: block;">1. Test drive taken within campaign period / Other brand vehicle purchased between campaign period / proof of other vehicle purchase to be submitted between campaign period.</span>
        <br />
        <br />
        4. The Cash benefit upto &#8377;6,000 on Ford Figo and upto &#8377;10,000 on Ford Aspire, is valid only on select variants of the models on offer.
        <br />
        <br />
        5. Exchange bonus will be &#8377;20,000/- on exchange of any Ford Car and &#8377;15,000/- on exchange of a non-Ford car. The valuation of the old car may differ and is by the independent valuers and at the sole discretion of exchange partners.
        <br />
        <br />
        6. Interest rate of 8.15% per annum is available at select dealership across India, if financed through Ford Credit India Private Limited ("Ford Credit") and cannot be exchanged for cash. The finance is at the sole discretion of Ford Credit.
        <br />
        <br />
        7. The assured gift is worth &#8377;8,000/- and is applicable on purchase select Models and/or variants and for booking done between 01-31 August, with full payment on or before 31 August, 2017. 
        <br />
        <br />
        8. This offer is only available in Maharashtra and Goa and is applicable for booking done between 1st August 2017 to 31st August 2017 with full payment on or before 31st August, 2017.
        <br />
        <br />
        9. Colors are indicative only and may vary due to printing constraints. Accessories shown may not be part of standard fitment. 
        <br />
        <br />
        10. Ford India reserve the right to cancel, terminate or suspend this offer at any time during the campaign period without any prior notice. For more information, please contact an Ford authorized dealer.'''
        
    [[module]]
path='email_modules/footer/disclaimer'
color='white'
segmentelseif = ["(user.CustomAttribute['Segment'] == 'C')"]

	text = '''
		*Terms & conditions Apply.
        <br />
        <br />
        1. All Prices shown are ex-showroom Mumbai for Next-Gen Ford Figo Base Petrol and Ford Aspire Ambiente Petrol. The above shown vehicle models are Next-Gen Figo 1.5D Sports Edition MT and Ford Aspire 1.5D Sports Edition MT.
        <br />
        <br />
        2. The Gift voucher can be availed by customer only if he has taken a test drive of Ford Figo and/or Ford Aspire at any Ford authorized dealership, and bought any other competition brand vehicle after taking test drive of above mentioned Ford car/s.
        <br />
        <br />
        3. To avail gift, it is mandatory to have met the following conditions within 01-31 August, herein referred to as "campaign period"-
        <br />
        <span style="padding-left: 10px; display: block;">1. Test drive taken within campaign period / Other brand vehicle purchased between campaign period / proof of other vehicle purchase to be submitted between campaign period.</span>
        <br />
        <br />
        4. The Cash benefit upto &#8377;6,000 on Ford Figo and upto &#8377;10,000 on Ford Aspire, is valid only on select variants of the models on offer.
        <br />
        <br />
        5. Exchange bonus will be &#8377;20,000/- on exchange of any Ford Car and &#8377;15,000/- on exchange of a non-Ford car. The valuation of the old car may differ and is by the independent valuers and at the sole discretion of exchange partners.
        <br />
        <br />
        6. Interest rate of 8.15% per annum is available at select dealership across India, if financed through Ford Credit India Private Limited ("Ford Credit") and cannot be exchanged for cash. The finance is at the sole discretion of Ford Credit.
        <br />
        <br />
        7. The assured gift is worth &#8377;8,000/- and is applicable on purchase select Models and/or variants and for booking done between 01-31 August, with full payment on or before 31 August, 2017. 
        <br />
        <br />
        8. This offer is only available in Maharashtra and Goa and is applicable for booking done between 1st August 2017 to 31st August 2017 with full payment on or before 31st August, 2017.
        <br />
        <br />
        9. Colors are indicative only and may vary due to printing constraints. Accessories shown may not be part of standard fitment. 
        <br />
        <br />
        10. Ford India reserve the right to cancel, terminate or suspend this offer at any time during the campaign period without any prior notice. For more information, please contact an Ford authorized dealer.'''
    
    [[module]]
path='email_modules/footer/disclaimer'
color='white'
segmentelseif = ["(user.CustomAttribute['Segment'] == 'D')"]

	text = '''
		*Terms & conditions Apply.
        <br />
        <br />
        1. All Prices shown are ex-showroom Mumbai for Next-Gen Ford Figo Base Petrol and Ford Aspire Ambiente Petrol. The above shown vehicle models are Next-Gen Figo 1.5D Sports Edition MT and Ford Aspire 1.5D Sports Edition MT.
        <br />
        <br />
        2. The Gift voucher can be availed by customer only if he has taken a test drive of Ford Figo and/or Ford Aspire at any Ford authorized dealership, and bought any other competition brand vehicle after taking test drive of above mentioned Ford car/s.
        <br />
        <br />
        3. To avail gift, it is mandatory to have met the following conditions within 01-31 August, herein referred to as "campaign period"-
        <br />
        <span style="padding-left: 10px; display: block;">1. Test drive taken within campaign period / Other brand vehicle purchased between campaign period / proof of other vehicle purchase to be submitted between campaign period.</span>
        <br />
        <br />
        4. The Cash benefit upto &#8377;6,000 on Ford Figo and upto &#8377;10,000 on Ford Aspire, is valid only on select variants of the models on offer.
        <br />
        <br />
        5. Exchange bonus will be &#8377;20,000/- on exchange of any Ford Car and &#8377;15,000/- on exchange of a non-Ford car. The valuation of the old car may differ and is by the independent valuers and at the sole discretion of exchange partners.
        <br />
        <br />
        6. Interest rate of 8.15% per annum is available at select dealership across India, if financed through Ford Credit India Private Limited ("Ford Credit") and cannot be exchanged for cash. The finance is at the sole discretion of Ford Credit.
        <br />
        <br />
        7. The assured gift is worth &#8377;8,000/- and is applicable on purchase select Models and/or variants and for booking done between 01-31 August, with full payment on or before 31 August, 2017. 
        <br />
        <br />
        8. This offer is only available in Maharashtra and Goa and is applicable for booking done between 1st August 2017 to 31st August 2017 with full payment on or before 31st August, 2017.
        <br />
        <br />
        9. Colors are indicative only and may vary due to printing constraints. Accessories shown may not be part of standard fitment. 
        <br />
        <br />
        10. Ford India reserve the right to cancel, terminate or suspend this offer at any time during the campaign period without any prior notice. For more information, please contact an Ford authorized dealer.'''
        
[[module]]
path='email_modules/footer/in/online'
color='white'
+++