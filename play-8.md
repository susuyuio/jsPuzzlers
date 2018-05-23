# Q:
    var two   = 0.2
    var one   = 0.1
    var eight = 0.8
    var six   = 0.6
    [two - one == one, eight - six == two]
# A:
    [true, false]
# P:
    IEEE 754标准中的浮点数并不能精确地表达小数
    ？待确定哪里不精准？