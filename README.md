# KUZ’KA.BUH — бухгалтерия для селлеров маркетплейсов

Монолит на **Django 5 + PostgreSQL 15**, HTMX, Bootstrap 5. PDF-договор (WeasyPrint), лиды с уведомлениями в email и Telegram, SEO (sitemap/robots/JSON-LD), блог/FAQ, формы с защитой.

## 1) Подготовка Ubuntu 22.04

```bash
sudo apt update && sudo apt -y upgrade
sudo apt -y install python3.11 python3.11-venv python3-pip git nginx postgresql postgresql-contrib
# зависимости WeasyPrint
sudo apt -y install libcairo2 libpango-1.0-0 libpangoft2-1.0-0 libpangocairo-1.0-0 libffi8 libgdk-pixbuf-2.0-0 shared-mime-info fonts-dejavu-core
