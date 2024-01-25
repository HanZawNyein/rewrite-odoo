```zsh
git clone https://github.com/HanZawNyein/rewrite-odoo.git --depth 1 --branch 16.0 --single-branch
```

```zsh
cd rewrite-odoo
```

```zsh
pip3 install -r requirements.txt
```

## Creation `.conf`

```editorconfig title='rewrite-odoo.conf' linenums="1" hl_lines="1 2" 
[options]
; This is the password that allows database operations:
;admin_passwd = master
db_host = False
db_port = False
db_user = odoo
db_password = odoo
```