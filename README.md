# Lumina

- Samuel : Documentação
- Pedro : Conexão do banco de dados
- Matheus : Contato com o cliente
- Caio : Telas faltantes e Slides
- Zayon : Telas faltantes e Slides
- Romulo : Contato com o cliente
- Bernardo : Telas faltantes e Slides

  Execução do Site (Flask)

--- PASSO 1: Pré-requisitos e Extensões ---
1. Certifique-se de ter o Python instalado em sua máquina.

--- PASSO 2: Instalação das Dependências ---
Abra o terminal integrado do VS Code e execute o seguinte comando 
para instalar todas as bibliotecas necessárias de uma só vez:

    pip install -r requirements.txt
ou
    pip install Flask Flask-SQLAlchemy-Lite PyMySQL)

--- PASSO 3: Execução da Aplicação ---
1. Abra o arquivo main.py e execute-o.
2. No terminal, localize o endereço local gerado (exemplo: http://127.0.0.1:5000).
3. Copie o endereço e cole na barra de pesquisa do seu navegador.


OBS:

Como o banco de dados está configurado apenas para o ambiente local e as rotas
utilizam a estrutura de templates do Flask:

- Somente a página inicial, a de cadastro e a de login funcionarão diretamente 
  pelos links/botões da interface.
- Para acessar as demais páginas, é necessário abrir diretamente o arquivo da 
  página correspondente ou digitar a rota exata (URL) diretamente no navegador.
