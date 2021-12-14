/**
  **************************************************************************
  * @file     readme.txt
  * @version  v2.0.0
  * @date     2021-11-26
  * @brief    readme
  **************************************************************************
  */

  this demo is based on the at-start board, in this demo, shows in halfduplex
  mode how to use polling transfer data. use the mode switch to realize spi and
  i2s communication.
  the pins connection as follow:
  - pb0 as mck out
  - i2s2 slaver        i2s1 master
  - pb12     <--->     pa4(ws)
  - pb13     <--->     pa5(ck)
  - pb15     <--->     pa7(sd)

