+++
markets = ["au"]
title = '''AU Yellow-Flag 011 Brakes'''

[[module]]
path='email_modules/preheader'


	preheader='''Hi <%${user.CustomAttribute['FullName']}%>. When you last serviced your Ford <%${user.CustomAttribute['Model']}%> with us.'''


[[module]] #Banner Image No Link
path = '''email_modules/image/banner_nolink'''
color = '''white'''

	image='''au_edm2d_brake_20161114'''


[[module]] #Cover 07
path='email_modules/cover/02'
color='''white'''

	title='''Reminder: Your Brakes May Need Attention'''
	copy='''Hi <%${user.CustomAttribute['FullName']}%><br /><br />
    When you last serviced your Ford <%${user.CustomAttribute['Model']}%> with us, our technician completed a Vehicle Report Card. Your brakes were flagged as yellow, meaning they may require replacement before your next scheduled service. <br /><br />
    We know you are not yet due for a scheduled service, however if you would like your brakes checked for peace of mind in the interim, please call <%${user.CustomAttribute['Dealer_Name']}%> Ford on <%${user.CustomAttribute['Dealer_Phone']}%> to book an inspection.
    '''
    
	
[[module]]
path='email_modules/singles/ctablock'
color='''white'''
segmentif = ["(user.CustomAttribute['SERVAPPT'] == 'YES')"]

	cta1_text = '''BOOK A BRAKES INSPECTION'''
	cta1_url = '''https://consumer.xtime.net.au/scheduling/?company=14745&store=<%${user.CustomAttribute['DealerCode']}%>&VIN=<%${user.CustomAttribute['VIN']}%>&provider=FORD_AU_THE_BLUE_HIVE&keyword=<%${user.CustomAttribute['CampaignID']}%>&dest=&extid=<%${user.CustomAttribute['CampaignID']}%>&extctxt=FORD_AU_THE_BLUE_HIVE&cfn=<%${user.CustomAttribute['FullName']}%>&cln=<%${user['LastName']}%>&cpn=<%${user.CustomAttribute['Mobile_Phone']}%>&cem=<%${user.CustomAttribute['RealEmail']}%>&button=blue'''
	cta1_link_name = '''service_booking'''

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

	text = '''
				'''


[[module]] #Footer AU Online
path='email_modules/footer/au/online'
color='white'
+++