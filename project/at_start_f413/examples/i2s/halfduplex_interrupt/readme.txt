/**
  **************************************************************************
  * @file     readme.txt
  * @version  v2.0.7
  * @date     2022-08-16
  * @brief    readme
  **************************************************************************
  */

  this demo is based on the at-start board, in this demo, shows in halfduplex
  mode how to use interrupt transfer data.
  the pins connection as follow:
  - pb0 as mck out
  - i2s2 slaver        i2s1 master
  - pb12     <--->     pa4(ws)
  - pb13     <--->     pa5(ck)
  - pb15     <--->     pa7(sd)

  for more detailed information. please refer to the application note document AN0102.