һ��conf/  #����
	1.global.ini  #��������������ã��������ַ����Ӧ������ַ����Ӧ�ں�����
	2.logggin.conf  #��־���ã���־�����ʽ����־��ʽ

����driver/  #���������
	1.chromedriver.exe  #�ȸ����������
	2.geckodriver.exe  #������������
	3.IEDriverServer.exe  #IE���������
	4.msedgedriver.exe  #edge���������

������־/  #��־�ļ�����conf/logggin.conf�ļ�����
	1.service.log 
	2.today.log
	3.max1G.log
	
�ġ�modules/  #������
	1 mains/  #��Ҫ�ļ�
  		1.browser.py  #�������ʼ������ز���
  		2.load_ini.py  #����conf/global.ini�����ļ�
  		3.log.py  #������־���ò�ʵ����
  		4.myunit.py  #���������
		5.sendemail.py  #������²��Ա��沢�����ʼ�
		6.report.py  #�����µı���Ŀ¼�Ͳ������µı���Ŀ¼
		7.suite.py  #�����µĲ���suite��run����suite
 	2 yancloud/  #����ƽ̨ϵͳ��ʾ
  		1.login/  ��½ģ����ʾ	
			1.element_login.py  #ҳ��Ԫ����ʾ
			2.login_procs.py  #����������ʾ
			3.login_test.py  #����������ʾ
  		2.update/  ����ģ����ʾ
			1.element_update.py  #ҳ��Ԫ����ʾ
			2.update_procs.py  #����������ʾ
			3.update_test.py  #����������ʾ

 	3 jd/  #�����̳�ϵͳ��ʾ
  		1.��½ģ��
			1.ҳ��Ԫ��
			2.��������
			3.��������
  		2.����ģ��
			1.ҳ��Ԫ��
			2.��������
			3.��������
	������

	4.run_yancloud_test.py  #����ƽ̨ϵͳִ���ļ�
	5.����			#�����̳�ϵͳִ���ļ�

�塢package/  #������������������

����report/  #���Ա��汣��Ŀ¼

�ߡ�run_test.py  #���Խű�ִ������ļ�

�ˡ�README.rst  #�����ļ�

