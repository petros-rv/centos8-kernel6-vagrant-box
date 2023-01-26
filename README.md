#название выполняемого задания
Домашняя работа по лекции OTUS №1 "С чего начинается Linux"
#текст задания
1. Создать аккаунт в Github
2. Создать аккаунт в VagrantCloud
3. Установить программу Packer (для создания образа ВМ для закачки в VagrantCloud)
4. Создать файл centos.json
5. Создать образ ВМ с помощью centos.json (packer build centos.json)
6. Подключиться к созданной ВМ (vagrant ssh)
7. Проверить ядро в ВМ (uname -r) 
8. Загрузить созданный бокс centos-8-kernel-5-x86_64-Minimal.box в VagrantCloud 
   (vagrant cloud publish --release petrosrv/centos8-kernel5 1.0 virtualbox centos-8-kernel-5-x86_64-Minimal.box
9. Добавить в локальный git файлы Vagrantfile и README.md
   (git add Vagrantfile README.md)
10. Создать commit 
    (git commit -m "vagrant uname -r 6.1.7-1.el8.elrepo.x86_64")
7. Загрузить Vagrantfile и README.md на Github 
    (git push) 


