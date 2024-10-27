# Sistema de Gerenciamento de Atividades

## Descrição

Este projeto é um sistema de gerenciamento de atividades desenvolvido em Python utilizando o framework Django. O objetivo é permitir que usuários cadastrem, editem, excluam e marquem atividades como concluídas, otimizando a organização pessoal e aumentando a produtividade.

## Funcionalidades

- **Cadastro de Atividades**: Crie novas atividades com título, descrição, data de vencimento e prioridade.
- **Listagem de Atividades**: Visualize todas as atividades cadastradas, com opções de filtro por status e prioridade.
- **Edição de Atividades**: Edite atividades já cadastradas com validações em tempo real.
- **Exclusão de Atividades**: Remova atividades com confirmação para evitar exclusões acidentais.
- **Marcação de Atividades como Concluídas**: Marque atividades como concluídas com um clique.

## Tecnologias Utilizadas

- **Backend**: Django (com Django REST Framework)
- **Frontend**: HTML, CSS, JavaScript (Bootstrap ou React opcional)
- **Banco de Dados**: SQLite (ou PostgreSQL para produção)
- **Controle de Versão**: Git

## Instalação

### Pré-requisitos

- Python 3.x
- pip (gerenciador de pacotes do Python)
- Django

### Passos para a instalação

1. Clone o repositório:

   ```bash
   git clone https://github.com/seuusuario/sistema-gerenciamento-atividades.git
   cd sistema-gerenciamento-atividades
   ```

2. Crie um ambiente virtual:

   ```bash
   python -m venv venv
   source venv/bin/activate  # Para Windows use: venv\Scripts\activate
   ```

3. Instale as dependências:

   ```bash
   pip install -r requirements.txt
   ```

4. Faça as migrações do banco de dados:

   ```bash
   python manage.py migrate
   ```

5. Crie um superusuário para acessar o admin:

   ```bash
   python manage.py createsuperuser
   ```

6. Inicie o servidor de desenvolvimento:

   ```bash
   python manage.py runserver
   ```

7. Acesse a aplicação no navegador:

   ```
   http://127.0.0.1:8000/
   ```

## Uso

Após acessar a aplicação, você pode:

- Cadastrar novas atividades através do formulário disponível.
- Visualizar todas as atividades na lista.
- Editar ou excluir atividades conforme necessário.
- Marcar atividades como concluídas.

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests.

## Licença

Este projeto está licenciado sob a MIT License. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

Sinta-se à vontade para personalizar este README conforme necessário!
