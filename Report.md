Yumin Lisa Wei (U32552049)
Senior Design Mini-Project
9/27/22 (Granted Extension Due to Medical Emergency)

The purpose of this project is to be able to change the LED output of a Rasberry Pi by modifying the C+ program. From the pwm_led_fade.c file, we learn that the rate at which the fade occurs is controlled by a PWM signal or a pulse width modulation signal. A PWM signal is an analog signal where one increases/deacreases the pulse width/time on to increase/decrease the duty cycle, and in this case create a slower/faster fade. Therefore, the wider the pulse width/time on, the higher the duty cycle, the slower the rate of change because time on is longer.
For this mini-project, I changed one line of code. In line 62 of code is setting the clock divider by reducing the counter clock to 4; I modified 4 to 18. This increases the pulse width of the PWM by 4.5x. As a result, the fading light will be going 4.5x slower. This behavior is observed in the videos taken and included in this repository. 
