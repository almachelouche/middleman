+++
markets = ["au"]
title = '''AU Service Reminder 003 8-10years xtime_nonSYNC 50 offer '''

[[module]]
path='email_modules/preheader'

	preheader='''Don't get stuck without wheels. Book a Free Loan Car with your <%${user.CustomAttribute['Model']}%>'s scheduled service.'''


[[module]] #Banner Image
path='email_modules/image/banner'
color='white'

	image = '''au_edm2_svc_new_banner_20170817'''
	url_link = '''https://www.ford.com.au/owners/service/'''
    
[[module]]
path='email_modules/spacer/default'
color='white'

	height="30"
    
[[module]]
path='email_modules/singles/copy'
color='''white'''

	copy = '''Hi <%${user.CustomAttribute['FullName']}%>,<br /><br />This is just a friendly reminder that your Ford <%${user.CustomAttribute['Model']}%> is nearly due for its <%${user.CustomAttribute['Service_Interval']}%>km service.<br /><br />
    We know how important your <%${user.CustomAttribute['Model']}%></span> is to you, so we're sure you'll appreciate the many benefits of putting your <%${user.CustomAttribute['Model']}%></span> in the trusted hands of Ford trained technicians. You can even book a Free Loan Car&#185; for the day when you book your scheduled service.<br /><br />
    Book your service and Free Loan Car&#185; with <span style="color:#2D96CD"><%${user.CustomAttribute['Dealer_Name']}%></span> on <span style="color:#2D96CD"><%${user.CustomAttribute['Dealer_Phone']}%></span> today, or find your <a href="https://www.ford.com.au/dealership/" style="text-decoration:underline; color:#2D96CD">nearest dealer</a>.You can even book online below.
    <br /> <br /> 
        Plus, thanks to Castrol Oils, for a limited time,  you can get $50 off your next scheduled service by presenting this email to your Service Department. 
    '''

[[module]]
path='email_modules/spacer/default'
color='white'

	height="30"

[[module]]
path='email_modules/singles/ctablock'
color='''white'''

	cta1_text = '''BOOK YOUR SERVICE'''
	cta1_url = '''https://consumer.xtime.net.au/scheduling/?company=14745&store=<%${user.CustomAttribute['DealerCode']}%>&VIN=<%${user.CustomAttribute['VIN']}%>&provider=FORD_AU_THE_BLUE_HIVE&keyword=<%${user.CustomAttribute['CampaignID']}%>&dest=&extid=<%${user.CustomAttribute['CampaignID']}%>&extctxt=FORD_AU_THE_BLUE_HIVE&cfn=<%${user.CustomAttribute['FullName']}%>&cln=<%${user['LastName']}%>&cpn=<%${user.CustomAttribute['Mobile_Phone']}%>&cem=<%${user.CustomAttribute['RealEmail']}%>&button=blue'''
	cta1_link_name = '''service_booking'''
    
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

    text_box_height = '''240'''
	title1 = '''Service Price Promise&#178;'''
	copy1 = '''Know how much your standard service will cost before you even come in, with the <a href="https://www.ford.com.au/owners/service/calculator/" name="calculator" style="text-decoration:underline; color:#2D96CD"> Service Price Promise Calculator</span>.'''
	image1 = '''au_edm2_service_price_promise_20170818'''
	image1_link_url = '''https://www.ford.com.au/owners/service/calculator/'''
	image1_link_name = '''Some'''
	title2 = '''Free Loan Car&#185;'''
	copy2 = '''Life shouldn't stop when you service your vehicle. That's why we offer a <a href="https://www.ford.com.au/owners/service/" name="freeloan" style="text-decoration:underline; color:#2D96CD">Free Loan Car&#185</a>  when you book a scheduled service.'''
	image2 = '''au_edm2_free_loan_car_20170818'''
	image2_link_url = '''https://www.ford.com.au/owners/service/'''
	image2_link_name = '''Some'''
    
[[module]] #Footer AU Social
path='email_modules/footer/au/social'
color='white'

[[module]] #Footer Disclaimer 
path='email_modules/footer/disclaimer'
color='white'

	text = '''DISCLAIMERS:<br /><br />
     VIN number: <% ${user.CustomAttribute['VIN']}%>
                <br /> <br />
                Scheduled Service: <%${user.CustomAttribute['Service_Interval']}%>
                <br /> <br />
                * Redemption of the Ford Service Voucher is subject to certain Terms and Conditions as set out below; To take advantage of this voucher, simply print this email and take it to your local Ford Dealership when you take your Ford in for its next scheduled service. This offer is valid for a limited time only on your scheduled service above. The scheduled service must be completed by Nov 30, 2017. If you have any questions regarding this exclusive bonus, please contact your local Ford Dealership. This offer is for Private and registered Blue and Silver Fleet customers with an ABN only. The voucher provided is in the form of a discount applied to the final costs of your scheduled service as provided by the Dealer. This offer is only open to the VIN above for its next scheduled service as per details above also. One voucher per VIN.
                <br /> <br /> 
				1) Available at participating dealers on scheduled services or overnight warranty repairs. Private and Blue, Silver and Gold Business Fleet customers only. Booking may be required. See <a href="https://www.ford.com.au/owners/service/t-and-c/" name="terms11" style="text-decoration:underline; color:#91a4b1"> www.ford.com.au/owners/service/t-and-c</a> for full terms.<br /><br />
                2) Available at participating Ford dealers on vehicles built from 2007. Customers will pay equal to or less than the maximum price as published by Ford for the period of the web quote for standard items in the A and B logbook services. See <a href="https://www.ford.com.au/owners/service/t-and-c/" name="terms11" style="text-decoration:underline; color:#91a4b1"> www.ford.com.au/owners/service/t-and-c</a> for full terms.<br /><br />'''
                

[[module]] #Footer AU Online
path='email_modules/footer/au/online'
color='white'    
+++