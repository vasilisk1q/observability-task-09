# Домашнее задание
## Конфигурации Grafana Loki

# Цель:
## Заменить Elasticsearch на Grafana Loki.


# Описание/Пошаговая инструкция выполнения домашнего задания:
В данном ДЗ вы можете воспользоваться наработками из предыдущего.

В данном ДЗ вам предстоит заменить Elasticsearch на Grafana Loki. Убедитесь, что данные поступают в Grafana Loki и к ним есть доступ.

В качестве результата ДЗ принимаются - файл конфигурации Grafana Loki, 
файл конфигурации шиппера логов (любой шиппер на ваш выбор), скриншот, в котором видно, что вы получили доступ к логам в Grafana Loki.

# Решение
Файлы конфигурации grafana, promtail, loki представлены [здесь](https://github.com/vasilisk1q/observability-task-09/blob/main/docker-compose.yml).
Файл конфигурации [promtail](https://github.com/vasilisk1q/observability-task-09/blob/main/etc/promtail/config.yml)

Скриншот данных полученных в графана:
![image](https://github.com/user-attachments/assets/917221a1-6925-4d55-9b03-c22f30fcb0d1)

![image](https://github.com/user-attachments/assets/b206398b-e4c2-4b5b-9aba-0e050987a10b)
