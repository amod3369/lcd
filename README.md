# lcd
display the name in lcd broad
#include <LiquidCrystal.h>

LiquidCrystal lcd(5, 6, 7, 8, 9, 10);

void setup()
{
  lcd.begin(16, 2);

  lcd.print("hello DLithe....!!");
}

void loop()
{
  lcd.setCursor(3, 1);
  lcd.print(" by Amod");
  
}
