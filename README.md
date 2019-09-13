#maquina virtual
python3 -m venv env
source env/bin/activate
pip install django djangorestframework pygments
cd tuto
python manage.py runserver

#controle
http://127.0.0.1:8000/admin/
#admin - login
#admin - senha

#visualizar todos
http://127.0.0.1:8000/snippets/

#visualizar individual
http://127.0.0.1:8000/snippets/1

#cadastrar
http://127.0.0.1:8000/admin/snippets/snippet/

