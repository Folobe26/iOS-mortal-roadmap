# iOS-Mortal-Roadmap

This repo provides common roadmap for characterless iOS developers to a higher level.

Feel free to add PR or issues.


<table>
<tr>
<td>Basic tools
<ul>
<li>English
<li>Google search
<li>Git/Github
<li>Charles/wireshark
<li>Iterm & zsh
<li>VSCode
<li>Xcode
<li>Vim
<li>Netease Music
<li>figma
</li>
</ul>
</td>
<td>Languages
<ul>
<li>Objc
<li>Swift
<li>C/C++
<li>Ruby
<li>Java/groovy
<li>Python/Shell
<li>…
</li>
<br>
<br>
<br>
</ul>
</td>
</tr>
<tr>
<td>Business related
<ul>
<li>Basic tools 
<ul>
<li>Google docs/sheet
<li>ProcessOn/Lucidchart
<li>Domain driven design 
<li>Jira
<li>Design pattern (MVC / MVVM…)
</li>
</ul>
<li>UI related
<ul>
<li>CoreFoundation  
<ul>
<li>Runloop
</li>  
</ul>
<li>UIKit
<ul>
<li>UICV/UITV
<li>Navigation/Presenting
<li>Text Related
</li>  
</ul>
<li>CoreGraphics/CoreAnimation/Charts
<li>IGListKit
<li>SDWebImage
<li>AFNetworking
<li>YYText
<li>IJKPlayer/VideoLab
<li>Lottie/PAG
</li> 
</ul>
</li> 
</ul>
</td>
<td>
<ul>
<li>Non-UI related
<ul>
<li>GCD
<li>WCDB/FMDB(SQLite)/MMKV
<li>CoreData
<li>NSFileManager
<li>JSONModel/Swift_Codable/YYJSON
<li>Protobuf
<li>Remodel
<li>ConsistencyManager
<li>Regex
<li>Keychain
<li>Deeplink/Router (no specific framework)
<li>PromiseKit (usefulless IMO)
<li>Xlog
</li> 
</ul>
<li>API related 
<ul>
<li>GraphQL
<li>XQUIC/NSURLSession (HTTP3)
</li> 
<br>
<br>
<br>
</ul>
</li> 
</ul>
</td>
</tr>
<tr>
<td>Linter
<ul>
<li>SwiftLint
<li>OCLint
<li>…
</li>
<br>
<br>
<br>
<br>
</ul>
</td>
<td>Test related
<ul>
<li>XCTest
<li>OCMock
<li>Appium/KIF
<li>Bluepill
<li>Code Coverage
<li>AI Test 
<ul>
<li>Fastbot_iOS
</li> 
</ul>
</li> 
</ul> </td></tr><tr> <td>Profile tools (Performance related)
<ul>
<li>Instruments
<li>Lookin/Reveal
<li>GameBench/PerfDog/AnyTrace
<li>Memory graph
<li>Hitch detector (ANR)
<li>Xcode Organizer
<li>MetricKit
</li>
</ul>
<br>
<br>
<br>
</td>
<td>Building related
<ul>
<li>Clang 
<ul>
<li>libtooling
</li> 
</ul>
<li>Cocoapods + xcodeproj(ruby)
<li>HomeBrew
<li>Bazel
<li>ninja(+gn)/make(+cmake)
<li>hmap(milend/hmap)
<li>dyld 2/3
<li>ld64/zld
<li>linkmap
</li>
</ul> </td></tr><tr> <td>CI/CD related
<ul>
<li>Xcrun
<li>Jenkins/Gradle
<li>Codesign
<li>fastlane
<li>Interacte with Xcode project 
<ul>
<li>Xcodeproj/XcodeGen/tuist
</li> 
</ul>
</li> 
</ul>
</td>
<td>Render
<ul>
<li>Skia
<li>Metal/openGLES
<li>Unity/UnrealEngine(game)
</li>
</ul>
<br>
<br>
<br>
</td>
</tr>
<tr>
<td>Debug related
<ul>
<li>dwarf
<li>dsym
</li>
</ul>
<br>
<br>
</td>
<td>Hotpatch / HotReload
<ul>
<li>JSPatch
<li>WaxPatch
<li>InjectionIII
<li>Mango/OCRunner
</li>
</ul> </td></tr><tr> <td>Crash related
<ul>
<li>Xcode Tools(Zombie,ASAN,TSAN)
<li>KSCrash/PLCrashReporter
<li>Atosl
<li>APMPlus/Firebase/Bugly/Umeng/Sentry/Datadog…
<li>GWPASan
<li>CoreDump
<li>CrashCushion
</li>
</ul> </td> <td>Safety related
<ul>
<li>Hopper
<li>IDA
</li>
</ul>
<br>
<br>
<br>
<br>
<br>
</td>
</tr>
<tr>
<td>System domain (XNU)
<ul>
<li>Mach-O
<li>mmap (virtual memory)
<li>mach message/XPC
<li>sandbox
<li>APFS
<li>IOKit
</li>
</ul>
</td>
<td>Functional programming
<ul>
<li>ReactCocoa/RXSwift
</li>
</ul>
<br>
<br>
<br>
<br>
<br>
</td>
</tr>

</table>


## Basic Tools

### English

As this repo is written in English, English part is ignored.

### Google search

This section recommends several useful google search tips with little effort to learn.

Check them out in:
- [A simplified cheatsheet](https://www.cfcs.org/sites/default/files/Google%20search%20tips.pdf)
- [A full cheatsheet](https://static.semrush.com/blog/uploads/files/39/12/39121580a18160d3587274faed6323e2.pdf)

I strongly recommend using `""`, `-`, `*`, `~`, `site:`, `filetype:` etc.

### Git/Github

Git will be your best friend in your whole career. pls learn it staidly in [this official site](https://git-scm.com/book/en/v2).

Be sure you can explain following commands:
- git add
    - git add -i
    - git add -p
    - diff between git add -u & git add -A & git add .
- pull
    - git pull -r
    - git pull -squash
    - diff between git pull and git pull --commit
    - git pull --edit
    - git pull --autostash
- push
    - git push -f
    - git push --prune
- rebase
    - git rebase --ignore-whitespace
    - git rebase --signoff
- worktree
    - git worktree add / remove
    - git worktree list
    - git worktree lock
    - git worktree move
- cherry-pick
- revert
- gc
- stash
    - git stash pop
    - git stash save
- prune
- blame
- restore
- diff
- cogfigurations in .git/config

### Charles / Wireshark

Charles satisfy most need in daily development, but if your app uses a stronger network framework than http1.1 or http2 like QUIC, you should switch to wireshark.


### Iterm & Zsh

Best relacement of terminal and bash for now.

### VScode

VScode now doesn't support for ObjC or Swift well, especially bad support for ObjC. But LinkedIn has been transfered to swift for a long time, I found there are more and more plugins supporting for writing swift code in vscode and even there is an official swift plugin in progress. And the most important reason for me to use vscode rather than xcode is that xcode's indexing system is getting slower and slower. I can't tolerate such a stupid IDE and switch to embrace open-source tools.


There are too many vscode's tutorials, I only list [an iOS related customization of vscode by nshipster](https://nshipster.com/vscode/).

Actually, as most of large iOS project contains many ruby, groovy, python scripts, using vscode and armed with useful plugins are basic requirement of an efficient iOS developer now.


### Xcode

Wait for someone or myself to introduce THIS F S.


### Vim

So many people said Vim is useless nowadays but I'm still used to vim when `git commit -m`. Being familiar with common vim commands will help you in some corner cases you don't expect at all.

[Vim Cheat sheet](https://vim.rtorr.com/)

### Netease Music

Choose a good music app, if any chance, don't choose netease music.

### figma

Figma is a good tool used by so many companies like bytedance, linkedin... Being familiar with this tool will improve the efficiency you get info from some design.

And figma is an absolutely useful tool when you are demostrating your arch of some module in your project. Put some illustrations in RFC will also help reviewers understand what you are doing like the workflow, the layer arch or something else.

## Languages

- ObjC
    - objc message forwading, selectors, method swizzle
    - objc class layout / ivars (fragile ivar, ivar encoding) / protocols / isa pointer / method list (class method and instance method)
    - +load, +initialize, Category
    - associated property
    - stack block, escaping block, variable captured by block
    - KVC and KVO
    - tagged pointer
    - ARC mechanism
        - MRC and ARC
        - autoreleasing
        - weak and strong
        - copy
- Swift
    - frozen enum
    - diff between NSArray and Array
    - Any, AnyObject
    - ?, !
    - swift class layout
    - struct
    - protocol
    - extension
    - concurrency, async, await, actor model
    - open, public, private, internal, fileprivate
    - codeable
    - property wrapper
    - string solution
    - POWERFUL generics
- C/C++
    - Basic C programming
    - C++
        - Object model
            - virtual methods
            - virtual base classes
            - EBO (empty base optimization)
        - RAII
            - exception-safe types
        - Value categories
            - lvalue
            - rvalue & move semantic
        - Smart pointer
            - `std::shared_ptr` & `std::make_shared`
            - `std::unique_ptr`
        - Template programming
            - variadic template
            - template template
            - CRTP
            - type erasing
                - `std::function` (application)
        - Common optimizations
            - SBO (small buffer object)
            - RVO & NRVO
    - STL
        - container types
        - traits
        - algorithms
    - C++20
        - modules
        - coroutine
        - concept
- Ruby
- Java/groovy
- Python/Shell

ObjC and Swift are most commonly used in daily development, as no language is simple, we should master in these 2 tools to cover wired issue you may meet in daily development. The language detail is also the foundation of dealing with complex problems like improving building time, improving debugging efficience, etc...

C/C++ are commonly regarded as having low overhead than swift and objc. And they all have good compatibility in different platform, widely used to create cross-platform frameworks like video, audio, networking, etc... Master in C++ will bring you capbilities to read complex computer science solutions like rendering or editing videos or playing audios.

Ruby is used by cocoapods which is the famous package manager nowadays. `Podfile` is something every iOS developer need to know in every large iOS project. Learning ruby and writing podfile or cocoapods hooks will help you understand iOS development easier.

Java and groovy are used by gradle and jenkins.

Python and shell are used to accelerate some specific problems like posting local crash logs.


## Business related

### Basic tools

### UI related

- CoreFoundation

CoreFoundation and Foundation perform as the foundation of the entrie iOS system. CF performs following roles:

    - Data structures provider. It provides like CFArray, CFDictionary, CFTree if you are programming in C.
    - Practical utils provider. It provides CFLocale, CFXMLParser, CFDate...
    - IPC Wrapper. Use CFMessagePort or CFMachPort to communicate with other processes.
    - Low-level Network provider. You can use CFSocket to do socket level networking requests.
    - Runloop provider. CFRunloop is the key role in any applications in XNU.

Check CoreFoundation's headers if you wish.

CoreFoundation is wholely open-sourced by apple. See it [here](https://opensource.apple.com/source/CF/)

There are 2 classes I want to explain here:

    - CFMachPort
    - CFRunloop
which are considered the most special classes provided by XNU.

CFMachPort is used to communicate with other process. One process sends a message to another process. Message is sended and received by 2 mach ports, one in the sender process, another in receiver process. Almost every system framework relies on IPC to work with others. Even our app relies on IPC to achieve goals like rendering something, handling user interaction, handling networking notifications and so on. But almost all these IPC behaviors are covered by system framework. You can see nothing in the opaque UIKit about IPC or NSURLSession in Foundation.

Check more details in these links:
[hurdextras](http://hurdextras.nongnu.org/ipc_guide/)
[A demo of register disk mount/unmount notification from system by mach port](https://github.com/aosm/DiskArbitration/blob/master/diskarbitrationd/DAMain.c)
[Some investigation of system notification in Chinese](https://juejin.cn/post/6844903837690494989)
[Communication between our server and client](https://github.com/nevali/opencflite/tree/master/examples/CFMessagePort)
[Implmentation of registering local and remote port when communication](https://opensource.apple.com/source/CF/CF-1153.18/CFMessagePort.c.auto.html)

If you checked the last but the most important one, you will find `bootstrap_look_up2` and `bootstrap_register2` and `task_get_bootstrap_port` which will bring you to the concrete XNU's implementation which differs a lot from unix.

Then is runloop.
Runloop is something highly investigated by now. If you are still strange with it, check this [official doc](https://developer.apple.com/library/archive/documentation/Cocoa/Conceptual/Multithreading/RunLoopManagement/RunLoopManagement.html#//apple_ref/doc/uid/10000057i-CH16-SW1) and [source code of __CFRunLoopRun](https://opensource.apple.com/source/CF/CF-1153.18/CFRunLoop.c.auto.html)

- UIKit & IGListKit && YYText

Actually, most iOS developer call themselves UIKit caller. Just kidding.. But it does reflect the relationship between UIKit and development of iOS. UIKit builds every app's entire world. Each app has a UIWindow as the key window. Then we have to set up a root UIViewController of this key window. Then commonly we put a UITableView or UICollectionView in the root viewcontroler. Each row of the tableview or collectionview has some UIImageView and UIButton and UILabel and UITextView. Some of imageviews are set up with UIGestureRecognizers, then they can interact with users to respond to specific gestures. A simple but complete app is built done.

I don't want to discuss each classes in UIKit because there are too many. I only talk about following classes:

    - UICollectionView and UITableView
    - UINavigationController and UIViewController's presenting method
    - UILabel and UITextView

Use UICollectionView for **Horizental & Vertical scrolling**. Use UITableView for **Vertical scrolling**. So if you want to implement an horizental scrolling UI element, you can only use UICollectionView.
No matter UICollectionView and UITableView, under UIKit's MVC arch, we provide a datasource and a delegate for these 2 UI classes. Data source for data spec. Delegate for scrolling, sizing, configuring...

You can see delegate method is completely a ball of mud. IGListKit comes up to help you out.

The key concept of IGListKit is to seperate sections into several sectionproviders to release the pressure of controller. In raw UIKit, Controller takes all the responsibilities to run UICollectionView. Now with IGListKit, we have a manager called Adapter to manage all the resources UICollectionView needed. Resources are seperated into several parts, which is exactly sectionproviders. So our controller is clean now.

In addition to releasing pressure of controller, IGListKit also provides more coherence in one section. Most logics are put into ONE sectionProvider, the logics get bundled more tightly.

But in contrast to IGListKit's official guidance, I don't think section providers are easily to reuse. Actually, NO CONTROLLER CAN BE REUSED. The only thing we can reuse is the relationsip between view and model. Even the configuration can not be reused.

LinkedIn recently worked out a new UI framework which focuses on the relationship between UI and model, give up thinking of reuse of section controller or provider, the only thing designed to be reused is the relationship between model and view. And of course, the configuration can be reused optionally.

Another advantage of IGListKit is the high performance it provides with diff algorithm. No more reloadData. Only perform change from one snapshot to another.

But IGListKit doesn't fix the problem that we can call several times in one loop. But LinkedIn's one fixes this issue by a delayed update in one loop.

The interfaces of IGListKit still need to improve.

Then is navigation and presenting. Transition between different pages are common need in mobile app, Apple designed UINavigaitonController to horizentally transfer from one to another, and presenting to verically transfer form one to another. The difference is that, navigation to next must cover current page. But presenting one doesn't require that. So we have modal presenting. I don't know how Android implements in transition between pages, but for me UINavigationController and the presenting behaviro are both not easy to use especially when you want to customize. 

See this framework to learn more: [CoreNavigation](https://github.com/aronbalog/CoreNavigation/blob/master/Documentation/CONFIGURATION.md#animating)

For rendering text in iOS, I strongly recommend YYText to discover the principles behind UILabel with CoreText API. `YYLabel` provides strong feature and is easy to debug with transparent code. In one word, either `YYLabel` or `UILabel` are just wrapper for CoreText. CoreText doesn't provide the canvas, we need a UIView to provide the concrete canvas, so thats YYLabel or UILabel. With exploring of the implementation of YYLabel, you will learn Font, glyph, CTRun, paragraph, baseline and other concepts. As computers now still transfer infomation by rendering words, don't miss these exciting part!

