Start Git

git init

git config --global user.email "gsgang@2sumdata.com"
git config --global user.name "Method-G"

git add README.txt

git commit -m "사이트 설명 추가"

gangsim@GSGANG-2SUMDATA MINGW64 /d/GitTest/iTshirt-cat (master)
$ git commit -m "사이트 설명 추가"
[master (root-commit) 227230d] 사이트 설명 추가
 1 file changed, 6 insertions(+)
 create mode 100644 README.txt

-- 여기까지가 첫번쨰 commit

git add README.txt

git commit -m "설명 업데이트"




git log
commit 06c51cb33b7599b89a42fd33f2c758c4032f4d4d (HEAD -> master)
Author: Method-G <gsgang@2sumdata.com>
Date:   Thu Jan 7 16:41:43 2021 +0900

    설명 업데이트

commit 227230d4642980ecedf98405a8d910916a871545
Author: Method-G <gsgang@2sumdata.com>
Date:   Thu Jan 7 16:38:53 2021 +0900

    사이트 설명 추가

git checkout 227230d

git add README.txt

git commit -m "Checkout이전까지저장"

git remote add origin https://github.com/Method-G/iTshirt.git

git push origin master
gangsim@GSGANG-2SUMDATA MINGW64 /d/GitTest/iTshirt-cat ((c20a4df...))
$ git push origin master
Enumerating objects: 12, done.
Counting objects: 100% (12/12), done.
Delta compression using up to 4 threads
Compressing objects: 100% (8/8), done.
Writing objects: 100% (12/12), 1.40 KiB | 477.00 KiB/s, done.
Total 12 (delta 3), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (3/3), done.
To https://github.com/Method-G/iTshirt.git
 * [new branch]      master -> master

git clone https://github.com/Method-G/iTshirt.git .

<iTshirt-oct 폴더에서 작업한 내용>
git add README.txt

git commit -m "new job in oct floder"

git push origin master