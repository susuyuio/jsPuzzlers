# Q:
    function sidEffecting(ary) {
        ary[0] = ary[2];
    }
    function bar(a,b,c) {
        c = 10
        sidEffecting(arguments);
        return a + b + c;
    }
    bar(1,1,1)
# A:
    21
# P:
    arguments is object,arguments[2] is c
    but,
    any rest parameters, any default parameters or any destructured parameters, arguments is not mapped arguments object ...

    function sidEffecting(ary) {
        ary[0] = ary[2];
    }
    function bar(a,b,c=3) {
        c = 10
        sidEffecting(arguments);
        return a + b + c;
    }
    bar(1,1,1)
    // 12