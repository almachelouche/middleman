
+++
markets = ["sk-lincoln"]
title = '''SK Service Reminder First 001'''

[[module]]
path='email_modules/preheader'
color='''nothing'''

   preheader='''링컨과 함께하는 시작이 더욱 아름답고 편안하기를 바랍니다.'''

[[module]] #Header Logo
path='email_modules/header/logo'
color='white'

  image = '''lincoln_white'''
  url_link = '''https://www.lincoln-korea.com/'''

[[module]]
path='email_modules/cover/02'

color='''white'''
icon=''''''
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
color='''lincoln_black'''

title = '''<span style="font-size:20px;font-family:'Nanum Gothic',Malgun Gothic,sans-serif"><span style="font-weight:bold;"><span style="white-space:nowrap;">24시간 긴급출동 서비스</span></span></span>'''
  copy = '''<span style="font-family:'Nanum-Gothic',Malgun Gothic,sans-serif;letter-spacing: -1px;">
  <span style="white-space:nowrap;">링컨 긴급출동 서비스는</span>
  <span style="white-space:nowrap;"> 365일 24시간 이용 가능합니다.</span><br />
  <span style="white-space:nowrap;">운전 중 예상치 못한 긴급 상황이 발생하면,</span>
  <span style="white-space:nowrap;"><a href="tel:080-300-3673" name="tel" style="text-decoration:none; color:#FFFFFF;">080-300-3673</a>으로 연락주십시오.</span>
  </span>'''

[[module]]
path='email_modules/singles/ctablock'
color='''lincoln_black'''

	cta1_text = '''<span style="font-family:'Nanum Gothic',Malgun Gothic,sans-serif;color:#515151;"><span style="white-space:nowrap;">더 알아보기</span></span>'''
	cta1_url = '''https://www.lincoln-korea.com/parts-service/roadside-assistance/'''
	cta1_link_name = '''era'''

[[module]] #Split 02
path='email_modules/split/02'
color='lincoln_grey'

title = '''<span style="font-family:'Nanum Gothic',Malgun Gothic,sans-serif;font-size:20px;"><span style="font-weight:bold;">
<span style="white-space:nowrap;">보다 편리하게 누리는,</span><br />
<span style="white-space:nowrap;">프리미엄 서비스</span></span>'''
copy = '''<span style="font-family:'Nanum Gothic',Malgun Gothic,sans-serif;letter-spacing: -1px;">
<span style="white-space:nowrap;">오직 특별한 분만을 위한</span><br />
<span style="white-space:nowrap;">품격 있는 서비스를 제공합니다.</span><br /><br />
<span style="white-space:nowrap;">아래의 링크를 클릭하시면</span><br />
<span style="white-space:nowrap;">귀하에게 필요한 자세한 서비스 정보를</span><br />
<span style="white-space:nowrap;">확인하실 수 있습니다.</span>
<ul style="margin: 20px; padding: 0;text-decoration:underline; color:#b45f1a">
<li><a href="https://www.lincoln-korea.com/parts-service/pick-delivery/" name="pick_delivery" style="text-decoration:underline; color:#b45f1a;font-family:'Nanum Gothic',Malgun Gothic,sans-serif;"><span style="white-space:nowrap;">픽업&딜리버리 서비스</span></a></li>
<li><a href="https://www.lincoln-korea.com/genuine-parts/" name="parts_service" style="text-decoration:underline; color:#b45f1a;font-family:'Nanum Gothic',Malgun Gothic,sans-serif;"><span style="white-space:nowrap;">부품 및 서비스</span></a></li></ul></span>'''
  image = '''sk_lincoln_edm1_effortlessownership_20170427'''

[[module]] #Dual 01
path='email_modules/dual/01'
color='lincoln_white'

  icon1 = '''sk_lincoln_edm1_contact_20170510'''
  title1 = '''<span style="font-size:20px;font-family:'Nanum Gothic',Malgun Gothic,sans-serif"><span style="font-weight:bold;">
  <span style="white-space:nowrap;">기대 그 이상의 경험,</span><br />
  <span style="white-space:nowrap;">링컨 고객센터</span></span></span>'''
  copy1 = '''<span style="font-size:15px;font-family:'Nanum Gothic',Malgun Gothic,sans-serif;letter-spacing: -1px;">
  <span style="white-space:nowrap;">도움이나 의견이 필요하시면</span><br />
  <span style="white-space:nowrap;"><a href="tel:1600-6003" name="tel" style="text-decoration:none; color:#b45f1a;">1600-6003</a>으로 언제든 연락 주십시오.</span>
  </span>'''
  icon2 = '''sk_lincoln_edm1_dealerlocator_20170510'''
  title2 = '''<span style="font-size:20px;font-family:'Nanum Gothic',Malgun Gothic,sans-serif"><span style="font-weight:bold;">
  <span style="white-space:nowrap;">가까운 전시장 및</span><br />
  <span style="white-space:nowrap;">서비스센터 찾기</span>
  </span></span>'''
  copy2 = '''<span style="font-size:15px;font-family:'Nanum Gothic',Malgun Gothic,sans-serif;letter-spacing: -1px;">
  <span style="white-space:nowrap;">가장 가까운 전시장 및</span><br />
  <span style="white-space:nowrap;">서비스센터를 찾아보십시오.</span></span>'''
  cta1_text = '''<span style="font-family:'Nanum Gothic',Malgun Gothic,sans-serif"><span style="white-space:nowrap;">자세히 보기</span></span>'''
  cta1_url = '''https://www.lincoln-korea.com/contact-us/'''
  cta1_link_name = '''contact_us'''
  cta2_text = '''<span style="font-family:'Nanum Gothic',Malgun Gothic,sans-serif"><span style="white-space:nowrap;">전시장 및 서비스센터 찾기</span></span>'''
  cta2_url = '''https://www.lincoln-korea.com/dealer-locate/'''
  cta2_link_name = '''find_dealer'''

[[module]] #Footer SK Lincoln Social
path='email_modules/footer/sk/lincoln/social'
color='white'

[[module]] #Footer Disclaimer
path='email_modules/footer/lincoln_disclaimer'
color='white'

 text = '''<span style="font-family:'Nanum Gothic',Malgun Gothic,sans-serif"><br/>
 <span style="white-space:nowrap;">앞으로 저희가 보내드리는 이메일 수신을 위해 귀하의 주소록이나 이메일</span>
 <span style="white-space:nowrap;">수신 허용 목록에 <span style="font-family:'Nanum Gothic',Malgun Gothic,sans-serif; text-decoration:underline;">fordnews@mail.edmasia.com</span>을 추가해주십시오.</span><br/><br/>
본 이메일은 귀하의 요청에 따라 발송되었습니다. 이메일 수신을 원치 않으시면 <a href="<%unsubscribe_link_text%>" style="color:#FFFFFF; text-decoration:underline">여기</a>를 클릭하십시오.<br />
본 이메일은 발신 전용 메일로, 회신은 처리되지 않습니다. <a href="https://www.lincoln-korea.com/privacy/" name="privacy" style="text-decoration:underline; color:#FFFFFF;">개인정보처리방침</a><br/><br/>
 <span style="white-space:nowrap;">Copyright © 2017 Ford Sales & Service Korea Inc.</span><br /><br />
 이메일이 제대로 보이지 않는 경우, <a href="<%syslink_message_read url='/public/read_message.jsp'%>" style="color:#FFFFFF; text-decoration:underline">여기</a>를 클릭하십시오. 웹페이지로 보실 수 있습니다.
 <br /><br /></span>
 '''

+++
