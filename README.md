# DMIT 黑五：优惠码怎么蹲、哪些套餐值得等，各机房年付价一次讲清

如果你搜到这篇文章，大概率是同一个处境：DMIT 的常规价你下不去手，想等黑五看能不能便宜一截，但又怕到时候手慢一步、库存和优惠码全没了。

这个担心是合理的。DMIT 一年真正放量的窗口不多，黑五算是其中最集中的一次。它跟那些「全场 3 折、全年挂着折扣码」的商家完全不是一路——DMIT 平时很少给公开码，黑五的力度也不算离谱，但因为库存有限、机型还带特价批次，蹲对时间点确实能省下一笔。

下面把黑五这件事拆成三部分讲：DMIT 历年黑五到底放什么，现在常规套餐卖多少钱，以及你该提前做什么准备。

## 先说清楚：DMIT 黑五值得等的是什么

DMIT 是 2017 年前后开始运营的美国主机商，机房分布在美国洛杉矶、圣何塞、中国香港和日本东京，产品线按网络质量分三档：Premium（Pro，三网回程 CN2 GIA）、Eyeball（EB，回程走 9929 / CMIN2 这类优化线路）、Tier 1（T1，纯国际线路，不做大陆优化）。硬件平台又分 AS3（AMD EPYC 7003）、AN4（EPYC 9004）和 AN5（EPYC 9005）几代，目前洛杉矶的 AN4 已经全部下架，在售的以 AN5 为主。

这家商家的特点是**不怎么超售**，代价就是贵和经常缺货。社区里常年挂着的抱怨就两种：一是「正价年付都要 800 多人民币，超预算」，二是「想买的机型又没货」。而黑五能缓解的，恰好是第一个问题——它把年付价格往下压一档，同时偶尔放出单价更低的一批特价机型。

所以黑五值得等，但不是「随便买都便宜」。真正划算的是年付、半年付，以及那些只在活动期上架的特价批次。

## DMIT 黑五的优惠，历年基本是这几种形式

翻一下 DMIT 从 2022 年至今的黑五记录，玩法其实相当固定，只是每年力度和覆盖机房会变：

**全场周期折扣码。** 2022 年黑五，DMIT 给的是年付 7 折、半年付 8 折、月付 9 折，覆盖当年还叫 Standard Network 的产品线，要求 STARTER 及以上计划，活动窗口是 11 月 25 日到 12 月 5 日（UTC）。这枚年付 7 折码 `Lite-Annually-Recur-30OFF` 和半年付 8 折码 `Lite-Semi-Annually-Recur-20OFF`，在之后几年的第三方整理里反复出现，属于持续时间最长的一类。

**分期放的限时码。** 有一年 DMIT 预告过在黑五当天每小时发布一个优惠码，每个码有效期只有 1 小时，订单还要求 5 分钟内完成付款。这种玩法对蹲守的人是机会，对睡过头的就是纯折磨。社区的说法是「DMIT 前几天黑五活动，24 小时各发布一个优惠码」，有人蹲了一整天只抢到 15% 的那一枚。

**账户金返还和买赠。** 2022 年洛杉矶区域月付新订单累计消费每满 100 美元返 35 美元账户金，东京区域买 Pro.STARTER 及以上的年付产品送一台同样产品；2023 年黑五则做了「任选两台 Pro 系列产品免费得一台」，以及最高返还 70% 账户金。这类玩法适合本来就要多台机器的用户，只买一台的话等于看热闹。

**特价批次机型。** 这是黑五最实在的部分。2022 年上过 `PVM.LAX.Pro.WEE`，1 核 / 1GB / 10GB SSD / 500Mbps@450GB，36.9 美元包年，走的是 CN2 GIA 线路；洛杉矶还有一款高防机型 `LAX.sPro.Fixed`，2 核 2G / 40G SSD / 1TB@300Mbps，年付 139 美元、用码后 125 美元，去程接 Cloudflare Magic Transit，标称 5Tbps 的 DDoS 防护容量。这类机器的问题是数量少、补货随机，卖完就没了。

> 一个现实提醒：DMIT 卖得越好，黑五放特价的动力越小。今年正价机长期处于被抢空的状态，社区里不少人据此判断特价批次会更难抢。这不是官方说法，但下单前值得把心理预期放低一点。

## 黑五前该做的四件准备

多数人黑五没抢到，不是因为穷，是因为准备不足。

1. **提前注册并登录账号。** 黑五当天的限时码往往要求极短的付款窗口，现场注册、验证邮箱、绑支付方式，很容易卡掉整单。
2. **把付款方式先配好。** DMIT 支持 PayPal、支付宝和信用卡，支付宝对国内用户最顺手。支付通道在活动期间可能排队，别把首次支付留到抢码那一刻。
3. **确定两三个目标机型，别只盯一个。** 想清楚你要的是电信优化（Pro）、移动/联通优化（EB），还是只要大带宽大流量（T1）。目标机型缺货时能立刻换备选，比现场纠结强。
4. **盯着补货而不是盯着价格。** DMIT 的库存是分批放的，社区里有人专门做补货监控和历史补货时间表。活动期前后的一两天，刷新频率决定成败。

## 现在官网在售的主要套餐和价格

DMIT 在售 SKU 有几十个，按「机房 × 网络档位 × 硬件平台」组合。下表是各条线路的常规在售阶梯，用于判断黑五折扣落在哪个价位上。价格均为美元，库存和定价变动频繁，下单页显示为准。

### 洛杉矶 LAX（AN5 平台）

| 线路 | 套餐 | 配置 | 价格 | 查看 |
| --- | --- | --- | --- | --- |
| Premium（三网 CN2 GIA） | LAX.AN5.Pro.TINY | 1核 / 2G / 20G / 1T@1Gbps | $14.9/月 | [查看洛杉矶 Pro 套餐](https://www.dmit.io/cart.php?region=los-angeles&generation=an5&network=premium&aff=12046) |
| Premium | LAX.AN5.Pro.Pocket | 2核 / 2G / 40G / 1.5T@4Gbps | $21.9/月 | [查看洛杉矶 Pro 套餐](https://www.dmit.io/cart.php?region=los-angeles&generation=an5&network=premium&aff=12046) |
| Premium | LAX.AN5.Pro.STARTER | 2核 / 2G / 80G / 3T@10Gbps | $43.9/月 | [查看洛杉矶 Pro 套餐](https://www.dmit.io/cart.php?region=los-angeles&generation=an5&network=premium&aff=12046) |
| Premium | LAX.AN5.Pro.MINI | 4核 / 4G / 80G / 5T@10Gbps | $79.9/月 | [查看洛杉矶 Pro 套餐](https://www.dmit.io/cart.php?region=los-angeles&generation=an5&network=premium&aff=12046) |
| Premium | LAX.AN5.Pro.MICRO | 4核 / 4G / 160G / 7T@10Gbps | $110.9/月 | [查看洛杉矶 Pro 套餐](https://www.dmit.io/cart.php?region=los-angeles&generation=an5&network=premium&aff=12046) |
| Premium | LAX.AN5.Pro.MEDIUM | 6核 / 8G / 160G / 15T@10Gbps | $289.9/月 | [查看洛杉矶 Pro 套餐](https://www.dmit.io/cart.php?region=los-angeles&generation=an5&network=premium&aff=12046) |
| Premium | LAX.AN5.Pro.LARGE | 8核 / 16G / 320G / 25T@10Gbps | $499.9/月 | [查看洛杉矶 Pro 套餐](https://www.dmit.io/cart.php?region=los-angeles&generation=an5&network=premium&aff=12046) |
| Premium | LAX.AN5.Pro.GIANT | 12核 / 24G / 640G / 50T@10Gbps | $1009.9/月 | [查看洛杉矶 Pro 套餐](https://www.dmit.io/cart.php?region=los-angeles&generation=an5&network=premium&aff=12046) |
| Eyeball（9929 / CMIN2） | LAX.AN5.EB.MINI | 4核 / 4G / 80G / 10T@10Gbps | $79.9/月 | [查看洛杉矶在售机型](https://www.dmit.io/aff.php?aff=12046) |
| Eyeball | LAX.AN5.EB.MICRO | 4核 / 4G / 160G / 14T@10Gbps | $110.9/月 | [查看洛杉矶在售机型](https://www.dmit.io/aff.php?aff=12046) |
| Eyeball | LAX.AN5.EB.MEDIUM | 6核 / 8G / 160G / 30T@10Gbps | $289.9/月 | [查看洛杉矶在售机型](https://www.dmit.io/aff.php?aff=12046) |
| Tier 1（国际线路） | LAX.T1.WEE | 1核 / 1G / 20G / 1T | $36.9/年 | [查看洛杉矶 T1 套餐](https://www.dmit.io/aff.php?aff=12046) |
| Tier 1 | LAX.T1.TINY | 1核 / 1G / 20G / 2T | $6.9/月 | [查看洛杉矶 T1 套餐](https://www.dmit.io/aff.php?aff=12046) |
| Tier 1 | LAX.T1.STARTER | 1核 / 2G / 40G / 4T | $12.9/月 | [查看洛杉矶 T1 套餐](https://www.dmit.io/aff.php?aff=12046) |
| Tier 1 | LAX.T1.MINI | 2核 / 2G / 60G / 8T | $21.9/月 | [查看洛杉矶 T1 套餐](https://www.dmit.io/aff.php?aff=12046) |
| Tier 1 | LAX.T1.MICRO | 4核 / 4G / 80G / 16T | $32.9/月 | [查看洛杉矶 T1 套餐](https://www.dmit.io/aff.php?aff=12046) |
| Tier 1 | LAX.T1.MEDIUM | 4核 / 8G / 160G / 32T | $49.9/月 | [查看洛杉矶 T1 套餐](https://www.dmit.io/aff.php?aff=12046) |

Pro 和 EB 系列超出月流量后不停机，改成限速（Pro 入门档 4Mbps、中大档 8–10Mbps）继续不限量使用；T1 系列超量后的限速更宽松，洛杉矶 T1 是 100Mbps 不限流。这个「限速不限量」的策略，是很多人宁可多花钱也不换便宜商家的原因。

### 香港 HKG 与东京 TYO

| 机房 | 套餐 | 配置 | 价格 | 查看 |
| --- | --- | --- | --- | --- |
| 香港 · Tier 1 | HKG.T1.WEE | 1核 / 1G / 20G / 1T | $36.9/年 | [查看香港在售套餐](https://www.dmit.io/aff.php?aff=12046) |
| 香港 · Tier 1 | HKG.T1.TINY | 1核 / 1G / 20G / 2T | $6.9/月 | [查看香港在售套餐](https://www.dmit.io/aff.php?aff=12046) |
| 香港 · Tier 1 | HKG.T1.STARTER | 1核 / 2G / 40G / 4T | $12.9/月 | [查看香港在售套餐](https://www.dmit.io/aff.php?aff=12046) |
| 香港 · Tier 1 | HKG.T1.MINI | 2核 / 2G / 60G / 8T | $21.9/月 | [查看香港在售套餐](https://www.dmit.io/aff.php?aff=12046) |
| 香港 · Tier 1 | HKG.T1.MICRO | 4核 / 4G / 80G / 16T | $32.9/月 | [查看香港在售套餐](https://www.dmit.io/aff.php?aff=12046) |
| 香港 · Tier 1 | HKG.T1.MEDIUM | 4核 / 8G / 160G / 32T | $49.9/月 | [查看香港在售套餐](https://www.dmit.io/aff.php?aff=12046) |
| 香港 · Premium | HKG.AN5.Pro 系列 | 1核 / 1G 起（三网 CN2 GIA） | $39.9/月起 | [查看香港 Pro 套餐](https://www.dmit.io/aff.php?aff=12046) |
| 东京 · Tier 1 | TYO.T1.TINY | 1核 / 1G / 20G / 2T | $6.9/月 | [查看东京在售套餐](https://www.dmit.io/aff.php?aff=12046) |
| 东京 · Tier 1 | TYO.T1.STARTER | 1核 / 2G / 40G / 4T | $12.9/月 | [查看东京在售套餐](https://www.dmit.io/aff.php?aff=12046) |
| 东京 · Tier 1 | TYO.T1.MINI | 2核 / 2G / 60G / 8T | $21.9/月 | [查看东京在售套餐](https://www.dmit.io/aff.php?aff=12046) |
| 东京 · Tier 1 | TYO.T1.MICRO | 4核 / 4G / 80G / 16T | $32.9/月 | [查看东京在售套餐](https://www.dmit.io/aff.php?aff=12046) |
| 东京 · Tier 1 | TYO.T1.MEDIUM | 4核 / 8G / 160G / 32T | $49.9/月 | [查看东京在售套餐](https://www.dmit.io/aff.php?aff=12046) |
| 东京 · Tier 1 | TYO.T1.LARGE | 8核 / 16G / 320G / 64T | $99.9/月 | [查看东京在售套餐](https://www.dmit.io/aff.php?aff=12046) |

香港和东京的 T1 超量后限速 50Mbps 不限流，比洛杉矶紧一档。另外 HKG Pro 系列已经整体升级到 AN5 平台（DDR5 5600 内存 + EPYC 9655P），价格也从更低的老批次抬到 $39.9/月起。

### 关于缺货这件事

洛杉矶 AN4 平台已经彻底下架，香港和东京的 T1、Pro 部分机型长期处于售罄状态，客服给出的解释是 IP 资源不足。也就是说，黑五真正能买到的东西，取决于活动当天仓库里有什么，而不是取决于你预算多少。这也是为什么「提前列好备选」比「提前研究折扣力度」更重要。

## 按需求选：黑五该下手哪一档

**只有一个需求：从国内访问稳。** 那就只有 Pro 线值得考虑，电信去程 GIA（AS4809）、三网 GIA 回程，晚高峰表现是 DMIT 的核心卖点。代价是 Pro 入门档 AN5.Pro.TINY 月付 $14.9，年付折算下来也要一百多美元，比 T1 贵出一个量级。如果预算卡得很死，等黑五看有没有 Pro.WEE 这类特价批次上架。

**移动或联通为主。** Eyeball 线（回程 9929 / CMIN2）通常比 Pro 便宜一档，移动用户体验甚至更舒服。这条线的常规机型配置给得更大方，MiNi 档就有 4 核 4G / 80G / 10TB 流量。

**跑下载、做中转、面向海外用户。** T1 线够用，而且便宜。$6.9/月的 TINY 是全系最低价，$36.9 包年的 WEE 是很多人的第一台 DMIT。但请接受一个前提：T1 是国际互联，不对国内做优化，电信联通双程走 NTT、有时绕美。买它之前别抱「便宜也能快」的幻想。

**要建站、要抗攻击。** 关注黑五有没有高防批次，历年上过带 Cloudflare Magic Transit 的机型，价格比常规 Pro 高但不离谱。香港 Pro 适合对延迟要求极致的场景，$39.9/月起的门槛在那儿摆着。

## 优惠码怎么用，以及要避开的坑

DMIT 的优惠码在结账页面填入后点「Validate Code」验证，不同码对应不同产品线和付款周期，混用会直接报无效。

目前第三方整理里反复出现、并且覆盖多轮的码有这么几个：

- `Lite-Annually-Recur-30OFF` —— Tier 1 / Standard 网络系列年付 7 折，要求 STARTER 及以上；
- `Lite-Semi-Annually-Recur-20OFF` —— 同系列半年付 8 折；
- `2025-EXISTING-CUSTOMER-10OFF` —— 现有客户增购 9 折，适用于月均费用超过 3.33 美元的在售产品，T1 不受此限制。

除此之外，DMIT 每个促销周期都会放一批带区域和平台限定的循环码，例如香港 / 东京 Pro 的 8 折码、T1 的 7 折码、洛杉矶 Pro / EB 的年付折扣码加返现组合。这类码有效期短、改动频繁，别人分享的码到你这儿很可能已经失效，唯一可靠的验证方式就是在购物车里试一次。

有一个坑必须提：社区里出现过用户用了已被判定无效的促销码下单，机器用了将近一周后被直接回收、订单退款的情况，涉及三台洛杉矶高防机型、四百多美元。争议点在于事前没有通知。**所以凡是促销码订单，别第一时间上生产环境，重要数据做好异地备份，下单记录和码的验证截图留一份。** 这句话放在买任何便宜 VPS 上都成立，不是 DMIT 独有的问题。

## 常见问题

**黑五折扣会持续多久？** 参考 2022 年那轮，主活动窗口是 11 月 25 日到 12 月 5 日（UTC），但当天限时码可能只有 1 小时有效期。别把「活动持续十天」和「你的码还有效」混为一谈。

**月付能用黑五码吗？** 大部分黑五码限定年付或半年付，月付折扣很少，通常是 9 折左右。按月付买，黑五的性价比基本打折一半。

**T1 和 Pro 差价那么大，值不值？** 看你的用户在哪。国内用户为主，且在意晚高峰丢包和延迟，Pro 的溢价是有回报的；纯粹跑海外业务或做流量中转，多花的钱买不到对应的收益。

**IP 被墙了怎么办？** 洛杉矶 Pro 和 EB 系列已经支持自助更换 IP，包括不少早期买的促销款。月付订单分配的 IP 官方不保证全球可用，想稳一点可以在下单时加购相关保障服务。

**现在没货，黑五会补吗？** 官方没有承诺。黑五前后确实是补货相对集中的时间窗，但具体放哪些机型、放多少，事前拿不到准确信息。想第一时间知道，靠的是补货监控和活动当天高频刷新。

## 最后一句实话

DMIT 黑五不是「捡漏」，更像是「用年付换一个合理价格」的机会。真正的难点从来不是折扣有多少，而是你想要的机型当天有没有货、你能不能在两小时内完成注册、选型、填码、付款这一整套动作。

把这些事提前做完，剩下的就只是等那一天。看到目标机型上架的那一刻，点进去下单就行——👉 [看看 DMIT 当前在售的套餐和库存](https://www.dmit.io/aff.php?aff=12046)。
