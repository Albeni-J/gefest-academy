# gefest-academy
`<!DOCTYPE html>
<html>
<body>
<script>

//Вывести все простые числа от a до b. a b - любые ваши числа. Главное чтобы a не превышало b.

let a = Number(prompt())
let b = Number(prompt())

for(let i = a; i < b; i++) {
  if(checkIsPrime(i)) { 
    continue;
  }
  console.log(i)
}
function checkIsPrime(numbe) {
  for(let i = 2; i < numbe; i++)
  {
    if(!(numbe % i)){
      return 1;
    }
  }
}
</script>

<h1>My First Heading</h1>
<p>My first paragraph.</p>

</body>
</html>
`
