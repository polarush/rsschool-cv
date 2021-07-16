# Eugeniy Polyarush

- **Samara, Russia8**
- **Phone number 1: +7(927)779-41-98**
- **Phone number 2: +7(927)723-35-44**
- **E-mail: polyarush.e@mail.ru**
- **GitHub: [https://github.com/polarush/](https://github.com/polarush/)**

> Hello! My name is Eugeniy Polyarush, and I am a self-educated programmer. 
> I work in web-design, system administration, system integration, SEO. 
> I have created sites by Wordpress, Opencart etc..., and work with programmers, 
> write technical specs for additional modules and new functional. 
> I code small integrating or parsing scripts, and also I do it just for fun.
> In the near future I want to become a front-end developer. 


# Technologies i use:

- JavaScript - Basic level
- Python - Flask, Beautiful soup, Selenium, Requests, Instapy, MySQL(python library)
- SQL - MySQL, PostgreSQL
- HTML - Bootstrap 3,4  
- CSS3 
- Linux BASH - base
- GIT basic
- IDE's - PyCharm, VSCode, NPP
- Graphical Software - Adobe Photoshop, Premiere Pro, After Effects, GIMP 

# My code:
## _Javascript:_
[Mumbling](https://www.codewars.com/kata/5667e8f4e3f572a8f2000039)
Solution:
```sh
function accum(s) {
  let temp = ''
  let n = 1;
  temp += s[0] 
  while (n !== s.length) {
    temp += `-${s[n].toLowerCase().repeat(n+1)}`
    n++
  }

  let arrTemp = temp.split('-')
  let result = ''
  arrTemp.forEach(function(item, i, arr) {
  result += `-${item.replace(item[0],item[0].toUpperCase())}`
  });

  return result.slice(1)
}
```

[Remove First and Last Character](https://www.codewars.com/kata/56bc28ad5bdaeb48760009b0)
Solution:
```sh
function removeChar(str){
  return str.slice(1, str.length-1)
};
```

[Reversed Strings](https://www.codewars.com/kata/5168bb5dfe9a00b126000018)
Solution:
```sh
function solution(str){
  let string = '';
  for (let n = str.length-1; n >= 0; n--) {
    string += str[n]
  }
  return string
}
```

[Remove exclamation marks](https://www.codewars.com/kata/57a0885cbb9944e24c00008e)
Solution:
```sh
function removeExclamationMarks(s) {
  let re = /!/gi;
  let newStr = s.replace(re, '');

  return newStr;
}
```

## _Python:_
[Permutations](https://www.codewars.com/kata/5254ca2719453dcc0b00027d)
Solution:
```sh
import itertools
def permutations(string):
    return set(["".join(x) for x in itertools.permutations(string)])
```
[Extract the domain name from a URL](https://www.codewars.com/kata/514a024011ea4fb54200004b)
Solution:
```sh
import re
def domain_name(parsed_uri):
    if re.findall('www.',parsed_uri,flags=0) == ['www.']:
        return parsed_uri.split('//')[-1].split('/')[0].split('.')[1]
    else:
        return parsed_uri.split('//')[-1].split('/')[0].split('.')[0]
```


[The Hashtag Generator](https://www.codewars.com/kata/52449b062fb80683ec000024)
Solution:
```sh
def generate_hashtag(s):
    a = s.title().replace(' ','')
    if len(a) > 140 or len(a) == 0:
        return False
    return '#'+a
```


[Human Readable Time](https://www.codewars.com/kata/52685f7382004e774f0001f7)
Solution:
```
def make_readable(seconds):
    secs = seconds % 60
    mins = seconds // 60
    mins_rem = mins % 60
    hrs = mins // 60
    
    return "{:02}:{:02}:{:02}".format(hrs, mins_rem, secs)
```



# Work experience (company, years, function):


> w3site.kz - (aug 2010 – sep 2012) - Account manager
> arbuz.kz - (sep 2012 – mar 2014) - Junior System Administrator, Junior Web-Designer, Web-Admin
> inprog.kz - (mar 2014 – jan 2015) - Web-Administrator, Web Designer, Web-Master
> contrast-polygraphy.kz - (jan 2015 – sep 2017) - System Administrator
> Freelance - (sep 2017 – may 2021) - Web-Master
> service-axus.ru - (jun 2021 – today) - Web-Master

# Education: 
- High school (Almaty), 
- MIPT online lectures,
- Youtube lectures about SQL, Python, HTML/CSS, algorithms and data structures (2019-2021)
- RS School 2021.


# English: A2
