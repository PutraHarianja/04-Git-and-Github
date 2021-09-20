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



https://www.w3docs.com/learn-git/git-clean.html
https://git-scm.com/docs/
https://www.atlassian.com/git/tutorials/using-branches/merge-conflicts
  
  
---
