# Quantumult X小白配置 制作 by Orz-3 TG频道：t.me/Orzmini 2022/07/26

[general]
server_check_url=http://cp.cloudflare.com/generate_204
dns_exclusion_list=*.cmpassport.com, *.jegotrip.com.cn, *.icitymobile.mobi, id6.me
geo_location_checker=http://ip-api.com/json/?lang=zh-CN, https://raw.githubusercontent.com/Orz-3/Orz-3/master/QuantumultX/IP.js
resource_parser_url=https://fastly.jsdelivr.net/gh/KOP-XIAO/QuantumultX@master/Scripts/resource-parser.js
excluded_routes=239.255.255.250/32
udp_whitelist=1-442, 444-65535

[dns]
no-ipv6
server=119.29.29.29
address=/mtalk.google.com/108.177.125.188
server=/dl.google.com/119.29.29.29
server=/dl.l.google.com/119.29.29.29
server=/update.googleapis.com/119.29.29.29
server=/*.dl.playstation.net/119.29.29.29
server=/amplifi.lan/system
server=/router.synology.com/system
server=/sila.razer.com/system
server=/router.asus.com/system
server=/routerlogin.net/system
server=/orbilogin.com/system
server=/www.LinksysSmartWiFi.com/system
server=/LinksysSmartWiFi.com/system
server=/myrouter.local/system
server=/www.miwifi.com/system
server=/miwifi.com/system
server=/mediarouter.home/system
server=/tplogin.cn/system
server=/tplinklogin.net/system
server=/melogin.cn/system
server=/falogin.cn/system

[policy]
static=全球加速, 香港节点, 台湾节点, 日本节点, 狮城节点, 美国节点, proxy, img-url=https://raw.githubusercontent.com/Orz-3/mini/master/Color/Global.png
static=苹果服务, direct, 香港节点, 台湾节点, 美国节点, 日本节点, 狮城节点, proxy, img-url=https://raw.githubusercontent.com/Orz-3/mini/master/Color/Apple.png
static=港台番剧, direct, 香港节点, 台湾节点, img-url=https://raw.githubusercontent.com/Orz-3/mini/master/Color/StreamingSE.png
static=国际媒体, 香港节点, 台湾节点, 日本节点, 美国节点, 狮城节点, proxy, 🇰🇷 韩国-专线访问 VUKR, 🇸🇬 新加坡-专线访问 DP, 🇭🇰 香港-专线访问 DP, 🇹🇼 台湾-专线访问 BGP, img-url=https://raw.githubusercontent.com/Orz-3/mini/master/Color/Streaming.png
static=Netflix, proxy, direct, 🇸🇬 新加坡-专线访问 DP, 🇹🇼 台湾-专线访问 BGP, img-url=https://raw.githubusercontent.com/Orz-3/mini/master/Color/Netflix.png
static=黑白名单, 全球加速, direct, 香港节点, 台湾节点, 日本节点, 狮城节点, 美国节点, proxy, img-url=https://raw.githubusercontent.com/Orz-3/mini/master/Color/Final.png
url-latency-benchmark=香港节点, server-tag-regex=(?=.*(港|HK|(?i)Hong))^((?!(台|日|韩|新|美)).)*$, check-interval=60000000, tolerance=0, img-url=https://raw.githubusercontent.com/Orz-3/mini/master/Color/HK.png
url-latency-benchmark=台湾节点, server-tag-regex=(?=.*(台|TW|(?i)Taiwan))^((?!(港|日|韩|新|美)).)*$, check-interval=60000000, tolerance=0, img-url=https://raw.githubusercontent.com/Orz-3/mini/master/Color/TW.png
url-latency-benchmark=日本节点, server-tag-regex=(?=.*(日|JP|(?i)Japan))^((?!(港|台|韩|新|美)).)*$, check-interval=60000000, tolerance=0, img-url=https://raw.githubusercontent.com/Orz-3/mini/master/Color/JP.png
url-latency-benchmark=狮城节点, server-tag-regex=(?=.*(新|狮|獅|SG|(?i)Singapore))^((?!(港|台|日|韩|美)).)*$, check-interval=60000000, tolerance=0, img-url=https://raw.githubusercontent.com/Orz-3/mini/master/Color/SG.png
url-latency-benchmark=美国节点, server-tag-regex=(?=.*(美|US|(?i)States|American))^((?!(港|台|日|韩|新)).)*$, check-interval=60000000, tolerance=0, img-url=https://raw.githubusercontent.com/Orz-3/mini/master/Color/US.png

[server_remote]
https://s1.bnpublicsub.com/api/v1/client/subscribe?token=a36083279886116211d7ad704faec859#in=专线, tag=bitz, img-url=https://raw.githubusercontent.com/Orz-3/mini/master/Color/Personal.png, update-interval=172800, opt-parser=true, enabled=true

[filter_remote]
https://raw.githubusercontent.com/DivineEngine/Profiles/master/Surge/Ruleset/Unbreak.list, tag=规则修正, force-policy=direct, update-interval=172800, opt-parser=true, enabled=true
https://raw.githubusercontent.com/DivineEngine/Profiles/master/Surge/Ruleset/Guard/Advertising.list, tag=广告拦截, force-policy=reject, update-interval=172800, opt-parser=true, enabled=true
https://raw.githubusercontent.com/DivineEngine/Profiles/master/Surge/Ruleset/Guard/AdvertisingPlus.list#type=domain-set, tag=广告拦截, force-policy=reject, update-interval=172800, opt-parser=true, enabled=true
https://raw.githubusercontent.com/NobyDa/Script/master/Surge/AdRule.list, tag=广告拦截, force-policy=reject, update-interval=172800, opt-parser=true, enabled=true
https://raw.githubusercontent.com/app2smile/rules/master/rule/tieba-ad-qx.list, tag=贴吧广告, force-policy=reject, update-interval=172800, opt-parser=false, enabled=true
https://raw.githubusercontent.com/DivineEngine/Profiles/master/Surge/Ruleset/Guard/Hijacking.list, tag=运营劫持, force-policy=reject, update-interval=172800, opt-parser=true, enabled=true
https://raw.githubusercontent.com/DivineEngine/Profiles/master/Surge/Ruleset/Guard/Privacy.list, tag=隐私保护, force-policy=reject, update-interval=172800, opt-parser=true, enabled=true
https://raw.githubusercontent.com/DivineEngine/Profiles/master/Surge/Ruleset/StreamingMedia/Video/TikTok.list, tag=海外抖音, force-policy=全球加速, update-interval=172800, opt-parser=true, enabled=true
https://raw.githubusercontent.com/DivineEngine/Profiles/master/Surge/Ruleset/Extra/Google/GoogleVoice.list, tag=Google Voice, force-policy=美国节点, update-interval=172800, opt-parser=true, enabled=true
https://raw.githubusercontent.com/DivineEngine/Profiles/master/Surge/Ruleset/StreamingMedia/Region/HK.list, tag=流媒体HK, force-policy=香港节点, update-interval=172800, opt-parser=true, enabled=true
https://raw.githubusercontent.com/DivineEngine/Profiles/master/Surge/Ruleset/StreamingMedia/Region/TW.list, tag=流媒体TW, force-policy=台湾节点, update-interval=172800, opt-parser=true, enabled=true
https://raw.githubusercontent.com/DivineEngine/Profiles/master/Surge/Ruleset/StreamingMedia/Region/JP.list, tag=流媒体JP, force-policy=日本节点, update-interval=172800, opt-parser=true, enabled=true
https://raw.githubusercontent.com/DivineEngine/Profiles/master/Surge/Ruleset/StreamingMedia/Region/US.list, tag=流媒体US, force-policy=美国节点, update-interval=172800, opt-parser=true, enabled=true
https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/QuantumultX/Netflix/Netflix.list, tag=Netflix, force-policy=Netflix, update-interval=172800, opt-parser=false, enabled=true
https://raw.githubusercontent.com/DivineEngine/Profiles/master/Surge/Ruleset/StreamingMedia/Streaming.list, tag=国际媒体, force-policy=国际媒体, update-interval=172800, opt-parser=true, enabled=true
https://raw.githubusercontent.com/DivineEngine/Profiles/master/Surge/Ruleset/StreamingMedia/StreamingSE.list, tag=港台番剧, force-policy=港台番剧, update-interval=172800, opt-parser=true, enabled=true
https://raw.githubusercontent.com/DivineEngine/Profiles/master/Surge/Ruleset/Global.list, tag=全球加速, force-policy=全球加速, update-interval=172800, opt-parser=true, enabled=true
https://raw.githubusercontent.com/DivineEngine/Profiles/master/Surge/Ruleset/Extra/Apple/Apple.list, tag=苹果服务, force-policy=苹果服务, update-interval=172800, opt-parser=true, enabled=true
https://raw.githubusercontent.com/DivineEngine/Profiles/master/Surge/Ruleset/China.list, tag=国内网站, force-policy=direct, update-interval=172800, opt-parser=true, enabled=true

[rewrite_remote]
https://raw.githubusercontent.com/Peng-YM/Sub-Store/master/config/QX.snippet, tag=Sub Store, update-interval=172800, opt-parser=false, enabled=false
https://raw.githubusercontent.com/chavyleung/scripts/master/box/rewrite/boxjs.rewrite.quanx.conf, tag=BoxJs, update-interval=172800, opt-parser=false, enabled=false
https://raw.githubusercontent.com/Orz-3/QuantumultX/master/Bili_Auto_Regions.conf, tag=Bilibili换区脚本, update-interval=172800, opt-parser=false, enabled=false
https://raw.githubusercontent.com/Orz-3/QuantumultX/master/JD_TB_price.conf, tag=比价脚本, update-interval=172800, opt-parser=false, enabled=false
https://raw.githubusercontent.com/NobyDa/Script/master/QuantumultX/TestFlightDownload.conf , tag=TestFlight区域限制解除, update-interval=172800, opt-parser=false, enabled=true
https://raw.githubusercontent.com/Orz-3/QuantumultX/master/TikTok.conf, tag=Tiktok解锁, update-interval=172800, opt-parser=false, enabled=false
https://raw.githubusercontent.com/Orz-3/QuantumultX/master/Netflix_ratings.conf, tag=Netflix评分, update-interval=172800, opt-parser=false, enabled=true
https://raw.githubusercontent.com/DivineEngine/Profiles/master/Quantumult/Rewrite/General.conf, tag=神机重定向, update-interval=172800, opt-parser=false, enabled=true
https://raw.githubusercontent.com/DivineEngine/Profiles/master/Quantumult/Rewrite/Block/YouTubeAds.conf, tag=YouTube去广告, update-interval=172800, opt-parser=false, enabled=false
https://raw.githubusercontent.com/app2smile/rules/master/module/bilibili-qx.conf, tag=Bilibili去广告, update-interval=172800, opt-parser=false, enabled=false
https://raw.githubusercontent.com/app2smile/rules/master/module/tieba-qx.conf, tag=贴吧去广告, update-interval=172800, opt-parser=false, enabled=false
https://raw.githubusercontent.com/DivineEngine/Profiles/master/Quantumult/Rewrite/Block/Advertising.conf, tag=神机去广告, update-interval=172800, opt-parser=true, enabled=false
https://raw.githubusercontent.com/NobyDa/Script/master/QuantumultX/Rewrite_lhie1.conf, tag=lhie1去广告, update-interval=172800, opt-parser=false, enabled=false
https://raw.githubusercontent.com/DivineEngine/Profiles/master/Quantumult/Rewrite/Block/AdvertisingPlus.conf, tag=去广告脚本, update-interval=172800, opt-parser=false, enabled=false

[server_local]

[filter_local]
host-suffix, local, direct
ip-cidr, 192.168.0.0/16, direct
ip-cidr, 10.0.0.0/8, direct
ip-cidr, 172.16.0.0/12, direct
ip-cidr, 127.0.0.0/8, direct
ip-cidr, 100.64.0.0/10, direct
ip-cidr, 224.0.0.0/4, direct
ip6-cidr, fe80::/10, direct
ip-cidr, 203.107.1.1/24, reject
ip-cidr, 183.240.197.130/32, direct
final, 黑白名单

[rewrite_local]

[task_local]
event-interaction https://raw.githubusercontent.com/KOP-XIAO/QuantumultX/master/Scripts/streaming-ui-check.js, tag=流媒体解锁查询, img-url=arrowtriangle.right.square.system, enabled=true

[http_backend]

[mitm]
passphrase = 5046EA90
p12 = MIILuwIBAzCCC4UGCSqGSIb3DQEHAaCCC3YEggtyMIILbjCCBccGCSqGSIb3DQEHBqCCBbgwggW0AgEAMIIFrQYJKoZIhvcNAQcBMBwGCiqGSIb3DQEMAQYwDgQIAPUPEx9zAJsCAggAgIIFgPD8Cxc/rcMlbqsbpgs4gj6/tSVW84Iq+BRnBCfv6OCxpcFADI9/ynXhIRLI008Dz+nOsPEnrKOseZ7JbLZ5uuL2qmA4r8koySFOR7TRHgXZdgAA0fT1RJV1ZRsY3QsHthu7X1lzuyEhbcaw6axKBPhxC7tfkCTyoi/j7eAssosxWfL5OytnEz8MCskts9qgvF4CM5AHiTZIeuhp66niXeGzNFT430hgM28/886INOwTp5X7lsbXj0OIIilwtKl5FkCB3Re5FdWbj7zk2cZcnOVFuBVJth1Rdhzf1m2Thb2By7VEyNNJd2q/KXPRA6579vsffG1g3fPcYy4oVK0kkMTQW0TJYX8wLOWfSK+JvvPOvXm9O66scnVZnItT78vIedJVnEefsdAMCygahw2WKMHNbv/iqzHcWRjeXr5kHz8VH8l6m3bqbTAbovo8pWCBjUXyQAYZCWg8bmN3EXsfvF5otMCSCeD7+HmdDxxWu/BDuB1CmG/VnZwFkKNE7TN0/jEuoR4G7DUgFXM3inJfSK4bVNhzpSfB8tSa2B7xRmolsu8saqrL0SEUqI++gqDxqWI8eqB4h8WUljUuXJjNF7NXrtHjkTsgqVd81xMdd3NtxeKxiYV14dGimILZT1Mk7Aa5YxHn/+bkXy92smfEJxw72SJZQf3L9Kw0HAgX/KVfG0ul78smpCOg2BxfhEqSojOd0jEiMFPu8RYf7+8c7iQJf5qUiKKLoqhGhfEvcZz2XkOtpcKWURNUdzRHvvHYbroiS/6d09pYq2i5kFmfroYUitb/WjoxqBln7qYnhLBS3Vj5HkoOSVNYz9MZ0rmCAR6Ngbk+zQfsDq9oql2gqgwteHDwGHPUasoJqVztT5S+v7BAIHFr9IkKInlJBVVIOZMvCWbwuHyDq22YXb2yWzE5rAkyMvJ6gQ5GLrPq0dl401dmSiEIVdxtgq/iX6PPWq6PUOTLhDzDoL11bnM5qHO/KQTvBAwlGMtYyzAvbE53Rp9RisonY349soAUKsF82oRzJh64A72eduoBSkD4g0ivnGe1J0Zt3sy/3zqZWrwK+wyfEejTHNlH/JsDqAzpc2TvFn/eBJdXAdioMq735gac10qOgJJNQsnnGsGh1vzvVHI2U1jjruktHrTGmlc+/XODHAYhr9kRsvT66/k47imwTUOjxwpJxDm7mR5o9XPEOIv1+OCLn32fqaUhJJqQ4SR4MxJzEPq0EzV5vZJ03waPd9TqNx7S/teq68ZffXQ1LSHu+rw9Erq5GA5dtnYezAuUlds+ZRU858enuCIhFxNXL4hQZ8AABUrByl6jDZknTjoCNf7kgveEXdhlWkK7vJKVYwKH2qjmBJTJScYryLQyTWeBh9LHQMhhzO73orA9Acg7MDA9HpDcl+jrjVHJGcAL3ecHg6iupc6id7IprqzXHouXZUHUeHiba1N9FRufDJ0+XAJZ5Sgpj3EwwjoaEJ6uuLrEEe55PApbYVituD3RKGionmqyDkKPjko7OtF1vxowfRu3OUn8tScGiL2fdVY/u6iDRZVKEShTlzQbBdmWxM+/mdTYezhypKf3bOSe9PPpyu8W+UJ2SNQyy2VySoadPBvSgS+sYCGtQG1AcyHNWzkOZrq2Ttk4OAt3eWS2xqU6BR89NQlIovJjD4U4i+3xWF/SDhQFr/PSsw6J6SLKsiE2+qMNdp4l+0D4PrgExdYkLw9cTtvDKoEaCtOJNEJWjISR86Pnjz8qo6QsRhTc+8SfPT7Dna8nmNS/ChPGwcWgPAjntsF6GQMQ6XNQArCFE79s87BEXwZyzEbyxLmS6uyA2vLD6Y5m8mUlGQvxEzad3LAl90mDtHDchSVsoO98yFjWhuhM2hCEHs/D01owggWfBgkqhkiG9w0BBwGgggWQBIIFjDCCBYgwggWEBgsqhkiG9w0BDAoBAqCCBO4wggTqMBwGCiqGSIb3DQEMAQMwDgQITfM/Y+RpLZMCAggABIIEyKElfgiKHFCGBdlprF8W+wdij2jfGjpYjxsQjSJbuJ/39UDR6a0LjWLv4APYYHIa3GPNx5Bs250tIrEvYIYbAoFIwmAWQ0i5FLFMIWDYdYy+s8qyER+XqhQW/zur1n5bQrUP7HVVAy+Lh5ZrKa9UFl147A9aiqgaZ0+2HAvmp53+Mi38KPJLxQa4oRv9kj/YuTqB0ogVv7ZhzfXEAjsIoWPjtd1oi9Q/r2ItU9cMzXSuy1bLrOUKRBQmgMcrZYSm5PoP8nz9VbA77NT7BGWvfXqv1GrDIa85jeF1JBeOJQDwA2iquC5VmEcd4nlM4BOpAR3jc4hPGS+Er5nmnZcGg4SswM4JMa1GU32f4mfhjeFjw8tgLG1t05AqRjwvyWO0/qfrQbPZKjLuT9In+WeUktXUn8Dk3/wpDYuWxzVZVjppKoT3az+MgoxK15wmFWBERNo9R5Alsme92zdTWgOmzMCv+Y8bYBJWKugKGAshQ/duqPdNSFeULFF5gjSf1jPC9voyHkEmIzFNEHyQynoziLUJpZiO4m6na5zkcStNSNCE3mh0qSGQXRtH1szluasYeAFyzC9rdhtOW9bnPv4csO9Cz1LNKnctk36i0NsZNpmBkrtcKbRKJyBSOdhfz9VeG1CpqZUNv1U969iXx6d4bs9sG8x8OEeykCXylFpngTKycY5GZ1Kg41k0kn5qvoNU4co1iq0oe7qyK3h57EKbzbDsfjI9P4EwkRhbTmBAKVDiyTOxpYVYMPgbrBvwXaGjy6tit9FEKRRS4L0HoPwBsgTPBr7hXBAlD5vh90CdZy8Pvb102X6fBVvtlWQOGchnm3REnoA0QgpO+4nuiaqy5DrxP8LRsJZCcCKHNQQFJyOGnOLIvFSzEpyFY6CQhojQnlA+ES1adAewmT/ecby1uo/qUW+JR8TopUpd2YYUc+wNRQSUYTe7mB4YCkqy5+Ut8HCsPU/4rmHNdSGqEKErJhFyvKBERS7S0BTcIVTY+t+9MYeQWT6vXUrvC4ZCyI9B8vCfgUJ9/sREbhS1Axu3VanWmR0un7FjYvE8wJmCyU8Rffr1hEuOTm+mX2rdjAfruXhLFaRIWujnKzyl8vR7BQfZc49TdZwxkHoAAMmi3FbYl3lVE+1+gRpXt5fT0wJD77qM7E5phtR91FI0/3U09iibiZgPdExMfr2Lmoyvhanxm/Wtxdyy4zqplBUSOaMhzFz1ti/o7Da2bp/pDk5HWaCvE1eJ5BJV4FJaDGvyMeV/1qfnYB6VO+Qra6CnfXm8huLEBT8tLRGfD5t6RqilIE42fDyuhgYA82ir8i2EACvWVb1H3bosCJXfgPBp3wh/eBtUXfRKrBtBquBd02re+YkMRoEtagNebJYJHmcLsQHY8KAptp77Yi7Ld/zLlRB3IZ6fDvM2qLIjXUKbkt2+Ww2QaFeCT5sdMJQDnt9n/Djz8Ay4IxDfJQXOTgpC27X50xQgbKJS+NH5cNWrW9UT2ELZyUcl1R7SH34MnQGbnFg4SDM1FuXbdCBRd3LeTtDKombs97vTSahnQUMvrMAOqKqjRNkrT4u5AHosgaxXapBOaHSocnMAIwDpW0D0vhkO+6Gihbfq55GA6f415nxCB1l7z4YdKcp07jGBgjAjBgkqhkiG9w0BCRUxFgQUQsppdBcRCy81DhSAqag8yfhLyIkwWwYJKoZIhvcNAQkUMU4eTABRAHUAYQBuAHQAdQBtAHUAbAB0ACAAWAAgAEMAQQAgADUARAAwAEEANAAyADAAQQAgACgAMQA3ACAAUwBlAHAAIAAyADAAMgAyACkwLTAhMAkGBSsOAwIaBQAEFJO/d9syN3dSTINhEpsvgbZcCmCrBAjPFWKSKFOq+g==
skip_validating_cert = true
