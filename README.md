
#### 编写规则
```
[custom]
;设置规则标志位
ruleset=📢 Google,https://raw.githubusercontent.com/coswind/rule/master/google.list
ruleset=📹 Media,https://raw.githubusercontent.com/coswind/rule/master/media.list
ruleset=👨🏻‍💻 GitHub,https://raw.githubusercontent.com/coswind/rule/master/github.list
ruleset=🐦 Twitter,https://raw.githubusercontent.com/coswind/rule/master/twitter.list
ruleset=🙌 Custom,https://raw.githubusercontent.com/coswind/rule/master/custom.list?t=1
ruleset=🐟 漏网之鱼,[]FINAL
;设置规则标志位

;设置分组标志位
custom_proxy_group=🚀 节点选择`select`[]🇭🇰 香港节点`[]🇨🇳 台湾节点`[]🇸🇬 狮城节点`[]🇯🇵 日本节点`[]🇺🇲 美国节点`[]🇰🇷 韩国节点`[]🚀 手动切换`[]DIRECT
custom_proxy_group=🚀 手动切换`select`.*

custom_proxy_group=📢 Google`select`[]🚀 节点选择`[]🇸🇬 狮城节点`[]🇭🇰 香港节点`[]🇨🇳 台湾节点`[]🇯🇵 日本节点`[]🇺🇲 美国节点`[]🇰🇷 韩国节点`[]🚀 手动切换`[]DIRECT
custom_proxy_group=📹 Media`select`[]🚀 节点选择`[]🇸🇬 狮城节点`[]🇭🇰 香港节点`[]🇨🇳 台湾节点`[]🇯🇵 日本节点`[]🇺🇲 美国节点`[]🇰🇷 韩国节点`[]🚀 手动切换`[]DIRECT
custom_proxy_group=👨🏻‍💻 GitHub`select`[]🚀 节点选择`[]🇸🇬 狮城节点`[]🇭🇰 香港节点`[]🇨🇳 台湾节点`[]🇯🇵 日本节点`[]🇺🇲 美国节点`[]🇰🇷 韩国节点`[]🚀 手动切换`[]DIRECT
custom_proxy_group=🐦 Twitter`select`[]🚀 节点选择`[]🇸🇬 狮城节点`[]🇭🇰 香港节点`[]🇨🇳 台湾节点`[]🇯🇵 日本节点`[]🇺🇲 美国节点`[]🇰🇷 韩国节点`[]🚀 手动切换`[]DIRECT
custom_proxy_group=🙌 Custom`select`[]🚀 节点选择`[]🇸🇬 狮城节点`[]🇭🇰 香港节点`[]🇨🇳 台湾节点`[]🇯🇵 日本节点`[]🇺🇲 美国节点`[]🇰🇷 韩国节点`[]🚀 手动切换`[]DIRECT

custom_proxy_group=🐟 漏网之鱼`select`[]🚀 节点选择`[]DIRECT`[]🇭🇰 香港节点`[]🇨🇳 台湾节点`[]🇸🇬 狮城节点`[]🇯🇵 日本节点`[]🇺🇲 美国节点`[]🇰🇷 韩国节点`[]🚀 手动切换
custom_proxy_group=🇭🇰 香港节点`select`(港|HK|hk|Hong Kong|HongKong|hongkong)
custom_proxy_group=🇯🇵 日本节点`select`(日本|川日|东京|大阪|泉日|埼玉|沪日|深日|JP|Japan)
custom_proxy_group=🇺🇲 美国节点`select`(美|波特兰|达拉斯|俄勒冈|凤凰城|费利蒙|硅谷|拉斯维加斯|洛杉矶|圣何塞|圣克拉拉|西雅图|芝加哥|US|United States)
custom_proxy_group=🇸🇬 狮城节点`select`(新加坡|坡|狮城|SG|Singapore)
custom_proxy_group=🇨🇳 台湾节点`select`(台|新北|彰化|TW|Taiwan)
custom_proxy_group=🇰🇷 韩国节点`select`(KR|Korea|KOR|首尔|韩|韓)
;设置分组标志位

enable_rule_generator=true
overwrite_original_rules=true
```
