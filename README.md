[![phpBB](https://www.phpbb.com/theme/images/logos/blue/160x52.png)](http://www.phpbb.com)

## 关于

phpBB是一个用PHP编写的免费开源公告板.

## 社区

获取phpbb的副本，查找支持，并提供更多信息。[phpBB.com](http://www.phpbb.com)! Discuss the development on [area51](http://area51.phpbb.com/phpBB/index.php).

## 安装依赖项

要能够从repo(而不是从预先构建的包)运行安装，您需要运行以下命令来安装phpBB的依赖项。

	cd phpBB
	php ../composer.phar install


## 贡献

1. [在phpBB.com上创建一个帐户](http://www.phpbb.com/community/ucp.php?mode=register)
2. [创建一张票(除非已经有一张)](http://tracker.phpbb.com/secure/CreateIssue!default.jspa)
3. 读我们 [编码准则](https://area51.phpbb.com/docs/dev/development/coding_guidelines.html) 和 [GIT贡献准则](https://area51.phpbb.com/docs/dev/development/git.html)
4. 给我们一个拉的请求

## 开发文档

读我们 [开发文档](phpBB/docs/vagrant.md) 了解如何使用Vagant开发和贡献phpBB。

## 自动测试

为了防止倒退，我们进行了单元测试和功能测试。 您可以查看竹子的连续集成。或者在[这里](https://bamboo.phpbb.com) 查看我们的Travis构建：

* [![Build Status](https://travis-ci.org/phpbb/phpbb.svg?branch=master)](http://travis-ci.org/phpbb/phpbb)[![Build status](https://ci.appveyor.com/api/projects/status/8g98ybngd2f3axy1/branch/master?svg=true)](https://ci.appveyor.com/project/phpBB/phpbb/branch/master) **master** - Latest development version
* [![Build Status](https://travis-ci.org/phpbb/phpbb.svg?branch=3.2.x)](http://travis-ci.org/phpbb/phpbb)[![Build status](https://ci.appveyor.com/api/projects/status/8g98ybngd2f3axy1/branch/3.2.x?svg=true)](https://ci.appveyor.com/project/phpBB/phpbb/branch/3.2.x) **3.2.x** - Development of version 3.2.x
* [![Build Status](https://travis-ci.org/phpbb/phpbb.svg?branch=3.1.x)](http://travis-ci.org/phpbb/phpbb) **3.1.x** - Development of version 3.1.x

## 许可证

[GNU General Public License v2](http://opensource.org/licenses/gpl-2.0.php)
