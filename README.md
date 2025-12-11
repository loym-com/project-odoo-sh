# project-odoo-sh

Tested on Ubuntu

```
git clone git@github.com:loym-com/tools-odoo-sh project_18

cd project_18/loym-com/tools-odoo-sh/.tools-odoo-sh

---

bash task help

bash task add_submodule OCA web 18.0

---

python3 create_odoo_conf.py project_18

python3 create_venv.py

---

nano ../../../odoo.conf

source ../../../.venv/bin/activate

python3 ../../../odoo/odoo/odoo-bin -c ../../../odoo.conf
```