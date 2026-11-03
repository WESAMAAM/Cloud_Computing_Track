## Table of Contents

* [1- Definition and Introduction](#1--definition-and-introduction)
 * [For a Better Understanding](#for-a-better-understanding)
* [2- Now, Let's Dig in](#2--now-lets-dig-in)
 * [To Go Deeper](#to-go-deeper)
* [3- Additional](#3--additional)

---

# 1- Definition and Introduction

| **What is Linux?** | **ما هو لينكس؟** |
| :--- | ---: |
| Linux is a free and open-source operating system family built around the Linux kernel, created by Linus Torvalds in 1991. It comes in versions called "distributions", such as Ubuntu, Debian, and Amazon Linux. It is widely used on servers, and in cloud computing you will mostly work with it through the command line (terminal) rather than a graphical interface. | لينكس عائلة من أنظمة التشغيل المجانية ومفتوحة المصدر، مبنية حول نواة لينكس التي أنشأها لينوس تورفالدز عام 1991. تأتي بإصدارات تسمى "التوزيعات" مثل أوبونتو، ودبيان، وأمازون لينكس. تُستخدم على نطاق واسع في الخوادم، وفي الحوسبة السحابية ستتعامل معها غالباً عبر سطر الأوامر بدلاً من الواجهة الرسومية. |
| **Key Features of Linux:** | **:الميزات الرئيسية للينكس** |
| **1- Free and Open Source:** Anyone can use, study, and modify Linux, which is why it has a huge community and thousands of free tools. | 1- مجاني ومفتوح المصدر: يمكن لأي شخص استخدام لينكس ودراسته وتعديله، ولهذا لديه مجتمع ضخم وآلاف الأدوات المجانية. |
| **2- Command Line (Terminal):** You control the system by typing commands. It is faster and more powerful than clicking, and it is how you manage cloud servers. | 2- سطر الأوامر: تتحكم بالنظام عبر كتابة الأوامر، وهذا أسرع وأقوى من الضغط على الأزرار، وهو الطريقة التي تُدار بها الخوادم السحابية. |
| **3- Common on Servers and the Cloud:** AWS offers its own distribution, Amazon Linux, as an option for its EC2 servers, and many other Linux distributions are available too. | 3- منتشر في الخوادم والسحابة: تقدم أمازون توزيعتها الخاصة (أمازون لينكس) كخيار لخوادم الحوسبة المرنة، كما تتوفر توزيعات لينكس أخرى كثيرة. |
| **4- Permissions and Security:** Every file has an owner and permission settings that control who can read, edit, or run it. | 4- الصلاحيات والأمان: لكل ملف مالك وإعدادات صلاحيات تحدد من يستطيع قراءته أو تعديله أو تشغيله. |
| **5- Automation:** Repetitive tasks can be written once as a script (Bash) and run automatically. | 5- الأتمتة: يمكن كتابة المهام المتكررة مرة واحدة على شكل سكربت (باش) وتشغيلها تلقائياً. |

# For a Better Understanding

| To Make It Clear | حتى تتضح الصورة |
| :--- | ---: |
| Imagine managing a huge building. A graphical interface is like a panel of colored buttons: easy, but limited to what the buttons offer. The command line is like speaking directly to the building manager with precise written orders. You can ask for anything, and repeat the same order a thousand times with one line. That is why cloud engineers use it. | تخيل أنك تدير مبنى ضخماً. الواجهة الرسومية تشبه لوحة أزرار ملونة: سهلة لكنها محدودة بما تقدمه الأزرار. أما سطر الأوامر فيشبه أن تتحدث مباشرة مع مدير المبنى بأوامر مكتوبة ودقيقة. تستطيع أن تطلب أي شيء، وتكرر نفس الأمر ألف مرة بسطر واحد. ولهذا يعتمد عليه مهندسو السحابة. |

<!-- TODO: add 1-2 short intro videos here, same style as the Terraform page:
<div align="center">
<a href="VIDEO_LINK"><b>VIDEO TITLE</b></a>
</div>
-->

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

| Where to Practice | أين أتدرب؟ |
| :--- | ---: |
| **Option 1:** On Windows, install WSL (Windows Subsystem for Linux) to get a Linux terminal for free. | **الخيار الأول:** في ويندوز، ثبّت WSL (نظام ويندوز الفرعي للينكس) للحصول على طرفية لينكس مجاناً. |
| **Option 2:** Run Linux inside a virtual machine on your computer. | **الخيار الثاني:** شغّل لينكس داخل جهاز افتراضي على حاسبك. |
| **Option 3:** Create a small Linux server on AWS (EC2) and connect to it. | **الخيار الثالث:** أنشئ خادم لينكس صغيراً على AWS (خدمة EC2) واتصل به. |

> **Important Note**
> A server left running on AWS may incur costs. Check the current Free Tier terms on the AWS website, and always terminate (delete) your EC2 instance when you finish practicing.

# To Go Deeper

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

# 3- Additional

| The Linux Command Line | About |
| :--- | :--- |
| **Author:** William Shotts | A free book that teaches the Linux command line from the basics up to writing shell scripts. It is available to read or download for free from the author's website (linuxcommand.org). |

| Certification Overview | Linux Certifications |
| :--- | :--- |
| Linux certifications are optional and not required for this track. Two well-known options are the Linux Foundation Certified System Administrator (LFCS) and CompTIA Linux+. Both are paid exams, so check the current price and exam version on the official websites before planning. | They are useful for members who want to focus on Linux system administration after finishing the track. |
