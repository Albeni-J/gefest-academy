# gefest-academy
1. Вывести все простые числа от a до b. a b - любые ваши числа. Главное чтобы a не превышало b.
```
<!DOCTYPE html>
<html>
<body>
<script>

//Вывести все простые числа от a до b. a b - любые ваши числа. Главное чтобы a не превышало b.

let a = Number(prompt())
let b = Number(prompt())

for(let i = a; i < b; i++) {
  if(checkIsNotPrime(i)) { 
    continue;
  }
  console.log(i)
}
function checkIsNotPrime(number) {
  for(let i = 2; i < number; i++)
  {
    if(!(number % i)){
      return 1;
    }
  }
}
</script>

<h1>My First Heading</h1>
<p>My first paragraph.</p>

</body>
</html>
```
3. Дана строка S.
Нужно посчитать количество слов в строке. 

К примеру в строк "Hello my name is Assan"  5 cлов
Нужно будет вывести число 5.

```
<!DOCTYPE html>
<html>
<body>
<script>

//Дана строка S.
//Нужно посчитать количество слов в строке. 

//К примеру в строк "Hello my name is Assan"  5 cлов
//Нужно будет вывести число 5.
let s = 'Hello my name is Lena '
let a = s.split(" ")
console.log(a)
console.log(a.length)


</script>

<h1>My First Heading</h1>
<p>My first paragraph.</p>

</body>
</html>

```
