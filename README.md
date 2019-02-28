# SettingDiff

# 使用方式

 在项目的根目录的build.gradle文件中添加如下代码：
 
      maven {
            url "https://raw.githubusercontent.com/mgtvott/SettingDiff/master"
        }
        
        
在需要使用该库的build.gradle文件的dependencies添加依赖， 代码如下

dependencies {

    ......省略其它依赖
    implementation 'com.mgtv.setting.diff.fac:settingDiff:1.0.0-SNAPSHOT'
   
}       
        
