# Jogoteca
### Este projeto é uma aplicação web simples para gerenciar uma coleção de jogos, utilizando o framework Flask em Python.

## Requisitos
- Python 3.6 ou superior
- pip (gerenciador de pacotes do Python)
- virtualenv (opcional, mas recomendado para criar ambientes virtuais)
- Configuração do Ambiente

### Passo 1: Clonar o Repositório
Clone este repositório para sua máquina local usando o comando:
```bash
  git clone <URL_DO_REPOSITORIO>
```

### Passo 2: Criar um Ambiente Virtual
Para criar um ambiente virtual, execute os seguintes comandos:
```bash
  python -m venv venv
```
Isso criará um diretório venv com o ambiente virtual.

### Passo 3: Ativar o Ambiente Virtual
Ative o ambiente virtual com o comando apropriado para o seu sistema operacional:

Windows:

```bash
venv\Scripts\activate
```
macOS e Linux:
```bash
source venv/bin/activate
```
### Passo 4: Instalar as Dependências
Com o ambiente virtual ativado, instale as dependências do projeto usando o comando:

```bash
pip install Flask
```
## Estrutura do Projeto
- app.py: Código principal da aplicação Flask.
- templates/: Diretório contendo os templates HTML.
- Executando a Aplicação
- Para iniciar a aplicação, certifique-se de que o ambiente virtual está ativado e execute:

```bash
python app.py
```
A aplicação estará disponível em http://127.0.0.1:5000/.

## Funcionalidades
### Lista de Jogos
A página inicial (/) lista todos os jogos cadastrados.

### Adicionar Novo Jogo
A página /novo permite adicionar um novo jogo. Esta funcionalidade requer autenticação.

### Autenticação de Usuário
A página /login permite que usuários se autentiquem. Usuários pré-definidos estão configurados no código.

### Logout
A rota /logout permite que os usuários façam logout.
## Autores

- [@IasminCQFernandes](https://www.github.com/iasmincqfernandes)

