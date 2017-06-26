+++
markets = ["au"]
title = '''AU Yellow-Flag 010 Tyres'''

[[module]]
path='email_modules/preheader'


	preheader='''Get your brakes factory-fitted by a Ford technician.'''

[[module]] #Header Logo
path='email_modules/header/logodesktop'
color='black'

	image = '''black'''
	url_link = '''https://www.ford.com.au/'''
    

[[module]] #Banner Image No Link
path = '''email_modules/image/banner_nolink'''
color = '''white'''

	image='''au_edm2d_lptg_20170626'''


[[module]] #Cover 07
path='email_modules/cover/02'
color='''white'''

copy='''Hi <%${user.CustomAttribute['FullName']}%><br /><br />At Ford we offer tyres at competitive prices. We are excited to announce that we are launching a Low Price Tyre Guarantee; we’ll match competitors price on selected tyres we stock&#185;. <br /><br />For the launch <span style="text-decoration:underline;font-weight:bold">your <%${user.CustomAttribute['Dealer_Name']}%> is offering $50 off your next tyre purchase&#178;</span>. To take up this offer, just bring this email along to your tyre service appointment before 31st August 2017.<br /><br />Our Ford technicians offer professional advice on an extensive range of tyres to suit your budget and needs, and with our Low Price Tyre Guarantee if you find a lower price on selected tyre we stock from another competitor we’ll match it within 30 days of purchase&#185;. <br /><br />No one knows your Ford like we do.  So put your Ford <%${user.CustomAttribute['Model']}%> in the hands of our trained technicians at <%${user.CustomAttribute['Dealer_Name']}%.'''
	cta1_text='''FIND OUT MORE'''
	cta1_url='''https://consumer.xtime.net.au/scheduling/?company=14745&store=#DealerCode#&VIN=#VIN#&provider=FORD_AU_THE_BLUE_HIVE&keyword=#Campaign_ID#&dest=&extid=#Campaign_ID#&extctxt=FORD_AU_THE_BLUE_HIVE&cfn=#FirstName#&cln=#LastName#&cpn=#CustomerPhoneT#&cem=#EmailAddr#'''
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

	text = '''DISCLAIMERS 
				<br /> <br />
				1. The Low Price Tyre Guarantee offer is available on selected tyres of listed brands that are stocked by participating Ford dealers.  Competitor tyres must be new, identical and available from an Australian tyre retailer.  Offer includes “4 for 3” or similar competitor offers, but excludes competitor cashback offers, gift cards,  “wheel and tyre” bundles, tyres purchased under an instalment payment plan, clearance and liquidation stock and any competitor quotes that cannot be verified.  Offer is available until 31st August 2017 at participating Ford dealers to private retail and Blue Business Fleet customers.  Includes valid competitor’s quote within 30 days after purchase.  Various adjustments, including fitment and freight, apply to ensure a like-for-like price comparison.  See your participating Ford dealer for full terms and conditions.<br /><br />
				2. $50 voucher is redeemable on tyres only at [Dealer Name] until 31st August 2017.<br /><br />'''


[[module]] #Footer AU Online
path='email_modules/footer/au/online'
color='white'
+++