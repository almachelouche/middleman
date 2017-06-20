+++
markets = ["example"]
draft = true
title = '''Before'''

	preheader = ''''''

[[module]] #Header Logo
path='email_modules/header/logo'
color='white'

	image = '''white'''
	url_link = '''https://www.india.ford.com/'''

						[[module]] #************Segment If Header
						path = '''email_modules/segments/headif'''
						color = '''nothing'''
							segmentgroup='''segment'''
							segment='''A'''

[[module]] #Banner Image
path='email_modules/image/banner'
color='white'

	image = '''cashback_20160328_cover'''
	url_link = '''https://www.google.com'''

						[[module]] #************Segment If Footer
						path = '''email_modules/segments/footif'''
						color = '''nothing'''
							segment='''A'''
						[[module]] #************Segment Else Header
						path = '''email_modules/segments/headelse'''
						color = '''nothing'''
							segmentgroup='''segment'''
							segment='''B'''

[[module]] #Banner Image
path='email_modules/image/banner'
color='white'

	image = '''cashback_20160328_cover'''
	url_link = '''https://www.google.com'''

						[[module]] #************Segments Else Footer
						path = '''email_modules/segments/footelse'''
						color = '''nothing'''
							segmentgroup='''segment'''
							segment='''B'''
						[[module]] #************Segment Else Header
						path = '''email_modules/segments/headelse'''
						color = '''nothing'''
							segmentgroup='''segment'''
							segment='''C'''

[[module]] #Banner Image
path='email_modules/image/banner'
color='white'

	image = '''cashback_20160328_cover'''
	url_link = '''https://www.google.com'''

						[[module]] #************Segments Else Footer
						path = '''email_modules/segments/footelse'''
						color = '''nothing'''
							segmentgroup='''segment'''
							segment='''C'''
						[[module]] #************Segment Else Header
						path = '''email_modules/segments/headelse'''
						color = '''nothing'''
							segmentgroup='''segment'''
							segment='''D'''

[[module]] #Banner Image
path='email_modules/image/banner'
color='white'

	image = '''cashback_20160328_cover'''
	url_link = '''https://www.google.com'''

						[[module]] #************Segments Else Footer
						path = '''email_modules/segments/footelse'''
						color = '''nothing'''
							segmentgroup='''segment'''
							segment='''D'''
							[[module]] #************Segment Else Header
						path = '''email_modules/segments/headelse'''
						color = '''nothing'''
							segmentgroup='''segment'''
							segment='''E'''

[[module]] #Banner Image
path='email_modules/image/banner'
color='white'

	image = '''cashback_20160328_cover'''
	url_link = '''https://www.google.com'''

						[[module]] #************Segments Else Footer
						path = '''email_modules/segments/footelse'''
						color = '''nothing'''
							segmentgroup='''segment'''
							segment='''E'''
							[[module]] #************Segment Else Header
						path = '''email_modules/segments/headelse'''
						color = '''nothing'''
							segmentgroup='''segment'''
							segment='''F'''

[[module]] #Banner Image
path='email_modules/image/banner'
color='white'

	image = '''cashback_20160328_cover'''
	url_link = '''https://www.google.com'''

						[[module]] #************Segments Else Footer
						path = '''email_modules/segments/footelse'''
						color = '''nothing'''
							segmentgroup='''segment'''
							segment='''F'''

[[module]] #Cover 01
path='email_modules/cover/01'
color='''white'''
 
	title = '''How are you celebrating?'''
	copy = '''Hello <%${user.CustomAttribute['FullName']}%><br /><br />It has been nearly one year for you and your Ford <%${user.CustomAttribute['Selected_Vehicle']}%>! We sincerely hope the drive has been smooth, rewarding, and - most of all - enjoyable.<br /><br />As part of the Ford family, we'll continue to look out for you this coming year. That's why we created the Ford Owners app - to make owning a Ford easier than ever.	'''

							[[module]] #************Segment If Header
							path = '''email_modules/segments/headif'''
							color = '''nothing'''
									segmentgroup='''segment'''
									segment='''A'''

[[module]] #Custom 05
path='email_modules/custom/4columnicon4titlescopy'
color='white'

	title1 = '''Service Checklist'''
	icon1 = '''ew'''
	text1 = '''Know what needs to be serviced, when.'''
	title2 = '''24h Roadside Assistance'''
	icon2 = '''ew'''
	text2 = '''Because we'll never leave you stranded. 	'''
	title3 = '''How-to Videos'''
	icon3 = '''ew'''
	text3 = '''Step-by-step guide to Ford tech. '''
	title4 = '''Dealer Locator'''
	icon4 = '''ew'''
	text4 = '''Because we're always here for you.'''

							[[module]] #************Segment If Footer
							path = '''email_modules/segments/footif'''
							color = '''nothing'''
									segmentgroup='''segment'''
									segment='''A'''
							[[module]] #************Segment Else Header
							path = '''email_modules/segments/headelse'''
							color = '''nothing'''
									segmentgroup='''segment'''
									segment='''B'''

[[module]] #Custom 05
path='email_modules/custom/4columnicon4titlescopy'
color='white'

	title1 = '''Service Checklist'''
	icon1 = '''ew'''
	text1 = '''Know what needs to be serviced, when.'''
	title2 = '''24h Roadside Assistance'''
	icon2 = '''ew'''
	text2 = '''Because we'll never leave you stranded. 	'''
	title3 = '''How-to Videos'''
	icon3 = '''ew'''
	text3 = '''Step-by-step guide to Ford tech. '''
	title4 = '''Dealer Locator'''
	icon4 = '''ew'''
	text4 = '''Because we're always here for you.'''

							[[module]] #************Segments Else Footer
							path = '''email_modules/segments/footelse'''
							color = '''nothing'''
									segmentgroup='''segment'''
									segment='''B'''
							[[module]] #************Segment Else Header
							path = '''email_modules/segments/headelse'''
							color = '''nothing'''
									segmentgroup='''segment'''
									segment='''C'''

[[module]] #Custom 05
path='email_modules/custom/4columnicon4titlescopy'
color='white'

	title1 = '''Service Checklist'''
	icon1 = '''ew'''
	text1 = '''Know what needs to be serviced, when.'''
	title2 = '''24h Roadside Assistance'''
	icon2 = '''ew'''
	text2 = '''Because we'll never leave you stranded. 	'''
	title3 = '''How-to Videos'''
	icon3 = '''ew'''
	text3 = '''Step-by-step guide to Ford tech. '''
	title4 = '''Dealer Locator'''
	icon4 = '''ew'''
	text4 = '''Because we're always here for you.'''

							[[module]] #************Segments Else Footer
							path = '''email_modules/segments/footelse'''
							color = '''nothing'''
									segmentgroup='''segment'''
									segment='''C'''
							[[module]] #************Segment Else Header
							path = '''email_modules/segments/headelse'''
							color = '''nothing'''
									segmentgroup='''segment'''
									segment='''D'''

[[module]] #Custom 05
path='email_modules/custom/4columnicon4titlescopy'
color='white'

	title1 = '''Service Checklist'''
	icon1 = '''ew'''
	text1 = '''Know what needs to be serviced, when.'''
	title2 = '''24h Roadside Assistance'''
	icon2 = '''ew'''
	text2 = '''Because we'll never leave you stranded. 	'''
	title3 = '''How-to Videos'''
	icon3 = '''ew'''
	text3 = '''Step-by-step guide to Ford tech. '''
	title4 = '''Dealer Locator'''
	icon4 = '''ew'''
	text4 = '''Because we're always here for you.'''

							[[module]] #************Segments Else Footer
							path = '''email_modules/segments/footelse'''
							color = '''nothing'''
									segmentgroup='''segment'''
									segment='''D'''
							[[module]] #************Segment Else Header
							path = '''email_modules/segments/headelse'''
							color = '''nothing'''
									segmentgroup='''segment'''
									segment='''E'''

[[module]] #Custom 05
path='email_modules/custom/4columnicon4titlescopy'
color='white'

	title1 = '''Service Checklist'''
	icon1 = '''ew'''
	text1 = '''Know what needs to be serviced, when.'''
	title2 = '''24h Roadside Assistance'''
	icon2 = '''ew'''
	text2 = '''Because we'll never leave you stranded. 	'''
	title3 = '''How-to Videos'''
	icon3 = '''ew'''
	text3 = '''Step-by-step guide to Ford tech. '''
	title4 = '''Dealer Locator'''
	icon4 = '''ew'''
	text4 = '''Because we're always here for you.'''

							[[module]] #************Segments Else Footer
							path = '''email_modules/segments/footelse'''
							color = '''nothing'''
									segmentgroup='''segment'''
									segment='''E'''
							[[module]] #************Segment Else Header
							path = '''email_modules/segments/headelse'''
							color = '''nothing'''
									segmentgroup='''segment'''
									segment='''F'''

[[module]] #Custom 05
path='email_modules/custom/4columnicon4titlescopy'
color='white'

	title1 = '''Service Checklist'''
	icon1 = '''ew'''
	text1 = '''Know what needs to be serviced, when.'''
	title2 = '''24h Roadside Assistance'''
	icon2 = '''ew'''
	text2 = '''Because we'll never leave you stranded. 	'''
	title3 = '''How-to Videos'''
	icon3 = '''ew'''
	text3 = '''Step-by-step guide to Ford tech. '''
	title4 = '''Dealer Locator'''
	icon4 = '''ew'''
	text4 = '''Because we're always here for you.'''

							[[module]] #************Segments Else Footer
							path = '''email_modules/segments/footelse'''
							color = '''nothing'''
									segmentgroup='''segment'''
									segment='''F'''


[[module]] #Cover 12
path='email_modules/cover/03'
color='''white'''

	copy = '''Download the app now, absolutely free, and have all of this important information and more at your fingertips, anywhere you and your Ford go.'''
	cta1_text = '''iOS'''
	cta1_url = '''https://itunes.apple.com/in/app/ford-owners/id990342351?mt=8'''
	cta2_text = '''ANDROID'''
	cta2_url = '''https://play.google.com/store/apps/details?id=com.ford.fordowners&hl=en'''

[[module]] #Cover 05
path='email_modules/cover/02'
color='''white'''

	title = '''Your Profile Details'''
	copy = '''Name&#58; <%${user['FirstName']}%> <%${user['LastName']}%><br />Email&#58; <%${user.CustomAttribute['RealEmail']}%><br />Phone&#58; <%${user.CustomAttribute['Mobile_Phone']}%><br />Address&#58; <%${user.CustomAttribute['Address_1']}%> <%${user.CustomAttribute['Address_2']}%><br /><br />Anything changed?'''
	cta1_text = '''UPDATED YOUR DETAILS'''
	cta1_url = '''https://www.india.ford.com/profile-update-form?fbdata=req_firstName=<% ${user['FirstName']} %>||req_lastName=<% ${user['LastName']} %>||req_mobileNumber=<%${user.CustomAttribute['Mobile_Phone']}%>||req_EmailID=<% ${user.CustomAttribute['RealEmail']} %>||req_BuildingNo=<% ${user.CustomAttribute['Address_1']} %>||req_StreetRoad=<%${user.CustomAttribute['Address_2']}%>||req_Area=<% ${user.CustomAttribute['Area']} %>||req_Landmark=<% ${user.CustomAttribute['Landmark']} %>||req_city=<% ${user.CustomAttribute['City']} %>||req_State=<% ${user.CustomAttribute['State']} %>||req_postCode=<% ${user.CustomAttribute['Post_Code']} %>'''
	icon = '''ew'''

[[module]] #Footer 5 Icons
path='email_modules/footer/5icons'
color='white'

	icon1_url='''http://google.com'''
	icon1_image='''in_dealers_20160414'''
	alt1 = '''alt text'''
	icon2_url='''http://google.com'''
	icon2_image='''in_ford_credit_20160401'''
	alt2 = '''alt text'''
	icon3_url='''http://google.com'''
	icon3_image='''in_ford_assured_20160401'''
	alt3 = '''alt text'''
	icon4_url='''http://google.com'''
	icon4_image='''in_customer_care_number_20160401'''
	alt4 = '''alt text'''
	icon5_url='''http://google.com'''
	icon5_image='''in_rsa_no_20160615'''
	alt5 = '''alt text'''


[[module]] #Footer IN Social
path='email_modules/footer/in/social'
color='white'

[[module]] #Footer IN Online
path='email_modules/footer/in/online'
color='white'
+++