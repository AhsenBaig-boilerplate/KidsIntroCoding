# Lesson 2

Will go over writing our own

## Part 1

```js
var HowMuchanHour = 300;

var HowManyHoursAWeek = 40;

var TotalPay =  <> * <>;
```

## Part 2

```js
// Not equals to
// !==
// !=
// is not null
// <> 

var HowMuchanHour = 300;

var HowManyHoursAWeek = 40;

if (<var1> != null && <var1> != "")
{
    if(<var2> != null && <var2> != "")
    {
        var TotalPay =  <> * <>;
    }
}

```

## Part 3

```js
var HowMuchanHour = 300;

var HowManyHoursAWeek = 40;

if (HowMuchanHour != null && HowMuchanHour != "")
{
    if(HowManyHoursAWeek != null && HowManyHoursAWeek != "")
    {
        var TotalPay =  HowMuchanHour * HowManyHoursAWeek;
    }
}
```

## Part 4

```js
var HowMuchanHour = "";
var HowManyHoursAWeek = 40;
var TotalPay = "";

var ValidInput = (HowMuchanHour != null  && HowMuchanHour != "") && (HowManyHoursAWeek != null && HowManyHoursAWeek != "");

if (ValidInput)
{
    TotalPay =  HowMuchanHour * HowManyHoursAWeek;
}
```

## Part 5 - Advanced

```js
var howMuchAnHour = prompt("How much an hour?", "");

if (howMuchAnHour != null && howMuchAnHour != "") {
    document.write("You make: " + howMuchAnHour + " an hour!");
}

var howManyHoursAWeek = prompt("How many hours a week?", "");

if (howManyHoursAWeek != null && howManyHoursAWeek != "") {
    document.write("You work: " + howManyHoursAWeek + " a week!");
}

var ValidInput = (howMuchAnHour != null  && howMuchAnHour != "" && isNaN(howMuchAnHour)) 
&& (howManyHoursAWeek != null && howManyHoursAWeek != "" && isNaN(howManyHoursAWeek));

if (ValidInput)
{
    TotalPay =  howMuchAnHour * howManyHoursAWeek;
    document.write("Total Pay: " + TotalPay);
}
else{
    document.write("Invalid input");
}

```

## Part 6 - Advanced

```js
var howMuchAnHour = prompt("How much an hour?", "");

if (howMuchAnHour != null && howMuchAnHour != "") {
    document.write("You make: " + howMuchAnHour + " an hour!");
}

var howManyHoursAWeek = prompt("How many hours a week?", "");

if (howManyHoursAWeek != null && howManyHoursAWeek != "") {
    document.write("You work: " + howManyHoursAWeek + " a week!");
}

var ValidInput = (howMuchAnHour != null  && howMuchAnHour != "" && isNaN(howMuchAnHour)) 
&& (howManyHoursAWeek != null && howManyHoursAWeek != "" && isNaN(howManyHoursAWeek));

if (ValidInput)
{
    TotalPay =  howMuchAnHour * howManyHoursAWeek;
    document.write("Total Pay: " + TotalPay);
}
else{
    document.write("Invalid input");
}
```
## Part 7 - Advanced final

```js
var howMuchAnHour = prompt("How much an hour?", "");

var validHoursValue = howMuchAnHour != null && howMuchAnHour != "" &&  !isNaN(howMuchAnHour);

if (validHoursValue) {
    document.write("You make: " + howMuchAnHour + " an hour! <br />");
}
else
{
    document.write(howMuchAnHour + " is not a number for how many hours. <br />");
}

var howManyHoursAWeek = prompt("How many hours a week?", "");

var validHoursPerWeek = howManyHoursAWeek != null && howManyHoursAWeek != "" && !isNaN(howManyHoursAWeek);

if (validHoursPerWeek) {
    document.write("You work: " + howManyHoursAWeek + " a week! <br />");
}
else
{
    document.write(howManyHoursAWeek + " is not a number for hours per week.<br />");
}

var ValidInput = (validHoursValue && validHoursPerWeek);

if (ValidInput)
{
    TotalPay =  howMuchAnHour * howManyHoursAWeek;
    document.write("Total Pay: " + TotalPay);
}
else{
    document.write("Invalid input");
}
```
