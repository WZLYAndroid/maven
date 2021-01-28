## maven


项目根目录 build.gradle 添加仓库地址 ：
	
	allprojects {
    	repositories {
			maven { url 'https://wzlyandroid.github.io/maven' }
    	}
	}
	
项目中依赖所需库, 以 test 库为例：

	dependencies {
    	implementation 'com.wzly.module:test:0.0.1'
	} 
