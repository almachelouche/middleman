+++
markets = ["vn"]
title = '''VN Repurchase 008 All'''
draft = true

[[module]]
path='email_modules/preheader'
color='''nothing'''

preheader = '''Xem ngay giá xe Ford mới đặc biệt hấp dẫn. Thêm nhiều lựa chọn hơn cho bạn.'''

[[module]] #Header Logo
path='email_modules/header/logo'
color='white'

	image = '''white'''
	url_link = '''https://www.ford.com.vn/'''

[[module]] #Cover 07
path='email_modules/cover/02'
color='''white'''

	title = '''Thêm nhiều lựa chọn hơn cho bạn'''
	copy = '''Xin chào <%${user.CustomAttribute['Title']}%> <%${user['FirstName']}%><br /><br />Focus Trend Mới được trang bị động cơ EcoBoost 1.5L và Hộp số Tự động 6 cấp cho sức mạnh tối đa với lượng xăng tối thiểu. Sao phải băn khoăn khi bạn có cả 2: sức mạnh và công nghệ vượt trội với một mức giá không thể hấp dẫn hơn: 699 triệu đồng. Tặng ngay phone 7 cho 100 khách hàng đầu tiên.'''
	cta1_text = '''TÌM HIỂU THÊM'''
	cta1_url = '''https://www.ford.com.vn/cars/focus/compare-models/'''
	cta1_link_name = '''focus_trend'''

	[[module]] #Banner Image No Link
path = '''email_modules/image/banner_nolink'''
color = '''white'''

	image = '''vn_edm5_focustrend_20161229''' 

[[module]]
path='email_modules/cover/02'

color='''white'''
title='''Xuân này bạn đón Lộc gì cùng Ford?'''
copy='''Còn gì thú vị hơn lái một chiếc Ford Mới đón Lộc Xuân. Giá xe cực hấp dẫn chỉ từ 536 triệu đồng.'''
cta1_text='''TÌM HIỂU THÊM '''
cta1_url='''https://www.ford.com.vn/promotion-corner/2016/hot-deal-1/'''
cta1_link_name = '''retail_campaign'''

 [[module]] #Banner Image No Link
path = '''email_modules/image/banner_nolink'''
color = '''white'''

	image = '''vn_edm5_retailcampaign_20161229''' 

[[module]] #Split 03
path='email_modules/split/03'
color='fordblue'

	title = '''Tặng Voucher 3.000.000 VNĐ thay lời cảm ơn'''
	copy = '''Sự tin tưởng và yêu mến thương hiệu Ford của Quý khách hàng là món quà vô giá đối với chúng tôi. Thế nên chúng tôi xin gửi tặng voucher 3.000.000 đồng cho mỗi xe Quý vị mua thêm thay cho lời cảm ơn chân thành từ Ford Việt Nam khi Quý vị tiếp tục đồng hành cùng chúng tôi.'''
	cta1_text = '''TÌM HIỂU THÊM'''
	cta1_url = '''https://www.ford.com.vn/owner/vehicle-support/incentives/'''
	cta1_link_name = '''loyalty_offer'''
	cta1_icon = '''more'''
	image = '''vn_edm5_3millionvnd_20160801'''

[[module]] #Cover 05
path='email_modules/cover/02'
color='''white'''

	title = '''Thay đổi thông tin cá nhân?'''
	copy = '''Quý vị đừng quên cập nhật thông tin của mình tại đây để không bỏ lỡ thông tin mới nhất từ Ford Việt Nam.'''
	cta1_text = '''CẬP NHẬT NGAY'''
	cta1_url = '''https://www.ford.com.vn/#/overlay/content/ford/vn/vi_vn/site-wide-content/overlays/form-overlay/login'''
	cta1_link_name = '''anything_changed'''
	icon = '''vn_edm2_ownerprofile_20160801'''

[[module]] #VN Social
path='email_modules/footer/vn/social'
color='white'

[[module]] #VN Online
path='email_modules/footer/vn/online'
color='white'


+++