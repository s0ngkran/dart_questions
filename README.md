## Dart

### Question1
```dart
main(){
  String name = "John";
  int age = 25;
  double height = 175;
  // print this message -> "ฉันชื่อ [name] ฉันอายุ [age] ปี และฉันสูง [height] เมตร")

  // code here
}
```

### Question2
```dart
main(){
  // ตรวจสอบว่าตัวเลขเป็นบวก ลบ หรือศูนย์ 
  // โดยตัวเลขจะถูกเก็บไว้ในตัวแปรชื่อ number 
  //
  // ถ้าตัวเลขเป็นบวก พิมพ์ว่า "ตัวเลขเป็นบวก"
  // ถ้าตัวเลขเป็นลบ พิมพ์ว่า "ตัวเลขเป็นลบ"
  // ถ้าตัวเลขเป็นศูนย์ พิมพ์ว่า "ตัวเลขเป็นศูนย์"
  int number = 10;

  // code here
}
```

### Question3
```dart
main() {
  // ตรวจสอบเกรดของนักเรียนตามคะแนน 
  // โดยคะแนนจะถูกเก็บไว้ในตัวแปรชื่อ score ใช้เกณฑ์ต่อไปนี้ในการพิมพ์เกรด:

  // ถ้าคะแนน 90 ขึ้นไป พิมพ์ว่า "เกรด: A"
  // ถ้าคะแนนอยู่ระหว่าง 80 ถึง 89 พิมพ์ว่า "เกรด: B"
  // ถ้าคะแนนอยู่ระหว่าง 70 ถึง 79 พิมพ์ว่า "เกรด: C"
  // ถ้าคะแนนอยู่ระหว่าง 60 ถึง 69 พิมพ์ว่า "เกรด: D"
  // ถ้าคะแนนต่ำกว่า 60 พิมพ์ว่า "เกรด: F"

  int score = 80;
  // code here

}
```

### Question4
```dart
main() {
  // เขียนโปรแกรมที่รับค่าวันที่เป็น int จาก 1 ถึง 7 
  // ถ้าค่าเป็น 1 พิมพ์ว่า "วันจันทร์"
  // ถ้าค่าเป็น 2 พิมพ์ว่า "วันอังคาร"
  // ถ้าค่าเป็น 3 พิมพ์ว่า "วันพุธ"
  // ถ้าค่าเป็น 4 พิมพ์ว่า "วันพฤหัสบดี"
  // ถ้าค่าเป็น 5 พิมพ์ว่า "วันศุกร์"
  // ถ้าค่าเป็น 6 พิมพ์ว่า "วันเสาร์"
  // ถ้าค่าเป็น 7 พิมพ์ว่า "วันอาทิตย์"
  int day = 3;

  // code here
}
```

### Question5
```dart
main() {
  // เขียนโปรแกรมที่รับค่าความยาวและความกว้างของสี่เหลี่ยมจากผู้ใช้
  // จากนั้นคำนวณและพิมพ์ค่าพื้นที่ของสี่เหลี่ยม
  double length = 10.0;
  double width = 5.0;

  // code here
}
```

### Question6
```dart
main() {
  // สร้างฟังก์ชันที่รับค่า int n 
  // จากนั้นพิมพ์ตัวเลขตั้งแต่ 1 ถึง n
  int n = 5;

  // code here
}
```

### Question7
```dart
main() {
  // เขียนโปรแกรมที่รับค่าตัวเลขจากผู้ใช้ 
  // จากนั้นตรวจสอบว่าตัวเลขนั้นเป็นเลขคู่หรือเลขคี่ 
  // ถ้าเป็นเลขคู่ให้พิมพ์ว่า "เลขคู่"
  // ถ้าเป็นเลขคี่ให้พิมพ์ว่า "เลขคี่"
  int number = 7;

  // code here
}
```

### Question8
```dart
main() {
  // เขียนโปรแกรมที่รับค่ารัศมีของวงกลม 
  // จากนั้นคำนวณและพิมพ์ค่าพื้นที่ของวงกลม
  double radius = 7.5;

  // code here
}
```

### Question9
```dart
main() {
  // เขียนโปรแกรมที่รับค่าน้ำหนักของผู้ใช้ในกิโลกรัม 
  // และส่วนสูงในเซนติเมตร 
  // จากนั้นคำนวณและพิมพ์ค่าดัชนีมวลกาย (BMI)
  double weight = 70.0;
  double height = 175.0;

  // code here
}
```

### Question10
```dart
main() {
  // เขียนโปรแกรมที่รับค่าจำนวนเต็มสองจำนวน
  // จากนั้นเปรียบเทียบและพิมพ์ค่าที่มากกว่า
  int a = 10;
  int b = 20;

  // code here
}
```

### Question11
```dart
// special question
// learn from this url https://dart.dev/language/loops
main() {
  // สร้างฟังก์ชันที่รับค่า int n
  // จากนั้นคืนค่าผลรวมของตัวเลขตั้งแต่ 1 ถึง n
  int n = 10;

  // code here
}
```

### Question12
```dart
main() {
  // เขียนโปรแกรมที่พิมพ์ตัวเลขตั้งแต่ 1 ถึง 10 โดยใช้ลูป for
  // code here
}
```

### Question13
```dart
main() {
  // เขียนโปรแกรมที่พิมพ์ตัวเลขตั้งแต่ 10 ถึง 1 โดยใช้ลูป while
  // code here
}
```

### Question14
```dart
main() {
  // เขียนโปรแกรมที่พิมพ์เลขคู่ระหว่าง 1 ถึง 20 โดยใช้ลูป for
  // code here
}
```

### Question15
```dart
main() {
  // เขียนโปรแกรมที่หาผลรวมของตัวเลขตั้งแต่ 1 ถึง 100 โดยใช้ลูป while
  // code here
}
```

### Question16
```dart
main() {
  // เขียนโปรแกรมที่พิมพ์ตัวเลขในอาร์เรย์ โดยใช้ลูป for
  List<int> numbers = [1, 2, 3, 4, 5];
  // hint: use numbers.length and numbers[index] to access each element

  // code here
}
```

### Question17
```dart
main() {
  // เขียนโปรแกรมที่พิมพ์ตารางสูตรคูณของ 2 โดยใช้ลูป for
  // ex. 
  // 2 x 1 = 2
  // 2 x 2 = 4
  // ...

  // code here
}
```

### Question18
```dart
main() {
  // เขียนโปรแกรมที่ใช้ลูป while เพื่อพิมพ์ตัวอักษรแต่ละตัวในสตริง
  String text = "Dart";
  // hint: use text.length and text[index] to access each character
  // ex.
  // D
  // a
  // r
  // t

  // code here
}
```

### Question19
```dart
main() {
  // เขียนโปรแกรมที่หาผลคูณของตัวเลขตั้งแต่ 1 ถึง n โดยใช้ลูป for
  int n = 5;
  // hint: create variable to store result

  // code here
}
```

### Question20
```dart
main() {
  // เขียนโปรแกรมที่ใช้ลูป for เพื่อพิมพ์เลขยกกำลังสองตั้งแต่ 1 ถึง 10

  // code here
}
```

### Question21
```dart
main() {
  // เขียนโปรแกรมที่พิมพ์ค่าเฉลี่ยของตัวเลขในลิสต์ โดยใช้ลูป for
  List<int> numbers = [10, 20, 30, 40, 50];
  // hint: create variable to store sum
  // hint: divide sum by numbers.length

  // code here
}
```

### Question22
```dart
void yourFunction(int n){
  // code here
}

main() {
  // สร้างฟังก์ชันที่รับค่า int n
  // จากนั้นพิมพ์ตัวเลขที่หารด้วย 3 ลงตัวตั้งแต่ 1 ถึง n โดยใช้ลูป for
  // ตัวอย่างเช่น ถ้า n = 10, ผลลัพธ์ควรเป็น: 3, 6, 9

  int n = 10;

  yourFunction(n)
}
```

### Question23
```dart
// void doSum(){
// write your function here
// }

main() {
  // สร้างฟังก์ชันที่รับค่า int n
  // จากนั้นพิมพ์ผลบวกของเลขคู่ตั้งแต่ 1 ถึง n โดยใช้ลูป for
  // ตัวอย่างเช่น ถ้า n = 10, ผลลัพธ์ควรเป็น: 2 + 4 + 6 + 8 + 10 = 30

  int n = 10;

  doSum(n)
}
```

### Question24
```dart
// create a function here

main() {
  // สร้างฟังก์ชันที่รับค่า int n
  // จากนั้นพิมพ์ตัวเลขที่เป็นคี่ตั้งแต่ 1 ถึง n โดยใช้ลูป while
  // ตัวอย่างเช่น ถ้า n = 10, ผลลัพธ์ควรเป็น: 1, 3, 5, 7, 9

  int n = 10;

  printEven(n)
}
```

### Question25
```dart
// code here

main() {
  // สร้างฟังก์ชันที่รับค่า int n
  // จากนั้นพิมพ์ตารางสูตรคูณของ n โดยใช้ลูป for
  // ตัวอย่างเช่น ถ้า n = 5, ผลลัพธ์ควรเป็น:
  // 5 x 1 = 5
  // 5 x 2 = 10
  // ...
  // 5 x 10 = 50

  int n = 5;

  printMultiTable(n)
}
```

### Question26
```dart
main() {
  // สร้างฟังก์ชันที่รับค่า int n
  // จากนั้นพิมพ์ผลรวมของเลขตั้งแต่ 1 ถึง n ที่หารด้วย 5 ลงตัว โดยใช้ลูป for
  // ตัวอย่างเช่น ถ้า n = 20, ผลลัพธ์ควรเป็น: 5 + 10 + 15 + 20 = 50

  int n = 20;

  // code here
}
```

### Question27
```dart
main() {
  // สร้างฟังก์ชันที่รับค่า int n
  // จากนั้นพิมพ์ตัวเลขตั้งแต่ 1 ถึง n ที่ไม่หารด้วย 4 ลงตัว โดยใช้ลูป for
  // hint: ใช้คำสั่ง continue เพื่อข้ามตัวเลขที่หารด้วย 4 ลงตัว

  int n = 10;

  // code here
}
```

### Question28
```dart
main() {
  // สร้างฟังก์ชันที่รับค่า int n
  // จากนั้นพิมพ์ตัวเลขตั้งแต่ 1 ถึง n จนกว่าจะพบตัวเลขที่หารด้วย 7 ลงตัว โดยใช้ลูป for
  // hint: ใช้คำสั่ง break เพื่อหยุดลูปเมื่อพบตัวเลขที่หารด้วย 7 ลงตัว

  int n = 20;

  // code here
}
```

### Question29
```dart
// สร้างฟังก์ชันที่รับค่า int n และค่า int step (ค่า step เป็นค่าเริ่มต้น 1)
// ฟังก์ชันจะพิมพ์ตัวเลขตั้งแต่ 1 ถึง n โดยเพิ่มค่า step ทีละขั้น
// ถ้าไม่ได้ระบุค่า step จะใช้ค่าเริ่มต้นเป็น 1

void printNumbers(int n, {int step = 1}) {
  // code here
}

void main() {
  printNumbers(10);    // ใช้ค่า step เป็น 1
  printNumbers(10, {step: 2}); // ใช้ค่า step เป็น 2
}
```

### Question30
```dart
// สร้างฟังก์ชันที่รับค่า int start, int end, และ int step (ค่า step เป็นค่าเริ่มต้น 1)
// ฟังก์ชันจะพิมพ์ตัวเลขตั้งแต่ start ถึง end โดยเพิ่มค่า step ทีละขั้น
// ใช้ named arguments สำหรับ start, end, และ step
// hint: {required int start, int step = 1}

void printRange(
// code here
// code here
// code here
) {
  // for (int i = start; i <= end; i += step) {
  //  print(i);
  // }
}

void main() {
  printRange(start: 1, end: 10);    // ใช้ค่า step เป็น 1
  printRange(start: 1, end: 10, step: 2); // ใช้ค่า step เป็น 2
}
```

### Question31
```dart
// สร้างฟังก์ชันที่รับค่า String name, int age, และ String country (ค่า country เป็นค่าเริ่มต้น "Unknown")
// ฟังก์ชันจะพิมพ์ข้อความที่ระบุชื่อ, อายุ และประเทศ
// ใช้ named arguments สำหรับ name, age, และ country

void printPersonInfo({
// missing argument?
required int age, String country = "Unknown"}) {
  print("Name: $name");
  // code here; print age and country
}

void main() {
  printPersonInfo(name: "Alice", age: 30); // ใช้ค่า default สำหรับ country
  printPersonInfo(name: "Bob", age: 25, country: "Thailand"); // ระบุค่า country
}
```

### Question32
```dart
// สร้างฟังก์ชันที่รับค่า int a และ int b
// ฟังก์ชันจะคืนค่าผลรวมของ a และ b
// จากนั้นในฟังก์ชัน main ให้พิมพ์ผลลัพธ์ที่ได้จากการเรียกใช้ฟังก์ชันนี้

int add(int a, int b) {
  // code here
}

void main() {
  int result = add(5, 7);
  print(result); // ควรพิมพ์ 12
}
```

### Question33
```dart
// สร้างฟังก์ชันที่รับค่า int n
// ฟังก์ชันจะคืนค่าผลคูณของตัวเลขตั้งแต่ 1 ถึง n
// จากนั้นในฟังก์ชัน main ให้พิมพ์ผลลัพธ์ที่ได้จากการเรียกใช้ฟังก์ชันนี้

int multiply(int n) {
  // code here
}

void main() {
  int result = multiply(5);
  print(result); // ควรพิมพ์ 120 (ผลคูณของ 1, 2, 3, 4, 5)
}
```

### Question34
```dart
// สร้างฟังก์ชันที่รับค่า int n
// ฟังก์ชันจะคืนค่าข้อความ "Even" ถ้า n เป็นเลขคู่ และ "Odd" ถ้า n เป็นเลขคี่
// จากนั้นในฟังก์ชัน main ให้พิมพ์ผลลัพธ์ที่ได้จากการเรียกใช้ฟังก์ชันนี้

String checkEvenOdd(int n) {
  // code here
}

void main() {
  String result = checkEvenOdd(4);
  print(result); // ควรพิมพ์ "Even"
  
  result = checkEvenOdd(7);
  print(result); // ควรพิมพ์ "Odd"
}
```

### Question35
```dart
// สร้างฟังก์ชันที่รับค่า int score
// ฟังก์ชันจะคืนค่าเกรดตามคะแนนที่ได้รับ โดยใช้เกณฑ์ต่อไปนี้:
// - คะแนน 90 ขึ้นไป: "A"
// - คะแนน 80 ถึง 89: "B"
// - คะแนน 70 ถึง 79: "C"
// - คะแนน 60 ถึง 69: "D"
// - คะแนนต่ำกว่า 60: "F"
// จากนั้นในฟังก์ชัน main ให้พิมพ์ผลลัพธ์ที่ได้จากการเรียกใช้ฟังก์ชันนี้

String determineGrade(int score) {
  // code here
}

void main() {
  String grade = determineGrade(85);
  print(grade); // ควรพิมพ์ "B"
  
  grade = determineGrade(55);
  print(grade); // ควรพิมพ์ "F"
}
```

### Question36
```dart
// สร้างฟังก์ชันที่รับค่า int n
// ฟังก์ชันจะคืนค่าผลลัพธ์ของการคูณตัวเลขตั้งแต่ 1 ถึง n (factorial)
// แต่ให้ทำงานกับค่าของ n ที่ไม่เกิน 5
// จากนั้นในฟังก์ชัน main ให้พิมพ์ผลลัพธ์ที่ได้จากการเรียกใช้ฟังก์ชันนี้

void main() {
  int result = factorial(3);
  print(result); // ควรพิมพ์ 6 (ผลคูณของ 1, 2, 3)
  
  result = factorial(4);
  print(result); // ควรพิมพ์ 24 (ผลคูณของ 1, 2, 3, 4)
}
```

### Question37
```dart
// สร้างฟังก์ชันที่รับค่า List<int> numbers
// ฟังก์ชันจะคืนค่าผลรวมของตัวเลขในลิสต์
// จากนั้นในฟังก์ชัน main ให้พิมพ์ผลลัพธ์ที่ได้จากการเรียกใช้ฟังก์ชันนี้

int sumList(List<int> numbers) {
  // code here
}

void main() {
  int result = sumList([1, 2, 3, 4, 5]);
  print(result); // ควรพิมพ์ 15 (ผลรวมของ 1, 2, 3, 4, 5)
}
```

### Question38
```dart
// สร้างฟังก์ชันที่รับค่า List<int> numbers
// ฟังก์ชันจะคืนค่าตัวเลขที่มากที่สุดในลิสต์
// จากนั้นในฟังก์ชัน main ให้พิมพ์ผลลัพธ์ที่ได้จากการเรียกใช้ฟังก์ชันนี้

int findMax(List<int> numbers) {
  // code here
}

void main() {
  int max = findMax([4, 7, 1, 9, 3]);
  print(max); // ควรพิมพ์ 9 (ตัวเลขที่มากที่สุดในลิสต์)
}
```

### Question39
```dart
// สร้างฟังก์ชันที่รับค่า List<int> numbers
// ฟังก์ชันจะคืนค่าลิสต์ใหม่ที่มีตัวเลขในลิสต์เดิมแต่เพิ่ม 1 ทุกตัว
// จากนั้นในฟังก์ชัน main ให้พิมพ์ผลลัพธ์ที่ได้จากการเรียกใช้ฟังก์ชันนี้

List<int> incrementList(List<int> numbers) {
  // code here
}

void main() {
  List<int> incremented = incrementList([1, 2, 3, 4]);
  print(incremented); // ควรพิมพ์ [2, 3, 4, 5] (เพิ่ม 1 ให้ทุกตัวเลขในลิสต์)
}
```

### Question40
```dart
// สร้างฟังก์ชันที่รับค่า List<int> numbers
// ฟังก์ชันจะคืนค่าลิสต์ใหม่ที่มีตัวเลขที่เป็นเลขคู่จากลิสต์เดิมเท่านั้น
// จากนั้นในฟังก์ชัน main ให้พิมพ์ผลลัพธ์ที่ได้จากการเรียกใช้ฟังก์ชันนี้

List<int> filterEven(List<int> numbers) {
  // code here
}

void main() {
  List<int> evens = filterEven([1, 2, 3, 4, 5, 6]);
  print(evens); // ควรพิมพ์ [2, 4, 6] (ตัวเลขคู่ในลิสต์)
}
```
