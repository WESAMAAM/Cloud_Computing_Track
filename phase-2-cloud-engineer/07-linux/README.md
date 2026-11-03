# Linux | لينكس

| At a Glance | نظرة سريعة |
| :--- | ---: |
| **Level:** Beginner, no prior experience needed | **المستوى:** مبتدئ، لا يحتاج خبرة سابقة |
| **Estimated duration:** 4 to 6 weeks at about 1 hour per day (an estimate, to be adjusted after the first cohort) | **المدة التقديرية:** من 4 إلى 6 أسابيع بمعدل ساعة يومياً (تقدير مبدئي يُعدّل بعد أول دفعة) |
| **Cost:** Free (all resources on this page) | **التكلفة:** مجاني (جميع مصادر هذه الصفحة) |
| **Outcome:** Comfortable using the terminal, able to connect to a Linux server, and able to write simple Bash scripts | **النتيجة:** إجادة استخدام الطرفية، والاتصال بخادم لينكس، وكتابة سكربتات باش بسيطة |

## Table of Contents

* [1- Definition and Introduction](#1--definition-and-introduction)
 * [For a Better Understanding](#for-a-better-understanding)
* [2- Now, Let's Dig in](#2--now-lets-dig-in)
* [3- Essential Commands](#3--essential-commands)
* [4- Hands-on Labs](#4--hands-on-labs)
 * [Mini Project: Server Health Report](#mini-project-server-health-report)
* [5- Test Yourself](#5--test-yourself)
* [6- To Go Deeper](#6--to-go-deeper)
* [7- Additional](#7--additional)
* [8- Still Needed](#8--still-needed)

---

# 1- Definition and Introduction

| **What is Linux?** | **ما هو لينكس؟** |
| :--- | ---: |
| Linux is a free and open-source operating system family built around the Linux kernel, created by Linus Torvalds in 1991. It comes in versions called "distributions", such as Ubuntu, Debian, and Amazon Linux. It is widely used on servers, and in cloud computing you will mostly work with it through the command line (terminal) rather than a graphical interface. | لينكس عائلة من أنظمة التشغيل المجانية ومفتوحة المصدر، مبنية حول نواة لينكس التي أنشأها لينوس تورفالدز عام 1991. تأتي بإصدارات تسمى "التوزيعات" مثل أوبونتو، ودبيان، وأمازون لينكس. تُستخدم على نطاق واسع في الخوادم، وفي الحوسبة السحابية ستتعامل معها غالباً عبر سطر الأوامر بدلاً من الواجهة الرسومية. |
| **Key Features of Linux:** | **:الميزات الرئيسية للينكس** |
| **1- Free and Open Source:** Anyone can use, study, and modify Linux, which is why it has a huge community and thousands of free tools. | 1- مجاني ومفتوح المصدر: يمكن لأي شخص استخدام لينكس ودراسته وتعديله، ولهذا لديه مجتمع ضخم وآلاف الأدوات المجانية. |
| **2- Command Line (Terminal):** You control the system by typing commands. It is faster and more powerful than clicking, and it is how cloud servers are managed. | 2- سطر الأوامر: تتحكم بالنظام عبر كتابة الأوامر، وهذا أسرع وأقوى من الضغط على الأزرار، وهو الطريقة التي تُدار بها الخوادم السحابية. |
| **3- Common on Servers and the Cloud:** AWS offers its own distribution, Amazon Linux, as an option for its EC2 servers, and many other Linux distributions are available too. | 3- منتشر في الخوادم والسحابة: تقدم أمازون توزيعتها الخاصة (أمازون لينكس) كخيار لخوادم الحوسبة المرنة، كما تتوفر توزيعات لينكس أخرى كثيرة. |
| **4- Permissions and Security:** Every file has an owner and permission settings that control who can read, edit, or run it. | 4- الصلاحيات والأمان: لكل ملف مالك وإعدادات صلاحيات تحدد من يستطيع قراءته أو تعديله أو تشغيله. |
| **5- Automation:** Repetitive tasks can be written once as a script (Bash) and run automatically. | 5- الأتمتة: يمكن كتابة المهام المتكررة مرة واحدة على شكل سكربت (باش) وتشغيلها تلقائياً. |

| **Why Linux for Cloud Engineers?** | **لماذا لينكس لمهندس السحابة؟** |
| :--- | ---: |
| Cloud servers are usually managed remotely, with no screen and no mouse. If you can use the terminal, you can fix problems, read logs, install software, and automate tasks on any server. It also supports the next steps of this track: Terraform builds servers, and Linux is what you work with once they are running. | الخوادم السحابية تُدار عادةً عن بُعد، بلا شاشة ولا فأرة. إذا أتقنت الطرفية تستطيع إصلاح المشاكل وقراءة السجلات وتثبيت البرامج وأتمتة المهام على أي خادم. وهي أيضاً تدعم الخطوات القادمة في المسار: تيرافورم يبني الخوادم، ولينكس هو ما تتعامل معه بعد تشغيلها. |

# For a Better Understanding

| To Make It Clear | حتى تتضح الصورة |
| :--- | ---: |
| Imagine managing a huge building. A graphical interface is like a panel of colored buttons: easy, but limited to what the buttons offer. The command line is like speaking directly to the building manager with precise written orders. You can ask for anything, and repeat the same order a thousand times with one line. That is why cloud engineers use it. | تخيل أنك تدير مبنى ضخماً. الواجهة الرسومية تشبه لوحة أزرار ملونة: سهلة لكنها محدودة بما تقدمه الأزرار. أما سطر الأوامر فيشبه أن تتحدث مباشرة مع مدير المبنى بأوامر مكتوبة ودقيقة. تستطيع أن تطلب أي شيء، وتكرر نفس الأمر ألف مرة بسطر واحد. ولهذا يعتمد عليه مهندسو السحابة. |

<div align="center">

## Check out the following videos to learn more about Linux:

</div>

<div align="center">

<a href="https://www.youtube.com/watch?v=sWbUDq4S6Y8">
  <img src="https://img.youtube.com/vi/sWbUDq4S6Y8/hqdefault.jpg" width="700">
</a>
<br>
<a href="https://www.youtube.com/watch?v=sWbUDq4S6Y8"><b>Introduction to Linux – Full Course for Beginners (freeCodeCamp, about 6 hours)</b></a>

</div>

---

<div align="center">

<a href="https://www.youtube.com/results?search_query=Fireship+100+Linux+Things+you+Need+to+Know"><b>Quick overview (12 min): "100+ Linux Things you Need to Know" by Fireship</b></a>

<br>

<a href="https://www.youtube.com/results?search_query=freeCodeCamp+Linux+Crash+Course+for+Beginners+with+Labs"><b>Hands-on: "Linux Crash Course for Beginners with Labs" by freeCodeCamp</b></a>

</div>

# 2- Now, Let's Dig in

| Introduction to Linux (LFS101) | مقدمة في لينكس |
| :--- | ---: |
| This free, self-paced course from the Linux Foundation introduces Linux to beginners, using both the graphical interface and the command line. | كورس مجاني ذاتي التعلم من مؤسسة لينكس (Linux Foundation) يعرّف المبتدئين بلينكس، باستخدام الواجهة الرسومية وسطر الأوامر. |
| It covers the Linux philosophy and components, system configuration, command-line operations, finding documentation, processes, file operations, and text editors. | يغطي فلسفة لينكس ومكوناته، وإعدادات النظام، وعمليات سطر الأوامر، والبحث في التوثيق، والعمليات، والتعامل مع الملفات، ومحررات النصوص. |
| **By the end of this course, learners will be able to:** | **:بنهاية الكورس، سيكون المتعلم قادراً على** |
| 1- Understand what Linux is and how its distributions differ. | 1- فهم ما هو لينكس وكيف تختلف توزيعاته. |
| 2- Work with both the graphical interface and the command line. | 2- العمل بالواجهة الرسومية وسطر الأوامر. |
| 3- Navigate the file system and manage files and folders. | 3- التنقل في نظام الملفات وإدارة الملفات والمجلدات. |
| 4- Find help using the built-in documentation. | 4- إيجاد المساعدة باستخدام التوثيق المدمج في النظام. |
| 5- Understand and manage processes. | 5- فهم العمليات وإدارتها. |
| 6- Edit text files from the terminal. | 6- تحرير الملفات النصية من الطرفية. |

<div align="center">

# [Introduction to Linux (LFS101)](https://training.linuxfoundation.org/training/introduction-to-linux/)

</div>

| Suggested 4-Week Plan (estimate) | الخطة المقترحة لأربعة أسابيع (تقديرية) |
| :--- | ---: |
| **Week 1:** What Linux is, distributions, terminal basics, navigating the file system, creating, copying, moving, and deleting files. | **الأسبوع الأول:** ما هو لينكس، التوزيعات، أساسيات الطرفية، التنقل في نظام الملفات، إنشاء الملفات ونسخها ونقلها وحذفها. |
| **Week 2:** Viewing and searching text, pipes and redirection, users and permissions. | **الأسبوع الثاني:** عرض النصوص والبحث فيها، الأنابيب وإعادة التوجيه، المستخدمون والصلاحيات. |
| **Week 3:** Processes and services, disk and memory usage, networking commands, installing packages. | **الأسبوع الثالث:** العمليات والخدمات، استخدام القرص والذاكرة، أوامر الشبكات، تثبيت الحزم. |
| **Week 4:** Bash scripting basics, connecting to an EC2 Linux server, and the mini project. | **الأسبوع الرابع:** أساسيات سكربتات باش، الاتصال بخادم لينكس على EC2، والمشروع المصغر. |

| Where to Practice | أين أتدرب؟ |
| :--- | ---: |
| **Option 1 (easiest on Windows):** Install WSL (Windows Subsystem for Linux). In PowerShell, run `wsl --install`, then restart if asked. | **الخيار الأول (الأسهل على ويندوز):** ثبّت WSL (نظام ويندوز الفرعي للينكس). في PowerShell نفّذ الأمر `wsl --install` ثم أعد التشغيل إذا طُلب منك. |
| **Option 2:** Run Linux inside a virtual machine on your computer. | **الخيار الثاني:** شغّل لينكس داخل جهاز افتراضي على حاسبك. |
| **Option 3:** Create a small Linux server on AWS (EC2) and connect to it. Needed for Lab 5. | **الخيار الثالث:** أنشئ خادم لينكس صغيراً على AWS (خدمة EC2) واتصل به. مطلوب للتمرين الخامس. |

| Which Package Command? | أي أمر تثبيت أستخدم؟ |
| :--- | ---: |
| Ubuntu and Debian (including the default WSL Ubuntu) use `apt`. Amazon Linux 2023 uses `dnf`. The commands are similar but not identical, so check which distribution you are on. | أوبونتو ودبيان (ومنها أوبونتو الافتراضية في WSL) تستخدم `apt`. أما أمازون لينكس 2023 فتستخدم `dnf`. الأوامر متشابهة لكنها ليست متطابقة، فتأكد من التوزيعة التي تعمل عليها. |

> **Important Note**
> A server left running on AWS may incur costs. Check the current Free Tier terms on the AWS website, and always terminate (delete) your EC2 instance when you finish practicing.

# 3- Essential Commands

| Command | What it does | الوظيفة |
| :--- | :--- | ---: |
| `pwd` | Shows the folder you are in | يعرض المجلد الذي أنت فيه |
| `ls` | Lists files and folders (`ls -l` for details) | يعرض الملفات والمجلدات (`ls -l` للتفاصيل) |
| `cd` | Changes folder | ينتقل إلى مجلد آخر |
| `mkdir` | Creates a folder | ينشئ مجلداً |
| `touch` | Creates an empty file | ينشئ ملفاً فارغاً |
| `cp` | Copies a file or folder | ينسخ ملفاً أو مجلداً |
| `mv` | Moves or renames | ينقل أو يعيد التسمية |
| `rm` | Deletes a file (`rm -r` for folders). There is no recycle bin | يحذف ملفاً (`rm -r` للمجلدات). لا يوجد سلة محذوفات |
| `cat` | Prints a file's content | يطبع محتوى ملف |
| `less` | Reads a long file page by page | يقرأ ملفاً طويلاً صفحة صفحة |
| `head` / `tail` | Shows the first or last lines (`tail -f` follows a log live) | يعرض أول أو آخر الأسطر (`tail -f` لمتابعة السجل مباشرة) |
| `grep` | Searches for text inside files | يبحث عن نص داخل الملفات |
| `find` | Searches for files by name | يبحث عن ملفات بالاسم |
| `chmod` | Changes file permissions | يغيّر صلاحيات الملف |
| `chown` | Changes the file owner | يغيّر مالك الملف |
| `sudo` | Runs a command with admin privileges | ينفذ أمراً بصلاحيات المدير |
| `ps` / `top` | Shows running processes | يعرض العمليات الجارية |
| `kill` | Stops a process | يوقف عملية |
| `systemctl` | Starts, stops, and checks services | يشغّل الخدمات ويوقفها ويفحصها |
| `df -h` | Shows disk space | يعرض مساحة القرص |
| `free -h` | Shows memory usage | يعرض استخدام الذاكرة |
| `ping` | Tests connection to a host | يختبر الاتصال بجهاز |
| `curl` | Sends a request to a web address | يرسل طلباً إلى عنوان ويب |
| `ssh` | Connects to a remote server | يتصل بخادم بعيد |
| `man` | Opens the manual of any command | يفتح دليل استخدام أي أمر |
| `nano` | A simple text editor for the terminal | محرر نصوص بسيط للطرفية |

| Two Symbols Worth Knowing | رمزان تستحق معرفتهما |
| :--- | ---: |
| **Redirection:** `>` writes output to a file (overwriting it), and `>>` adds to the end of the file. Example: `ls > files.txt` | **إعادة التوجيه:** الرمز `>` يكتب الناتج في ملف (ويستبدل محتواه)، والرمز `>>` يضيف في نهاية الملف. مثال: `ls > files.txt` |
| **Pipe:** The vertical bar symbol sends the output of one command into another. Example: `ps aux` followed by the pipe and `grep ssh` shows only the processes that mention ssh. | **الأنبوب:** الخط العمودي يمرر ناتج أمر إلى أمر آخر. مثال: الأمر `ps aux` ثم الأنبوب ثم `grep ssh` يعرض فقط العمليات التي تذكر ssh. |

# 4- Hands-on Labs

| Lab 1: Navigation | التمرين الأول: التنقل |
| :--- | ---: |
| Open the terminal, find where you are with `pwd`, list files with `ls -l`, and move into another folder and back with `cd`. Then create a folder named `practice` with `mkdir`. | افتح الطرفية، واعرف مكانك بالأمر `pwd`، واعرض الملفات بالأمر `ls -l`، وانتقل إلى مجلد آخر وارجع بالأمر `cd`. ثم أنشئ مجلداً باسم `practice` بالأمر `mkdir`. |

| Lab 2: Files and Permissions | التمرين الثاني: الملفات والصلاحيات |
| :--- | ---: |
| Inside `practice`, create a file with `touch notes.txt`, then write text into it with `nano`. Run `ls -l` and read the permissions. Then use `chmod 600 notes.txt` and see what changed. | داخل `practice` أنشئ ملفاً بالأمر `touch notes.txt` ثم اكتب فيه نصاً بواسطة `nano`. نفّذ `ls -l` واقرأ الصلاحيات. بعدها استخدم `chmod 600 notes.txt` ولاحظ ما تغيّر. |

| Lab 3: Processes and Logs | التمرين الثالث: العمليات والسجلات |
| :--- | ---: |
| Run `top` to see running processes (press `q` to exit). Check disk space with `df -h` and memory with `free -h`. Then read the last 20 lines of a log file with `tail -n 20`. | شغّل `top` لرؤية العمليات الجارية (اضغط `q` للخروج). افحص مساحة القرص بالأمر `df -h` والذاكرة بالأمر `free -h`. ثم اقرأ آخر 20 سطراً من ملف سجل بالأمر `tail -n 20`. |

| Lab 4: Your First Bash Script | التمرين الرابع: أول سكربت باش |
| :--- | ---: |
| Create a file named `hello.sh` containing `#!/bin/bash` on the first line and `echo "Hello from Linux"` on the second. Make it executable with `chmod +x hello.sh` and run it with `./hello.sh`. | أنشئ ملفاً باسم `hello.sh` يحتوي في السطر الأول على `#!/bin/bash` وفي الثاني على `echo "Hello from Linux"`. اجعله قابلاً للتنفيذ بالأمر `chmod +x hello.sh` ثم شغّله بالأمر `./hello.sh`. |

| Lab 5: Connect to an AWS Server | التمرين الخامس: الاتصال بخادم على AWS |
| :--- | ---: |
| Launch a small Amazon Linux EC2 instance and download its key pair file (`.pem`). Protect the key with `chmod 400 my-key.pem`, then connect with `ssh -i my-key.pem ec2-user@YOUR_SERVER_IP`. Practice a few commands, then **terminate the instance**. | أنشئ خادم أمازون لينكس صغيراً على EC2 ونزّل ملف المفتاح (`.pem`). احمِ المفتاح بالأمر `chmod 400 my-key.pem` ثم اتصل بالأمر `ssh -i my-key.pem ec2-user@YOUR_SERVER_IP`. جرّب بعض الأوامر ثم **احذف الخادم**. |

> **Security Warning**
> Never upload your `.pem` key file to GitHub or share it with anyone. This repository is public, so anything committed to it can be seen by everyone.

# Mini Project: Server Health Report

| About the Project | عن المشروع |
| :--- | ---: |
| Write a Bash script that prints a short health report of a server: the date, the hostname, how long it has been running, disk usage, memory usage, and the 5 processes using the most memory. Run it on your own Linux and, if possible, on your EC2 server. Then upload the script to your own GitHub repository. This connects Linux, AWS, and Git in one small project. | اكتب سكربت باش يطبع تقريراً مختصراً عن حالة الخادم: التاريخ، واسم الجهاز، ومدة التشغيل، واستخدام القرص، واستخدام الذاكرة، وأكثر 5 عمليات استهلاكاً للذاكرة. شغّله على لينكس عندك، وعلى خادم EC2 إن أمكن. ثم ارفع السكربت إلى مستودع GitHub الخاص بك. هذا المشروع يربط لينكس وAWS وGit في عمل صغير واحد. |

A starting point (try to write it yourself first, then compare):

```bash
#!/bin/bash
echo "Server Health Report"
echo "Date: $(date)"
echo "Hostname: $(hostname)"
echo "Uptime: $(uptime -p)"
echo "--- Disk Usage ---"
df -h /
echo "--- Memory ---"
free -h
echo "--- Top 5 processes by memory ---"
ps aux --sort=-%mem | head -n 6
```

Run it with `chmod +x server-health.sh` and then `./server-health.sh > report.txt`.

**Bonus ideas:** make the script accept a folder name and report its size, or schedule it to run every day using `cron`.

# 5- Test Yourself

| Question | السؤال |
| :--- | ---: |
| 1- What does `pwd` do? | 1- ماذا يفعل الأمر `pwd`؟ |
| 2- What is the difference between `>` and `>>`? | 2- ما الفرق بين `>` و `>>`؟ |
| 3- What does `chmod 755 script.sh` mean? | 3- ماذا يعني `chmod 755 script.sh`؟ |
| 4- What does the pipe symbol do? | 4- ماذا يفعل رمز الأنبوب؟ |
| 5- What does `sudo` do, and why should you be careful with it? | 5- ماذا يفعل `sudo` ولماذا يجب الحذر منه؟ |
| 6- How do you follow a log file live as new lines arrive? | 6- كيف تتابع ملف سجل مباشرة أثناء ورود أسطر جديدة؟ |
| 7- Which command shows free disk space in a readable format? | 7- أي أمر يعرض المساحة الفارغة في القرص بصيغة مقروءة؟ |
| 8- What does `grep "error" app.log` do? | 8- ماذا يفعل الأمر `grep "error" app.log`؟ |
| 9- Which username do you use to connect to an Amazon Linux EC2 server? | 9- ما اسم المستخدم للاتصال بخادم أمازون لينكس على EC2؟ |
| 10- Why must you never upload a `.pem` key to a public GitHub repo? | 10- لماذا يجب ألا ترفع ملف مفتاح `.pem` إلى مستودع GitHub عام؟ |

<details>
<summary><b>Show the answers | إظهار الإجابات</b></summary>

| Answer | الإجابة |
| :--- | ---: |
| 1- It prints the folder you are currently in. | 1- يطبع المجلد الذي تعمل فيه حالياً. |
| 2- `>` overwrites the file with the output, while `>>` adds the output to the end of the file. | 2- الرمز `>` يستبدل محتوى الملف بالناتج، بينما `>>` يضيف الناتج في نهاية الملف. |
| 3- The owner can read, write, and run the file. The group and everyone else can read and run it, but not edit it. | 3- المالك يستطيع القراءة والكتابة والتشغيل. المجموعة وبقية المستخدمين يستطيعون القراءة والتشغيل فقط دون التعديل. |
| 4- It sends the output of one command as the input of the next command. | 4- يمرر ناتج أمر ليكون مدخلاً للأمر الذي بعده. |
| 5- It runs a command with administrator (root) privileges. Be careful because a wrong command can damage the system. | 5- ينفذ الأمر بصلاحيات المدير (root). يجب الحذر لأن أمراً خاطئاً قد يضر بالنظام. |
| 6- Use `tail -f` followed by the file name. | 6- استخدم `tail -f` متبوعاً باسم الملف. |
| 7- `df -h` | 7- الأمر `df -h` |
| 8- It prints the lines of `app.log` that contain the word "error". | 8- يطبع أسطر الملف `app.log` التي تحتوي على كلمة "error". |
| 9- `ec2-user` (Ubuntu servers use `ubuntu`). | 9- `ec2-user` (خوادم أوبونتو تستخدم `ubuntu`). |
| 10- Anyone who gets the key can access your server, which can lead to misuse and unexpected AWS costs. | 10- أي شخص يحصل على المفتاح يستطيع الدخول إلى خادمك، مما قد يؤدي إلى إساءة استخدامه وتكاليف غير متوقعة على AWS. |

</details>

# 6- To Go Deeper

| OverTheWire: Bandit | أوفر ذا واير: باندت |
| :--- | ---: |
| Bandit is a free game for beginners where you learn Linux commands by solving levels. Each level asks you to find a password using the terminal, so you practice real commands instead of just reading about them. | باندت لعبة مجانية للمبتدئين تتعلم فيها أوامر لينكس بحل المراحل. كل مرحلة تطلب منك إيجاد كلمة مرور عبر الطرفية، فتتدرب على أوامر حقيقية بدلاً من القراءة فقط. |

<div align="center">

# [OverTheWire: Bandit](https://overthewire.org/wargames/bandit/)

</div>

| Linux Journey | رحلة لينكس |
| :--- | ---: |
| A free website with short, simple lessons that start from zero and build step by step. A good companion to LFS101 when a topic needs a simpler explanation. | موقع مجاني بدروس قصيرة ومبسطة تبدأ من الصفر وتتدرج خطوة بخطوة. رفيق جيد لكورس LFS101 عندما يحتاج موضوع ما إلى شرح أبسط. |

<div align="center">

# [Linux Journey](https://linuxjourney.com/)

</div>

# 7- Additional

| The Linux Command Line | About |
| :--- | :--- |
| **Author:** William Shotts | A free book that teaches the Linux command line from the basics up to writing shell scripts. It is available to read or download for free from the author's website (linuxcommand.org). |

| Certification Overview | Linux Certifications |
| :--- | :--- |
| Linux certifications are optional and not required for this track. Two well-known options are the Linux Foundation Certified System Administrator (LFCS) and CompTIA Linux+. Both are paid exams, so check the current price and exam version on the official websites before planning. | They are useful for members who want to focus on Linux system administration after finishing the track. |

| What Comes Next | الخطوة التالية |
| :--- | ---: |
| After Linux, continue with the Solutions Architect Associate preparation. If you want extra skills, see the `extras` folder (Docker, CI/CD, monitoring). | بعد لينكس، تابع التحضير لشهادة Solutions Architect Associate. وإن أردت مهارات إضافية فراجع مجلد `extras` (دوكر، التكامل والنشر المستمر، المراقبة). |

# 8- Still Needed

- A good free Arabic resource for learning Linux
- Direct links for the two video suggestions above (currently YouTube search links)
- Feedback from the first members who try the labs, to improve the time estimates
