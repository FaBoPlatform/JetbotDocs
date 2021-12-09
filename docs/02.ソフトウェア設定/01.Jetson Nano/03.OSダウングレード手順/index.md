# 古いJetPackイメージ

|対象ハードウェア|JetPackバージョン|URL|動作|内容|
|:--|:--|:--|:--|:--|
|Jetson Nano 2GB|JetPack 4.4.1|[FaBoストア](https://fabo.store/collections/jetbot)|basic_motion,collision_avoidance,road_following|docker版、最小限のコード変更、日本語化|
|Jetson Nano 4GB|JetPack 4.4.1|[FaBoストア](https://fabo.store/collections/jetbot)|basic_motion,collision_avoidance,road_following|docker版、最小限のコード変更、日本語化|
|Jetson Nano 4GB|JetPack 4.3|[FaBoストア](https://fabo.store/collections/jetbot)|basic_motion,collision_avoidance,road_following,object_following|コード変更、日本語化|

!!!warning "bootromバージョンとJetPackバージョン"
  Jetsonはbootromバージョン(基盤に保持)とJetPackバージョン(SDカードイメージ)が一致している必要があります。  
  これらのSDカードを利用する前に、bootromバージョンを更新(もしくはダウングレード)するためにリカバリーモードにして[sdkmanager](https://developer.nvidia.com/nvidia-sdk-manager)で対応するJetPackバージョンで一度flashしておく必要があります。  
  bootromとJetPackバージョンが一致しない場合は、起動時にHDMIのエラーで止まったり、電源が入らなくなることがあります。([sdkmanager](https://developer.nvidia.com/nvidia-sdk-manager)でflashすれば直ります)  
  詳しくは[nvidia developer forums](https://forums.developer.nvidia.com/c/agx-autonomous-machines/jetson-embedded-systems/jetson-nano/76)を参照するか、[discord](https://discord.com/invite/fX7UE9R)でお問い合わせください。

### JetBotの起動

SDカードをJetson Nanoに差し込み起動します。

本SDカードのidとpassは下記の通りです。ログイン時に使用します。

|項目|内容|
|:--|:--|
|ID|jetbot|
|Pass|jetbot|

