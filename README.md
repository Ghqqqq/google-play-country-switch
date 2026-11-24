# Google Play 转区

一个 Codex 技能，用于核对 Google Play 当前地区、检查目标地区的支付资料，以及尝试在不绑卡的情况下进入转区确认页。

## 安装

```sh
git clone https://github.com/Ghqqqq/google-play-country-switch.git "${CODEX_HOME:-$HOME/.codex}/skills/google-play-country-switch"
```

## 使用

在 Codex 中输入：

> 用 $google-play-country-switch 检查当前 Google Play 地区，看看能不能免绑卡切到新加坡。

技能会用同一个已登录的账号检查 Play 地区和支付资料。如果需要新建资料，可以停在地址表单，由账号持有人直接填写并提交。到达转区确认页后，按用户的授权范围继续。

## 实测范围

在一次中国 Play 转新加坡的流程里，创建新加坡支付资料后，原本禁用的新加坡选项变为可选，无需绑卡即可进入转区确认页。该次测试核验到了确认阶段。实际切区和 Google One 结账需要分别核验。Google 的现行要求以官方说明和账号页面为准。

[Google Play 官方转区说明](https://support.google.com/googleplay/answer/7431675) · [Google 支付资料说明](https://support.google.com/faqs/answer/7644076)
