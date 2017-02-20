+++
markets = ["vn"]
title = '''VN Service Reminder First 005 All'''

[[module]]
path='email_modules/preheader'
color='''nothing'''

preheader = '''Đặt lịch thật dễ dàng. Quý vị hãy tìm hiểu và đặt lịch làm dịch vụ ngay hôm nay.'''

[[module]] #Header Logo
path='email_modules/header/logo'
color='white'

  image = '''white'''
  url_link = '''http://www.ford.com.vn'''

[[module]] #Cover 05
path='email_modules/cover/02'
color='''white'''

  title = '''Ford giới thiệu Dịch vụ Bảo Dưỡng Nhanh'''
  copy = '''Xin chào <%${user.CustomAttribute['Title']}%> <%${user['FirstName']}%><br /><br />Chúng tôi xin thông báo chiếc xe <%${user.CustomAttribute['Model']}%> của bạn đã đến hạn làm Bảo dưỡng 10.000km. Đây là đợt bảo dưỡng đầu tiên nằm trong lịch bảo dưỡng định kỳ nhằm đảm bảo chiếc xe của bạn luôn vận hành trong điều kiện tốt nhất.<br /><br />Bạn không có nhiều thời gian? Đừng lo lắng. Hãy đặt lịch làm bảo dưỡng trên website của đại lý Ford ủy quyền, Dịch vụ Bảo dưỡng Nhanh của Ford sẽ đảm bảo hoàn tất công việc chỉ trong 60 phút.<br /><br />Ngoài ra, bạn sẽ được giảm 10% giá phụ tùng bảo dưỡng đến hết tháng 12.'''
  cta1_text = '''ĐẶT LỊCH LÀM BẢO DƯỠNG'''
  cta1_url = '''http://www.ford.com.vn/owners/service/express-service'''
  cta1_link_name = '''express_service'''
  icon = '''vn_edm2_svc_wrench_20160801'''

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

[[module]]
path='email_modules/split/04'
color='green'

title='''Ưu đãi đặc biệt cuối năm'''
copy='''Chi phí hợp lý tiết kiệm tới 25% có ngay 2 lần thay  lọc dầu (nhớt) hoặc  thay dầu (nhớt) hoặc  20% cho Bảo dưỡng Định kỳ trọn gói SSP-Midlife so với bảo dưỡng thông thường. Chương trình chỉ dành cho 550 khách hàng đầu tiên cho đến hết ngày 30/12/2016, chương trình ưu đãi có thể kết thúc trước thời hạn.'''
cta1_text='''TÌM KIẾM ĐẠI LÝ'''
cta1_url='''http://www.ford.com.vn/locate-a-dealer/'''
cta1_link_name = '''find_dealer'''
cta1_icon='''more'''
image='''vn_edm2_savingupto25%_20161122'''

[[module]] #Cover 05
path='email_modules/cover/02'
color='''white'''

  title = '''AN TÂM HƠN VỚI "BẢO HÀNH MỞ RỘNG"'''
  copy = '''Sản phẩm "Bảo Hành mở rộng" sẽ giúp bạn yên tâm tận hưởng cùng chiếc xe của mình, không còn phải lo chi phí sửa chữa, thay thế kể cả khi đã hết bảo hành tiêu chuẩn.<br /><br />Thời gian bảo hành được mở rộng thêm tối đa 2 năm / 40 000 KM tùy điều kiện nào đến trước ngay khi hết bảo hành tiêu chuẩn. Ngoài ra quyền bảo hành mở rộng được phép chuyển nhượng sẽ làm tăng giá trị bán lại chiếc xe của bạn.'''
  cta1_text = '''BẢO VỆ XẾ YÊU'''
  cta1_url = '''http://www.ford.com.vn/owners/solutions/extendedwarranty'''
  cta1_link_name = '''extended_warranty'''
  icon = '''vn_edm_extendedwarranty_20160801'''

[[module]] #Dual 01
path='email_modules/dual/01'
color='white'

  icon1 = '''vn_edm2_call_20160801'''
  title1 = '''Đặt lịch làm dịch vụ<br />ngay!<br />'''
  copy1 = '''Gọi cho đại lý <%${user.CustomAttribute['Dealer_Name']}%> của Quý vị số máy <a style="color:#2D96CD" href="tel:<%${user.CustomAttribute['Work_Phone']}%>"><%${user.CustomAttribute['Work_Phone']}%></a> <br /> <a name="find_dealer" style="color:#2D96CD" href="http://www.ford.com.vn/locate-a-dealer/"><br />Tìm kiếm đại lý gần nhất</a>'''
  icon2 = '''vn_edm2_ownerprofile_20160801'''
  title2 = '''Thay đổi thông tin cá<br />nhân?'''
  copy2 = '''Quý vị đừng quên cập nhật thông tin của mình tại đây để không bỏ lỡ thông tin mới nhất từ Ford Việt Nam.'''
  cta1_text = ''''''
  cta1_url = ''''''
  cta1_link_name = ''''''
  cta2_text = '''CẬP NHẬT NGAY'''
  cta2_url = '''https://www.ford.com.vn/owner/login'''
  cta2_link_name = '''anything_changed'''

[[module]] #VN Social
path='email_modules/footer/vn/social'
color='white'

[[module]] #VN Online
path='email_modules/footer/vn/online'
color='white'

+++