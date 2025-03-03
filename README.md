<!DOCTYPE html>
<html lant=uk>
<head>
</head>
<body>
 <script>
let intVar = 10;
let floatVar = 3.14;
let strVar = "Hello";
let boolVar = true;
console.log("Початкові значення та їх типи:");
console.log(numberVar, typeof numberVar);
console.log(floatVar, typeof floatVar);
console.log(stringVar, typeof stringVar);
console.log(boolVar, typeof boolVar);
numberVar = "42";
floatVar = false;
stringVar = 100 + "50";
boolVar = Number(boolVar);
console.log("\nПісля змін:");
console.log(numberVar, typeof numberVar);
console.log(floatVar, typeof floatVar);
console.log(stringVar, typeof stringVar);
console.log(boolVar, typeof boolVar);
let convertedNumber = Number("123");
let convertedString = String(456);
let convertedBoolean1 = Boolean(1);
let convertedBoolean2 = Boolean(0);
console.log("\nДодаткові перетворення:");
console.log(convertedNumber, typeof convertedNumber);
console.log(convertedString, typeof convertedString);
console.log(convertedBoolean1, typeof convertedBoolean1);
console.log(convertedBoolean2, typeof convertedBoolean2);
let myObject = {
    number: numberVar,
    float: floatVar,
    text: stringVar,
    boolean: boolVar
};
console.log("\nОб'єкт у форматі JSON:");
console.log(JSON.stringify(myObject, null, 2));
 </script>
</body>
</html>
