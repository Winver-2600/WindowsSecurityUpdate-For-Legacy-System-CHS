# WindowsSecurityUpdate-For-Legacy-System-CHS
本项目旨在为中国大陆地区用户提供旧系统的安全补丁


┄┄┄┄┄┄ 由于Windows Update网站的关闭，很多旧版Windows系统无法获取到安全补丁，因而对于那些装了旧系统的人们无法保持系统处于最新状态。

而对于国外的Legacy Update项目和Windows Update Restored项目却因为其加载极其缓慢（指检查更新时）而不得不放弃使用。

根据Legacy Update项目网站的描述，Microsoft下载中心删除了大量旧系统的安全补丁，这就导致安全补丁既不能通过Windows Update自动获取，也不能手动下载并安装。

对于Microsoft 更新目录，这个网站中有着大量更新，具体可分为以下几类： 安全更新程序，更新程序，关键更新程序，更新程序集，Feature Pack（功能包），Service Pack（服务包），工具，驱动程序。这些文件中只有安全更新和SP包对于中国大陆的人们来说可能有用，其它的均不重要。 而这便是最致命的一点，当针对一个系统的一个版本中的一个架构去进行搜索，都会查找到大量更新，这就会提示"Your search resulted in over 1000 matching updates. Only the first 1000 are returned. To narrow your search, try adding additional keywords to your search terms."（您的搜索结果超过1000条匹配更新。只有前1000个会被归还。为了缩小搜索范围，可以尝试在搜索词中添加更多关键词。）...... :( 
对于Legacy Update项目和Windows Update Restored项目也如此（存在大量非安全性的更新）

有报告称在Internet Archive: Wayback Machine项目中搜索"download.microsoft.com"网站可以下载一些旧的安全更新，但均为英文版且这其中所归档的文件也数量有限，但对于中国大陆地区的用户来说，这个网站是无法访问的，原因在于GFW（"Great FireWall of China"，中国国家防火墙，可从百度搜索）

本项目便是在这样的环境下诞生的:)（没米开网站:(也没精力写网页）转到释放页（Release），你可以查找到大量安全更新，注意是安全更新，没有Windows的其他更新，也没有对于Office，Visual C++ Redistributable，.NET/.NET Framework，XNA Framework，DirectX，Visual Basic，Visual Studio等的更新， 只包含Windows系统，Media Player，Internet Explorer和一些组件的安全更新。 
注意：同时不包含安装安全更新时所依赖的其它非安全性的更新（不安装依赖更新会报错"此更新不适用于您的计算机"，当然，如果在不安装任何依赖更新条件下，几乎所有的更新均会显示"此更新不适用于您的计算机"，没事，跳过即可）（包括服务堆栈和Windows Update服务的更新） 
本项目所选取的安全更新文件均从官方网站下载（连文件发布日期都可能对的上），链接：https://support.microsoft.com/zh-cn/servicing/os/windows-server/2019/11/security-updates-are-available-on-iso-9660-dvd5-image-files-from-the-microsoft-download-center，链接中的文件高达320GB，经过筛选，分类，现已压缩至50GB以内 该项目包含了除WindowsRT外所有系统，除IA64，ARM32/64架构外所有架构的简体中文更新文件，WinVista以前为EXE格式，以后（包括其本身）为MSU格式（Microsoft Update Standalone Package），支持的系统从Win2000到WinServer2016，提供的日期从2006年1月到2016年8月整整十年零八个月。 
支持的系统清单：Windows 2000，WindowsXP，Windows Server 2003（包括R2），Windows Vista，Windows Server 2008，Windows Server 2008 R2，Windows 7，Windows Embedded Standard 7，Windows 8，Windows Server 2012，Windows Server 2012 R2，Windows8.1，Windows Server 2016。

友情链接： 
Windows Update网站： https://fe2.update.microsoft.com/ -403

Windows Update Catalog网站： https://catalog.update.microsoft.com/ -YES

Legacy Update项目网站： https://legacyupdate.net/ -YES

Windows Update Restored项目网站： https://www.windowsupdaterestored.com/ -YES 

Internet Archive项目网站： http://archive.org/ -NOT CONNECT（GFW）

⚠️⚠️⚠️重要说明：⚠️⚠️⚠️
本项目仅允许在中国大陆地区使用（因为全是简体中文）
本项目与微软公司没有任何关系
本项目中绝大部分的数据均来自微软公司（包括但不限于msu文件，exe文件，msi文件），"Windows"和"Microsoft"分别为视窗操作系统和微软公司的英文标识，微软公司依照国际版权法合法保留所有权利，禁止一切损害版权的行为
本项目数据均来自微软官方，微软公司保留一切权利，数据虽然按原样保留，但基于人工筛选，不能保证数据的绝对完整性，在安装前一定要先对文件进行核验，对系统进行备份，以防故障发生，由此导致的数据损失，后果自负
由于数据在时间上漫长和空间上的庞大，又因为是人工筛选，难免会有遗漏（尽管我进行了两次校验），
在微软下载中心简体中文页面，几乎所有的下载的发布日期均为2020年12月15日，所以又有一个工程量便是校正日期
本项目采用GPL-3许可证
本项目最终一切解释权归创建者所有