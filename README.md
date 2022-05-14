Playbook site.yml:
Устанавливает пакеты клиента и сервера clickhouse  
Версия clickhouse и необходимые пакеты задаются в ./group_vars/clickhouse/vars.yml  
Устанавливает и запускает Vector, переменные для него задаются в ./group_vars/vector/vars.yml, конфиг копируется из темплэйта ./templates/vector.yaml.j2  
Клонироует lighthouse из его git репозиртария, переменные для него задаются в ./group_vars/lighthouse/vars.yml  
Устанавливает и запускает nginx, клнфиг для него копируется из темплэйта templates/nginx.conf.j2  



