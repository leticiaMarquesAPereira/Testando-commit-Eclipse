## Criando repositório e fazendo PUSH com Eclipse

Passo 1: Iniciar um repositório Git no seu projeto

- Clique com o botão direito no projeto que você deseja versionar com o Git.
- Selecione Team > Share Project.
- Escolha Git e clique em Next.
- Selecione Create para criar um novo repositório Git local (ou escolha um repositório existente, se aplicável).
- Clique em Finish.

##
        
Passo 2: Adicionar Arquivos e Fazer Commit

- Clique com o botão direito no projeto.
- Vá em Team > Add to Index.
  
Fazer commit dos arquivos:

- Clique com o botão direito no projeto.
- Vá em Team > Commit.
- Adicione uma mensagem de commit e selecione os arquivos que deseja comitar.
- Clique em Commit (ou Commit and Push se você já tiver um repositório remoto configurado).

##
      
Passo 3: Configurar Repositório Remoto no GitHub

- Vá para o GitHub e crie um novo repositório (não adicione README, .gitignore ou licença).

Adicionar repositório remoto no Eclipse:

- Clique com o botão direito no projeto.
- Vá em Team > Remote > Push.
- Configure a URL do repositório GitHub (copie a URL do repositório criado).
- Gere um Token no GitHub e insira-o no lugar de SENHA (seu user vai ser o mesmo do GitHub)
- Clique em Next e configure as branches (geralmente, master ou main).
- Clique em Finish.

##
          
Passo 4: Pushing para o GitHub

Pushing do projeto para o repositório remoto:

- Clique com o botão direito no projeto.
- Vá em Team > Push to Upstream.
