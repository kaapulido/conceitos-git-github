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
