# LuaCeption
Intégration de Lua dans des programmes C , C++ , C#

Pour installer les dépendances sur Linux 
```bash
sudo apt install liblua5.3-dev
```
Pour compiler le main d'exemple
```bash
gcc -I/usr/include/lua5.3 -o main main.c -llua5.3 -lm
```
## Pourquoi ?
Lua est utiliser depuis toujours dans différents moteur de jeu pour:

	 - sa facilliter d'intégration
	 - sa simplicité 
	 - sa vitesse d'éxécution
Ce repo a pour but d'expliquer comment créer une API de modding dans un futur moteur de jeu.
