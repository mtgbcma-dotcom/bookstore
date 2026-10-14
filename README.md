# Bookstore

Projeto desenvolvido no módulo 56 do curso Full Stack Python da EBAC.

Configurei o ambiente com Poetry, adicionei o Django REST Framework
e registrei rest_framework em INSTALLED_APPS. Também atualizei
as dependências e o arquivo poetry.lock.

## Executar o projeto

```powershell
poetry install --no-root
poetry run python manage.py migrate
poetry run python manage.py runserver
```

Acesse http://127.0.0.1:8000/.

## Verificar a configuração

```powershell
poetry run python manage.py check
```

## Tecnologias

- Python
- Django
- Django REST Framework
- Poetry