# 中文版本
- 请在本版本下方查看英文版本说明。
# 投资辅助分析工具
- 该工具是可以辅助您进行投资分析的小工具。

## 版本
- 目前版本为：0.5.0
>- 该版本并不是正式版。
>- ! 目前仅支持简体中文。

## 运行
- 使用源代码的话，请首先确认您的环境中有安装NPM以及Node.js，之后使用如下命令：
- >npm install
- >npm install electron -g（如果已经安装请忽略)
- >npm install electron-forge -g （如果已经安装请忽略）
- >electron-forge start

## 开发工具
>- [Electron](https://github.com/electron/electron)
>- [jQuery](https://jquery.com)
>- [DataTable](https://datatable.org)
>- [numeral](http://numeraljs.com/)

## 当前功能
- [x] 分析并确认当前是否入市的好时机
- [x] 自动筛选出可转债组合，白马股组合以及便宜组合
- [x] 在已筛选组合表中，仍然可以二次筛选和排序，感谢DataTable
- [x] 通过不同背景颜色，快速区分类型
- [x] 增加了可转债平均市价，以及跳转到富投网的链接
- [x] 增加了中证全指温度


## 下一步
- [ ] 投资时间和金额记录
- [ ] 基金定投日期/时间提醒
- [ ] 自动计算收益率
- [ ] 更多，待增加……

## 去除
- [x] 暂时去除了自动升级功能，因为没有适用的签名证书，抱歉！

-------------------------------------------------------------------------------------------------------------
# English Version
- Please check Chinese version on the top.
# Investment Analysis Tool
- This is the Investment Analysis Tool to help you to improve investment decision.

## Version
- Current version is: 0.5.0
>- Not a release ready version yet.
>- ! Only support Chinese for current version

## Run
- With source code, please confirm you have Node.js and NPM installed first:
- >npm install
- >npm install electron -g（Ignore if already installed)
- >npm install electron-forge -g （Ignore if already installed）
- >electron-forge start

## Development Tools
>- [Electron](https://github.com/electron/electron)
>- [jQuery](https://jquery.com)
>- [DataTable](https://datatable.org)
>- [numeral](http://numeraljs.com/)

## Current Functions
- [x] Analysis and confirm if the correct time entrance into stock market is now
- [x] Automatically filter the list of Convertable Bonds, stocks of good companies and cheap enough to buy in
- [x] Support filter and ordering inside tables, thanks for DataTable
- [x] Quickly notice the differences base on differnt background color
- [x] Added CB average price, and the redirect link to [richvest.com](http://www.richvest.com/)
- [x] Added long term investment temporature of CSI All Share Index

## Next Steps
- [ ] Invest time and number recording
- [ ] Reminder of invest time / date point
- [ ] Automatically calculator of yield
- [ ] etc...

## Removed Functions
- [x] Removed the Auto-update feature temporarily due to I cannot get a valid code-signing certificate yet, sorry for that!
