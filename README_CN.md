![Image text](https://raw.githubusercontent.com/Deepblue1996/Bun/master/tool/ic_bluetooth.png)

<a href="http://developer.android.com/index.html"><img src="https://img.shields.io/badge/platform-android-green.svg"></a>
[![](https://jitpack.io/v/Deepblue1996/Bun.svg)](https://jitpack.io/#Deepblue1996/Bun)
<a href="https://www.apache.org/licenses/LICENSE-2.0"><img src="https://img.shields.io/badge/license-apache-green.svg"></a>

Bun是一个方便的蓝牙信号库，支持蓝牙发送信号，数据返回操作，它还在不断优化中。

### [不是开源的，只供使用]

[[English document]](https://github.com/Deepblue1996/Dove/blob/master/README.md)

## 如何配置Bun

创建并打开 Application 类,

在 onCreate () 方法中:

<pre><code>com.jiagu.sdk.BlueCoreProtected.install(this);
</code></pre>

## 基础配置

要在构建中加入Git项目:

步骤1. 将JitPack存储库添加到构建文件中

gradle
maven
sbt
leiningen

在根构建中添加它, repositories里添加:

	allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
      		maven { url "https://raw.githubusercontent.com/Deepblue1996/BlueData/master" }
        		maven { url "https://raw.githubusercontent.com/Deepblue1996/BlueCore/master" }
        		maven { url "https://raw.githubusercontent.com/Deepblue1996/Bun/master" }
		}
	}

步骤2. 添加依赖关系

	dependencies {
	        compile 'com.deep:Bun:1.0.0'
	}

步骤3. Gradle

## LICENSE

<pre><code>Copyright 2018 Deepblue

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
</code></pre>
