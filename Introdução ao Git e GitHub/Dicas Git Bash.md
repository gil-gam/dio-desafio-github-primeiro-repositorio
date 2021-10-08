# Dicas Git Bash


## 
**COMO CORRIGIR AS MENSAGENS DOS COMMITS**

- git pull origin main
- git rebase -i HEAD~5 (entra no editor e mostra as mensagens dos últimos 5 commits)
- dentro do editor:
  - alterar pick para reword; alterar a mensagem como quiser;
  - alterar pick para drop: apaga o commit;
  - ESC
  - :w  + ENTER (grava)
  - :x + ENTER (sai do editor)
- git push --force origin main
- verificar as alterações no GitHub;



