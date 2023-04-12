# printer_supplies
機種変更後のプリンター消耗品について、過去5年の実績に基づき年間需要量を見込むもの。
ベースとなるデータはcsvではなく、excelでつくって、作業の時にデータフレームにすることにした。
ssh接続がうまくいかない
ようわからない

RstudioのProject optionsのGit/SVNのタブで
originの欄が
https://github.com/iotsuka1958/printer_supplies.git
となっていたので、それを
git@github.com:iotsuka1958/printer_supplies.git
とすればいいと見込んだがorigin欄がグレーアウトしていて直接入力ができない。
そこでchatGPTに質問したらうまくいった。
./git/configのurl = 以下を
git@github.com:iotsuka1958/printer_supplies.git
に修正したらうまくいった。
RstudioのProject optionsのGit/SVNのタブで
originの欄が書き換わっていた。
めでたし。

とおもったが、そもそも職場のパソコンはsshがうまくいかない。
これはgithubの問題ではなさそう。
./.git/configのurlをhttpsに戻した。
これはうまくいくので、とりあえずはこのままいく。
