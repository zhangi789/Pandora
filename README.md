# pandora 
## 个人收藏的Android常用自定义控件。其主要功能有：
### 1.   封装MVP框架
### 2.   网络请求Rxjava2+Retrofit+rxlifecycle2的完美封装
### 3.   ImageSelector图片选择器
### 4.   基础工具类

# 集成AS 
> Step 1.先在 build.gradle(Project:XXXX) 的 repositories 添加:

	allprojects {
		repositories {
			...
			maven { url "https://jitpack.io" }
		}
	}
> Step 2. 然后在 build.gradle(Module:app) 的 dependencies 添加:

	dependencies {
	
	         implementation 'com.github.zhangi789:pandora:3.1.2'
	}
