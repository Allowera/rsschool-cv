# Elvira Karyakina

## Contact information:

* __Phone:__ +7 904 5379675
* __E-mail:__ ya.neznayu456@mail.ru
* __GitHub:__ @Allowera

## About Myself:

I have a strong desire to learn and acquire new skills. Diligent in performing the tasks in the best possible way and on time. Hardworking and sociable enough to work in a team.

## Skills

* HTML/CSS
* JavaScript (Basic)
* Git/GitHub

## Code example:

__KATA "Array.diff" from CODEWARS:__

```
function arrayDiff(a, b){
    for(var i = 0; i < a.length; i++){
        for(var j = 0; j < b.length; j++){
            if(a[i] === b[j]){
                a.splice(i, 1);
                i = i - 1;
            };
        };
    };
    return a;
};
let result = arrayDiff([1,3,5,5,8,5], [1,5,3]);
console.log(result);
```
