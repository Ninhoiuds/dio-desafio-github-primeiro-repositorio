# Criar chave SSH :closed_lock_with_key:

- No GIT Bash digitar: SSH - keygen -t ed25519 -C -  seu email.

  Serão criados dois arquivos um público e outro privado, para visualizar a pasta digite: cat id.ed25519.pub

  obs: Sempre compartilhar a chave .pub

- Copiar a chave e colar no GITHUB

- Para passar a chave para o Agente digitar: eval $(ssh-agent-s) 

  ssh -add id-ed25519

# Criar Token

- No GITHUB / Developer Settings / Personal Access Token / Generate New Token / marcar repo.

