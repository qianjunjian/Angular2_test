git �ύ��������
1.git add <filename>
  git add *
2.���� git �����������̵ĵ�һ����ʹ������������ʵ���ύ�Ķ���
  git commit -m "�����ύ��Ϣ"
3.��ĸĶ������Ѿ��ڱ��زֿ�� HEAD ���ˡ�ִ�����������Խ���Щ�Ķ��ύ��Զ�˲ֿ⣺
  git push origin master
  ���԰� master ��������Ҫ���͵��κη�֧��

����㻹û�п�¡���вֿ⣬��������Ĳֿ����ӵ�ĳ��Զ�̷������������ʹ������������ӣ�
git remote add origin git@github.com:qianjunjian/Angular2_test.git
�������ܹ�����ĸĶ����͵�����ӵķ�������ȥ�ˡ�

��֧
1.����һ������"feature_x"�ķ�֧�����л���ȥ��
  git checkout -b feature_x
2.�л�������֧��
  git checkout master
3.�ٰ��½��ķ�֧ɾ����
  git branch -d feature_x
4.�����㽫��֧���͵�Զ�˲ֿ⣬��Ȼ�÷�֧���� ��Ϊ���������ģ�
  git push origin <branch>

������ϲ�
1.Ҫ������ı��زֿ������¸Ķ���ִ�У�
  git pull
2.Ҫ�ϲ�������֧����ĵ�ǰ��֧������ master����ִ�У�
  git merge <branch>