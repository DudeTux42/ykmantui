Freitag 23.02.24

## Ablauf 

**1. Gliederung.**

1. Einführung in Begrifflichkeiten    
2. Installation    
3. Git    
4. GitHub

**2. Was ist Git**

- Versionskontrolle: Git ermöglicht das Verfolgen und Verwalten von Änderungen an Dateien über die Zeit, erleichtert Fehlerbehebung und Projektverlaufstracking.  
  
- Branching und Merging: Entwickler können isoliert neue Funktionen entwickeln und diese nahtlos in den Hauptcode integrieren.

 **3. Installation** 

1. Geh auf [www.git-scm.com/downloads](http://www.git-scm.com/downloads) und lade die windows version herunter,  
    für Linux nutze deinen Paketmager. Auf Mac-Os installiere Home-brew und schreibe
    brew install git ins terminal
2. Wechsle Standard branch zu main  

**4. Konfiguration**   ^a36452

1. Terminal öffnen
2. ``git config --global user.name <username>
3. ``git config –global user.email <Email>


**5. Lokales Repo erstellen** 
  

1. Im Terminal zu neu erstelltem Ordner navigieren.  
2. Git init  
3. Neue Datei im Ordner erstellen

**6. Status des Repos**

- ``git status

**7. Staging**

1. ``git add < . oder name von file>
2. Das Staging in Git ist wie eine Vorbereitungszone für deine Änderungen, bevor du sie endgültig speicherst, und "git add" ist der Befehl, mit dem du deine Änderungen dieser Vorbereitungszone hinzufügst.

**8. Commit**

1. ``git commit    
2. ``git

**9. Unterschiede zwischen Commits**

1. ``git log    
2. ``git show
   
**10. Branches**

1. Branch mit ``git branch <name> erstellen.    
2. Zu branch wechseln mit ``git checkout <name>    
3. Zu Master Branch wechseln (darauf hinweisen das die erstellte Datei nicht mehr da ist)    
4. Merge die beiden Branches mit ``git merge <feature>    
5. Branch löschen mit ``git branch -d <name>    

**11. Frühere version herstellen**

1. bis zu einem bestimmten commit (und file) alles zurücksetzten
2. ``git checkout <id> <path to file> 

**12. Einen Commit rückgängig machen**

- nur diesen einzelnen commit rückgänging machen
- Falls Tippfehler in message ``git commit --amend    
- Letzten Commit zurücksetzten ``git revert HEAD    
- Zu einem bestimmten Commit zurück gehen mit ``git revert <ID>  

**13. Remote Repo**

1. GitHub.com öffnen anmelden und neues Repo erstellen    
2. git remote add origin *link to GitHub*    
3. hinweise auf git ignore, public und private Repos.  

**14. Push/Pull**

- ``git push <name von Repo> <branch>  

**15. Git clone**

```shell
git clone <URL von remote Repo>

```


```js
let x = 1;

fn test(x){
	loop{
		println!({}, "Hello World!")
	}
};
```






```bash
sudp pacman -Syyu
```
