# gittest

//criar branch  
git branch -c nome_branch  
//"upload" da branch no local pro remoto  
git push -u origin nome_branch  
//"download" das branchs no repo  
git fetch  

//merge funciona com  
//vc dentro da branch que quer receber  
//conteudo de outra branch  
//exemplo estou na branch1 e quero conteudo branch2  
git merge branch2  

//conferir sempre os arquivos que vieram no merge  
//resolver os conflitos  
//só depois fazer o push  

//se der ruim o push do merge  
//precisa pegar a sha ou informar quantos  
//comitte atras quer voltar de como a branch estava  
//pra volta-la  
git reset --hard numero_de_comitts_atras  
ou  
git reset --hard sha  

git push -f  
