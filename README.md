# SeuSite.com

# Alterando o Número da Porta de Saída

1. Abra o arquivo `docker-compose.yml`;
2. Em "ports", no lugar de 8200, adicione a porta designada para o seu projeto.

# Configuração do VSCode para o Git

1. Abra o terminal do vscode;
2. Digite o comando `ssh-keygen -t ed25519 -C "usuariogit@email.com"`;
3. Pressione Enter para aceitar o local padrão para salvar a chave;
4. Não precisa de senha, então pressione Enter duas vezes;
5. Digite o comando `cat ~/.ssh/id_ed25519.pub` para exibir a chave pública;
6. Copie a chave pública e cole no GitHub de seu usuário em Settings > SSH and GPG keys > New SSH key;
7. Digite um título para a chave e cole a chave no campo Key;
8. Clique em Add SSH key;
9. Digite `git add .` para adicionar ao processo de `commit` todos os arquivos modificados do projeto;
10. Digite `git commit -m 'descricao informal do que foi modificado'`;

11. Digite `git push` no terminal local para enviar as alterações para o repositório remoto.

# Criando um Webhook para Notificar o Servidor Web

1. Abra o repositório do projeto integrador no GitHub;
2. Acesse o menu Settings na parte superior do repositório;
3. Na página que se abre, à esquerda, acesse o menu Webhooks;
4. Clique no botão "Add webhook" na parte superior direita;
5. No campo "Payload URL*" digite exatamente o seguinte:
    https://jenkins.cachoeiro.es/github-webhook/
6. Mantenha as outras opções como estão e clique no botão verde "Add webhook", no final da página.

# Adicionando Colaboradores

1. Abra o repositório do projeto integrador no GitHub;
2. Acesse o menu Settings na parte superior do repositório;
3. Acesse o menu Collaborators, na parte esquerda superior;
4. Na página que se abre, clique no botão verde "Add People";
5. No modal que se abre, digite o e-mail ou nome de usuário git do colaborador que deseja adicionar;
6. Se estiver correto, logo abaixo do campo será mostrada uma caixa com o colaborador, na qual você deve clicar;
7. No passo seguinte, basta clicar em "Add UsuarioTal to this repository".

# Vídeo de Apoio

Você pode acessar um vídeo que demonstra essas configurações em:

https://www.youtube.com/watch?v=R8DTirL-mRc

#Porta de Cada Projeto 

1. Jeito Rural: 8201
2. Vitalis: 8202
3. ReclamES: 8203
4. CarbonIO: 8204
5. VoluntariÊ: 8205
6. Fitness Life: 8206
7. 
8.
9.

