## Ход работы

### Запуск docker compose

![Docker compose](images/compose.png)

### Инициализация nextcloud

![Nextcloud init](images/nextcloud_init.png)

### Promtail подключился к нужному файлу

![Promtail seeked nextcloud.log](images/promtail_attach.png)

### Импорт шаблона в zabbix

![Zabbix template](images/zabbix_template.png)

### Разрешение использовать имя nextcloud

![Nextcloud name](images/nextcloud_name.png)

### Добавление хоста в zabbix

![Zabbix host](images/zabbix_host.png)

### Добавление источников данных в Grafana

![Loki datasource](images/loki_datasource.png)

![Zabbix datasource](images/zabbix_datasource.png)

### Дэшборды

![Loki grafana](images/loki_grafana.png)

![Zabbix grafana](images/zabbix_grafana.png)

![Grafana dashboard](images/grafana_dashboard.png)

## Вопросы

### Чем SLO отличается от SLA?

SLO (Service Level Objective) — это конкретная цель в рамках метрик доступности и производительности. SLA (Service Level Agreement) — это договорное обязательство перед клиентом, включающее последствия за несоблюдение SLO.

### Чем отличается инкрементальный бэкап от дифференциального?

Инкрементальный бэкап сохраняет только изменения с момента последнего бэкапа (полного или инкрементального). Дифференциальный бэкап сохраняет изменения с момента последнего полного бэкапа.

### В чем разница между мониторингом и observability?

Мониторинг — это отслеживание заранее известных метрик. Observability (наблюдаемость) — это возможность понять поведение системы на основе данных (логов, метрик, трассировок), даже если проблема ранее не была предсказана.
