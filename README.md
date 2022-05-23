# otis
##ДЗ1
Установка CMS Wordppress, exporter на первой виртуальной машине
nginx + phpfpm + mariadb
node_exporter
mysqld_exporter
blackbox
Установка prometheus, alertmanager, grafana, prometheus_bot (для отправки оповещений в telegram) на второй виртуальной машине
добавление targets в prometheus
настройка alertmanager для отправки сообщений в telegram

##ДЗ2
Добавление в grafana источника данных Prometheus
Создание дашборда для node_exporter первой виртуальной машины в папке infra
Создание дашборда для blackbox_exporter в папке app
Создание Contact point для telegram
Создание alert rule для оповещения о недоступности страницы CMS wordpress
Создание DrillDown dashboard для node_exporter виртуальной машины с CMS и страницы CMS https://example.com/wp-admin
