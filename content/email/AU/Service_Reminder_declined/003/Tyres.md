+++
markets = ["au"]
title = '''AU Yellow-Flag 011 Tyres'''

[[module]]
path='email_modules/preheader'


	preheader='''Get your brakes factory-fitted by a Ford technician.'''

[[module]] #Header Logo
path='email_modules/header/logo'
color='white'

	image = '''white'''
	url_link = '''http://www.ford.com.au'''

[[module]] #Banner Image No Link
path = '''email_modules/image/banner_nolink'''
color = '''white'''

	image='''au_edm2d_brake_20161114'''


[[module]] #Cover 07
path='email_modules/cover/02'
color='''white'''

	title='''Reminder: Your Tyres May Need Attention'''
	copy='''Hi <%${user.CustomAttribute['FullName']}%><br /><br />
    When you last serviced your Ford <%${user.CustomAttribute['Model']}%> with us, our technician filled out a Vehicle Report Card. Your tyres were flagged as yellow, meaning they may require replacement before your next scheduled service. 
 
    We know you are not yet due for a scheduled service, however it has been 6 months since we last checked your vehicle - if you would like your tyres checked for peace of mind in the interim, please call <%${user.CustomAttribute['Dealer_Name']}%> Ford on <%${user.CustomAttribute['Dealer_Phone']}%> to book an inspection.
    '''
	cta1_text='''BOOK A SERVICE'''
	cta1_url='''https://consumer.xtime.net.au/scheduling/?company=14745&store=#DealerCode#&VIN=#VIN#&provider=FORD_AU_THE_BLUE_HIVE&keyword=#Campaign_ID#&dest=&extid=#Campaign_ID#&extctxt=FORD_AU_THE_BLUE_HIVE&cfn=#FirstName#&cln=#LastName#&cpn=#CustomerPhoneT#&cem=#EmailAddr#'''
	cta1_link_name = '''link_name_here'''

[[module]] #AU Service Status Copy
path='email_modules/custom/svcstatus'
color='darkblue_au'

	toptitle='''Your current brakes status'''
	icon1='''au_edm2d_brake1_20170417'''
	title1='''Good <br />to go<br />'''
	copy1='''<br /><br />Brake Lining: <br />Over 5mm (Disc) <br />or over 2mm (Drum)'''
	icon2='''au_edm2d_brake3_20170417'''
	title2='''May need replacing <br />before next service<br /> '''
	copy2='''Brake Lining:<br /> 3mm to 5mm (Disc)<br /> or 1.01 to 2mm (Drum) '''
	icon3='''au_edm2d_brake2_20170417'''
	title3='''Replace <br />immediately <br /> '''
	copy3='''<br /><br />Brake Lining:<br /> Less than 3mm (Disc) <br />or less than 1mm (Drum)'''

[[module]] #Cover 01
path='email_modules/cover/01'
color='white'

	icon = '''in_edm2d_status_battery_black_20160801'''
	title = '''Did you know Ford sells tyres?'''
	copy = '''Our Ford technicians will expertly fit Genuine Ford Brake Pads. Specifically designed for your <%${user.CustomAttribute['Model']}%>'s braking system, they're fully tested to ensure long life and minimal fading and are covered under warranty for a period of 12 months or 20,000km&#185;.<br /><br />You can trust your Ford dealer to not only fit new tyres perfectly, but also offer you major brands at great prices. There's no need to shop around with Ford's Low Price Tyre Guarantee – we’ll match competitors' prices on selected tyres we stock.'''
	cta1_url = '''http://www.ford.com.au/owners/service/brakes'''
	cta1_text = '''FIND OUT MORE'''
	cta1_icon = '''more'''
	cta1_link_name = '''more1'''

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
				1. *The Low Price Tyre Guarantee offer is available to private retail and Blue Business Fleet customers on any Dunlop, Goodyear, Pirelli, Firestone, Bridgestone, Michelin, Continental, BFGoodrich, and General Tire tyre that are stocked by participating Ford dealers. Competitor tyres must be new and identical from an Australian tyre retailer. Offer includes “4 for 3” or similar competitor offers, but excludes competitor cashback offers, gift cards, “wheel and tyre bundles” tyres purchased under an instalment payment plan, clearance and liquidation stock, and any competitor quotes that cannot be verified. Customer must present a competitor quote for a competitor tyre (Competitor Tyre) that includes the date of generation, tyre specification information (i.e. brand, quality, size, speed, load, and sidewall) and price of the tyre. If the Competitor Tyre quoted price does not include fitment, the participating Ford dealer will deduct $25 from their quoted price to determine the Price Match Tyre price. For quotes or advertising from online retailers or retailers located more than 80km from the participating Ford dealer, a freight charge of $20 per tyre will be added to the quoted price to determine the Competitor Tyre price. Competitor quote date must be within 30 days of Price-Matched Tyre purchase date. Competitor quote can be presented at the time of purchase (in which case, the customer will pay the competitor price), or within 30 days of purchase (in which case, the customer will receive a refund equal to the difference between the amount paid at time of purchase, and the Competitor Tyre price). Competitor quote must be a printed quote or web-based advertisement. Ford reserves the right to call the competitor to verify the price and availability of the tyre quoted. Verbal or handwritten quotes, personal customer discounts, personal customer quotes received via email, and other quotes that cannot be verified are ineligible. Ford reserves the right to vary or withdraw the Low Price Tyre Guarantee offer at any time.
				'''


[[module]] #Footer AU Online
path='email_modules/footer/au/online'
color='white'
+++