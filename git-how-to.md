# Задание
## Как создать ssh-ключ
необходимо открыть терминал, использовать команду
`ssh-keygen -T ed25519 -C "youremail@p.edu"`
указать адрес сохранения пароля
## Как добавить ключ в GitHub
зайти в настройки профиля, выбрать SSH and GPG keys
ввести содержимое файла .pub
затем выполнить коммандуЖ
`ssh-add (адресс приватного ключа)`
`ssh -T git@github.com`
соединение должно быть установлено
## Как склонировать репозиторий
нужно выполнить комманды:
```git config --global user.name "ChanturiiaDzhoni"
git config --global user.email "chanturiia.dg@phystech.edu"
```
нужно в терминале перейти к папке в которой вы хотите созранить репозиторий и выполнить комманду:
`git clone git@github.com:ChanturiiaDzhoni/Chanturiia.git`
с адресом скопированным с сайта