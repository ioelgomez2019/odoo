la primera vez que ejecutaromos y abrimos coneccion a oddo debemoa poner con este comando
    -- python odoo-bin -r Jgomez -w Joel181895 --addons-path=addons -d DB_ODOO -i base
La segunda vez, si no queremos hacer un restore a la base de datos podemos atrabajar:
    -- python odoo-bin -r Jgomez -w Joel181895 --addons-path=addons -d DB_ODOO

como se creo un conf :
    -- python odoo-bin -c odoo.conf

para crear un modulo
python odoo-bin scaffold school modules