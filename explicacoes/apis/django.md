# Django

Um dos principais arquivos do Django são:
- `settings.py`;
- `manage.py`;

___

### settings.py

Neste arquivo é onde ficam todas as configurações do funcionamento da API, como:
  - Portas de acesso;
  - Liberação de url;
  - Senhas e gerenciamento de dados sensíveis;
  - Gerenciamento de linguagens da API (PT-BR/EN-US...);
  - Gerenciamento de arquivos estáticos;

___

### manage.py

O coração da API. Este é o arquivo utilizado para fazer a execução da API.
  
Para executar, basta rodar o comando `python manage.py runserver` no terminal.

Além de executar a api, também tem diversos outros comandos para gerenciamento da API.

Os principais são:
  - runserver;
  - migrate;
  - makemigrations;
  - startapp;
  - startproject;

Para mais informações execute `python manage.py help` ou consulte a página oficial do **[Django](https://docs.djangoproject.com/en/3.2/)**.

Obs.: Dentro da Tembici, utilizamos a versão 3.X do Django. A versão 4 ou superior apresenta diversas mudanças.

## Vantagens

- Possui uma página de admin nativa;
- Existe parte restfull e parte visual/interativa;
- Robusto;
- Tem diversos plugins para praticamente tudo que você precisar;