# Q: 
    ['1', '2', '3'].map(parseInt)

# A: 
    ['1','2','3'].map(parseInt);
    // [1, NaN, NaN]

    ['1','2', '3'].map(function(elem){return parseInt(elem);})
    //[1, 2, 3]

# P:
- map(function(element, index, array))
- parseInt(str, radix)  // radix - 基数
    > 如果省略该参数或其值为 0，则数字将以 10 为基础来解析。
    ```
        parseInt('1', 0);
        parseInt('2', 1);
        parseInt('3', 2);
    ```