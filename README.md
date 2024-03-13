# django-rest-framework-template

Etapas para o template funcionar:

1. Para gerar um Secret Key novo para o novo projeto --> Acessa o https://djecrety.ir/
   OU --> Etapas deste site: https://codinggear.org/django-generate-secret-key/
2. Mudar o nome do arquivo ".env-MODIFICAR-NOME" para ".env" e colocar os valores corretos no .env
3. Checar no settings.py qual database irá utilizar. Inicialmente está o padrão do Django
4. Remover ou renomear o app "endpoint_teste", inclusive no Installed_Apps no settings.py

5. Se necessário --> Adicionar novo domínio no ALLOWED_HOSTS e em CORS_ORIGIN_WHITELIST no settings.py
6. Caso não vá hospedar o backend na Vercel --> Apagar o arquivo vercel.json | Talvez possa apagar o "app = application" no arquivo wsgi.py
