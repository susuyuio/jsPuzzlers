# Q:
    var a = Date(0);
    var b = new Date(0);
    var c = new Date();
    [a === b, b === c, a === c]
# A:
    false, false, false
# P:
    a -- 当前时间 字符串
    b -- 初始时间 对象
    c -- 当前时间 对象