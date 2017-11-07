+++
markets = ["au"]
title = '''AU POM 004 opt-out Transit'''

[[module]]
path='email_modules/preheader'

	preheader='''This is just a friendly reminder that your Ford <%${user.CustomAttribute['Model']}%> is nearly due for its <%${user.CustomAttribute['Service_Interval']}%>km service.'''


[[module]]
path='email_modules/image/banner'
color='white'

	image = '''AU_edm2_optout_20171107'''
	url_link = '''https://www.ford.com.au/owners/service/'''

[[module]]
path='email_modules/spacer/default'
color='white'

	height="30"

[[module]]
path='email_modules/singles/copy'
color='''white'''

	copy = '''
		Hi <%${user.CustomAttribute['FullName']}%>, <br /><br />We hope you're enjoying your new Ford <%${user.CustomAttribute['Model']}%>.<br /><br />Now that you've been on the road for a few months your <%${user.CustomAttribute['Model']}%> is due for its complimentary 2-month/3,000km <a href="https://www.ford.com.au/owners/service/peace-of-mind-inspection/" style="text-decoration:underline; color:#2D96CD">Peace of Mind Service Inspection</a>&#185;. Our Ford trained technicians will inspect your vehicle and ensure it's running at its absolute best.<br /><br />Book your 'Peace of Mind' Service Inspection with <span style="color:#2D96CD"><%${user.CustomAttribute['Dealer_Name']}%></span> on <span style="color:#2D96CD"><%${user.CustomAttribute['Dealer_Phone']}%></span> today, or <a href="https://www.ford.com.au/dealership/" style="text-decoration:underline; color:#2D96CD">locate your nearest dealer</a>.'''

[[module]]
path='email_modules/spacer/default'
color='white'

	height="30"

[[module]] #Banner Image
path='email_modules/image/banner'
color='white'

	image='''au_edm2_transit_video_20170629'''
	url_link='''https://www.youtube.com/watch?v=H9061JG-1Rc&feature=youtu.be'''
	url_link_name='''transitvideo'''
    
[[module]]
path='email_modules/singles/copy'
color='''white'''

	copy = '''<br/><br/>Did you know your Transit uses something called Diesel Exhaust Fluid? Also known as AdBlue®, this fluid helps reduce vehicle emissions.<br/><br/>It's important that you maintain AdBlue® fluid. So, when your Transit begins to run low, you can purchase a new bottle from your local Ford dealer, selected petrol stations, and automotive retailers.<br/><br/>For more information, and guidance on how to refill your AdBlue® levels, watch the video above or visit the <a href="https://www.ford.com.au/owners/service/ad-blue/#" style="text-decoration:underline; color:#2D96CD;" >Ford AdBlue®</a> website.<br/><br/>'''  
    
[[module]]
path='email_modules/spacer/default'
color='white'

	height="30"

[[module]]
path='email_modules/spacer/platinum_20'
color='white'

	height="20"


[[module]]
path='email_modules/footer/au/social'
color='white'

[[module]] #Footer Disclaimer 
path='email_modules/footer/disclaimer'
color='white'

	text = '''DISCLAIMERS:<br /><br />
                1) 'Peace of Mind' Service Inspection expires after 5,000km's or 4 months after delivery of your new Ford (whichever is first).<br /><br />
                
                * Receiving this email does not mean that you are subscribed to receive Ford marketing communications. If you have subscribed and wish to unsubscribe or change your preferences, click below to unsubscribe.
                <br/> <br/>
                If you would like to subscribe to receive more information like this you can do so <a href="https://www.ford.com.au/#overlay/content/ford/au/en_au/site-wide-content/overlays/forms/enews.html" name="terms11" style="text-decoration:underline; color:#91a4b1"> here</a>.
                '''



[[module]]
path='email_modules/footer/au/online'
color='white'

+++