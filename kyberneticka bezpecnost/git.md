- Linus Torvalds
- byl to jeho vedlejší projekt vedle linuxu

### Klíče
- když jsem v linuxu tak se nacitaji klice z ~/.ssh
- do githubu nebo gitlabu se musí vkládat .pub klíč
	- .pub značí public (veřejný klíč, [[Šifrování#asymetrické|asimetrické]] šifrování)
	
při `git push`  z terminalu musí být nastaveno git@github.com:jmenoNaGithubu/repozitar.git jinak by se mohlo stat ze se informace budou nacitat na webouvou verzi

---


### Configurace
1. `git config --global user.name "Nastaví jmeno ktere se potom bude ukazovat u commitů"`


### Nový repozitář

1. Začneme nějakým souborem/složkou například README.md ![[typy souborů a konverze#.md|.md file]]
2. nasladně inicijalizujeme git pomoci `git init`
	- to vytvoří .git file, který vpodstatě říká že se má použivat git
	- od této chvíle se začínají zaznamenávat git příkazy

3. přidáme soubory, které následně budeme commitovat
	- řekne které soubory zahrnout a které ne
	`git add .` - přidání všech souborů
	

4.  `git config --global user.name "Vaše jméno" git config --global user.email "vas@email.cz"`

5. `git remote add origin <URL vzdáleného repozitáře>`

---
### Cloning repozitorářů

- jak název vypovídá kopíruje vzdálený nebo lokální repozitář
- vhodné například při stahování z githubu/gitlabu
- `git clone 'cesta k repozitáři' 'lokální název (není nutný)`