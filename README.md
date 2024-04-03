# ForumDiscussao
Este projeto tem como objetivo criar uma plataforma básica para discussões online, onde os usuários podem interagir por meio de postagens, comentários e perfil pessoal.

# Fórum de Discussão Flask

O Fórum de Discussão Flask é um projeto desenvolvido em Flask, um framework web em Python. Este projeto tem como objetivo criar uma plataforma básica para discussões online, onde os usuários podem interagir por meio de postagens, comentários e perfil pessoal.

## Funcionalidades

- **Página Inicial (Home)**: Exibe as postagens mais recentes em ordem cronológica decrescente.
- **Página de Contatos**: Página estática exibindo informações de contato.
- **Página de Usuários**: Exibe uma lista de todos os usuários cadastrados no sistema.
- **Autenticação de Usuários**: Implementação de login e logout de usuários.
- **Perfil do Usuário**: Página onde os usuários podem ver e editar suas informações pessoais, como email, nome de usuário e foto de perfil.
- **Criar Postagem**: Funcionalidade para que os usuários autenticados possam criar novas postagens.
- **Editar Postagem**: Usuários podem editar suas próprias postagens.
- **Excluir Postagem**: Usuários podem excluir suas próprias postagens.
- **Comentários em Postagens**: Os usuários podem comentar nas postagens.
- **Notificações e Mensagens**: Implementação de sistema básico de notificações e mensagens entre usuários.

## Requisitos

- Python 3.x
- Flask
- Flask-Bcrypt (para criptografia de senhas)
- Flask-Login (para autenticação de usuários)
- Flask-WTF (para formulários)
- Pillow (para manipulação de imagens)

## Como Usar

1. Clone este repositório em seu ambiente local:

```
git clone https://github.com/seu-usuario/nome-do-repositorio.git
```

2. Instale as dependências:

```
pip install -r requirements.txt
```

3. Configure o banco de dados no arquivo `config.py`.

4. Execute o aplicativo Flask:

```
python app.py
```

5. Acesse o aplicativo em seu navegador em (https://forumdiscussao-production.up.railway.app/)

## Contribuindo

Contribuições são bem-vindas! Sinta-se à vontade para abrir uma issue para relatar bugs ou solicitar novas funcionalidades. Se desejar contribuir diretamente, por favor, abra um pull request. Certifique-se de seguir as diretrizes de contribuição.

## Licença

Este projeto está licenciado sob a [MIT License](LICENSE).
