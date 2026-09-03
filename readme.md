# Gidder ikke å oppdatere profilen med informasjon om meg selv enda
## Deler heller ut step-by-step guide for hvordan man lager en markdown fil å pusher den til repoen på github

## Fra terminalen på pcen:
1. -> Brukte først cd 'Onedrive/Skrivebord' (For å komme til skrivebordet på pcen, som forsåvidt er lagret i onedrive)
2. -> Så mkdir 'ProfilRepoGitHub' (lager en ny mappe på skrivebordet)
3. -> Så touch 'readme.md' (lager en markdown fil med navn readme)
4. -> Git init (initiate at her skal det være en repo)
5. -> Så gikk jeg hit å redigerte den (altså i visual studio code)
6. -> Save markdown filen lokalt på pcen i mappen (ctrl+s)
7. -> git status
8. -> git add readme.md / kan også bruke git add .
9. -> git commit -m 'Første endring i readme filen til profilen' (FOR Å LOGGE ENDRINGEN)
10. -> git log (for å dobbeltsjekke :)
11. Så lage en repo på github - å kjøre kommandoene: (som står når man lager en repo på github)
12. git remote add origin https://github.com/elRobz/elRobz.git
13. git branch -M main
14. git push -u origin main

15. done, oj, må jo lagre endringene å pushe ut igjen! ctrl+s, git status, git add (navn), git commit -m (endring), git push