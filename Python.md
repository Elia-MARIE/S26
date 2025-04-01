# Cours Python - 31/03/25
## Rappels
MARC DUCOBU
<br>
### Installation et initialisation
1. Installation Ubuntu (PowerShell)
   - > wsl.exe --install Ubuntu-24.04
3. Création d'un dossier dans home/emarie
4. Dépôt des notebooks dans le dossier python-m3 (Terminal Ubuntu)
   - $ sudo snap install --classic astral-uv
   - $ uv
   - $ pwd
   - $ mkdir python-m3
   - $ cd python-m3/
   - $ ls
   - $ uv init
   - $ uv add jupyter
   - $ uv run jupyter notebook
5. Ouverture du notebook

# Cours Python - 01/04/25
MARC DUCOBU
<br>

### Ajout de Spyder (Terminal Ubuntu)
- $ uv add spyder
- $ uv run

### Résolution des erreurs Qt et lancement de Spyder avec uv (Debian/Ubuntu)
**Problème rencontré :**
Spyder ne se lançait pas, avec des erreurs comme :
- Could not load the Qt platform plugin "xcb"
- ImportError: libsmime3.so: cannot open shared object file
- ImportError: libasound.so.2: cannot open shared object file
<br>
**Solution complète :**
1. Installer les bibliothèques Qt nécessaires :
   - $ sudo apt install qt5dxcb-plugin libqt5gui5 libqt5core5a libxcb-xinerama0 libgl1
2. Installer la bibliothèque de sécurité requise :
   - $ sudo apt install libnss3
3. Installer la bibliothèque audio (version t64) :
   - $ sudo apt install libasound2t64
<br>
**Relancer Spyder :**

   - $ uv run spyder
