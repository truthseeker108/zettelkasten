Cím: a GIT alapjai

A git egy olyan elosztott verziókövető rendszer, ami snapshotokat készít az aktuális állapotról,
a commitek tartalmáról hash azonosít képez és azokat irányított körmentes fában (DAG)tárolja.  
A snapshot készítést commitnak nevezzük. 
A branch a git esetében egy mutató, amivel a DAG-ban egy új elágazást tudunk létrehozni, 
így egy új fejlesztési ágat kapunk párhuzamos fejlesztés céljából. 
Ez a mutató szabadon mozgatható a commitok között.
A HEAD egy olyan speciális mutató, ami alapesetben az éppen aktuálisan checkoutolt branchre mutat. 
A HEAD közvetlenül is mutathat egy commitra,ezt detached HEAD állapotnak nevezzük. 
Egy commit checkoutolása után  a munkakönyvtár a HEAD által kijelölt commitnak megfelelő állapotban van. 
A mutatók mozgatását végző git parancsok alapesetben innen fogják kezdeni a DAG bejárását. 
A staging area/index  azoknak a fájloknak az átmeneti tárolója, amit a következő commitba szeretnénk belefoglalni.
A remote repository ugyanannak a git projektnek egy másik helyen tárolt másolata, 
ami eltérő commitokat és brancheket is tartalmazhat. 
Bár kinevezhetünk egy távoli repositoryt központinak, ez technikaliag ugyanolyan git repository, mint bármelyik lokális, 
mindössze annyi a különbség, hogy a lokális változatokat ehhez a "központi" repositoryhoz szinkronizáljuk. 

#versionning, #top10DevopsTool, #CICD, #IaC
