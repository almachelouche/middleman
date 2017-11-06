+++
markets = ["au"]
title = '''AU Service Reminder 004 opt-out'''

[[module]]
path='email_modules/preheader'

	preheader='''This is just a friendly reminder that your Ford <%${user.CustomAttribute['Model']}%> is nearly due for its <%${user.CustomAttribute['Service_Interval']}%>km service.'''


[[module]]
path='email_modules/image/banner'
color='white'

	image = '''AU_edm2_optout_20171009'''
	url_link = '''https://www.ford.com.au/owners/service/'''

[[module]]
path='email_modules/spacer/default'
color='white'

	height="30"

[[module]]
path='email_modules/singles/copy'
color='''white'''

	copy = '''
		Hi <%${user.CustomAttribute['FullName']}%>,
		<br />
		<br />
		 This is just a friendly reminder that your Ford <%${user.CustomAttribute['Model']}%> is nearly due for its <%${user.CustomAttribute['Service_Interval']}%>km service. 
		<br />
		<br />
        We know how important your <%${user.CustomAttribute['Model']}%> is to you, and maintaining regular servicing intervals will ensure your Ford <%${user.CustomAttribute['Model']}%> runs at its absolute best.  
    	<br />
    	<br />
    	Book your service with <span style="color:#2D96CD"><%${user.CustomAttribute['Dealer_Name']}%></span> on <span style="color:#2D96CD"><%${user.CustomAttribute['Dealer_Phone']}%></span> today, or find your <a href="https://www.ford.com.au/dealership/" style="text-decoration:underline; color:#2D96CD">nearest dealer</a>.
    '''

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
				1) Receiving this email does not mean that you are subscribed to receive Ford marketing communications. If you have subscribed and wish to unsubscribe or change your preferences, click unsubscribe.
                <br/> <br/>
                If you would like to subscribe to receive more information like this you can do so <a href="https://www.ford.com.au/#overlay/content/ford/au/en_au/site-wide-content/overlays/forms/enews.html" name="terms11" style="text-decoration:underline; color:#91a4b1"> here</a>.
                '''

https://www.ford.com.au/#overlay/content/ford/au/en_au/site-wide-content/overlays/forms/enews.html


[[module]]
path='email_modules/footer/au/online'
color='white'

+++