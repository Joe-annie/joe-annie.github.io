###  Oxford - James Morrill -physionet_sepsis_challenge_2019

path: /home/yfdai/health-timeseries/physionet_sepsis_challenge_2019-master

Project based on the [cookiecutter data science project template](https://drivendata.github.io/cookiecutter-data-science/). #cookiecutterdatascience http://drivendata.github.io/cookiecutter-data-science/

- sakefile http://tonyfischetti.github.io/sake/sake-doc.html#Using-Sake (installed on local)
- Sake expects certain things of the directory you run it from. Without any options, it looks for files called "`Sakefile`", "`Sakefile.yaml`", "`Sakefile.yml`" (in that order) and uses the first one it finds.









### youqiang‘s OCR code：

配node的opencv环境（option）

写一个code review



### 一些pandas和numpy的toolkit和可复用操作

wu's code(ISI competition ,todo: clean and archive )

ds course code：Courses/Stats202

pandas ： Time series / date functionality https://pandas.pydata.org/pandas-docs/stable/user_guide/timeseries.html

- aggregate time 



### python coding style guide

- How are arguments passed by value or by reference in Python?

  - Python uses a mechanism, which is known as "**Call-by-Object**", sometimes also called "**Call by Object Reference**" or "**Call by Sharing**"

    If you pass immutable arguments like integers, strings or tuples to a function, the passing acts like **C****all-by-value**. It's different, if we pass mutable arguments.

    All **parameters (arguments**) in the Python language are **passed by reference**. It means if you change what a parameter refers to within a function(or assign to another variable) , the change also reflects back in the calling function/original variable .However when you reassign the arguments in function it will not reflects back: agentDB/experiments.ipynb

    

- why use **yield generator** and yield from http://simeonvisser.com/posts/python-3-using-yield-from-in-generators-part-1.html

- the generator **cannot**  return the second time !!

  > ​    rddpairs = {k:v for k,v in frequent_itemsets_forpath(db, min_support=100)}
  >
  > ​    \# rddpairs = {k:v for k,v in frequent_itemsets_forpath(db, min_support=100) if v < maxsupp}

### Command line

https://www.booleanworld.com/kill-process-linux/

top, ps aux/ ux , ps -ef 

**`-f`** 

displays information as if the user specified

> ```
> -o ruser=UID -o pid,ppid,pcpu=C -o stime,tty=TTY -o atime,args
> ```

> rm -rf $(find . | grep alldf.csv)

###  **PostgreSQL **

https://www.codementor.io/engineerapart/getting-started-with-postgresql-on-mac-osx-are8jcopb

https://postgresapp.com/ already installed 



### MongoDB

为什么每次下数据需要的时间不同？

>b'2019-12-06 10:01:20.249735 > '
>b'2019-12-06 10:01:22.487105 > '
>b'2019-12-06 10:01:22.527094 > '
>b'2019-12-06 10:01:22.576408 > '
>b'2019-12-06 10:01:22.600810 > '
>runtime: 2.4689157009124756s / maybe 40s

定时脚本

> crontab -e



### Github

has upload repo: myrecords (mac)

agentDB, FindRules-onedf ( on server)

created .gitignore 

command refer:  https://help.github.com/en/github/importing-your-projects-to-github/adding-an-existing-project-to-github-using-the-command-line



### 资源监测

> 推荐一组流程自动化+监视的工具：jenkins，prometheus，grafana。
>
> 对于有大量需要定时运行的程序，用crontab既不安全，不稳定，也不优雅。
>
> 以前用airflow做job scheduling，airflow基于python、有UI、稳定可靠，用着还不错。但公司server缺少它的dependency，没有sudo权限下不能用。于是发现了新的一组工具比airflow功能强大、易用，更重要的是，self-contained。
>
> Jenkins是个开源的 automation server可以用来定时自动 build/test/deliver各种程序。和airflow相同功能，但比airflow使用更方便，语法更简洁。
>
> Prometheus是一个开源的用于系统监控的数据库工具，最初由SoundCloud搭建。我用Prometheus 来爬jenkins产生的各种metrics
>
> Grafana是一个开源数据库可视化软件。
>
> 把这三者串联在一起，就可以实现在在grafana上监控/预警各个程序自动运行的情况、跟踪资源使用。 



### BLOG pages

https://joe-annie.github.io/

tutor:

https://www.fast.ai/2020/01/20/nb2md/