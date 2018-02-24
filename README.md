# RubyArray
配列

## 処理
配列の内容をeach_with_indexメソッドを使って順次読み出し出力します。

## コード
```
team = ["佐藤","鈴木","田中","岸田","有森"]
team.each_with_index do |name|
    puts "#{name}さん"
end
```
上記の他にも
```
team = ["佐藤","鈴木","田中","岸田","有森"]
for i in team
    puts "#{i}さん"
end
```
などでも同じことが出来る。

## 出力結果  
```
佐藤さん
鈴木さん
田中さん
岸田さん
有森さん
```
  
## 開発環境
| 開発ツール |  |
|:-|:-|
| OS | Windows10 |
| 仮想化ソフト | Oracle VM VirtualBox 5.2 |
| 構築ソフト | Vagrant 2.0.2 |
| 仮想化上OS | CentOS 6.9 |
| SSHクライアント | PuTTY 0.6.8 |
| FTPクライアント | Cyberduck 6.3.5 |
| エディタ | Atom 1.24.0 |
| 開発言語 | Ruby 2.4.0 |
