# Q:
    [typeof null, null instanceof Object]
# A:
    ['object', false]
# P:
    typeof 返回一个表示类型的字符串
    instanceof 运算符用来检测 constructor.prototype 是否存在于参数 object 的原型链上
    
<table>
    <tr>
        <td>type</td>
        <td>result</td>
    </tr>
    <tr>
        <td>Undefined</td>
        <td>'undefined'</td>
    </tr>
    <tr>
        <td>null</td>
        <td>'object'</td>
    </tr>
    <tr>
        <td>Boolean</td>
        <td>'boolean'</td>
    </tr>
    <tr>
        <td>String</td>
        <td>'string'</td>
    </tr>
    <tr>
        <td>Number</td>
        <td>'number'</td>
    </tr>
    <tr>
        <td>Symbol</td>
        <td>'symbol'</td>
    </tr>
    <tr>
        <td>Function</td>
        <td>'function'</td>
    </tr>
    <tr>
        <td>Object</td>
        <td>'object'</td>
    </tr>
</table>