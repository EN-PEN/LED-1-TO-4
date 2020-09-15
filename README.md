題目1(1~4)

😠😠😠😠
😡😠😠😠
😠😡😠😠
😠😠😡😠
😠😠😠😡
如下:

int LED=5;
void setup() {
 for (int i=2 ;i<6;i++)
 pinMode(i,OUTPUT);
}

void loop() {
  // put your main code here, to run repeatedly:
  for(int i=5; i>1; i--)
    digitalWrite(i,HIGH);
    
  if (LED>=2)
   digitalWrite(LED,LOW);
     
  else
    LED=6;
    LED--;
   delay(200);
}

圖如下：![image](https://github.com/EN-PEN/LED-1-TO-4/blob/master/IMG20200915111514.jpg)


題目2:(1~8)
😠😠😠😠😠😠😠😠
😡😠😠😠😠😠😠😠
😠😡😠😠😠😠😠😠
😠😠😡😠😠😠😠😠
😠😠😠😡😠😠😠😠
😠😠😠😠😡😠😠😠
😠😠😠😠😠😡😠😠
😠😠😠😠😠😠😡😠
😠😠😠😠😠😠😠😡
int LED=10;
void setup() {
 for (int i=2 ;i<10;i++)
 pinMode(i,OUTPUT);
}

void loop() {
  // put your main code here, to run repeatedly:
  for(int i=10; i>1; i--)
    digitalWrite(i,HIGH);
    
  if (LED>=0)
   digitalWrite(LED,LOW);
     
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
