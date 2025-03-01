# Gitʹ��˵��

    ���ԣ�http://blog.csdn.net/javafreely/article/details/18217273

Git �ǵ�ǰ�����еİ汾���Ƴ���֮һ���ı������� Git ��һЩ�����÷�:

- ���� git �ֿ� ��ʼ�� git �ֿ� 

> mkdir project  # ������ĿĿ¼ 

> cd project  # ���뵽��ĿĿ¼ 

> git init  # ��ʼ�� git �ֿ⡣��������ڵ�ǰĿ¼�½�һ�� .git Ŀ¼�����ڴ洢 git �ֿ�������Ϣ 

- ��ʼ���ύ 

> touch README 

> git add .  # ����ǰĿ¼��ӵ� git �ֿ��У� ʹ�� git add -A ����������иĶ����ĵ� 

> git commit  -m  "Initial commit" 

> git remote add origin  git @github.com:lugir /repo.git  # ���òֿ� 

- �޲��ύ���޲����һ�ε��ύ���������µ��ύ�� 

> git commit  --amend  -m  "commit message." 

- �ύ��ͻʱ���Ժϲ��������� 

> git pull  # ��ȡԶ�̰汾���ύ�뱾���ύ���кϲ� 

> git push  # �ύ 

- ʹ�ñ��˵Ĳֿ� 

> git clone http: //path /to /git.git  # clone �����ݻ���ڵ�ǰĿ¼�µ���Ŀ¼ 

- ������ӱ��ػش����ֿ� 

> git push  -u origin master 

- ʹ�� `git status` �鿴�ļ�״̬ 

> git status 

- �鿴�ύ��־ 

> git log  # �鿴�ύ��Ϣ 

> git log  --pretty=oneline  # ������ĵ�����ʽ��ʾ�ύ��Ϣ 

- Git ��֧ 

> git branch  # �鿴��֧ 

> git branch  6.x- 1.x  # ��ӷ�֧ 6.x-1.x 

> git branch checkout master  # �л�������֧ 

> git branch  -d  6.x- 1.x  # ɾ����֧ 6.x-1.x 

> git push origin :branchname  # ɾ��Զ�˷�֧ 

- Git ��ǩ 

> git tag  # �鿴��֧ 

> git tag  6.x- 1.0  # ��ӱ�ǩ 6.x-1.0 

> git show  6.x- 1.0  # �鿴��ǩ 6.x-1.0 ����Ϣ 

> git tag  -a  6.x- 1.0 965e066  # Ϊ֮ǰ�ύ����Ϣ��¼ 965e066 ���ϱ�ǩ 

> git push  --tags  # �ύʱ���ϱ�ǩ��Ϣ 

> git push origin : /refs /tags /tagname  # ɾ��Զ�˱�ǩ 

- �� git �ֿ��е�����Ŀ 

> git archive  --format  tar  --output  /path /to /file.tar master  # �� master �� tar ��ʽ�����ָ���ļ� 

**ʹ�� Git ��һЩ��������**

��Ҫ`commit/`�ύ`patch`ʱ�� 

- ʹ�� `git diff --check` �����β��û�ж���Ŀհ�

- ÿ�� `commit` ֻ��һ�����顣���һ���ĵ��ж�������ʹ�� `git add --patch` ֻѡ���ĵ��еĲ��ֱ������ `stage`

- д��� `commit message`