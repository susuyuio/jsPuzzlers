# Q:
    var a = {}, b = Object.prototype;
    [a.prototype === b, Object.getPrototypeOf(a) === b]

    function f() {}
    var a = f.prototype, b = Object.getPrototypeOf(f);
    a === b
# A:
    false, true

    false
# P:
    Functions have a prototype property but other objects don't so a.prototype is undefined. 
    Every Object instead has an internal property accessible via Object.getPrototypeOf

    f.prototype is the object that will become the parent of any objects created with new f while Object.getPrototypeOf returns the parent in the inheritance hierarchy.