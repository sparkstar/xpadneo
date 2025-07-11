00 01 02 03 04 05 06 07 08 09 : idx
------------------------------------------------
0f 7f 7f 7f 7f 00 00 00 00 00 : normal
00 7f 7f 7f 7f 00 00 00 00 00 : HAT TOP
02 7f 7f 7f 7f 00 00 00 00 00 : HAT RIGHT
04 7f 7f 7f 7f 00 00 00 00 00 : HAT BOTTOM
06 7f 7f 7f 7f 00 00 00 00 00 : HAT LEFT
06 XX YY 7f 7f 00 00 00 00 00 : LEFT ANALOG(XX is the X axis(0x00 to 0xFF), YY is the Y axis(0x00 to 0xFF))
06 7f 7f XX YY 00 00 00 00 00 : RIGHT ANALOG(XX is the X axis(0x00 to 0xFF), YY is the Y axis(0x00 to 0xFF))
0f 7f 7f 7f 7f 00 XX 00 01 00 : LT(nintendo TL2, BTN_TL2, XX is the analog value of the trigger)
0f 7f 7f 7f 7f YY 00 00 02 00 : RT(nintendo TR2, BTN_TR2, YY is the analog value of the trigger)
0f 7f 7f 7f 7f 00 00 00 04 00 : MINUS(nintendo MINUS, BTN_SELECT)
0f 7f 7f 7f 7f 00 00 00 08 00 : PLUS(nintendo PLUS, BTN_START)
0f 7f 7f 7f 7f 00 00 00 10 00 : HOME(nintendo HOME, BTN_HOME)
0f 7f 7f 7f 7f 00 00 00 20 00 : THUMBL(nintendo THUMBL, BTN_THUMBL)
0f 7f 7f 7f 7f 00 00 00 40 00 : THUMBR(nintendo THUMBR, BTN_THUMBR)
0f 7f 7f 7f 7f 00 00 01 00 00 : A(nintendo B, BTN_SOUTH)
0f 7f 7f 7f 7f 00 00 02 00 00 : B(nintendo A, BTN_EAST)
0f 7f 7f 7f 7f 00 00 04 00 00 : L4(nintendo C, BTN_C)
0f 7f 7f 7f 7f 00 00 08 00 00 : X(nintendo Y, BTN_NORTH)
0f 7f 7f 7f 7f 00 00 10 00 00 : Y(nintendo X, BTN_WEST)
0f 7f 7f 7f 7f 00 00 20 00 00 : R4(nintendo Z, BTN_Z)
0f 7f 7f 7f 7f 00 00 40 00 00 : LB(nintendo TL, BTN_TL)
0f 7f 7f 7f 7f 00 00 80 00 00 : RB(nintendo TR, BTN_TR)
