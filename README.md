Translate synergistically embedded android
===========================



##描述:

* 大家业余时间充分利用起来，练练英语，学学android 
协同分工：
史思远：我选第１章了，大家别跟我抢啊。。
王新锋：第二章，我先翻译着，比较晦涩～
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

##markdown [help](https://help.github.com/articles/markdown-basics/)

##Contents

###Preface
###1. Introduction
* History
* Features and Characteristics
* Development Model
* Differences From “Classic” Open Source Projects 
* Feature Inclusion, Roadmaps, and New Releases
* Ecosystem
* A Word on the Open Handset Alliance
* Getting "Android"
* Legal Framework
* Code Licenses
* Branding Use
* Google’s Own Android Apps 
* Alternative App Markets
* Oracle versus Google
* Mobile Patent Warfare
* Hardware and Compliance Requirements
* Compliance Definition Document
* Compliance Test Suite
* Development Setup and Tools

###2. Internals Primer
* App Developer’s View 
* Android Concepts
* Framework Intro
* App Development Tools
* Native Development
* Overall Architecture
* Linux Kernel
* Wakelocks
* Low-Memory Killer
* Binder
* Anonymous Shared Memory (ashmem)
* Alarm
* Logger
* Other Notable Androidisms
* Hardware Support
* The Linux Approach
* Android’s General Approach 
* Loading and Interfacing Methods
* Device Support Details
* Native User-Space
* Filesystem Layout
* Libraries
* Init
* Toolbox
* Daemons
* Command-Line Utilities
* Dalvik and Android’s Java 
* Java Native Interface (JNI)
* System Services
* Service Manager and Binder Interaction
* Calling on Services
* A Service Example: the Activity Manager
* Stock AOSP Packages
* System Startup

###3. AOSP Jump-Start
* Development Host Setup
* Getting the AOSP
* Inside the AOSP
* Build Basics
* Build System Setup
* Building Android
* Running Android
* Using the Android Debug Bridge (ADB)
* Mastering the Emulator

###4. The Build System
* Comparison with Other Build Systems
* Architecture
* Configuration
* envsetup.sh
* Function Definitions
* Main Make Recipes
* Cleaning
* Module Build Templates
* Output
* Build Recipes
* The Default droid Build
* Seeing the Build Commands
* Building the SDK for Linux and Mac OS
* Building the SDK for Windows
* Building the CTS
* Building the NDK
* Updating the API
* Building a Single Module
* Building Out of Tree
* Building Recursively, In-Tree
* Basic AOSP Hacks
* Adding a Device
* Adding an App
* Adding an App Overlay
* Adding a Native Tool or Daemon
* Adding a Native Library

###5. Hardware Primer
* Typical System Architecture
* The Baseband Processor
* Core Components
* Real-World Interaction
* Connectivity
* Expansion, Development, and Debugging
* What’s in a System-on-Chip (SoC)? 
* Memory Layout and Mapping
* Development Setup
* Evaluation Boards

###6. Native User-Space
* Filesystem
* The Root Directory
* /system
* /data
* SD Card 
* The Build System and the Filesystem
* adb
* Theory of Operation
* Main Flags, Parameters, and Environment Variables
* Basic Local Commands
* Device Connection and Status
* Basic Remote Commands
* Filesystem Commands
* State-Altering Commands
* Tunneling PPP
* Android’s Command Line 
* The Shell Up to 2.3/Gingerbread
* The Shell Since 4.0/Ice-Cream Sandwich
* Toolbox
* Core Native Utilities and Daemons
* Extra Native Utilities and Daemons
* Framework Utilities and Daemons
* Init
* Theory of Operation
* Configuration Files
* Global Properties
* ueventd
* Boot Logo

###7. Android Framework
* Kick-Starting the Framework
* Core Building Blocks
* System Services
* Boot Animation
* Dex Optimization
* Apps Startup
* Utilities and Commands
* General-Purpose Utilities
* Service-Specific Utilities
* Dalvik Utilities
* Support Daemons
* installd
* vold
* netd
* rild
* keystore
* Other Support Daemons
* Hardware Abstraction Layer

###A. Legacy User-Space
###B. Adding Support for New Hardware
###C. Customizing the Default Lists of Packages
###D. Default init.rc Files
###E. Resources
###Index
