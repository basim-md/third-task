# third-task
دائرة للتحكم بعين الروبوت
تغيير الديلاي في الكود يخفض ويزيد من صرفية الكهرباء
كود الاردوينو :
int Led1 =1;
int Led2 =3;
void setup() {
  pinMode(Led1,OUTPUT);
  pinMode(Led2,OUTPUT);
}
void loop()
{
 digitalWrite(Led1,HIGH);
   digitalWrite(Led2,HIGH);
  delay(100);
  digitalWrite(Led1,LOW);
   digitalWrite(Led2,LOW);
  delay(100);
}
رابط الدائرة من التنكركاد:
https://www.tinkercad.com/things/d8J9LDd1MID-incredible-krunk/editel?sharecode=7NgPG4Fr1BZRXgi4QPFfrQS-EsdC8f7DSq7KqM6kUrQ
