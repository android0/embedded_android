Translate synergistically embedded android
===========================



##描述:

* 大家业余时间充分利用起来，练练英语，学学android 


##github help

* 初始化项目
1. 进入项目地址，先fork这个项目到你的项目中
2. 把你fork的项目clone到你本地
3. `git branch dev` 新建一个分支
4. `git checkout dev` 切换到dev分支
5. `git remote add upstream https://github.com/android0/embedded_android` 把项目添加你的远程仓库
6. `git remote update` 把android0的分支拿到你本地
7. `git fetch upstream master` 把android0的maser分支更新到本地
8. `git rebase upstream/master` 更新合并
9. 如果你完成修改，使用 `git push -u origin dev` 提交更新
10. 然后进入你的github网站申请pull request

日常更新，之后更新使用如下命令

1. `git remote update upstream`  把android0的修改更新到本地
2. `git rebase upstream/master` 更新合并



##Contents

* Preface
* 1. Introduction  
 * History      
 * Features and Characteristics         
 * Development Model            
 * Differences With "Classic" Open Source Projects      
 * Feature Inclusion, Roadmaps, and New Releases        
 * Ecosystem    
 * A Word on the Open Handset Alliance 
 * Getting "Android" 
 * Legal Framework 
 * Code Licenses 
 * Branding Use 
 * Google's Own Android Apps 
 * Alternative App Markets 
 * Oracle v Google 
 * Hardware and Compliance Requirements 
 * Compliance Definition Document 
 * Compliance Test Suite 
 * Development Setup and Tools 

* 2. Internals Primer
 * App Developer's View 
 * Android Concepts 
 * Framework Intro 
 * App Development Tools 
 * Native Development 
 * Overall Architecture 
 * Linux Kernel 
 * Wakelocks 
 * Low Memory Killer 
 * Binder 
 * Anonymous Shared Memory (ashmem) 
 * Alarm 
 * Logger 
 * Other Notable Androidisms 
 * Hardware Support 
 * The Linux Approach 
 * Android's General Approach 
 * Loading and Interfacing Methods 
 * Device Support Details 
 * Native User-Space 
 * Filesystem layout 
 * Libraries 
 * Init 
 * Toolbox 
 * Daemons 
 * Command-Line Utilities 
 * Dalvik and Android's Java 
 * Java Native Interface (JNI) 
 * System Services 
 * Service Manager and Binder Interaction 
 * Calling on Services 
 * A Service Example: the Activity Manager 
 * Stock AOSP Packages 
 * System Startup 

* 3. AOSP Jumpstart 
 * Getting the AOSP      
 * Inside the AOSP       
 * Build Basics          
 * Build System Setup 
 * Building Android 
 * Running Android 
 * Using ADB 
 * Mastering the Emulator 

* 4. The Build System
 * Comparisons With Other Build Systems 
 * Architecture 
 * Configuration 
 * envsetup.sh 
 * Directive Definitions
 * Main Make Recipes 
 * Cleaning 
 * Module Build Templates 
 * Output 
 * Build Recipes 
 * The Default droid Build 
 * Seeing the Build Commands 
 * Building the SDK for Linux and MacOS 
 * Building the SDK for Windows 
 * Building the CTS 
 * Building the NDK 
 * Updating the API 
 * Building a Single Module 
 * Building Out of Tree 
 * Basic AOSP Hacks 
 * Adding an App 
 * Adding a Native Tool or Daemon 
 * Adding a Native Library 
 * Adding a Device 
 * Adding an App Overlay
