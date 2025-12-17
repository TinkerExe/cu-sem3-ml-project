# cu-sem3-ml-project
Итоговый проект курса Machine Learning

## Установка

**Для Arch Linux:**
```bash
sudo pacman -S graphviz pkgconf python-pygraphviz
python -m venv --system-site-packages .venv
source .venv/bin/activate
pip install -r requirements.txt
```

**Для Ubuntu / Debian:**
```bash
# Раскоментируетсе все !pip и !apt-get в файле
# или
sudo apt-get update
sudo apt-get install graphviz graphviz-dev pkgconf
python -m venv .venv
source .venv/bin/activate
pip install pygraphviz
pip install -r requirements.txt
```
