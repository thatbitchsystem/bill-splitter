CLS
testing = 1
IF testing = 1 THEN
	REM gloop:
	REM PRINT TouchX, TouchY
	REM GOTO gloop
END IF

OPEN "receipt" FOR OUTPUT AS #1

TCOLOR 255,255,255
BCOLOR 220,208,255

100
CLS
loopcounter = 0
COLOR 181, 126, 220

CIRCLE 80, 210, 48 '1
CIRCLE 210, 210, 48 '2
CIRCLE 340, 210, 48 '3

CIRCLE 80, 330, 48
CIRCLE 210, 330, 48
CIRCLE 340, 330, 48

CIRCLE 80, 450, 48
CIRCLE 210, 450, 48
CIRCLE 340, 450, 48

CIRCLE 80, 570, 48
CIRCLE 210, 570, 48
CIRCLE 340, 570, 48

RRECT 3,3,411,144, 6
RRECT 150,630,380,715, 20

BEGINDRAW
COLOR 255,255,255

REM do print debug with disnum/datnum to check

GOTO mat

DRAWTEXT "1",  25, 15
DRAWTEXT "2",  85, 15
DRAWTEXT "3",  145, 15
DRAWTEXT "4",  205, 15
DRAWTEXT "5",  285, 15
DRAWTEXT "6",  345, 15

TEXTFONT 70
DRAWTEXT ".",  255, 53
mat:

main:

TEXTFONT 85
DRAWTEXT "1",  55, 160
DRAWTEXT "2",  185, 160
DRAWTEXT "3",  315, 160

DRAWTEXT "4",  52, 282
DRAWTEXT "5",  185, 282
DRAWTEXT "6",  313, 282

DRAWTEXT "7",  55, 402.5
DRAWTEXT "8",  185, 402.5
DRAWTEXT "9",  315, 402.5

DRAWTEXT "0",  185, 522
DRAWTEXT ".",  313, 522

TEXTFONT 40
DRAWTEXT "CLS",  45, 545
DRAWTEXT "Enter",  240, 660
ENDDRAW


GOTO 150


GOTO 150

Touchnumber:
DIM decarray(2)
DIM touchnumber(4)
IF testing = 1 THEN
	DIM decarray(90)
	DIM touchnumber(90)
END IF


loopcounter = 0
isdec = 0
counterb = 0
outputnumber = 0
finalnumber = 0
disnumcounter = 0
Touchnumberloop:
disnum = 1

displaystart:


GOTO aaaa

REM WHILE (disnum - 1 ) < loopcounter


REM loop wont break out of output loop and go back to touch loop, fix this
PRINT "disnum", disnum
PRINT "disnum counter", disnumcounter
PRINT "touchnumber" touchnumber(1), touchnumber(2), touchnumber(3), touchnumber(4)
PRINT "loopcounter", loopcounter

BEGINDRAW
COLOR 255,255,255
TEXTFONT 110
IF touchnumber(1) = 0 THEN
	GOTO aaaa
ENDIF

IF touchnumber(disnum) = 1 THEN
	IF disnum = 1 THEN
		DRAWTEXT "1",  25, 15
	ENDIF
	IF disnum = 2 THEN
		DRAWTEXT "1",  85, 15
	ENDIF
	IF disnum = 3 THEN
		DRAWTEXT "1",  145, 15
	ENDIF
	IF disnum = 4 THEN
		DRAWTEXT "1",  205, 15
	ENDIF
END IF
IF touchnumber(disnum) = 2 THEN
	IF disnum = 1 THEN
		DRAWTEXT "2",  25, 15
	ENDIF
	IF disnum = 2 THEN
		DRAWTEXT "2",  85, 15
	ENDIF
	IF disnum = 3 THEN
		DRAWTEXT "2",  145, 15
	ENDIF
	IF disnum = 4 THEN
		DRAWTEXT "2",  205, 15
	ENDIF
	INC disnumcounter
END IF
IF touchnumber(disnum) = 3 THEN
	IF disnum = 1 THEN
		DRAWTEXT "3",  25, 15
	ENDIF
	IF disnum = 2 THEN
		DRAWTEXT "3",  85, 15
	ENDIF
	IF disnum = 3 THEN
		DRAWTEXT "3",  145, 15
	ENDIF
	IF disnum = 4 THEN
		DRAWTEXT "3",  205, 15
	ENDIF
	INC disnumcounter
END IF
IF touchnumber(disnum) = 4 THEN
	IF disnum = 1 THEN
		DRAWTEXT "4",  25, 15
	ENDIF
	IF disnum = 2 THEN
		DRAWTEXT "4",  85, 15
	ENDIF
	IF disnum = 3 THEN
		DRAWTEXT "4",  145, 15
	ENDIF
	IF disnum = 4 THEN
		DRAWTEXT "4",  205, 15
	ENDIF
	INC disnumcounter
ENDIF
IF touchnumber(disnum) = 5 THEN
	IF disnum = 1 THEN
		DRAWTEXT "5",  25, 15
	ENDIF
	IF disnum = 2 THEN
		DRAWTEXT "5",  85, 15
	ENDIF
	IF disnum = 3 THEN
		DRAWTEXT "5",  145, 15
	ENDIF
	IF disnum = 4 THEN
		DRAWTEXT "5",  205, 15
	ENDIF
	INC disnumcounter
END IF
IF touchnumber(disnum) = 6 THEN
	IF disnum = 1 THEN
		DRAWTEXT "6",  25, 15
	ENDIF
	IF disnum = 2 THEN
		DRAWTEXT "6",  85, 15
	ENDIF
	IF disnum = 3 THEN
		DRAWTEXT "6",  145, 15
	ENDIF
	IF disnum = 4 THEN
		DRAWTEXT "6",  205, 15
	ENDIF
	INC disnumcounter
END IF
IF touchnumber(disnum) = 7 THEN
	IF disnum = 1 THEN
		DRAWTEXT "7",  25, 15
	ENDIF
	IF disnum = 2 THEN
		DRAWTEXT "7",  85, 15
	ENDIF
	IF disnum = 3 THEN
		DRAWTEXT "7",  145, 15
	ENDIF
	IF disnum = 4 THEN
		DRAWTEXT "7",  205, 15
	ENDIF
	INC disnumcounter
END IF
IF touchnumber(disnum) = 8 THEN
	IF disnum = 1 THEN
		DRAWTEXT "8",  25, 15
	ENDIF
	IF disnum = 2 THEN
		DRAWTEXT "8",  85, 15
	ENDIF
	IF disnum = 3 THEN
		DRAWTEXT "8",  145, 15
	ENDIF
	IF disnum = 4 THEN
		DRAWTEXT "8",  205, 15
	ENDIF
	INC disnumcounter
END IF
IF touchnumber(disnum) = 9 THEN
	IF disnum = 1 THEN
		DRAWTEXT "9",  25, 15
	ENDIF
	IF disnum = 2 THEN
		DRAWTEXT "9",  85, 15
	ENDIF
	IF disnum = 3 THEN
		DRAWTEXT "9",  145, 15
	ENDIF
	IF disnum = 4 THEN
		DRAWTEXT "9",  205, 15
	ENDIF
	INC disnumcounter
END IF
IF touchnumber(disnum) = 0 THEN
	IF disnum = 1 THEN
		DRAWTEXT "0",  25, 15
	ENDIF
	IF disnum = 2 THEN
		DRAWTEXT "0",  85, 15
	ENDIF
	IF disnum = 3 THEN
		DRAWTEXT "0",  145, 15
	ENDIF
	IF disnum = 4 THEN
		DRAWTEXT "0",  205, 15
	ENDIF
	INC disnumcounter
END IF
REM WEND

IF disnumcounter = 4 THEN
	PRINT "success"
	PAUSE
	GOTO main
ELSE
	IF disnumcounter > disnum THEN
		INC disnum
		GOTO displaystart
	ENDIF
ENDIF


GOTO displaystart
REM WHILE datnum < isdec
datnumloop:
IF decarray(datnum) = 1 THEN
	IF datnum = 1 THEN
		DRAWTEXT "1",  285, 15
		INC datnum
		GOTO datnumloop
	ENDIF
	IF datnum = 2 THEN
		DRAWTEXT "6",  345, 15
		INC datnum
		GOTO datnumloop
	ENDIF
END IF
IF decarray(datnum) = 2 THEN
	IF datnum = 1 THEN
		DRAWTEXT "2",  285, 15
		INC datnum
		GOTO datnumloop
	ENDIF
	IF datnum = 2 THEN
		DRAWTEXT "2",  345, 15
		INC datnum
		GOTO datnumloop
	ENDIF
END IF
IF decarray(datnum) = 3 THEN
	IF datnum = 1 THEN
		DRAWTEXT "3",  285, 15
		INC datnum
		GOTO datnumloop
	ENDIF
	IF datnum = 2 THEN
		DRAWTEXT "3",  345, 15
		INC datnum
		GOTO datnumloop
	ENDIF
END IF
IF decarray(datnum) = 4 THEN
	IF datnum = 1 THEN
		DRAWTEXT "4",  285, 15
		INC datnum
		GOTO datnumloop
	ENDIF
	IF datnum = 2 THEN
		DRAWTEXT "4",  345, 15
		INC datnum
		GOTO datnumloop
	ENDIF
END IF
IF decarray(datnum) = 5 THEN
	IF datnum = 1 THEN
		DRAWTEXT "5",  285, 15
		INC datnum
		GOTO datnumloop
	ENDIF
	IF datnum = 2 THEN
		DRAWTEXT "5",  345, 15
		INC datnum
		GOTO datnumloop
	ENDIF
END IF
IF decarray(datnum) = 6 THEN
	IF datnum = 1 THEN
		DRAWTEXT "6",  285, 15
		INC datnum
		GOTO datnumloop
	ENDIF
	IF datnum = 2 THEN
		DRAWTEXT "6",  345, 15
		INC datnum
		GOTO datnumloop
	ENDIF
END IF
IF decarray(datnum) = 7 THEN
	IF datnum = 1 THEN
		DRAWTEXT "7",  285, 15
		INC datnum
		GOTO datnumloop
	ENDIF
	IF datnum = 2 THEN
		DRAWTEXT "7",  345, 15
		INC datnum
		GOTO datnumloop
	ENDIF
END IF
IF decarray(datnum) = 8 THEN
	IF datnum = 1 THEN
		DRAWTEXT "8",  285, 15
		INC datnum
		GOTO datnumloop
	ENDIF
	IF datnum = 2 THEN
		DRAWTEXT "8",  345, 15
		INC datnum
		GOTO datnumloop
	ENDIF
END IF
IF decarray(datnum) = 9 THEN
	IF datnum = 1 THEN
		DRAWTEXT "9",  285, 15
		INC datnum
		GOTO datnumloop
	ENDIF
	IF datnum = 2 THEN
		DRAWTEXT "9",  345, 15
		INC datnum
		GOTO datnumloop
	ENDIF
END IF
IF decarray(datnum) = 0 THEN
	IF datnum = 1 THEN
		DRAWTEXT "0",  285, 15
		INC datnum
		GOTO datnumloop
	ENDIF
	IF datnum = 2 THEN
		DRAWTEXT "0",  345, 15
		INC datnum
		GOTO datnumloop
	ENDIF
END IF
END IF
REM WEND
ENDDRAW

aaaa:


SLEEP 0.1
IF TouchX > 30 AND TouchX < 140 AND TouchY > 160 AND TouchY < 260 THEN
	PRINT "you pressed 1"
	
	COLOR 153, 93, 196
	CIRCLE 80, 210, 44
	
	COLOR 255,255,255
	TEXTFONT 83
	DRAWTEXT "1",  57, 162
	
	SLEEP 0.33
	
	COLOR 181, 126, 220
	CIRCLE 80, 210, 48
	
	COLOR 255,255,255
	TEXTFONT 85
	DRAWTEXT "1",  55, 160
	
	touchinput = 1
	IF isdec > 0 AND < 3 THEN
		decarray(isdec) = touchinput
		INC isdec
		GOTO Touchnumberloop
	END IF
	IF isdec = 0 THEN
		INC loopcounter
		INC disnum
		touchnumber(loopcounter) = touchinput
	END IF
ENDIF

IF TouchX > 160 AND TouchX < 270 AND TouchY > 160 AND TouchY < 260 THEN
	PRINT "you pressed 2"
	
	COLOR 153, 93, 196
	CIRCLE 210, 210, 44
	
	COLOR 255,255,255
	TEXTFONT 83
	DRAWTEXT "2", 187, 162
	
	SLEEP 0.33
	
	COLOR 181, 126, 220
	CIRCLE 210, 210, 48
	
	COLOR 255,255,255
	TEXTFONT 85
	DRAWTEXT "2", 185, 160
	
	touchinput = 2
	IF isdec > 0 AND < 3 THEN
		decarray(isdec) = touchinput
		INC isdec
		GOTO Touchnumberloop
	END IF
	IF isdec = 0 THEN
		INC loopcounter
		touchnumber(loopcounter) = touchinput
	END IF
ENDIF

IF TouchX > 290 AND TouchX < 450 AND TouchY > 160 AND TouchY < 260 THEN
	PRINT "you pressed 3"
	
	COLOR 153, 93, 196
	CIRCLE 340, 210, 44
	
	COLOR 255,255,255
	TEXTFONT 83
	DRAWTEXT "3", 317, 162
	
	SLEEP 0.33
	
	COLOR 181, 126, 220
	CIRCLE 340, 210, 48
	
	COLOR 255,255,255
	TEXTFONT 85
	DRAWTEXT "3", 315, 160
	
	touchinput = 3
	IF isdec > 0 AND < 3 THEN
		decarray(isdec) = touchinput
		INC isdec
		GOTO Touchnumberloop
		
	END IF
	IF isdec = 0 THEN
		INC loopcounter
		touchnumber(loopcounter) = touchinput
	END IF
ENDIF
IF TouchX > 30 AND TouchX < 140 AND TouchY > 290 AND TouchY < 390 THEN
	PRINT "you pressed 4"
	
	COLOR 153, 93, 196
	CIRCLE 80, 330, 44
	
	COLOR 255,255,255
	TEXTFONT 83
	DRAWTEXT "4",  54, 284
	
	SLEEP 0.33
	
	COLOR 181, 126, 220
	CIRCLE 80, 330, 48
	
	COLOR 255,255,255
	TEXTFONT 85
	DRAWTEXT "4",  52, 282
	
	touchinput = 4
	IF isdec > 0 AND < 3 THEN
		decarray(isdec) = touchinput
		INC isdec
		GOTO Touchnumberloop
	END IF
	IF isdec = 0 THEN
		INC loopcounter
		touchnumber(loopcounter) = touchinput
	END IF
ENDIF
IF TouchX > 160 AND TouchX < 270 AND TouchY > 275 AND TouchY < 380 THEN
	PRINT "you pressed 5"
	
	COLOR 153, 93, 196
	CIRCLE 210, 330, 44
	
	COLOR 255,255,255
	TEXTFONT 83
	DRAWTEXT "5",  187, 284
	
	SLEEP 0.33
	
	COLOR 181, 126, 220
	CIRCLE 210, 330, 48
	
	COLOR 255,255,255
	TEXTFONT 85
	DRAWTEXT "5",  185, 282
	
	touchinput = 5
	IF isdec > 0 AND < 3 THEN
		decarray(isdec) = touchinput
		INC isdec
		GOTO Touchnumberloop
	END IF
	IF isdec = 0 THEN
		INC loopcounter
		touchnumber(loopcounter) = touchinput
	END IF
ENDIF
IF TouchX > 290 AND TouchX < 390 AND TouchY > 290 AND TouchY < 390 THEN
	PRINT "you pressed 6"
	
	COLOR 153, 93, 196
	CIRCLE 340, 330, 44
	
	COLOR 255,255,255
	TEXTFONT 83
	DRAWTEXT "6",  315, 284
	
	SLEEP 0.33
	
	COLOR 181, 126, 220
	CIRCLE 340, 330, 48
	
	COLOR 255,255,255
	TEXTFONT 85
	DRAWTEXT "6",  313, 282
	
	touchinput = 6
	IF isdec > 0 AND < 3 THEN
		decarray(isdec) = touchinput
		REM PRINT decarray(isdec)
		INC isdec
		GOTO Touchnumberloop
	END IF
	IF isdec = 0 THEN
		INC loopcounter
		touchnumber(loopcounter) = touchinput
	END IF
ENDIF
IF TouchX > 30 AND TouchX < 140 AND TouchY > 400 AND TouchY < 510 THEN
	PRINT "you pressed 7"
	
	COLOR 153, 93, 196
	CIRCLE 80, 450, 44
	
	COLOR 255,255,255
	TEXTFONT 83
	DRAWTEXT "7",  57, 404.5
	
	SLEEP 0.33
	
	COLOR 181, 126, 220
	CIRCLE 80, 450, 48
	
	COLOR 255,255,255
	TEXTFONT 85
	DRAWTEXT "7",  55, 402.5
	
	touchinput = 7
	IF isdec > 0 AND < 3 THEN
		decarray(isdec) = touchinput
		INC isdec
		GOTO Touchnumberloop
	END IF
	IF isdec = 0 THEN
		INC loopcounter
		touchnumber(loopcounter) = touchinput
	END IF
ENDIF
IF TouchX > 160 AND TouchX < 270 AND TouchY > 400 AND TouchY < 510 THEN
	PRINT "you pressed 8"
	
	COLOR 153, 93, 196
	CIRCLE 210, 450, 44
	
	COLOR 255,255,255
	TEXTFONT 83
	DRAWTEXT "8",  187, 404.5
	
	
	SLEEP 0.33
	
	COLOR 181, 126, 220
	CIRCLE 210, 450, 48
	
	COLOR 255,255,255
	TEXTFONT 85
	DRAWTEXT "8",  185, 402.5
	
	touchinput = 8
	IF isdec > 0 AND < 3 THEN
		decarray(isdec) = touchinput
		INC isdec
		GOTO Touchnumberloop
	END IF
	IF isdec = 0 THEN
		INC loopcounter
		touchnumber(loopcounter) = touchinput
	END IF
ENDIF
IF TouchX > 290 AND TouchX < 390 AND TouchY > 400 AND TouchY < 510 THEN
	PRINT "you pressed 9"
	
	COLOR 153, 93, 196
	CIRCLE 340, 450, 44
	
	
	COLOR 255,255,255
	TEXTFONT 83
	DRAWTEXT "9",  317, 404.5
	
	SLEEP 0.33
	DRAWTEXT "9",  317, 404.5
	
	COLOR 181, 126, 220
	CIRCLE 340, 450, 48
	
	COLOR 255,255,255
	TEXTFONT 85
	DRAWTEXT "9",  315, 402.5
	
	touchinput = 9
	IF isdec > 0 AND < 3 THEN
		decarray(isdec) = touchinput
		INC isdec
		GOTO Touchnumberloop
	END IF
	IF isdec = 0 THEN
		INC loopcounter
		touchnumber(loopcounter) = touchinput
	END IF
ENDIF

IF TouchX > 30 AND TouchX < 140 AND TouchY > 520 AND TouchY < 620 THEN
	PRINT "you pressed CLS"
	
	COLOR 153, 93, 196
	CIRCLE 80, 570, 44
	
	COLOR 255,255,255
	TEXTFONT 39
	DRAWTEXT "CLS",  47, 547
	
	SLEEP 0.33
	
	COLOR 181, 126, 220
	CIRCLE 80, 570, 48
	
	COLOR 255,255,255
	TEXTFONT 40
	DRAWTEXT "CLS",  45, 545
	
	COLOR 181, 126, 220
	RRECT 3,3,411,144, 6
	CLS TTY
	
	IF questionnumber = 1 THEN
		PRINT "Please enter how many items on bill:"
	END IF
	IF questionnumber = 2 THEN
		PRINT "How much did this item cost? " "(" reversecounter " of " n ")"
	END IF
	IF questionnumber = 3 THEN
		GOTO regularfuckup
		fuckup:
		singleinput = 1
		regularfuckup:
		PRINT "Who is paying for this item? $" cost
		PRINT "1 - Both"
		PRINT "2 - Akhila"
		PRINT "3 - Riley"
	END IF
	IF questionnumber = 4 THEN
		PRINT "Is there more to calculate?"
		PRINT "1 = yes"
		PRINT "2 = no"
	END IF
	IF questionnumber = 5 THEN
		PRINT "Combined subtotal $" sub_total
		PRINT "What is the total on the bill?"
	END IF
	GOTO Touchnumber
ENDIF

IF TouchX > 160 AND TouchX < 260 AND TouchY > 520 AND TouchY < 620 THEN
	IF isdec = 1 THEN
		GOTO skiptheskip
	ENDIF
	IF loopcounter = 0 THEN
		COLOR 153, 93, 196
		CIRCLE 210, 570, 44
		
		COLOR 255,255,255
		TEXTFONT 83
		DRAWTEXT "0",  187, 524
		
		SLEEP 0.33
		
		COLOR 181, 126, 220
		CIRCLE 210, 570, 48
		
		COLOR 255,255,255
		TEXTFONT 85
		DRAWTEXT "0",  185, 522
		
		GOTO Touchnumberloop
	ENDIF
	skiptheskip:
	
	PRINT "you pressed 0"
	
	COLOR 153, 93, 196
	CIRCLE 210, 570, 44
	
	COLOR 255,255,255
	TEXTFONT 83
	DRAWTEXT "0",  187, 524
	
	SLEEP 0.33
	
	COLOR 181, 126, 220
	CIRCLE 210, 570, 48
	
	COLOR 255,255,255
	TEXTFONT 85
	DRAWTEXT "0",  185, 522
	
	touchinput = 0
	IF isdec > 0 AND < 3 THEN
		decarray(isdec) = touchinput
		INC isdec
		GOTO Touchnumberloop
	END IF
	IF isdec = 0 THEN
		INC loopcounter
		touchnumber(loopcounter) = touchinput
	END IF
ENDIF

IF TouchX > 160 AND TouchX < 390 AND TouchY > 630 AND TouchY < 715 THEN
	PRINT "you pressed enter"
	
	COLOR 153, 93, 196
	RRECT 154,634,376,711, 17.5
	
	COLOR 255,255,255
	TEXTFONT 39
	DRAWTEXT "Enter",  243, 662
	
	SLEEP 0.66
	
	COLOR 181, 126, 220
	RRECT 150,630,380,715, 20
	
	COLOR 255,255,255
	TEXTFONT 40
	DRAWTEXT "Enter",  240, 660
	
	
	GOTO savenumber
ENDIF


IF TouchX > 290 AND TouchX < 390 AND TouchY > 520 AND TouchY < 620 THEN
	
	
	COLOR 153, 93, 196
	CIRCLE 340, 570, 44
	
	COLOR 255,255,255
	TEXTFONT 81
	DRAWTEXT ".",  318, 527
	
	SLEEP 0.33
	
	COLOR 181, 126, 220
	CIRCLE 340, 570, 48
	
	COLOR 255,255,255
	TEXTFONT 85
	DRAWTEXT ".",  315, 522
	IF questionnumber = 1 OR questionnumber = 3 OR questionnumber = 1 THEN
		GOTO Touchnumberloop
	ENDIF
	PRINT "you pressed ."
	isdec = 1
	GOTO Touchnumberloop
ENDIF


IF singleinput >= 1  AND loopcounter = 1 THEN
	outputnumber = touchinput
	singleinput = 0
	RETURN
ENDIF
IF loopcounter = 1 AND disnum = 0 THEN
	disnum = 1
END IF


GOTO Touchnumberloop

REM put the two lines below to above the goto flr testing
PRINT "touch number", touchnumber(1), touchnumber(2),touchnumber(3),touchnumber(4)
PRINT "dec num", decarray(1),decarray(2)

savenumber:
counterb= 1
IF loopcounter = 4 THEN
	GOTO 10
END IF
IF loopcounter = 3 THEN
	GOTO 20
END IF
IF loopcounter = 2 THEN
	GOTO 30
END IF
IF loopcounter = 1 THEN
	GOTO 40
END IF

10
finalnumber = finalnumber + ( touchnumber(counterb) * 1000 )
INC counterb

20
finalnumber = finalnumber + ( touchnumber(counterb) * 100 )
INC counterb

30
finalnumber = finalnumber + ( touchnumber(counterb) * 10 )
INC counterb

40
finalnumber = finalnumber + touchnumber(counterb)
finalnumber = finalnumber + ( ( decarray(1) * 0.1 ) )

IF isdec > 1 THEN
	finalnumber = finalnumber + ( ( decarray(2) * 0.01 ) )
ENDIF
ENDIF

outputnumber = finalnumber
RETURN

REM outputnumber is the variable all others should be using

150
CLS TTY
cost = 0
questionnumber = 1
PRINT "Please enter how many items on bill:"
GOSUB Touchnumber
n = outputnumber

reversecounter = 1
CLS tty

WHILE i < n
	200
	questionnumber = 2
	REM PRINT "what was the name of the item"
	REM get string name
	PRINT "How much did this item cost? " "(" reversecounter " of " n ")"
	INC reversecounter
	GOSUB Touchnumber
	cost = outputnumber
	REM cost2 is variable for storing cost for if the user messes up a choice
	cost2 = cost
	
	CLS tty
	questionnumber = 3
	PRINT "Who is paying for this item? $" cost
	PRINT "1 - Both"
	PRINT "2 - Akhila"
	PRINT "3 - Riley"
	singleinput = 1
	GOSUB Touchnumber
	300
	choice = outputnumber
	PRINT "choice" choice
	IF choice = 1 THEN
		total_both = total_both + cost
		PRINT #1, "Item #" (reversecounter - 1) " = $" cost2 " - Both ($" (cost/2) " each)"
		GOTO 400
	ELSE
		IF choice = 2 THEN
			akhila_total = akhila_total + cost
			PRINT #1, "Item #" (reversecounter - 1) " = $" cost2 " - Akhila"
			GOTO 400
		ELSE
			IF choice = 3 THEN
				riley_total = riley_total + cost
				PRINT #1, "Item #" (reversecounter - 1) " = $" cost2 " - Riley"
				GOTO 400
			ELSE
				CLS tty
				PRINT "Dumbass that wasn't a valid option, try again"
				GOSUB fuckup
				GOTO 300
			END IF
		END IF
	END IF
	400
	CLS tty
	again = 0
	cost = 0
	INC i
WEND

questionnumber = 4
PRINT "Is there more to calculate?"
PRINT "1 = yes"
PRINT "2 = no"
singleinput = 1
GOSUB Touchnumber
again = outputnumber
CLS tty
IF again = 1 THEN
	n = 0
	GOTO 100
ELSE
	IF again = 2 THEN
		GOTO 500
	ELSE
		PRINT "You hit an invalid button, dumbass. Try again."
		PAUSE
		CLS tty
		PRINT "How much did the item cost?" cost2
		PRINT "Who is paying for the item?"
		PRINT "1 - Both"
		PRINT "2 - Akhila"
		PRINT "3 - Riley"
		PRINT choice
		GOTO 400
	END IF
END IF

500

PRINT "Akhila spent...............$" akhila_total
PRINT "Riley spent................$" riley_total
PRINT "Total shared spent.........$" total_both

PRINT #1, "Akhila spent...............$" akhila_total
PRINT #1, "Riley spent................$" riley_total
PRINT #1, "Total shared spent.........$" total_both

total_both_halved_temp = ( total_both * 0.5 )

result_1 = MOD(total_both_halved_temp, 0.01)
IF result_1 <= 0.005 THEN
	result_2 = total_both_halved_temp - result_1
ELSE
	result_2 = ( total_both_halved_temp - result_1 ) + 0.01
ENDIF
total_both_halved = result_2

PRINT "Amount each person pays....$" total_both_halved

akhila_sub_total = akhila_total + total_both_halved
riley_sub_total = riley_total + total_both_halved
sub_total = riley_sub_total + akhila_sub_total

PRINT "Combined subtotal..........$" sub_total

mistakeloop:
PRINT "Akhila's subtotal..........$" akhila_sub_total
PRINT "Rileys subtotal............$" riley_sub_total

PRINT #1, "Combined subtotal..........$" sub_total
GOTO skipmistake
questionnumber = 6
PRINT "does there need to be any adjustments?"
PRINT "1 - yes"
PRINT "2 - no"
singleinput= 1
GOSUB Touchnumber
IF outputnumber = 2 THEN
	GOTO skipmistake
ENDIF
IF outputnumber = 1 THEN
	questionnumber = 7
	CLS tty
	singleinput = 1
	PRINT "which subtotal needs to be adjusted"
	PRINT "1 - Akhila Subtotal   $" akhila_sub_total
	PRINT "2 - Riley Subtotal    $" riley_sub_total
	GOSUB Touchnumber
	IF outputnumber = 1 THEN
		CLS tty
		PRINT "Akhila's current Subtotal $" akhila_sub_total
		PRINT "Need to add or subtract?
		PRINT "1 - add"
		PRINT "2 - subtract
		singleinput = 1
		GOSUB Touchnumber
		IF outputnumber = 1 THEN
			PRINT "How much to add to Akhila's Subtotal?"
			PRINT "$" akhila_sub_total
			GOSUB Touchnumber
			akhila_sub_total = akhila_sub_total + outputnumber
			PRINT "Akhila's new subtotal is $" akhila_sub_total
			sub_total = riley_sub_total + akhila_sub_total
			
			PAUSE
			CLS tty
			GOTO mistakeloop
		ENDIF
		IF outputnumber = 2 THEN
			PRINT "How much to subtract from Akhila's Subtotal?"
			PRINT "$" akhila_sub_total
			GOSUB Touchnumber
			akhila_sub_total = akhila_sub_total - outputnumber
			PRINT "Akhila's new subtotal is $" akhila_sub_total
			sub_total = riley_sub_total + akhila_sub_total
			PAUSE
			CLS tty
			GOTO mistakeloop
		ENDIF
		
	ENDIF
	IF outputnumber = 3 THEN
		CLS tty
		PRINT "Riley's current Subtotal $" riley_sub_total
		PRINT "Need to add or subtract?
		PRINT "1 - add"
		PRINT "2 - subtract
		singleinput = 1
		GOSUB Touchnumber
		IF outputnumber = 1 THEN
			PRINT "How much to add to Riley's Subtotal?"
			PRINT "$" riley_sub_total
			GOSUB Touchnumber
			riley_sub_total = riley_sub_total + outputnumber
			PRINT "Riley's new subtotal is $" riley_sub_total
			sub_total = riley_sub_total + akhila_sub_total
			PAUSE
			CLS tty
			GOTO mistakeloop
		ENDIF
		IF outputnumber = 2 THEN
			PRINT "How much to subtract from Riley's Subtotal?"
			PRINT "$" riley_sub_total
			GOSUB Touchnumber
			riley_sub_total = riley_sub_total - outputnumber
			PRINT "Riley's new subtotal is $" riley_sub_total
			sub_total = riley_sub_total + akhila_sub_total
			PAUSE
			CLS tty
			GOTO mistakeloop
		ENDIF
	END IF
END IF

PAUSE

skipmistake:


PRINT "Combined subtotal $" sub_total

PRINT "What is the total on the bill?"
questionnumber = 5

GOSUB Touchnumber
bill_total = outputnumber

tax_total =  bill_total - sub_total

akhila_tax_rate = akhila_sub_total / sub_total
riley_tax_rate = riley_sub_total / sub_total


akhila_tax = akhila_tax_rate * tax_total
riley_tax = riley_tax_rate * tax_total
akhila_grand_total = akhila_sub_total + akhila_tax
riley_grand_total = riley_sub_total + riley_tax

result_1 = MOD(akhila_tax, 0.01)
IF result_1 <= 0.005 THEN
	result_2 = akhila_tax - result_1
ELSE
	result_2 = (akhila_tax - result_1 ) + 0.01
ENDIF
akhila_tax = result_2

result_1 = MOD(riley_tax, 0.01)
IF result_1 <= 0.005 THEN
	result_2 = riley_tax - result_1
ELSE
	result_2 = (riley_tax - result_1 ) + 0.01
ENDIF
riley_tax = result_2

result_1 = MOD(akhila_grand_total, 0.01)
IF result_1 <= 0.005 THEN
	result_2 = akhila_grand_total - result_1
ELSE
	result_2 = (akhila_grand_total - result_1 ) + 0.01
ENDIF
akhila_grand_total = result_2

result_1 = MOD(riley_grand_total, 0.01)
IF result_1 <= 0.005 THEN
	result_2 = riley_grand_total - result_1
ELSE
	result_2 = (riley_grand_total - result_1 ) + 0.01
ENDIF
riley_grand_total = result_2

CLS tty



PRINT "Bill total.................$" bill_total
PRINT "Akhila's subtotal..........$" akhila_sub_total
PRINT "Akhila's Tax...............$" akhila_tax
PRINT "Akhila owes................$" akhila_grand_total
PRINT "Riley's subtotal...........$" riley_sub_total
PRINT "Riley's Tax................$" riley_tax
PRINT "Riley owes.................$" riley_grand_total

PRINT #1, "Bill total.................$" bill_total
PRINT #1, "Akhila's subtotal..........$" akhila_sub_total
PRINT #1, "Akhila's Tax...............$" akhila_tax
PRINT #1, "Akhila owes................$" akhila_grand_total
PRINT #1, "Riley's subtotal...........$" riley_sub_total
PRINT #1, "Riley's Tax................$" riley_tax
PRINT #1, "Riley owes.................$" riley_grand_total

CLOSE #1
REM COPY "Receipt", "Receipt copy"

END

GOTO 777
LOADSPRITE 1, "pipe"
LOADSPRITE 2, "Mario"
LOADSPRITE 3, "koopa_shell"

DRAWSPRITE 1,300,650,0.23
DRAWSPRITE 2,60,580,0.4
DRAWSPRITE 3,83,680,1.2
777














