# helloworld
my first code

4.NVIDIA修复了GPU驱动程序、GeForce Experience中的安全漏洞
NVIDIA发布了安全更新，以修复Windows GPU显示驱动程序和NVIDIA GeForce Experience（GFE）软件中的12个高危和中危漏洞。 NVIDIA GFE是GeForce GTX显卡的同类应用程序。NVIDIA修复的漏洞可能导致Windows计算机上运行代码执行、特权提升、信息泄露和拒绝服务。[外刊-阅读原文]

5.Epic商城再次曝出DRM漏洞 玩家不花钱就能玩所有游戏
最近CCN的安全研究员Willian Worrall就曝光了Epic商城的又一个安全漏洞：玩家即使没购买过游戏，也可以无障碍游玩。研究员在多台设备上测试了这个漏洞，只要持有游戏的账号登陆了这台设备并安装了游戏，那么这台设备上所有用户都能运行游戏。Epic商城依靠低分成和巨额独占费，获得了不少游戏大作的先发权，比如《天外世界》《无主之地3》《荒野大镖客2》等等。[阅读原文]

6.漏洞猎人在Pwn2Own Tokyo 2019上通过入侵电视、路由器和电话获得195000美元的收入
Pwn2Own是趋势科技的零日活动（ZDI）组织的年度黑客竞赛活动。 Pwn2Own Tokyo 2019竞赛针对17个系统列表中的一种设备的工作漏洞提供了超过750000美元的奖励。 这是有史以来第一次，Pwn2Own Tokyo 2019要求参与者在Portal智能显示器和Facebook Oculus Quest虚拟现实耳机中发现漏洞。[外刊-阅读原文]


7.Libarchive库中的一个漏洞影响了主要Linux发行版
Google专家在压缩库libarchive中发现了一个漏洞，为CVE-2019-18408，可能导致任意代码执行。libarchive库是一种多格式的存档和压缩库，它实现用于读取/写入各种压缩格式的单个接口。该漏洞影响主要的Linux发行版，包括Debian，Ubuntu，Arch Linux，FreeBSD和NetBSD。[外刊-阅读原文]

Remote Code Execution

CVE-2019-13720
 Chrome 的 exploit 内嵌了一个 0day 提权 (EoP) exploit (CVE-2019-1458)

CVE-2019-1468 是存在于 Windows 字体库中的一个远程代码执行漏洞，是因为该库不正确地处理一些内嵌字体造成的。攻击者可通过使用网页中特殊构造的恶意内嵌字体，之后诱骗用户访问该网页的方式利用该漏洞。或者用户可以在机器上打开特殊构造的字体文件。
CVE-2019-1471 是存在于 Hyper-V 管理程序中的一个远程代码执行漏洞。Hyper-V 有时候未能正确验证guest 操作系统上认证用户的输入。攻击者可通过在 guest OS 上运行特殊构造的应用程序的方式利用该漏洞，从而导致 Hyper-V 主机 OS 在主机操作系统上执行任意代码。
除了上述已遭利用的 0dayCVE-2019-1458 外，思科还分析了其它两个“重要”级别的漏洞。
CVE-2019-1469 是存在于 Windows 中的信息泄露漏洞，当win32k 组件未能提供内核信息时就会触发该漏洞。攻击者能够利用该漏洞获取未初始化的内存和内核内存执行其它攻击。
CVE-2019-1485 是存在于 VBscript 引擎中的一个远程代码执行漏洞。攻击者可利用该漏洞损坏受影响系统的内存，从而在当前用户的上下文中执行任意代码。要触发该漏洞，用户必须在 IE web 浏览器中访问恶意的尤其是特殊构造的网站。攻击者也可在使用IE 渲染引擎的应用程序或微软 Office 文档中嵌入被标记为“初始化安全”的一个 ActiveX 控制，之后诱骗用户打开该文件。

CVE-2019-0801 | Office 远程代码执行漏洞
