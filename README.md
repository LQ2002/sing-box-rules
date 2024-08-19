# 仅自用

## 规则推荐：
> https://github.com/Yuu518/sing-box-rules  
> https://github.com/MetaCubeX/meta-rules-dat  
> https://github.com/xmdhs/sing-box-ruleset  
> https://github.com/TG-Twilight/AWAvenue-Ads-Rule

## 规则转换命令:
` sing-box rule-set compile --output Example-final.srs Example.json `

## sing-box配置转换
> https://github.com/xmdhs/clash2sfa

## json:
```
{
        "type": "remote",
        "format": "source",
        "download_detour": "direct",
        "tag": "aws-ip",
        "url": "https://raw.githubusercontent.com/LQ2002/sing-box-rules/main/aws-ip.json"
}
```
## srs:
```
{
        "type": "remote",
        "format": "binary",
        "download_detour": "direct",
        "tag": "aws-ip",
        "url": "https://raw.githubusercontent.com/LQ2002/sing-box-rules/main/aws-ip.srs"
}
```
## .srs To .json
```
sing-box rule-set decompile Example.srs -o Example.json
```
