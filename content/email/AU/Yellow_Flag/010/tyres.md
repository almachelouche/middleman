+++
markets = ["au"]
title = '''AU Yellow-Flag 010 Tyres'''

[[module]]
path='email_modules/preheader'


	preheader='''<%${user.CustomAttribute['Dealer_Name']}%> is offering $50 off your next tyre purchase'''

[[module]] #Header Logo
path='email_modules/header/logo'
color='white'

	image = '''white'''
	url_link = '''http://www.ford.com.au'''
    
[[module]] #Banner Image 
path='email_modules/image/banner'
color='white'

	image='''au_edm2d_lptg_20170626'''
	url_link = '''https://www.ford.com.au/owners/service/low-price-tyre-guarantee/'''


[[module]] #Cover 07
path='email_modules/cover/02'
color='''white'''

copy='''Hi <%${user.CustomAttribute['FullName']}%><br /><br />At Ford we’re committed to offering you tyres at competitive prices, which is why we’re excited to announce our Low Price Tyre Guarantee; we’ll match a competitor’s price on selected tyres we stock&#185;. <br /><br />To celebrate <span style="text-decoration:underline;font-weight:bold">To celebrate, your Byrne Ford is offering $50 off your next tyre purchase².</span>. Our factory trained Ford technicians offer professional advice on an extensive wide range of tyres to suit your budget and needs, and with our Low Price Tyre Guarantee, if you find a lower price on selected tyres we stock at a competitor, we’ll match it within 30 days of purchase¹.  <br /><br />Nobody knows your Ford like we do. So put your Ford Everest in the hands of our trained technicians at Byrne Ford'''
	cta1_text='''FIND OUT MORE'''
	cta1_url='''https://www.ford.com.au/owners/service/low-price-tyre-guarantee/'''
	cta1_link_name = '''TYRES'''

[[module]] #Banner Image No Link
path = '''email_modules/image/banner_nolink'''
color = '''white'''

	image='''au_edm2d_brake2_20161114'''

[[module]] #Footer AU Social
path='email_modules/footer/au/social'
color='white'

[[module]] #Footer Disclaimer
path='email_modules/footer/disclaimer'
color='white'

	text = '''DISCLAIMERS: 
				<br /> <br />
				1. The Low Price Tyre Guarantee offer is available on selected tyres of listed brands that are stocked by participating Ford dealers.  Competitor tyres must be new, identical and available from an Australian tyre retailer.  Offer includes “4 for 3” or similar competitor offers, but excludes competitor cashback offers, gift cards,  “wheel and tyre” bundles, tyres purchased under an instalment payment plan, clearance and liquidation stock and any competitor quotes that cannot be verified.  Offer is available until 31st August 2017 at participating Ford dealers to private retail and Blue Business Fleet customers.  Includes valid competitor’s quote within 30 days after purchase.  Various adjustments, including fitment and freight, apply to ensure a like-for-like price comparison.  See your participating Ford dealer for full terms and conditions.<br /><br />
				2. $50 voucher is redeemable on tyres only at <%${user.CustomAttribute['Dealer_Name']}%> until 31st August 2017.<br /><br />'''


[[module]] #Footer AU Online
path='email_modules/footer/au/online'
color='white'
+++