# NepaliDateTool.UWP
Nepali date converter tool for UWP

NuGet Link: https://www.nuget.org/packages/NepaliDateTool.UWP/

**How to use?**

```c#
DateTime dt = DateTime.Now;

NepaliDate nDate = NepaliDate.AD2BS(dt);

string nepaliDate=nDate.ToString(); //=> २०७३/०८/२१

string nepaliDate2=nDate.ToString(inNepali: false); //=> 2073/08/21

string nepaliDate3=nDate.ToString("mmm dd, yyyy DDD"); //=> असोज २१, २०७३ आइतबार



NepaliDate.getNepaliMonth(6); //=> Ashwin

NepaliDate.getNepaliMahina(6); //=> आश्विन

NepaliDate.getNepaliMahina(6,true); //=> असोज

NepaliDate.getNepaliNumber(123); //=> १२३
```
---------------------------------------------

|**Formats**|**Example**|
|-----------|-----------|
|yyyy       |  2073     |
|yyy        | 073       |
|yy         |73         |
|MMM        |   आश्विन   |
|mmm        |  असोज    |
|mm         | ०६        |
|m          |६          |
|dd         | २१, ०६     | 
|d          |२१, ६     | 
|DDD        |   आइतबार |
|DD         |   आइत    |
|D          |  १        |


and many more...

[ Don't forget to give Star if you liked it ]
