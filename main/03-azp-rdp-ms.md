# CTC教育サービス

## Microsoft関連 コース ガイド

### ■対象コース

本ページでは以下のコースが対象となります。

| 項目                                                         |
| ------------------------------------------------------------ |
| [AZ-900 Microsoft Azure 基礎](https://www.school.ctc-g.co.jp/course/P728.html) |



### ■ご準備いただくもの

1. **Azure Portal 接続確認手順（※重要※)**

   研修ではAzureにWebブラウザからアクセスし操作を行います。受講するPC環境からアクセスできるか確認をお願いします。

   a.以下のアカウント情報とパスワードを使用して、Azure Portalにサインイン(ログイン)できるか事前確認をお願いします。

   | 項目                              | 詳細                                        |
   | --------------------------------- | ------------------------------------------- |
   | サインイン先URL(**Azure Portal**) | https://portal.azure.com                    |
   | ユーザー名                        | `azure-portal-test@ctctedu.onmicrosoft.com` |
   | パスワード                        | Pa55w.rd1234                                |

   <img src="./icon/azurelogin.png" alt="azurelogin" style="zoom: 67%;" /> 　　　<img src="./icon/azureloginpass.png" alt="azureloginpass" style="zoom:67%;" />

   

   b.サインイン後に「**Azure へようこそ!**」の画面が表示されましたら、正常にサインインが完了しています。

   <img src="./icon/azureportal.png" alt="azureportal" style="zoom:53%;" />　

   

   c.最後にサインアウトを行います。画面右上にあるユーザーアイコンをクリックし、「**サインアウト**」をしてください。

   <img src="./icon/azureportalllogout.png" alt="azureportalllogout" style="zoom:67%;" />　

   

   ------

   

2. **RDP接続確認手順（※重要※）**

   演習ではリモートデスクトップ接続(RDP)を利用します。受講するPC環境からアクセスできるか確認をお願いします。

   > ※以下のキャプチャはWindows10の画面を掲載しています。

   a.Windowsのスタートメニューから「**リモート**」と検索し、「**リモートデスクトップ接続**」を選択します。

   ![rdp1](./icon/rdp1.png) 

   

    b.リモートデスクトップ接続画面に「**20.48.105.229**」と入力し、接続をクリックします。

   ![rdp2](./icon/rdp2.png)　

   

   c.「**資格情報を入力してください**」と画面表示されます。これでRDP接続の確認は完了となります。

   　そのまま、画面を閉じてください。

   ![rdp3](./icon/rdp3.png)　

   > ※ユーザー名とパスワードの入力、サインインする必要はありません。
   >
   > ※上記画面が表示されたことにより、RDP接続が出来ていることになります。

   

   **【RDP接続が上手くいかない場合】**

   RDP接続時にエラーが表示される場合があります。

   ![rdperror](./icon/rdperror.png)　

   

   接続できない原因はいくつかあります。よくあるトラブルシュートは以下の通りです。

   | 項目                                                         | 詳細                                                         |
   | ------------------------------------------------------------ | ------------------------------------------------------------ |
   | <img src="./icon/Network.png" alt="Network" style="zoom: 25%;" />　**ネットワークの変更** | 会社のネットワークからアクセスした場合、RDP接続を禁止する設定がファイヤーウォール等に<br />行われている可能性があります。別のネットワークから接続可能な場合、そちらからお試ししてご受講ください。 |
   | <img src="./icon/securepc.png" alt="securepc" style="zoom:25%;" />　 **使用するPC変更** | 会社貸与のPCでは、RDP接続が出来ない設定が行われている場合があります。<br />ご自身でお持ちのPCなど、他のPCからアクセスできるかお試しください。 |
   | <img src="./icon/VPN.png" alt="VPN" style="zoom:2%;" />　 **VPNの停止** | 業務で使用しているPCのVPNソフトが起動しているため、接続できない可能性があります。<br />VPNソフトを停止してお試しください。 |

   上記の対処でも接続できない、またはご用意できない場合もございます。

   その場合、AzureにはWebブラウザから仮想マシンにアクセスする機能でご提供することも可能です。

   弊社側で事前に準備する必要がございます。お手数ですが、**「受講案内メール」へのご返信**または**弊社の担当営業**へご連絡ください。

   なお、お客様にご準備いただくものはございません。受講当日はそのままご参加ください。

   ------

   

3. **Microsoftアカウントの作成(※重要※)**

   Microsoft認定コースを受講する場合、**「Microsoftアカウント」**が必須となります。

   以下の手順を参考にMicrosoftアカウントをご用意ください。

   > 既にMicrosoftアカウントをお持ちの方は、ご自身のアカウントをご用意ください。

   a.Microsoftアカウント (https://account.microsoft.com/) へアクセスします。

   b.画面中央にある「サインイン」をクリックします。

   <img src="./icon/MicrosoftAccount1.png" alt="MicrosoftAccount1" style="zoom:75%;" />　

   

   c.サインイン画面で「アカウントをお持ちではない場合、作成できます。」をクリックします。

   <img src="./icon/MicrosoftAccount2.png" alt="MicrosoftAccount2" style="zoom:75%;" />　

   

   d.アカウントの作成画面でメールアドレスを入力して「次へ」または「新しいメールアドレスを取得」を選択します。

   | 項目                                  | 詳細                                                         |
   | ------------------------------------- | ------------------------------------------------------------ |
   | メールアドレスを入力                  | GmailやYahoo!メールなどのアドレスを利用することが可能です。<br />Microsoftアカウントを他のメールアドレスと統一したい場合は、こちらを選択してください。 |
   | 新しいメールアドレスを取得<br />※推奨 | Microsoftアカウントとメールアドレスを取得することが可能です。<br />ドメインは「outlook.com」「outlook.jp」「hotmail.com」から選択できます。<br />Microsoftアカウントとして個別に利用したい場合は、こちらを選択してください。 |

   <img src="./icon/MicrosoftAccount3.png" alt="MicrosoftAccount3" style="zoom:75%;" />　

   

   e.パスワードを入力します。

   > ※パスワードを忘れた場合、ご自身で再設定する必要がございます。

   <img src="./icon/MicrosoftAccount4.png" alt="MicrosoftAccount4" style="zoom:75%;" />　

   

   f.「ロボットでないことを証明するために クイズに回答してください。」と表示されます。

   　画面に従ってパズルを解いてください。

   > ※パズルは複数パターンあります。

   <img src="./icon/MicrosoftAccount5.png" alt="MicrosoftAccount5" style="zoom:75%;" />　

   

   g.Microsoftアカウントの作成が完了し、Microsoftアカウントのホーム画面が表示されます。

   <img src="./icon/MicrosoftAccount6.png" alt="MicrosoftAccount6" style="zoom:75%;" />　

   

   h.最後に画面右上にあるアイコンをクリックし、「**サインアウト**」を行います。

   <img src="./icon/MicrosoftAccount7.png" alt="MicrosoftAccount7" style="zoom:75%;" />　

------



事前準備は終了となります。お忙しいところ、ご協力いただき誠にありがとうございます。

何かご不明な点がございましたら、「受講案内メール」または弊社の「担当営業」、「担当講師」へお気軽にお申し付けください。



受講当日、お会いできることを心よりお待ちしております。

