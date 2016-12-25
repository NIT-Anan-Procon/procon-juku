#毎週金曜日に開催予定の勉強会で使うリポジトリのはず  
  
  冬休み中の課題 : Gitを使ってみよう  
index.htmlを書き換えて, 自分のページに飛ばすリンクを貼るなどする.  
注意)
まず自分用のディレクトリを作成して, そのディレクトリ内にファイルを作成すること.  
  
  
1.その前にGitHubのアカウントを作成(プロコンのorganizationに招待します).  
2.ターミナルを開いて  
`$ git`  
not found 的なエラーが出た時に  
  
Mac  
`$ brew install git`  
  
Linux  
`$ apt-get install git`
  
で多分大丈夫  
  
  
3.ユーザー情報を登録  
`$ git config --global user.name "John Doe"` user name  
`$ git config --global user.email johndoe@example.com` e-mail  
  
4.GitHubからリポジトリをローカルに持ってくる  
`$ git clone https://github.com/NIT-Anan-Procon/procon-juku.git`
  
5.あとは勉強会のときにやった手順で  
質問があればSlackまで  
  
  
参照  
---
https://git-scm.com/book/ja/v1/Git-%E3%81%AE%E3%82%AB%E3%82%B9%E3%82%BF%E3%83%9E%E3%82%A4%E3%82%BA-Git-%E3%81%AE%E8%A8%AD%E5%AE%9A
