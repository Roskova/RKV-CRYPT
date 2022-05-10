![Logo](https://raw.githubusercontent.com/Roskova/RKV-CRYPT/main/logo.png)
# RKV-CRYPT
### Logiciel de cryptage modulaire par ROSKOVA
**RKV-CRYPT est un logiciel de cryptage modulaire développé par ROSKOVA** qui a pour but de permettre à n'importe qui sans expérience en informatique de crypter des messages de façon sécurisés. Le Cryptage (lorsque le projet sera final) offert par RKV-CRYPT est particulièrement efficace contre les attaques grâce à sa grande modularité permettant de combiner différentes méthodes de chiffrement tant symétrique qu'asymétrique rendant ainsi les attaques inefficaces. Le principe de RKV-CRYPT est de permettre à l'utilisateur de choisir lui-même comment il veut que le logiciel crypte le message (plusieurs couches de cryptage modulaire sont appliquées au message). Le logiciel est standalone ou peut-être utilisé conjointement avec le fichier config.txt permettant de personnaliser l'interface.

### Refonte de RKV-CRYPT (2.0)
La structure de RKV-CRYPT est en cours de refonte complète. La version 1.x n'étant pas fondée en POO, cela rend l'ajout de fonctionnalité particulièrement compliqué et empêchait la compréhension et le travail d'équipe efficace (même si je travaille seul sur le projet actuellement). Une version fonctionnelle de RKV-CRYPT 2.x devrait être disponible d'ici août 2022.

### Arborescence du dossier de configuration (OBSOLÈTE)
```txt
 ./
	Config/
		Interface.txt+
		Table.txt+
		Config.txt+
		Module.txt+
	Module/
		Numerisation/
			Config.txt
			Table.txt
			Interface.txt
		Block4plus/
			Config.txt
			Interface.txt
		Numerisation.dll
		Block4plus.dll
	Docs/
		RKVCRYPT_manual_fr-ca.pdf+
		RKVCRYPT_manual_en.pdf*
 RKVCRYPT.exe
 README.txt*
```
______________________________________________________________________

Les fichiers marquer * sont optionnel et n’affecte pas la fonctionnalité de RKVCRYPT.

Les fichiers marquer + sont obligatoire et seront autogénéré lorsque manquant. Cela réinitialise les modifications apporter à ceux-ci.
