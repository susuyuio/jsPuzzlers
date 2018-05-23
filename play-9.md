# Q:
    function showCase(value) {
        switch(value) {
        case 'A':
            console.log('Case A');
            break;
        case 'B':
            console.log('Case B');
            break;
        case undefined:
            console.log('undefined');
            break;
        default:
            console.log('Do not know!');
        }
    }
    showCase(new String('A'));
    showCase(String('A'));
# A:
    Do not know!
    'Case A'
# P:
    var sA1 = new String('A');
    var sA2 = 'A';
    var sA3 = String('A');
    sA1 === sA2;    // false
    sA1 == sA2; // true
    typeof sA1; // 'object'
    typeof sA2; // 'string'
    typeof sA3; // 'string'