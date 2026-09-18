# 全国计算机等级考试Linux应用与开发技术试题（六）

## 一、单项选择题（共 40 题）

**1. 与Windows系统相比，Linux系统在以下应用领域中使用相对较少的是(  )**

<table>
  <tr><td width="50%">A. 桌面</td><td>B. 服务器</td></tr>
  <tr><td>C. 嵌入式</td><td>D. 集群</td></tr>
</table>

**2. 下面关于Shell的说法，错误的是(  )**

<table>
  <tr><td width="50%">A. Shell是操作系统的外壳</td><td>B. Shell是用户与Linux内核之间的接口</td></tr>
  <tr><td>C. Shell是一种和C类似的高级程序设计语言</td><td>D. Shell是一个命令语言解释器</td></tr>
</table>

**3. 终止当前正在运行的命令，需要按下(  )**

<table>
  <tr><td width="50%">A. Ctrl-B</td><td>B. Ctrl-C</td></tr>
  <tr><td>C. Ctrl-D</td><td>D. Ctrl-F</td></tr>
</table>

**4. 下列Linux路径，正确的是(  )**

<table>
  <tr><td width="50%">A. `//usr\zhang/file`</td><td>B. `\usr\zhang\file`</td></tr>
  <tr><td>C. `/usr/zhang/file`</td><td>D. `\usr//zhang/file`</td></tr>
</table>

**5. 缺省情况下，/etc/passwd和/etc/shadow两个文件的权限分别是(  )**

<table>
  <tr><td width="50%">A. `-rw-r-----` , `-r---------`</td><td>B. `-rw-r--r--` , `-r--r--r--`</td></tr>
  <tr><td>C. `-rw-r--r--` , `-r---------`</td><td>D. `-rw-r---rw-` , `-r------r--`</td></tr>
</table>

**6. 如果umask设置为022，缺省创建的文件的权限为(  )**

<table>
  <tr><td width="50%">A. `----w--w-`</td><td>B. `-w--w-----`</td></tr>
  <tr><td>C. `-r-xr-x---`</td><td>D. `-rw-r--r--`</td></tr>
</table>

**7. shell启动的时候，读取用户环境变量的文件是(  )**

<table>
  <tr><td width="50%">A. .bash 和 .bashrc</td><td>B. bashrc 和 .bash_conf</td></tr>
  <tr><td>C. bashrc 和 bash_profile</td><td>D. .bashrc 和 .bash_profile</td></tr>
</table>

**8. 要查看当前目录下名为“myfile”的文件的大小、修改日期和时间等信息，可以使用命令(  )**

<table>
  <tr><td width="50%">A. `ls /`</td><td>B. `ls -l /`</td></tr>
  <tr><td>C. `ls -l myfile`</td><td>D. `ls -l ./myfile`</td></tr>
</table>

**9. 若要统计a.dat文件的信息，并将结果追加到output.ls文件中，可以使用命令(  )**

<table>
  <tr><td width="50%">A. `wc> a.dat>output.ls`</td><td>B. `wc> a.dat>>output.ls`</td></tr>
  <tr><td>C. `a.dat>wc>>output.ls`</td><td>D. `wc< a.dat>>output.ls`</td></tr>
</table>

**10. 查看日志文件，希望实时跟踪文件新增内容，使用命令(  )**

<table>
  <tr><td width="50%">A. less</td><td>B. cat</td></tr>
  <tr><td>C. tail</td><td>D. tail -f</td></tr>
</table>

**11. 创建用户user01，UID为200，GID为1000，家目录/home/user01，正确命令是(  )**

<table>
  <tr><td width="50%">A. `adduser -u 200 -g 1000 -h /home/user01 user01`</td><td>B. `adduser -u 200 -g 1000 -d /home/user01 user01`</td></tr>
  <tr><td>C. `useradd -u 200 -g 1000 -d /home/user01 user01`</td><td>D. `useradd -u 200 -g 1000 -h /home/user01 user01`</td></tr>
</table>

**12. 可以将多个文件内容拼接输出的命令是(  )**

<table>
  <tr><td width="50%">A. awk</td><td>B. cat</td></tr>
  <tr><td>C. grep</td><td>D. cut</td></tr>
</table>

**13. 修改用户larry的密码，命令为(  )**

<table>
  <tr><td width="50%">A. `su larry`</td><td>B. `change password larry`</td></tr>
  <tr><td>C. `password larry`</td><td>D. `passwd larry`</td></tr>
</table>

**14. userdel默认删除用户时，下面描述正确的是(  )**

<table>
  <tr><td width="50%">A. 会删除该用户所有相关文件</td><td>B. 存放在用户家目录以外的其他文件</td></tr>
  <tr><td>C. 会删除家目录下全部文件</td><td>D. 不会删除家目录以外，家目录会删除</td></tr>
</table>

**15. vi编辑器中显示行号的命令是(  )**

<table>
  <tr><td width="50%">A. `set numberoff`</td><td>B. `set no`</td></tr>
  <tr><td>C. `set nu`</td><td>D. `set nu=on`</td></tr>
</table>

**16. 将bigfile复制到/etc/oldfile，放到后台执行，命令是(  )**

<table>
  <tr><td width="50%">A. `cp bigfile /etc/oldfile #`</td><td>B. `cp bigfile /etc/oldfile &`</td></tr>
  <tr><td>C. `cp bigfile /etc/oldfile`</td><td>D. `cp bigfile /etc/oldfile @`</td></tr>
</table>

**17. vi中将第1行开始的5行复制，到指定位置粘贴，操作是(  )**

<table>
  <tr><td width="50%">A. 将光标移到第1行，输入5dd，然后将光标移到指定位置，按p键</td><td>B. 将光标移到第1行，在命令行模式下输入5yy，然后将光标移到指定位置，按p键</td></tr>
  <tr><td>C. 将光标移到第1行，输入5yy，然后将光标移到指定位置，按d键</td><td>D. 将光标移到第1行，输入5dd，然后将光标移到指定位置，按y键</td></tr>
</table>

**18. `ls -l` 输出信息为 `drwxr-xr-x afile`，则afile是(  )**

<table>
  <tr><td width="50%">A. 普通文件</td><td>B. 链接文件</td></tr>
  <tr><td>C. 目录文件</td><td>D. 设备文件</td></tr>
</table>

**19. /home/tmp目录下有3个文件，要删除该目录，命令为(  )**

<table>
  <tr><td width="50%">A. `cd /home/tmp`</td><td>B. `rm /home/tmp`</td></tr>
  <tr><td>C. `rmdir /home/tmp`</td><td>D. `rm -r /home/tmp`</td></tr>
</table>

**20. 分页查看/etc/passwd文件内容，命令是(  )**

<table>
  <tr><td width="50%">A. `ls /etc/passwd | more`</td><td>B. `ls -l /etc/passwd | more`</td></tr>
  <tr><td>C. `cat /etc/passwd | more`</td><td>D. `wc /etc/passwd | more`</td></tr>
</table>

**21. 在Linux终端窗口中输入命令时，以下表示命令未结束，在下一行继续输入的是(  )**

<table>
  <tr><td width="50%">A. `/`</td><td>B. `\`</td></tr>
  <tr><td>C. `&`</td><td>D. `;`</td></tr>
</table>

**22. 下列关于/etc/group文件的描述，正确的是(  )**

<table>
  <tr><td width="50%">A. 记录系统中的每个用户</td><td>B. 记录每个组分配ID、名称等信息</td></tr>
  <tr><td>C. 存储用户的口令</td><td>D. 详细说明用户的文件访问权限</td></tr>
</table>

**23. 下列能将文件a.dat的权限从“rwx------”改为“rwxr-x---”的命令是(  )**

<table>
  <tr><td width="50%">A. `chown rwxr-x--- a.dat`</td><td>B. `chmod rwxr-x--- a.dat`</td></tr>
  <tr><td>C. `chmod g+rx a.dat`</td><td>D. `chmod 760 a.dat`</td></tr>
</table>

**24. 使用命令 `mount -t iso9660 /dev/cdrom /media/cdrom` 将光盘挂载后，对光盘进行卸载的命令是(  )**

<table>
  <tr><td width="50%">A. `unmount /media/cdrom`</td><td>B. `umount /media/cdrom`</td></tr>
  <tr><td>C. `mout -U /media/cdrom`</td><td>D. `unmount -U /media/cdrom`</td></tr>
</table>

**25. 使用ln命令分别生成指向原文件file的硬链接文件file1和符号链接文件file2，如果将原文件file删除，则file1和file2是否还能够正常访问(  )**

<table>
  <tr><td width="50%">A. file1可以正常访问，但是file2无法再访问</td><td>B. file2可以正常访问，但是file1无法再访问</td></tr>
  <tr><td>C. file1和file2都可以正常访问</td><td>D. file1和file2都不可以正常访问</td></tr>
</table>

**26. 磁盘管理中，通常将逻辑分区建立在(  )**

<table>
  <tr><td width="50%">A. 从分区</td><td>B. 扩展分区</td></tr>
  <tr><td>C. 主分区</td><td>D. 第二分区</td></tr>
</table>

**27. 一般来说，使用fdisk命令将改动写入硬盘的当前分区表，需要使用选项(  )**

<table>
  <tr><td width="50%">A. p</td><td>B. r</td></tr>
  <tr><td>C. x</td><td>D. w</td></tr>
</table>

**28. Linux的根分区系统类型可以设置成(  )**

<table>
  <tr><td width="50%">A. FAT16</td><td>B. FAT32</td></tr>
  <tr><td>C. Ext4</td><td>D. NTFS</td></tr>
</table>

**29. VMware Workstation虚拟平台中，物理主机与虚拟主机在同一网段，虚拟主机可直接利用物理网络访问外网，这种网络连接方式是(  )**

<table>
  <tr><td width="50%">A. 桥接</td><td>B. NAT模式</td></tr>
  <tr><td>C. 仅主机模式</td><td>D. DHCP模式</td></tr>
</table>

**30. 在默认的安装中，存放Apache配置文件的目录是(  )**

<table>
  <tr><td width="50%">A. `/etc/httpd/`</td><td>B. `/etc/httpd/conf`</td></tr>
  <tr><td>C. `/etc/`</td><td>D. `/etc/apache`</td></tr>
</table>

**31. FTP服务使用的端口是(  )**

<table>
  <tr><td width="50%">A. 21</td><td>B. 23</td></tr>
  <tr><td>C. 25</td><td>D. 53</td></tr>
</table>

**32. 在执行命令 `cd ..` 之前和之后，执行pwd命令的结果相同，则pwd命令的执行结果为(  )**

<table>
  <tr><td width="50%">A. `/`</td><td>B. `/boot`</td></tr>
  <tr><td>C. `/root`</td><td>D. `/home/li`</td></tr>
</table>

**33. 在Linux系统中，第二块SCSI设备应该表示为(  )**

<table>
  <tr><td width="50%">A. hd2</td><td>B. hdb</td></tr>
  <tr><td>C. sd2</td><td>D. sdb</td></tr>
</table>

**34. 当执行“ll”时会看到和执行“ls -l”同样的输出结果，这是因为(  )**

<table>
  <tr><td width="50%">A. ll是以长格式显示文件或目录的一个命令</td><td>B. ll是指向ls命令的一个特殊的符号链接</td></tr>
  <tr><td>C. ll是通过alias命令设置的简化“ls -l”的一个别名</td><td>D. ll是Linux系统内核中的一个特殊函数</td></tr>
</table>

**35. 下列对shell变量FRUIT操作，正确的是(  )**

<table>
  <tr><td width="50%">A. 为变量赋值：`$FRUIT=apple`</td><td>B. 显示变量的值：`fruit=apple`</td></tr>
  <tr><td>C. 显示变量的值：`echo FRUIT`</td><td>D. 判断变量是否有值：`[ -f "FRUIT" ]`</td></tr>
</table>

**36. Linux中的普通文件，依据其存储的方式可以分为(  )**

<table>
  <tr><td width="50%">A. word和binary</td><td>B. txt和word document</td></tr>
  <tr><td>C. ASCII和binary</td><td>D. ASCII和rich text Format</td></tr>
</table>

**37. 使用vi编辑器将文件某行删除后，发现该行内容需要保留，重新恢复该行内容的最佳操作方法是(  )**

<table>
  <tr><td width="50%">A. 在编辑模式下重新输入该行</td><td>B. 不保存直接退出vi，并重新编辑该文件</td></tr>
  <tr><td>C. 在命令模式下使用“u”命令</td><td>D. 在编辑模式下使用“r”命令</td></tr>
</table>

**38. 在/etc/ssh目录中，OpenSSH服务器程序的主配置文件是(  )**

<table>
  <tr><td width="50%">A. ssh_config</td><td>B. sshd_config</td></tr>
  <tr><td>C. ssh.config</td><td>D. sshd.config</td></tr>
</table>

**39. 若需要查询系统中已安装的RPM软件包“talk”的详细信息，可以执行命令(  )**

<table>
  <tr><td width="50%">A. `rpm -ql talk`</td><td>B. `rpm -qpi talk`</td></tr>
  <tr><td>C. `rpm -qi talk`</td><td>D. `rpm -qf talk`</td></tr>
</table>

**40. 系统中有用户user1和user2，同属于users组。在user1用户目录下有一文件file1，它的权限是644，如果user2用户想修改user1用户目录下的file1文件，file1的权限应修改为(  )**

<table>
  <tr><td width="50%">A. 744</td><td>B. 664</td></tr>
  <tr><td>C. 646</td><td>D. 746</td></tr>
</table>

## 二、填空题（共 10 题）

1. 默认情况下，超级用户和普通用户的登录提示符分别是：【41】\_\_\_\_\_\_\_\_\_\_和【42】\_\_\_\_\_\_\_\_\_\_。
2. 将前一个命令的标准输出作为后一个命令的标准输入，称之为【43】\_\_\_\_\_\_\_\_\_\_。
3. Linux中的文件链接分为【44】\_\_\_\_\_\_\_\_\_\_和【45】\_\_\_\_\_\_\_\_\_\_两种。
4. 结束后台进程的命令是【46】\_\_\_\_\_\_\_\_\_\_。
5. 可以用 `ls -al` 命令来观察文件的权限，每个文件的权限都用10位表示，并分为四段，其中第一段占1位，表示文件类型，第二段占3位，表示【47】\_\_\_\_\_\_\_\_\_\_对该文件的权限。
6. 在Linux系统中，用来存放系统所需要的配置文件的目录是【48】\_\_\_\_\_\_\_\_\_\_。
7. 在shell编程时，使用方括号表示测试条件的规则是：方括号两边必须有【49】\_\_\_\_\_\_\_\_\_\_。
8. vi编辑器的默认模式是命令模式，无论用户处于何种工作模式，按下【50】\_\_\_\_\_\_\_\_\_\_键，即可进入该模式。
9. 编写的脚本程序运行前必须赋予该脚本文件【51】\_\_\_\_\_\_\_\_\_\_权限。
10. 将磁盘/dev/hdc卸载的命令是【52】\_\_\_\_\_\_\_\_\_\_。

## 三、综合应用题（共 2 题）

**1. (1) 设Linux文件系统的目录结构如下图所示：**

```text
/
├── bin
├── dev
├── etc
├── lib
├── mnt
├── temp
├── ……
└── usr
    ├── ste
    │   ├── doc
    │   │   ├── pla
    │   │   └── ……
    │   ├── sys
    │   └── new
    └── rut
        ├── new
        └── ……
```

（注：原图中 sys、new 用方框表示为文件，且 new 由 ste 与 rut 两个目录共同指向。）

(1) 若当前工作目录是 `/usr/ste`，那么，访问文件pla的相对路径名是什么？【53】\_\_\_\_\_\_\_\_\_\_
(2) 若当前工作目录是 `/usr/ste`，那么，访问文件pla的绝对路径名是什么？【54】\_\_\_\_\_\_\_\_\_\_
(3) 若当前工作目录是 `/`，想要删除ste目录下的目录doc和doc下的所有文件，请写出应使用的命令。【55】\_\_\_\_\_\_\_\_\_\_
(4) 若当前工作目录是 `/`，想要在usr目录下建立一个与ste、rut同级的目录misc，请写出应使用的命令。【56】\_\_\_\_\_\_\_\_\_\_
(5) 若当前工作目录是 `/usr/ste`，想要将当前目录改变为rut，请写出应使用的命令。【57】\_\_\_\_\_\_\_\_\_\_

**(2) 查看file文件的内容如下：**

```bash
[student@localhost~] $ cat file
Open source is a good mechanism to develop programs.
GNU is free air not free beer.
Oh! My god.
google is the best tool for search keyword.
goooooogle yes!
the symbol * is represented as start.
```

执行下列命令后，结果显示上述文件中的哪些行？（请在空格处填入行号，多个行号按从小到大的顺序，之间由逗号隔开；文件的行号从1开始）

(1) `[student@localhost~] $ grep "the" file` 【58】\_\_\_\_\_\_\_\_\_\_
(2) `[student@localhost~] $ grep -E '^the' file` 【59】\_\_\_\_\_\_\_\_\_\_
(3) `[student@localhost~] $ grep -E 'goo*' file` 【60】\_\_\_\_\_\_\_\_\_\_
(4) `[student@localhost~] $ grep -vE '^[A-Z]' file` 【61】\_\_\_\_\_\_\_\_\_\_
(5) `[student@localhost~] $ grep -E '$!' file` 【62】\_\_\_\_\_\_\_\_\_\_

**2. (1) 已知脚本sh01用 `$RANDOM` 产生一个随机数，用户猜测，脚本给出提示“大于或小于”该随机数，直至猜对为止，并显示猜测的次数，请补全代码。**

```bash
[student@localhost~] cat sh01

#!/bin/bash
let num=【63】__________
let time=0
while true
do
    read -p "please input you guess:" data
    【64】__________
    if [ $data 【65】__________ $num ]
    then
        echo "you are right, and you guess $time times"
        【66】__________
    elif [ $data 【67】__________ $num ]
    then
        echo "it is high"
    else
        echo "it is low"
    fi
done
```

**(2) 补全脚本的执行结果。**

```bash
[root@localhost~] # cat father

#!/bin/bash
echo "this is the father"
film="The Shawshank Redemption"
echo "I like the film:$film"
./child
echo "back to father"
echo "and the film is:$film"
```

```bash
[root@localhost~] # cat child

#!/bin/bash
echo "I am the child"
echo "film name is : $film"
film="god father"
echo "change film to : $film"
```

```bash
[root@localhost~] # ./father
this is the father
I like the film:【68】__________
【69】__________
film name is :
change film to :【70】__________
【71】__________
and the film is:【72】__________
```

---

<br>

## 试卷（六） 参考答案与解析

### 一、单项选择题

1. **A** | 【解析】Linux在服务器（稳定性强、开源低成本）、嵌入式（可定制、适配多硬件）、集群（支持分布式调度、高性能）领域应用广泛，是主流选择。而桌面领域，Linux因生态兼容性差（缺主流软件/游戏）、操作门槛高（依赖命令行）、硬件适配不足，在个人消费级市场占比极低，远不及Windows，故桌面是其使用较少的领域。
2. **C** | 【解析】Shell是操作系统的外壳，作为用户与Linux内核的接口，负责解释执行用户输入的命令，是命令语言解释器；Shell虽支持编程，但属于脚本语言，语法和执行方式与C语言（编译型高级语言）有本质区别，并非和C类似的高级程序设计语言。
3. **B** | 【解析】Ctrl-B用于终端内向左移动光标；Ctrl-D表示EOF（文件结束符），可退出当前Shell会话；Ctrl-C是默认的中断信号触发键，可强制终止当前正在前台运行的命令或程序；Ctrl-F用于终端内向右移动光标。
4. **C** | 【解析】Linux系统中，路径分隔符统一使用正斜杠 `/`，而反斜杠 `\` 是Windows系统的路径分隔符。
5. **C** | 【解析】/etc/passwd存储用户基本信息，需所有用户可读，但仅root可修改，所以所有者读写、组用户读、其他用户读，默认权限为 `-rw-r--r--`；/etc/shadow存储用户加密密码，需严格保密，只有root用户可以浏览和操作，其他用户无任何权限，默认权限为 `-r---------`。
6. **D** | 【解析】在Linux中，文件默认创建权限为666，umask表示要减去的权限，用默认权限减去umask得到最终权限。文件：666-022 = 644，对应权限 `-rw-r--r--`。
7. **D** | 【解析】Shell启动时读取的用户环境变量文件均为隐藏文件（文件名以 `.` 开头）。`.bash_profile` 在登录式Shell启动时加载，用于配置登录相关的环境变量；`.bashrc` 在非登录式Shell（如终端中新窗口）启动时加载，用于配置日常交互的环境变量。
8. **C** | 【解析】选项A是查看根目录下的内容；选项B是查看根目录下的详情信息；选项C是查看当前目录下myfile的详细信息；选项D是查看上级目录下myfile的详细信息。
9. **D** | 【解析】wc是统计文件信息（行数、字数、字节数）的命令。`<` 表示输入重定向，`wc < a.dat` 意味让wc处理a.dat的内容；`>>` 表示追加输出，将结果添加到output.ls末尾。
10. **D** | 【解析】less用于分页查看文件，需手动操作翻页；cat用于一次性输出文件全部内容；tail默认显示文件末尾10行，仅读取当前内容；`tail -f` 选项可实时追踪文件变化，文件新增内容会即时显示，是监控日志的标准命令。
11. **C** | 【解析】Linux中创建用户的标准命令是useradd，adduser多为特定发行版的封装工具，`-u` 指定用户ID（UID），正确格式为 `-u 200`；`-g` 指定用户组ID（GID），正确格式为 `-g 1000`；`-d` 用于指定用户主目录，而非 `-h`（`-h` 通常为帮助参数）。
12. **B** | 【解析】awk用于文本处理，cat是连接文件内容、可将多个文件合并为一个，grep用于在文件中搜索匹配的字符串，cut用于从文本中提取指定列或字段。
13. **D** | 【解析】`su larry` 是从root切换到larry用户，Linux中没有命令 `change password larry` 和 `password larry`，`passwd larry` 可以修改用户larry密码。
14. **B** | 【解析】userdel默认仅删除用户账号相关配置（即/etc/passwd、/etc/shadow、/etc/group中的用户信息），不处理文件。
15. **C** | 【解析】vi编辑器中，显示行号需通过设置命令set实现，格式为 `set [选项]`，`set nu` 是vi中显示每一行行号的标准命令。
16. **B** | 【解析】Linux中，在命令末尾加 `&` 符号是将命令放入后台执行的标准方式，执行后终端会立即释放；选项A `#` 是注释符号，会使整行命令失效；选项C默认前台执行，命令未完成前终端被占用；选项D `@` 并非Linux中用于后台执行的符号。
17. **B** | 【解析】根据题目要求先将光标移动到第1行，之后输入 `5yy` 表示复制从光标所在行开始的5行内容，最后移动到指定位置，按p键粘贴。
18. **C** | 【解析】`ls -l` 首字符d代表目录文件，`-` 普通文件，l符号链接。
19. **D** | 【解析】`rm -r` 递归删除带内容目录；rmdir只能删空目录，普通rm不能直接删目录。
20. **C** | 【解析】选项A中ls命令仅用于列出文件名称，不会显示文件内容；选项B中 `ls -l` 用于显示文件的详细属性（权限、大小等）；选项C中cat命令读取文件内容并输出，通过管道传递给more命令实现分页查看；选项D中wc命令用于统计行数、单词数。
21. **B** | 【解析】`/` 通常用作路径分隔符；在命令末尾添加 `\` 并按回车，终端会显示续行提示符（通常是 `>`），允许在下一行继续输入命令的剩余部分；`&` 用于将命令放入后台运行；`;` 用于分隔多个命令，让它们按顺序执行；综上所述，本题答案为选项B。
22. **B** | 【解析】/etc/group文件主要存储系统中所有用户组的信息，包括组名、组ID（GID）、组内成员等，故本题答案为选项B。
23. **C** | 【解析】选项A中chown用于修改文件所有者或组，而非权限；选项B中在chmod的符号模式中，权限字符串必须明确指定对象；选项C为组(group)添加读(r)和执行(x)权限，原始权限rwx------中组权限为---，添加rx后变为r-x，结果即为rwxr-x---；选项D中权限数字760对应“rwxrw-----”（所有者rwx=7，组rw-=6，其他---=0），与目标权限“rwxr-x---”（对应数字750）不符；综上所述，本题答案为选项C。
24. **B** | 【解析】umount是卸载设备的专用命令，此处通过挂载点/media/cdrom卸载光盘，故本题答案为选项B。
25. **A** | 【解析】硬链接（file1）与原文件共享相同的inode和数据块，删除原文件只是减少inode的引用计数，不会影响硬链接对数据的访问，因此file1仍能正常访问内容；符号链接（file2）是指向原文件路径的特殊文件，本质上是一个“指针”，当原文件被删除后，这个“指针”指向的路径不再有效，file2会变成“悬空链接”，无法访问内容；故本题答案为选项A。
26. **B** | 【解析】主分区直接建立在硬盘上，可直接被操作系统识别和使用，最多只能创建4个；扩展分区是主分区的一种特殊形式，本身不能直接存储数据，主要作用是容纳逻辑分区，故本题答案为选项B。
27. **D** | 【解析】选项p用于打印当前分区表信息；选项r切换到恢复模式，用于特殊分区修复操作；选项x用于进入专家模式，提供高级分区配置功能；选项w将所有分区修改写入硬盘分区表并保存；综上所述，本题答案为选项D。
28. **C** | 【解析】Ext4是Linux主流的原生文件系统，可以将Linux的根分区（/）设置为Ext4文件系统，它支持权限管理、日志功能、硬链接等Linux核心特性，故本题答案为选项C。
29. **A** | 【解析】桥接模式下虚拟主机直接连接到物理网络，与物理主机处于同一网段，拥有独立的IP地址，能直接访问外网和物理网络中的其他设备；NAT模式下虚拟主机通过VMware的虚拟NAT设备访问外网，与物理主机不在同一网段；仅主机模式下虚拟主机仅能与物理主机及同一物理主机上的其他虚拟主机通信；DHCP是一种动态分配IP地址的协议；综上所述，本题答案为选项A。
30. **B** | 【解析】/etc/httpd/是Apache的主配置目录，但仅包含目录本身；/etc/httpd/conf是Apache核心配置文件的默认存放目录；/etc/是系统级配置文件的总目录；/etc/apache在Linux中属于错误路径；综上所述，本题答案为选项B。
31. **A** | 【解析】FTP（文件传输协议）使用21号端口作为控制端口，用于建立连接、传输命令；23号端口是Telnet的默认端口，25号端口是SMTP的默认端口，53号端口是DNS的默认端口；综上所述，本题答案为选项A。
32. **A** | 【解析】pwd打印当前工作目录的绝对路径；`cd ..` 将当前工作目录切换到上一级目录，唯一例外是当前目录已是根目录时，因为根目录没有父目录，`cd ..` 不会产生任何变化，前后pwd结果均为 `/`；选项B、C的父目录均为 `/`，选项D的父目录为 `/home`，切换前后结果都不同；综上所述，本题答案为A选项。
33. **D** | 【解析】SCSI类型统一使用sd前缀，后跟26个字母顺序，例如第一块SCSI设备表示为sda，第二块SCSI设备表示为sdb，故本题答案为D选项。
34. **C** | 【解析】在Linux系统中，ll并非独立命令，而是通过别名（alias）机制绑定到 `ls -l`。用户输入ll时，系统会自动替换为 `ls -l` 执行，因此输出格式与内容完全相同，故本题答案为C选项。
35. **C** | 【解析】选项A中shell变量赋值时变量名前不能加 `$`（用于取变量值），正确写法应为 `FRUIT=apple`；选项B中 `fruit=apple` 是给变量fruit赋值，而非显示变量FRUIT的值；选项C中 `echo $FRUIT` 用于显示变量的值；选项D中 `-f` 用于检查文件是否存在，而非判断变量是否为空；综上所述，本题答案为C选项。
36. **C** | 【解析】Linux中，普通文件按存储方式可分为两大类：ASCII文件（文本文件），存储的是可打印的ASCII字符；Binary文件（二进制文件），存储的是计算机可直接执行的二进制数据，故本题答案为选项C。
37. **C** | 【解析】u是vi命令模式下的撤销指令，功能是“撤销上一步操作”。若刚执行dd（删除行）命令误删了需要保留的行，只需在命令模式下按下u键，即可立即恢复被删除的行，故本题答案为C选项。
38. **B** | 【解析】ssh_config对应SSH客户端配置，sshd是SSH服务器进程名，sshd_config是/etc/ssh目录下OpenSSH服务器的主配置文件，故本题答案为选项B。
39. **C** | 【解析】`-ql` 用于列出已安装包包含的所有文件路径，`-qpi` 用于查询未安装的RPM包文件（需指定.rpm文件路径），`-qi` 表示查询并查看详细信息，`-qf` 需要“文件路径”作为参数（如 `rpm -qf /usr/bin/talk`），用于查询文件所属的包；综上所述，本题答案为C选项。
40. **B** | 【解析】file1的权限644对应符号权限rw-r--r--，修改文件需要写（w）权限；user2属于users组，组权限为r--（无写权限），因此无法修改file1。由于user2与user1同属users组，最优方案是给组添加写权限（而非给其他用户添加，避免扩大权限范围）。调整后符号权限变为rw-rw-r--，数字权限变为664；故本题答案为B选项。

### 二、填空题

41. **#** | 【解析】`#` 和 `$` 分别是超级用户和普通用户的登录提示符，`#` 用于明确区分高权限操作环境，提醒用户谨慎执行命令。
42. **$** | 【解析】`#` 用于明确区分高权限操作环境，提醒用户谨慎执行命令
43. **管道** | 【解析】管道（或者管道符，考试都算分）是一种实现命令间数据传递的机制，它允许将前一个命令的标准输出直接作为后一个命令的标准输入，无需通过中间文件存储临时数据。
44. **硬链接** | 【解析】在Linux系统中，文件链接是实现文件共享的重要机制，分为硬链接和软链接两种类型（44、45两空互换也算对）。
45. **软链接** | 【解析】在Linux系统中，文件链接是实现文件共享的重要机制，分为硬链接和软链接两种类型（44、45两空互换也算对）。
46. **kill** | 【解析】在Linux系统中，kill命令用于向进程发送信号，最常用的功能是结束后台运行的进程。
47. **文件所有者** | 【解析】`ls -al` 命令显示的文件权限字符串共10位，按功能分为四段。第一段（第1位）表示文件类型；第二段（第2-4位）表示文件所有者（或者所有者、owner，考试都算分）对该文件的权限，分别对应读（r）、写（w）、执行（x）权限。
48. **/etc** | 【解析】在Linux系统的目录结构中，/etc是专门用于存放系统和应用程序配置文件的核心目录。
49. **空格** | 【解析】在shell编程中，使用方括号 `[]` 表示测试条件时，方括号两边必须有空格。
50. **ESC** | 【解析】在vi编辑器中，按下Esc键可以从任何工作模式回到命令模式。
51. **可执行** | 【解析】在Linux中，新创建的脚本文件默认没有可执行权限，所以编写的脚本程序运行前必须赋予该脚本文件可执行权限（或者执行、x，考试都算分）。
52. **`umount /dev/hdc`** | 【解析】用于卸载文件系统的命令是umount，使用时可以直接指定设备路径或设备的挂载点，故此空填写 `umount /dev/hdc`。

### 三、综合应用题

**1. 参考答案：**
【53】 `doc/pla` | 【解析】相对路径是从当前工作目录开始的路径。当前工作目录是/usr/ste，要访问的文件pla在/usr/ste/doc下，所以相对路径为 `doc/pla`（或 `./doc/pla`，考试都给分）。
【54】 `/usr/ste/doc/pla` | 【解析】绝对路径是从根目录(/)开始的完整路径，文件pla位于/usr/ste/doc下。
【55】 `rm -r /usr/ste/doc` | 【解析】rm是删除命令，`-r` 表示递归删除目录及其内容。
【56】 `mkdir /usr/misc` | 【解析】mkdir是创建目录的命令，要在usr目录下建立与ste、rut同级的misc目录。
【57】 `cd ../rut` | 【解析】cd是切换目录的命令，当前工作目录是/usr/ste，要切换到rut目录（或 `cd /usr/rut`）。
【58】 `4,6` | 【解析】`grep "the" file` 在file文件中查找包含字符串“the”的行，第4行和第6行包含“the”。
【59】 `6` | 【解析】`-E` 表示使用扩展正则表达式，`^the` 表示匹配以“the”开头的行，第6行以“the”开头。
【60】 `1,3,4,5` | 【解析】`goo*` 表示匹配以“g”开头、后面跟着零个或多个“o”的字符串，第1行包含“good”、第3行包含“god”、第4行包含“google”、第5行包含“goooooogle”。
【61】 `4,5,6` | 【解析】`-v` 表示反向匹配，`^[A-Z]` 表示匹配以大写字母开头的行，反向匹配后输出不以大写字母开头的行，即第4、5、6行。
【62】 `3` | 【解析】该命令用于搜索以“!”字符结尾的行，第3行以“!”结尾。

**2. 参考答案：**
【63】 `$RANDOM` | 【解析】RANDOM是Bash shell中的内置变量，会生成一个0到32767之间的随机整数，这里用来生成要猜测的随机数并赋值给变量num。
【64】 `let time=time+1` | 【解析】每次用户输入猜测后，都需要将猜测次数加1，用于统计猜测的次数。
【65】 `-eq` | 【解析】`-eq` 是Bash中用于判断两个整数是否相等的比较运算符，所以这里用 `$data -eq $num` 判断是否猜中。
【66】 `exit 0` | 【解析】当用户猜对时需要退出程序，`exit 0` 用于终止当前脚本。
【67】 `-gt` | 【解析】`-gt` 用于判断左边整数是否大于右边整数，当data大于num时提示“it is high”。
【68】 `The Shawshank Redemption` | 【解析】在father脚本中先定义了 `film="The Shawshank Redemption"`，然后执行 `echo "I like the film:$film"`。
【69】 `I am the child` | 【解析】执行 `./child` 会调用child脚本，child脚本的第一行输出就是 `echo "I am the child"`。
【70】 `god father` | 【解析】在child脚本中，执行 film="god father" 后，接着执行 echo "film name is : $film" ，此时$film的值是god father。
【71】 `back to father` | 【解析】child脚本执行完毕后，会回到father脚本继续执行，father脚本中接下来的输出就是 echo "back to father" ，所以此处输出back to father。
【72】 `The Shawshank Redemption` | 【解析】child脚本中对film变量的修改是局部的（子进程的修改不影响父进程），所以回到father脚本后，`$film` 仍然是最初定义的The Shawshank Redemption。

---

# 全国计算机等级考试Linux应用与开发技术试题（七）

## 一、单项选择题（共 40 题）

**1. 以下关于程序、进程和线程的描述中，正确的是(  )**

<table>
  <tr><td width="50%">A. 程序在运行时直接变成线程，而不是进程。</td><td>B. 进程是程序的静态描述，而线程是进程的动态执行实例。</td></tr>
  <tr><td>C. 线程是比进程更小的独立运行单位，每个线程都有自己的地址空间。</td><td>D. 一个进程可以包含多个线程，它们共享进程的地址空间和资源。</td></tr>
</table>

**2. 以下关于Linux操作系统的描述中，正确的是(  )**

<table>
  <tr><td width="50%">A. Linux是一个开源的类Unix操作系统，广泛用于服务器、嵌入式系统和个人计算机。</td><td>B. Linux只能运行在服务器上，不能用于个人计算机。</td></tr>
  <tr><td>C. Linux是由微软开发的专有操作系统。</td><td>D. Linux不支持多用户和多任务操作。</td></tr>
</table>

**3. 在Linux系统中，使用RPM包管理器查询已安装的软件包信息的命令是(  )**

<table>
  <tr><td width="50%">A. `rpm -q package_name`</td><td>B. `rpm -i package_name.rpm`</td></tr>
  <tr><td>C. `rpm -e package_name`</td><td>D. `rpm --rebuild package_name.rpm`</td></tr>
</table>

**4. 在Shell脚本中，下面哪个通配符表达式可以匹配当前目录下所有以“log”结尾但不以“s”开头的文件(  )**

<table>
  <tr><td width="50%">A. `*[!s]log`</td><td>B. `[!s]*log`</td></tr>
  <tr><td>C. `?s*log`</td><td>D. `[s]*log`</td></tr>
</table>

**5. 在Shell脚本中，以下哪种方式可以正确将字符串Hello World赋值给变量greeting(  )**

<table>
  <tr><td width="50%">A. `greeting="Hello World"`</td><td>B. `greeting = "Hello World"`</td></tr>
  <tr><td>C. `greeting=Hello World`</td><td>D. `$greeting="Hello World"`</td></tr>
</table>

**6. 在Shell脚本中，若变量a=5和b=3，以下哪种方法可以正确计算a和b的数值之和并将结果赋值给变量sum(  )**

<table>
  <tr><td width="50%">A. `sum=$((a + b))`</td><td>B. `sum=a+b`</td></tr>
  <tr><td>C. `sum=$(a + b)`</td><td>D. `sum=(a + b)`</td></tr>
</table>

**7. 下面哪个文件存储了用户的加密密码，并且只有超级用户权限才能读取其中内容(  )**

<table>
  <tr><td width="50%">A. `/etc/group`</td><td>B. `/etc/passwd`</td></tr>
  <tr><td>C. `/etc/shadow`</td><td>D. `/etc/gshadow`</td></tr>
</table>

**8. 将一个已存在的用户“john”添加到已存在的用户组“developers”中，正确的命令是(  )**

<table>
  <tr><td width="50%">A. `usermod -aG developers john`</td><td>B. `useradd -g developers john`</td></tr>
  <tr><td>C. `groupadd john developers`</td><td>D. `chgrp john developers`</td></tr>
</table>

**9. 要查看当前用户的ID和所属用户组信息，应使用的命令是(  )**

<table>
  <tr><td width="50%">A. finger</td><td>B. who</td></tr>
  <tr><td>C. id</td><td>D. lastlog</td></tr>
</table>

**10. 假设你有一个包含多行文本的文件data.txt，其中有些行是重复的。你希望得到一个文件unique.txt，其中包含排序后的不重复行。以下哪个命令可以实现这一目标(  )**

<table>
  <tr><td width="50%">A. `sort data.txt | uniq > unique.txt`</td><td>B. `uniq data.txt | sort > unique.txt`</td></tr>
  <tr><td>C. `sort data.txt > unique.txt`</td><td>D. `uniq -c data.txt > unique.txt`</td></tr>
</table>

**11. 想将当前目录及其子目录中所有以.log结尾的文件移动到/var/logs/archive/目录。以下哪个命令能正确且安全地实现这一目标(  )**

<table>
  <tr><td width="50%">A. `find . -name ".log" -exec mv {} /var/logs/archive/ ;`</td><td>B. `mv .log /var/logs/archive/`</td></tr>
  <tr><td>C. `find . -type d -name ".log" -mv /var/logs/archive/`</td><td>D. `find /var/logs/archive/ -name ".log" -exec mv . ;`</td></tr>
</table>

**12. 关于Linux系统中的符号链接，以下说法正确的是(  )**

<table>
  <tr><td width="50%">A. 使用 `ln -s` 命令创建的符号链接可以指向不存在的目标文件或目录</td><td>B. 硬链接和符号链接都可以跨越文件系统边界</td></tr>
  <tr><td>C. 删除符号链接的目标文件后，符号链接将自动转为硬链接</td><td>D. 使用 `ls -l` 命令查看时，符号链接和硬链接的显示格式完全相同</td></tr>
</table>

**13. 若需要一次性创建多级目录/var/log/app/error，并为所有新创建的目录设置权限为755(rwxr-xr-x)，应使用以下哪个命令(  )**

<table>
  <tr><td width="50%">A. `mkdir -p -m 755 /var/log/app/error`</td><td>B. `mkdir -pv -m 755 /var/log/app/error`</td></tr>
  <tr><td>C. `mkdir /var/log/app/error && chmod 755 /var/log/app/error`</td><td>D. `mkdir -p /var/log/app/error && chmod 755 /var/log/app/error`</td></tr>
</table>

**14. 以下哪个命令可以将文件“example.txt”的权限设置为所有者可读写，用户组和其他人只能读(  )**

<table>
  <tr><td width="50%">A. `chmod 600 example.txt`</td><td>B. `chmod 755 example.txt`</td></tr>
  <tr><td>C. `chmod 644 example.txt`</td><td>D. `chmod 777 example.txt`</td></tr>
</table>

**15. 以下哪个命令可以实时监控系统进程的动态信息（如CPU、内存使用情况等），并以交互式界面持续更新显示(  )**

<table>
  <tr><td width="50%">A. ps</td><td>B. top</td></tr>
  <tr><td>C. kill</td><td>D. pstree</td></tr>
</table>

**16. 以下哪个命令可以通过进程的名称来终止所有匹配的进程(  )**

<table>
  <tr><td width="50%">A. pkill</td><td>B. kill</td></tr>
  <tr><td>C. killall</td><td>D. ps</td></tr>
</table>

**17. 想知道用户student启动了哪些进程以及这些进程之间的关系，可使用的命令是(  )**

<table>
  <tr><td width="50%">A. `pstree student`</td><td>B. `lsof -u student`</td></tr>
  <tr><td>C. `top -u student`</td><td>D. `ps -u student`</td></tr>
</table>

**18. 如果要将一个EXT4文件系统类型的设备 `/dev/sdc1` 挂载到目录 `/mnt/data` 上，并明确指定文件系统类型，可使用的命令是(  )**

<table>
  <tr><td width="50%">A. `mount -t ext4 /dev/sdc1 /mnt/data`</td><td>B. `mount /dev/sdc1 /mnt/data`</td></tr>
  <tr><td>C. `mount -t ext4 /mnt/data /dev/sdc1`</td><td>D. `mount /dev/sdc1 /mnt/data -t ntfs`</td></tr>
</table>

**19. 要查看Linux系统中第一个SCSI硬盘的磁盘空间使用情况，并以易读格式（如GB、MB）显示，应使用的命令是(  )**

<table>
  <tr><td width="50%">A. `df -h /dev/sda`</td><td>B. `du -h /dev/sda`</td></tr>
  <tr><td>C. `df -h /dev/hda`</td><td>D. `du -h /dev/hda`</td></tr>
</table>

**20. 使用parted命令查看当前磁盘分区布局，应使用哪个交互子命令(  )**

<table>
  <tr><td width="50%">A. list</td><td>B. print</td></tr>
  <tr><td>C. show</td><td>D. display</td></tr>
</table>

**21. 查看内存使用情况，包括已用内存、可用内存、交换分区等信息，应使用的命令是(  )**

<table>
  <tr><td width="50%">A. free</td><td>B. ls</td></tr>
  <tr><td>C. vmstat</td><td>D. top</td></tr>
</table>

**22. 在Linux系统中，为某个文件系统启用用户磁盘配额的过程中，哪一步是必需的(  )**

<table>
  <tr><td width="50%">A. 修改/etc/fstab文件以添加配额支持</td><td>B. 使用ls命令查看文件系统内容</td></tr>
  <tr><td>C. 使用rm命令移除旧的配额文件</td><td>D. 修改/etc/passwd文件以支持配额</td></tr>
</table>

**23. 用来追踪数据包在IP网络间穿行的路径的程序是(  )**

<table>
  <tr><td width="50%">A. ping</td><td>B. traceroute</td></tr>
  <tr><td>C. host</td><td>D. tcpdump</td></tr>
</table>

**24. 在Linux系统中，临时禁用某个网络接口，可使用的命令是(  )**

<table>
  <tr><td width="50%">A. `ip link set dev down`</td><td>B. `ifconfig --disable`</td></tr>
  <tr><td>C. `netctl stop`</td><td>D. `systemctl disable network@`</td></tr>
</table>

**25. 下列哪个命令既可以查看当前系统的主机名，又可以临时更改主机名(  )**

<table>
  <tr><td width="50%">A. netstat</td><td>B. ifconfig</td></tr>
  <tr><td>C. route</td><td>D. hostname</td></tr>
</table>

**26. Linux系统的日志文件通常保存在哪个目录下(  )**

<table>
  <tr><td width="50%">A. `/etc/`</td><td>B. `/usr/adm`</td></tr>
  <tr><td>C. `/var/log`</td><td>D. `/var/run`</td></tr>
</table>

**27. 下列哪个选项正确描述了Linux系统中 httpd 服务的作用(  )**

<table>
  <tr><td width="50%">A. httpd提供了Web服务器功能，用于处理和响应HTTP请求</td><td>B. httpd负责处理DNS域名解析请求</td></tr>
  <tr><td>C. httpd提供数据库存储服务</td><td>D. httpd用于邮件的发送与接收服务</td></tr>
</table>

**28. 关于VI编辑器的工作模式，下列描述正确的是(  )**

<table>
  <tr><td width="50%">A. 在命令模式下，按下 `:` 键可以进入末行模式</td><td>B. 在命令模式下，按下i键可以保存文件</td></tr>
  <tr><td>C. 在插入模式下，按下Esc键可以直接退出编辑器</td><td>D. 在末行模式下，按下dd可删除当前行</td></tr>
</table>

**29. 以下关于VI编辑器中文本编辑操作的描述中，正确的是(  )**

<table>
  <tr><td width="50%">A. 在命令模式下，按下“dd”可撤销上一步操作</td><td>B. 在插入模式下，按下“x”可删除当前字符</td></tr>
  <tr><td>C. 在命令模式下，按下“yy”可复制当前整行</td><td>D. 在命令模式下，按下“p”可进入插入模式进行编辑</td></tr>
</table>

**30. 在VI编辑器中设置Tab键宽度为4个字符，应使用的命令是(  )**

<table>
  <tr><td width="50%">A. `:set tabstop=4`</td><td>B. `:set tabsize=4`</td></tr>
  <tr><td>C. `:set tabwidth=4`</td><td>D. `:set tablength=4`</td></tr>
</table>

**31. 在VI编辑器中，若要在不退出编辑器的情况下执行外部Shell命令“ls -la”，应使用的正确命令是(  )**

<table>
  <tr><td width="50%">A. `:!ls -la`</td><td>B. `:shell ls -la`</td></tr>
  <tr><td>C. `:exec ls -la`</td><td>D. `:run "ls -la"`</td></tr>
</table>

**32. 在Emacs编辑器中，若要保存当前编辑的文件，应使用以下哪种快捷键组合(  )**

<table>
  <tr><td width="50%">A. Ctrl + s</td><td>B. Ctrl + x Ctrl + s</td></tr>
  <tr><td>C. Ctrl + Shift + s</td><td>D. Ctrl + Alt + s</td></tr>
</table>

**33. OpenSSH服务端默认的监听端口号是(  )**

<table>
  <tr><td width="50%">A. 21</td><td>B. 80</td></tr>
  <tr><td>C. 22</td><td>D. 23</td></tr>
</table>

**34. OpenSSH的服务器端配置文件默认路径是(  )**

<table>
  <tr><td width="50%">A. `/etc/ssh/sshd_config`</td><td>B. `/etc/ssh/ssh_config`</td></tr>
  <tr><td>C. `/home/user/.ssh/config`</td><td>D. `/etc/sshd/sshd.conf`</td></tr>
</table>

**35. 在使用GCC编译C程序时，下列哪个命令行选项用于生成带调试信息的可执行文件(  )**

<table>
  <tr><td width="50%">A. `-S`</td><td>B. `-O`</td></tr>
  <tr><td>C. `-c`</td><td>D. `-g`</td></tr>
</table>

**36. 关于GCC编译器的命令行选项，下列描述正确的是(  )**

<table>
  <tr><td width="50%">A. -O2选项提供了较高级别的优化，平衡了编译时间和执行性能</td><td>B. -Wall选项用于提供最高级别的代码优化</td></tr>
  <tr><td>C. -g选项可以去除所有调试信息以减小可执行文件大小</td><td>D. -c选项用于直接生成可执行文件而跳过链接步骤</td></tr>
</table>

**37. 关于GDB调试命令的功能，下列描述正确的是(  )**

<table>
  <tr><td width="50%">A. `info breakpoints` 用于列出所有断点信息</td><td>B. continue命令用于单步执行当前行代码</td></tr>
  <tr><td>C. next命令用于进入当前行的函数调用内部</td><td>D. watch命令用于实时显示某个变量的值</td></tr>
</table>

**38. 在GDB中，哪个命令可以用来单步执行程序中的下一条语句，如果该语句为函数调用，同时进入函数调用内部(  )**

<table>
  <tr><td width="50%">A. next</td><td>B. step</td></tr>
  <tr><td>C. continue</td><td>D. run</td></tr>
</table>

**39. 在Linux环境下进行基于MVC的Java Web开发时，以下哪个组件通常负责处理用户请求并决定调用哪个业务逻辑组件(  )**

<table>
  <tr><td width="50%">A. 服务（Service）</td><td>B. 模型（Model）</td></tr>
  <tr><td>C. 视图（View）</td><td>D. 控制器（Controller）</td></tr>
</table>

**40. 在Linux环境下，要搭建一个开源Web服务器以支持Java应用的运行，以下哪个服务器软件是最佳选择(  )**

<table>
  <tr><td width="50%">A. Apache Tomcat</td><td>B. Microsoft IIS</td></tr>
  <tr><td>C. Nginx</td><td>D. Apache HTTP Server</td></tr>
</table>

## 二、填空题（共 10 题）

41. Linux的一个重要设计理念是“一切皆\_\_\_\_\_\_\_\_\_\_”。
42. Linux系统中，守护（后台）进程通常名字以字母\_\_\_\_\_\_\_\_\_\_结尾，表示它是一个守护进程。
43. Linux系统中，每个进程都具有唯一标识，称为\_\_\_\_\_\_\_\_\_\_。
44. 在Linux文件权限控制中，表示可执行权限的字母标记为\_\_\_\_\_\_\_\_\_\_。
45. 在Linux系统中，若要完全删除用户账号“student”及其主目录，应使用的命令是：\_\_\_\_\_\_\_\_\_\_。
46. 要显示当前目录下的所有文件（包括隐藏文件），应该使用的命令是：\_\_\_\_\_\_\_\_\_\_。
47. Linux中用于挂载文件系统的常用命令是：\_\_\_\_\_\_\_\_\_\_。
48. Linux系统中存储进程信息、系统状态和硬件信息的目录是：\_\_\_\_\_\_\_\_\_\_。
49. 查看所有用户的所有进程详细信息的常用命令是：\_\_\_\_\_\_\_\_\_\_。
50. 在Linux系统下进行C/C++程序开发时，用于自动化编译过程、定义编译规则和依赖关系的文件通常为：\_\_\_\_\_\_\_\_\_\_。

## 三、综合应用题（共 2 题）

**1. 假设现在有一台本地主机名为client，远程服务器主机名为devsrv，用户需要从本地客户端以用户名developer免密登录到远程服务器devsrv。**

(1) 为此应首先在本地主机client上运行【51】\_\_\_\_\_\_\_\_\_\_命令生成公私密钥对；之后使用如下命令将公钥一键复制到远程服务器上对应用户的认证文件中：
   `ssh-copy-id` 【52】\_\_\_\_\_\_\_\_\_\_
   配置完成后，即可在本地终端使用命令 `ssh developer@devsrv` 免密登录到远程服务器上。
(2) 开发者成功登录devsrv服务器后，计划在目录 `/home/developer/project/` 下编译一个名为app.c的C语言程序。首先在终端中进入该目录，并使用gcc进行编译，调用如下命令：
   `gcc -c app.c` 【53】\_\_\_\_\_\_\_\_\_\_ `/home/developer/include -Wall -g`
(3) 随后，开发者需要将该文件与位于 `/home/developer/libs/` 的功能函数库文件libsupport.a链接，使用：
   `gcc app.o` 【54】\_\_\_\_\_\_\_\_\_\_ `app` 【55】\_\_\_\_\_\_\_\_\_\_ `/home/developer/libs -lsupport`
(4) 编译成功后，需要使用gdb调试程序app。启动gdb应输入：【56】\_\_\_\_\_\_\_\_\_\_
(5) 启动调试器后，在app.c文件的第22行设置断点，输入命令：【57】\_\_\_\_\_\_\_\_\_\_
(6) 接下来输入run命令运行程序，当程序运行到断点处停下时，如希望查看函数调用时各个函数的调用栈信息，则应输入【58】\_\_\_\_\_\_\_\_\_\_命令。
(7) 调试完成后，开发者决定在后台运行程序app，输入命令：
   `[developer@devsrv project]$` 【59】\_\_\_\_\_\_\_\_\_\_
(8) 为提升开发效率，开发者进一步编写了Makefile文件，使用【60】\_\_\_\_\_\_\_\_\_\_工具管理编译过程。

**2. 编写一个Shell脚本，用于批量处理日志文件并生成简单的统计报告。该脚本满足以下要求：**

(1) 接受一个日志目录作为参数
(2) 处理该目录下所有以.log结尾的文件
(3) 对每个日志文件统计：错误（ERROR）的数量；警告（WARNING）的数量；成功（SUCCESS）的数量
(4) 生成一个包含所有统计信息的报告文件
(5) 汇总出包含最多错误的前3个日志文件
(6) 如果没有指定目录或目录不存在，输出适当的错误信息

```bash
#!/bin/bash
# 日志文件统计脚本
# 用法: ./log_analyzer.sh <日志目录>
# 检查参数
if [ 【61】__________ -ne 1 ];then
  echo "错误: 请提供日志文件目录"
  echo "用法: $0 <日志目录>"
  exit 1
fi
LOG_DIR=$1
# 检查目录是否存在
if [ ! 【62】__________ "$LOG_DIR" ]; then
  echo "错误: 目录 '$LOG_DIR' 不存在"
  exit 1
fi
# 检查是否有日志文件
LOG_FILES=$(find "$LOG_DIR" 【63】__________ "*.log")
if [ -z "$LOG_FILES" ];then
  echo "错误: 在 '$LOG_DIR' 中没有找到日志文件"
  exit 1
fi
# 创建报告文件
REPORT_FILE="log_report_$(date +%Y%m%d_%H%M%S).txt"
echo "日志文件分析报告 - $(date)" > $REPORT_FILE
echo "==========================================" >> $REPORT_FILE
echo "" >> $REPORT_FILE
# 用于存储错误数量和文件名的临时文件
ERROR_COUNTS="/tmp/error_counts_$$"
> $ERROR_COUNTS
# 处理每个日志文件
【64】__________ LOG_FILE in $LOG_FILES; do
  FILENAME=$(basename "$LOG_FILE")
  #统计各类消息
  ERROR_COUNT=$(grep -c 'ERROR' "$LOG_FILE")
  WARNING_COUNT=$(grep -c 'WARNING' "$LOG_FILE")
  SUCCESS_COUNT=$(grep -c '【65】__________' "$LOG_FILE")
  #记录错误数量用于排序
  echo "$ERROR_COUNT $FILENAME" >> $ERROR_COUNTS
  #添加到报告
  echo "文件: 【66】__________" >> $REPORT_FILE
  echo "错误(ERROR):$ERROR_COUNT" >> $REPORT_FILE
  echo "警告(WARNING):$WARNING_COUNT" >> $REPORT_FILE
  echo "成功(SUCCESS):$SUCCESS_COUNT" >> $REPORT_FILE
  echo "" >> $REPORT_FILE
【67】__________
#添加汇总信息
echo "==========================================" >> $REPORT_FILE
echo "错误最多的前3个文件:" >> $REPORT_FILE
【68】__________ -nr $ERROR_COUNTS | head -3 |while read COUNT FILENAME; do
  echo "  $FILENAME: $COUNT 个错误" >> $REPORT_FILE
done
# 删除临时文件
rm -f $【69】__________
echo "分析完成，报告已保存到 $REPORT_FILE"
exit 【70】__________
```

---

<br>

## 试卷（七） 参考答案与解析

### 一、单项选择题

1. **D** | 【解析】程序运行时的动态执行实例是进程，而非线程；线程是进程内的执行单元。进程拥有独立的地址空间，而线程没有独立的地址空间，共享所属进程的地址空间、文件描述符、内存等资源，故选项D描述正确。
2. **A** | 【解析】Linux是开源、类Unix系统，广泛应用于服务器、嵌入式设备、PC等，A选项描述正确；Linux可以作为桌面系统用于个人计算机，B选项错误；Linux由林纳斯·托瓦兹等人开发，不是微软产品，也不是专有软件，C选项错误；Linux天生支持多用户、多任务，D选项错误。
3. **A** | 【解析】`rpm -q` 是查询（query）指定软件包是否已安装的命令。`rpm -i` 用于安装RPM包，`rpm -e` 用于卸载已安装的软件包，`rpm --rebuild` 用于重建数据库。
4. **B** | 【解析】`*[!s]log` 匹配以单个非s字符和log结尾的文件（比如alog、1log），但无法匹配testlog这种长文件名；`[!s]*log` 是不以s开头加上任意内容，并以log结尾，符合题意；`?s*log` 匹配第二个字符是s且以log结尾的文件；`[s]*log` 是以s开头和log结尾。
5. **A** | 【解析】Shell赋值语法要求是“变量名=值”，等号两侧绝对不能有空格，并且字符串包含空格必须用双引号包裹；B选项等号两侧有空格，报错；C选项字符串有空格却没加引号，赋值失败；D选项 `$` 符号是读取变量用的，赋值时不能加。
6. **A** | 【解析】A选项 `$(( ))` 是Shell标准的整数算术运算语法，可以直接计算变量数值；B选项只是把字符串a+b赋给sum，不会做任何计算；C选项 `$()` 是执行命令的语法，a+b不是合法命令；D选项括号 `()` 通常用于创建子shell或定义数组，此处写法不符合标准用法。
7. **C** | 【解析】/etc/group存储用户组信息；/etc/passwd存储用户基本信息；/etc/shadow存储用户加密密码及策略，仅root可读，保障系统安全；/etc/gshadow存储用户组密码。
8. **A** | 【解析】`usermod -aG` 是将用户追加到附属组的操作。useradd是新建用户，groupadd是新建组，chgrp是修改文件/目录所属组，均不符合题意。
9. **C** | 【解析】finger用于查看详细用户信息；who显示当前登录用户；id直接显示当前用户的UID、GID及所有所属组信息；lastlog显示登录记录。
10. **A** | 【解析】uniq命令仅能去除相邻重复行，因此需先通过sort命令将文件内容排序，使得相同行相邻，再通过管道传递给uniq进行去重。
11. **A** | 【解析】find命令配合 `-exec` 选项能够递归查找并执行mv操作，确保处理到所有子目录中的文件。
12. **A** | 【解析】软链接（符号链接）允许指向尚不存在的目标；硬链接不可跨越文件系统。
13. **A** | 【解析】`mkdir -p` 支持递归创建多级目录，`-m 755` 可在创建时直接设定权限。
14. **C** | 【解析】读(r)=4，写(w)=2。所有者(6=4+2)可读写，组(4)可读，他人(4)可读，组合得644。
15. **B** | 【解析】ps是查看进程快照，只显示执行那一刻的状态；top实时动态显示系统进程、CPU、内存等资源占用，交互式、持续刷新；kill用于终止进程，不负责监控；pstree以树状结构展示进程关系，无实时监控功能。
16. **C** | 【解析】pkill能通过进程名终止进程，但其匹配方式更灵活；kill主要用于通过进程的ID(PID)来终止单个进程；killall的核心功能就是根据进程名称来终止进程，执行 `killall <进程名>` 时，会向所有与指定名称完全匹配的进程发送终止信号；ps是查看进程状态的快照，不具备终止进程的功能。
17. **A** | 【解析】pstree以树形结构显示进程之间的父子关系，跟上用户名（如student）时，会专门显示该用户启动的所有进程；lsof用于列出用户或进程打开的文件；top是动态实时的系统监控工具，以列表形式展示，无法直观体现进程间的父子关系；ps输出是扁平列表，无法直接看出层级关系。
18. **A** | 【解析】A选项 `-t ext4` 明确指定文件系统为EXT4，设备/dev/sdc1挂载到/mnt/data；B选项没有用 `-t` 明确指定文件系统类型，不符合“明确指定类型”的要求；C选项设备和挂载点顺序写反；D选项指定的文件系统是NTFS，与题目要求不符。
19. **A** | 【解析】A选项以可读格式（GB/MB）查看第一块SCSI/SATA硬盘所在文件系统的磁盘空间使用情况；B选项du是统计文件/目录大小的命令，无法识别设备文件的磁盘空间；C选项/dev/hda是老式IDE硬盘的命名；D选项既用错命令又用错硬盘名。
20. **B** | 【解析】在parted交互模式中，print是专门用于查看当前磁盘分区布局、磁盘信息、分区表类型的核心子命令；list不是parted交互模式下的有效子命令，parted中也没有show和display命令。
21. **A** | 【解析】free是专门用于查看内存使用情况的工具，清晰展示物理内存和交换分区（Swap）的总量、已用量、空闲量；ls与查看内存无关；vmstat更侧重系统整体性能快照；top主要功能是进程监控，而非专门查看内存摘要。
22. **A** | 【解析】在Linux中启用用户或组磁盘配额，必须先在/etc/fstab中为对应文件系统添加配额挂载参数（usrquota、grpquota），重新挂载后才能启用配额功能；B选项与启用配额无关；C选项不是必需步骤，quotacheck会自动处理；D选项配额在文件系统层面管理，与/etc/passwd无关。
23. **B** | 【解析】ping用于测试网络连通性并测量延迟，但不显示数据包经过的路径；traceroute专门用于确定IP数据包从源主机到目标主机所经过的完整路径；host用于执行DNS查询；tcpdump是网络数据包分析器（抓包工具），不是追踪路径。
24. **A** | 【解析】A选项是Linux下临时禁用网卡的标准命令，重启网络或系统后会失效；B选项ifconfig没有 `--disable` 选项，正确写法是 `ifconfig eth0 down`；C选项是停止网络配置服务，不是禁用单个接口；D选项 `systemctl disable` 是永久禁用服务。
25. **D** | 【解析】netstat用于显示网络连接、路由表和网络接口统计信息；ifconfig用于配置和显示网络接口信息；hostname既可以查看当前系统的主机名，也可以临时更改主机名；route用于显示和操作IP路由表。
26. **C** | 【解析】/etc/主要用于存放系统的配置文件；/usr/adm是早期Unix日志目录，现代Linux已基本不用；/var/log是存放系统日志和应用程序日志的标准目录；/var/run用于存放系统启动后产生的运行时数据。
27. **A** | 【解析】httpd作为Web服务器，监听网络端口（通常是80或443），接收客户端的HTTP/HTTPS请求并返回相应资源；处理DNS解析的通常是named（BIND）；提供数据库服务的是MySQL、PostgreSQL等；邮件收发由Postfix、Sendmail等负责。
28. **A** | 【解析】命令模式下按 `:` 键会切换到末行模式，底部出现冒号提示符，可输入保存、退出等命令；按i键是进入插入模式，保存文件需在末行模式输入 `:w`；插入模式下按Esc是返回命令模式，退出需在末行模式输入 `:q`；dd是命令模式下删除当前行的快捷键，末行模式删除行用 `:d`。
29. **C** | 【解析】命令模式下dd的作用是删除（剪切）当前整行，撤销上一步操作的命令是u；x删除当前字符仅在命令模式下生效；命令模式下yy是复制当前整行，C选项正确；命令模式下p是粘贴，进入插入模式的快捷键是i、a、o等。
30. **A** | 【解析】在VI编辑器中，要将Tab键的宽度设置为4个字符，应使用 `:set tabstop=4`；tabsize、tabwidth、tablength都不是Vi/Vim的合法配置参数。
31. **A** | 【解析】在Vim/Vi中，不退出编辑器直接执行外部Shell命令的固定语法是 `:!外部命令`，执行后临时显示结果，按回车即可回到编辑器；`:shell` 是打开一个新的交互式Shell；`:exec`、`:run` 在Vi/Vim中没有这种执行外部命令的语法。
32. **B** | 【解析】在Emacs中保存文件的标准快捷键是先按 Ctrl + x，再按 Ctrl + s。
33. **C** | 【解析】FTP默认端口是21，HTTP默认端口是80，SSH（安全外壳协议）默认端口是22，用于安全的远程登录和管理；Telnet默认端口是23，以明文方式传输数据，安全性远低于SSH。
34. **A** | 【解析】/etc/ssh/sshd_config是OpenSSH服务器（sshd）的主配置文件，可设置监听端口、允许登录的用户、认证方式等；/etc/ssh/ssh_config是客户端的系统级配置文件；/home/user/.ssh/config是客户端的用户级配置文件。
35. **D** | 【解析】`-S` 只编译不汇编，生成汇编文件（.s）；`-O` 开启代码优化，会移除调试信息，不适合调试；`-c` 只编译不链接，生成目标文件（.o）；`-g` 生成调试信息（GDB可识别），可执行文件包含源代码行号、变量名等调试数据。
36. **A** | 【解析】`-O2` 是GCC最常用的优化级别，兼顾编译效率和运行性能，A选项正确；`-Wall` 是开启所有常用的编译警告，最高级别优化是 `-O3`，B选项错误；`-g` 是生成调试信息，去除调试信息用strip命令或 `-s` 选项，C选项错误；`-c` 只编译不链接，生成目标文件，D选项错误。
37. **A** | 【解析】`info breakpoints` 是GDB中专门查看所有已设置断点的命令，会展示断点编号、位置、状态、命中次数等完整信息；continue是继续运行程序直到遇到下一个断点或程序结束；next是不进入函数的单步执行（逐过程）；watch是监视点命令，当变量的值发生改变时暂停程序。
38. **B** | 【解析】next遇到函数调用不会进入函数内部，直接执行完整个函数并跳到下一行；step遇到函数调用会进入函数内部；continue是继续执行程序直到遇到下一个断点；run是启动程序运行。
39. **D** | 【解析】控制器（Controller）接收用户的所有请求，解析请求参数，决定调用哪个业务逻辑组件（Service），处理完成后再决定跳转哪个视图页面；模型（Model）负责封装数据和业务数据处理逻辑；视图（View）负责展示数据；服务（Service）属于业务逻辑层，是被Controller调用的组件。
40. **A** | 【解析】Apache Tomcat是开源、跨平台（完美支持Linux），专为Java Servlet/JSP设计的Web容器+应用服务器，是运行Java项目的标准首选；Microsoft IIS仅Windows使用；Nginx不内置Java运行环境，一般用来反向代理Tomcat；Apache HTTP Server主要处理静态资源，无Java解析能力。

### 二、填空题

41. **文件** | 【解析】“一切皆文件”是Linux核心设计理念，普通文件、目录、设备、管道等在系统中都以文件形式来访问管理。
42. **d** | 【解析】Linux守护进程（后台服务进程）命名习惯大多以字母d结尾，代表daemon守护程序，例如sshd、httpd。
43. **PID** | 【解析】PID是操作系统内核为每个正在运行的进程分配的唯一标识，系统通过PID来识别、管理和控制进程。
44. **x** | 【解析】Linux文件权限：r代表读、w代表写、x代表可执行。
45. **`userdel -r student`** | 【解析】删除用户账号使用userdel命令，加上参数 `-r` 可同步删除该用户的主目录、邮箱等所有关联数据。另外 `userdel --remove student` 和 `deluser --remove-home student` 也应判对给分。
46. **`ls -a`** | 【解析】`-a` 可以让ls命令显示所有文件，包括以点开头的隐藏文件。另外 `ls --all` 通常也可判对；若按题图原答案口径，`ls -A` 也可给分。
47. **mount** | 【解析】Linux中mount是挂载文件系统、磁盘、分区、镜像等的命令。
48. **/proc** | 【解析】/proc是虚拟文件系统，不占用实际磁盘空间，内核会动态在此目录下存放所有进程信息、实时系统运行状态、内核参数，并提供CPU、内存、硬件、网络等系统硬件信息。
49. **`ps -ef`** | 【解析】查看所有用户的全部进程完整详细信息，标准答案写为 `ps -ef`；`ps aux` 也常用于显示系统中所有进程的详细信息，按题图原答案口径，`ps -aux` 也可给分。
50. **makefile** | 【解析】makefile是Linux下C/C++自动化编译的标准配置文件，通过定义编译规则、文件依赖关系、链接指令，让make工具自动完成整个编译、链接流程。

### 三、综合应用题

**1. 参考答案：**
【51】 `ssh-keygen` | 【解析】要在本地主机生成公私密钥对，需要使用ssh-keygen命令。
【52】 `developer@devsrv` | 【解析】ssh-copy-id用于将本地的公钥复制到远程服务器，语法格式为 `ssh-copy-id [用户@]主机名`。
【53】 `-I` | 【解析】GCC使用 `-I`（大写的i）参数来添加头文件搜索路径。
【54】 `-o` | 【解析】`-o` 用于指定输出文件的名字，这里将生成的可执行文件命名为app。
【55】 `-L` | 【解析】`-L` 用于指定库文件（.a或.so）的搜索路径，告诉链接器去/home/developer/libs目录下找库文件。
【56】 `gdb app` | 【解析】启动GDB调试器的标准命令是 `gdb 可执行文件名`。
【57】 `break app.c:22` | 【解析】在GDB中设置断点的命令是break，在多文件项目中为确保准确性，使用“文件名:行号”的格式。
【58】 `backtrace` | 【解析】当程序在断点处停下时，查看函数调用栈信息的命令是backtrace。
【59】 `./app &` | 【解析】若要让程序在后台运行、不占用当前终端窗口，需要在命令末尾加上 `&` 符号。
【60】 `make` | 【解析】make是读取当前目录下Makefile并自动执行编译命令的工具。

**2. 参考答案：**
【61】 `$#` | 【解析】`$#` 是Shell中的特殊变量，代表传递给脚本的参数个数，这里需要检查用户是否只提供了一个参数，`-ne` 表示“不等于”。
【62】 `-d` | 【解析】`-d` 用于判断一个路径是否为目录，`!` 表示取反，如果 `$LOG_DIR` 不是一个存在的目录，则执行报错逻辑。
【63】 `-name` | 【解析】find命令的标准用法是 `find <路径> -name "*.log"`，用于查找指定路径下所有以.log结尾的文件。
【64】 `for` | 【解析】for…in是Shell脚本中最常用的循环结构，用于遍历find命令找到的所有日志文件列表。
【65】 `SUCCESS` | 【解析】需要统计“成功”的数量，`grep -c` 用于统计匹配行的数量，这里填入匹配字符串SUCCESS。
【66】 `$FILENAME` | 【解析】循环内部已通过 `FILENAME=$(basename "$LOG_FILE")` 提取了当前文件名并赋值给FILENAME变量，因此报告中输出文件名应填写FILENAME。
【67】 `done` | 【解析】Shell中for循环的结束标记使用done。
【68】 `sort` | 【解析】为找出错误最多的文件，需要对临时文件 `$ERROR_COUNTS` 排序，`sort -nr` 表示按数字大小（`-n`）逆序（`-r`，即从大到小）排列。
【69】 `ERROR_COUNTS` | 【解析】ERROR_COUNTS指向之前创建的临时数据文件，脚本运行结束后不再需要，删除它是为了保持系统环境整洁。
【70】 `0` | 【解析】在Shell脚本中，`exit 0` 表示脚本成功执行并正常退出。
