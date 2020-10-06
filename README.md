題目1(1~4)

😠😠😠😠
😡😠😠😠
😠😡😠😠
😠😠😡😠
😠😠😠😡
如下:

int LED=5;(初始值)
void setup() {
 for (int i=2 ;i<6;i++)(For迴圈設定2~6層遞)
 pinMode(i,OUTPUT);(設定輸出腳)
}

void loop() {
  // put your main code here, to run repeatedly:
  for(int i=5; i>1; i--)(設定遞增)
    digitalWrite(i,HIGH);(亮)
    
  if (LED>=2)
   digitalWrite(LED,LOW);(滅)
     
  else(重置)
    LED=6;
    LED--;
   delay(200);
}

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
int LED=10;(設定初始值)
void setup() {
 for (int i=2 ;i<10;i++)(for設定層遞2~10)
 pinMode(i,OUTPUT);(設定輸出腳)
}

void loop() {
  // put your main code here, to run repeatedly:
  for(int i=10; i>1; i--)
    digitalWrite(i,HIGH);(亮)
    
  if (LED>=0)
   digitalWrite(LED,LOW);(滅)
     
  else
    LED=10;
    LED--;
   delay(200);
}

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

int LED=10;
void setup() {
 for (int i=2 ;i<10;i++)
 pinMode(i,OUTPUT);
}

void loop() {
  // put your main code here, to run repeatedly:
  for(int i=2; i<10; i++)
    digitalWrite(i,HIGH);
    
  if (LED>=10)
   digitalWrite(LED,LOW);
     
  else
    LED=1;
    LED++;
   delay(200);
}
