# Hi. I’m Yauheni Tsimashchuk, nice to meet you 👋

## Contacts:
[GitHub](https://github.com/EvvTim) |
[Linkedin](https://www.linkedin.com/in/yauheni-tsimashchuk/) |
[E-mail](mailto:evgeniytim94@gmail.com) |
[Facebook](https://www.facebook.com/evvtim) |
[Codepen](https://codepen.io/evvtim) |

## About me:

Recently, I was completely absorbed by the world of coding. I am interested in Front-End. I am currently looking for my first job or internship as a Junior Front-end Developer.

## Skills:
- JavaScript
- TypeScript  
- React
- React Native
- HTML
- Css
- Linux

## Code examples:
#### Validate my Password
.js
```js
function validPass(password){
    return /(?=.+[a-z])(?=.+\d)^[a-z\d]{3,20}$/i.test(password) ? 'VALID' : 'INVALID';
}

```
#### Friday the 13ths
.js
```js
function fridayTheThirteenths(start, end=start) {
    let arr=[];
    for (let i=start; i<=end; ++i)
        for (let x=1; x<13; ++x)
        {
            let d=new Date(i,x-1,13)
            if (d.getDay()==5)
                arr.push(x+'/'+13+'/'+i);
        }
    return arr.join(' ')
}

```
#### Find The Parity Outlier
.js
```js
function findOutlier(integers){
    let even = []
    let odd = []

    for (let i = 0; i < integers.length; i++) {
        if (integers[i] % 2 === 0) {
            even.push(integers[i])
        } else {
            odd.push(integers[i])
        }
    }

    if (even.length === 1) {
        return even[0]
    } else {
        return odd[0]
    }
}

```


![Anurag's github stats](https://github-readme-stats.vercel.app/api?username=EvvTim&show_icons=true&count_private=true)

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=EvvTim&layout=compact)](https://github.com/anuraghazra/github-readme-stats)

