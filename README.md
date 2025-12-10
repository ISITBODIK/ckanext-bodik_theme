# ckanext-bodik_theme

BODIK (Big Data & Open Data Initiative Kyushu) において運用しているBODIK ODCSで利用している  
CKAN 用のデザインテーマ拡張 (Theme Extension) です。

---

## Features

- CKANの組織IDを元にデザインを変更

---

## Requirements

- CKAN 2.10 以降
- Python 3.x

---

## Install

```bash
git clone https://github.com/ISITBODIK/ckanext-bodik_theme.git
cd ckanext-bodik_theme
pip install -e .
```

---

## Configuration

ckan.ini に下記の設定を追加してください。
```
ckan.plugins = ... bodik_theme

# CKAN site URL
ckan.site_url = https://your-ckan-domain.example

# WordPress site URL
bodik.wordpress_url = https://your-wordpress-domain.example

# Opendata Map site URL
bodik.map_url = https://your-map-domain.example
```

---

## License
MIT License

Copyright (c) 2025  
ISIT (Institute of Systems, Information Technologies and Nanotechnologies)  
Big Data & Open Data Initiative Kyushu (BODIK)