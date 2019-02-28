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


#初始上传
git init
git remote add origin git@github.com:mgtvott/SettingDiff.git
git add .
git commit -m "first commit"
git push origin -u master

如果上传时报错，则先git pull，如果这时git pull出现“fatal: refusing to merge unrelated histories“，则先执行

git pull origin master --allow-unrelated-histories

然后重新执行：git push origin mastermaven，如果没有报错则，文件已经会上传到github。 
