# backup-marzban
# Instalasi dependensi
```pip install python-telegram-bot```

# Mengunduh skrip Python dari GitHub
```wget https://raw.githubusercontent.com/daffahelmi/backup-marzban/main/backup.py -O /root/backup-m.py```

Untuk membackup```python3 backup-m.py```
# Untuk eksekusi backup setiap 6 jam sekali
```crontab -e```

```0 */6 * * * /usr/bin/python3 /root/backup-m.py```
