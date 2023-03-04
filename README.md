# 🛡️Tiktok_Signature

> Tiktok_Signature 是一个方便快捷的工具，可以帮助你自动生成抖音 xbogus、mstoken 和 ttwid。

## 功能介绍

Tiktok_Signature 工具提供如下功能：

- 生成 xbogus
- 生成 mstoken
- 生成 ttwid

## 快速开始

[![Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/5ime/Tiktok_Signature)

1. 点击上方按钮，跳转至 `Vercel` 进行部署。

2. 输入一个你喜欢的 `Vercel` 项目名称并点击 `Create` 继续:

3. 此时 `Vercel` 会基于 `Tiktok_Signature` 模板帮助你新建并初始化仓库，仓库名为你之前输入的项目名。

    一两分钟后，满屏的烟花会庆祝你部署成功。此时点击 `Go to Dashboard` 可以跳转到应用的控制台。

4. 点击 `Visit` ，即可跳转到部署好的网站地址，此地址即为你的接口地址。

## 请求示例

请发送 `POST` 请求，同时设置 `Content-Type` 为 `application/json`，请求体为如下格式：

```json
{
  "url": "https://www.douyin.com/aweme/v1/web/aweme/detail/?aweme_id=7142091187963399427&aid=1128&version_name=23.5.0&device_platform=android&os_version=2333",
  "userAgent": "Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/109.0.0.0 Safari/537.36"
}
```

返回结果如下：

```json
{
  "code": 200,
  "msg": "success",
  "data": {
    "xbogus": "DFSzswSLS-iANnEfta2O9z9WcBn1",
    "mstoken": "slkG34TBufKXgHND79ANvb86mXE8z8kUheMKR2frR6NpyDLFgZFNLnumOYglmUt5cNqs4Z53C4cSSQ8t5Qw1AAcSxQMZ66t02F38gF1vb72",
    "ttwid": "1%7CMzira2CT0P-CLey42gr9QsEGL_Wmq3Yg5PQF2X412hY%7C1677897397%7C0df7a1da2a44ccac7dda848d236c8d5276d3eae070dfb3fe6df6e86fbd896d93",
    "url": "https://www.douyin.com/aweme/v1/web/aweme/detail/?aweme_id=7142091187963399427&aid=1128&version_name=23.5.0&device_platform=android&os_version=2333&X-Bogus=DFSzswSLS-iANnEfta2O9z9WcBn1"
  }
}
```

## 注意事项

- 本工具仅供学习交流使用，请勿用于非法和商业用途；
- 本工具基于抖音加密算法实现，算法可能会随时更新，故本工具也可能无法正常使用；

## 参考项目

- **https://github.com/aithedev/X-Bogus (原创作者)**

- https://github.com/HH7H/X-Bogus/

- https://github.com/B1gM8c/X-Bogus
