������ ������ � Git � GitHub ������ ���������
pwd
cd
Cd ..
cd /
ls
Cd mediaGet2
$ cd "���������� � ��� ��������"
$ cd e:/gitpractic
$ ls -a
$ ls ..
$ ls ~
$ touch my-new-file.txt
$ mkdir new-dir 
$ mkdir -p dir1/dir-inside/dir-deeper-inside
~/my-git-projects
touch ../../file.txt
$ cp index.html src/
cp index.html style.css script.js src/
$ mkdir first-project   
$ touch first-project/data.txt first-project/table.csv
$ mv 2.txt 3.txt ./1
Mv data.txt ../
cat myfile.txt
rm example.txt
rmdir images
rm -r images
Cd ..
mkdir second-project && cd second-project && touch index.html style.css
Cd tab
tab
$ git version
��������� gitconfig
git config --global user.name "User Namovich"
git config --global user.email username@yandex.ru
$ cat ~/.gitconfig
$ git config --list
git init
rm -rf .git
Git status
git add --all
git add todo.txt
git add .
$ git add todo.txt
# ���
$ git add --all
git commit -m '��� ������ ������!'
git log
$ cd ~ # ������� � �������� ����������
$ ls -la .ssh/ # ������ ������ ��������� ������

ssh-keygen -t rsa -b 4096 -C "����������� �����, � ������� �������� ��� ������� �� GitHub"

ls -a ~/.ssh

clip < ~/.ssh/id_ed25519.pub
��������� �� GitHub � �������� ����� Settings (����. ����������) � ���� ��������.
� ���� ����� ������� �� ����� SSH and GPG keys.
� ����������� ������� �������� New SSH key (����. ������ SSH-�����).
� ���� Title (����. ����������) �������� �������� �����. ��������, Personal key (����. ������� �����).
� ���� Key type (����. ���� �����) ������ ���� Authentication Key (����. ����� ��������������).
� ���� Key ���������� ��� ���� �� ������ ������.
������� �� ������ Add SSH key (����. ��������� SSH-�����).
ssh -T git@github.com
git remote add
git remote add origin git@github.com:%���_��������%/first-project.git
git remote -v
git push -u origin master
git push
touch README.md
