# -WDA-IOS-
脚本的用途： 将多语言的检查自动化，节省人工耗时。脚本的工作原理是：根据进入程序的各个界面去获取当前界面的所有文案内容，然后跟多语言Excel表进行对比匹配是否存在，存在则表示该界面的多语言已正确添加，否则表示未添加或添加多语言不正确。用户需要自行设计进入各个界面的用例，然后调用matchStr()或matchStrN()方法去匹配当前界面的多语言，设计用例所需的各种操作方法已经写好只需直接调用，详看runtest.py文件，在module.py文件里面也还有很多操作方法未写到runtest.py文件内，用户可以根据自身需要自行调用。
