
FROM python:3.6-alpine3.8                     
# Скачиваем легковесный образ python-alpine

COPY 1.py /app/                               
# Копируем 1.py с компьютера в дирректорию /app образа

WORKDIR /app                                  
# Делаем /app рабочей дирректорией для след. команды

ENTRYPOINT ["python3", "/app/1.py"]           
# Говорим "Питон3, запусти приложение /app/1.py"
