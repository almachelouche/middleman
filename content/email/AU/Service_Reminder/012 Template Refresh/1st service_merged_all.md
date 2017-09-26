<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">
<head>
<meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
<meta name="format-detection" content="telephone=no" />
<meta name="viewport" content="width=device-width, initial-scale=1.0"/>
<title>AU_Service_Reminder</title>
<style type="text/css">
 
@import url(//fonts.googleapis.com/earlyaccess/nanumgothic.css);

 
 
.ReadMsgBody {
	width: 100%;
}
 
 
.ExternalClass {
	width: 100%;
}
 
 
.ExternalClass * {
	line-height: 100%;
}
 
 
p {
	margin: 1em 0;
}
 
table td {
	border-collapse: collapse;
}
 
@-ms-viewport {
	width: device-width;
}
 
 
.appleLinks {
	color: inherit;
	text-decoration: none;
}
 
.appleLinks a {
	color: inherit;
	text-decoration: none;
}
a:link, a:visited {
	color: #616161;
	text-decoration: none
}
a:hover, a:active {
	color: #616161;
	text-decoration: none;
}

 
 @media screen and (max-width: 580px) {

	body[yahoo]	.col315 {
		width: 100% !important;
		padding:0px 20px;
		max-width:none !important;
	}
	 
	*.nomobile {
		display: none !important;
	}
	 
	*.mobile_align_center { 
			text-align: center !important ;
			margin-left: auto !important; 
			margin-right: auto !important;
	}
	 
	*.mobile_align_center_split {
			text-align: center !important;
			margin-left: auto !important; 
			margin-right: auto !important;
	}
	 
	*.mobile_align_center_split_tpad {
			text-align: center !important;
			margin-left: auto !important; 
			margin-right: auto !important;
			padding-top: 20px !important;
	}
	 
	*.show {
		display: block !important;
		margin: 0 !important;
		padding: 0 !important;
		overflow: visible !important;
		width: auto !important;
		max-height: inherit !important;
	}
    *.img-max {
        max-width: 100% !important;
        width: 100% !important;
        height: auto !important;
     }
    *.auto_height {
        height: auto !important;
     }
    *.padding {
        padding: 10px 0 15px 0 !important;
     }
    *.wrapper {
        width: 100% !important;
        max-width: 100% !important;
     }
	 
	table[class=resize_table_to_320], td[class=resize_table_to_320] {
		width: 100% !important;
		height: auto;
		margin: 0 auto;
	}
	.drop {
		width: 100% !important;
		height: auto;
		margin: 0 auto;
		float: left !important;
	}
	.spacer {
		width: 100% !important;
		height: 20px;
		margin: 0 auto;
		float: left !important;
	}
	.droptest {
		width: 100% !important;
		height: 2px;
		margin: 0 auto;
		float: left !important;
	}
	.drop1 {
		width: 100% !important;
		height: auto;
		margin: 0 auto;
		float: left !important;
		padding-top: 20px !important;
	}
	.het_12 {
		height: 12px !important;
	}
	.pad_Bot_20 {
		padding-bottom: 20px !important;
	}
	.img_Rez {
		width: 100% !important;
		height: auto !important;
		display: block !important;
	}
	.alg_Cen {
		text-align: center !important;
	}
	.alg_Lef {
		text-align: left !important;
		padding-left: 0px !important;
	}
	.img_R {
		width: 100% !important;
		height: auto !important;
	}
	.drop3 {
		width: 100% !important;
		height: auto;
		margin: 0 auto;
		float: left !important;
		text-align:left !important;
	}
	.showOnMobile {
		display:block!important;
		max-height: none !important;
		max-width:none !important;
		line-height: 1.5 !important;
		width:100%!important;
		height:auto!important;
	}
	.hideOnDesktop {
		display:none!important;
		width:0px!important;
		height: 0px!important;
		overflow:hidden!important;
		line-height: 0px!important;
		font-size:0px!important;
	}
}

@media only screen and (max-width: 580px) {
	.full {
		display: block;
		width: 100%;
	}
}
 
 @media screen and (max-width: 320px) {
	 
	.img_R {
		width: 100% !important;
		height: auto !important;
	}
}
</style>
</head>

<!--8TO10Years_xtime_NonSync-->
<%InsertIf expression="${((user.CustomAttribute['Esplit'] == '8TO10') && (user.CustomAttribute['SERVAPPT'] == 'YES') && (user.CustomAttribute['SYNC_Available'] == 'NO'))}" %>
<span class="preheader" style="display: none !important; visibility: hidden; opacity: 0; color: transparent; height: 0px; width: 0px; max-height:1px; max-width:1px; overflow:hidden; mso-hide:all;font-size:1px;">Don't get stuck without wheels. Book a Free Loan Car with your <%${user.CustomAttribute['Model']}%>'s scheduled service.</span>
<%/InsertIf%>

<!--8TO10Years_Nonxtime_NonSync-->
<%InsertElse expression="${((user.CustomAttribute['Esplit'] == '8TO10') && (user.CustomAttribute['SERVAPPT'] == 'NO') && (user.CustomAttribute['SYNC_Available'] == 'NO'))}" %>
<span class="preheader" style="display: none !important; visibility: hidden; opacity: 0; color: transparent; height: 0px; width: 0px; max-height:1px; max-width:1px; overflow:hidden; mso-hide:all;font-size:1px;">Don't get stuck without wheels. Book a Free Loan Car with your <%${user.CustomAttribute['Model']}%>'s scheduled service.</span>
<%/InsertElse%>

<!--1TO7Years_xtime_Sync-->
<%InsertElse expression="${((user.CustomAttribute['Esplit'] == '1TO7') && (user.CustomAttribute['SERVAPPT'] == 'YES') && (user.CustomAttribute['SYNC_Available'] == 'YES'))}" %>
<span class="preheader" style="display: none !important; visibility: hidden; opacity: 0; color: transparent; height: 0px; width: 0px; max-height:1px; max-width:1px; overflow:hidden; mso-hide:all;font-size:1px;">Don't get stuck without wheels. Book a Free Loan Car with your <%${user.CustomAttribute['Model']}%>'s scheduled service.</span>
<%/InsertElse%>

<!--1TO7Years_xtime_NonSync-->
<%InsertElse expression="${((user.CustomAttribute['Esplit'] == '1TO7') && (user.CustomAttribute['SERVAPPT'] == 'YES') && (user.CustomAttribute['SYNC_Available'] == 'NO'))}" %>
<span class="preheader" style="display: none !important; visibility: hidden; opacity: 0; color: transparent; height: 0px; width: 0px; max-height:1px; max-width:1px; overflow:hidden; mso-hide:all;font-size:1px;">Don't get stuck without wheels. Book a Free Loan Car with your <%${user.CustomAttribute['Model']}%>'s scheduled service.</span>
<%/InsertElse%>

<!--1TO7Years_Nonxtime_Sync-->
<%InsertElse expression="${((user.CustomAttribute['Esplit'] == '1TO7') && (user.CustomAttribute['SERVAPPT'] == 'NO') && (user.CustomAttribute['SYNC_Available'] == 'YES'))}" %>
<span class="preheader" style="display: none !important; visibility: hidden; opacity: 0; color: transparent; height: 0px; width: 0px; max-height:1px; max-width:1px; overflow:hidden; mso-hide:all;font-size:1px;">Don't get stuck without wheels. Book a Free Loan Car with your <%${user.CustomAttribute['Model']}%>'s scheduled service.</span>
<%/InsertElse%>

<!--1TO7Years_Nonxtime_NonSync-->
<%InsertElse expression="${((user.CustomAttribute['Esplit'] == '1TO7') && (user.CustomAttribute['SERVAPPT'] == 'NO') && (user.CustomAttribute['SYNC_Available'] == 'NO'))}" %>
<span class="preheader" style="display: none !important; visibility: hidden; opacity: 0; color: transparent; height: 0px; width: 0px; max-height:1px; max-width:1px; overflow:hidden; mso-hide:all;font-size:1px;">Don't get stuck without wheels. Book a Free Loan Car with your <%${user.CustomAttribute['Model']}%>'s scheduled service.</span>
<%/InsertElse%>

<body yahoo bgcolor="#F2F2F2" style="min-width: 100%; margin: 0px; padding:0px; -webkit-text-size-adjust:none; -ms-text-size-adjust: none;" yahoo="fix">

<!--8TO10Years_xtime_NonSync-->
<%InsertIf expression="${((user.CustomAttribute['Esplit'] == '8TO10') && (user.CustomAttribute['SERVAPPT'] == 'YES') && (user.CustomAttribute['SYNC_Available'] == 'NO'))}" %>
<div style="font-size:0px; line-height:0px; color:white; display:none;">Don't get stuck without wheels. Book a Free Loan Car with your <%${user.CustomAttribute['Model']}%>'s scheduled service.</div>

<!--email_modules/preheader ends-->


<!--email_modules/image/banner white starts-->


<table align="center" class="resize_table_to_320" width="640" border="0" cellspacing="0" cellpadding="0" style="max-width: 640px;" bgcolor="#FFFFFF">
		<tr>
				<td align="left" valign="top">
						<table width="100%" border="0" cellspacing="0" cellpadding="0">
								<tr>
										<td align="left" valign="top" style="font-size: 0px;">
												<a href="https://www.ford.com.au/owners/service/" name="" target="_blank" title=""><img class="img_R" align="left" src="https://s3-ap-southeast-1.amazonaws.com/edm-images/covers/au_edm2_svc_new_banner_20170817_desktop.jpg" alt="Image Banner" title="Image Banner" border="0" style="display:block; margin:0;" /></a>
										</td>
								</tr>
						</table>
				</td>
		</tr>
</table>

<!--email_modules/image/banner ends-->


<!--email_modules/spacer/default white starts-->

<table align="center" class="resize_table_to_320" width="640" border="0" cellspacing="0" cellpadding="0">
	<tr>
			<td height="30" bgcolor="#FFFFFF" align="left" valign="top" style="font-size:0%;">
				&nbsp;
			</td>
 	</tr>
</table>
<!--email_modules/spacer/default ends-->


<!--email_modules/singles/copy white starts-->

<table width="640" border="0" cellspacing="0" cellpadding="0" bgcolor="#FFFFFF" class="resize_table_to_320" align="center">
	<tr>
		<td style="padding:30px;padding-top:0px;padding-bottom:0px" valign="top">
			<table width="100%" border="0" cellspacing="0" cellpadding="0">
				<tr>
					<td valign="top" align="center">
						<table	border="0" cellspacing="0" cellpadding="0">
							<tr>
								<td style="text-align:center; color:#616161; font-family: 'Arial','Helvetica','Sans-Serif'; font-size:16px; line-height: 21px;
								font-weight: normal; font-style: normal;">Hi <%${user.CustomAttribute['FullName']}%>,<br /><br />This is just a friendly reminder that your Ford <%${user.CustomAttribute['Model']}%> is nearly due for its <%${user.CustomAttribute['Service_Interval']}%>km service.<br /><br />
    We know how important your <%${user.CustomAttribute['Model']}%></span> is to you, so we're sure you'll appreciate the many benefits of putting your <%${user.CustomAttribute['Model']}%></span> in the trusted hands of Ford trained technicians. You can even book a Free Loan Car&#185; for the day when you book your scheduled service.<br /><br />
    Book your service and Free Loan Car&#185; with <span style="color:#2D96CD"><%${user.CustomAttribute['Dealer_Name']}%></span> on <span style="color:#2D96CD"><%${user.CustomAttribute['Dealer_Phone']}%></span> today, or find your <a href="https://www.ford.com.au/dealership/" style="text-decoration:underline; color:#2D96CD">nearest dealer</a>.You can even book online below.</td>
							</tr>
						</table>
					</td>
				</tr>
			</table>
		</td>
	</tr>
</table>
<!--email_modules/singles/copy ends-->


<!--email_modules/spacer/default white starts-->

<table align="center" class="resize_table_to_320" width="640" border="0" cellspacing="0" cellpadding="0">
	<tr>
			<td height="30" bgcolor="#FFFFFF" align="left" valign="top" style="font-size:0%;">
				&nbsp;
			</td>
 	</tr>
</table>
<!--email_modules/spacer/default ends-->


<!--email_modules/singles/ctablock white starts-->

<table width="640" border="0" cellspacing="0" cellpadding="0" bgcolor="#FFFFFF" class="resize_table_to_320" align="center">
	<tr>
		<td style="padding:30px;padding-top:0px;" valign="top">
			<table width="100%" border="0" cellspacing="0" cellpadding="0">
				<tr>
					<td valign="top" align="center">
						<table	border="0" cellspacing="0" cellpadding="0">
							<tr>
								<td height="40" valign="middle" align="center" bgcolor="#2D96CD" style="vertical-align: middle; padding-left:20px; padding-right:20px; text-align:center; font-family: Arial, Helvetica, Sans-Serif; font-size: 16px;">
									<a href="https://consumer.xtime.net.au/scheduling/?company=14745&store=<%${user.CustomAttribute['DealerCode']}%>&VIN=<%${user.CustomAttribute['VIN']}%>&provider=FORD_AU_THE_BLUE_HIVE&keyword=<%${user.CustomAttribute['CampaignID']}%>&dest=&extid=<%${user.CustomAttribute['CampaignID']}%>&extctxt=FORD_AU_THE_BLUE_HIVE&cfn=<%${user.CustomAttribute['FullName']}%>&cln=<%${user['LastName']}%>&cpn=<%${user.CustomAttribute['Mobile_Phone']}%>&cem=<%${user.CustomAttribute['RealEmail']}%>&button=blue" name="service_booking" target="_blank" title="" style="text-decoration:none; width:100%; display:block; color:#FFFFFF;">BOOK YOUR SERVICE</a>
								</td>
							</tr>
						</table>
					</td>
				</tr>
			</table>
		</td>
	</tr>
</table>
<!--email_modules/singles/ctablock ends-->


<!--email_modules/spacer/default white starts-->

<table align="center" class="resize_table_to_320" width="640" border="0" cellspacing="0" cellpadding="0">
	<tr>
			<td height="30" bgcolor="#FFFFFF" align="left" valign="top" style="font-size:0%;">
				&nbsp;
			</td>
 	</tr>
</table>
<!--email_modules/spacer/default ends-->


<!--email_modules/spacer/platinum_20 white starts-->

<table align="center" class="resize_table_to_320" width="640" border="0" cellspacing="0" cellpadding="0">
	<tr>
			<td height="20" bgcolor="#F2F2F2" align="left" valign="top" style="font-size:0%;">
				&nbsp;
			</td>
 	</tr>
</table>
<!--email_modules/spacer/platinum_20 ends-->


<!--email_modules/dual/05 white starts-->

<table width="640" border="0" cellpadding="0" cellspacing="0" border="0" align="center" bgcolor="#FFFFFF" class="resize_table_to_320" style="max-width: 640px;">
	<tr>
		
		<td valign="top" align="center" class="drop">
			
			<table width="310" cellpadding="0" cellspacing="0" border="0" class="wrapper">
				<tr>
					
					
					
					<td width="30" class="auto_height"height="240" style="height:240px; font-size:240px; line-height:240px;"  >
						<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
					</td>
					
					<td class="auto_height"height="240" style="height:240px; font-size:240px; line-height:240px;"  >
						<table width="100%" height="100%" cellpadding="0" cellspacing="0" border="0">
							<tr>
								<td>
									<table width="100%" cellpadding="0" cellspacing="0" border="0">
										
										<tr>
											<td height="20">
												<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
											</td>
										</tr>
										
												<tr>
													<td height="10">
														<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
													</td>
												</tr>
												<tr>
													<td align="center" style="font-family: Arial, Helvetica, Sans-Serif; font-size: 24px; line-height: 30px; font-weight: normal; font-style: normal; mso-line-height-rule: exactly;">Service Price Promise&#178;</td>
												</tr>
												
												<tr>
													<td height="10">
														<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
													</td>
												</tr>
										
										<tr>
											<td height="10">
												<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
											</td>
										</tr>
										<tr>
											<td style="text-align: center; color: #616161; font-family: Arial, Helvetica, Sans-Serif; font-size: 16px; line-height: 21px; font-weight: normal; font-style: normal; mso-line-height-rule: exactly;">Know how much your standard service will cost before you even come in, with the <a href="https://www.ford.com.au/owners/service/calculator/" name="calculator" style="text-decoration:underline; color:#2D96CD"> Service Price Promise Calculator</span>.</td>
										</tr>
										
										<tr>
											<td height="10">
												<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
											</td>
										</tr>
										
										<tr>
											<td height="20">
												<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
											</td>
										</tr>
									</table>
								</td>
							</tr>
						</table>
					</td>
					
					<td width="30" class="auto_height"height="240" style="height:240px; font-size:240px; line-height:240px;"  >
						<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
					</td>
				</tr>
			</table>
			
			<table width="310" cellpadding="0" cellspacing="0" border="0" bgcolor="F2F2F2" class="img-max">
				<tr>
					<td	valign="top" align="center">
						<a href="https://www.ford.com.au/owners/service/calculator/" name="Some" target="_blank"><img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/tiles/au_edm2_service_price_promise_20170818_tile.jpg" width="310"	border="0"	class="img_Rez" />
						</a></td>
				</tr>
			</table>
		</td>
		
		<td width="20" valign="top" align="center" bgcolor="#F2F2F2" class="spacer">
			<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
		</td>
		
		<td valign="top" align="center" class="drop">
			
			<table width="310" cellpadding="0" cellspacing="0" border="0" class="wrapper">
				<tr>
					
					<td width="30" class="auto_height"height="240" style="height:240px; font-size:240px; line-height:240px;"  >
						<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
					</td>
					
					<td class="auto_height"height="240" style="height:240px; font-size:240px; line-height:240px;"  >
						<table width="100%" height="100%" cellpadding="0" cellspacing="0" border="0">
							<tr>
								<td>
									<table width="100%" cellpadding="0" cellspacing="0" border="0">
										
										<tr>
											<td height="20">
												<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
											</td>
										</tr>
										
												<tr>
													<td height="10">
														<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
													</td>
												</tr>
												<tr>
													<td align="center" style="font-family: Arial, Helvetica, Sans-Serif; font-size: 24px; line-height: 30px; font-weight: normal; font-style: normal; mso-line-height-rule: exactly;">Free Loan Car&#185;</td>
												</tr>
												
												<tr>
													<td height="10">
														<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
													</td>
												</tr>
										
										<tr>
											<td height="10">
												<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
											</td>
										</tr>
										<tr>
											<td style="text-align: center; color: #616161; font-family: Arial, Helvetica, Sans-Serif; font-size: 16px; line-height: 21px; font-weight: normal; font-style: normal; mso-line-height-rule: exactly;">Life shouldn't stop when you service your vehicle. That's why we offer a <a href="https://www.ford.com.au/owners/service/" name="freeloan" style="text-decoration:underline; color:#2D96CD">Free Loan Car&#185</a>  when you book a scheduled service.</td>
										</tr>
										
										<tr>
											<td height="10">
												<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
											</td>
										</tr>
										
										<tr>
											<td height="20">
												<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
											</td>
										</tr>
									</table>
								</td>
							</tr>
						</table>
					</td>
					
					<td width="30" class="auto_height"height="240" style="height:240px; font-size:240px; line-height:240px;"  >
						<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
					</td>
				</tr>
			</table>
			
			<table width="310" cellpadding="0" cellspacing="0" border="0" bgcolor="F2F2F2" class="img-max">
				<tr>
					<td	valign="top" align="center">
						<a href="https://www.ford.com.au/owners/service/" name="Some" target="_blank"><img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/tiles/au_edm2_free_loan_car_20170818_tile.jpg" width="310"	border="0" class="img_Rez" />
						</a></td>
				</tr>
			</table>
		</td>
	</tr>
</table>
<!--email_modules/dual/05 ends-->


<!--email_modules/footer/au/social white starts-->


<table bgcolor="#F2F2F2" align="center" class="resize_table_to_320" width="640" border="0" cellspacing="0" cellpadding="0" style="max-width: 640px;">
	<tr>
		<td align="left" valign="top" style="padding-left:20px; padding-right:20px; padding-top:20px;">
			<table align="left" border="0" cellspacing="0" cellpadding="0">
				<tr>
					<td width="84" align="left" valign="middle" style="color:#91A4B1;font-family:Arial, Verdana, Sans-serif;font-size:12px;">Follow us on:</td>
					<td align="left" valign="top">
						<table border="0" cellspacing="0" cellpadding="0">
							<tr>
								<td width="24" align="left" valign="middle" style="font-size:0%;">
									<a href="https://twitter.com/fordaustralia/" title="Twitter" name="twitter_footer" target="_blank" style="font-size:10px; color:#319AD6; text-decoration:none; text-align:center; font-weight:bold;"><img style="display:block;" border="0" src="https://s3-ap-southeast-1.amazonaws.com/edm-images/twitter.gif" alt="T" width="30" height="30" /></a>
								</td>
							</tr>
						</table></td>
					<td width="10" align="left" valign="middle" style="font-size:0%;">
						&nbsp;
					</td>
					<td align="left" valign="top">
						<table border="0" cellspacing="0" cellpadding="0">
							<tr>
								<td width="24" align="left" valign="middle" style="font-size:0%;">
									<a href="https://www.facebook.com/FordAustralia/" name="facebook_footer" title="Facebook" target="_blank" style="font-size:10px; color:#319AD6; text-decoration:none; text-align:center; font-weight:bold;"><img style="display:block;" border="0" src="https://s3-ap-southeast-1.amazonaws.com/edm-images/facebook.gif" alt="F" width="30" height="30" /></a>
								</td>
							</tr>
						</table>
					</td>
				</tr>
			</table>
		</td>
	</tr>
</table>

<!--email_modules/footer/au/social ends-->


<!--email_modules/footer/disclaimer white starts-->


<table bgcolor="#F2F2F2" align="center" class="resize_table_to_320" width="640" border="0" cellspacing="0" cellpadding="0" style="max-width: 640px;">
		<tr>
			<td align="left" valign="top" style="padding-left:20px; padding-right:20px; padding-top:20px;">
				<table width="100%" border="0" cellspacing="0" cellpadding="0">
						<tr>
								<td class="drop1" align="left" valign="top" style="font-size: 11px; line-height: 14px; font-weight: normal; color:#91A4B1; font-style: normal; font-family: 'Arial','Helvetica','Sans-Serif';">DISCLAIMERS:<br /><br />
				1) Available at participating dealers on scheduled services or overnight warranty repairs. Private and Blue, Silver and Gold Business Fleet customers only. Booking may be required. See <a href="https://www.ford.com.au/owners/service/t-and-c/" name="terms11" style="text-decoration:underline; color:#91a4b1"> www.ford.com.au/owners/service/t-and-c</a> for full terms.<br /><br />
                2) Available at participating Ford dealers on vehicles built from 2007. Customers will pay equal to or less than the maximum price as published by Ford for the period of the web quote for standard items in the A and B logbook services. See <a href="https://www.ford.com.au/owners/service/t-and-c/" name="terms11" style="text-decoration:underline; color:#91a4b1"> www.ford.com.au/owners/service/t-and-c</a> for full terms.<br /><br /></td>
						</tr>
				</table>
			</td>
	</tr>
</table>


<!--email_modules/footer/disclaimer ends-->


<!--email_modules/footer/au/online white starts-->


<table bgcolor="#F2F2F2" align="center" class="resize_table_to_320" width="640" border="0" cellspacing="0" cellpadding="0" style="max-width: 640px;">
		<tr>
			<td align="left" valign="top" style="padding-left:20px; padding-right:20px; padding-top:20px; padding-bottom:20px;">
				<table width="100%" border="0" cellspacing="0" cellpadding="0">
						<tr>
								<td class="drop1" align="left" valign="top" style="font-size: 11px; line-height: 14px; font-weight: normal; color:#91A4B1; font-style: normal; font-family: 'Arial','Helvetica','Sans-Serif';">
											<a href="https://www.ford.com.au/preference?emailid=20150918-0104_Unsubscribe_WelcomeNewSep_Generic_0_FOA&fbdata=First_Name_PPm%3D<%${user['FirstName']}%>||Last_Name_PPm%3D<%${user['LastName']}%>||Email_PP%3D<%${user.CustomAttribute['RealEmail']}%>" target='_blank' style='color:#91A4B1; text-decoration:underline'>Click here</a> to unsubscribe from future Ford e-mails.<br />Copyright &#169; Ford Motor Company of Australia<br /><br /><a href='http://www.ford.com.au/disclaimer' target='_blank' style='color:#91A4B1; text-decoration:underline'>Disclaimer</a> <a href='http://www.ford.com.au/privacy/' target='_blank' style='color:#91A4B1; text-decoration:underline'>Privacy</a> <a href='http://www.ford.com.au/' target='_blank' style='color:#91A4B1; text-decoration:underline'>ford.com.au</a><br /><br />If you're having difficulty viewing this email, <a href="<%syslink_message_read url='/public/read_message.jsp'%>" target='_blank' style='color:#91A4B1; text-decoration:underline'>go to the web version</a>
								</td>
						</tr>
				</table>
			</td>
	</tr>
</table>

<!--email_modules/footer/au/online ends-->
<div style="font-size:0px; line-height:0px; color:white; display:none;">2017-09-20 02:03:39 UTC</div>
<%/InsertIf%>

<!--8TO10Years_Nonxtime_NonSync-->
<%InsertElse expression="${((user.CustomAttribute['Esplit'] == '8TO10') && (user.CustomAttribute['SERVAPPT'] == 'NO') && (user.CustomAttribute['SYNC_Available'] == 'NO'))}" %>
<div style="font-size:0px; line-height:0px; color:white; display:none;">Don't get stuck without wheels. Book a Free Loan Car with your <%${user.CustomAttribute['Model']}%>'s scheduled service.</div>

<!--email_modules/preheader ends-->


<!--email_modules/image/banner white starts-->


<table align="center" class="resize_table_to_320" width="640" border="0" cellspacing="0" cellpadding="0" style="max-width: 640px;" bgcolor="#FFFFFF">
		<tr>
				<td align="left" valign="top">
						<table width="100%" border="0" cellspacing="0" cellpadding="0">
								<tr>
										<td align="left" valign="top" style="font-size: 0px;">
												<a href="https://www.ford.com.au/owners/service/" name="" target="_blank" title=""><img class="img_R" align="left" src="https://s3-ap-southeast-1.amazonaws.com/edm-images/covers/au_edm2_svc_new_banner_20170817_desktop.jpg" alt="Image Banner" title="Image Banner" border="0" style="display:block; margin:0;" /></a>
										</td>
								</tr>
						</table>
				</td>
		</tr>
</table>

<!--email_modules/image/banner ends-->


<!--email_modules/spacer/default white starts-->

<table align="center" class="resize_table_to_320" width="640" border="0" cellspacing="0" cellpadding="0">
	<tr>
			<td height="30" bgcolor="#FFFFFF" align="left" valign="top" style="font-size:0%;">
				&nbsp;
			</td>
 	</tr>
</table>
<!--email_modules/spacer/default ends-->


<!--email_modules/singles/copy white starts-->

<table width="640" border="0" cellspacing="0" cellpadding="0" bgcolor="#FFFFFF" class="resize_table_to_320" align="center">
	<tr>
		<td style="padding:30px;padding-top:0px;padding-bottom:0px" valign="top">
			<table width="100%" border="0" cellspacing="0" cellpadding="0">
				<tr>
					<td valign="top" align="center">
						<table	border="0" cellspacing="0" cellpadding="0">
							<tr>
								<td style="text-align:center; color:#616161; font-family: 'Arial','Helvetica','Sans-Serif'; font-size:16px; line-height: 21px;
								font-weight: normal; font-style: normal;">		Hi <%${user.CustomAttribute['FullName']}%>,
		<br />
		<br />
		This is just a friendly reminder that your Ford <%${user.CustomAttribute['Model']}%> is nearly due for its <%${user.CustomAttribute['Service_Interval']}%>km service.
		<br />
		<br />
    	We know how important your <%${user.CustomAttribute['Model']}%></span> is to you, so we're sure you'll appreciate the many benefits of putting your <%${user.CustomAttribute['Model']}%></span> in the trusted hands of Ford trained technicians. You can even book a Free Loan Car&#185; for the day when you book your scheduled service.
    	<br />
    	<br />
    	Book your service and Free Loan Car&#185; with <span style="color:#2D96CD"><%${user.CustomAttribute['Dealer_Name']}%></span> on <span style="color:#2D96CD"><%${user.CustomAttribute['Dealer_Phone']}%></span> today, or find your <a href="https://www.ford.com.au/dealership/" style="text-decoration:underline; color:#2D96CD">nearest dealer</a>.
    </td>
							</tr>
						</table>
					</td>
				</tr>
			</table>
		</td>
	</tr>
</table>
<!--email_modules/singles/copy ends-->


<!--email_modules/spacer/default white starts-->

<table align="center" class="resize_table_to_320" width="640" border="0" cellspacing="0" cellpadding="0">
	<tr>
			<td height="30" bgcolor="#FFFFFF" align="left" valign="top" style="font-size:0%;">
				&nbsp;
			</td>
 	</tr>
</table>
<!--email_modules/spacer/default ends-->


<!--email_modules/spacer/default white starts-->

<table align="center" class="resize_table_to_320" width="640" border="0" cellspacing="0" cellpadding="0">
	<tr>
			<td height="30" bgcolor="#FFFFFF" align="left" valign="top" style="font-size:0%;">
				&nbsp;
			</td>
 	</tr>
</table>
<!--email_modules/spacer/default ends-->


<!--email_modules/spacer/platinum_20 white starts-->

<table align="center" class="resize_table_to_320" width="640" border="0" cellspacing="0" cellpadding="0">
	<tr>
			<td height="20" bgcolor="#F2F2F2" align="left" valign="top" style="font-size:0%;">
				&nbsp;
			</td>
 	</tr>
</table>
<!--email_modules/spacer/platinum_20 ends-->


<!--email_modules/dual/05 white starts-->

<table width="640" border="0" cellpadding="0" cellspacing="0" border="0" align="center" bgcolor="#FFFFFF" class="resize_table_to_320" style="max-width: 640px;">
	<tr>
		
		<td valign="top" align="center" class="drop">
			
			<table width="310" cellpadding="0" cellspacing="0" border="0" class="wrapper">
				<tr>
					
					
					
					<td width="30" class="auto_height"height="240" style="height:240px; font-size:240px; line-height:240px;"  >
						<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
					</td>
					
					<td class="auto_height"height="240" style="height:240px; font-size:240px; line-height:240px;"  >
						<table width="100%" height="100%" cellpadding="0" cellspacing="0" border="0">
							<tr>
								<td>
									<table width="100%" cellpadding="0" cellspacing="0" border="0">
										
										<tr>
											<td height="20">
												<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
											</td>
										</tr>
										
												<tr>
													<td height="10">
														<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
													</td>
												</tr>
												<tr>
													<td align="center" style="font-family: Arial, Helvetica, Sans-Serif; font-size: 24px; line-height: 30px; font-weight: normal; font-style: normal; mso-line-height-rule: exactly;">Service Price Promise&#178;</td>
												</tr>
												
												<tr>
													<td height="10">
														<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
													</td>
												</tr>
										
										<tr>
											<td height="10">
												<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
											</td>
										</tr>
										<tr>
											<td style="text-align: center; color: #616161; font-family: Arial, Helvetica, Sans-Serif; font-size: 16px; line-height: 21px; font-weight: normal; font-style: normal; mso-line-height-rule: exactly;">Know how much your standard service will cost before you even come in, with the <a href="https://www.ford.com.au/owners/service/calculator/" name="calculator" style="text-decoration:underline; color:#2D96CD"> Service Price Promise Calculator</span>.</td>
										</tr>
										
										<tr>
											<td height="10">
												<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
											</td>
										</tr>
										
										<tr>
											<td height="20">
												<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
											</td>
										</tr>
									</table>
								</td>
							</tr>
						</table>
					</td>
					
					<td width="30" class="auto_height"height="240" style="height:240px; font-size:240px; line-height:240px;"  >
						<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
					</td>
				</tr>
			</table>
			
			<table width="310" cellpadding="0" cellspacing="0" border="0" bgcolor="F2F2F2" class="img-max">
				<tr>
					<td	valign="top" align="center">
						<a href="https://www.ford.com.au/owners/service/calculator/" name="Some" target="_blank"><img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/tiles/au_edm2_service_price_promise_20170818_tile.jpg" width="310"	border="0"	class="img_Rez" />
						</a></td>
				</tr>
			</table>
		</td>
		
		<td width="20" valign="top" align="center" bgcolor="#F2F2F2" class="spacer">
			<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
		</td>
		
		<td valign="top" align="center" class="drop">
			
			<table width="310" cellpadding="0" cellspacing="0" border="0" class="wrapper">
				<tr>
					
					<td width="30" class="auto_height"height="240" style="height:240px; font-size:240px; line-height:240px;"  >
						<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
					</td>
					
					<td class="auto_height"height="240" style="height:240px; font-size:240px; line-height:240px;"  >
						<table width="100%" height="100%" cellpadding="0" cellspacing="0" border="0">
							<tr>
								<td>
									<table width="100%" cellpadding="0" cellspacing="0" border="0">
										
										<tr>
											<td height="20">
												<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
											</td>
										</tr>
										
												<tr>
													<td height="10">
														<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
													</td>
												</tr>
												<tr>
													<td align="center" style="font-family: Arial, Helvetica, Sans-Serif; font-size: 24px; line-height: 30px; font-weight: normal; font-style: normal; mso-line-height-rule: exactly;">Free Loan Car&#185;</td>
												</tr>
												
												<tr>
													<td height="10">
														<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
													</td>
												</tr>
										
										<tr>
											<td height="10">
												<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
											</td>
										</tr>
										<tr>
											<td style="text-align: center; color: #616161; font-family: Arial, Helvetica, Sans-Serif; font-size: 16px; line-height: 21px; font-weight: normal; font-style: normal; mso-line-height-rule: exactly;">Life shouldn't stop when you service your vehicle. That's why we offer a <a href="https://www.ford.com.au/owners/service/" name="freeloan" style="text-decoration:underline; color:#2D96CD">Free Loan Car&#185</a>  when you book a scheduled service.</td>
										</tr>
										
										<tr>
											<td height="10">
												<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
											</td>
										</tr>
										
										<tr>
											<td height="20">
												<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
											</td>
										</tr>
									</table>
								</td>
							</tr>
						</table>
					</td>
					
					<td width="30" class="auto_height"height="240" style="height:240px; font-size:240px; line-height:240px;"  >
						<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
					</td>
				</tr>
			</table>
			
			<table width="310" cellpadding="0" cellspacing="0" border="0" bgcolor="F2F2F2" class="img-max">
				<tr>
					<td	valign="top" align="center">
						<a href="https://www.ford.com.au/owners/service/" name="Some" target="_blank"><img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/tiles/au_edm2_free_loan_car_20170818_tile.jpg" width="310"	border="0" class="img_Rez" />
						</a></td>
				</tr>
			</table>
		</td>
	</tr>
</table>
<!--email_modules/dual/05 ends-->


<!--email_modules/footer/au/social white starts-->


<table bgcolor="#F2F2F2" align="center" class="resize_table_to_320" width="640" border="0" cellspacing="0" cellpadding="0" style="max-width: 640px;">
	<tr>
		<td align="left" valign="top" style="padding-left:20px; padding-right:20px; padding-top:20px;">
			<table align="left" border="0" cellspacing="0" cellpadding="0">
				<tr>
					<td width="84" align="left" valign="middle" style="color:#91A4B1;font-family:Arial, Verdana, Sans-serif;font-size:12px;">Follow us on:</td>
					<td align="left" valign="top">
						<table border="0" cellspacing="0" cellpadding="0">
							<tr>
								<td width="24" align="left" valign="middle" style="font-size:0%;">
									<a href="https://twitter.com/fordaustralia/" title="Twitter" name="twitter_footer" target="_blank" style="font-size:10px; color:#319AD6; text-decoration:none; text-align:center; font-weight:bold;"><img style="display:block;" border="0" src="https://s3-ap-southeast-1.amazonaws.com/edm-images/twitter.gif" alt="T" width="30" height="30" /></a>
								</td>
							</tr>
						</table></td>
					<td width="10" align="left" valign="middle" style="font-size:0%;">
						&nbsp;
					</td>
					<td align="left" valign="top">
						<table border="0" cellspacing="0" cellpadding="0">
							<tr>
								<td width="24" align="left" valign="middle" style="font-size:0%;">
									<a href="https://www.facebook.com/FordAustralia/" name="facebook_footer" title="Facebook" target="_blank" style="font-size:10px; color:#319AD6; text-decoration:none; text-align:center; font-weight:bold;"><img style="display:block;" border="0" src="https://s3-ap-southeast-1.amazonaws.com/edm-images/facebook.gif" alt="F" width="30" height="30" /></a>
								</td>
							</tr>
						</table>
					</td>
				</tr>
			</table>
		</td>
	</tr>
</table>

<!--email_modules/footer/au/social ends-->


<!--email_modules/footer/disclaimer white starts-->


<table bgcolor="#F2F2F2" align="center" class="resize_table_to_320" width="640" border="0" cellspacing="0" cellpadding="0" style="max-width: 640px;">
		<tr>
			<td align="left" valign="top" style="padding-left:20px; padding-right:20px; padding-top:20px;">
				<table width="100%" border="0" cellspacing="0" cellpadding="0">
						<tr>
								<td class="drop1" align="left" valign="top" style="font-size: 11px; line-height: 14px; font-weight: normal; color:#91A4B1; font-style: normal; font-family: 'Arial','Helvetica','Sans-Serif';">DISCLAIMERS:
                <br /> <br /> 
				1) Available at participating dealers on scheduled services or overnight warranty repairs. Private and Blue, Silver and Gold Business Fleet customers only. Booking may be required. See <a href="www.ford.com.au/owners/service/t-and-c/" name="terms9" style="text-decoration:underline; color:#91a4b1">www.ford.com.au/owners/service/t-and-c</a> for full terms.<br /><br />
                2) Available at participating Ford dealers on vehicles built from 2007. Customers will pay equal to or less than the maximum price as published by Ford for the period of the web quote for standard items in the A and B logbook services. See <a href="https://www.ford.com.au/owners/service/t-and-c/" name="terms11" style="text-decoration:underline; color:#91a4b1"> www.ford.com.au/owners/service/t-and-c</a> for full terms.<br /><br /></td>
						</tr>
				</table>
			</td>
	</tr>
</table>


<!--email_modules/footer/disclaimer ends-->


<!--email_modules/footer/au/online white starts-->


<table bgcolor="#F2F2F2" align="center" class="resize_table_to_320" width="640" border="0" cellspacing="0" cellpadding="0" style="max-width: 640px;">
		<tr>
			<td align="left" valign="top" style="padding-left:20px; padding-right:20px; padding-top:20px; padding-bottom:20px;">
				<table width="100%" border="0" cellspacing="0" cellpadding="0">
						<tr>
								<td class="drop1" align="left" valign="top" style="font-size: 11px; line-height: 14px; font-weight: normal; color:#91A4B1; font-style: normal; font-family: 'Arial','Helvetica','Sans-Serif';">
											<a href="https://www.ford.com.au/preference?emailid=20150918-0104_Unsubscribe_WelcomeNewSep_Generic_0_FOA&fbdata=First_Name_PPm%3D<%${user['FirstName']}%>||Last_Name_PPm%3D<%${user['LastName']}%>||Email_PP%3D<%${user.CustomAttribute['RealEmail']}%>" target='_blank' style='color:#91A4B1; text-decoration:underline'>Click here</a> to unsubscribe from future Ford e-mails.<br />Copyright &#169; Ford Motor Company of Australia<br /><br /><a href='http://www.ford.com.au/disclaimer' target='_blank' style='color:#91A4B1; text-decoration:underline'>Disclaimer</a> <a href='http://www.ford.com.au/privacy/' target='_blank' style='color:#91A4B1; text-decoration:underline'>Privacy</a> <a href='http://www.ford.com.au/' target='_blank' style='color:#91A4B1; text-decoration:underline'>ford.com.au</a><br /><br />If you're having difficulty viewing this email, <a href="<%syslink_message_read url='/public/read_message.jsp'%>" target='_blank' style='color:#91A4B1; text-decoration:underline'>go to the web version</a>
								</td>
						</tr>
				</table>
			</td>
	</tr>
</table>

<!--email_modules/footer/au/online ends-->
<div style="font-size:0px; line-height:0px; color:white; display:none;">2017-09-20 02:03:39 UTC</div>
<%/InsertElse%>

<!--1TO7Years_xtime_Sync-->
<%InsertElse expression="${((user.CustomAttribute['Esplit'] == '1TO7') && (user.CustomAttribute['SERVAPPT'] == 'YES') && (user.CustomAttribute['SYNC_Available'] == 'YES'))}" %>
<div style="font-size:0px; line-height:0px; color:white; display:none;">Don't get stuck without wheels. Book a Free Loan Car with your <%${user.CustomAttribute['Model']}%>'s scheduled service.</div>

<!--email_modules/preheader ends-->


<!--email_modules/image/banner white starts-->


<table align="center" class="resize_table_to_320" width="640" border="0" cellspacing="0" cellpadding="0" style="max-width: 640px;" bgcolor="#FFFFFF">
		<tr>
				<td align="left" valign="top">
						<table width="100%" border="0" cellspacing="0" cellpadding="0">
								<tr>
										<td align="left" valign="top" style="font-size: 0px;">
												<a href="https://www.ford.com.au/owners/service/" name="" target="_blank" title=""><img class="img_R" align="left" src="https://s3-ap-southeast-1.amazonaws.com/edm-images/covers/au_edm2_svc_new_banner_20170817_desktop.jpg" alt="Image Banner" title="Image Banner" border="0" style="display:block; margin:0;" /></a>
										</td>
								</tr>
						</table>
				</td>
		</tr>
</table>

<!--email_modules/image/banner ends-->


<!--email_modules/spacer/default white starts-->

<table align="center" class="resize_table_to_320" width="640" border="0" cellspacing="0" cellpadding="0">
	<tr>
			<td height="30" bgcolor="#FFFFFF" align="left" valign="top" style="font-size:0%;">
				&nbsp;
			</td>
 	</tr>
</table>
<!--email_modules/spacer/default ends-->


<!--email_modules/singles/copy white starts-->

<table width="640" border="0" cellspacing="0" cellpadding="0" bgcolor="#FFFFFF" class="resize_table_to_320" align="center">
	<tr>
		<td style="padding:30px;padding-top:0px;padding-bottom:0px" valign="top">
			<table width="100%" border="0" cellspacing="0" cellpadding="0">
				<tr>
					<td valign="top" align="center">
						<table	border="0" cellspacing="0" cellpadding="0">
							<tr>
								<td style="text-align:center; color:#616161; font-family: 'Arial','Helvetica','Sans-Serif'; font-size:16px; line-height: 21px;
								font-weight: normal; font-style: normal;">Hi <%${user.CustomAttribute['FullName']}%>,<br /><br />This is just a friendly reminder that your Ford <%${user.CustomAttribute['Model']}%> is nearly due for its <%${user.CustomAttribute['Service_Interval']}%>km service.<br /><br />
    We know how important your <%${user.CustomAttribute['Model']}%></span> is to you, so we're sure you'll appreciate the many benefits of putting your <%${user.CustomAttribute['Model']}%></span> in the trusted hands of Ford trained technicians. You can even book a Free Loan Car&#185; for the day when you book your scheduled service.<br /><br />
    Book your service and Free Loan Car&#185; with <span style="color:#2D96CD"><%${user.CustomAttribute['Dealer_Name']}%></span> on <span style="color:#2D96CD"><%${user.CustomAttribute['Dealer_Phone']}%></span> today, or find your <a href="https://www.ford.com.au/dealership/" style="text-decoration:underline; color:#2D96CD">nearest dealer</a>. You can even book online below.</td>
							</tr>
						</table>
					</td>
				</tr>
			</table>
		</td>
	</tr>
</table>
<!--email_modules/singles/copy ends-->


<!--email_modules/spacer/default white starts-->

<table align="center" class="resize_table_to_320" width="640" border="0" cellspacing="0" cellpadding="0">
	<tr>
			<td height="30" bgcolor="#FFFFFF" align="left" valign="top" style="font-size:0%;">
				&nbsp;
			</td>
 	</tr>
</table>
<!--email_modules/spacer/default ends-->


<!--email_modules/singles/ctablock white starts-->

<table width="640" border="0" cellspacing="0" cellpadding="0" bgcolor="#FFFFFF" class="resize_table_to_320" align="center">
	<tr>
		<td style="padding:30px;padding-top:0px;" valign="top">
			<table width="100%" border="0" cellspacing="0" cellpadding="0">
				<tr>
					<td valign="top" align="center">
						<table	border="0" cellspacing="0" cellpadding="0">
							<tr>
								<td height="40" valign="middle" align="center" bgcolor="#2D96CD" style="vertical-align: middle; padding-left:20px; padding-right:20px; text-align:center; font-family: Arial, Helvetica, Sans-Serif; font-size: 16px;">
									<a href="https://consumer.xtime.net.au/scheduling/?company=14745&store=<%${user.CustomAttribute['DealerCode']}%>&VIN=<%${user.CustomAttribute['VIN']}%>&provider=FORD_AU_THE_BLUE_HIVE&keyword=<%${user.CustomAttribute['CampaignID']}%>&dest=&extid=<%${user.CustomAttribute['CampaignID']}%>&extctxt=FORD_AU_THE_BLUE_HIVE&cfn=<%${user.CustomAttribute['FullName']}%>&cln=<%${user['LastName']}%>&cpn=<%${user.CustomAttribute['Mobile_Phone']}%>&cem=<%${user.CustomAttribute['RealEmail']}%>&button=blue" name="service_booking" target="_blank" title="" style="text-decoration:none; width:100%; display:block; color:#FFFFFF;">BOOK YOUR SERVICE</a>
								</td>
							</tr>
						</table>
					</td>
				</tr>
			</table>
		</td>
	</tr>
</table>
<!--email_modules/singles/ctablock ends-->


<!--email_modules/spacer/default white starts-->

<table align="center" class="resize_table_to_320" width="640" border="0" cellspacing="0" cellpadding="0">
	<tr>
			<td height="30" bgcolor="#FFFFFF" align="left" valign="top" style="font-size:0%;">
				&nbsp;
			</td>
 	</tr>
</table>
<!--email_modules/spacer/default ends-->


<!--email_modules/spacer/platinum_20 white starts-->

<table align="center" class="resize_table_to_320" width="640" border="0" cellspacing="0" cellpadding="0">
	<tr>
			<td height="20" bgcolor="#F2F2F2" align="left" valign="top" style="font-size:0%;">
				&nbsp;
			</td>
 	</tr>
</table>
<!--email_modules/spacer/platinum_20 ends-->


<!--email_modules/dual/05 white starts-->

<table width="640" border="0" cellpadding="0" cellspacing="0" border="0" align="center" bgcolor="#FFFFFF" class="resize_table_to_320" style="max-width: 640px;">
	<tr>
		
		<td valign="top" align="center" class="drop">
			
			<table width="310" cellpadding="0" cellspacing="0" border="0" class="wrapper">
				<tr>
					
					
					
					<td width="30" class="auto_height"height="240" style="height:240px; font-size:240px; line-height:240px;"  >
						<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
					</td>
					
					<td class="auto_height"height="240" style="height:240px; font-size:240px; line-height:240px;"  >
						<table width="100%" height="100%" cellpadding="0" cellspacing="0" border="0">
							<tr>
								<td>
									<table width="100%" cellpadding="0" cellspacing="0" border="0">
										
										<tr>
											<td height="20">
												<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
											</td>
										</tr>
										
												<tr>
													<td height="10">
														<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
													</td>
												</tr>
												<tr>
													<td align="center" style="font-family: Arial, Helvetica, Sans-Serif; font-size: 24px; line-height: 30px; font-weight: normal; font-style: normal; mso-line-height-rule: exactly;">Service Price Promise&#178;</td>
												</tr>
												
												<tr>
													<td height="10">
														<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
													</td>
												</tr>
										
										<tr>
											<td height="10">
												<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
											</td>
										</tr>
										<tr>
											<td style="text-align: center; color: #616161; font-family: Arial, Helvetica, Sans-Serif; font-size: 16px; line-height: 21px; font-weight: normal; font-style: normal; mso-line-height-rule: exactly;">Know how much your standard service will cost before you even come in, with the <a href="https://www.ford.com.au/owners/service/calculator/" name="calculator" style="text-decoration:underline; color:#2D96CD"> Service Price Promise Calculator</span>.</td>
										</tr>
										
										<tr>
											<td height="10">
												<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
											</td>
										</tr>
										
										<tr>
											<td height="20">
												<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
											</td>
										</tr>
									</table>
								</td>
							</tr>
						</table>
					</td>
					
					<td width="30" class="auto_height"height="240" style="height:240px; font-size:240px; line-height:240px;"  >
						<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
					</td>
				</tr>
			</table>
			
			<table width="310" cellpadding="0" cellspacing="0" border="0" bgcolor="F2F2F2" class="img-max">
				<tr>
					<td	valign="top" align="center">
						<a href="https://www.ford.com.au/owners/service/calculator/" name="Some" target="_blank"><img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/tiles/au_edm2_service_price_promise_20170818_tile.jpg" width="310"	border="0"	class="img_Rez" />
						</a></td>
				</tr>
			</table>
		</td>
		
		<td width="20" valign="top" align="center" bgcolor="#F2F2F2" class="spacer">
			<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
		</td>
		
		<td valign="top" align="center" class="drop">
			
			<table width="310" cellpadding="0" cellspacing="0" border="0" class="wrapper">
				<tr>
					
					<td width="30" class="auto_height"height="240" style="height:240px; font-size:240px; line-height:240px;"  >
						<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
					</td>
					
					<td class="auto_height"height="240" style="height:240px; font-size:240px; line-height:240px;"  >
						<table width="100%" height="100%" cellpadding="0" cellspacing="0" border="0">
							<tr>
								<td>
									<table width="100%" cellpadding="0" cellspacing="0" border="0">
										
										<tr>
											<td height="20">
												<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
											</td>
										</tr>
										
												<tr>
													<td height="10">
														<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
													</td>
												</tr>
												<tr>
													<td align="center" style="font-family: Arial, Helvetica, Sans-Serif; font-size: 24px; line-height: 30px; font-weight: normal; font-style: normal; mso-line-height-rule: exactly;">Free Loan Car&#185;</td>
												</tr>
												
												<tr>
													<td height="10">
														<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
													</td>
												</tr>
										
										<tr>
											<td height="10">
												<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
											</td>
										</tr>
										<tr>
											<td style="text-align: center; color: #616161; font-family: Arial, Helvetica, Sans-Serif; font-size: 16px; line-height: 21px; font-weight: normal; font-style: normal; mso-line-height-rule: exactly;">Life shouldn't stop when you service your vehicle. That's why we offer a <a href="https://www.ford.com.au/owners/service/" name="freeloan" style="text-decoration:underline; color:#2D96CD">Free Loan Car&#185</a>  when you book a scheduled service.</td>
										</tr>
										
										<tr>
											<td height="10">
												<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
											</td>
										</tr>
										
										<tr>
											<td height="20">
												<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
											</td>
										</tr>
									</table>
								</td>
							</tr>
						</table>
					</td>
					
					<td width="30" class="auto_height"height="240" style="height:240px; font-size:240px; line-height:240px;"  >
						<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
					</td>
				</tr>
			</table>
			
			<table width="310" cellpadding="0" cellspacing="0" border="0" bgcolor="F2F2F2" class="img-max">
				<tr>
					<td	valign="top" align="center">
						<a href="https://www.ford.com.au/owners/service/" name="Some" target="_blank"><img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/tiles/au_edm2_free_loan_car_20170818_tile.jpg" width="310"	border="0" class="img_Rez" />
						</a></td>
				</tr>
			</table>
		</td>
	</tr>
</table>
<!--email_modules/dual/05 ends-->


<!--email_modules/spacer/platinum_20 white starts-->

<table align="center" class="resize_table_to_320" width="640" border="0" cellspacing="0" cellpadding="0">
	<tr>
			<td height="20" bgcolor="#F2F2F2" align="left" valign="top" style="font-size:0%;">
				&nbsp;
			</td>
 	</tr>
</table>
<!--email_modules/spacer/platinum_20 ends-->


<!--email_modules/dual/05 white starts-->

<table width="640" border="0" cellpadding="0" cellspacing="0" border="0" align="center" bgcolor="#FFFFFF" class="resize_table_to_320" style="max-width: 640px;">
	<tr>
		
		<td valign="top" align="center" class="drop">
			
			<table width="310" cellpadding="0" cellspacing="0" border="0" class="wrapper">
				<tr>
					
					
					
					<td width="30" class="auto_height"height="380" style="height:380px; font-size:380px; line-height:380px;"  >
						<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
					</td>
					
					<td class="auto_height"height="380" style="height:380px; font-size:380px; line-height:380px;"  >
						<table width="100%" height="100%" cellpadding="0" cellspacing="0" border="0">
							<tr>
								<td>
									<table width="100%" cellpadding="0" cellspacing="0" border="0">
										
										<tr>
											<td height="20">
												<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
											</td>
										</tr>
										
												<tr>
													<td height="10">
														<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
													</td>
												</tr>
												<tr>
													<td align="center" style="font-family: Arial, Helvetica, Sans-Serif; font-size: 24px; line-height: 30px; font-weight: normal; font-style: normal; mso-line-height-rule: exactly;">Auto Club Membership&#179;</td>
												</tr>
												
												<tr>
													<td height="10">
														<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
													</td>
												</tr>
										
										<tr>
											<td height="10">
												<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
											</td>
										</tr>
										<tr>
											<td style="text-align: center; color: #616161; font-family: Arial, Helvetica, Sans-Serif; font-size: 16px; line-height: 21px; font-weight: normal; font-style: normal; mso-line-height-rule: exactly;">Each time you complete your standard service at a participating Ford dealer you'll receive State Auto Club Roadside Assistance and membership for up to 12 months.</td>
										</tr>
										
										<tr>
											<td height="10">
												<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
											</td>
										</tr>
										
												<tr>
													<td height="10">
														<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
													</td>
												</tr>
												<tr>
															<td style="text-align: center; color: #616161; font-family: Arial, Helvetica, Sans-Serif; font-size: 16px; line-height: 21px; font-weight: normal; font-style: normal; mso-line-height-rule: exactly;">
																
																<a href="https://www.ford.com.au/owners/service/roadside-assistance/" name="AutoClubMembership" style="color: #2D96CD; text-decoration: underline;">Learn More</a>
															</td>
														</tr>
												<tr>
													<td height="10">
														<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
													</td>
												</tr>
										<tr>
											<td height="20">
												<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
											</td>
										</tr>
									</table>
								</td>
							</tr>
						</table>
					</td>
					
					<td width="30" class="auto_height"height="380" style="height:380px; font-size:380px; line-height:380px;"  >
						<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
					</td>
				</tr>
			</table>
			
			<table width="310" cellpadding="0" cellspacing="0" border="0" bgcolor="F2F2F2" class="img-max">
				<tr>
					<td	valign="top" align="center">
						<a href="https://www.ford.com.au/owners/service/roadside-assistance/" name="Some" target="_blank"><img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/tiles/au_edm2_auto_club_membership_20170818_tile.jpg" width="310"	border="0"	class="img_Rez" />
						</a></td>
				</tr>
			</table>
		</td>
		
		<td width="20" valign="top" align="center" bgcolor="#F2F2F2" class="spacer">
			<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
		</td>
		
		<td valign="top" align="center" class="drop">
			
			<table width="310" cellpadding="0" cellspacing="0" border="0" class="wrapper">
				<tr>
					
					<td width="30" class="auto_height"height="380" style="height:380px; font-size:380px; line-height:380px;"  >
						<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
					</td>
					
					<td class="auto_height"height="380" style="height:380px; font-size:380px; line-height:380px;"  >
						<table width="100%" height="100%" cellpadding="0" cellspacing="0" border="0">
							<tr>
								<td>
									<table width="100%" cellpadding="0" cellspacing="0" border="0">
										
										<tr>
											<td height="20">
												<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
											</td>
										</tr>
										
												<tr>
													<td height="10">
														<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
													</td>
												</tr>
												<tr>
													<td align="center" style="font-family: Arial, Helvetica, Sans-Serif; font-size: 24px; line-height: 30px; font-weight: normal; font-style: normal; mso-line-height-rule: exactly;">SAT NAV<br/>Updates&#8308;</td>
												</tr>
												
												<tr>
													<td height="10">
														<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
													</td>
												</tr>
										
										<tr>
											<td height="10">
												<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
											</td>
										</tr>
										<tr>
											<td style="text-align: center; color: #616161; font-family: Arial, Helvetica, Sans-Serif; font-size: 16px; line-height: 21px; font-weight: normal; font-style: normal; mso-line-height-rule: exactly;">If you have SYNC®2 with SAT NAV, we'll help you stay on track with yearly map updates for up to 7 years when you complete your service with a participating dealer.</td>
										</tr>
										
										<tr>
											<td height="10">
												<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
											</td>
										</tr>
										<tr>
													<td height="10">
														<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
													</td>
												</tr>
												<tr>
															<td style="text-align: center; color: #616161; font-family: Arial, Helvetica, Sans-Serif; font-size: 16px; line-height: 21px; font-weight: normal; font-style: normal; mso-line-height-rule: exactly;">
																
																<a href="https://www.ford.com.au/owners/service/free-sat-nav-updates/" name="accessory" style="color: #2D96CD; text-decoration: underline;">Learn More</a>
															</td>
														</tr>
												<tr>
													<td height="10">
														<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
													</td>
												</tr>
										<tr>
											<td height="20">
												<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
											</td>
										</tr>
									</table>
								</td>
							</tr>
						</table>
					</td>
					
					<td width="30" class="auto_height"height="380" style="height:380px; font-size:380px; line-height:380px;"  >
						<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
					</td>
				</tr>
			</table>
			
			<table width="310" cellpadding="0" cellspacing="0" border="0" bgcolor="F2F2F2" class="img-max">
				<tr>
					<td	valign="top" align="center">
						<a href="https://www.ford.com.au/owners/service/free-sat-nav-updates/" name="Some" target="_blank"><img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/tiles/au_edm2_free_sat_nav_updates_20170818_tile.jpg" width="310"	border="0" class="img_Rez" />
						</a></td>
				</tr>
			</table>
		</td>
	</tr>
</table>
<!--email_modules/dual/05 ends-->

<!--email_modules/footer/au/social white starts-->


<table bgcolor="#F2F2F2" align="center" class="resize_table_to_320" width="640" border="0" cellspacing="0" cellpadding="0" style="max-width: 640px;">
	<tr>
		<td align="left" valign="top" style="padding-left:20px; padding-right:20px; padding-top:20px;">
			<table align="left" border="0" cellspacing="0" cellpadding="0">
				<tr>
					<td width="84" align="left" valign="middle" style="color:#91A4B1;font-family:Arial, Verdana, Sans-serif;font-size:12px;">Follow us on:</td>
					<td align="left" valign="top">
						<table border="0" cellspacing="0" cellpadding="0">
							<tr>
								<td width="24" align="left" valign="middle" style="font-size:0%;">
									<a href="https://twitter.com/fordaustralia/" title="Twitter" name="twitter_footer" target="_blank" style="font-size:10px; color:#319AD6; text-decoration:none; text-align:center; font-weight:bold;"><img style="display:block;" border="0" src="https://s3-ap-southeast-1.amazonaws.com/edm-images/twitter.gif" alt="T" width="30" height="30" /></a>
								</td>
							</tr>
						</table></td>
					<td width="10" align="left" valign="middle" style="font-size:0%;">
						&nbsp;
					</td>
					<td align="left" valign="top">
						<table border="0" cellspacing="0" cellpadding="0">
							<tr>
								<td width="24" align="left" valign="middle" style="font-size:0%;">
									<a href="https://www.facebook.com/FordAustralia/" name="facebook_footer" title="Facebook" target="_blank" style="font-size:10px; color:#319AD6; text-decoration:none; text-align:center; font-weight:bold;"><img style="display:block;" border="0" src="https://s3-ap-southeast-1.amazonaws.com/edm-images/facebook.gif" alt="F" width="30" height="30" /></a>
								</td>
							</tr>
						</table>
					</td>
				</tr>
			</table>
		</td>
	</tr>
</table>

<!--email_modules/footer/au/social ends-->


<!--email_modules/footer/disclaimer white starts-->


<table bgcolor="#F2F2F2" align="center" class="resize_table_to_320" width="640" border="0" cellspacing="0" cellpadding="0" style="max-width: 640px;">
		<tr>
			<td align="left" valign="top" style="padding-left:20px; padding-right:20px; padding-top:20px;">
				<table width="100%" border="0" cellspacing="0" cellpadding="0">
						<tr>
								<td class="drop1" align="left" valign="top" style="font-size: 11px; line-height: 14px; font-weight: normal; color:#91A4B1; font-style: normal; font-family: 'Arial','Helvetica','Sans-Serif';">DISCLAIMERS:<br /><br />
				1) Available at participating dealers on scheduled services or overnight warranty repairs. Private and Blue, Silver and Gold Business Fleet customers only. Booking may be required. See <a href="https://www.ford.com.au/owners/service/t-and-c/" name="terms11" style="text-decoration:underline; color:#91a4b1"> www.ford.com.au/owners/service/t-and-c</a> for full terms.<br /><br />
                2) Available at participating Ford dealers on vehicles built from 2007. Customers will pay equal to or less than the maximum price as published by Ford for the period of the web quote for standard items in the A and B logbook services. See <a href="https://www.ford.com.au/owners/service/t-and-c/" name="terms11" style="text-decoration:underline; color:#91a4b1"> www.ford.com.au/owners/service/t-and-c</a> for full terms.<br /><br />
                3) Private and Blue Business Fleet customers who have not reached earlier of 7 years or 105,000km, only at participating Dealers. State Auto Club Roadside Assistance & Membership is included for 12 months or until your next eligible standard service (whichever occurs first). Customers must comply with scheduled servicing intervals to maintain continuity of membership. See <a href="https://www.ford.com.au/owners/service/t-and-c/" name="terms11" style="text-decoration:underline; color:#91a4b1"> www.ford.com.au/owners/service/t-and-c</a> for full terms.<br /><br />
                4) Customers must comply with scheduled servicing intervals. See <a href="https://www.ford.com.au/owners/service/t-and-c/" name="terms11" style="text-decoration:underline; color:#91a4b1"> www.ford.com.au/owners/service/t-and-c</a> for full terms.<br /><br /></td>
						</tr>
				</table>
			</td>
	</tr>
</table>


<!--email_modules/footer/disclaimer ends-->


<!--email_modules/footer/au/online white starts-->


<table bgcolor="#F2F2F2" align="center" class="resize_table_to_320" width="640" border="0" cellspacing="0" cellpadding="0" style="max-width: 640px;">
		<tr>
			<td align="left" valign="top" style="padding-left:20px; padding-right:20px; padding-top:20px; padding-bottom:20px;">
				<table width="100%" border="0" cellspacing="0" cellpadding="0">
						<tr>
								<td class="drop1" align="left" valign="top" style="font-size: 11px; line-height: 14px; font-weight: normal; color:#91A4B1; font-style: normal; font-family: 'Arial','Helvetica','Sans-Serif';">
											<a href="https://www.ford.com.au/preference?emailid=20150918-0104_Unsubscribe_WelcomeNewSep_Generic_0_FOA&fbdata=First_Name_PPm%3D<%${user['FirstName']}%>||Last_Name_PPm%3D<%${user['LastName']}%>||Email_PP%3D<%${user.CustomAttribute['RealEmail']}%>" target='_blank' style='color:#91A4B1; text-decoration:underline'>Click here</a> to unsubscribe from future Ford e-mails.<br />Copyright &#169; Ford Motor Company of Australia<br /><br /><a href='http://www.ford.com.au/disclaimer' target='_blank' style='color:#91A4B1; text-decoration:underline'>Disclaimer</a> <a href='http://www.ford.com.au/privacy/' target='_blank' style='color:#91A4B1; text-decoration:underline'>Privacy</a> <a href='http://www.ford.com.au/' target='_blank' style='color:#91A4B1; text-decoration:underline'>ford.com.au</a><br /><br />If you're having difficulty viewing this email, <a href="<%syslink_message_read url='/public/read_message.jsp'%>" target='_blank' style='color:#91A4B1; text-decoration:underline'>go to the web version</a>
								</td>
						</tr>
				</table>
			</td>
	</tr>
</table>

<!--email_modules/footer/au/online ends-->
<div style="font-size:0px; line-height:0px; color:white; display:none;">2017-09-20 02:03:39 UTC</div>
<%/InsertElse%>

<!--1TO7Years_xtime_NonSync-->
<%InsertElse expression="${((user.CustomAttribute['Esplit'] == '1TO7') && (user.CustomAttribute['SERVAPPT'] == 'YES') && (user.CustomAttribute['SYNC_Available'] == 'NO'))}" %>
<div style="font-size:0px; line-height:0px; color:white; display:none;">Don't get stuck without wheels. Book a Free Loan Car with your <%${user.CustomAttribute['Model']}%>'s scheduled service.</div>

<!--email_modules/preheader ends-->


<!--email_modules/image/banner white starts-->


<table align="center" class="resize_table_to_320" width="640" border="0" cellspacing="0" cellpadding="0" style="max-width: 640px;" bgcolor="#FFFFFF">
		<tr>
				<td align="left" valign="top">
						<table width="100%" border="0" cellspacing="0" cellpadding="0">
								<tr>
										<td align="left" valign="top" style="font-size: 0px;">
												<a href="https://www.ford.com.au/owners/service/" name="" target="_blank" title=""><img class="img_R" align="left" src="https://s3-ap-southeast-1.amazonaws.com/edm-images/covers/au_edm2_svc_new_banner_20170817_desktop.jpg" alt="Image Banner" title="Image Banner" border="0" style="display:block; margin:0;" /></a>
										</td>
								</tr>
						</table>
				</td>
		</tr>
</table>

<!--email_modules/image/banner ends-->


<!--email_modules/spacer/default white starts-->

<table align="center" class="resize_table_to_320" width="640" border="0" cellspacing="0" cellpadding="0">
	<tr>
			<td height="30" bgcolor="#FFFFFF" align="left" valign="top" style="font-size:0%;">
				&nbsp;
			</td>
 	</tr>
</table>
<!--email_modules/spacer/default ends-->


<!--email_modules/singles/copy white starts-->

<table width="640" border="0" cellspacing="0" cellpadding="0" bgcolor="#FFFFFF" class="resize_table_to_320" align="center">
	<tr>
		<td style="padding:30px;padding-top:0px;padding-bottom:0px" valign="top">
			<table width="100%" border="0" cellspacing="0" cellpadding="0">
				<tr>
					<td valign="top" align="center">
						<table	border="0" cellspacing="0" cellpadding="0">
							<tr>
								<td style="text-align:center; color:#616161; font-family: 'Arial','Helvetica','Sans-Serif'; font-size:16px; line-height: 21px;
								font-weight: normal; font-style: normal;">Hi <%${user.CustomAttribute['FullName']}%>,<br /><br />This is just a friendly reminder that your Ford <%${user.CustomAttribute['Model']}%> is nearly due for its <%${user.CustomAttribute['Service_Interval']}%>km service.<br /><br />
    We know how important your <%${user.CustomAttribute['Model']}%></span> is to you, so we're sure you'll appreciate the many benefits of putting your <%${user.CustomAttribute['Model']}%></span> in the trusted hands of Ford trained technicians. You can even book a Free Loan Car&#185; for the day when you book your scheduled service.<br /><br />
    Book your service and Free Loan Car&#185; with <span style="color:#2D96CD"><%${user.CustomAttribute['Dealer_Name']}%></span> on <span style="color:#2D96CD"><%${user.CustomAttribute['Dealer_Phone']}%></span> today, or find your <a href="https://www.ford.com.au/dealership/" style="text-decoration:underline; color:#2D96CD">nearest dealer</a>. You can even book online below.</td>
							</tr>
						</table>
					</td>
				</tr>
			</table>
		</td>
	</tr>
</table>
<!--email_modules/singles/copy ends-->


<!--email_modules/spacer/default white starts-->

<table align="center" class="resize_table_to_320" width="640" border="0" cellspacing="0" cellpadding="0">
	<tr>
			<td height="30" bgcolor="#FFFFFF" align="left" valign="top" style="font-size:0%;">
				&nbsp;
			</td>
 	</tr>
</table>
<!--email_modules/spacer/default ends-->


<!--email_modules/singles/ctablock white starts-->

<table width="640" border="0" cellspacing="0" cellpadding="0" bgcolor="#FFFFFF" class="resize_table_to_320" align="center">
	<tr>
		<td style="padding:30px;padding-top:0px;" valign="top">
			<table width="100%" border="0" cellspacing="0" cellpadding="0">
				<tr>
					<td valign="top" align="center">
						<table	border="0" cellspacing="0" cellpadding="0">
							<tr>
								<td height="40" valign="middle" align="center" bgcolor="#2D96CD" style="vertical-align: middle; padding-left:20px; padding-right:20px; text-align:center; font-family: Arial, Helvetica, Sans-Serif; font-size: 16px;">
									<a href="https://consumer.xtime.net.au/scheduling/?company=14745&store=<%${user.CustomAttribute['DealerCode']}%>&VIN=<%${user.CustomAttribute['VIN']}%>&provider=FORD_AU_THE_BLUE_HIVE&keyword=<%${user.CustomAttribute['CampaignID']}%>&dest=&extid=<%${user.CustomAttribute['CampaignID']}%>&extctxt=FORD_AU_THE_BLUE_HIVE&cfn=<%${user.CustomAttribute['FullName']}%>&cln=<%${user['LastName']}%>&cpn=<%${user.CustomAttribute['Mobile_Phone']}%>&cem=<%${user.CustomAttribute['RealEmail']}%>&button=blue" name="service_booking" target="_blank" title="" style="text-decoration:none; width:100%; display:block; color:#FFFFFF;">BOOK YOUR SERVICE</a>
								</td>
							</tr>
						</table>
					</td>
				</tr>
			</table>
		</td>
	</tr>
</table>
<!--email_modules/singles/ctablock ends-->


<!--email_modules/spacer/default white starts-->

<table align="center" class="resize_table_to_320" width="640" border="0" cellspacing="0" cellpadding="0">
	<tr>
			<td height="30" bgcolor="#FFFFFF" align="left" valign="top" style="font-size:0%;">
				&nbsp;
			</td>
 	</tr>
</table>
<!--email_modules/spacer/default ends-->


<!--email_modules/spacer/platinum_20 white starts-->

<table align="center" class="resize_table_to_320" width="640" border="0" cellspacing="0" cellpadding="0">
	<tr>
			<td height="20" bgcolor="#F2F2F2" align="left" valign="top" style="font-size:0%;">
				&nbsp;
			</td>
 	</tr>
</table>
<!--email_modules/spacer/platinum_20 ends-->


<!--email_modules/dual/05 white starts-->

<table width="640" border="0" cellpadding="0" cellspacing="0" border="0" align="center" bgcolor="#FFFFFF" class="resize_table_to_320" style="max-width: 640px;">
	<tr>
		
		<td valign="top" align="center" class="drop">
			
			<table width="310" cellpadding="0" cellspacing="0" border="0" class="wrapper">
				<tr>
					
					
					
					<td width="30" class="auto_height"height="240" style="height:240px; font-size:240px; line-height:240px;"  >
						<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
					</td>
					
					<td class="auto_height"height="240" style="height:240px; font-size:240px; line-height:240px;"  >
						<table width="100%" height="100%" cellpadding="0" cellspacing="0" border="0">
							<tr>
								<td>
									<table width="100%" cellpadding="0" cellspacing="0" border="0">
										
										<tr>
											<td height="20">
												<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
											</td>
										</tr>
										
												<tr>
													<td height="10">
														<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
													</td>
												</tr>
												<tr>
													<td align="center" style="font-family: Arial, Helvetica, Sans-Serif; font-size: 24px; line-height: 30px; font-weight: normal; font-style: normal; mso-line-height-rule: exactly;">Service Price Promise&#178;</td>
												</tr>
												
												<tr>
													<td height="10">
														<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
													</td>
												</tr>
										
										<tr>
											<td height="10">
												<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
											</td>
										</tr>
										<tr>
											<td style="text-align: center; color: #616161; font-family: Arial, Helvetica, Sans-Serif; font-size: 16px; line-height: 21px; font-weight: normal; font-style: normal; mso-line-height-rule: exactly;">Know how much your standard service will cost before you even come in, with the <a href="https://www.ford.com.au/owners/service/calculator/" name="calculator" style="text-decoration:underline; color:#2D96CD"> Service Price Promise Calculator</span>.</td>
										</tr>
										
										<tr>
											<td height="10">
												<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
											</td>
										</tr>
										
										<tr>
											<td height="20">
												<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
											</td>
										</tr>
									</table>
								</td>
							</tr>
						</table>
					</td>
					
					<td width="30" class="auto_height"height="240" style="height:240px; font-size:240px; line-height:240px;"  >
						<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
					</td>
				</tr>
			</table>
			
			<table width="310" cellpadding="0" cellspacing="0" border="0" bgcolor="F2F2F2" class="img-max">
				<tr>
					<td	valign="top" align="center">
						<a href="https://www.ford.com.au/owners/service/calculator/" name="Some" target="_blank"><img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/tiles/au_edm2_service_price_promise_20170818_tile.jpg" width="310"	border="0"	class="img_Rez" />
						</a></td>
				</tr>
			</table>
		</td>
		
		<td width="20" valign="top" align="center" bgcolor="#F2F2F2" class="spacer">
			<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
		</td>
		
		<td valign="top" align="center" class="drop">
			
			<table width="310" cellpadding="0" cellspacing="0" border="0" class="wrapper">
				<tr>
					
					<td width="30" class="auto_height"height="240" style="height:240px; font-size:240px; line-height:240px;"  >
						<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
					</td>
					
					<td class="auto_height"height="240" style="height:240px; font-size:240px; line-height:240px;"  >
						<table width="100%" height="100%" cellpadding="0" cellspacing="0" border="0">
							<tr>
								<td>
									<table width="100%" cellpadding="0" cellspacing="0" border="0">
										
										<tr>
											<td height="20">
												<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
											</td>
										</tr>
										
												<tr>
													<td height="10">
														<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
													</td>
												</tr>
												<tr>
													<td align="center" style="font-family: Arial, Helvetica, Sans-Serif; font-size: 24px; line-height: 30px; font-weight: normal; font-style: normal; mso-line-height-rule: exactly;">Free Loan Car&#185;</td>
												</tr>
												
												<tr>
													<td height="10">
														<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
													</td>
												</tr>
										
										<tr>
											<td height="10">
												<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
											</td>
										</tr>
										<tr>
											<td style="text-align: center; color: #616161; font-family: Arial, Helvetica, Sans-Serif; font-size: 16px; line-height: 21px; font-weight: normal; font-style: normal; mso-line-height-rule: exactly;">Life shouldn't stop when you service your vehicle. That's why we offer a <a href="https://www.ford.com.au/owners/service/" name="freeloan" style="text-decoration:underline; color:#2D96CD">Free Loan Car&#185</a>  when you book a scheduled service.</td>
										</tr>
										
										<tr>
											<td height="10">
												<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
											</td>
										</tr>
										
										<tr>
											<td height="20">
												<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
											</td>
										</tr>
									</table>
								</td>
							</tr>
						</table>
					</td>
					
					<td width="30" class="auto_height"height="240" style="height:240px; font-size:240px; line-height:240px;"  >
						<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
					</td>
				</tr>
			</table>
			
			<table width="310" cellpadding="0" cellspacing="0" border="0" bgcolor="F2F2F2" class="img-max">
				<tr>
					<td	valign="top" align="center">
						<a href="https://www.ford.com.au/owners/service/" name="Some" target="_blank"><img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/tiles/au_edm2_free_loan_car_20170818_tile.jpg" width="310"	border="0" class="img_Rez" />
						</a></td>
				</tr>
			</table>
		</td>
	</tr>
</table>
<!--email_modules/dual/05 ends-->


<!--email_modules/spacer/platinum_20 white starts-->

<table align="center" class="resize_table_to_320" width="640" border="0" cellspacing="0" cellpadding="0">
	<tr>
			<td height="20" bgcolor="#F2F2F2" align="left" valign="top" style="font-size:0%;">
				&nbsp;
			</td>
 	</tr>
</table>
<!--email_modules/spacer/platinum_20 ends-->


<!--email_modules/dual/05 white starts-->

<table width="640" border="0" cellpadding="0" cellspacing="0" border="0" align="center" bgcolor="#FFFFFF" class="resize_table_to_320" style="max-width: 640px;">
	<tr>
		
		<td valign="top" align="center" class="drop">
			
			<table width="310" cellpadding="0" cellspacing="0" border="0" class="wrapper">
				<tr>
					
					
					
					<td width="30" class="auto_height"height="380" style="height:380px; font-size:380px; line-height:380px;"  >
						<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
					</td>
					
					<td class="auto_height"height="380" style="height:380px; font-size:380px; line-height:380px;"  >
						<table width="100%" height="100%" cellpadding="0" cellspacing="0" border="0">
							<tr>
								<td>
									<table width="100%" cellpadding="0" cellspacing="0" border="0">
										
										<tr>
											<td height="20">
												<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
											</td>
										</tr>
										
												<tr>
													<td height="10">
														<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
													</td>
												</tr>
												<tr>
													<td align="center" style="font-family: Arial, Helvetica, Sans-Serif; font-size: 24px; line-height: 30px; font-weight: normal; font-style: normal; mso-line-height-rule: exactly;">Auto Club Membership&#179;</td>
												</tr>
												
												<tr>
													<td height="10">
														<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
													</td>
												</tr>
										
										<tr>
											<td height="10">
												<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
											</td>
										</tr>
										<tr>
											<td style="text-align: center; color: #616161; font-family: Arial, Helvetica, Sans-Serif; font-size: 16px; line-height: 21px; font-weight: normal; font-style: normal; mso-line-height-rule: exactly;">Each time you complete your standard service at a participating Ford dealer you'll receive State Auto Club Roadside Assistance and membership for up to 12 months.</td>
										</tr>
										
										<tr>
											<td height="10">
												<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
											</td>
										</tr>
										
												<tr>
													<td height="10">
														<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
													</td>
												</tr>
												<tr>
															<td style="text-align: center; color: #616161; font-family: Arial, Helvetica, Sans-Serif; font-size: 16px; line-height: 21px; font-weight: normal; font-style: normal; mso-line-height-rule: exactly;">
																
																<a href="https://www.ford.com.au/owners/service/roadside-assistance/" name="AutoClubMembership" style="color: #2D96CD; text-decoration: underline;">Learn More</a>
															</td>
														</tr>
												<tr>
													<td height="10">
														<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
													</td>
												</tr>
										<tr>
											<td height="20">
												<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
											</td>
										</tr>
									</table>
								</td>
							</tr>
						</table>
					</td>
					
					<td width="30" class="auto_height"height="380" style="height:380px; font-size:380px; line-height:380px;"  >
						<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
					</td>
				</tr>
			</table>
			
			<table width="310" cellpadding="0" cellspacing="0" border="0" bgcolor="F2F2F2" class="img-max">
				<tr>
					<td	valign="top" align="center">
						<a href="https://www.ford.com.au/owners/service/roadside-assistance/" name="Some" target="_blank"><img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/tiles/au_edm2_auto_club_membership_20170818_tile.jpg" width="310"	border="0"	class="img_Rez" />
						</a></td>
				</tr>
			</table>
		</td>
		
		<td width="20" valign="top" align="center" bgcolor="#F2F2F2" class="spacer">
			<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
		</td>
		
		<td valign="top" align="center" class="drop">
			
			<table width="310" cellpadding="0" cellspacing="0" border="0" class="wrapper">
				<tr>
					
					<td width="30" class="auto_height"height="380" style="height:380px; font-size:380px; line-height:380px;"  >
						<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
					</td>
					
					<td class="auto_height"height="380" style="height:380px; font-size:380px; line-height:380px;"  >
						<table width="100%" height="100%" cellpadding="0" cellspacing="0" border="0">
							<tr>
								<td>
									<table width="100%" cellpadding="0" cellspacing="0" border="0">
										
										<tr>
											<td height="20">
												<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
											</td>
										</tr>
										
												<tr>
													<td height="10">
														<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
													</td>
												</tr>
												<tr>
													<td align="center" style="font-family: Arial, Helvetica, Sans-Serif; font-size: 24px; line-height: 30px; font-weight: normal; font-style: normal; mso-line-height-rule: exactly;">Vehicle Health Report</td>
												</tr>
												
												<tr>
													<td height="10">
														<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
													</td>
												</tr>
										
										<tr>
											<td height="10">
												<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
											</td>
										</tr>
										<tr>
											<td style="text-align: center; color: #616161; font-family: Arial, Helvetica, Sans-Serif; font-size: 16px; line-height: 21px; font-weight: normal; font-style: normal; mso-line-height-rule: exactly;">To help you better understand your vehicle's condition, you'll receive a comprehensive vehicle health report every time you service.</td>
										</tr>
										
										<tr>
											<td height="10">
												<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
											</td>
										</tr>
										<tr>
													<td height="10">
														<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
													</td>
												</tr>
												<tr>
															<td style="text-align: center; color: #616161; font-family: Arial, Helvetica, Sans-Serif; font-size: 16px; line-height: 21px; font-weight: normal; font-style: normal; mso-line-height-rule: exactly;">
																
																<a href="https://www.ford.com.au/owners/service/vehicle-report-card" name="healthreport" style="color: #2D96CD; text-decoration: underline;">Learn More</a>
															</td>
														</tr>
												<tr>
													<td height="10">
														<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
													</td>
												</tr>
										<tr>
											<td height="20">
												<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
											</td>
										</tr>
									</table>
								</td>
							</tr>
						</table>
					</td>
					
					<td width="30" class="auto_height"height="380" style="height:380px; font-size:380px; line-height:380px;"  >
						<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
					</td>
				</tr>
			</table>
			
			<table width="310" cellpadding="0" cellspacing="0" border="0" bgcolor="F2F2F2" class="img-max">
				<tr>
					<td	valign="top" align="center">
						<a href="https://www.ford.com.au/owners/service/vehicle-report-card" name="Some" target="_blank"><img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/tiles/au_edm2_vehicle_health_report_20170818_tile.jpg" width="310"	border="0" class="img_Rez" />
						</a></td>
				</tr>
			</table>
		</td>
	</tr>
</table>
<!--email_modules/dual/05 ends-->


<!--email_modules/footer/au/social white starts-->


<table bgcolor="#F2F2F2" align="center" class="resize_table_to_320" width="640" border="0" cellspacing="0" cellpadding="0" style="max-width: 640px;">
	<tr>
		<td align="left" valign="top" style="padding-left:20px; padding-right:20px; padding-top:20px;">
			<table align="left" border="0" cellspacing="0" cellpadding="0">
				<tr>
					<td width="84" align="left" valign="middle" style="color:#91A4B1;font-family:Arial, Verdana, Sans-serif;font-size:12px;">Follow us on:</td>
					<td align="left" valign="top">
						<table border="0" cellspacing="0" cellpadding="0">
							<tr>
								<td width="24" align="left" valign="middle" style="font-size:0%;">
									<a href="https://twitter.com/fordaustralia/" title="Twitter" name="twitter_footer" target="_blank" style="font-size:10px; color:#319AD6; text-decoration:none; text-align:center; font-weight:bold;"><img style="display:block;" border="0" src="https://s3-ap-southeast-1.amazonaws.com/edm-images/twitter.gif" alt="T" width="30" height="30" /></a>
								</td>
							</tr>
						</table></td>
					<td width="10" align="left" valign="middle" style="font-size:0%;">
						&nbsp;
					</td>
					<td align="left" valign="top">
						<table border="0" cellspacing="0" cellpadding="0">
							<tr>
								<td width="24" align="left" valign="middle" style="font-size:0%;">
									<a href="https://www.facebook.com/FordAustralia/" name="facebook_footer" title="Facebook" target="_blank" style="font-size:10px; color:#319AD6; text-decoration:none; text-align:center; font-weight:bold;"><img style="display:block;" border="0" src="https://s3-ap-southeast-1.amazonaws.com/edm-images/facebook.gif" alt="F" width="30" height="30" /></a>
								</td>
							</tr>
						</table>
					</td>
				</tr>
			</table>
		</td>
	</tr>
</table>

<!--email_modules/footer/au/social ends-->


<!--email_modules/footer/disclaimer white starts-->


<table bgcolor="#F2F2F2" align="center" class="resize_table_to_320" width="640" border="0" cellspacing="0" cellpadding="0" style="max-width: 640px;">
		<tr>
			<td align="left" valign="top" style="padding-left:20px; padding-right:20px; padding-top:20px;">
				<table width="100%" border="0" cellspacing="0" cellpadding="0">
						<tr>
								<td class="drop1" align="left" valign="top" style="font-size: 11px; line-height: 14px; font-weight: normal; color:#91A4B1; font-style: normal; font-family: 'Arial','Helvetica','Sans-Serif';">DISCLAIMERS:<br /><br />
				1) Available at participating dealers on scheduled services or overnight warranty repairs. Private and Blue, Silver and Gold Business Fleet customers only. Booking may be required. See <a href="https://www.ford.com.au/owners/service/t-and-c/" name="terms11" style="text-decoration:underline; color:#91a4b1"> www.ford.com.au/owners/service/t-and-c</a> for full terms.<br /><br />
                2) Available at participating Ford dealers on vehicles built from 2007. Customers will pay equal to or less than the maximum price as published by Ford for the period of the web quote for standard items in the A and B logbook services. See <a href="https://www.ford.com.au/owners/service/t-and-c/" name="terms11" style="text-decoration:underline; color:#91a4b1"> www.ford.com.au/owners/service/t-and-c</a> for full terms.<br /><br />
                3) Private and Blue Business Fleet customers who have not reached earlier of 7 years or 105,000km, only at participating Dealers. State Auto Club Roadside Assistance & Membership is included for 12 months or until your next eligible standard service (whichever occurs first). Customers must comply with scheduled servicing intervals to maintain continuity of membership. See <a href="https://www.ford.com.au/owners/service/t-and-c/" name="terms11" style="text-decoration:underline; color:#91a4b1"> www.ford.com.au/owners/service/t-and-c</a> for full terms.<br /><br /></td>
						</tr>
				</table>
			</td>
	</tr>
</table>


<!--email_modules/footer/disclaimer ends-->


<!--email_modules/footer/au/online white starts-->


<table bgcolor="#F2F2F2" align="center" class="resize_table_to_320" width="640" border="0" cellspacing="0" cellpadding="0" style="max-width: 640px;">
		<tr>
			<td align="left" valign="top" style="padding-left:20px; padding-right:20px; padding-top:20px; padding-bottom:20px;">
				<table width="100%" border="0" cellspacing="0" cellpadding="0">
						<tr>
								<td class="drop1" align="left" valign="top" style="font-size: 11px; line-height: 14px; font-weight: normal; color:#91A4B1; font-style: normal; font-family: 'Arial','Helvetica','Sans-Serif';">
											<a href="https://www.ford.com.au/preference?emailid=20150918-0104_Unsubscribe_WelcomeNewSep_Generic_0_FOA&fbdata=First_Name_PPm%3D<%${user['FirstName']}%>||Last_Name_PPm%3D<%${user['LastName']}%>||Email_PP%3D<%${user.CustomAttribute['RealEmail']}%>" target='_blank' style='color:#91A4B1; text-decoration:underline'>Click here</a> to unsubscribe from future Ford e-mails.<br />Copyright &#169; Ford Motor Company of Australia<br /><br /><a href='http://www.ford.com.au/disclaimer' target='_blank' style='color:#91A4B1; text-decoration:underline'>Disclaimer</a> <a href='http://www.ford.com.au/privacy/' target='_blank' style='color:#91A4B1; text-decoration:underline'>Privacy</a> <a href='http://www.ford.com.au/' target='_blank' style='color:#91A4B1; text-decoration:underline'>ford.com.au</a><br /><br />If you're having difficulty viewing this email, <a href="<%syslink_message_read url='/public/read_message.jsp'%>" target='_blank' style='color:#91A4B1; text-decoration:underline'>go to the web version</a>
								</td>
						</tr>
				</table>
			</td>
	</tr>
</table>

<!--email_modules/footer/au/online ends-->
<div style="font-size:0px; line-height:0px; color:white; display:none;">2017-09-20 02:03:39 UTC</div>
<%/InsertElse%>

<!--1TO7Years_Nonxtime_Sync-->
<%InsertElse expression="${((user.CustomAttribute['Esplit'] == '1TO7') && (user.CustomAttribute['SERVAPPT'] == 'NO') && (user.CustomAttribute['SYNC_Available'] == 'YES'))}" %>
<div style="font-size:0px; line-height:0px; color:white; display:none;">Don't get stuck without wheels. Book a Free Loan Car with your <%${user.CustomAttribute['Model']}%>'s scheduled service.</div>

<!--email_modules/preheader ends-->


<!--email_modules/image/banner white starts-->


<table align="center" class="resize_table_to_320" width="640" border="0" cellspacing="0" cellpadding="0" style="max-width: 640px;" bgcolor="#FFFFFF">
		<tr>
				<td align="left" valign="top">
						<table width="100%" border="0" cellspacing="0" cellpadding="0">
								<tr>
										<td align="left" valign="top" style="font-size: 0px;">
												<a href="https://www.ford.com.au/owners/service/" name="" target="_blank" title=""><img class="img_R" align="left" src="https://s3-ap-southeast-1.amazonaws.com/edm-images/covers/au_edm2_svc_new_banner_20170817_desktop.jpg" alt="Image Banner" title="Image Banner" border="0" style="display:block; margin:0;" /></a>
										</td>
								</tr>
						</table>
				</td>
		</tr>
</table>

<!--email_modules/image/banner ends-->


<!--email_modules/spacer/default white starts-->

<table align="center" class="resize_table_to_320" width="640" border="0" cellspacing="0" cellpadding="0">
	<tr>
			<td height="30" bgcolor="#FFFFFF" align="left" valign="top" style="font-size:0%;">
				&nbsp;
			</td>
 	</tr>
</table>
<!--email_modules/spacer/default ends-->


<!--email_modules/singles/copy white starts-->

<table width="640" border="0" cellspacing="0" cellpadding="0" bgcolor="#FFFFFF" class="resize_table_to_320" align="center">
	<tr>
		<td style="padding:30px;padding-top:0px;padding-bottom:0px" valign="top">
			<table width="100%" border="0" cellspacing="0" cellpadding="0">
				<tr>
					<td valign="top" align="center">
						<table	border="0" cellspacing="0" cellpadding="0">
							<tr>
								<td style="text-align:center; color:#616161; font-family: 'Arial','Helvetica','Sans-Serif'; font-size:16px; line-height: 21px;
								font-weight: normal; font-style: normal;">Hi <%${user.CustomAttribute['FullName']}%>,<br /><br />This is just a friendly reminder that your Ford <%${user.CustomAttribute['Model']}%> is nearly due for its <%${user.CustomAttribute['Service_Interval']}%>km service.<br /><br />
    We know how important your <%${user.CustomAttribute['Model']}%></span> is to you, so we're sure you'll appreciate the many benefits of putting your <%${user.CustomAttribute['Model']}%></span> in the trusted hands of Ford trained technicians. You can even book a Free Loan Car&#185; for the day when you book your scheduled service.<br /><br />
    Book your service and Free Loan Car&#185; with <span style="color:#2D96CD"><%${user.CustomAttribute['Dealer_Name']}%></span> on <span style="color:#2D96CD"><%${user.CustomAttribute['Dealer_Phone']}%></span> today, or find your <a href="https://www.ford.com.au/dealership/" style="text-decoration:underline; color:#2D96CD">nearest dealer</a>.</td>
							</tr>
						</table>
					</td>
				</tr>
			</table>
		</td>
	</tr>
</table>
<!--email_modules/singles/copy ends-->


<!--email_modules/spacer/default white starts-->

<table align="center" class="resize_table_to_320" width="640" border="0" cellspacing="0" cellpadding="0">
	<tr>
			<td height="30" bgcolor="#FFFFFF" align="left" valign="top" style="font-size:0%;">
				&nbsp;
			</td>
 	</tr>
</table>
<!--email_modules/spacer/default ends-->


<!--email_modules/spacer/default white starts-->

<table align="center" class="resize_table_to_320" width="640" border="0" cellspacing="0" cellpadding="0">
	<tr>
			<td height="30" bgcolor="#FFFFFF" align="left" valign="top" style="font-size:0%;">
				&nbsp;
			</td>
 	</tr>
</table>
<!--email_modules/spacer/default ends-->


<!--email_modules/spacer/platinum_20 white starts-->

<table align="center" class="resize_table_to_320" width="640" border="0" cellspacing="0" cellpadding="0">
	<tr>
			<td height="20" bgcolor="#F2F2F2" align="left" valign="top" style="font-size:0%;">
				&nbsp;
			</td>
 	</tr>
</table>
<!--email_modules/spacer/platinum_20 ends-->


<!--email_modules/dual/05 white starts-->

<table width="640" border="0" cellpadding="0" cellspacing="0" border="0" align="center" bgcolor="#FFFFFF" class="resize_table_to_320" style="max-width: 640px;">
	<tr>
		
		<td valign="top" align="center" class="drop">
			
			<table width="310" cellpadding="0" cellspacing="0" border="0" class="wrapper">
				<tr>
					
					
					
					<td width="30" class="auto_height"height="240" style="height:240px; font-size:240px; line-height:240px;"  >
						<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
					</td>
					
					<td class="auto_height"height="240" style="height:240px; font-size:240px; line-height:240px;"  >
						<table width="100%" height="100%" cellpadding="0" cellspacing="0" border="0">
							<tr>
								<td>
									<table width="100%" cellpadding="0" cellspacing="0" border="0">
										
										<tr>
											<td height="20">
												<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
											</td>
										</tr>
										
												<tr>
													<td height="10">
														<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
													</td>
												</tr>
												<tr>
													<td align="center" style="font-family: Arial, Helvetica, Sans-Serif; font-size: 24px; line-height: 30px; font-weight: normal; font-style: normal; mso-line-height-rule: exactly;">Service Price Promise&#178;</td>
												</tr>
												
												<tr>
													<td height="10">
														<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
													</td>
												</tr>
										
										<tr>
											<td height="10">
												<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
											</td>
										</tr>
										<tr>
											<td style="text-align: center; color: #616161; font-family: Arial, Helvetica, Sans-Serif; font-size: 16px; line-height: 21px; font-weight: normal; font-style: normal; mso-line-height-rule: exactly;">Know how much your standard service will cost before you even come in, with the <a href="https://www.ford.com.au/owners/service/calculator/" name="calculator" style="text-decoration:underline; color:#2D96CD"> Service Price Promise Calculator</span>.</td>
										</tr>
										
										<tr>
											<td height="10">
												<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
											</td>
										</tr>
										
										<tr>
											<td height="20">
												<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
											</td>
										</tr>
									</table>
								</td>
							</tr>
						</table>
					</td>
					
					<td width="30" class="auto_height"height="240" style="height:240px; font-size:240px; line-height:240px;"  >
						<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
					</td>
				</tr>
			</table>
			
			<table width="310" cellpadding="0" cellspacing="0" border="0" bgcolor="F2F2F2" class="img-max">
				<tr>
					<td	valign="top" align="center">
						<a href="https://www.ford.com.au/owners/service/calculator/" name="Some" target="_blank"><img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/tiles/au_edm2_service_price_promise_20170818_tile.jpg" width="310"	border="0"	class="img_Rez" />
						</a></td>
				</tr>
			</table>
		</td>
		
		<td width="20" valign="top" align="center" bgcolor="#F2F2F2" class="spacer">
			<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
		</td>
		
		<td valign="top" align="center" class="drop">
			
			<table width="310" cellpadding="0" cellspacing="0" border="0" class="wrapper">
				<tr>
					
					<td width="30" class="auto_height"height="240" style="height:240px; font-size:240px; line-height:240px;"  >
						<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
					</td>
					
					<td class="auto_height"height="240" style="height:240px; font-size:240px; line-height:240px;"  >
						<table width="100%" height="100%" cellpadding="0" cellspacing="0" border="0">
							<tr>
								<td>
									<table width="100%" cellpadding="0" cellspacing="0" border="0">
										
										<tr>
											<td height="20">
												<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
											</td>
										</tr>
										
												<tr>
													<td height="10">
														<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
													</td>
												</tr>
												<tr>
													<td align="center" style="font-family: Arial, Helvetica, Sans-Serif; font-size: 24px; line-height: 30px; font-weight: normal; font-style: normal; mso-line-height-rule: exactly;">Free Loan Car&#185;</td>
												</tr>
												
												<tr>
													<td height="10">
														<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
													</td>
												</tr>
										
										<tr>
											<td height="10">
												<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
											</td>
										</tr>
										<tr>
											<td style="text-align: center; color: #616161; font-family: Arial, Helvetica, Sans-Serif; font-size: 16px; line-height: 21px; font-weight: normal; font-style: normal; mso-line-height-rule: exactly;">Life shouldn't stop when you service your vehicle. That's why we offer a <a href="https://www.ford.com.au/owners/service/" name="freeloan" style="text-decoration:underline; color:#2D96CD">Free Loan Car&#185</a>  when you book a scheduled service.</td>
										</tr>
										
										<tr>
											<td height="10">
												<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
											</td>
										</tr>
										
										<tr>
											<td height="20">
												<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
											</td>
										</tr>
									</table>
								</td>
							</tr>
						</table>
					</td>
					
					<td width="30" class="auto_height"height="240" style="height:240px; font-size:240px; line-height:240px;"  >
						<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
					</td>
				</tr>
			</table>
			
			<table width="310" cellpadding="0" cellspacing="0" border="0" bgcolor="F2F2F2" class="img-max">
				<tr>
					<td	valign="top" align="center">
						<a href="https://www.ford.com.au/owners/service/" name="Some" target="_blank"><img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/tiles/au_edm2_free_loan_car_20170818_tile.jpg" width="310"	border="0" class="img_Rez" />
						</a></td>
				</tr>
			</table>
		</td>
	</tr>
</table>
<!--email_modules/dual/05 ends-->


<!--email_modules/spacer/platinum_20 white starts-->

<table align="center" class="resize_table_to_320" width="640" border="0" cellspacing="0" cellpadding="0">
	<tr>
			<td height="20" bgcolor="#F2F2F2" align="left" valign="top" style="font-size:0%;">
				&nbsp;
			</td>
 	</tr>
</table>
<!--email_modules/spacer/platinum_20 ends-->


<!--email_modules/dual/05 white starts-->

<table width="640" border="0" cellpadding="0" cellspacing="0" border="0" align="center" bgcolor="#FFFFFF" class="resize_table_to_320" style="max-width: 640px;">
	<tr>
		
		<td valign="top" align="center" class="drop">
			
			<table width="310" cellpadding="0" cellspacing="0" border="0" class="wrapper">
				<tr>
					
					
					
					<td width="30" class="auto_height"height="380" style="height:380px; font-size:380px; line-height:380px;"  >
						<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
					</td>
					
					<td class="auto_height"height="380" style="height:380px; font-size:380px; line-height:380px;"  >
						<table width="100%" height="100%" cellpadding="0" cellspacing="0" border="0">
							<tr>
								<td>
									<table width="100%" cellpadding="0" cellspacing="0" border="0">
										
										<tr>
											<td height="20">
												<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
											</td>
										</tr>
										
												<tr>
													<td height="10">
														<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
													</td>
												</tr>
												<tr>
													<td align="center" style="font-family: Arial, Helvetica, Sans-Serif; font-size: 24px; line-height: 30px; font-weight: normal; font-style: normal; mso-line-height-rule: exactly;">Auto Club Membership&#179;</td>
												</tr>
												
												<tr>
													<td height="10">
														<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
													</td>
												</tr>
										
										<tr>
											<td height="10">
												<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
											</td>
										</tr>
										<tr>
											<td style="text-align: center; color: #616161; font-family: Arial, Helvetica, Sans-Serif; font-size: 16px; line-height: 21px; font-weight: normal; font-style: normal; mso-line-height-rule: exactly;">Each time you complete your standard service at a participating Ford dealer you'll receive State Auto Club Roadside Assistance and membership for up to 12 months.</td>
										</tr>
										
										<tr>
											<td height="10">
												<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
											</td>
										</tr>
										
												<tr>
													<td height="10">
														<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
													</td>
												</tr>
												<tr>
															<td style="text-align: center; color: #616161; font-family: Arial, Helvetica, Sans-Serif; font-size: 16px; line-height: 21px; font-weight: normal; font-style: normal; mso-line-height-rule: exactly;">
																
																<a href="https://www.ford.com.au/owners/service/roadside-assistance/" name="AutoClubMembership" style="color: #2D96CD; text-decoration: underline;">Learn More</a>
															</td>
														</tr>
												<tr>
													<td height="10">
														<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
													</td>
												</tr>
										<tr>
											<td height="20">
												<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
											</td>
										</tr>
									</table>
								</td>
							</tr>
						</table>
					</td>
					
					<td width="30" class="auto_height"height="380" style="height:380px; font-size:380px; line-height:380px;"  >
						<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
					</td>
				</tr>
			</table>
			
			<table width="310" cellpadding="0" cellspacing="0" border="0" bgcolor="F2F2F2" class="img-max">
				<tr>
					<td	valign="top" align="center">
						<a href="https://www.ford.com.au/owners/service/roadside-assistance/" name="" target="_blank"><img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/tiles/au_edm2_auto_club_membership_20170818_tile.jpg" width="310"	border="0"	class="img_Rez" />
						</a></td>
				</tr>
			</table>
		</td>
		
		<td width="20" valign="top" align="center" bgcolor="#F2F2F2" class="spacer">
			<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
		</td>
		
		<td valign="top" align="center" class="drop">
			
			<table width="310" cellpadding="0" cellspacing="0" border="0" class="wrapper">
				<tr>
					
					<td width="30" class="auto_height"height="380" style="height:380px; font-size:380px; line-height:380px;"  >
						<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
					</td>
					
					<td class="auto_height"height="380" style="height:380px; font-size:380px; line-height:380px;"  >
						<table width="100%" height="100%" cellpadding="0" cellspacing="0" border="0">
							<tr>
								<td>
									<table width="100%" cellpadding="0" cellspacing="0" border="0">
										
										<tr>
											<td height="20">
												<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
											</td>
										</tr>
										
												<tr>
													<td height="10">
														<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
													</td>
												</tr>
												<tr>
													<td align="center" style="font-family: Arial, Helvetica, Sans-Serif; font-size: 24px; line-height: 30px; font-weight: normal; font-style: normal; mso-line-height-rule: exactly;">SAT NAV Updates&#8308;</td>
												</tr>
												
												<tr>
													<td height="10">
														<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
													</td>
												</tr>
										
										<tr>
											<td height="10">
												<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
											</td>
										</tr>
										<tr>
											<td style="text-align: center; color: #616161; font-family: Arial, Helvetica, Sans-Serif; font-size: 16px; line-height: 21px; font-weight: normal; font-style: normal; mso-line-height-rule: exactly;">If you have SYNC®2 with SAT NAV, we'll help you stay on track with yearly map updates for up to 7 years when you complete your service with a participating dealer.</td>
										</tr>
										
										<tr>
											<td height="10">
												<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
											</td>
										</tr>
										<tr>
													<td height="10">
														<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
													</td>
												</tr>
												<tr>
															<td style="text-align: center; color: #616161; font-family: Arial, Helvetica, Sans-Serif; font-size: 16px; line-height: 21px; font-weight: normal; font-style: normal; mso-line-height-rule: exactly;">
																
																<a href="https://www.ford.com.au/owners/service/free-sat-nav-updates/" name="accessory" style="color: #2D96CD; text-decoration: underline;">Learn More</a>
															</td>
														</tr>
												<tr>
													<td height="10">
														<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
													</td>
												</tr>
										<tr>
											<td height="20">
												<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
											</td>
										</tr>
									</table>
								</td>
							</tr>
						</table>
					</td>
					
					<td width="30" class="auto_height"height="380" style="height:380px; font-size:380px; line-height:380px;"  >
						<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
					</td>
				</tr>
			</table>
			
			<table width="310" cellpadding="0" cellspacing="0" border="0" bgcolor="F2F2F2" class="img-max">
				<tr>
					<td	valign="top" align="center">
						<a href="https://www.ford.com.au/owners/service/free-sat-nav-updates/" name="" target="_blank"><img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/tiles/au_edm2_free_sat_nav_updates_20170818_tile.jpg" width="310"	border="0" class="img_Rez" />
						</a></td>
				</tr>
			</table>
		</td>
	</tr>
</table>
<!--email_modules/dual/05 ends-->


<!--email_modules/footer/au/social white starts-->


<table bgcolor="#F2F2F2" align="center" class="resize_table_to_320" width="640" border="0" cellspacing="0" cellpadding="0" style="max-width: 640px;">
	<tr>
		<td align="left" valign="top" style="padding-left:20px; padding-right:20px; padding-top:20px;">
			<table align="left" border="0" cellspacing="0" cellpadding="0">
				<tr>
					<td width="84" align="left" valign="middle" style="color:#91A4B1;font-family:Arial, Verdana, Sans-serif;font-size:12px;">Follow us on:</td>
					<td align="left" valign="top">
						<table border="0" cellspacing="0" cellpadding="0">
							<tr>
								<td width="24" align="left" valign="middle" style="font-size:0%;">
									<a href="https://twitter.com/fordaustralia/" title="Twitter" name="twitter_footer" target="_blank" style="font-size:10px; color:#319AD6; text-decoration:none; text-align:center; font-weight:bold;"><img style="display:block;" border="0" src="https://s3-ap-southeast-1.amazonaws.com/edm-images/twitter.gif" alt="T" width="30" height="30" /></a>
								</td>
							</tr>
						</table></td>
					<td width="10" align="left" valign="middle" style="font-size:0%;">
						&nbsp;
					</td>
					<td align="left" valign="top">
						<table border="0" cellspacing="0" cellpadding="0">
							<tr>
								<td width="24" align="left" valign="middle" style="font-size:0%;">
									<a href="https://www.facebook.com/FordAustralia/" name="facebook_footer" title="Facebook" target="_blank" style="font-size:10px; color:#319AD6; text-decoration:none; text-align:center; font-weight:bold;"><img style="display:block;" border="0" src="https://s3-ap-southeast-1.amazonaws.com/edm-images/facebook.gif" alt="F" width="30" height="30" /></a>
								</td>
							</tr>
						</table>
					</td>
				</tr>
			</table>
		</td>
	</tr>
</table>

<!--email_modules/footer/au/social ends-->


<!--email_modules/footer/disclaimer white starts-->


<table bgcolor="#F2F2F2" align="center" class="resize_table_to_320" width="640" border="0" cellspacing="0" cellpadding="0" style="max-width: 640px;">
		<tr>
			<td align="left" valign="top" style="padding-left:20px; padding-right:20px; padding-top:20px;">
				<table width="100%" border="0" cellspacing="0" cellpadding="0">
						<tr>
								<td class="drop1" align="left" valign="top" style="font-size: 11px; line-height: 14px; font-weight: normal; color:#91A4B1; font-style: normal; font-family: 'Arial','Helvetica','Sans-Serif';">DISCLAIMERS:<br /><br />
				1) Available at participating dealers on scheduled services or overnight warranty repairs. Private and Blue, Silver and Gold Business Fleet customers only. Booking may be required. See <a href="https://www.ford.com.au/owners/service/t-and-c/" name="terms11" style="text-decoration:underline; color:#91a4b1"> www.ford.com.au/owners/service/t-and-c</a> for full terms.<br /><br />
                2) Available at participating Ford dealers on vehicles built from 2007. Customers will pay equal to or less than the maximum price as published by Ford for the period of the web quote for standard items in the A and B logbook services. See <a href="https://www.ford.com.au/owners/service/t-and-c/" name="terms11" style="text-decoration:underline; color:#91a4b1"> www.ford.com.au/owners/service/t-and-c</a> for full terms.<br /><br />
                3) Private and Blue Business Fleet customers who have not reached earlier of 7 years or 105,000km, only at participating Dealers. State Auto Club Roadside Assistance & Membership is included for 12 months or until your next eligible standard service (whichever occurs first). Customers must comply with scheduled servicing intervals to maintain continuity of membership. See <a href="https://www.ford.com.au/owners/service/t-and-c/" name="terms11" style="text-decoration:underline; color:#91a4b1"> www.ford.com.au/owners/service/t-and-c</a> for full terms.<br /><br />
                4) Customers must comply with scheduled servicing intervals. See <a href="https://www.ford.com.au/owners/service/t-and-c/" name="terms11" style="text-decoration:underline; color:#91a4b1"> www.ford.com.au/owners/service/t-and-c</a> for full terms.<br /><br /></td>
						</tr>
				</table>
			</td>
	</tr>
</table>


<!--email_modules/footer/disclaimer ends-->


<!--email_modules/footer/au/online white starts-->


<table bgcolor="#F2F2F2" align="center" class="resize_table_to_320" width="640" border="0" cellspacing="0" cellpadding="0" style="max-width: 640px;">
		<tr>
			<td align="left" valign="top" style="padding-left:20px; padding-right:20px; padding-top:20px; padding-bottom:20px;">
				<table width="100%" border="0" cellspacing="0" cellpadding="0">
						<tr>
								<td class="drop1" align="left" valign="top" style="font-size: 11px; line-height: 14px; font-weight: normal; color:#91A4B1; font-style: normal; font-family: 'Arial','Helvetica','Sans-Serif';">
											<a href="https://www.ford.com.au/preference?emailid=20150918-0104_Unsubscribe_WelcomeNewSep_Generic_0_FOA&fbdata=First_Name_PPm%3D<%${user['FirstName']}%>||Last_Name_PPm%3D<%${user['LastName']}%>||Email_PP%3D<%${user.CustomAttribute['RealEmail']}%>" target='_blank' style='color:#91A4B1; text-decoration:underline'>Click here</a> to unsubscribe from future Ford e-mails.<br />Copyright &#169; Ford Motor Company of Australia<br /><br /><a href='http://www.ford.com.au/disclaimer' target='_blank' style='color:#91A4B1; text-decoration:underline'>Disclaimer</a> <a href='http://www.ford.com.au/privacy/' target='_blank' style='color:#91A4B1; text-decoration:underline'>Privacy</a> <a href='http://www.ford.com.au/' target='_blank' style='color:#91A4B1; text-decoration:underline'>ford.com.au</a><br /><br />If you're having difficulty viewing this email, <a href="<%syslink_message_read url='/public/read_message.jsp'%>" target='_blank' style='color:#91A4B1; text-decoration:underline'>go to the web version</a>
								</td>
						</tr>
				</table>
			</td>
	</tr>
</table>

<!--email_modules/footer/au/online ends-->
<div style="font-size:0px; line-height:0px; color:white; display:none;">2017-09-20 02:03:39 UTC</div>
<%/InsertElse%>

<!--1TO7Years_Nonxtime_NonSync-->
<%InsertElse expression="${((user.CustomAttribute['Esplit'] == '1TO7') && (user.CustomAttribute['SERVAPPT'] == 'NO') && (user.CustomAttribute['SYNC_Available'] == 'NO'))}" %>
<div style="font-size:0px; line-height:0px; color:white; display:none;">Don't get stuck without wheels. Book a Free Loan Car with your <%${user.CustomAttribute['Model']}%>'s scheduled service.</div>

<!--email_modules/preheader ends-->


<!--email_modules/image/banner white starts-->


<table align="center" class="resize_table_to_320" width="640" border="0" cellspacing="0" cellpadding="0" style="max-width: 640px;" bgcolor="#FFFFFF">
		<tr>
				<td align="left" valign="top">
						<table width="100%" border="0" cellspacing="0" cellpadding="0">
								<tr>
										<td align="left" valign="top" style="font-size: 0px;">
												<a href="https://www.ford.com.au/owners/service/" name="" target="_blank" title=""><img class="img_R" align="left" src="https://s3-ap-southeast-1.amazonaws.com/edm-images/covers/au_edm2_svc_new_banner_20170817_desktop.jpg" alt="Image Banner" title="Image Banner" border="0" style="display:block; margin:0;" /></a>
										</td>
								</tr>
						</table>
				</td>
		</tr>
</table>

<!--email_modules/image/banner ends-->


<!--email_modules/spacer/default white starts-->

<table align="center" class="resize_table_to_320" width="640" border="0" cellspacing="0" cellpadding="0">
	<tr>
			<td height="30" bgcolor="#FFFFFF" align="left" valign="top" style="font-size:0%;">
				&nbsp;
			</td>
 	</tr>
</table>
<!--email_modules/spacer/default ends-->


<!--email_modules/singles/copy white starts-->

<table width="640" border="0" cellspacing="0" cellpadding="0" bgcolor="#FFFFFF" class="resize_table_to_320" align="center">
	<tr>
		<td style="padding:30px;padding-top:0px;padding-bottom:0px" valign="top">
			<table width="100%" border="0" cellspacing="0" cellpadding="0">
				<tr>
					<td valign="top" align="center">
						<table	border="0" cellspacing="0" cellpadding="0">
							<tr>
								<td style="text-align:center; color:#616161; font-family: 'Arial','Helvetica','Sans-Serif'; font-size:16px; line-height: 21px;
								font-weight: normal; font-style: normal;">Hi <%${user.CustomAttribute['FullName']}%>,<br /><br />This is just a friendly reminder that your Ford <%${user.CustomAttribute['Model']}%> is nearly due for its <%${user.CustomAttribute['Service_Interval']}%>km service.<br /><br />
    We know how important your <%${user.CustomAttribute['Model']}%></span> is to you, so we're sure you'll appreciate the many benefits of putting your <%${user.CustomAttribute['Model']}%></span> in the trusted hands of Ford trained technicians. You can even book a Free Loan Car&#185; for the day when you book your scheduled service.<br /><br />
    Book your service and Free Loan Car&#185; with <span style="color:#2D96CD"><%${user.CustomAttribute['Dealer_Name']}%></span> on <span style="color:#2D96CD"><%${user.CustomAttribute['Dealer_Phone']}%></span> today, or find your <a href="https://www.ford.com.au/dealership/" style="text-decoration:underline; color:#2D96CD">nearest dealer</a>.</td>
							</tr>
						</table>
					</td>
				</tr>
			</table>
		</td>
	</tr>
</table>
<!--email_modules/singles/copy ends-->


<!--email_modules/spacer/default white starts-->

<table align="center" class="resize_table_to_320" width="640" border="0" cellspacing="0" cellpadding="0">
	<tr>
			<td height="30" bgcolor="#FFFFFF" align="left" valign="top" style="font-size:0%;">
				&nbsp;
			</td>
 	</tr>
</table>
<!--email_modules/spacer/default ends-->


<!--email_modules/spacer/default white starts-->

<table align="center" class="resize_table_to_320" width="640" border="0" cellspacing="0" cellpadding="0">
	<tr>
			<td height="30" bgcolor="#FFFFFF" align="left" valign="top" style="font-size:0%;">
				&nbsp;
			</td>
 	</tr>
</table>
<!--email_modules/spacer/default ends-->


<!--email_modules/spacer/platinum_20 white starts-->

<table align="center" class="resize_table_to_320" width="640" border="0" cellspacing="0" cellpadding="0">
	<tr>
			<td height="20" bgcolor="#F2F2F2" align="left" valign="top" style="font-size:0%;">
				&nbsp;
			</td>
 	</tr>
</table>
<!--email_modules/spacer/platinum_20 ends-->


<!--email_modules/dual/05 white starts-->

<table width="640" border="0" cellpadding="0" cellspacing="0" border="0" align="center" bgcolor="#FFFFFF" class="resize_table_to_320" style="max-width: 640px;">
	<tr>
		
		<td valign="top" align="center" class="drop">
			
			<table width="310" cellpadding="0" cellspacing="0" border="0" class="wrapper">
				<tr>
					
					
					
					<td width="30" class="auto_height"height="240" style="height:240px; font-size:240px; line-height:240px;"  >
						<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
					</td>
					
					<td class="auto_height"height="240" style="height:240px; font-size:240px; line-height:240px;"  >
						<table width="100%" height="100%" cellpadding="0" cellspacing="0" border="0">
							<tr>
								<td>
									<table width="100%" cellpadding="0" cellspacing="0" border="0">
										
										<tr>
											<td height="20">
												<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
											</td>
										</tr>
										
												<tr>
													<td height="10">
														<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
													</td>
												</tr>
												<tr>
													<td align="center" style="font-family: Arial, Helvetica, Sans-Serif; font-size: 24px; line-height: 30px; font-weight: normal; font-style: normal; mso-line-height-rule: exactly;">Service Price Promise&#178;</td>
												</tr>
												
												<tr>
													<td height="10">
														<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
													</td>
												</tr>
										
										<tr>
											<td height="10">
												<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
											</td>
										</tr>
										<tr>
											<td style="text-align: center; color: #616161; font-family: Arial, Helvetica, Sans-Serif; font-size: 16px; line-height: 21px; font-weight: normal; font-style: normal; mso-line-height-rule: exactly;">Know how much your standard service will cost before you even come in, with the <a href="https://www.ford.com.au/owners/service/calculator/" name="calculator" style="text-decoration:underline; color:#2D96CD"> Service Price Promise Calculator</span>.</td>
										</tr>
										
										<tr>
											<td height="10">
												<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
											</td>
										</tr>
										
										<tr>
											<td height="20">
												<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
											</td>
										</tr>
									</table>
								</td>
							</tr>
						</table>
					</td>
					
					<td width="30" class="auto_height"height="240" style="height:240px; font-size:240px; line-height:240px;"  >
						<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
					</td>
				</tr>
			</table>
			
			<table width="310" cellpadding="0" cellspacing="0" border="0" bgcolor="F2F2F2" class="img-max">
				<tr>
					<td	valign="top" align="center">
						<a href="https://www.ford.com.au/owners/service/calculator/" name="Some" target="_blank"><img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/tiles/au_edm2_service_price_promise_20170818_tile.jpg" width="310"	border="0"	class="img_Rez" />
						</a></td>
				</tr>
			</table>
		</td>
		
		<td width="20" valign="top" align="center" bgcolor="#F2F2F2" class="spacer">
			<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
		</td>
		
		<td valign="top" align="center" class="drop">
			
			<table width="310" cellpadding="0" cellspacing="0" border="0" class="wrapper">
				<tr>
					
					<td width="30" class="auto_height"height="240" style="height:240px; font-size:240px; line-height:240px;"  >
						<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
					</td>
					
					<td class="auto_height"height="240" style="height:240px; font-size:240px; line-height:240px;"  >
						<table width="100%" height="100%" cellpadding="0" cellspacing="0" border="0">
							<tr>
								<td>
									<table width="100%" cellpadding="0" cellspacing="0" border="0">
										
										<tr>
											<td height="20">
												<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
											</td>
										</tr>
										
												<tr>
													<td height="10">
														<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
													</td>
												</tr>
												<tr>
													<td align="center" style="font-family: Arial, Helvetica, Sans-Serif; font-size: 24px; line-height: 30px; font-weight: normal; font-style: normal; mso-line-height-rule: exactly;">Free Loan Car&#185;</td>
												</tr>
												
												<tr>
													<td height="10">
														<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
													</td>
												</tr>
										
										<tr>
											<td height="10">
												<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
											</td>
										</tr>
										<tr>
											<td style="text-align: center; color: #616161; font-family: Arial, Helvetica, Sans-Serif; font-size: 16px; line-height: 21px; font-weight: normal; font-style: normal; mso-line-height-rule: exactly;">Life shouldn't stop when you service your vehicle. That's why we offer a <a href="https://www.ford.com.au/owners/service/" name="freeloan" style="text-decoration:underline; color:#2D96CD">Free Loan Car&#185</a>  when you book a scheduled service.</td>
										</tr>
										
										<tr>
											<td height="10">
												<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
											</td>
										</tr>
										
										<tr>
											<td height="20">
												<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
											</td>
										</tr>
									</table>
								</td>
							</tr>
						</table>
					</td>
					
					<td width="30" class="auto_height"height="240" style="height:240px; font-size:240px; line-height:240px;"  >
						<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
					</td>
				</tr>
			</table>
			
			<table width="310" cellpadding="0" cellspacing="0" border="0" bgcolor="F2F2F2" class="img-max">
				<tr>
					<td	valign="top" align="center">
						<a href="https://www.ford.com.au/owners/service/" name="Some" target="_blank"><img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/tiles/au_edm2_free_loan_car_20170818_tile.jpg" width="310"	border="0" class="img_Rez" />
						</a></td>
				</tr>
			</table>
		</td>
	</tr>
</table>
<!--email_modules/dual/05 ends-->


<!--email_modules/spacer/platinum_20 white starts-->

<table align="center" class="resize_table_to_320" width="640" border="0" cellspacing="0" cellpadding="0">
	<tr>
			<td height="20" bgcolor="#F2F2F2" align="left" valign="top" style="font-size:0%;">
				&nbsp;
			</td>
 	</tr>
</table>
<!--email_modules/spacer/platinum_20 ends-->


<!--email_modules/dual/05 white starts-->

<table width="640" border="0" cellpadding="0" cellspacing="0" border="0" align="center" bgcolor="#FFFFFF" class="resize_table_to_320" style="max-width: 640px;">
	<tr>
		
		<td valign="top" align="center" class="drop">
			
			<table width="310" cellpadding="0" cellspacing="0" border="0" class="wrapper">
				<tr>
					
					
					
					<td width="30" class="auto_height"height="380" style="height:380px; font-size:380px; line-height:380px;"  >
						<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
					</td>
					
					<td class="auto_height"height="380" style="height:380px; font-size:380px; line-height:380px;"  >
						<table width="100%" height="100%" cellpadding="0" cellspacing="0" border="0">
							<tr>
								<td>
									<table width="100%" cellpadding="0" cellspacing="0" border="0">
										
										<tr>
											<td height="20">
												<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
											</td>
										</tr>
										
												<tr>
													<td height="10">
														<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
													</td>
												</tr>
												<tr>
													<td align="center" style="font-family: Arial, Helvetica, Sans-Serif; font-size: 24px; line-height: 30px; font-weight: normal; font-style: normal; mso-line-height-rule: exactly;">Auto Club Membership&#179;</td>
												</tr>
												
												<tr>
													<td height="10">
														<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
													</td>
												</tr>
										
										<tr>
											<td height="10">
												<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
											</td>
										</tr>
										<tr>
											<td style="text-align: center; color: #616161; font-family: Arial, Helvetica, Sans-Serif; font-size: 16px; line-height: 21px; font-weight: normal; font-style: normal; mso-line-height-rule: exactly;">Each time you complete your standard service at a participating Ford dealer you'll receive State Auto Club Roadside Assistance and membership for up to 12 months.</td>
										</tr>
										
										<tr>
											<td height="10">
												<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
											</td>
										</tr>
										
												<tr>
													<td height="10">
														<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
													</td>
												</tr>
												<tr>
															<td style="text-align: center; color: #616161; font-family: Arial, Helvetica, Sans-Serif; font-size: 16px; line-height: 21px; font-weight: normal; font-style: normal; mso-line-height-rule: exactly;">
																
																<a href="https://www.ford.com.au/owners/service/roadside-assistance/" name="autoClubMembership" style="color: #2D96CD; text-decoration: underline;">Learn More</a>
															</td>
														</tr>
												<tr>
													<td height="10">
														<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
													</td>
												</tr>
										<tr>
											<td height="20">
												<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
											</td>
										</tr>
									</table>
								</td>
							</tr>
						</table>
					</td>
					
					<td width="30" class="auto_height"height="380" style="height:380px; font-size:380px; line-height:380px;"  >
						<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
					</td>
				</tr>
			</table>
			
			<table width="310" cellpadding="0" cellspacing="0" border="0" bgcolor="F2F2F2" class="img-max">
				<tr>
					<td	valign="top" align="center">
						<a href="https://www.ford.com.au/owners/service/roadside-assistance/" name="Some" target="_blank"><img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/tiles/au_edm2_auto_club_membership_20170818_tile.jpg" width="310"	border="0"	class="img_Rez" />
						</a></td>
				</tr>
			</table>
		</td>
		
		<td width="20" valign="top" align="center" bgcolor="#F2F2F2" class="spacer">
			<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
		</td>
		
		<td valign="top" align="center" class="drop">
			
			<table width="310" cellpadding="0" cellspacing="0" border="0" class="wrapper">
				<tr>
					
					<td width="30" class="auto_height"height="380" style="height:380px; font-size:380px; line-height:380px;"  >
						<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
					</td>
					
					<td class="auto_height"height="380" style="height:380px; font-size:380px; line-height:380px;"  >
						<table width="100%" height="100%" cellpadding="0" cellspacing="0" border="0">
							<tr>
								<td>
									<table width="100%" cellpadding="0" cellspacing="0" border="0">
										
										<tr>
											<td height="20">
												<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
											</td>
										</tr>
										
												<tr>
													<td height="10">
														<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
													</td>
												</tr>
												<tr>
													<td align="center" style="font-family: Arial, Helvetica, Sans-Serif; font-size: 24px; line-height: 30px; font-weight: normal; font-style: normal; mso-line-height-rule: exactly;">Genuine Service</td>
												</tr>
												
												<tr>
													<td height="10">
														<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
													</td>
												</tr>
										
										<tr>
											<td height="10">
												<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
											</td>
										</tr>
										<tr>
											<td style="text-align: center; color: #616161; font-family: Arial, Helvetica, Sans-Serif; font-size: 16px; line-height: 21px; font-weight: normal; font-style: normal; mso-line-height-rule: exactly;">We know how important your <Nameplate> is to you, so we're sure you'll appreciate that our factory-trained technicians only use Genuine Ford parts and equipment.</td>
										</tr>
										
										<tr>
											<td height="10">
												<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
											</td>
										</tr>
										<tr>
													<td height="10">
														<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
													</td>
												</tr>
												<tr>
															<td style="text-align: center; color: #616161; font-family: Arial, Helvetica, Sans-Serif; font-size: 16px; line-height: 21px; font-weight: normal; font-style: normal; mso-line-height-rule: exactly;">
																
																<a href="http://genuineisbest.com.au/" name="LearnMore" style="color: #2D96CD; text-decoration: underline;">Learn More</a>
															</td>
														</tr>
												<tr>
													<td height="10">
														<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
													</td>
												</tr>
										<tr>
											<td height="20">
												<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
											</td>
										</tr>
									</table>
								</td>
							</tr>
						</table>
					</td>
					
					<td width="30" class="auto_height"height="380" style="height:380px; font-size:380px; line-height:380px;"  >
						<img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/custom/spacer.gif" width="1" height="1" border="0" style="display: block;">
					</td>
				</tr>
			</table>
			
			<table width="310" cellpadding="0" cellspacing="0" border="0" bgcolor="F2F2F2" class="img-max">
				<tr>
					<td	valign="top" align="center">
						<a href="http://genuineisbest.com.au/" name="Some" target="_blank"><img src="https://s3-ap-southeast-1.amazonaws.com/edm-images/tiles/au_edm2_genuine_service_20170818_tile.jpg" width="310"	border="0" class="img_Rez" />
						</a></td>
				</tr>
			</table>
		</td>
	</tr>
</table>
<!--email_modules/dual/05 ends-->


<!--email_modules/footer/au/social white starts-->


<table bgcolor="#F2F2F2" align="center" class="resize_table_to_320" width="640" border="0" cellspacing="0" cellpadding="0" style="max-width: 640px;">
	<tr>
		<td align="left" valign="top" style="padding-left:20px; padding-right:20px; padding-top:20px;">
			<table align="left" border="0" cellspacing="0" cellpadding="0">
				<tr>
					<td width="84" align="left" valign="middle" style="color:#91A4B1;font-family:Arial, Verdana, Sans-serif;font-size:12px;">Follow us on:</td>
					<td align="left" valign="top">
						<table border="0" cellspacing="0" cellpadding="0">
							<tr>
								<td width="24" align="left" valign="middle" style="font-size:0%;">
									<a href="https://twitter.com/fordaustralia/" title="Twitter" name="twitter_footer" target="_blank" style="font-size:10px; color:#319AD6; text-decoration:none; text-align:center; font-weight:bold;"><img style="display:block;" border="0" src="https://s3-ap-southeast-1.amazonaws.com/edm-images/twitter.gif" alt="T" width="30" height="30" /></a>
								</td>
							</tr>
						</table></td>
					<td width="10" align="left" valign="middle" style="font-size:0%;">
						&nbsp;
					</td>
					<td align="left" valign="top">
						<table border="0" cellspacing="0" cellpadding="0">
							<tr>
								<td width="24" align="left" valign="middle" style="font-size:0%;">
									<a href="https://www.facebook.com/FordAustralia/" name="facebook_footer" title="Facebook" target="_blank" style="font-size:10px; color:#319AD6; text-decoration:none; text-align:center; font-weight:bold;"><img style="display:block;" border="0" src="https://s3-ap-southeast-1.amazonaws.com/edm-images/facebook.gif" alt="F" width="30" height="30" /></a>
								</td>
							</tr>
						</table>
					</td>
				</tr>
			</table>
		</td>
	</tr>
</table>

<!--email_modules/footer/au/social ends-->


<!--email_modules/footer/disclaimer white starts-->


<table bgcolor="#F2F2F2" align="center" class="resize_table_to_320" width="640" border="0" cellspacing="0" cellpadding="0" style="max-width: 640px;">
		<tr>
			<td align="left" valign="top" style="padding-left:20px; padding-right:20px; padding-top:20px;">
				<table width="100%" border="0" cellspacing="0" cellpadding="0">
						<tr>
								<td class="drop1" align="left" valign="top" style="font-size: 11px; line-height: 14px; font-weight: normal; color:#91A4B1; font-style: normal; font-family: 'Arial','Helvetica','Sans-Serif';">DISCLAIMERS:<br /><br />
				1) Available at participating dealers on scheduled services or overnight warranty repairs. Private and Blue, Silver and Gold Business Fleet customers only. Booking may be required. See <a href="https://www.ford.com.au/owners/service/t-and-c/" name="terms11" style="text-decoration:underline; color:#91a4b1"> www.ford.com.au/owners/service/t-and-c</a> for full terms.<br /><br />
                2) Available at participating Ford dealers on vehicles built from 2007. Customers will pay equal to or less than the maximum price as published by Ford for the period of the web quote for standard items in the A and B logbook services. See <a href="https://www.ford.com.au/owners/service/t-and-c/" name="terms11" style="text-decoration:underline; color:#91a4b1"> www.ford.com.au/owners/service/t-and-c</a> for full terms.<br /><br />
                3) Private and Blue Business Fleet customers who have not reached earlier of 7 years or 105,000km, only at participating Dealers. State Auto Club Roadside Assistance & Membership is included for 12 months or until your next eligible standard service (whichever occurs first). Customers must comply with scheduled servicing intervals to maintain continuity of membership. See <a href="https://www.ford.com.au/owners/service/t-and-c/" name="terms11" style="text-decoration:underline; color:#91a4b1"> www.ford.com.au/owners/service/t-and-c</a> for full terms.<br /><br /></td>
						</tr>
				</table>
			</td>
	</tr>
</table>


<!--email_modules/footer/disclaimer ends-->


<!--email_modules/footer/au/online white starts-->


<table bgcolor="#F2F2F2" align="center" class="resize_table_to_320" width="640" border="0" cellspacing="0" cellpadding="0" style="max-width: 640px;">
		<tr>
			<td align="left" valign="top" style="padding-left:20px; padding-right:20px; padding-top:20px; padding-bottom:20px;">
				<table width="100%" border="0" cellspacing="0" cellpadding="0">
						<tr>
								<td class="drop1" align="left" valign="top" style="font-size: 11px; line-height: 14px; font-weight: normal; color:#91A4B1; font-style: normal; font-family: 'Arial','Helvetica','Sans-Serif';">
											<a href="https://www.ford.com.au/preference?emailid=20150918-0104_Unsubscribe_WelcomeNewSep_Generic_0_FOA&fbdata=First_Name_PPm%3D<%${user['FirstName']}%>||Last_Name_PPm%3D<%${user['LastName']}%>||Email_PP%3D<%${user.CustomAttribute['RealEmail']}%>" target='_blank' style='color:#91A4B1; text-decoration:underline'>Click here</a> to unsubscribe from future Ford e-mails.<br />Copyright &#169; Ford Motor Company of Australia<br /><br /><a href='http://www.ford.com.au/disclaimer' target='_blank' style='color:#91A4B1; text-decoration:underline'>Disclaimer</a> <a href='http://www.ford.com.au/privacy/' target='_blank' style='color:#91A4B1; text-decoration:underline'>Privacy</a> <a href='http://www.ford.com.au/' target='_blank' style='color:#91A4B1; text-decoration:underline'>ford.com.au</a><br /><br />If you're having difficulty viewing this email, <a href="<%syslink_message_read url='/public/read_message.jsp'%>" target='_blank' style='color:#91A4B1; text-decoration:underline'>go to the web version</a>
								</td>
						</tr>
				</table>
			</td>
	</tr>
</table>

<!--email_modules/footer/au/online ends-->
<div style="font-size:0px; line-height:0px; color:white; display:none;">2017-09-20 02:03:39 UTC</div>
<%/InsertElse%>

</body>
</html>
