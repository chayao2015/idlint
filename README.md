idlint
======

身份证校验小工具

## 说明
特殊说明该部分代码来自互联网基础上修改, 如果不小心侵犯版权,还请联系我删除

## 编译

    sh build.sh

## 输入
身份证号码
## 输出
$success $gender
$success = 0  表示是符合规范的身份证
$gender  {0:女 1:男}

## 例子

    ./idlint <身份证号>
    
