
+++
markets = ["sk-ford"]
title = '''SK Ford Service Reminder First 001'''

[[module]]
path='email_modules/preheader'
color='''nothing'''

   preheader='''저희 포드는 새로운 가족이 되신 고객님께 다시 한 번 깊은 감사의 마음을 전합니다'''

[[module]] #Header Logo
path='email_modules/header/logo'
color='white'

  image = '''white'''
  url_link = '''https://www.ford-korea.com'''

[[module]]
path='email_modules/cover/02'

color='''white'''
icon='''ph_edm2_svc_wrench_20160801'''
title='''Time files when you're having fun'''
copy='''Hello <%${user['FirstName']}%><br /><br />Here’s a quick reminder that your new <%${user.CustomAttribute['Model']}%> is due for its first service. Our expert engineers will ensure it is running at its absolute best.<br /><br />When you book your first service appointment, you’ll receive a free 30-point inspection and a Vehicle Report Card that helps you track your Ford’s health status. 
<br /><br />It's important to book your service today. Just click below to contact <%${user.CustomAttribute['Dealer_Name']}%> (during business hours) or to find your nearest dealer.'''
cta1_text='''CALL <%${user.CustomAttribute['Work_Phone']}%>'''
cta1_url='''tel:<%${user.CustomAttribute['Home_Phone']}%>'''
cta2_text='''FIND A DEALER'''
cta2_url='''https://www.ford.com.ph/locate-a-dealer/'''
cta2_link_name='''find_dealer'''

[[module]] #Custom 01
path='email_modules/custom/3columntitle3icons'
color='white'

  title = '''<span style="font-family:Tahoma, Verdana, Sans-serif">ทำไมต้องศูนย์บริการฟอร์ด?</span>'''
  icon1 = '''ico_2e_fordsvc_a'''
  text1 = '''<span style="font-family:Tahoma, Verdana, Sans-serif"><span style="white-space:nowrap;">มั่นใจอะไหล่แท้ฟอร์ด</span> 
                    <span style="white-space:nowrap;">100%</span>  
                    <span style="white-space:nowrap;">พร้อมการบำรุงรักษารถยนต์</span>
                    <span style="white-space:nowrap;">อย่างมีประสิทธิภาพ</span>เพื่อ
                    <span style="white-space:nowrap;">สมรรถนะสูงสุดของรถคุณ</span></span>'''
  icon2 = '''ico_2e_fordsvc_b'''
  text2 = '''<span style="font-family:Tahoma, Verdana, Sans-serif"><span style="white-space:nowrap;">ตรวจเช็คด้วยช่างเทคนิค</span> 
                    <span style="white-space:nowrap;">ฟอร์ดที่ผ่านการอบรม</span> 
                    <span style="white-space:nowrap;">รวมถึงเครื่องมือและอุปกรณ์</span> 
                    <span style="white-space:nowrap;">ทันสมัยที่ออกแบบมาเพื่อ</span>
                    <span style="white-space:nowrap;">รถฟอร์ดโดยเฉพาะ</span></span>'''
  icon3 = '''ico_2e_fordsvc_c_th'''
  text3 = '''<span style="font-family:Tahoma, Verdana, Sans-serif"><span style="white-space:nowrap;">เก็บบันทึกสถิติรถฟอร์ด</span> 
                    <span style="white-space:nowrap;">ของคุณอย่างเป็นระบบ</span> 
                    <span style="white-space:nowrap;">เพื่อเพิ่มมูลค่าในการขายต่อ</span></span>'''

[[module]] #Banner Image No Link
path = '''email_modules/image/banner_nolink'''
color = '''white'''

  image = '''th_edm2_whyfordsvc_20161115'''


[[module]] #Cover 01
path='email_modules/cover/01'
color='''fordblue'''
 
  title = '''<span style="font-size:20px;font-family:'Nanum Gothic',Malgun Gothic,sans-serif"><b>24시간 긴급출동 서비스</b></span>'''
  copy = '''<span style="font-size:16px;font-family:'Nanum-Gothic',Malgun Gothic,sans-serif">포드 긴급출동 서비스는 365일 24시간 이용 가능합니다.<br />운전 중 예상치 못한 긴급 상황이 발생하면, <a href="tel:080-300-3673" name="tel" style="text-decoration:none; color:#FFFFFF;">080-300-3673</a>으로 연락주세요.</span>'''
  
[[module]]
path='email_modules/singles/ctablock'
color='''fordblue'''
	
	cta1_text = '''<span style="font-family:'Nanum Gothic',Malgun Gothic,sans-serif">더 알아보기</span>'''
	cta1_url = '''https://www.ford-korea.com/owner/emergency/'''
	cta1_link_name = '''era'''
    
[[module]] #Split 02
path='email_modules/split/02'
color='green'

  title = '''<span style="font-family:'Nanum Gothic',Malgun Gothic,sans-serif;font-size:20px;"><b>포드 오너를 위한 필수 정보</b></span>'''
  copy = '''<span style="color:#FFFFFF;font-family:'Nanum Gothic',Malgun Gothic,sans-serif">포드 웹사이트에는 더 쉽게<br/>차량을 관리할 수 있도록 돕는<br/>값진 정보가 가득합니다. <br/><br/>아래의 링크를 클릭하시면<br/>고객님께 꼭 필요한 서비스 정보를<br />확인하실 수 있습니다.
	<ul style="margin: 20px; padding: 0;text-decoration:underline; color:#FFFFFF">
		<li><a href="https://www.ford-korea.com/owner/warranty/" name="warranty" style="text-decoration:underline; color:#FFFFFF;">보증 서비스</a></li>
		<li><a href="https://www.ford-korea.com/owner/maintenance/" name="vehicle_maintenance" style="text-decoration:underline; color:#FFFFFF;font-family:'Nanum Gothic',Malgun Gothic,sans-serif;">차량 관리</a></li>
		<li><a href="https://www.ford-korea.com/owner/genuine-service/" name="genuine_service" style="text-decoration:underline; color:#FFFFFF;font-family:'Nanum Gothic',Malgun Gothic,sans-serif;">전문가의 공인 서비스 </a></li>
		<li><a href="https://www.ford-korea.com/owner/recall-guidance/" name="recall_guidance" style="text-decoration:underline; color:#FFFFFF;font-family:'Nanum Gothic',Malgun Gothic,sans-serif;">리콜 안내</a></li>
	</ul></span>'''
  image = '''sk_ford_edm1_greenmodule_20170419'''

[[module]] #Dual 01
path='email_modules/dual/01'
color='white'

  icon1 = '''ph_edm2_call_20160801'''
  title1 = '''<span style="font-size:20px;font-family:'Nanum Gothic',Malgun Gothic,sans-serif">고객센터 문의하기</span>'''
  copy1 = '''<span style="font-size:15px;font-family:'Nanum Gothic',Malgun Gothic,sans-serif">도움이나 의견이 필요하시다면 <br/><a href="tel:1600-6003" name="tel" style="text-decoration:none; color:#2d96cd;">1600-6003</a>으로 언제든 문의주세요.</span>'''
  icon2 = '''sk_ford_edm1_dealerlocator_20170419'''
  title2 = '''<span style="font-size:20px; font-family:'Nanum Gothic',Malgun Gothic,sans-serif">전시장 및 서비스 센터 찾기</span>'''
  copy2 = '''<span style="font-size:15px;font-family:Nanum Gothic,Malgun Gothic,sans-serif">가장 가까운 전시장 및<br />서비스 센터를 찾아보세요.</span>'''
  cta1_text = '''<span style="font-family:'Nanum Gothic',Malgun Gothic,sans-serif">문의하기</span>'''
  cta1_url = '''https://www.ford-korea.com/contact-us/'''
  cta1_link_name = '''contact_us'''
  cta2_text = '''<span style="font-family:Malgun Gothic,sans-serif">전시장 및 서비스 센터 찾기</span>'''
  cta2_url = '''https://www.ford-korea.com/locate-a-dealer/'''
  cta2_link_name = '''find_dealer'''

[[module]] #Footer SK Ford Social
path='email_modules/footer/sk/ford/social'
color='white'

[[module]] #Footer Disclaimer
path='email_modules/footer/disclaimer'
color='white'

text = '''<span style="font-family:'Nanum Gothic',Malgun Gothic,sans-serif"><br/>앞으로 저희가 보내드리는 이메일 수신을 위해 귀하의 주소록이나 이메일 수신 허용 목록에 <br/><span style="font-family:'Nanum Gothic',Malgun Gothic,sans-serif; text-decoration:underline; color:#ffffff;">fordnews@mail.edmasia.com</span>을 추가해주십시오.<br/><br/>본 이메일은 귀하의 요청에 따라 발송되었습니다. 이메일 수신을 원치 않으시면 <a href="<%unsubscribe_link_text%>" style="color:#91a4b1; text-decoration:underline">여기</a>를 클릭하십시오. <br />본 이메일은 발신 전용 메일로, 회신은 처리되지 않습니다. <a href="https://www.ford-korea.com/privacy/" name="privacy" style="text-decoration:underline; color:#91a4b1;">개인정보처리방침</a> <br/><br/>Copyright © 2017 Ford Sales & Service Korea Inc.<br /><br />이메일이 제대로 보이지 않는 경우, <span class="mobile-display-block"></span><a href="<%syslink_message_read url='/public/read_message.jsp'%>" style="color:#91a4b1; text-decoration:underline">여기</a>를 클릭하십시오. 웹페이지로 보실 수 있습니다.<p> </p><p> </p><p> </p></span>'''

+++
