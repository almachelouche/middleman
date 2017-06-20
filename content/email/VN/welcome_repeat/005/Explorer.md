+++
markets = ["vn"]
title = '''VN Welcome Repeat 005 Explorer'''
draft = true

[[module]]
path='email_modules/preheader'
color='''nothing'''

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
	copy = '''Chẳng có gì thú vị hơn được lái một chiếc xe mới, dù đó là chiếc xe đầu tiên hay thứ 10. Thế nên chúng tôi muốn nói "Cảm ơn Bạn" vì đã tiếp tục chọn Ford.<br /><br />Là thành viên gia đình Ford, chúng tôi tiếp tục gửi tới bạn không chỉ những tin tức mới nhất từ Ford, mà cả những ưu đãi dành cho Khách hàng trung thành với thương hiệu Ford.<br /><br />Và đừng quên tận hưởng bên chiếc Explorer của bạn!'''
	
	[[module]] #Banner Image No Link
path = '''email_modules/image/banner_nolink'''
color = '''white'''

	image = '''vn_edm1&4_np_explorer_20170223'''
		
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

[[module]] #Split 03
path='email_modules/split/03'
color='white'

	title = '''Tiết kiệm chi phí bảo dưỡng xe'''
	copy = '''Gói "Bảo Dưỡng Định kỳ Trọn gói – SSP" giúp tiết kiệm chi phí lên tới 14% so với làm bảo dưỡng thông thường. Không những thế, trong suốt thời gian tối đa 2 năm khi sử dụng gói SSP, bạn không phải lo lắng tăng giá phụ tùng hay nhân công do lạm phát. Toàn bộ quy trình bảo dưỡng được thực hiện bởi đội ngũ Kỹ thuật viên chuyên nghiệp tại các Đại lý Ủy quyền của Ford Việt Nam.'''
	cta1_text = '''TÌM HIỂU THÊM'''
	cta1_url = '''https://www.ford.com.vn/owner/service-and-maintenance/ssp/'''
	cta1_link_name = '''ssp'''
	cta1_icon = '''more'''
	image = '''vn_edm1a_14off_20160801'''

[[module]] #Split 04
path='email_modules/split/04'
color='fordblue'

	title = '''Không dùng hàng thay thế'''
	copy = '''Để tránh gây ảnh hưởng xấu đến độ bền và hiệu suất của xe, bạn hãy chọn sử dụng 100% phụ tùng chính hãng Ford. Những phụ tùng chính hãng được chúng tôi thiết kế và sản xuất phù hợp với chính chiếc xe Ford của bạn, giúp đảm bảo an toàn cho bạn và gia đình.'''
	cta1_text = '''TÌM HIỂU THÊM'''
	cta1_url = '''https://www.ford.com.vn/owner/service-and-maintenance/genuine-ford-parts/'''
	cta1_link_name = '''genuine_parts'''
	cta1_icon = '''more'''
	image = '''vn_edm1a_be100ford_20160801'''

[[module]] #Cover 05
path='email_modules/cover/02'
color='''white'''

	title = '''AN TÂM HƠN VỚI "BẢO HÀNH MỞ RỘNG"'''
	copy = '''Sản phẩm "Bảo Hành mở rộng" sẽ giúp bạn yên tâm tận hưởng cùng chiếc xe của mình, không còn phải lo chi phí sửa chữa, thay thế kể cả khi đã hết bảo hành tiêu chuẩn.<br /><br />Thời gian bảo hành được mở rộng thêm tối đa 2 năm / 40 000 KM tùy điều kiện nào đến trước ngay khi hết bảo hành tiêu chuẩn. Ngoài ra quyền bảo hành mở rộng được phép chuyển nhượng sẽ làm tăng giá trị bán lại chiếc xe của bạn.'''
	cta1_text = '''BẢO VỆ XẾ YÊU'''
	cta1_url = '''https://www.ford.com.vn/owner/warranty/extended-warranty/'''
	cta1_link_name = '''extended_warranty'''
	icon = '''vn_edm_extendedwarranty_20160801'''

[[module]] #VN Social
path='email_modules/footer/vn/social'
color='white'

[[module]] #Footer Online
path='email_modules/footer/online'
color='white'

	copy='''Nhấp chuột <a href="<%unsubscribe_link_text%>" style="color:#91a4b1; text-decoration:underline">tại đây</a> nếu bạn muốn ngừng nhận thư từ Ford<br />Bản quyền © Công ty TNHH Ford Việt Nam <br /><br />Nếu bạn không xem đươc e-mail này, <a href="<%syslink_message_read url='/public/read_message.jsp'%>" style="color:#91a4b1; text-decoration:underline"><br /> xin nhấp chuột tại đây để xem phiên bản trên web</a>'''


+++