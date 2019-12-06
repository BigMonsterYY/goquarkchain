### TPS Competition Questionnaire

*Please replace the square brackets and the text in it with your answers*

**Number of CPUs**

[(64 cpu)  (64 cpu)  (64 cpu)]

**Memory (GB)**

[128*3]

**Storage (GB)**

[50gb*3]

**Network**

[80 mbps]

**Machine Type (Optional)**

[腾讯 SA1.16XLARGE128]

**Command Lines for Running Cluster**
```
[    使用的官方文档提供的命令  ]
```

**Peak TPS**

[31940  34085]

**Video URL**

[https://youtu.be/WZ7ApBrbmKU]

**Output From `stats` Tool (Highest TPS)**
```
[============================
QuarkChain Cluster Stats
============================
CPU:                64
Memory:             125 GB
IP:                 172.30.0.16
Chains:             128
Network Id:         3
Peers:              172.30.0.15:51698,172.30.0.6:38291
============================
Timestamp		Syncing	TPS	Pend.TX	Conf.TX	BPS	SBPS	CPU	ROOT
2019-12-06 11:03:20	false	0.00	0	0	63.65	42.60	100.00	6
2019-12-06 11:03:30	true	0.00	0	0	62.60	38.28	100.00	7
2019-12-06 11:03:40	false	0.00	0	0	62.10	41.75	100.00	7
2019-12-06 11:03:50	false	0.00	0	0	62.85	41.20	100.00	8
2019-12-06 11:04:00	false	190.00	174280	2285	62.73	40.05	100.00	8
2019-12-06 11:04:10	false	520.00	264059	6285	62.45	37.73	100.00	9
2019-12-06 11:04:20	false	710.00	265437	8570	61.97	35.48	100.00	9
2019-12-06 11:04:30	true	2130.00	270104	25565	61.58	33.58	100.00	10
2019-12-06 11:04:40	false	4580.00	271049	54985	61.13	32.43	100.00	10
2019-12-06 11:04:50	false	5590.00	272838	67126	60.03	30.23	100.00	10
2019-12-06 11:05:00	false	6580.00	269006	82981	58.72	28.97	100.00	10
2019-12-06 11:05:10	false	8485.00	252797	107836	58.50	28.42	100.00	11
2019-12-06 11:05:20	false	9365.00	248140	118406	57.87	28.20	100.00	11
2019-12-06 11:05:30	false	11660.00	242162	145971	55.97	27.47	100.00	11
2019-12-06 11:05:40	true	19590.00	166491	242376	50.77	25.60	100.00	11
2019-12-06 11:05:50	true	26030.00	202680	348664	50.93	25.42	100.00	12
2019-12-06 11:06:00	false	31180.00	155696	495289	52.22	25.27	37.13	12
2019-12-06 11:06:10	false	31610.00	109120	537004	52.62	25.27	21.87	13
2019-12-06 11:06:20	false	31940.00	134275	547869	53.57	25.27	71.05	13
]
```
**Output From `stats` Tool (Second highest TPS)**
```
[============================
QuarkChain Cluster Stats
============================
CPU:                64
Memory:             125 GB
IP:                 172.30.0.6
Chains:             128
Network Id:         3
Peers:              172.30.0.15:38291,172.30.0.16:51348
============================
Timestamp		Syncing	TPS	Pend.TX	Conf.TX	BPS	SBPS	CPU	ROOT
2019-12-06 11:06:35	false	31560.00	372175	557009	55.68	18.40	100.00	14
2019-12-06 11:06:45	false	32845.00	385348	590719	56.17	18.40	100.00	14
2019-12-06 11:06:55	false	34085.00	502249	633002	56.82	18.40	100.00	15
2019-12-06 11:07:05	false	32800.00	473286	648437	57.82	18.40	100.00	15]
```

**Cluster Configurations**
[https://github.com/BigMonsterYY/goquarkchain/blob/master/tests/loadtest/deployer/deployConfig.json
https://github.com/BigMonsterYY/goquarkchain/blob/master/tests/loadtest/deployer/deployConfig-sample.json]

**Additional Comment**

[我使用了windows10自带的游戏录制工具，所以录出来的视频没有看到我的配置，这win10的它没有录到我点出浏览器查看配置，抱歉。]
