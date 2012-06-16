# recruitpush

        It is a recruitment information push system.

         Author: justzx2011@gmail.com  @justzx
        

#Dependencies:
          python-beautifulsoup  python-requests python-lxml
        
#Installation
        1 Download programme
         git clone https://github.com/justzx2011/recruitpush.git
        2 Install python-beautifulsoup
          # pacman -S python-beautifulsoup
        3 Install python-requests python-lxml
         # yourt -S python-requests python-lxml
        4 running programme
          # python2.7 recruitment.py
        5 config your http server and setting DocumentRoot at /srv/http/recruitment
        6 open the url http://localhost/recruitment/index.html
TODO
--------------
        2012-6-16   -------   完善README.md
DONE
-----  
        2012-6-16   -------   设计了网页的样式
        2012-6-15   -------   完成招聘信息的准确抓取
UPDATES
--------------
        2012-6-16   -------   将项目命名为recruitpush，并放置到github上
        2012-6-15   -------   完善了界面设计
RULES
----
        1 桌面版程序，界面上永远不许有按钮
        2 主程序中既是测试程序，不许有功能模块
        3 所有功能模块保持最大化的独立，尤其是界面和程序不许纠缠


Path & File
----
<p>
├── cache
│   └── construction
│       ├── bodyend.html
│       └── head.html
├── README.md
├── recruitment.py
└── style.css
</p>

Construction
----
