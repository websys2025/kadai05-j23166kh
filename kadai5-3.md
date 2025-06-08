## 外部APIの呼び出しのミニレポート
### Q3-1. 郵便番号APIについて説明せよ。
* エンドポイントと機能
https://zipcloud.ibsnet.co.jp/api/search
郵便番号からそれに対応する住所を出力する。
* リクエストとレスポンスのフォーマット　
?zipcode=
address
### Q3-2. 各自で調査したAPIについて説明せよ。
* APIの名称と参照URL
Yes/No API
https://yesno.wtf/
* エンドポイントと機能
https://yesno.wtf/api
実行を押すとYesかNo、Maybeのどれかで返答する。
選ばれた返答にあったGIFも一緒に表示される。
* リクエストとレスポンスのフォーマット
fetch('https://yesno.wtf/api')
answer、image
### Q3-3. 感想
* 今回の課題で苦労したこと　API取得するためのコーディング。
* 演習を通して理解できたこと　APIの面白さ
* Web APIの利便性や課題など　取り扱いに注意する必要がある。
