# gefest-academy
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
