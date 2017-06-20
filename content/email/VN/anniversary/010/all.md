+++
markets = ["vn"]
title = '''VN Anniversary 010 All'''
draft = true

[[module]]
path='email_modules/preheader'
color='''nothing'''

preheader = '''Bạn có tin đã 12 tháng trôi qua kể từ ngày bạn lái chiếc EcoSport mới về nhà? Chúng tôi không thể để ngày đặc biệt này trôi qua mà không gửi lời cảm ơn tới bạn, một lần nữa, vì đã chọn Ford.'''

[[module]] #Header Logo
path='email_modules/header/logo'
color='white'

	image = '''white'''
	url_link = '''http://www.ford.com.vn'''

[[module]] #Cover 01
path='email_modules/cover/01'
color='''white'''
 
	title = '''Mới như ngày hôm qua'''
	copy = '''Chào <%${user['LastName']}%><br /><br />Bạn có tin đã 12 tháng trôi qua kể từ ngày bạn lái chiếc EcoSport mới về nhà? Chúng tôi không thể để ngày đặc biệt này trôi qua mà không gửi lời cảm ơn tới bạn, một lần nữa, vì đã chọn Ford. Chúng tôi sẽ còn tiếp tục cập nhật thông tin để bạn sẽ luôn là người đầu tiên được thông báo về những ưu đãi đặc biệt và các thông tin hữu ích khác từ Ford Việt Nam. Chắc chắn là như vậy.'''

[[module]] #Banner Image No Link
path = '''email_modules/image/banner_nolink'''
color = '''white'''

	image = '''vn_edm1&4_np_ecosport_20160801'''		

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

[[module]] #Cover 05
path='email_modules/cover/02'
color='''white'''

	title = '''Thay đổi thông tin cá nhân?'''
	copy = '''Bạn đừng quên cập nhật thông tin của mình tại đây để không bỏ lỡ thông tin mới nhất từ Ford Việt Nam.'''
	cta1_text = '''CẬP NHẬT NGAY'''
	cta1_url = '''https://www.ford.com.vn/owner/login'''
	cta1_link_name = '''anthing_changed'''
	icon = '''vn_edm2_ownerprofile_20160801'''

[[module]] #VN Social
path='email_modules/footer/vn/social'
color='white'

[[module]] #Footer Online
path='email_modules/footer/online'
color='white'

	copy='''Nhấp chuột <a href="<%unsubscribe_link_text%>" style="color:#91a4b1; text-decoration:underline">tại đây</a> nếu bạn muốn ngừng nhận thư từ Ford<br />Bản quyền © Công ty TNHH Ford Việt Nam <br /><br />Nếu bạn không xem đươc e-mail này, <a href="<%syslink_message_read url='/public/read_message.jsp'%>" style="color:#91a4b1; text-decoration:underline"><br /> xin nhấp chuột tại đây để xem phiên bản trên web</a>'''

+++