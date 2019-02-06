# UploadWeight2Fitbit
fitbitへ体重をアップロードする

## 事前準備
### python
  3系なら大丈夫だと思いますが、今回は以下を使用。
  python3.7.2 windows 64bit版  
  https://www.python.org/downloads/release/python-372/

### python plugin
- python-fitbit。localにcloneしておく。  
https://github.com/orcasgit/python-fitbit

- [oauthlib](https://github.com/oauthlib/oauthlib)  
pip install oauthlib  

- [requests](https://github.com/requests/requests)  
pip install requests  

- [requests_oauthlib](https://github.com/requests/requests-oauthlib)  
pip install requests_oauthlib


- クライアントID、シークレットの取得(※)  



## 参考
https://dev.fitbit.com/apps

- fitbitが公開しているAPI  
https://dev.fitbit.com/build/reference/



   　　→ **token.bat** と **PythonFitbit.py** 内の内容は更新  
 　　→体重計からの計測結果を準備(*.csv)  

------
### 手順 ###
　1. "token.bat" を実行  
　　→Webページが表示 →閉じる  
　　→コマンドライン画面が消えるのを待つ  
　2. "PythonFitbit.py"を実行  
　　→体重がfitbitへアップロードされる  

※クライントID、シークレットの取得についてや、環境作成について  
　私は以下を参照  
https://pc.atsuhiro-me.net/entry/2014/05/07/022857

私はVisual Studio 2017にて作成
