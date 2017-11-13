+++
markets = ["vn"]
title = '''VN Anniversary 006 Ranger'''

[[module]]
path='email_modules/preheader'

	preheader = '''Bạn có tin đã 12 tháng trôi qua kể từ ngày bạn lái chiếc Ranger mới về nhà? Chúng tôi không thể để ngày đặc biệt này trôi qua mà không gửi lời cảm ơn tới bạn, một lần nữa, vì đã chọn Ford.'''

[[module]] #Header Logo
path='email_modules/header/logo'
color='white'

	image = '''white'''
	url_link = '''https://www.ford.com.vn/'''

[[module]] #Cover 01
path='email_modules/cover/01'
color='''white'''
 
	title = '''Mới như ngày hôm qua'''
	copy = '''Xin chào <%${user['LastName']}%>,<br /><br />Bạn có tin đã 12 tháng trôi qua kể từ ngày bạn lái chiếc Ranger mới về nhà? Chúng tôi không thể để ngày đặc biệt này trôi qua mà không gửi lời cảm ơn tới bạn, một lần nữa, vì đã chọn Ford. Chúng tôi sẽ còn tiếp tục cập nhật thông tin để bạn sẽ luôn là người đầu tiên được thông báo về những ưu đãi đặc biệt và các thông tin hữu ích khác từ Ford Việt Nam. Chắc chắn là như vậy.'''

[[module]] #Banner Image No Link
path = '''email_modules/image/banner_nolink'''
color = '''white'''

	image = '''vn_edm1&4_np_newranger_20160801'''

[[module]]
path='email_modules/cover/02'

color='''white'''
title='''Giới thiệu khách hàng và nhận ngay quà tặng'''
copy='''Quý vị có người thân và bạn bè đang có dự định mua xe Ford? Hãy giới thiệu họ với chúng tôi bằng cách điền vào "phiếu giới thiệu khách hàng tiềm năng" trên trang www.ford.com.vn, vào mục chủ xe, và quý vị có thể nhận ngay quà tặng phiếu dịch vụ trị giá đến 2 triệu đồng. Chương trình sẽ kết thúc vào ngày 31 tháng 12 năm 2017.'''
cta1_text='''XEM CHI TIẾT CHƯƠNG TRÌNH'''
cta1_url='''https://www.ford.com.vn/owner/owner-gets-owner/'''
cta1_link_name = '''member'''

[[module]] #Banner Image
path='email_modules/image/banner'
color='white'

	image='''vn_edm1_member_20171106'''
	url_link='''https://www.ford.com.vn/owner/owner-gets-owner/'''
	url_link_name='''member'''

[[module]] # Owner App Image Right
path='email_modules/custom/ownerapp_imgr'
color='black'

	title = '''Ứng dụng Chủ sở hữu xe Ford'''
	text1 = '''Với Ứng dụng Chủ sở hữu xe Ford, sử dụng một chiếc xe Ford chưa bao giờ dễ như thế.'''
	text2 = '''<ul style="margin: 20px; padding: 0;"><li>Quản lý "Danh mục bảo dưỡng"</li><li>Tìm hiểu các Ký hiệu trên Bảng điều khiển</li><li>Xem video "Giới thiệu các tính năng trên xe Ford"</li><li>Tìm Đại lý gần nhất</li></ul>'''
	cta1_text = '''IPHONE'''
	cta1_url = '''https://itunes.apple.com/vn/app/ford-owners/id990342351'''
	cta1_link_name = '''oa_iphone'''
	cta2_text = '''ANDROID'''
	cta2_url = '''https://play.google.com/store/apps/details?id=com.ford.fordowners&hl=en'''
	cta2_link_name = '''oa_android'''
	image = '''vn_edm1a_ownerapp_20160801'''
    
 [[module]] #Banner Image
path='email_modules/image/banner'
color='white'

	image='''vn_edm5_yesservice_20171113'''
	url_link='''https://www.ford.com.vn/about/news-events/2017/chuong-trinh-khuyen-mai-dich-vu-chao-thu-2017/'''
	url_link_name='''autumn'''

[[module]]
path='email_modules/cover/02'

color='''white'''
title='''Chương trình ưu đãi lớn'''
copy='''Quý vị cần thay nhớt? Quý vị cần thay bộ lọc nhớt mới? Nhanh tay hưởng ngay ưu đãi! Từ ngày 17 tháng 11 đến ngày 31 tháng 12 năm 2017, tất cả các khách hàng của Ford được giảm 15% khi thay nhớt và bộ lọc nhớt tại các Trung tâm Dịch vụ Bảo dưỡng Ford. Hãy nhanh tay nhấp vào dưới đây để tìm hiểu thêm thông tin về chương trình tuyệt vời này.'''
cta1_text='''TÌM HIỂU THÊM'''
cta1_url='''https://www.ford.com.vn/about/news-events/2017/chuong-trinh-khuyen-mai-dich-vu-chao-thu-2017/'''
cta1_link_name = '''autumn'''

[[module]] #Cover 05
path='email_modules/cover/02'
color='''white'''

	title = '''Thay đổi thông tin cá nhân?'''
	copy = '''Bạn đừng quên cập nhật thông tin của mình tại đây để không bỏ lỡ thông tin mới nhất từ Ford Việt Nam.'''
	cta1_text = '''CẬP NHẬT NGAY'''
	cta1_url = '''https://www.ford.com.vn/#/overlay/content/ford/vn/vi_vn/site-wide-content/overlays/form-overlay/login'''
	cta1_link_name = '''anything_changed'''
	icon = '''vn_edm2_ownerprofile_20160801'''

[[module]] #VN Social
path='email_modules/footer/vn/social'
color='white'

[[module]] #Footer Online
path='email_modules/footer/online'
color='white'

	copy='''Nhấp chuột <a href="<%unsubscribe_link_text%>" style="color:#91a4b1; text-decoration:underline">tại đây</a> nếu bạn muốn ngừng nhận thư từ Ford<br />Bản quyền © Công ty TNHH Ford Việt Nam <br /><br />Nếu bạn không xem đươc e-mail này, <a href="<%syslink_message_read url='/public/read_message.jsp'%>" style="color:#91a4b1; text-decoration:underline"><br /> xin nhấp chuột tại đây để xem phiên bản trên web</a>'''

+++