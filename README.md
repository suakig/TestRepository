 こののサイトを見て作った

githubの使用方法
http://www.openrtm.org/openrtm/ja/node/1607

SSH認証キーをBitbucket/GitHubに設定しよう！ [Mac簡単手順]
http://morizyun.github.io/blog/ssh-key-bitbucket-github/


パスフレーズは省略したので何も入れてないがいちようこれも

ssh-agent でパスフレーズの入力を省く
http://webos-goodies.jp/archives/50672669.html

これ便利

pbcopy

pbpaste > text.txt
ファイルの中身コピーしてくれる

pbcopy < ~/.ssh/id_rsa.pub





➜  Study git:(feature/branch) ✗ git commit                     
[feature/branch bfc3ea2] README.md modify
 Committer: 大濱泰明 <Ohamayasuaki@oohamayasuaki-no-MacBook-Pro.local>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly:

    git config --global user.name "Your Name"
    git config --global user.email you@example.com

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 1 file changed, 23 insertions(+)
Study git:(feature/branch) git config --global user.name "suakig"
Study git:(feature/branch) git config --global user.email suakig@gmail.com



