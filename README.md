# LAX.Pro.MALIBU 值不值 $49.9 一年：三网 CN2 GIA 实测什么水平？和 WEE、TINY 差在哪？超流量、续费、退款怎么算（附全套餐对比表）

$49.9 一年，1 核 AMD EPYC 9654、1GB 内存、20GB SSD、每月 1000GB 双向流量、1Gbps 带宽、1 个 IPv4 加一段 /64 IPv6，三网回程走 CN2 GIA（AS4809）。这是 LAX.Pro.MALIBU（正式名 LAX.AN4.Pro.MALIBU）的核心信息，DMIT 洛杉矶 Premium 产品线里的限量年付机型，只在补货窗口出现。

有两件事得先说清楚。性能、路由、解锁这些数据，来自 2025 年 1 月一份第三方融合怪脚本测评，是单次样本，不是长期跟踪；价格、库存、续费价，目前找不到官方价格页的实时快照，只能靠第三方整理交叉比对。所以下面所有配置和价格，下单前请以官网套餐页显示为准，尤其是"MALIBU 现在到底还有没有货"这个问题，本文回答不了。

## 选购速览

> 月流量不到 500GB、只搭一个轻量代理节点，选 WEE（$36.9/年，500Mbps），别为用不上的流量多付钱。
> 需要 1TB 流量和 1Gbps 带宽，MALIBU 比 WEE 贵 $13，换来流量翻倍、带宽翻倍，这是这笔差价最直接的换算。
> 要 2GB 内存跑建站面板、Java 应用或者多客户端聚合，1GB 硬扛不住，直接看 TINY 或 PalmSpring。

👉 [查看 DMIT LAX Pro MALIBU 当前库存与年付价格](https://www.dmit.io/aff.php?aff=9081&pid=186)

## 全套餐对比：Pro 限量、Pro 常规、EB 三条线

下面的价格和配置来自第三方整理文章，几份资料之间存在冲突（后面会逐条说明），标注"以官网为准"的地方不要当成定论。

### Pro 限量年付（三网 CN2 GIA 回程）

| 套餐 | 核心配置 | 流量 / 带宽 | 价格与周期 | 购买 |
| --- | --- | --- | --- | --- |
| LAX.Pro.WEE | 1 核 / 1GB / 20GB SSD | 500GB / 500Mbps | $36.9 / 年 | [ 查看 WEE](https://www.dmit.io/aff.php?aff=9081) |
| **LAX.Pro.MALIBU** | 1 核 / 1GB / 20GB SSD | **1000GB / 1Gbps** | **$49.9 / 年** | [ 查看 MALIBU](https://www.dmit.io/aff.php?aff=9081&pid=186) |
| LAX.Pro.PalmSpring | 2 核 / 2GB / 40GB SSD | 2000GB / 2Gbps | $100 / 年 | [ 查看 PalmSpring](https://www.dmit.io/aff.php?aff=9081) |
| LAX.Pro.Irvine | 2 核 / 4GB（另一说 2GB）/ 60GB（另一说 40GB） | 3000GB / 5Gbps | $159 / 年 | [ 查看 Irvine](https://www.dmit.io/aff.php?aff=9081) |

WEE 的早期版本是 450GB 流量配 10GB 硬盘，后来更新为 500GB 配 20GB，看到旧数据不用对号入座。Irvine 的内存和硬盘两份资料写法不一致，买之前务必在官网核一遍。

### Pro 常规套餐（同样三网 GIA，长期有货）

| 套餐 | 核心配置 | 流量 / 带宽 | 价格与周期 | 购买 |
| --- | --- | --- | --- | --- |
| LAX.Pro.TINY | 1 核 / 2GB / 20GB SSD | 1000GB / 1Gbps | $9.99/月 或 $88.88/年，两说 | [ 查看 TINY](https://www.dmit.io/aff.php?aff=9081) |
| LAX.Pro.Pocket | 1–2 核 / 2GB / 40GB SSD | 1500GB / 4Gbps | $14.9 / 月 | [ 查看 Pocket](https://www.dmit.io/aff.php?aff=9081) |
| LAX.Pro.STARTER | 2 核 / 2GB / 40–80GB SSD | 3000GB / 10Gbps | $29.9 / 月 | [ 查看 STARTER](https://www.dmit.io/aff.php?aff=9081) |
| LAX.Pro.MINI | 2–4 核 / 4GB / 80GB SSD | 5000GB / 10Gbps | $58.8 / 月 | [ 查看 MINI](https://www.dmit.io/aff.php?aff=9081) |
| LAX.Pro.MICROv3 | 4 核 / 4GB / 80GB SSD | 7000GB / 10Gbps | $74.99 / 月 | [ 查看 MICROv3](https://www.dmit.io/aff.php?aff=9081) |
| LAX.Pro.MEDIUMv2 | 4 核 / 8GB / 160GB SSD | 14000GB / 10Gbps | $168.88 / 月 | [ 查看 MEDIUMv2](https://www.dmit.io/aff.php?aff=9081) |
| LAX.Pro.Large | 8 核 / 16GB / 320GB SSD | 25000GB / 10Gbps | $338.88 / 月 | [ 查看 Large](https://www.dmit.io/aff.php?aff=9081) |
| LAX.Pro.GIANT | 8 核 / 24GB / 640GB SSD | 50000GB / 10Gbps | $620 / 月 | [ 查看 GIANT](https://www.dmit.io/aff.php?aff=9081) |

TINY 是这张表里最需要留意的一行。一份资料写 $9.99/月（标注 AN5 平台），另一份写 $88.88/年，还有更早的季付口径。$9.99×12＝$119.88，和 $88.88 对不上，可能是 AN4 与 AN5 两代产品的差别，也可能只是资料过期。按年付买之前，先把官网上的计费周期切换一遍再确认。

### EB 系列（CMIN2 回程，价格更低）

| 套餐 | 核心配置 | 流量 / 带宽 | 价格与周期 | 购买 |
| --- | --- | --- | --- | --- |
| LAX.EB.WEE | 1 核 / 1GB / 20GB SSD | 1000GB / 1Gbps | $39.9 / 年 | [ 查看 EB.WEE](https://www.dmit.io/aff.php?aff=9081) |
| LAX.EB.CORONA | 1 核 / 1GB / 20GB SSD | 1500GB / 2Gbps | $49.9 / 年 | [ 查看 EB.CORONA](https://www.dmit.io/aff.php?aff=9081) |
| LAX.EB.FONTANA | 2 核 / 2GB / 40GB SSD | 2500GB / 4Gbps | $100 / 年 | [ 查看 EB.FONTANA](https://www.dmit.io/aff.php?aff=9081) |
| LAX.EB.TINY | 1 核 / 2GB / 20GB SSD | 1500GB / 2Gbps | $9.99 / 月 | [ 查看 EB.TINY](https://www.dmit.io/aff.php?aff=9081) |
| LAX.EB.Pocket | 2 核 / 2GB / 40GB SSD | 3000GB / 4Gbps | $14.9 / 月 | [ 查看 EB.Pocket](https://www.dmit.io/aff.php?aff=9081) |
| LAX.EB.STARTER | 2 核 / 2GB / 80GB SSD | 5000GB / 10Gbps | $29.9 / 月 | [ 查看 EB.STARTER](https://www.dmit.io/aff.php?aff=9081) |
| LAX.EB.MINI | 4 核 / 4GB / 80GB SSD | 10000GB / 10Gbps | $58.8 / 月 | [ 查看 EB.MINI](https://www.dmit.io/aff.php?aff=9081) |
| LAX.EB.MICRO | 4 核 / 4GB / 160GB SSD | 14000GB / 10Gbps | $74.99 / 月 | [ 查看 EB.MICRO](https://www.dmit.io/aff.php?aff=9081) |
| LAX.EB.MEDIUM | 6 核 / 8GB / 160GB SSD | 30000GB / 10Gbps | $168.88 / 月 | [ 查看 EB.MEDIUM](https://www.dmit.io/aff.php?aff=9081) |
| LAX.EB.Large | 8 核 / 16GB / 320GB SSD | 50000GB / 10Gbps | $338.88 / 月 | [ 查看 EB.Large](https://www.dmit.io/aff.php?aff=9081) |
| LAX.EB.GIANT | 12 核 / 24GB / 640GB SSD | 100000GB / 10Gbps | $620 / 月 | [ 查看 EB.GIANT](https://www.dmit.io/aff.php?aff=9081) |

线路分级是 Premium（三网双向 CN2 GIA）高于 Eyeball（三网回程 CMI）高于 Tier 1（国际线路）。EB 便宜在回程走 CMI 而不是 GIA，配置数字反而比同价位的 Pro 更好看，比如 EB.WEE 卖 $39.9 就给 1TB 流量和 1Gbps，而 Pro.WEE 卖 $36.9 只有 500GB 和 500Mbps。

## 10GB 还是 20GB：配置口径变过一次

2024 年 5 月 30 日这款套餐首发时，公布的是 10GB SSD，测试 IP 154.17.2.12。后来所有资料都改成了 20GB SSD，2025 年 1 月的实测里磁盘可用空间是 19.60 GiB，和 20GB 口径吻合。看到"10G 硬盘"的老帖子，那是首发版本或者早期公告的写法，现在按 20GB 理解。

同一份实测还给出了硬件底细：AMD EPYC 9654 96-Core，单核 2396.396 MHz，L3 缓存 16MB，AES-NI 和 VM-x/AMD-V 都开着；内存可用 958.71 MiB，另外挂了 1024 MiB Swap；系统是 Debian 12，内核 6.1.0-21，TCP 拥塞控制 BBR，KVM 虚拟化，NAT 类型 Full Cone；IPv4 归属 AS906 DMIT Cloud Services，位置洛杉矶。

## 线路：宣传口径和实测路由差在几个节点上

官方定位是电信去程 CN2 直连（AS4809）、联通去程 CN2 直连（AS4809）、移动去程 CMIN2（AS58807），三网回程全部 CN2 GIA（AS4809）。Pro 系列还承诺不随意切换路由，这是它比 EB 贵的原因之一。

实测回程大样本基本对得上：北京电信、北京联通、北京移动、上海电信、上海移动、广州电信、广州移动、成都电信，全部标为"电信 CN2GIA 精品线路"。逐跳看更直观，广州电信 150.88ms 落到香港 CN2-Global，151.48 到 158.79ms 走广州 CN2-BackBone，155.78ms 之后才转 AS4134 电信骨干；广州移动 150.97ms 经香港 CN2-Global，160.39ms 到广州 CN2-BackBone，159.15ms 转 AS9808。

例外有两处，前排文章基本不提。

第一处是联通。上海联通、广州联通、成都联通三个节点在标注"电信CN2GIA"的同时，还并列标了"联通4837 普通线路"。以广州联通为例，145.52ms 进入 CN2-BackBone，165.87ms 转到 AS4837，之后 165.89ms、169.22ms、182.35ms 一路在联通自己的骨干网里走。也就是说，回程主体确实是 GIA，但落到部分联通接入点时会切回 4837。

第二处是成都移动 211.137.96.205，标的是"电信CN2GT 优质线路 / 电信163 普通线路"，是全表唯一一个没落到 GIA 的节点。

脚本自己带了提示：同一目标出现多条线路时，后续信息可能已经越过汇聚层，仅供参考。所以这两处例外不代表你家的联通或移动宽带一定绕路，但它确实说明"三网全 GIA"是个整体描述，不是每个省份每个接入点都精确成立。

延迟方面，第三方推广文章写晚高峰 150–165ms、丢包极低，也有写电信联通 130–170ms、移动稍高的。实测测速样本里国内节点落在 135–162ms：联通 WuXi 149.68ms、联通上海5G 162.01ms、电信浙江 135.19ms、电信 Zhenjiang5G 135.93ms、移动 Beijing 151.25ms。推广文的数字更漂亮，以实测为准。

## 性能：单核 4473 分，1M 块读写 1.2GB/s

引用 2025 年 1 月那次融合怪脚本测评的具体数字，单次样本，不代表长期表现：

- sysbench 单核 4473 Scores
- 内存单线程读 48752.58 MB/s，写 29654.74 MB/s
- dd 直连模式 1GB-1M 块读写都是 1.2 GB/s（1111 IOPS）；100MB-4K 块写 112 MB/s、读 106 MB/s
- fio 4k 读写 62.55 / 62.65 MB/s，64k 读写 1.06 / 1.07 GB/s，512k 读 941.41 MB/s、写 991.43 MB/s
- Speedtest 洛杉矶本地 1048.28 / 1008.06 Mbps，延迟 0.33ms，丢包 0%
- 联通 WuXi 816.79 / 772.19 Mbps，电信浙江 596.70 / 773.95 Mbps，移动 Beijing 873.78 / 496.57 Mbps

4K 随机读写六十多 MB/s 这个水平，跑 WordPress、轻量数据库、单节点代理都不构成瓶颈，但别指望它当高并发存储用。

## 真实成本：$49.9 和月付 $9.99 差多少

这是多数人算不清的一笔账。MALIBU 一年 $49.9，同样三网 GIA 回程的 TINY 月付 $9.99，一年 $119.88，两者差 $69.98。换句话说，MALIBU 用一年的钱，差不多是 TINY 五个月的费用。

不过代价是：MALIBU 只有 1GB 内存，TINY 是 2GB；MALIBU 超流量限速 2Mbps，TINY 是 4Mbps；MALIBU 仅年付，一次性付清，TINY 月付随时能停。这一年省下的 $70，本质上是拿内存、限速档位和退出灵活性换来的。

还有续费。资料里引述的条款是"某个计费周期内购买价格不涨，到期后续费按当时官网价格"。限量补货机型能不能原价续，取决于官方当时的公告，没有任何资料能给出承诺。第一年 $49.9 不等于第二年还是 $49.9，把这一点算进预算。

👉 [按年付 $49.9 开通 LAX.Pro.MALIBU](https://www.dmit.io/aff.php?aff=9081&pid=186)

## 流量超限会怎样：2Mbps 能干什么

月流量 1000GB，双向计算，也就是上行下行都算在里面。用超之后不停机、不关机，降到 2Mbps 继续跑。

2Mbps 大概是什么体验：网页能开，文字类工作、SSH、IM 消息没问题，标清视频勉强，1080p 和下载基本别想。这个档位在 DMIT 的产品线里属于最紧的一档，PalmSpring、Irvine 和月付 TINY 超限后是 4Mbps，MINI 是 8Mbps。同样是"降速不停机"，4Mbps 的可用性比 2Mbps 高一个档次。

如果你的用法是每月稳定跑几百 GB，MALIBU 的 1TB 够用；如果经常摸到 1TB 上限，那降速之后的体验会明显拖后腿，不如直接看 PalmSpring（2TB、2Gbps、超限 4Mbps）。

有第三方整理文章提到 DMIT 在 2025 年底把 LAX Pro 全系改成超量降速不停机，这条说法没有官方公告原文佐证，下单页上的流量策略说明才是可靠依据。

## 谁不该买 MALIBU

**需要 2GB 以上内存的**。1GB 跑 Nginx 加 PHP 还行，跑 MySQL 加 Java 就紧张。要建站、要跑面板、要开多个服务，TINY 的 2GB 更合适，PalmSpring 的 2 核 2GB 更宽裕。

**要 Windows 的**。DMIT 默认 Linux，Windows 得自己想办法。

**每月稳定跑几 TB 的**。2Mbps 的限速档位就是为轻量用途设的，重度下载、多用户聚合、跑大流量业务，这个套餐不合适，去看 Pro 常规的高配套餐或者 EB 系列。

**只想试一个月看看的**。MALIBU 没有月付选项，只能年付。想短周期试线路，月付 TINY 更合理。

**预算优先、对回程线路没那么敏感的**。EB.WEE 年付 $39.9，给 1TB 流量和 1Gbps 带宽，回程走 CMI 而不是 GIA，便宜 $10，配置数字还更好看。

## 买之前要确认的几件事

**库存**。MALIBU 是限量机型，资料里最新的补货记录停在 2024 年 7 月 18 日，当时站点提示"限量版方案一般补货后半天到一天就会售罄"。补货没有固定规律，促销节点前后出现概率高一些是第三方文章的推测，不是官方说法。判断方法只有一个：进套餐页看 Order Now 按钮能不能点。

**换 IP**。购买满 7 天后可以申请，IP 不通的情况下每 15 天免费换一次，其他情况 $5 一次。LAX Pro 后台支持自助操作，不用开工单。这个政策两份资料写法一致，可信度较高。

**退款**。30 天内可以申请，按剩余时间折算退还，扣除支付网关手续费。另有第三方整理的条款把"购买不超过 3 天且流量不超过 30GB"列为可全额退款的情形，并把"网络不够好""IP 地理位置原因"列进不予退款的范围。条款细节以官网为准，但 30 天的窗口足够你把线路跑一遍再决定要不要留。

**登录方式**。默认 SSH 密钥登录。一份资料说密钥只能下载一次、不支持密码直连，另一份说后台可以改成密码登录、官方有中文教程。两说并存，第一次登录前先把官方文档翻一遍，别把密钥弄丢。

**新账号等待期**。有第三方经验描述称新注册账号可能要等 7 天才能下单，但不是所有账号都会触发。打算抢补货的话，提前几天把账号注册好。

**支付**。支付宝、微信支付、PayPal 都能用，部分资料还列了信用卡。

👉 [进 DMIT 套餐页确认 MALIBU 是否有货、核对续费价](https://www.dmit.io/aff.php?aff=9081&pid=186)

## 流媒体和 IP 质量：别信"全解锁"

2025 年 1 月那份实测的结论比推广文保守得多：

- Netflix：IPv4 和 IPv6 都是 Originals Only，识别地区美国，只能看自制剧
- Disney+：同一份报告里两段测试结果打架，CommonMediaTests 段落显示 US 区可解锁，RegionRestrictionCheck 段落显示"No (IP Banned By Disney+ 1)"，说明解锁不稳定
- YouTube Premium：US 区可用；Amazon Prime Video：US 区可用；Google Gemini：US 区可用；TikTok 区域标 US
- ChatGPT：IPv4 可用，IPv6 连接失败
- Spotify 注册：不可用；Reddit：不可用

IP 属性是 hosting / DataCenter，云提供商和数据中心都标 Yes，ASN 滥用得分 0.0013（Low），公司滥用 0.0002（Very Low），ipqualityscore 欺诈得分 65，DNS 黑名单 314 项检查里 6 项 blacklisted、24 项 other。邮件端口方面 Gmail 的 SMTP 通、IMAP 不通，Outlook 和 Office365 的 SMTP 通、SMTPS 不通。

推广文章写"原生美国 IP，Netflix、TikTok 等主流流媒体实测可解锁"，和上面这份具体测试对不上。按具体测试理解：部分服务可用，Netflix 只有自制剧，Disney+ 时好时坏，不保证。

## FAQ

**现在（2026 年 11 月）还有货吗？**

资料里查不到。最新的补货公开记录是 2024 年 7 月 18 日，之后这款机型是否仍在售、价格是否还是 $49.9，没有官方页面可以确认。唯一可靠的做法是打开套餐页看按钮状态。

**我是联通或移动用户，CN2 GIA 对我有用吗？**

有用，但没宣传得那么整齐。回程主体走 AS4809，实测里上海、广州、成都三个联通节点同时出现了 4837 的标注，成都移动则落到 CN2GT 和 163。多数省份体验接近电信用户，个别接入点会绕。

**流量超了会直接关机吗？**

不会。降到 2Mbps 继续跑，网页和文字工作还能用，视频和下载基本停摆。

**支付宝能付款吗？**

可以，另外支持微信支付和 PayPal，部分资料还列了信用卡。

**Netflix 能解锁吗？**

按实测只能看自制剧，地区识别为美国。Disney+ 在同一份报告里出现了两种相反结果，属于不稳定状态。

## 最后怎么选

只要一个轻量代理节点、月流量压在 500GB 以内，WEE 的 $36.9 就够，多花的 $13 换不来实际体验差别。

需要 1TB 流量和 1Gbps 带宽，MALIBU 是这条产品线上性价比最集中的一款，前提是你能接受 1GB 内存和 2Mbps 的超限限速档。

要 2GB 内存、要月付灵活，TINY 更合适，一年多花约 $70 买的是内存和随时退出的权利。

预算优先、对回程线路没那么挑，EB.WEE 年付 $39.9 给 1TB 流量，走 CMI 回程。

下单前把两件事确认掉：套餐页上的 Order Now 能不能点，以及续费价格写的是什么。限量机型的第二年价格，没有任何资料能替官方承诺。

👉 [前往 DMIT 核对 LAX.Pro.MALIBU 的实时库存与价格](https://www.dmit.io/aff.php?aff=9081&pid=186)
