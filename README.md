贝壳单词v2.0下载：

全新 Material Design UI；  
新增 用户系统和自定义头像功能；  
新增 『自建词库』；  
新增 『英语角』功能；  
新增 『理念』页面和指引等页面；  
新增 各种动感、动画效果；  
新增 全局滑动返回；  
新增 许多隐藏彩蛋；  
更加 精致、易用，和人性化；  
随着 2.0这两天会也发布更多新精品词库。  
如履薄冰，小心翼翼，不懈追求~~  

<img src="http://www.tuili.com/blog/UploadFiles/2015-1/10919559348.png" width="256" height="256">

## 最新更新内容：
1. 修复 刷新问题，并新增下拉刷新；
2. 修复 一些小纰漏；
3. 新增 长按单词可以加入收藏（考虑到美观的原因，所以目前暂时这样）；
4. 新增 『我的收藏』页面，可浏览收藏单词也可以长按删除单词；
5. 新增 人性化的自由开关，可自由设置是否在通知栏显示音标；
6. 新增 当贝壳消息处在最顶上的时候，会自动展开成大的 View 显示例句和解释，效果很棒！（感谢[Robert Liu](https://github.com/lsanotes)的贡献）

另外，还有很多新提出的设计想法和任务，非常欢迎有人能一起参与，见这个 issue：https://github.com/drakeet/Seashell-app/issues/1


## 前言
这个app是我在大二下学期考试期间背单词的时候突发奇想，并花了大概4天的时间做出来的，所以有很多地方可能写得不好，或者很多功能点没有写完，考虑到目前还有另外一些项目特别忙，于是将这个项目开源了，逻辑很简单，代码也不多，但对于 Android 初学者能够快速学习到几项比较基本常用的开发知识(●'◡'●)ﾉ♥ 我在最近也进行了一些更新，特别欢迎和希望能够有人和我一起来学习以及有空完善它^ ^

## 介绍

背单词的时候我就想，百词斩做得再好，用户不愿意打开就根本没用，那怎么做一个好的背单词应用呢？

我觉得只要常驻通知栏，【每天在通知栏显示一个单词就够了】，通知栏浏览率那么高，托QQ的福，每次顺便瞟一眼，就像我们认识一个人一样，多看几眼，也就认识了。因此，背单词根本就是顺便且无意识无压力的事，一年好歹能记牢365个单词^ ^ 不行的话隔周复习，或两天一个也行，记不住也不会责备你要求你，反正就是无压力无压力非常无压力……地背单词~~~于是我花了两个早上的时间开发完成了这个毫无压力的背单词应用，贝壳单词，它保证你一年365天都能够非常轻松愉快地背单词。

“贝壳单词”，谐音“背个单词”，贝壳比喻通知栏，贝壳中孕育珍珠。在极低耗电量极低占内存的情况下，自动隔天更新一个单词至通知栏，隔周自动复习。可以查看今日与昨日的单词，未来还将设置用户自选词库和本地词库。从此，大学的英语课即使不上了，也不必再担心英语日渐倒退，因为你每一天都在无意识之中稳步前进……

#### 注：

* 我在取这个名字之前，在各大应用商店搜索了一番，发现并没有叫贝壳单词的，并且也觉得很不错，就果断用了，后来才发现有一个背单词应用叫做『扇贝单词』orz，也就是说，绝对不是看了人家的名字而去模仿人家，因为那时我根本不知道扇贝单词，而且我们做的事情其实是不一样的，我也觉得我们的贝壳单词更有喻意哈。

* 现在看来，当初的代码写得不是很得体，不是很好，并且我也不能花费太多时间来维护它，如果你不喜欢背单词，所以如果你喜欢这个创意，这是一个能够长期占领通知栏的应用，嘻嘻，目前小米应用商店日下载量大概稳定在200左右，特别特别欢迎有人能够来和我一起维护它，我们便可以把开发者的名字一起写在应用的『关于』里面了~~

## App store:

豌豆荚设计奖及更多理念：http://www.wandoujia.com/award/blog/me.drakeet.seashell

小米：http://app.mi.com/detail/65475  360：http://zhushou.360.cn/detail/index/soft_id/1814521


我的博客：http://drakeet.me

## 截图

<img src="/screenshots/v13/main.jpg" alt="main" title="screenshot" width="300" height="500" />
<img src="/screenshots/v13/drawer.jpg" alt="main" title="screenshot" width="300" height="500" />
<img src="/screenshots/v13/notify.jpg" alt="main" title="screenshot" width="300" height="500" />
<img src="/screenshots/v13/already.jpg" alt="main" title="screenshot" width="300" height="500" />
<img src="/screenshots/v13/about.jpg" alt="main" title="screenshot" width="300" height="500" />
![截图](/screenshots/s6.png)

## 未修复BUG
未知，暂无^ ^

## 用到的开源库
* SimonVT / android-menudrawer : 侧滑菜单
* LitePalFramework / LitePal : 数据库 ORM
* MarkMjw / PullScrollView : UI 框架
* flavienlaurent / NotBoringActionBar : 已背单词页面
* msdx / androidkit : 目前只用于双击退出
* Google / Gson
* drakeet / MaterialDialog Material Design 对话框兼容库

（我会再找时间梳理一下代码，并且在`README.md`中写明代码结构和各项逻辑关系^ ^）

## 关于我
我的博客：http://drakeet.me
邮箱：drakeet.me@gmail.com

License
============

    Copyright 2014 drakeet

	Licensed under the Apache License, Version 2.0 (the "License");
	you may not use this file except in compliance with the License.
	You may obtain a copy of the License at

     http://www.apache.org/licenses/LICENSE-2.0

	Unless required by applicable law or agreed to in writing, software
	distributed under the License is distributed on an "AS IS" BASIS,
	WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
	See the License for the specific language governing permissions and
	limitations under the License.
