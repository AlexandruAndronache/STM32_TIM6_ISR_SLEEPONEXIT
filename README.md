# STM32_TIM6_ISR_SLEEPONEXIT
 Power saving via SLEEPONEXIT feature

 This project showcases the SLEEPONEXIT feature of the STM32F44 microcontroller.
 Each time an interrupt callback has finished executing the processor goes in NORMAL SLEEP MODE until a new interrupt is triggered.
 Using this method the consumption has been reduced from 3.8 mA to 2.1 mA.