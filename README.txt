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

