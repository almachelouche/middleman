+++
markets = ["au"]
title = '''AU 2 CTA Test'''


[[module]]
path='email_modules/spacer/default'
color='white'

	height="30"

[[module]]
path='email_modules/singles/copy'
color='''white'''

	copy = '''Hello <%${user.CustomAttribute['FullName']}%><br /><br />Long time, no see! We noticed that your Ford <%${user.CustomAttribute['Model']}%> hasn't been fully serviced lately, and that's got us worried.<br /><br />To stay safe on the road, it's important that you replace worn-out parts as soon as possible.<br /><br />Your next service is due on: <% ${user.CustomAttribute['NextServiceDate']} %>''' 

[[module]]
path='email_modules/spacer/default'
color='white'

	height="30"

[[module]]
path='email_modules/singles/2ctablockside'
color='''white'''

	cta1_text = '''LOCATE A DEALER'''
	cta1_url = '''https://www.ford.com.au/dealership/'''
	cta1_link_name = ''''''
	cta2_text = '''LATEST OFFERS'''
	cta2_url = '''https://www.ford.com.au/dealership/'''
	cta2_link_name = ''''''
    
+++