---
layout: post
title: "如何快速选择开源软件协议"
date: 2016-07-22 10:00:00
description: "如何快速选择开源软件协议,How to easy chose and opensource license for your project"
keywords: "opensource,license,MIT,Apache,GPL,GPL2,GPL3"
permalink: /2016/07/22/easy-chosing-opensource-license/
categories:
- opensource 
- license
tags:
- opensource
- license
---

![](/images/2016-07-22-easy-chosing-opensource-license/14691964599348.jpg)

### 一、背景介绍
目前开源协议有很多，同一款协议也衍生出了许多变种。开源世界中，我们可以使用合适的开源协议，保证自己作品的版权。   
我们这里不做过多的介绍，只介绍一些自己常用的三个选择及其理由，以供参考。

### 二、详细描述
#### 2.1 “我需要一个简单宽松的协议”  
MIT License是一个简短、宽松、自由的协议。该协议允许人们使用你的代码，但必须要保留你的版权信息。与此同时，并不会给你带来任何责任和风险。`jQuery`,`.NET Core`和`Rails`使用的均是MIT License。

```
The MIT License (MIT)
Copyright (c) <year> <copyright holders>

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
```

#### 2.2 “我更加关心自己的专利”
Apache License 2.0是一项和MIT License相似的协议，但自己希望自己的专利能在开源免费使用的同时，保留自己在开源产品中的专利权益。同样，该协议要求使用者必须保留你的版权信息。  
`Android`, `Apache`和`Swift`使用的均是Apache License 2.0协议。

```
Apache License Version 2.0
Copyright [yyyy] [name of copyright owner]

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```

#### 2.3 “我关心代码的分享以及促进”
如果你希望别人在分享的自己的作品之后，也必须遵循相同的协议，也必须是开源和免费。那么GPLv3是你更好的选择。该协议当中也明确地包含了贡献人的专利权益方面的款项。原作品的版权条款也必须延续保留。GPL协议存在非常强的“传染性”
`Bash`, `GIMP`和`Privacy Badger`使用的均是GPLv3协议。

```
GNU GENERAL PUBLIC LICENSE Version 3
Copyright (C) {year}  {name of author}

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>.
```

如果你的产品是基于终端的，你还可以加上如下一段，使得使用者知晓如何可以联系到你。

```
{project}  Copyright (C) {year}  {fullname}
This program comes with ABSOLUTELY NO WARRANTY; for details type `show w'.
This is free software, and you are welcome to redistribute it
under certain conditions; type `show c' for details.
```

### 三、参考资料
- Opensource License：[http://choosealicense.com/licenses/](http://choosealicense.com/licenses/)
- 各种开源协议介绍：[http://www.open-open.com/solution/view/1319816219625](http://www.open-open.com/solution/view/1319816219625)
- 开源那么重要，开源协议你认识吗？[http://yeyuan.baijia.baidu.com/article/43303](http://yeyuan.baijia.baidu.com/article/43303)

