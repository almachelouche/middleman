+++
markets = ["vn"]
title = '''VN Welcome Repeat 009 Transit'''

[[module]]
path='email_modules/preheader'

	preheader = '''Chẳng có gì thú vị hơn được lái một chiếc xe mới, dù đó là chiếc xe đầu tiên hay thứ 10. Thế nên chúng tôi muốn nói "Cảm ơn Bạn" vì đã tiếp tục chọn Ford.'''

[[module]] #Header Logo
path='email_modules/header/logo'
color='white'

	image = '''white'''
	url_link = '''https://www.ford.com.vn'''

[[module]] #Cover 01
path='email_modules/cover/01'
color='''white'''
 
	title = '''Xin chào <%${user['LastName']}%>,<br /><br />Hành trình vẫn tiếp diễn'''
	copy = '''Chẳng có gì thú vị hơn được lái một chiếc xe mới, dù đó là chiếc xe đầu tiên hay thứ 10. Thế nên chúng tôi muốn nói "Cảm ơn Bạn" vì đã tiếp tục chọn Ford.<br /><br />Là thành viên gia đình Ford, chúng tôi tiếp tục gửi tới bạn không chỉ những tin tức mới nhất từ Ford, mà cả những ưu đãi dành cho Khách hàng trung thành với thương hiệu Ford.<br /><br />Và đừng quên tận hưởng bên chiếc Transit của bạn!'''

	[[module]] #Banner Image No Link
path = '''email_modules/image/banner_nolink'''
color = '''white'''

	image = '''vn_edm1&4_np_transit_20160801'''

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

	title = '''Chiếc xe của bạn được bảo vệ lâu hơn và linh hoạt hơn'''
	copy = '''Bạn càng mua sớm gói Bảo hành Mở rộng, giá càng tốt. Ngoài ra bạn có rất nhiều lựa chọn linh hoạt: bảo vệ toàn bộ xe với gói An tâm hay chỉ bảo vệ hộp số và động cơ với gói Tiết kiệm trong thời gian 1 năm hay 2 năm. Chúng tôi luôn bảo vệ bạn trên mọi hành trình.'''
	cta1_text = '''BẢO VỆ XẾ YÊU'''
	cta1_url = '''https://www.ford.com.vn/owner/warranty/extended-warranty/'''
	cta1_link_name = '''extended_warranty'''
	icon = '''vn_edm_extendedwarranty_20160801'''

[[module]] #Banner Image
path='email_modules/image/banner'
color='white'

	image='''vn_edm1_autumn_20171013'''
	url_link='''https://www.ford.com.vn/about/news-events/2017/chuong-trinh-khuyen-mai-dich-vu-chao-thu-2017/'''
	url_link_name='''autumn'''

[[module]]
path='email_modules/cover/02'

color='''white'''
title='''Chương trình ưu đãi lớn'''
copy='''Quý vị cần thay nhớt? Quý vị cần thay bộ lọc nhớt mới? Nhanh tay hưởng ngay ưu đãi! Từ ngày 1 tháng 10 đến ngày 14 tháng 11 năm 2017, tất cả các khách hàng của Ford sẽ được giảm 15% trên giá bán lẻ của phụ tùng dầu (nhớt) và lọc dầu (nhớt) khi làm bảo dưỡng chính hãng tại các Trung tâm Dịch vụ Ford. Hãy nhanh tay tìm hiểu thêm thông tin về chương trình tuyệt vời này.'''
cta1_text='''TÌM HIỂU THÊM'''
cta1_url='''https://www.ford.com.vn/about/news-events/2017/chuong-trinh-khuyen-mai-dich-vu-chao-thu-2017/'''
cta1_link_name = '''autumn'''

[[module]] #VN Social
path='email_modules/footer/vn/social'
color='white'

[[module]] #Footer Online
path='email_modules/footer/online'
color='white'

	copy='''Nhấp chuột <a href="<%unsubscribe_link_text%>" style="color:#91a4b1; text-decoration:underline">tại đây</a> nếu bạn muốn ngừng nhận thư từ Ford<br />Bản quyền © Công ty TNHH Ford Việt Nam <br /><br />Nếu bạn không xem đươc e-mail này, <a href="<%syslink_message_read url='/public/read_message.jsp'%>" style="color:#91a4b1; text-decoration:underline"><br /> xin nhấp chuột tại đây để xem phiên bản trên web</a>'''


+++