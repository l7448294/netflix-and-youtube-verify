# 本项目基于[netflix-all-verify](https://github.com/quzard/netflix-all-verify) 修改,增加了对youtube premium批量检测的功能

youtube premium后台播放
简单加了个参数-t 0是检测nf -t 1 是检测youtube premium

```bash
./main -t 1
```
  
# netflix-all-verify

NetFlix批量检测,golang编写

Netflix的大规模封锁,网上的Netflix检测脚本只有本地检测的功能, 因而诞生了本项目

本项目基于[netflix-verify](https://github.com/sjlleo/netflix-verify) 修改,增加了对批量检测的功能

## 使用方法

在终端运行 netflix-all-verify后输入clash的订阅地址

```bash
./netflix-all-verify
```

## 未来工作

- [x] 集成clash，不依靠客户端
- [x] 落地机ip检测,检测复用ip
- [x] 导出为Excel
- [ ] 内置订阅转换,便于不同订阅地址的使用
- [ ] web界面
- [ ] 结果导出图片化
- [ ] 测速

## 感谢

1. 感谢 [netflix-verify](https://github.com/sjlleo/netflix-verify)
2. 感谢 [clash](https://github.com/Dreamacro/clash)
