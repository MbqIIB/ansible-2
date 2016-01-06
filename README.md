# ansible-master
# kuidas giti kasutada ansible failide üleslaadimiseks:

# Paigalda GIT:
   1. $ sudo apt-get install git #install 
   2. $ git config --global user.name "asjalik" #kasutajanimi 
   3. $ git config --global user.email "laidma27[at]gmail.com" #email 
   4. $ git init #initializeb directoryt kus asud 
   5. $ git add . #lisbab kõik mis directorys on
   6. $ git add README.md #lisab kindla faili 
   7. $ git commit -m "Ansible" 
   8. $ git remote add origin https://github.com/asjalik/ansible-master.git #addib remotesse 
   9. $ git push origin master #pushib failid kõik üles gi 

#KUIDAS UPDATE FAILE:
   1. $ git commit #näitab ära mida saab commitida
   2. $ git commit -am "Adding tutorial" #kcommit kirjeldu 

# Genereeri ssh-key, kui sul seda pole:
   1. ssh-keygen -t rsa
   2. Võtit saad näha ~/.ssh/id_rsa.pub

# To configure your GitHub account to use your SSH key:
   1. In your favorite text editor, open the ~/.ssh/id_rsa.pub file.
   2. Select the entire contents of the file and copy it to your clipboard. Do not add any newlines or whitespace.

# Add the copied key to GitHub:
   1. In the top right corner of any page, click your profile photo, then click Settings. 
   2. In the user settings sidebar, click SSH keys.
   3. Click Add SSH key. 
   4. In the Title field, add a descriptive label for the new key. For example, if you're using a personal Mac, you might call this key "Personal MacBook Air".
   5. Paste your key into the "Key" field. 
   6. Click Add key. 
   7. Confirm the action by entering your GitHub password.
