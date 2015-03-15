# realtime-multi-chat-skyway-sample
リアルタイム通信(peer to peer)して、複数メンバーで音声再生するサンプルです。  
他のメンバーが入ると自動接続します。  
クラウドサービス[SkyWay](http://nttcom.github.io/skyway/)(WebRTC)を使用しています。  

```
git clone https://github.com/front-core/peer-to-peer-sample.git
cd peer-to-peer-sample/realtime-multi-audio-skyway-sample
npm install
grunt
```
Access to  
[http://localhost:9001/](http://localhost:9001/)  
or  
[http://naoki-otsu.info/realtime-multi-audio-skyway-sample/](http://naoki-otsu.info/realtime-multi-audio-skyway-sample/)  

SkyWayを利用する為には、  
[開発者登録](https://skyway.io/ds/registration/)してAPI_KEYの発行、また利用するドメインの指定が必要です。(無料)  
