GitHub. HW_2
1. На локальном репозитории сделать ветки для:
- Postman : Git branch Postman 
- Jmeter :  Git branch Jmetr
- CheckLists :  Git branch CheckLists
- Bag Reports :  Git branch BugReports
- SQL :  Git branch SQL
- Charles :  Git branch Charles
- Mobile testing :  Git branch  MobileTesting
 
2. Запушить все ветки на внешний репозиторий : git push --all
3. В ветке Bag Reports сделать текстовый документ со структурой баг репорта : Git checkout BugReports;   cat > BugReports.txt
4. Запушить структуру багрепорта на внешний репозиторий : git add . + git commit ( i + comment + esc + :wq)   git push  origin BugReports
5. Вмержить ветку Bag Reports в Main : Git merge Main 
6. Запушить main на внешний репозиторий. Git push 
7. В ветке CheckLists набросать структуру чек листа. cat > README.md
8. Запушить структуру на внешний репозиторий > git add . +  git commit ( i + comment + esc + :wq)  +git push  origin CheckLists
9. На внешнем репозитории сделать Pull Request ветки CheckLists в main
10. Синхронизировать Внешнюю и Локальную ветки Main : git checkout main ;  git pull
