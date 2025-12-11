# project-odoo-sh

Tested on Ubuntu

```
git clone --recurse-submodules --shallow-submodules --depth=1 git@github.com:loym-com/project-odoo-sh project_18

cd project_18/loym-com/tools-odoo-sh/.tools-odoo-sh

cp settings_template.py settings.py

---

bash task help

bash task add_submodule OCA server-tools 18.0

bash task update

---

python3 create_odoo_conf.py project_18

python3 create_venv.py

---

nano ../../../odoo.conf

source ../../../.venv/bin/activate

python3 ../../../odoo/odoo/.odoo/odoo-bin -c ../../../odoo.conf

# Open browser, go to localhost:8069, login with username 'admin' password 'admin'
```