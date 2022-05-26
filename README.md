# otis
ДЗ-1
-----------------------------------
Установка CMS Wordppress, exporters на первой виртуальной машине <br>
(nginx + phpfpm + mariadb)<br>
node_exporter<br>
mysqld_exporter<br>
blackbox<br>
Установка prometheus, alertmanager, grafana, prometheus_bot (для отправки оповещений в telegram) на второй виртуальной машине<br>
добавление targets в prometheus<br>
настройка alertmanager для отправки сообщений в telegram<br>

ДЗ-2
-----------------------------------
Добавление в grafana источника данных Prometheus<br>
Создание дашборда для node_exporter первой виртуальной машины в папке infra<br>
Создание дашборда для blackbox_exporter в папке app<br>
Создание Contact point для telegram<br>
Создание alert rule для оповещения о недоступности страницы CMS wordpress<br>
Создание DrillDown dashboard для node_exporter виртуальной машины с CMS и страницы CMS https://example.com/wp-admin

ДЗ-3
----------------------------------
Установка heartbeat, metricbeat, filebeat на виртуальной машине
Настройка отправки логов в ELK через logstash
ELK установлен на отдельной виртуальной машине и будет использован в ДЗ4
