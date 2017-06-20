+++
markets = ["vn"]
title = '''VN Repurchase 005 All'''
draft = true

[[module]]
path='email_modules/preheader'
color='''nothing'''

preheader = '''Xem ngay giá xe Ford mới đặc biệt hấp dẫn'''

[[module]] #Header Logo
path='email_modules/header/logodesktop'
color='black'

	image = '''white'''
	url_link = '''http://www.ford.com.vn'''

[[module]] #Cover 07
path='email_modules/cover/02'
color='''white'''

	title = '''Explorer lần đầu tiên xuất hiện tại Việt Nam'''
	copy = '''Xin chào <%${user.CustomAttribute['Title']}%> <%${user['FirstName']}%><br /><br />Chiếc xe SUV cao cấp nhập khẩu từ Mỹ vừa được ra mắt tại triển lãm Vietnam Autoshow 2016. Được trang bị động cơ EcoBoost mạnh mẽ dung tích 2.3L, SYNC3 cùng khả năng off-road siêu hạng - Explorer xứng tầm một chiếc SUV nhập khẩu hạng sang. Sẵn sàng cho mọi hành trình. Luôn tiến lên phía trước.'''
	cta1_text = '''TÌM HIỂU THÊM'''
	cta1_url = '''http://www.ford.com.vn/suvs/explorer/'''
	cta1_link_name = '''new_explorer'''

	[[module]] #Banner Image No Link
path = '''email_modules/image/banner_nolink'''
color = '''white'''

	image = '''vn_edm5_newexplorer_20160928''' 

[[module]]
path='email_modules/cover/02'

color='''white'''
title='''Nói "YES!" và nhận ưu đãi khủng khi mua xe Ford mới!'''
copy='''Hãy chớp lấy cơ hội mua sắm cuối năm với mức giá cực hấp dẫn. Bạn hoàn toàn có thể lái một em Ford mới về nhà với mức giá chỉ từ 536 triệu đồng.'''
cta1_text='''TÌM HIỂU THÊM'''
cta1_url='''http://www.ford.com.vn/promotion-corner/2016/hot-deal-1/'''
cta1_link_name = '''yes'''

[[module]] #Custom 3 Column Car
path='email_modules/custom/3column_car'
color='white'

	icon1 = '''vn_edm6_3vehicle1_20160801'''
	icon2 = '''vn_edm6_3vehicle2_20160801'''
	icon3 = '''vn_edm6_3vehicle3_20160801'''
	cta1_text = '''<span style="font-size:15px;">KHÁM PHÁ FOCUS</span>'''
	cta1_url = '''http://www.ford.com.vn/cars/focus/'''
	cta1_link_name = '''focus'''
	cta2_text = '''<span style="font-size:15px;">KHÁM PHÁ ECOSPORT</span>'''
	cta2_url = '''http://www.ford.com.vn/suvs/ecosport/'''
	cta2_link_name = '''ecosport'''
	cta3_text = '''<span style="font-size:15px;">KHÁM PHÁ FIESTA</span>'''
	cta3_url = '''http://www.ford.com.vn/cars/fiesta/'''
	cta3_link_name = '''fiesta'''
	cta1_icon = '''more''' 

[[module]] #Split 03
path='email_modules/split/03'
color='fordblue'

	title = '''Tặng Voucher 3.000.000 VNĐ thay lời cảm ơn'''
	copy = '''Sự tin tưởng và yêu mến thương hiệu Ford của Quý khách hàng là món quà vô giá đối với chúng tôi. Thế nên chúng tôi xin gửi tặng voucher 3.000.000 đồng cho mỗi xe Quý vị mua thêm thay cho lời cảm ơn chân thành từ Ford Việt Nam khi Quý vị tiếp tục đồng hành cùng chúng tôi.'''
	cta1_text = '''TÌM HIỂU THÊM'''
	cta1_url = '''http://www.ford.com.vn/owners/driving-tips/incentives-ford'''
	cta1_link_name = '''special_offer'''
	cta1_icon = '''more'''
	image = '''vn_edm5_3millionvnd_20160801'''

[[module]] #Cover 05
path='email_modules/cover/02'
color='''white'''

	title = '''Thay đổi thông tin cá nhân?'''
	copy = '''Quý vị đừng quên cập nhật thông tin của mình tại đây để không bỏ lỡ thông tin mới nhất từ Ford Việt Nam.'''
	cta1_text = '''CẬP NHẬT NGAY'''
	cta1_url = '''https://www.ford.com.vn/owner/login'''
	cta1_link_name = '''anything_changed'''
	icon = '''vn_edm2_ownerprofile_20160801'''

[[module]] #VN Social
path='email_modules/footer/vn/social'
color='white'

[[module]] #VN Online
path='email_modules/footer/vn/online'
color='white'


+++