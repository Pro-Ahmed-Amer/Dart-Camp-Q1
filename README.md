# Dart-Camp-Q1

# <u>Assignment - 1</u>

Q \ Separate the **"Even" & "Odd"** numbers between **1 - 20** ? And print it in this way ? Using three ways (For & While & Do-While) !!!

**<u>Notes:</u>**

- Even number => number % 2 = 0

- Odd number => number % 2 = 1

1-) Method One :

```dart
main(){
  for(var i=1; i<=20; i++){
    if(i % 2 == 0){
      print("$i - Even");
    }else{
      print("$i - Odd");
    }
  }
}
```

****

2-) Method Two :

```dart
main() {
  var i = 1;
  while (i <= 20) {
    if (i % 2 == 0) {
      print("$i - Even");
    } else {
      print("$i - Odd");
    }
    i++;
  }
}
```

*****

3-) Method Three :

```dart
main() {
  var i = 1;
  do {
    if (i % 2 == 0) {
      print("$i - Even");
    } else {
      print("$i - Odd");
    }
    i++;
  } while (i <= 20);
}
```

****

Output :

```
1 - Odd
2 - Even
3 - Odd
4 - Even
5 - Odd
6 - Even
7 - Odd
8 - Even
9 - Odd
10 - Even
11 - Odd
12 - Even
13 - Odd
14 - Even
15 - Odd
16 - Even
17 - Odd
18 - Even
19 - Odd
20 - Even
```

