# Развертывание

1. Скопировать все файлы репозитория в `~/default`

2. Дать симлинки на конфиги для nginx:
```bash
sudo ln -s /home/web/default/configs/default_nginx.conf /etc/nginx/sites-enabled/
```
3. Перезапустить nginx:

```bash
sudo servise nginx reload
```

---

**ВАЖНО:** не забывайте убирать прокси-редиректы (править конфиг nginx) по мере перевода неиспользованых доменов в экусплуатацию  


