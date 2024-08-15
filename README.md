
# Exercicio 01 CI/CD Impacta

1 -Configurações iniciais: 

mkdir Exercicio01
cd Exercicio01/
git init
git config --global user.name "Jeferson Ferreira"
git config --global user.email "jeferson.luis@aluno.faculdadeimpacta.com.br"
ls .git/

https://raw.githubusercontent.com/XxJefinhooxX/imagens/main/image1.jpeg


2 -Executar comando: echo 01 - arquivo.txt

ls 
echo 01 > arquivo.txt
ls 

![Alt text](https://raw.githubusercontent.com/XxJefinhooxX/imagens/42ec701a865ec3af0da3ceb7b9bfd48301226089/image2.jpeg)


3 - Adicionar arquivo no staging e conferir status:

git add.
git status

![Alt text](https://raw.githubusercontent.com/XxJefinhooxX/imagens/main/image3.jpeg)

4 - Commitar o arquivo do staging com a descrição "git add example - arquivo.txt: 

git commit -m "git add example - arquivo.txt"
git status

![Alt text](https://raw.githubusercontent.com/XxJefinhooxX/imagens/main/image4.jpeg)

5 -  Sobrescrever conteudo do arquivo.txt:

![Alt text](https://raw.githubusercontent.com/XxJefinhooxX/imagens/main/image5.jpeg)

6 - Verificar o diffing no arquivo 
git diff 

![Alt text](https://raw.githubusercontent.com/XxJefinhooxX/imagens/main/image6.jpeg)

7 - Adicionar novamente o arquivo no staging e conferir o status e em seguida verificar o diffing no arquivo:

git add . 
git status 

echo 03 > arquivo.txt
git diff

![Alt text](https://raw.githubusercontent.com/XxJefinhooxX/imagens/main/image7.jpeg)

 8 - Fazer o restore do arquivo da área de staging e verificar o status: e em seguida relalizar commit do arquivo: 

![Alt text](https://raw.githubusercontent.com/XxJefinhooxX/imagens/main/image8.jpeg)

9 - Verificar o log: 

git log 

![Alt text](https://raw.githubusercontent.com/XxJefinhooxX/imagens/main/image9.jpeg)






