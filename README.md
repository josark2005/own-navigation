# MY Navigation

[![](https://data.jsdelivr.com/v1/package/gh/jokin1999/my-navigation/badge)](https://www.jsdelivr.com/package/gh/jokin1999/my-navigation)

一个轻量级自动根据目录动态生成导航的PHP程序，一个文件创造一整个导航。

![Preview](./preview.png)

## 概要

此程序用户快速导航到多个子网站，导航程序只寻找其所在目录下的子文件夹（不寻找`.`开头的文件夹）并展示链接便于用户快速进入。

## 文件结构

- `nav.php` 导航程序
- `.own_conf.example` 主配置文件案例
- `.own_navi.example` 自定义导航信息配置

## 环境要求

- PHP 7.0 或更新版本

## 快速安装

- 下载[nav.php](https://cdn.jsdelivr.net/gh/jokin1999/my-navigation@latest/nav.php)至站点根目录

## 快速配置

```bash
cp ./.own_conf.example ./.own_conf
```

修改`.own_conf`文件即可

## 自定义导航名称

- 拷贝`.own_navi.example`文件到需要导航的文件夹并命名为`.own_navi`
- 修改`.own_navi`

## 鸣谢

界面借鉴：[MikuTools](https://github.com/Ice-Hazymoon/MikuTools)

## LICENSE

MIT LICENSE
