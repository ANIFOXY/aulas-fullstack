git --versio | é para ver a versado git

git config --global user.name "Seu Nome"
git config --global user.email "Seu email"   | Serve para logar no seu GitHub

la -al ~/.ssh verifica se existe chave ssh

ssh-keygen -t ed25519 -C "seu email" | é para adicionar a chave de ID

eval "$(ssh-agent -s)" | iniciar um agente de ssh

ssh-add ~/.ssh/id_ed25519 | adiciona a chave ssh para o agente

git init | parar instalar as extenções

git status | é para ver os status dos arquivos

git add | server para adicionar todos os arquivo para sincornizar

git Branch | é para criar um Branch nova

git checkout | server para voce entrar em uma Branch sem criar ela

git checkout -b | serve para criar uma branck tmb

git commit -m | server para fazer um commit e sua descrisao

git branch -D | é para deletar uma branch

git merge | Faz a merge da branch para a Atual