+++
markets = ["vn"]
title = '''VN Welcome First 005 Transit'''
draft = true

[[module]]
path='email_modules/preheader'

	preheader = '''Có lẽ không có gì thú vị hơn khi được ngồi lái một chiếc xe mới. Và chúng tôi muốn nói lời cảm ơn bạn đã lựa chọn Ford.'''


[[module]] #Header Logo
path='email_modules/header/logo'
color='white'

	image = '''white'''
	url_link = '''http://www.ford.com.vn'''

[[module]] #Cover 01
path='email_modules/cover/01'
color='''white'''
 
	title = '''Xin chào <%${user['LastName']}%><br /><br />Bạn có thấy tuyệt vời khi ngồi sau vô lăng?'''
	copy = '''Có lẽ không có gì thú vị hơn khi được ngồi lái một chiếc xe mới. Và chúng tôi muốn nói lời cảm ơn bạn đã lựa chọn Ford.<br /><br />Là thành viên gia đình Ford, bạn sẽ nhận được những tin tức mới nhất từ Ford và cả những ưu đãi mà chúng tôi tin chắc bạn sẽ vui lòng đón nhận.<br /><br />Và đừng quên tận hưởng bên chiếc Transit mới của mình nhé!'''

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

[[module]] #Cover 01
path='email_modules/cover/01'
color='slatescreen'

	title = '''Hỏi đáp'''
	copy = '''Hỏi: Tại sao hộp số PowerShift phát ra tiếng kêu khi chuyển số. Tiếng kêu này có bình thường không?<br /><br />Đáp: Tiếng kêu đó bình thường vì hộp số PowerShift không phải là hộp số tự động truyền thống mà đó là hộp số được trang bị ly hợp kép...<br /><br />Hỏi: ESC dùng để làm gì?<br /><br />Đáp: ESC (Electronic Stability Control) giúp kiểm soát các hoạt động của xe và tự động điều chỉnh công suất của động cơ hoặc bổ sung thêm lực phanh...<br /><br />Hỏi: Tôi có thể liên hệ với ai nếu cần thêm trợ giúp?<br /><br />Đáp: Nếu Bạn có yêu cầu trợ giúp về kỹ thuật hay các vấn đề khác liên quan đến Ford, hãy gọi đường dây nóng <a href="tel:1800588888" style="text-decoration:none; color:#FFFFFF"><span style="color:#FFFFFF"><font color="#FFFFFF"> 1800-588888 </font></span></a> của Trung tâm Quan Hệ Khách hàng. Hoặc bạn có thể...'''
	cta1_text = '''Xem thêm'''
	cta1_url = '''https://www.facebook.com/notes/ford-việt-nam/một-số-câu-hỏi-thường-gặp-liên-quan-đến-ford-và-các-sản-phẩm-của-ford/917755158249573'''
	cta1_link_name = '''qa'''
	cta1_icon = '''more'''

[[module]] #Split 03
path='email_modules/split/03'
color='white'

	title = '''Tiết kiệm chi phí bảo dưỡng xe'''
	copy = '''Gói "Bảo Dưỡng Định kỳ Trọn gói – SSP" giúp tiết kiệm chi phí lên tới 14% so với làm bảo dưỡng thông thường. Không những thế, trong suốt thời gian tối đa 2 năm khi sử dụng gói SSP, bạn không phải lo lắng tăng giá phụ tùng hay nhân công do lạm phát. Toàn bộ quy trình bảo dưỡng được thực hiện bởi đội ngũ Kỹ thuật viên chuyên nghiệp tại các Đại lý Ủy quyền của Ford Việt Nam.'''
	cta1_text = '''TÌM HIỂU THÊM'''
	cta1_url = '''http://www.ford.com.vn/owners/solutions/ssp'''
	cta1_link_name = '''ssp'''
	cta1_icon = '''more'''
	image = '''vn_edm1a_14off_20160801'''

[[module]] #Split 04
path='email_modules/split/04'
color='fordblue'

	title = '''Không dùng hàng thay thế'''
	copy = '''Để tránh gây ảnh hưởng xấu đến độ bền và hiệu suất của xe, bạn hãy chọn sử dụng 100% phụ tùng chính hãng Ford. Những phụ tùng chính hãng được chúng tôi thiết kế và sản xuất phù hợp với chính chiếc xe Ford của bạn, giúp đảm bảo an toàn cho bạn và gia đình.'''
	cta1_text = '''TÌM HIỂU THÊM'''
	cta1_url = '''http://www.ford.com.vn/owners/service/genuine-parts'''
	cta1_link_name = '''genuine_parts'''
	cta1_icon = '''more'''
	image = '''vn_edm1a_be100ford_20160801'''

[[module]] #Cover 05
path='email_modules/cover/02'
color='''white'''

	title = '''Kỹ năng lái xe an toàn và tiết kiệm nhiên liệu'''
	copy = '''Hãy xem và tải Cẩm nang "Kỹ năng lái xe an toàn và tiết kiệm nhiên liệu" của Ford: từ kỹ năng lái xe trong điều kiện thời tiết xấu đến cách sử dụng công nghệ tiên tiến trên xe.'''
	cta1_text = '''TÌM HIỂU THÊM'''
	cta1_url = '''http://www.ford.com.vn/servlet/BlobServer/VN_Driving_Tips_Booklet.pdf?blobtable=DFYBlob&blobheader=application/pdf&blobwhere=1249236115572&blobcol=urlblob&blobkey=id'''
	cta1_link_name = '''driving_skills'''
	icon = '''vn_edm1a_drivingskill_20160801'''

[[module]] #VN Social
path='email_modules/footer/vn/social'
color='white'

[[module]] #Footer Online
path='email_modules/footer/online'
color='white'

	copy='''Nhấp chuột <a href="<%unsubscribe_link_text%>" style="color:#91a4b1; text-decoration:underline">tại đây</a> nếu bạn muốn ngừng nhận thư từ Ford<br />Bản quyền © Công ty TNHH Ford Việt Nam <br /><br />Nếu bạn không xem đươc e-mail này, <a href="<%syslink_message_read url='/public/read_message.jsp'%>" style="color:#91a4b1; text-decoration:underline"><br /> xin nhấp chuột tại đây để xem phiên bản trên web</a>'''



+++