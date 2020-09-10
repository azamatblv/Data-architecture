# Data-architecture

Команды для настройки ключа для Archi:
1) ssh-keygen -m PEM -t rsa -b 2048
2) /Users/aabalayev/.ssh/id_rsa_archi
3) eval "$(ssh-agent -s)"
4) -K ~/.ssh/id_rsa_archi
5) pbcopy < ~/.ssh/id_rsa_archi.pub
6) Добавить публичный ключ на странице  github
7) git@github.com:azamatblv/Data-architecture.git
