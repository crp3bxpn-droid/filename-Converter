# filename-Converter
webサービステスト公開<br>
・チャットGPTを使用して作成<br>
<br>
◻️環境準備<br>
・firefoxを使用して運用することを想定<br>
  chrome系のブラウザは使用上ファイル同時ダウンロード数が10ファイルまでのため。<br>
・firefoxの設定を変更して同時ダウンロード数を変更する。<br>
  本サービスは50件のファイルを同時に変更可能なため50と設定するのを推奨。<br>
  <br>
【firefoxの場合の設定方法】<br>
1.about:configを開く<br>
  Firefoxのアドレスバーに about:config と入力し、Enterキーを押します。<br>
  警告画面が表示されたら、「危険性を承知の上で続行」をクリックします。<br>
2.パラメータを検索・変更<br>
  検索ボックスに network.http.max-persistent-connections-per-server を入力し、該当する設定項目を探します。<br>
  右側の鉛筆アイコンをクリックして数値を変更し、チェックマークをクリックして保存します。 <br>
  <br>
◻️使用方法<br>
・SKU欄に変更後のファイル名を入力。<br>
・画像1〜5欄に画像ファイルをアップロード<br>
  間違えてアップロードした場合は削除できないので注意が必要<br>
・ダウンロードボタンをクリックすることでダウンロードが開始される<br>
  SKU欄に記載した値_1~5.選択した画像拡張子の形式にファイル名が変換される<br>
<br>
◻️ページURL<br>
https://crp3bxpn-droid.github.io/filename-Converter/
