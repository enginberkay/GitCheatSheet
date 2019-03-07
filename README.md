# GitDenemesi
Git komutları üzerine çalışma

git clone git_repo_url.git

git remote --verbose => remote reporları gösterir
git remote add <shortName> <url> => uzak repo bağlantısı ekler

Edit readme file

git status

git add readme.md
git add .

git commit -m "ilk commit"
git commit -a -m "yorum" => staged olmamış değişiklikleri dahil ederek check-in yapar

git push -u origin master

git status -s => liste halinde gösterir

git diff => staged dışında ki değişiklikler

git diff --staged yada git diff --cached => staged değişiklikler

git reset --hard HEAD => localde ki tüm değişiklikler HEAD versiyonuna döner

git revert => yapılan commiti geri alır (rollback)

git fetch origin => uzak repordaki değişiklikleri alır merge yapmaz

git pull origin => uzak repordaki değişiklikleri alır ve merge yapar

git branch => mevcut branchleri gösterir

git branch testing => testing branşı yaratır

git checkout testing => testing branşına geçer
git checkout -b testing => testing branşı yaratır ve geçiş yapar

git log --oneline => satır satır geçmişi gösterir
git log --oneline --decorate --graph --all

git merge testing => üzerinde çalışılan branch ile testing branchi merge edilir

git branch -d testing => testing branchi siler

git push origin --delete testing => remote branch silindi