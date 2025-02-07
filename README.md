# Django Júnior - Desafio SOIRTEC

Este projeto foi criado como parte de um desafio técnico da SOIRTEC para candidatos à vaga de desenvolvedor júnior. O objetivo principal é demonstrar o entendimento dos conceitos de Django, incluindo manipulação de modelos, banco de dados e métodos.

## Objetivo do Desafio

- Seguir o tutorial oficial do Django para configurar o banco de dados e as tabelas necessárias.
- Implementar métodos no modelo `Question` para calcular o total de votos e verificar se a questão possui votos.

## Funcionalidades Implementadas

- **Página de resultados**: Exibe as questões e suas respectivas opções de resposta com a quantidade de votos.
- **Administração de questões e respostas**: Através do painel administrativo do Django, é possível adicionar, editar e visualizar questões e suas opções.

## Como Rodar o Projeto

1. Clone este repositório:
   ```bash
   git clone https://github.com/MateusChavito/TesteSOIRTEC.git

## Como Rodar o Projeto

2. **Ative o ambiente virtual**:

   - **Windows**:
     ```bash
     venv\Scripts\activate
     ```

   - **Mac/Linux**:
     ```bash
     source venv/bin/activate
     ```

3. **Instale as dependências**:
   ```bash
   pip install -r requirements.txt

   
4. **Execute as migrações:**:
   ```bash
   python manage.py migrate


5. **Crie um superusuário para acessar o admin:**:
   ```bash
   python manage.py createsuperuser


6. **Inicie o servidor de desenvolvimento:**:
   ```bash
   python manage.py runserver


6. **Acesse a página principal e o painel de administração no seguinte endereço:**:

Página principal: http://127.0.0.1:8000/
Admin: http://127.0.0.1:8000/admin/


Tecnologias Utilizadas
Django 5.1.6
Python 3.13.2

