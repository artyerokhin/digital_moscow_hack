# digital_moscow_hack
Solution of https://hacks-ai.ru/championships/758465

# Разработка концепции ранжирования районов города по уровню самодостаточности

Для запуска кода используется docker образ gboeing/osmnx

Для запуска требуется (пример для Mac/Linux):
- получить образ docker `pull gboeing/osmnx`
- запустить образ в интерактивном режиме `docker run --rm -it -p 8888:8888 -v "$PWD":/home/jovyan/work gboeing/osmnx:latest`
- можно использовать ноутбук `self_sufficiency_estimation.ipynb`

Команды для запуска образа под Windows можно посмотреть по [ссылке](https://hub.docker.com/r/gboeing/osmnx)

Поддробнее почитать о концепции оценки можно в самом ноутбуке, либо в презентации
