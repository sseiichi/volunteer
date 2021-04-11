ここでは入力システムの一連の操作方法を説明しています。入力欄に具体的にどのようなデータを入力するかについては、「2. 個別の入力欄の説明」と「3. 共通の入力規則」のページをご覧ください。

#### 1. ブラウザで管理画面のURLを開くと、ログイン画面が表示されます。ユーザー名とパスワードを入力して「ログイン」ボタンをクリックします。
![](https://raw.githubusercontent.com/sseiichi/volunteer/main/docs/images/login.png)

#### 2. ログインすると次のような画面が表示されます。Booksをクリックします。

![](https://raw.githubusercontent.com/sseiichi/volunteer/main/docs/images/adminsite01.png)

#### 3. 現在登録されている図書データの一覧が表示されます。表の列名をクリックすると図書をソートできます。同じ列名をもう一度クリックするとソート順を逆にできます。フィルター項目をクリックすると、図書を絞り込めます。

![](https://raw.githubusercontent.com/sseiichi/volunteer/main/docs/images/adminsite02.png)

#### 4. 検索フォームに文字列を入力して「検索」ボタンをクリックすると、その文字列を「Title」と「Content ID」に含む図書が表示されます。

![](https://raw.githubusercontent.com/sseiichi/volunteer/main/docs/images/adminsite02.1.png)

#### 5. ソート、フィルター、検索フォームを使用して入力したい図書を探してください。画像では例として「12歳」で検索して「12歳からはじめるゼロからのPythonゲームプログラミング教室」を表示させてみました。

![](https://raw.githubusercontent.com/sseiichi/volunteer/main/docs/images/adminsite03.png)

#### 6. 書名をクリックすると「bookを変更」という画面に遷移します。「一部」ボタンを押すと、図書の一部が表示されるウインドウが新しく開きます。

![](https://raw.githubusercontent.com/sseiichi/volunteer/main/docs/images/adminsite04.png)

#### 7. 「Preview」ウインドウには図書の一部（前半の一部と後半の一部）が表示されます。ページ番号の下にページの画像が表示されます。この「Preview」ウインドウからタイトル、著者名、ISBNなどの書誌情報を読み取って、「bookを変更」画面の入力欄に入力してください。

ページ番号の**下**に対応するページの画像があることにご注意ください。

![](https://raw.githubusercontent.com/sseiichi/volunteer/main/docs/images/adminsite05.png)

## 入力中に不明点、判断に迷う点、エラーが発生した時
「bookを変更」画面内にある「Need recheck later」というチェックボックスにチェックを入れて、「Comments」欄に、わからなかった点、判断に迷った点、エラー内容を記載してください。「Need recheck later」というチェックボックスにチェックが入っていれば、後から管理者がその図書をチェックします。

![](https://raw.githubusercontent.com/sseiichi/volunteer/main/docs/images/adminsite16.png)

## ISBNから書籍情報を取得する方法
ISBNが記載されている書籍であれば、ISBNから書誌情報を取得して保存できます。ISBNが記載されている書籍では、この機能を使用して入力の手間を軽減してください。

#### 1. ISBNを入力して「検索」ボタンをクリックします。ISBNはハイフンつきで入力してもかまいません。ハイフンは自動で除去されます。ISBNの桁数は10桁でも13桁でも構いません。検索には2分程度かかることがあります。

![](https://raw.githubusercontent.com/sseiichi/volunteer/main/docs/images/adminsite06.png)

#### 2. 検索に成功すると「検索」ボタンの下に取得したデータが表示されます。データに問題がなければ「検索結果で上書き保存」ボタンが表示されます。このボタンをクリックすると書籍情報が取得したデータで上書きされます。

![](https://raw.githubusercontent.com/sseiichi/volunteer/main/docs/images/adminsite07.png)

#### 3. 「no search results?」と表示された時は、国会図書館にデータがありません。この場合はGoogle検索で書籍情報を探してください。

![](https://raw.githubusercontent.com/sseiichi/volunteer/main/docs/images/no_search_results.png)

#### 4. 取得したデータフォーマットに未対応の場合は、取得したデータの最後に「error」と表示されて、「検索結果で上書き保存」ボタンが表示されません。管理者に連絡して、別の図書の情報入力を進めてください。

![](https://raw.githubusercontent.com/sseiichi/volunteer/main/docs/images/adminsite08.png)

## 著者、翻訳者、編集者の入力方法
著者、翻訳者、編集者は、事前に登録された人物名から選択して入力する方式になっています。
#### 1. 「Authors」、「Translators」、「Editors」のテキストボックスに文字を入力すると、登録済みの人物名から候補が表示されます。表示された候補のうち、入力したいものをクリックすると入力されます。
![](https://raw.githubusercontent.com/sseiichi/volunteer/main/docs/images/adminsite09.png)

#### 2. 入力された人物名はテキストボックスの下に表示されます。削除したい場合は、テキストボックスの下の人物名をクリックすると削除されます。
![](https://raw.githubusercontent.com/sseiichi/volunteer/main/docs/images/adminsite10.png)

## 登録済みの著者、翻訳者、編集者の確認方法
#### 1. 既に登録されている著者、翻訳者、編集者を確認するには、画面左に表示される「Persons」をクリックします。
![](https://raw.githubusercontent.com/sseiichi/volunteer/main/docs/images/adminsite11.png)

ウインドウサイズを小さくしている場合、画面左のメニューが隠れているので画面左の「<<」ボタンを押して表示させてください。
![](https://raw.githubusercontent.com/sseiichi/volunteer/main/docs/images/expand_button.png)

#### 2. 「変更するpersonを選択」という画面で、登録済みの人物名を確認できます。
![](https://raw.githubusercontent.com/sseiichi/volunteer/main/docs/images/adminsite11.1.png)

## 著者、翻訳者、編集者の登録方法
#### 1. 「変更するpersonを選択」画面の右上にある「PERSONを追加」ボタンを押すと、人物名の登録画面に移動します。

![](https://raw.githubusercontent.com/sseiichi/volunteer/main/docs/images/add_person_button.png)

#### 2. 人物名の登録画面が表示されます。
入力項目の意味は次のとおりです。
* Last name: 苗字
* First name: 下の名前
* Last name transcription: 苗字のヨミガナ
* First name transcription: 下の名前のヨミガナ
* Middle name: ミドルネーム（ある人だけ）
* Middle name transcription: ミドルネームのヨミガナ（ある人だけ）
* Note: 同姓同名の人物を区別できる情報。生年など。(例)1934-

transcriptionには名前のヨミガナを全角カタカナで入力してください。外国人の名前の場合ヨミガナを振るのは難しいと思うので空白でかまいません。著者がグループや団体だったり、苗字が不明な場合はFirst nameだけを入力してください。

![](https://raw.githubusercontent.com/sseiichi/volunteer/main/docs/images/adminsite13.png)

## 出版社の入力方法
出版社は、事前に登録された会社から選択して入力する方式になっています。

#### 1. 「Publishers」のテキストボックスに文字を入力すると、登録済みの会社から候補が表示されます。表示された候補のうち、入力したいものをクリックすると入力されます。
![](https://raw.githubusercontent.com/sseiichi/volunteer/main/docs/images/adminsite17.png)

## 登録済みの会社の確認方法
#### 1. 既に登録されている会社を確認するには、画面左に表示される「Companies」をクリックします。
![](https://raw.githubusercontent.com/sseiichi/volunteer/main/docs/images/adminsite18.png)

ウインドウサイズを小さくしている場合、画面左のメニューが隠れているので画面左の「<<」ボタンを押して表示させてください。
![](https://raw.githubusercontent.com/sseiichi/volunteer/main/docs/images/expand_button.png)

#### 2. 「変更するcompanyを選択」という画面で、登録済みの会社を確認できます。
![](https://raw.githubusercontent.com/sseiichi/volunteer/main/docs/images/adminsite19.png)

## 会社の登録方法
#### 1. 「変更するcompanyを選択」画面の右上にある「COMPANYを追加」ボタンを押すと、会社の登録画面に移動します。

![](https://raw.githubusercontent.com/sseiichi/volunteer/main/docs/images/add_company_button.png)

#### 2. 会社の登録画面が表示されます。
入力項目の意味は次のとおりです。
* Name: 会社名
* Location: 会社の所在地。都道府県まででOKです
* Description: 入力不要です
* Note: 入力不要です
![](https://raw.githubusercontent.com/sseiichi/volunteer/main/docs/images/adminsite20.png)

## Tagの入力方法
#### 1. Tagsには他のフィールドに収まらない追加情報を入力します。また、[パロディ元作品名を入力してください](https://github.com/sseiichi/volunteer/wiki/2.-%E5%80%8B%E5%88%A5%E3%81%AE%E5%85%A5%E5%8A%9B%E6%AC%84%E3%81%AE%E8%AA%AC%E6%98%8E#tags)

#### 2. 登録済みのTagが候補としてリスト表示されているので、Tag名をクリックして選択します。複数選択するときには Control キーを押したままTag名をクリックしてください。Mac は Command キーを使ってください。
![](https://raw.githubusercontent.com/sseiichi/volunteer/main/docs/images/adminsite22.png)

#### 3. 選択解除するときは Control キーを押したままTag名をクリックしてください。
![](https://raw.githubusercontent.com/sseiichi/volunteer/main/docs/images/adminsite23.png)

## 登録済みのTagの確認方法
#### 1. 既に登録されているTagを確認するには、画面左に表示される「Tags」をクリックします。
![](https://raw.githubusercontent.com/sseiichi/volunteer/main/docs/images/adminsite26.png)

ウインドウサイズを小さくしている場合、画面左のメニューが隠れているので画面左の「<<」ボタンを押して表示させてください。
![](https://raw.githubusercontent.com/sseiichi/volunteer/main/docs/images/expand_button.png)

#### 2. 「変更するtagを選択」という画面で、登録済みのTagを確認できます。
![](https://raw.githubusercontent.com/sseiichi/volunteer/main/docs/images/adminsite27.png)

## Tagの登録方法
#### 1. 「変更するtagを選択」画面の右上にある「TAGを追加」ボタンを押すと、タグの登録画面に移動します。
![](https://raw.githubusercontent.com/sseiichi/volunteer/main/docs/images/add_tag_button.png)

#### 2. タグの入力項目はNameだけです
![](https://raw.githubusercontent.com/sseiichi/volunteer/main/docs/images/adminsite28.png)

## 入力した目次や奥付のページ番号が合っているかの確認
以下の手順で、入力した目次や奥付のページ番号が合っているか、確認してください。

#### 1. Disabledのチェックボックスを外してください。Disabledがチェックされていると、図書が表示されなくなり、表示の確認ができません。
![](https://raw.githubusercontent.com/sseiichi/volunteer/main/docs/images/adminsite21.png)

#### 2. Disabledのチェックボックスを外したら、一度「保存して編集を続ける」ボタンを押して保存してください。保存しないとチェックボックスの変更が反映されません。

#### 3. Disabledのチェックボックスを外して保存した後、Overview Windowという所の「確認」ボタンを押すと、入力した書誌情報がどのように表示されるか、ウインドウが開いて実際に確認できます。
![](https://raw.githubusercontent.com/sseiichi/volunteer/main/docs/images/adminsite24.png)

## データ保存方法
「bookを変更」画面の一番下にある、「保存して編集を続ける」ボタンか「保存」ボタンを押すと保存できます。サムネイル画像のファイルサイズが1MB以上だと、アップロード時に「413 Request Entity Too Large」というエラーが出て、保存されていないデータが全部消えてしまいます。サムネイル画像を登録するまえに一度保存しておくのがよいでしょう。
![](https://raw.githubusercontent.com/sseiichi/volunteer/main/docs/images/adminsite25.png)


## 入力を忘れやすい所
Volume

Disabled

Tags

を忘れやすいみたいです。保存前にご確認ください。
