Проект работы с Git и GitHub яндекс практикум
pwd
cd
Cd ..
cd /
ls
Cd mediaGet2
$ cd "Фотографии с дня рождения"
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
Настройка gitconfig
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
# или
$ git add --all
git commit -m 'Мой первый коммит!'
git log
$ cd ~ # перешли в домашнюю директорию
$ ls -la .ssh/ # вывели список созданных ключей

ssh-keygen -t rsa -b 4096 -C "электронная почта, к которой привязан ваш аккаунт на GitHub"

ls -a ~/.ssh

clip < ~/.ssh/id_ed25519.pub
Перейдите на GitHub и выберите пункт Settings (англ. «настройки») в меню аккаунта.
В меню слева нажмите на пункт SSH and GPG keys.
В открывшейся вкладке выберите New SSH key (англ. «новый SSH-ключ»).
В поле Title (англ. «заголовок») напишите название ключа. Например, Personal key (англ. «личный ключ»).
В поле Key type (англ. «тип ключа») должно быть Authentication Key (англ. «ключ аутентификации»).
В поле Key скопируйте ваш ключ из буфера обмена.
Нажмите на кнопку Add SSH key (англ. «добавить SSH-ключ»).
ssh -T git@github.com
git remote add
git remote add origin git@github.com:%ИМЯ_АККАУНТА%/first-project.git
git remote -v
git push -u origin master
git push
touch README.md
