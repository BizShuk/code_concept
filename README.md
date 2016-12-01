# Code concept

### Specific term
- DRY: Don't Repeat Yourself. ex: FizzBuzz
# web tech



- [Service Worker list in Chrome](chrome://serviceworker-internals) 
- [offline cookbook](https://jakearchibald.com/2014/offline-cookbook/)

# Linux

Linux
- [Linux Document Project](http://tldp.org/)



### basic 
1，針對物件導向的設計與分析：為了讓軟體有更好的可維護性，重用性以及快速開發， 簡短的OOAD與它的SOLID原則對於每一個軟體工程師來說都是該牢記的。  
2，軟體品質因素：軟體工程的好壞與軟體的品質因素是絕對關聯的。請在開發過程中深 刻的理解這一點。  
3，資料結構與演算法：深刻理解像陣列，清單，棧，樹，圖，集合等這樣的基本資料結構 ，並在軟體發展過程的關鍵部分使用好的演算法。這樣整個軟體邏輯就會很清晰了。  
4，Big-O符號來標記演算法複雜度：在開發過程中，請務必使用 Big-O 符號來比較兩個代 碼段或者不同演算法所消耗的時間複雜度，這在開發高性能軟體專案中是非常重要的。  
5，UML圖：UML圖已經是一個通用的軟體設計與分析的語言。如果你們在開發軟體的過程 中還沒有做UML圖，那麼給人的感覺就是這壓根就不是軟體工程。  
6，正確的衡量軟體發展進度。  
7，設計模式：設計模式是前人在解決各種各樣問題的過程中總結出來的一套標準對策， 在絕大部分情況下，使用這些模式肯定是利大於弊的。如果你不想在開發過程中重新造 輪子，那麼就直接使用它吧。   
8，理解作業系統的基本原理：因為所有的應用程式都是直接運行在作業系統這個層級的 ，學習作業系統的基本原理能讓我們對應用程式的底層以及性能有更好的把握。  
9，學習計算機組成原理：幾乎所有的應用程式甚至是OS都需要與物理硬體打交道的，所 以學習計算機組成原理與理解作業系統原理一樣都可以讓你對於應用程式有更深刻的理 解。  
10，網路基礎：網路與計算機組成，作業系統以及傳輸流程都是緊密關聯的，理解網路基礎 能讓你在開發過程中得心應手。  
11，需求分析：對於軟體工程來說，需求分析是項目的起點，也是整個項目最最重要的 部分。如果這玩意你搞錯了，整個項目的方向也就錯了。  
12，軟體測試：在軟體工程中，測試也是非常重要的。單元測試，黑盒測試，白盒測試，TDD，集成測試等等都是我們必須知道的。  
13，獨立管理：主要是說類庫(JAR,DLL等等)的管理，熟悉使用一些類似Maven,Ant,lvy這樣的知名工具對於大型專案的類庫管理是非常有用的。  
14，持續化集成：持續化集成能讓測試大型模組與元件更加簡單與自動化，關於這一點，你可以去瞭解 Hudson 這個工具。  
15，ORM：瞭解Hibernate這種將物件與資料庫表映射工具是非常有好處的，它可以減少你的代碼量並節省你的代碼維護時間。  
16，DI(獨立注入)：DI或者IoC(Inversion of Control)的具體實現框架Spring能讓你創建物件時更加輕鬆，對於大型企業級項目更是如此。  
17，版本控制系統：VSC工具(SVN,TFS,CVS等)對於團隊合作開發以及版本控制都是非常重要的。熟練使用這類工具算得上是必備技能。  
18，國際化：通過i18n來將不同語種的字串存儲在其他檔是讓軟體支援多語種最好的方法。所以i18n在不同的IDE上使用的方法我們應該瞭解。  
19，架構模式：理解類似MVC,MVP,MVVM這樣的架構模式非常關鍵，這能讓你寫出易維護，簡潔以及方便測試的代碼。  
20，編寫乾淨的代碼：你的代碼僅僅只是能夠正常運行是遠遠不夠的，它必須讓程式設計人員輕易看懂來方便後續維護，所以，代碼格式以及編寫易讀的代碼技術都是我們需要瞭解的關鍵點。  




### Object-Oriented
[HERE](OO.md)

##### Thread Safe
avoid race condition.

##### Immutable Object
assign to other variable , keep original one the same.

##### Other lock
- Semaphore, countable lock
- ReadWriteLock, seperate read and write

##### Deadlock
A
```
lock a
    lock b
```

B
```
lock b 
    lock a
```

### Flow Control

##### Producer Consumer pattern
a


### Multi-Thread
- [java multi-thread](https://popcornylu.gitbooks.io/java_multithread/content/thread.html)

##### Thread pool




### Service

##### HotSpot
trigger quantiies of service in the same time

### 
- [string](string.md)

- Call by other code in protection mode
- Async way
- Memory Limit
- File lock
- Race Condition
- Singleton
- shadow
lazy
