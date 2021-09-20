# Skilvul-05-Git-and-Github

SOAL KEDUA ada pada : https://github.com/PutraHarianja/Skilvul-04-Git-and-Github-02-portfolio-and-cv

---
SOAL KETIGA
1. What does git clean do?
-> git clean merupakan undo command, seperti git reset da git checkout namun command git clean ini bekerja pada untracked files.

2. What do the -d and -f flags for git clean do?
-> -f menghapus untracked files dari directory yang sekarang selain untracked folder atau file yang dispesified oleh .gitignore. Sementara -d digunakan untuk menghapus untracked directory dimana dapat dikombinasikan dengan yang lainnya menjadi -dn ataupun -df.

3. What git command creates a branch?
-> by using git brach command

4. What is the difference between a fast-forward and recursive merge?
-> Merge commitnya terus memiliki 2 parents. Kurang lebih tidak ada yang benar atau salah dari keduanya namun fast-forward kita memiliki straight line of history sedangkan recursive merge beberapa baris.

5. What git command changes to another branch?
-> by using git checkout

6. How do you remove modified or deleted files from the working directory?
-> by using git reset --hard atau jika menghapus sampai pull sebelumnya git stash

7. What git command deletes a branch?
-> by using git branch -d <local-branch> atau jika pada remote by using git push origin --delete <remote-branch-name>

8. What does the git diff command do?
-> menunjukkan perbedaan antara working tree dengna index, perubahan antara index dan tree, perubahan antara 2 tree, perubahan yang terjadi akibar merge atau perubahan antara 2 dile dalam disk.

9. How do you remove files from the staging area?
-> by using git reset

10. How do merge conflicts happen?
-> biasanya terjadi saat 2 orang melakukan perubahan pada line yang sama di suatu file, atau satu developer melakukan delete file sementara developer lagi melakukan modifikasi terhadapnya. 


REFERENSI
https://www.w3docs.com/learn-git/git-clean.html
https://git-scm.com/docs/
https://www.atlassian.com/git/tutorials/using-branches/merge-conflicts
  
  
---
  SOAL KEEMPAT
1. What is the difference between git reset and git revert. When would you use one over the other?
-> git revert : membuat commit baru yang mengundo perubahan dari comit sebelumnya. Command ini menambahkan history baru pada proyek tanda memodifikasi yang sebelumnya.

git reset : memodifikasi index yang dimana selain itu dia juga mengubah history yang ada. 

git revert digunakan saat : jika commit sudah dilakuakn pada proyek history namun kita memutuskan commit itu salah dan harusnya tidak dilakukan. 

git reset digunakan saat : jika kita punya commit namun belum dibagikan dengan orang lain, dan kita memutuskan bahwa kita tidak menginginkan hal tersebut. 


2. What is the difference between git merge and git rebase. When would you use one over the other?
-> Saat ada 2 developer yang melakukan commit terhadap satu hal akan terjadi konflik, hal ini dapat diselesaikan dengan 2 cara yaitu: Merge dan Rebase. Merge membentuk diamond shape dimana yang dimana mewarisi perubahan dari kedua commit tersebut, sedangkan Rebase  menghilangkan salah satu dari commit tersebut seolah olah salah satunya itu tidak ada. 
Rebase dapat dilakukan saat salah satu commit tersebut harusnya tidak pernah dicommit oleh developernya, sehingga keuntungan dengan memakai rebase tidak adanya diamond shape seperti pada Merge yang membingungkan dan historynya menjadi lebih jelas. 

3. What is the difference between git stash pop and git stash apply. When would you use one over the other?
-> git stash pop membuang (topmost) stash setelah menerapkannya, dimana git stash apply meninggalkannya di stash list untuk kemungkinan dipakai kembali nantinya. 
git stash pop dapat dilakukan jika kita ingin melakukan apply dan sekalian mendropnya(it stash apply && git stash drop) 

4. What kinds of things can you do in interactive mode when rebasing?
-> Ada 2 mode dalam git rebase yaitu standard dan --interactive. Dimana pada interactive mode keuntungannya adalah mengubah individual commit pada process. tanpa harus memindahkan semua commit pada base yang baru. Dengan mode ini anda dapat membersihkan history dengan menghapus dan mengubah sequence dari commit yang sudah ada. 


REFERENSI:
https://stackoverflow.com/questions/8358035/whats-the-difference-between-git-revert-checkout-and-reset#:~:text=For%20this%20reason%2C%20git%20revert%20should%20be%20used,restore%20one%20file%2C%20you%20can%20use%20git%20checkout.

https://stackoverflow.com/questions/16666089/whats-the-difference-between-git-merge-and-git-rebase

https://stackoverflow.com/questions/15286075/difference-between-git-stash-pop-and-git-stash-apply

https://www.w3docs.com/learn-git/git-rebase.html#the-difference-between-git-rebase-standard-and-git-rebase-interactive-7
