/**
  **************************************************************************
  * @file     readme.txt
  * @version  v2.0.5
  * @date     2022-05-20
  * @brief    readme
  **************************************************************************
  */

  this demo is based on the at-start board, in this demo, pa6, pa0 and pb6
  output pwm waveform. the tmrxclk is fixed to 144 mhz.
  the master tmrer tmr2 is running at 1 mhz and the duty cycle is equal to 20%
  the tmr3 is running:
  - at (tmr2 frequency)/ (tmr3 period + 1) = 100 khz and a duty cycle
  equal to tmr3_c1dt/(tmr3_pr + 1) = 30%
  the tmr4 is running:
  - at (tmr2 frequency)/ (tmr4 period + 1) = 200 khz and a duty cycle
  equal to tmr4_c1dt/(tmr4_pr + 1) = 60%

  for more detailed information. please refer to the application note document AN0085.
