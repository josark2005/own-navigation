# MY Navigation

[![](https://data.jsdelivr.com/v1/package/gh/jokin1999/my-navigation/badge)](https://www.jsdelivr.com/package/gh/jokin1999/my-navigation)

一个轻量级自动根据目录动态生成导航的PHP程序，一个文件创造一整个导航。

![Preview](./preview.png)

## 概要

此程序用户快速导航到多个子网站（相当于一个程序），导航程序只寻找其所在目录下的子文件夹（不寻找`.`开头的文件夹）并展示链接便于用户快速进入。

## 特性

- 开箱即用
- 支持分组
- 中文文档
- 界面美观

## 文件结构

- `nav.php` 导航程序（重命名为`index.php`可设置为主页）
- `.own_conf.example` 主配置文件案例
- `.own_navi.example` 自定义导航信息配置

## 环境要求

- PHP 7.0 或更新版本

## 快速安装

- 下载[nav.php](https://raw.githubusercontent.com/jokin1999/my-navigation/master/nav.php)至站点根目录

```bash
wget https://raw.githubusercontent.com/jokin1999/my-navigation/master/nav.php
# 下载配置文件(download configuration file)
php nav.php dc
# 下载子目录的配置文件(download configuration file)
php nav.php dces
```

- 可根据需要修改`nav.php`为`index.php`（设为主页）
- 设为主页后`php nav.php`命令需要修改为`php index.php`即可调用

## 配置

```bash
# 下载配置文件(download configuration file for navigation)
php nav.php dc
# 编辑 .own_conf
```

## 自定义导航设置

```bash
# 下载子目录的配置文件(download configuration file for each subfolder of navigation)
php nav.php dces
# 复制 .own_navi.example 到需要自定义设置的子文件夹并重命名为 .own_navi
cp ./.own_navi.example ./[your_subfolder]/.own_navi
# 编辑 ./[your_subfolder]/.own_navi
```

## 命令行模式
```bash
php nav.php [COMMAND]
    dc      下载配置文件
    dces    下载子目录的配置文件
```


## 鸣谢

界面借鉴：[MikuTools](https://github.com/Ice-Hazymoon/MikuTools)

## LICENSE

MIT LICENSE
