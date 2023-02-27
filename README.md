# Bound-invocation-
 
var obj = { foo: 'bar' };
function foo() {
 return this.foo;
}
fooObj = foo.bind(obj);
fooObj();
