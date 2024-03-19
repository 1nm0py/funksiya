# funksiya

[1. Misol](https://edabit.com/challenge/9MjEpkL7yAjAqiH58)

```js
function lessThan100(a, b) {
	let c = a+b
	if (c <= 100){
		return true
	}else {
		return false
	}
}
```
[2. Misol](https://edabit.com/challenge/4iCsexZgmDEMMxj46)

```js
function printArray(number) {
    var newArray = [];
  
    for(var i = 1; i <= number; i++) {
      newArray.push(i);
    }
  
    return newArray;
  }
```
[3. Misol](https://edabit.com/challenge/CCGBig9eRPFzAHv46)

```js
function swap(a, b) {
	let c = a
	let j = b
	return [j, c]
}
```
[4. Misol](https://edabit.com/challenge/8Qg78sf5SNDEANKti)

```js
function animals(chickens, cows, pigs) {
	let animals = (chickens *2 + cows*4 + pigs*4)
	return animals
}
```
[5. Misol](https://edabit.com/challenge/vJCZmgvvDjehyDcDK)

```js
function and(a, b) {
	if (a==true && b ==true){
		return true
	}
	else {
		return false
	}
}
```
[6. Misol](https://edabit.com/challenge/QSnaSH5S3oxZkwcNc)

```js
function isSameNum(num1, num2) {
	if (num1 === num2){
		return true
	}else{
		return false
	}
}
```
[7. Misol](https://edabit.com/challenge/FipbQSYquQLPZ8QXG)

```js
function isSeven(x) {
	if (x == 7){
		return true
	}else{
		return false
	}
}
```
[8. Misol](https://edabit.com/challenge/BGvTMfwxYDRbtaTJ3)

```js
function checkEquality(a, b) {
    if (a===b){
          return true
      }
      else {
          return false
      }
  }
```
[9. Misol](https://edabit.com/challenge/ghbHrRnRiDz9fvQNF)

```js
function profitableGamble(prob, prize, pay) {
	let a = prob * prize-pay
	if (a > 0){
		return true
	}
	else {
		return false
	}
}
```