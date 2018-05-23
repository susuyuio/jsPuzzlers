# Q:
    var name = 'World!';
    (function () {
        if (typeof name === 'undefined') {
            var name = 'Jack';
            console.log('Goodbye ' + name);
        } else {
            console.log('Hello ' + name);
        }
    })();
# A:
    Goodbye Jack
# P:
    var name = 'World!';
    (function () {
        var name;
        if (typeof name === 'undefined') {
            name = 'Jack';
            console.log('Goodbye ' + name);
        } else {
            console.log('Hello ' + name);
        }
    })();