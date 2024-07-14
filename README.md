The buzzer project is quite simple and exciting, as it enables even a newbie to learn how to make use of the Arduino board in controlling the operation of a buzzer.
By writing a small program, the buzzer will be able to create different types of sounds, including beeps and tones. 
You will learn about digital outputs, sound generation, and general programming through this project. It is a fun way to introduce yourself to the Arduino and electronics. 
Grab that Arduino board and buzzer, and you're ready to start making sound effects of your own.


write a code for buzzer sound using arduino

const int buzzer = 9;

 float height = 330; 

void setup(){
 
  pinMode(buzzer, OUTPUT); 

}

void loop(){
  
 if(!buzzer == height)
 
  {
  
    noTone(buzzer);
    
    while(1);
    
  }
  
  tone(buzzer, 1000); 
  
  delay(1000);    
  
  noTone(buzzer);   
  
  delay(1000);  
  

   if(!buzzer < height)
   
    {
    
      noTone(buzzer);
      
      while(1);
      
    }
    
    tone(buzzer, 1000);
    
    delay(1000); 
    
    noTone(buzzer); 
    
    delay(1000);
    
}


