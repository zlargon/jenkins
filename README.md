Jenkins 在 Mac 上的簡易安裝與設定
====

* ##### 因為工作上的需求, 開始研究 Jenkins 的使用, 雖然說 Jenkins 現在已經有提供安裝包, 省去了很多需要用 command line 去設定的事情, 但是還是有一些需要在安裝的時候需要注意的地方, 所以在這裡記錄了下來.
* ##### 因為是打算 build objective-C 的 code, 所以我們必須將 Jenkins 架在有 xcode 環境的電腦上, Jenkins 雖然能夠自動的作很多事情, 但是前提是你電腦裡面要有那些工具給他使用, 總不能叫他在 windows 上 build xcode 的 project 吧!
* ##### 這邊也會講到一些簡單的設定, 以及一些在這裡用到的套件使用說明, 所以不只有安裝完就結束了.
* ##### 其實這是我第一次作 GitBook, git 也是最近才學的, 那之前有幾個主題都是直接使用 github 中的 gist, 就簡單為主\(其實是甚麼都還不會...\), 所以希望閱讀的人有甚麼改進的意見能提出, 當然前提是有人來閱讀這份 GitBook 啦~XD
* #### 那開始吧!
