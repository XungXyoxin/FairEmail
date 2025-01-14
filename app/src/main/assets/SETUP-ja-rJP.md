# セットアップヘルプ

FairEmail のセットアップは非常に簡単です。 メールを受信するためにはアカウントを、送信するには ID をそれぞれ 1 つ以上設定する必要があります。 クイックセットアップでは、ほとんどの主要プロバイダーのアカウントと ID が一度に追加されます。

## 必要な条件

アカウントと ID を設定するには、インターネット接続が必要です。

## クイックセットアップ

該当するプロバイダーを選択するか、*その他のプロバイダー*を選択し、名前、メールアドレス、パスワードを入力し、*確認*をタップします。

これはほとんどのメールプロバイダーで機能します。

クイックセットアップが機能しない場合は、アカウントと ID を手動で設定する必要があります。手順については以下を参照してください。

## アカウントの設定 - メールを受信する

アカウントを追加するには、*手動セットアップとアカウントのオプション設定*から*アカウント*を選択し、下部にある「＋」ボタンをタップして IMAP (または POP3) を選択します。 リストからプロバイダーを選択し、ユーザー名 (ほとんどはメールアドレス)、パスワードを入力します。 *確認*をタップして FairEmail がメールサーバーに接続し、システムフォルダーのリストを取得できるようにします。 システムフォルダーの選択を確認後、*保存*をタップしてアカウントを追加できます。

プロバイダーがリストにない場合は、*カスタム*を選択してください。 *gmail.com* などのドメイン名を入力し、*設定を取得*をタップします。 プロバイダーが[自動検出](https://tools.ietf.org/html/rfc6186)をサポートしている場合、FairEmail はホスト名とポート番号を入力します。 それ以外の場合は、プロバイダーのセットアップ手順に従って正しい IMAP ホスト名・ポート番号・プロトコル (SSL/TLS または STARTTLS) を入力してください。 詳細は[こちら](https://github.com/M66B/FairEmail/blob/master/FAQ.md#authorizing-accounts)をご確認ください。

## ID の設定 - メールを送信する

同様に、ID を追加するには、*手動セットアップとアカウントのオプション設定*から *ID* を選択し、下部にある「＋」ボタンをタップします。 送信するメールに表示する名前を入力し、リンクするアカウントを選択します。 *保存*をタップしてIDを追加します。

アカウントを手動で設定した場合、ID も手動で設定する必要があります。 *gmail.com* などのドメイン名を入力し、*設定を取得*をタップします。 プロバイダーが[自動検出](https://tools.ietf.org/html/rfc6186)をサポートしている場合、FairEmail はホスト名とポート番号を入力します。 それ以外の場合は、プロバイダーのセットアップ手順に従って正しい SMTP ホスト名・ポート番号・プロトコル (SSL/TLS または STARTTLS) を入力してください。

エイリアスの使用については [FAQ](https://github.com/M66B/FairEmail/blob/master/FAQ.md#FAQ9) を確認してください。

## 権限の許可 - 連絡先情報にアクセスする

メールアドレスを検索したり、連絡先の写真を表示するには FairEmail に連絡先の読み取りを許可をする必要があります。 *権限の許可*をタップして、*許可*を選択します。

## バッテリー最適化の設定 - 継続的にメールを受信する

Android の最近のバージョンでは、電池の消費を抑えるために画面をオフにしたあとしばらくするとアプリをスリープ状態にします。 新着メールを遅延なく受信するには、FairEmail のバッテリー最適化を無効にする必要があります。 *管理*をタップし、指示に従ってください。

## 質問または問題

質問や問題がある場合は、[こちら](https://github.com/M66B/FairEmail/blob/master/FAQ.md)をご覧ください。