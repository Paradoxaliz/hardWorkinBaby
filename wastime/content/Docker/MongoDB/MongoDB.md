# MongoDB (NoSQL)

Никогда в разработке не используйте русские имена файлов и каталогов!
Никогда в разработке не используйте пробелы и спец.символы в именах файлов и каталогов!

Выполните все этапы работы с проектом по примеру с Nginx

---

## 1. Запуск MongoDB

В Windows Powershell:

```powershell
docker run -d `
  --name my-mongo `
  -p 27017:27017 `
  mongo:latest
```

В Git-Bash/Linux/WSL 2.0/Mac:

```bash
docker run -d \
  --name my-mongo \
  -p 27017:27017 \
  mongo:latest
```

![](../img/28.jpg)

---

## 2. Подключиться через shell

```bash
docker exec -it my-mongo mongosh
```

![](../img/29.jpg)

---

## Повыполняйте какие-нибудь команды в этой БД для проверки

![](../img/30.jpg)
