# Install_Check-run-passについて
<br>

## 概要
指定したソフトおよびバージョンのインストールが実施されているか確認を行い、インストールの要不要を判断するためのものです。<br>
ログオンバッチで毎日実行するなど、継続してチェックするが、必要ない場合は余計なインストールを実行したくない場合などに有効。
<br>
<br>

## 注意点
<li>ビルドが違う場合を前提に作成、同じソフトで同じビルドの場合は、インストール実施前にアンインストールを実行する必要がある
<li>インストール実行時のUACでの通知画面が表示された場合の確認と実施に関して、ユーザーに周知する必要あり
<li>余計なUACの通知を回避するため、通常実行でプログラムがスタートすることを想定。インストール実行時のみ管理者権限に動的に昇格
 
<br>
<br>

## Install_Check.bat

