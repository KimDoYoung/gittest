git정리
====

##개념

소스를 만들때 local machine에 stage와  .git repository 가 있고 remote에 lab or hub가 있다.
stage를 HEAD라 부르는가?

> 소스 -> stage -> .git -> hub
> add , commit, remote add
> checkout은 HEAD에서 꺼내오기 
> reset HEAD hi.txt  HEAD에서 제거하기

- 소스관리이니 branch가 있다.
-기타 관리하기 위해서 .gitignore와 $HOME/.gitconfig가 있다.
- 관리되지 않는 untracking
- checkout은 HEAD에서 꺼내서 WF의 내용을 덮어쓴다.

## gitconfig

$ git config --global user.name "KimDoYoung"
$ git config --global user.email kdy987@gmail.com

## command

git status -s 
A : HEAD이 있다. M : 소스가 수정되었다.  ?? untracking이다. 

git log 
