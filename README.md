# com.lew.game.chdr

插花达人 apk 备份

<https://game.xiaomi.com/game/62386340>

## 商店下载直链：

<https://gc.s.migames.com/gdownload/api/c/download?c=app&v=download&package=com.lew.game.chdr.mi&channel=meng_1439_352_android>

10月6日21:56分还在，2026年10月8日上述俩链接已经失效

接口仍返回 HTTP 200，但内容是错误 JSON，不是安装包：

```json
{"cid":"meng_1439_352_android","errCode":10201,"extId":1358773}
```

`errCode 10201` = 商店已下架。去掉 `channel` 参数同样返回 10201，所以不是参数问题。

## 页面已下线证据

![小米游戏中心 404](xiaomi-game-center-404.png)

## github备份下载链接：

（待补）

## 仓库内容

| 文件 | 说明 |
|---|---|
| `README.md` | 本文件 |
| `xiaomi-game-center-404.png` | 小米游戏中心页面 404 截图 |
| `*.apk` | 备份的安装包（走 Git LFS） |

## 应用信息

| 项 | 值 |
|---|---|
| 包名 | `com.lew.game.chdr.mi`（小米渠道版） |
| 版本 | 1.0.2 / 1.1.3（各渠道不一） |
| 大小 | 约 50 MB |
| 类型 | 休闲益智 / 三消 |

> 注：`*.apk` 已配置 Git LFS（见 `.gitattributes`），避免多次备份撑大仓库历史。
> 下载直链请用 Release 或 raw 链接；私有仓库需要带令牌访问。
