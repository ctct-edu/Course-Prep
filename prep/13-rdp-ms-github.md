# CTC教育サービス

## Microsoft関連 コース ガイド

### ■対象コース

本ページでは以下のコースが対象となります。

| 項目                                                         |
| ------------------------------------------------------------ |
| [AZ-2007 GitHub Copilot を使用してアプリ開発を高速化する](https://www.school.ctc-g.co.jp/course/P776.html) |



### ■ご準備いただくもの

1. **RDP接続確認手順（※重要※）**

   演習ではリモートデスクトップ接続(RDP)を利用します。受講するPC環境からアクセスできるか確認をお願いします。

   > ※以下のキャプチャはWindows11の画面を掲載しています。

   a.Windowsのスタートメニューから「**リモート**」と検索し、「**リモートデスクトップ接続**」を選択します。

   <img src="./icon/rdp01.png" alt="rdp01" width="350pix"> 

   

    b.リモートデスクトップ接続画面に「**4.215.201.10**」と入力し、接続をクリックします。

   <img src="./icon/rdp02.png" alt="rdp02" width="400pix">　

   

   c.「**資格情報を入力してください**」と画面表示されます。これでRDP接続の確認は完了となります。

   　そのまま、画面を閉じてください。

   　<img src="./icon/rdp03.png" alt="rdp03" width="400pix">

   > ※ユーザー名とパスワードの入力、サインインする必要はありません。
   >
   > ※上記画面が表示されたことにより、RDP接続が出来ていることになります。

   

   **【RDP接続が上手くいかない場合】**

   RDP接続時にエラーが表示される場合があります。

   <img src="./icon/rdperror0.png" alt="rdperror0" width="500pix">　

   

   接続できない原因はいくつかあります。よくあるトラブルシュートは以下の通りです。

   | 項目                                                         | 詳細                                                         |
   | ------------------------------------------------------------ | ------------------------------------------------------------ |
   | <img src="./icon/Network.png" width="80pix">　<br>**ネットワークの変更** | 会社のネットワークからアクセスした場合、RDP接続を禁止する設定がファイヤーウォール等に<br />行われている可能性があります。別のネットワークから接続可能な場合、そちらからお試ししてご受講ください。 |
   | <img src="./icon/securepc.png" alt="securepc" width="80pix">　 <br>**使用するPC変更** | 会社貸与のPCでは、RDP接続が出来ない設定が行われている場合があります。<br />ご自身でお持ちのPCなど、他のPCからアクセスできるかお試しください。 |
   | <img src="./icon/VPN.png" alt="VPN" width="80pix">　 <br>**VPNの停止** | 業務で使用しているPCのVPNソフトが起動しているため、接続できない可能性があります。<br />VPNソフトを停止してお試しください。 |

   上記の対処でも接続できない、またはご用意できない場合もございます。

   その場合、AzureにはWebブラウザから仮想マシンにアクセスする機能でご提供することも可能です。

   弊社側で事前に準備する必要がございます。お手数ですが、**「受講案内メール」へのご返信**または**弊社の担当営業**へご連絡ください。

   なお、お客様にご準備いただくものはございません。受講当日はそのままご参加ください。

   ------

2. **Microsoftアカウントの作成(※重要※)**

   Microsoft認定コースを受講する場合、「**Microsoftアカウント**」が必須となります。

   以下の手順を参考にMicrosoftアカウントをご用意ください。

   > 既にMicrosoftアカウントをお持ちの方は、ご自身のアカウントをご用意ください。

   a.Microsoftアカウント (https://account.microsoft.com/) へアクセスします。

   

   b.画面中央にある「サインイン」をクリックします。

   <img src="./icon/MicrosoftAccount1.png"  alt="MicrosoftAccount1" width="450pix" />　

   

   c.サインイン画面で「アカウントをお持ちではない場合、作成できます。」をクリックします。

   <img src="./icon/MicrosoftAccount2.png" alt="MicrosoftAccount2" width="350pix" />　

   

   d.アカウントの作成画面でメールアドレスを入力して「次へ」または「新しいメールアドレスを取得」を選択します。

   | 項目                                  | 詳細                                                         |
   | ------------------------------------- | ------------------------------------------------------------ |
   | 新しいメールアドレスを取得 | Microsoftアカウントとメールアドレスを取得することが可能です。<br />ドメインは「outlook.com」「outlook.jp」「hotmail.com」から選択できます。|
   
   <img src="./icon/MicrosoftAccount3.png" alt="MicrosoftAccount3" width="350pix" />　

   

   e.パスワードを入力します。

   > ※パスワードを忘れた場合、ご自身で再設定する必要がございます。

   <img src="./icon/MicrosoftAccount4.png" alt="MicrosoftAccount4" width="350pix" />　

   

   f.「ロボットでないことを証明するために クイズに回答してください。」と表示されます。

   　画面に従ってパズルを解いてください。

   > ※パズルは複数パターンあります。

   <img src="./icon/MicrosoftAccount5.png" alt="MicrosoftAccount5" width="350pix" />　

   

   g.Microsoftアカウントの作成が完了し、Microsoftアカウントのホーム画面が表示されます。

   <img src="./icon/MicrosoftAccount6.png" alt="MicrosoftAccount6" width="500pix" />　

------

3. **GitHubにアカウントを登録する(※重要※)**
   
   作成したMicrosoftアカウントを使用して、GitHubにサインアップします。

   ※**個人PC**、**スマホ**などで作業してください。

   ①「<https://github.com/>」にアクセスします。

   ②画面右上の「**sign up**」をクリックします。

      <img src="./icon/GitHubSignUp-1.png" alt="MicrosoftAccount6" width="500pix" />


   ③「Sign up to GitHub」と表示されます。
   
   以下の必要項目を入力し「**Create account**」をクリックします。

   | 項目                      | 説明                                                           |
   | :---------------------- | :----------------------------------------------------------- |
   | **Email**               | 先ほど作成したMicrosoftアカウントのメールアドレスを入力してください。                                     |
   | **Password**            | パスワードを入力してください。<br>※パスワードは、最低15文字以上、または数字と小文字を含む8文字以上でなければなりません。 |
   | **Username**            | ユーザー名を入力してください。公開される表示名となります。                       |
   | **Your Country/Region** | 所属する国または地域を選択してください。                                         |
   | **Email preferences**   | 定期的な製品更新やお知らせを受け取るかどうかを選択します。チェックは不要です。                |

   <img src="./icon/GitHubSignUp-2.png" alt="MicrosoftAccount6" width="500pix" />


   ④ 画面が切り替わり、パズルを解く画面が表示されます。
      
      指示に従いパズルを解いてください。パズルを解くと「**Confirm your email address**」と表示され、登録した本人への確認コードが送信されます。

      先ほど作成したMicrosoftアカウントのメールボックスを確認してください。Microsoftアカウントのページの左側にある九点リーダーアイコンをクリックし、「**Outlook**」を選択するとメール画面に移動できます。

      <img src="./icon/GitHubSignUp-3.png" alt="MicrosoftAccount6" width="500pix" />
   

   ⑤ GitHubから届いた確認コードを入力し「**Contiune**」をクリックします。
   <img src="./icon/GitHubSignUp-4.png" alt="MicrosoftAccount6" width="500pix" />

   ⑤登録が完了すると「Sign in to GitHub」が表示されます。

      メールアドレスとパスワードを入力し、「**sign in**」をクリックします。GitHubへのサインインが完了します。

      <img src="./icon/GitHubSignUp-5.png" alt="MicrosoftAccount6" width="500pix" />

------

事前準備は終了となります。お忙しいところ、ご協力いただき誠にありがとうございます。

何かご不明な点がございましたら、「受講案内メール」または弊社の「担当営業」、「担当講師」へお気軽にお申し付けください。



受講当日、お会いできることを心よりお待ちしております。
