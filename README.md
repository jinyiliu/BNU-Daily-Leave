# BNU-Daily-Leave

## Contribute to This Project!!
*** For more convenience, please contribute your code! ***

## A Naive Idea in Implementation
- Simulate to log in to [the Confirmation Platform](http://cas.bnu.edu.cn/cas/login?service=https%3A%2F%2Fonehall.bnu.edu.cn%2Ftp_fp%2Findex.jsp)
- Then with the session, we can turn to the [leaving registration page](https://onehall.bnu.edu.cn/tp_fp/view?m=fp#from=hall&serveID=e87d2875-6fcf-4e6a-81bc-8ff99915aed3&act=fp/serveapply)
- Fill in with pre-set-up data, and schedule it as a daily task

## Problems
1. When doing `post` to [the Confirmation Platform](http://cas.bnu.edu.cn/cas/login?service=https%3A%2F%2Fonehall.bnu.edu.cn%2Ftp_fp%2Findex.jsp), an item in `Form Data` is generated in a special way, aka there is no obvious `usrname` or `pwd` item in it. 

