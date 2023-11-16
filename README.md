# MINI TEST FRONTEND DEVELOPER HWG


## CODE
```javascript
const looping = (x) => {
  for (let i = 1; i <= x; i++) {
    if (i % 3 == 0 && i % 5 == 0) {
      console.log("TigaLima");
    } else if (i % 3 == 0) {
      console.log("Tiga");
    } else if (i % 5 == 0) {
      console.log("Lima");
    } else {
      console.log(i);
    }
  }
};

looping(50);
```
## HASILNYA
```powershell
$ node Test-Hwg.js
1
2
Tiga
4
Lima
Tiga
7
8
Tiga
Lima
11
Tiga
13
14
TigaLima
16
17
Tiga
19
Lima
Tiga
22
23
Tiga
Lima
26
Tiga
28
29
TigaLima
31
32
Tiga
34
Lima
Tiga
37
38
Tiga
Lima
41
Tiga
43
44
TigaLima
46
47
Tiga
49
Lima
```