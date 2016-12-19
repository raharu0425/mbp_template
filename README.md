先にやらないといけないこと 

xcode入れて、
brewいれて、
ansibleいれて、

 ~/.sshフォルダ作成
$ mkdir -p ~/.ssh
$ cd ~/.ssh
$ key-gen -t rsa

これで作成されたkeyをgithubに登録する

一回playbookをながしたらviをひらいて
:NeoBundleInstall!

そしてこれ
/Users/raharu/.vim/bundle/vimproc
 make
