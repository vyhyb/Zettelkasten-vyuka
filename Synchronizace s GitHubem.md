# Synchronizace s GitHubem

Pro synchronizaci s [GitHubem](https://github.com/) musíte mít ve svém počítači nainstalovaný [GIT](https://git-scm.com/https://git-scm.com/) s příslušnými odkazy PATH pro ovládání skrze příkazový řádek.

## Základní nastavení repozitáře
1. Nastavte lokální git repozitář
	1.1. vytvořte složku obsahující vaše silo

		mkdir my_vault
		cd my_vault

	1.2. založte lokální git repozitář

		git init

	1.3. vytvořte ve složce soubor a zkontrolujte stav repozitáře
	
		git status
	
	1.4. přidejte do repozitáře všechny soubory a vytvořte první commit
	
		git add .
		git commit -m "First commit!"

2. Vytvořte **soukromý** GitHub repozitář (**bez README a LICENCE** souborů)
3. Nahrajte lokální repozitář na GitHub

		git remote add origin https://github.com/<user>/<repo>.git
		git branch -M main
		git push -u origin main

K přihlášení je nutno vytvořit osobní přístupový token (Github-Settings-Developer settings-Personal access tokens-Create-(Select scopes - repo)) který je při ověření používaný místo klasického hesla.

K uložení přístupových údajů použijte

	git config --global credential.helper store

## Nastavení v Obsidianu
V Obsidianu je nutné pro automatické ukládání použít plugin `Git`. Zde je pouze nutné nastavit cestu k aplikaci `git.exe` (bez uživatelského rozhraní).

![[Pasted image 20240312113415.png]]
