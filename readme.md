# Conceitos de Git e Github
Este arquivo tem como objetivo armazenar os comandos básicos para utilização de Git e Github

## Configuração inicial 
Rode os comandos abaixo no terminal(cmd) do seu computador.
```bash
git config --global user.name "Karen Pulido"

git config --global user.email karen.pulido@fatec.sp.gov.br
```

## Comando do Git
Para iniciar o Git em uma pasta do computador utilizamos o init.
IMPORTANTE: Só é executado 1 vez.
```bash
git init
```

Para vincular o projeto ao Github utilizamos o comando remote, basta o repositório estar criado no Github e seguir a segunda opção da lista de comandos que aparece no site.<br>
**IMPORTANTE:** Depois do remote deve ser executados os outros 2 comandos da página.
```bash
git remote add origin < url_repositorio_github >
```


Para verificar a situação do repositório (pasta) usamos o status a qualquer momento.
```bash
git status
```

## Comando de ADD .
O ADD salva tudo o que está vinculado na pasta e o . é o local
```bash
git add .
``` 

## Comando Commit -m "Mensagem de até onde foi salvo - e a última etapa que foi realizada"
O Commit serve para que seja salvo até onde "paramos" e até "onde foi salvo".
```bash
commit -m "msg"
```

## Para baixar alterações que estão apenas no Github utilizamos o pull.<br>
**IMPORTANTE:** Sempre que baixar a última versão da nuvem antes de enviar a atual do computador
```bash
git pull
```

## Para enviar os comits do pc para o Github utilizamos o push.
```bash
git push
```
Para baixar o repositório do Github em um novo computador utilizamos o clone.
```bash
git clone < url_do_repositorio_github >
```

