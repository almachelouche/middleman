+++
markets = ["au"]
title = '''AU Yellow-Flag 011 Tyres'''

[[module]]
path='email_modules/preheader'


	preheader='''Hi <%${user.CustomAttribute['FullName']}%>. When you last serviced your Ford <%${user.CustomAttribute['Model']}%> with us.'''


[[module]] #Banner Image No Link
path = '''email_modules/image/banner_nolink'''
color = '''white'''

	image='''AU_edm2_declined_20171011'''


[[module]] #Cover 07
path='email_modules/cover/02'
color='''white'''

	title='''Reminder: Your Tyres May Need Attention'''
	copy='''Hi <%${user.CustomAttribute['FullName']}%><br /><br />
    When you last serviced your Ford <%${user.CustomAttribute['Model']}%> with us, our technician completed a Vehicle Report Card. Your tyres were flagged as yellow, meaning they may require replacement before your next scheduled service. <br /><br />
    We know you are not yet due for a scheduled service, however - if you would like your tyres checked for peace of mind in the interim, please call <%${user.CustomAttribute['Dealer_Name']}%> Ford on <%${user.CustomAttribute['Dealer_Phone']}%> to book an inspection.
    '''
    
	
[[module]]
path='email_modules/singles/ctablock'
color='''white'''
segmentif = ["(user.CustomAttribute['SERVAPPT'] == 'YES')"]

	cta1_text = '''BOOK YOUR SERVICE'''
	cta1_url = '''https://consumer.xtime.net.au/scheduling/?company=14745&store=<%${user.CustomAttribute['DealerCode']}%>&VIN=<%${user.CustomAttribute['VIN']}%>&provider=FORD_AU_THE_BLUE_HIVE&keyword=<%${user.CustomAttribute['CampaignID']}%>&dest=&extid=<%${user.CustomAttribute['CampaignID']}%>&extctxt=FORD_AU_THE_BLUE_HIVE&cfn=<%${user.CustomAttribute['FullName']}%>&cln=<%${user['LastName']}%>&cpn=<%${user.CustomAttribute['Mobile_Phone']}%>&cem=<%${user.CustomAttribute['RealEmail']}%>&button=blue'''
	cta1_link_name = '''service_booking'''

[[module]] #AU Service Status Copy
path='email_modules/custom/svcstatus'
color='darkblue_au'

	toptitle='''Your current tyres status'''
	icon1='''au_edm2d_brake1_20170417'''
	title1='''Good <br />to go<br />'''
	copy1='''<br /><br />Tyre Tread: <br />Above 4mm'''
	icon2='''au_edm2d_brake3_20170417'''
	title2='''May need replacing <br />before next service<br /> '''
	copy2='''Tyre Tread:<br /> 3mm to 4mm '''
	icon3='''au_edm2d_brake2_20170417'''
	title3='''Replace <br />immediately <br /> '''
	copy3='''<br /><br />Tyre Tread:<br /> Less than 3mm'''

[[module]] #Cover 01
path='email_modules/cover/01'
color='white'

	title = '''Did you know Ford sells tyres?'''
	copy = '''You can trust your Ford dealer to not only fit new tyres perfectly, but also offer you major brands at great prices. There's no need to shop around with Ford's Low Price Tyre Guarantee&#185; – we'll match competitors' prices on selected tyres we stock&#185;.'''
	cta1_url = '''https://www.ford.com.au/owners/service/tyres/'''
	cta1_text = '''FIND OUT MORE'''
	cta1_icon = '''more'''
	cta1_link_name = '''more1'''

[[module]] #Banner Image No Link
path = '''email_modules/image/banner_nolink'''
color = '''white'''

	image='''au_edm2_declined_service_tyres_18102017'''

[[module]] #Footer AU Social
path='email_modules/footer/au/social'
color='white'

[[module]] #Footer Disclaimer
path='email_modules/footer/disclaimer'
color='white'

	text = '''DISCLAIMERS 
				<br /> <br />
				1. The Low Price Tyre Guarantee offer is available on selected tyres of listed brands that are stocked by participating Ford dealers. Competitor tyres must be new, identical and available from an Australian tyre retailer. Offer includes "4 for 3" or similar competitor offers, but excludes competitor cashback offers, gift cards, "wheel and tyre" bundles, tyres purchased under an instalment payment plan, clearance and liquidation stock and any competitor quotes that cannot be verified. Offer is available to private retail and Blue Business Fleet customers. Includes valid competitor's quote within 30 days after purchase. Various adjustments, including fitment and freight, apply to ensure a like-for-like price comparison. See your participating Ford dealer for full terms and conditions. Ford reserves the right to vary or withdraw the Low Price Tyre Guarantee offer at any time.
				'''


[[module]] #Footer AU Online
path='email_modules/footer/au/online'
color='white'
+++