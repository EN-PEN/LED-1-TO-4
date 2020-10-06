題目1(1~4)

😠😠😠😠
😡😠😠😠
😠😡😠😠
😠😠😡😠
😠😠😠😡
如下:
```C++
int LED=5;(初始值)<br>
void setup() {<br>
 for (int i=2 ;i<6;i++)(For迴圈設定2~6層遞)<br>
 pinMode(i,OUTPUT);(設定輸出腳)<br>
}<br>

void loop() {<br>
  // put your main code here, to run repeatedly:<br>
  for(int i=5; i>1; i--)(設定遞增)<br>
    digitalWrite(i,HIGH);(亮)<br>
    
  if (LED>=2)<br>
   digitalWrite(LED,LOW);(滅)<br>
     
  else(重置)<br>
    LED=6;<br>
    LED--;<br>
   delay(200);<br>
}<br>
```
圖如下：![image](https://github.com/EN-PEN/LED-1-TO-4/blob/master/IMG20200915111514.jpg)


題目2:(1~8)(擴大)
😠😠😠😠😠😠😠😠
😡😠😠😠😠😠😠😠
😠😡😠😠😠😠😠😠
😠😠😡😠😠😠😠😠
😠😠😠😡😠😠😠😠
😠😠😠😠😡😠😠😠
😠😠😠😠😠😡😠😠
😠😠😠😠😠😠😡😠
😠😠😠😠😠😠😠😡
```C++
int LED=10;(設定初始值)<br>
void setup() {<br>
 for (int i=2 ;i<10;i++)(for設定層遞2~10)<br>
 pinMode(i,OUTPUT);(設定輸出腳)<br>
}<br>

void loop() {<br>
  // put your main code here, to run repeatedly:<br>
  for(int i=10; i>1; i--)<br>
    digitalWrite(i,HIGH);(亮)<br>
    
  if (LED>=0)<br>
   digitalWrite(LED,LOW);(滅)<br>
     
  else<br>
    LED=10;<br>
    LED--;<br>
   delay(200);<br>
}<br>
```
圖如下：![image](https://github.com/EN-PEN/LED-1-TO-4/blob/master/IMG20200915111230.jpg)

加分題: 

😠😠😠😠😠😠😠😠
😠😠😠😠😠😠😠😡
😠😠😠😠😠😠😡😠
😠😠😠😠😠😡😠😠
😠😠😠😠😡😠😠😠
😠😠😠😡😠😠😠😠
😠😠😡😠😠😠😠😠
😠😡😠😠😠😠😠😠
😡😠😠😠😠😠😠😠
```C++
int LED=10;<br>
void setup() {<br>
 for (int i=2 ;i<10;i++)<br>
 pinMode(i,OUTPUT);<br>
}<br>

void loop() {<br>
  // put your main code here, to run repeatedly:<br>
  for(int i=2; i<10; i++)<br>
    digitalWrite(i,HIGH);<br>
    
  if (LED>=10)<br>
   digitalWrite(LED,LOW);<br>
     
  else<br>
    LED=1;<br>
    LED++;<br>
   delay(200);<br>
}<br>
```
