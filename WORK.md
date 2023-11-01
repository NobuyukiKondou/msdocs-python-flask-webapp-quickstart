Azure Web Appを公開する際に、Azure Active Directory (Azure AD) を使用して閲覧者を限定するための手順は以下の通りです：

Azure Active Directoryのアプリ登録:

Azure Portalにログインします。
左側のナビゲーションペインから「Azure Active Directory」を選択します。
「アプリの登録」を選択し、「新しい登録」をクリックします。
必要な情報を入力し、アプリを登録します。
Azure Web Appの認証設定:

Azure Portalで、対象のWeb Appを選択します。
左側のナビゲーションペインから「認証/承認」を選択します。
「認証をオンにする」を「オン」に設定します。
「認証プロバイダーの追加」をクリックし、Azure Active Directoryを選択します。
以前に作成したAzure ADのアプリ登録を選択し、必要な情報を入力します。
アクセス許可の設定:

Azure PortalのAzure ADのアプリ登録ページに戻ります。
「APIの許可」を選択し、「許可の追加」をクリックします。
必要な許可を追加します。
ユーザーやグループへのアクセス許可の割り当て:

Azure PortalのAzure ADのアプリ登録ページで、「ロールと管理者」を選択します。
必要なロールを選択し、ユーザーやグループを追加してアクセス許可を割り当てます。
Web Appの再起動:

変更を適用するために、Azure Web Appを再起動します。
これで、Azure Web Appへのアクセスは、Azure ADを通じて認証されたユーザーのみに制限されます。指定したユーザーやグループのみがWeb Appにアクセスできるようになります。