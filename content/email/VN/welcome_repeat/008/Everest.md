+++
markets = ["vn"]
title = '''VN Welcome Repeat 008 Everest'''

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
	copy = '''Chẳng có gì thú vị hơn được lái một chiếc xe mới, dù đó là chiếc xe đầu tiên hay thứ 10. Thế nên chúng tôi muốn nói "Cảm ơn Bạn" vì đã tiếp tục chọn Ford.<br /><br />Là thành viên gia đình Ford, chúng tôi tiếp tục gửi tới bạn không chỉ những tin tức mới nhất từ Ford, mà cả những ưu đãi dành cho Khách hàng trung thành với thương hiệu Ford.<br /><br />Và đừng quên tận hưởng bên chiếc Everest của bạn!'''

	[[module]] #Banner Image No Link
path = '''email_modules/image/banner_nolink'''
color = '''white'''

	image = '''vn_edm1&4_np_everest_20160801'''

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

 [[module]]
path='email_modules/split/07'
color='white'

title='''Cho chiếc xe của bạn thêm nổi bật'''
copy='''Hãy trang bị cho chiếc xe của bạn phụ kiện chính hãng từ Ford. Các phụ kiện của Ford được thiết kế theo tiêu chuẩn chất lượng cao và chuyên biệt, sẵn sàng nâng cấp chiếc xe của bạn lên tầm cao mới.'''
cta1_text='''XEM CHI TIẾT PHỤ KIỆN'''
cta1_url='''https://www.ford.com.vn/suvs/everest/accessories/'''
cta1_link_name = '''acc_everest'''
image='''vn_edm1a_Everest_20170324'''

[[module]] #Cover 05
path='email_modules/cover/02'
color='''white'''

	title = '''Chiếc xe của bạn được bảo vệ lâu hơn và linh hoạt hơn'''
	copy = '''Bạn càng mua sớm gói Bảo hành Mở rộng, giá càng tốt. Ngoài ra bạn có rất nhiều lựa chọn linh hoạt: bảo vệ toàn bộ xe với gói An tâm hay chỉ bảo vệ hộp số và động cơ với gói Tiết kiệm trong thời gian 1 năm hay 2 năm. Chúng tôi luôn bảo vệ bạn trên mọi hành trình.'''
	cta1_text = '''BẢO VỆ XẾ YÊU'''
	cta1_url = '''https://www.ford.com.vn/owner/warranty/extended-warranty/'''
	cta1_link_name = '''extended_warranty'''
	icon = '''vn_edm_extendedwarranty_20160801'''

[[module]] #Split 03
path='email_modules/split/03'
color='green'

	title = '''Tiết kiệm hơn, tiện lợi hơn với sản phẩm "Bảo Dưỡng Định kì trọn gói – SSP"'''
	copy = '''Gói "Bảo Dưỡng Định kỳ Trọn gói – SSP" giúp tiết kiệm chi phí lên tới 13% so với làm bảo dưỡng thông thường. Không những thế, trong suốt thời gian tối đa 2 năm khi sử dụng gói SSP, bạn không phải lo lắng tăng giá phụ tùng hay nhân công do lạm phát. Toàn bộ quy trình bảo dưỡng được thực hiện bởi đội ngũ Kỹ thuật viên chuyên nghiệp tại các Đại lý Ủy quyền của Ford Việt Nam.'''
	cta1_text = '''TÌM HIỂU THÊM'''
	cta1_url = '''https://www.ford.com.vn/owner/service-and-maintenance/ssp/'''
	cta1_link_name = '''ssp'''
	cta1_icon = '''more'''
	image = '''vn_edm1a_13off_20170324'''

[[module]] #VN Social
path='email_modules/footer/vn/social'
color='white'

[[module]] #Footer Online
path='email_modules/footer/online'
color='white'

	copy='''Nhấp chuột <a href="<%unsubscribe_link_text%>" style="color:#91a4b1; text-decoration:underline">tại đây</a> nếu bạn muốn ngừng nhận thư từ Ford<br />Bản quyền © Công ty TNHH Ford Việt Nam <br /><br />Nếu bạn không xem đươc e-mail này, <a href="<%syslink_message_read url='/public/read_message.jsp'%>" style="color:#91a4b1; text-decoration:underline"><br /> xin nhấp chuột tại đây để xem phiên bản trên web</a>'''


+++