#JavaScript design patterns


##Modul
```javascript
var Mod = (function() {
		var b =20;
    var summ = function(a,b){
    	return (a+b)*b;
    }

    return {
      summ
    }

})();

console.log(Mod.summ(1,2)); //60
```

##Prototype design pattern
```javascript
var TeslaModelS = function() {
  this.numWheels    = 4;
  this.manufacturer = 'Tesla';
  this.make         = 'Model S';
}

TeslaModelS.prototype.go = function() {
  // Rotate wheels
}

TeslaModelS.prototype.stop = function() {
  // Apply brake pads
}
```
