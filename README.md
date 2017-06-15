# NepaliDateTool.UWP
Nepali date converter tool for UWP

How to use?

DateTime dt = DateTime.Now;
NepaliDate nDate = NepaliDate.AD2BS(dt);
string nepaliDate=nDate.ToString(); //=> २०७३/०८/२१
string nepaliDate2=nDate.ToString(false); //=> 2073/08/21
string nepaliDate3=nDate.ToString("mmm dd, yyyy DDD"); //=> 2073/08/21


NepaliDate.getNepaliMonth(6); //=> Ashwin
NepaliDate.getNepaliMahina(6); //=> आश्विन
NepaliDate.getNepaliMahina(6,true); //=> असोज
NepaliDate.getNepaliNumber(123); //=> १२३


Formats   Example
yyyy     2073
yyy      073
yy       73
MMM      आश्विन
mmm      असोज
mm       ०६
m        ६
dd       २१, ६ 
d        २१, ०६ 
DDD      आइतबार
DD       आइत
D        १

+ many more
