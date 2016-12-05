
##Comparison ==

Type(x)	Type(y)	Result
x and y are the same type	See Strict Equality (===) Algorithm
null	Undefined	true
Undefined	null	true
Number	String	x == toNumber(y)
String	Number	toNumber(x) == y
Boolean	(any)	toNumber(x) == y
(any)	Boolean	x == toNumber(y)
String or Number	Object	x == toPrimitive(y)
Object	String or Number	toPrimitive(x) == y
otherwise…	false
