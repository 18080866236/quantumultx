#自定义策略：
[policy]
;ssid=SSID,Proxy,♻️ 自动选择,Home2604_5G:♻️ 自动选择
;具体解释如下
;组名：🏠 SSID Group
;蜂窝网下默认策略：🇭🇰 HK Group， Wi-Fi下默认策略：🇭🇰 HK Group
;ASUS_5G 这个 Wi-Fi下走：🇲🇴 MO Group ， AMG-5G 这个 Wi-Fi下走直连：direct
; AUSS_5G 跟 AMG-5G 是我的 Wi-Fi 名字，而 🇭🇰 HK Group, 🇲🇴 MO Group是我的策略组 ；
; 请按需改成你自己的节点或策略组，别傻乎乎直接全部照搬。。。
static=🚀 节点选择, proxy, direct, ♻️ 自动选择, 🔮 负载均衡, img-url=https://raw.githubusercontent.com/mydaozun/quantumultx/main/icon/lightning-y.png
url-latency-benchmark=♻️ 自动选择, server-tag-regex=(?=.*)^((?!(专线|手游|游戏|(?i)IPLC|IEPL|game)).)*$, img-url=https://raw.githubusercontent.com/mydaozun/quantumultx/main/icon/lightning-g.png
round-robin=🔮 负载均衡, server-tag-regex=.*, img-url=https://raw.githubusercontent.com/mydaozun/quantumultx/main/icon/lightning-p.png

#自定义
# 其中 CMedia 策略组为中国媒体，GMedia 为国际媒体，Outside 为境外链接，Mainland 为大陆链接，Others 为最终规则
static=AdBlock, reject, direct, img-url=https://raw.githubusercontent.com/mydaozun/quantumultx/main/icon/adguard.png
static=Apple, direct, Outside, 🚀 节点选择,img-url=https://raw.githubusercontent.com/mydaozun/quantumultx/main/icon/Apple.png
static=AppleIOSUpdate, reject, direct, img-url=https://raw.githubusercontent.com/mydaozun/quantumultx/main/icon/apple-ios.png
static=Microsoft, direct, Outside, 🚀 节点选择,img-url=https://raw.githubusercontent.com/mydaozun/quantumultx/main/icon/microsoft.png
static=Netflix, Outside, direct, 🚀 节点选择, img-url=https://raw.githubusercontent.com/mydaozun/quantumultx/main/icon/netflix.png
static=YouTube, Outside, direct, 🚀 节点选择, img-url=https://raw.githubusercontent.com/mydaozun/quantumultx/main/icon/youtube.png
static=Spotify, Outside, proxy, direct, 🚀 节点选择, img-url=https://raw.githubusercontent.com/mydaozun/quantumultx/main/icon/Spotify.png
static=GMedia, Outside, direct, 🚀 节点选择, img-url=https://raw.githubusercontent.com/mydaozun/quantumultx/main/icon/media-r.png
static=CMedia, direct, proxy, img-url=https://raw.githubusercontent.com/mydaozun/quantumultx/main/icon/media-g.png
static=Speedtest, Outside, direct, 🚀 节点选择, img-url=https://raw.githubusercontent.com/mydaozun/quantumultx/main/icon/Speedtest.png
static=Outside, proxy, direct, 🚀 节点选择, img-url=https://raw.githubusercontent.com/mydaozun/quantumultx/main/icon/Internet.png
static=Mainland, direct, proxy, img-url=https://raw.githubusercontent.com/mydaozun/quantumultx/main/icon/CN.png
static=Fianl, Outside, direct, 🚀 节点选择, img-url=https://raw.githubusercontent.com/mydaozun/quantumultx/main/icon/fin.png


#自用图标库地址： 
  apple：https://raw.githubusercontent.com/mydaozun/quantumultx/main/icon/Apple.png
  auto-b：https://raw.githubusercontent.com/mydaozun/quantumultx/main/icon/Auto-b.png
  auto-y：https://raw.githubusercontent.com/mydaozun/quantumultx/main/icon/Auto-y.png
  Available：https://raw.githubusercontent.com/mydaozun/quantumultx/main/icon/Available.png
  Available_Alt：https://raw.githubusercontent.com/mydaozun/quantumultx/main/icon/Available_Alt.png
  CN：https://raw.githubusercontent.com/mydaozun/quantumultx/main/icon/CN.png
  Internet：https://raw.githubusercontent.com/mydaozun/quantumultx/main/icon/Internet.png
  JP：https://raw.githubusercontent.com/mydaozun/quantumultx/main/icon/JP.png
  KR：https://github.com/mydaozun/quantumultx/blob/main/icon/KR.png
  Siri：https://raw.githubusercontent.com/mydaozun/quantumultx/main/icon/Siri.png
  Speedtest：https://raw.githubusercontent.com/mydaozun/quantumultx/main/icon/Speedtest.png
  Spotify：https://raw.githubusercontent.com/mydaozun/quantumultx/main/icon/Spotify.png
  TW：https://raw.githubusercontent.com/mydaozun/quantumultx/main/icon/TW.png
  TikTok_Alt：https://raw.githubusercontent.com/mydaozun/quantumultx/main/icon/TikTok_Alt.png
  US：https://raw.githubusercontent.com/mydaozun/quantumultx/main/icon/US.png
  YouTube：https://raw.githubusercontent.com/mydaozun/quantumultx/main/icon/YouTube.png
  adguard：https://raw.githubusercontent.com/mydaozun/quantumultx/main/icon/adguard.png
  apple-ios：https://raw.githubusercontent.com/mydaozun/quantumultx/main/icon/apple-ios.png
  bilibili_3：https://raw.githubusercontent.com/mydaozun/quantumultx/main/icon/bilibili_3.png
  fin：https://raw.githubusercontent.com/mydaozun/quantumultx/main/icon/fin.png
  lightning-g：https://raw.githubusercontent.com/mydaozun/quantumultx/main/icon/lightning-g.png
  lightning-p：https://raw.githubusercontent.com/mydaozun/quantumultx/main/icon/lightning-p.png
  lightning-y：https://raw.githubusercontent.com/mydaozun/quantumultx/main/icon/lightning-y.png
  media-g：https://raw.githubusercontent.com/mydaozun/quantumultx/main/icon/media-g.png
  media-r：https://raw.githubusercontent.com/mydaozun/quantumultx/main/icon/media-r.png
  microsoft：https://raw.githubusercontent.com/mydaozun/quantumultx/main/icon/microsoft.png
  netflix：https://raw.githubusercontent.com/mydaozun/quantumultx/main/icon/netflix.png
：
：
：
：
：
：
：
：
：
：
：
：
：
：
：
：
：
：
：
：
：
：
：
：
：
：
：
