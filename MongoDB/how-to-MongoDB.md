Passo a Passo

Download e Instalação do MongoDB:

  1- Acesse e baixe a edição MongoDB Community Server para o seu sistema operacional em: https://www.mongodb.com/download-center#community.

  2- Ao termino do download, siga o processo de instalação desejavel em: https://docs.mongodb.com/tutorials/
  RECOMENDÁVEL para Windows: leia e siga SOMENTE com atenção as instruções NESSA ORDEM: 
  Get MongoDB Community Edition; Install MongoDB Community Edition - Interactive Installation; 
  Configure a Windows Service for MongoDB Community Edition;

Iniciar o serviço MongoDB:

  1- Seguindo com sucesso a instalação acima para windows, para iniciar mongod.exe basta entrar no cmd em modo
  de privilégio e escrever: net start MongoDB. Para desligar: net stop MongoDB.

  2- Se o MongoDB não tiver sido configurado como serviço no Windows, para iniciar o mongod.exe deve-se executar 
  o comando no prompt: "C:\Program Files\MongoDB\Server\3.4\bin\mongod.exe" SE ESSE FOR O DIRETÓRIO A QUAL ELE SE ENCONTRA.

  3- É importante parar o serviço uma vez que esse não estiver sendo utilizado, para poupar memória, 
  com o comando: net stop MongoDB , ou inserindo Crt+C no prompt a qual mongod.exe estiver aberto.
