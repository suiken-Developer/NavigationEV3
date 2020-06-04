# NavigationEV3
# (English)
NavigationEV3 helps control EV3. In addition, it is possible to control other robots by changing the parameters.

### What Can I do?  
The sophisticated GUI allows you to intuitively place robots and control the EV3.  
!!THIS SOFTWARE OR SOURCE CODE WILL NOT BE DISTRIBUTED TO THE GENERAL PUBLIC FREE OF CHARGE IN ANY CASE. CONTACT ME TO PURCHASE FOR A FEE (CONDITIONALLY). WE ALSO ACCEPT DONATIONS!!

### Main language and environment  
v1.0.0~ Python 3.8.2 (Windows 10 Pro,ver1909)  
v1.12.0~ Python 3.8.3rc1 (Windows 10 Pro,ver1909)  
v1.16.1~ Python 3.8.3 (Windows 10 Pro,ver2004)


## List of Functions
・ Automatically calculates the distance and angle just by placing the robot  
・ Robot rotation, deletion (all deletion), position adjustment possible  
・ Robot tire diameter can be changed  
・ Text file output of distance and angle  
・ Saving robot position in .ngd (Navigation Data) format  
・ Reading .ngd file and restoring court status  
・ Coat information can be read in .ncp (Navigation Cort Pack) format Add, delete, change, and list packs on the Cort Pack management screen  
・ Settings can be changed using Config  
・ Visual operation with control panel  


# (日本語)
NavigationEV3を使用すると、簡単にEV3を制御することが可能です。

### どのように使用するか  
洗練されたGUIで、直感的にロボットを配置。たったそれだけで距離と角度が自動算出されます。これをEV3に送信することで、簡単にロボットを操作。  
注意！ このソフトウェア又はソースコードはいかなる場合があろうと無償一般配布されません。私に問い合わせていただくと、有償にて（条件付き）購入することが可能です。寄付も受け付けております。

### メインの開発言語・環境  
v1.0.0~ Python 3.8.2 (Windows 10 Pro,ver1909)  
v1.12.0~ Python 3.8.3rc1 (Windows 10 Pro,ver1909)  
v1.16.1~ Python 3.8.3 (Windows 10 Pro,ver2004)

### 動作環境  
#### 最低スペック  
Windows 10 32Bit Ver10.0  
（ソースコードからの実行時）Python 3.7  
CPU: Intel Core i5 5th Gen  
RAM: 4GB  
HDD空き容量: 2GB  

#### 推奨スペック  
Windows 10 64Bit Ver2004
（ソースコードからの実行時）Python 3.8
CPU: Intel i7 8th Gen  
RAM: 8GB  
HDD空き容量: 20GB  
SSD空き容量: 15GB  


## 機能一覧
・ロボットを配置するだけで自動で距離と角度を算出  
・ロボット回転、削除（全削除）、位置調整可能  
・ロボットタイヤ径変更可能  
・距離と角度のテキストファイル出力  
・.ngd（Navigation Data）形式でロボットの位置保存  
・.ngdファイルの読み込みとコート状態復元  
・.ncp（Navigation Cort Pack）形式でコート情報読み込み可能  
・Cort Pack管理画面でパックの追加、削除、変更、一覧  
・Configを使用し設定変更可能  
・コントロールパネルで視覚的な操作  


# Change Logs (変更点)  
### 説明
- [ ] 計画中のバージョン
- [x] 実装済みバージョン

### バージョン履歴
- [x] **v1.0.0** Release (リリース)
- [x] **v1.1.0** 大幅な機能追加1 (Substantial function addition 1)
- [x] **v1.2.0** 大幅な機能追加2 (Substantial function addition 2)
- [x] **v1.3.0** 大幅な機能追加3 (Substantial function addition 3)
- [x] **v1.4.0** 大幅な機能追加4 (Substantial function addition 4)
- [x] **v1.5.0** 大幅な機能追加5 (Substantial function addition 5)
- [x] **v1.6.0** 大幅な機能追加6 (Substantial function addition 6)
- [x] **v1.7.0** コントロールパネルの更新 (Control panel updates)
- [x] **v1.8.0** ロボット画像変更、高精度化 (Robot image change, high precision)
- [x] **v1.9.0** 保存・タイヤ径など大幅変更 (Save and change tire diameter etc.)
- [x] **v1.9.1** Spinbox修正 (Spinbox fix)
- [x] **v1.9.2** ttkの定義変更 (Change ttk definition)
- [x] **v1.10.0** ウィンドウ縮小機能追加 (Window reduction function added)
- [x] **v1.10.1** ボタン配置変更、設定廃止 (Change button layout, abolish settings)
- [x] **v1.11.0** 線を上に描画、出力認識向上、角度変更機能、OpenCVによる画像角度自由化
                  (Drawing lines on top, improving output recognition, angle change function, image angle liberalization by OpenCV)
- [x] **v1.11.1** アイコン追加、一部画像パス指定定数定義作成、コード簡略化 (Icon addition, partial image path specification constant definition creation, code simplification)
- [x] **v1.12.0** Config.iniから設定を読み込む機能実装<文字型取得と存在しない時に問題あり> (Functional implementation to read the settings from Config.ini <There is a problem when there is no character type acquisition>)
- [x] **v1.12.1** コート画像選択式の準備<存在しないときにエラー発生中> (Preparation of coat image selection formula <error occurs when it does not exist>)
- [x] **v1.12.2** ウィンドウ設定にバージョンを表示するかを選択可能に<Debug内のみ可能・Configに移行？>
- [x] **v1.12.3** コート画像が存在しない時、デフォルト画像に差し替える<デフォルト画像紛失時の対処未定>
- [x] **v1.13.0** .ncpパッケージ仮対応、データをドキュメントフォルダ格納式に変更
- [x] **v1.14.0** .ncpパッケージ対応<解凍・重複防止など>
- [x] **v1.14.1** .ncpの解凍システムのミス修正<重複防止含む>
- [x] **v1.15.0** .ncpパッケージ管理タブ作成<変更・削除・一覧機能追加予定>
- [x] **v1.16.0** Helpタブ完全実装<ライセンス者設定制度準備>
- [x] **v1.16.1** 追加コートパック作成、アスキーアート修正
- [ ] **v1.17.0** パック削除機能追加<破損していない場合に限る>
- [ ] **v1.18.0** Config.ini設定を読み込む機能修正<文字型対応>、Config.iniの設定ミスの際、デフォルトに戻す（カラー、フォント含め）、項目などの損失修正、ncp破損修復設定、拡大縮小設定
- [ ] **v1.19.0** ロボット画像変更可能化、パック破損時の自動削除
