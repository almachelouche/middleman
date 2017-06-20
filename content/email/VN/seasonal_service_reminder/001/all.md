+++
markets = ["vn"]
title = '''VN Service Reminder Seasonal 001 All'''

[[module]]
path='email_modules/preheader'
color='''nothing'''

preheader = '''Đặt lịch làm bảo dưỡng online để được hưởng Dịch vụ Bảo dưỡng nhanh trong 60 phút.'''

[[module]] #Header Logo
path='email_modules/header/logo'
color='white'

	image = '''white'''
	url_link = '''http://www.ford.com.vn'''

[[module]] #Banner Image No Link
path = '''email_modules/image/banner_nolink'''
color = '''white'''

	image = '''vn_edm2b_expressservice_20161122'''

[[module]]
path='email_modules/cover/02'

color='''white'''
title='''Dịch vụ Bảo dưỡng nhanh trong vòng 60 phút'''
copy='''Xin chào <%${user.CustomAttribute['Title']}%> <%${user['FirstName']}%><br /><br />Xe của bạn đến kỳ làm bảo dưỡng, nhưng bạn có quá nhiều việc phải làm?
<br /><br />Ít thời gian không còn là nỗi lo lắng vì bây giờ bạn có thể đặt trước lịch làm bảo dưỡng online, khi đó bạn hoàn toàn yên tâm với Dịch vụ Bảo dưỡng nhanh của Ford. Toàn bộ công đoạn làm dịch vụ cho chiếc xe của bạn được đảm bảo hoàn thành chỉ trong 60 phút.<br /><br />Hơn nữa, bạn sẽ được hưởng 10% giảm giá phụ tùng bảo dưỡng đến hết tháng 12, 2016.'''
cta1_text='''ĐẶT LỊCH LÀM BẢO DƯỠNG'''
cta1_url='''http://www.ford.com.vn/owners/service/express-service'''
cta1_link_name = '''express_service'''

[[module]]
path='email_modules/split/04'
color='green'

title='''Quà tặng cho 2.000 khách hàng đầu tiên'''
copy='''Chúng tôi xin dành tặng cho mỗi khách hàng đến làm dịch vụ thay ắc qui hoặc má phanh hoặc lốp trong tháng 12 một chiếc ô Ford cao cấp. Quà tặng dành cho 2.000 khách hàng đầu tiên nên chương trình có thể kết thúc trước thời hạn.'''
cta1_text='''TÌM KIẾM ĐẠI LÝ'''
cta1_url='''http://www.ford.com.vn/locate-a-dealer/'''
cta1_link_name = '''find_dealer'''
cta1_icon='''more'''
image='''vn_edm2b_commodity_20161129'''

[[module]] #Custom 01
path='email_modules/custom/3columntitle3icons'
color='white'

	title = '''Tại sao nên chọn dịch vụ bảo dưỡng của Ford?'''
	icon1 = '''vn_edm2_fordsvc_b_20160801'''
	text1 = '''Trung tâm Dịch vụ bảo dưỡng Ford với những trang thiết bị được thiết kế cho đúng chiếc ô-tô của bạn.'''
	icon2 = '''vn_edm2_fordsvc_a_20160801'''
	text2 = '''Bảo dưỡng đúng kỳ hạn giúp chiếc xe của Quý vị luôn ở chế độ vận hành tốt nhất.'''
	icon3 = '''vn_edm2_fordsvc_c_20160801'''
	text3 = '''Hồ sơ bảo dưỡng định kỳ của xe sẽ giúp tăng thêm giá trị bán lại cho chính chiếc xe đó.'''

[[module]] #Banner Image No Link
path = '''email_modules/image/banner_nolink'''
color = '''white'''

	image = '''vn_edm2_svcreminder_20160801'''

[[module]] #VN Social
path='email_modules/footer/vn/social'
color='white'

[[module]] #VN Online
path='email_modules/footer/vn/online'
color='white'

+++