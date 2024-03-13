# django-rest-framework-template

Etapas para o template funcionar:

1. Para gerar um Secret Key novo para o novo projeto --> Acessa o https://djecrety.ir/
   OU --> Etapas deste site: https://codinggear.org/django-generate-secret-key/
2. Mudar o nome do arquivo ".env-MODIFICAR-NOME" para ".env" e colocar os valores corretos no .env

3. Se necessário --> Adicionar novo domínio no ALLOWED_HOSTS e em CORS_ORIGIN_WHITELIST no settings.py
4. Caso não vá hospedar o backend na Vercel --> Apagar o arquivo vercel.json
