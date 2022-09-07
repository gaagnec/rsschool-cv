# Andrey Stribuk

## Contact info:

- Address: Belarus, Minsk / Poland
- E-mail: gaagnec@gmail.com
- LinkedIn: www.linkedin.com/in/gaagnec
- GitHub: https://github.com/gaagnec

## Skills

- HTML
- CSS (Bootstrap, BEM)
- JavaScript (Basic)
- CMS Joomla, Wordpress, OpenCart
- Sublime Text3, VS Code
- Windows OS
- SEO

## Code examples

> Given a non-negative integer n, write a function to_binary/ToBinary which returns that number in a binary format.

```
function toBinary(n) {
  let result = '';
  let resultReverse = '';
  let p = n;
  for (i = 0; n >= 1; i++) {
    if (n % 2 === 0) {
      result = result + 0;
      n /= 2;
    } else {
      result = result + 1;
      n /= 2;
    }
    n = Math.floor(n);
  }
  for (i = result.length; i > 0; i--) {
    resultReverse = resultReverse.concat(result[i - 1]);
  }

  return Number(resultReverse);
}
```
