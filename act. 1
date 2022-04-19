from machine import Pin
import time
inp1 = Pin(28, Pin.IN)
inp2 = Pin(27, Pin.IN)
led1 = Pin(1, Pin.OUT)
led2 = Pin(2, Pin.OUT)
while 1:
  if inp1.value() == 1:
    led1.on()
  else:
    led1.off()

  if inp2.value() == 1:
    if led2.value() == 1:
      led2.off()  
      time.sleep_ms(500)
    if led2.value() == 0:
      led2.on()
      time.sleep_ms(500)
