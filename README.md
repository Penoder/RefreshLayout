使用步骤:

Step 1. 在项目的根目录下的 build.gradle 文件中添加

allprojects {
    repositories {
        maven { url 'https://www.jitpack.io' }
    }
}


Step 2. 在项目模块app 下的 build.gradle文件中添加

compile 'com.github.Penoder:RefreshLayout:1.0'
