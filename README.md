[����] ����רҵ���ֶ��ƽⷽ��
���Ȱ�װ�����Ѱ�
yum install -y wget && wget -O install.sh http://download.bt.cn/install/install.sh && sh install.sh

Ȼ������רҵ��
wget -O update.sh http://download.bt.cn/install/update_pro.sh && bash update.sh pro

�ҵ�·��/www/server/panel/class �ҵ��ļ�������ֱ��������common.py

��������164��
data = panelAuth().get_order_status(None)

�滻��
data = {'status' : True,'msg' : {'endtime' : 32503651199 }}

��ɺ󣬽��� /www/server/panel/data �½�һ���ļ� �ļ���Ϊ��userInfo.json ���ݿյģ������������ļ���ɾ�������½��ļ���

����������� /etc/init.d/bt restart �������� ������Ƥ����

ע�⣺��װǰ��رձ�����ҳ  ��ֹ����

���ʹ��ʧ�ܣ���ָ�����Ѱ� ����Ϊ
wget -O update.sh http://download.bt.cn/install/update.sh && bash update.sh free

�������¿��� ��Ӫ��֧������
