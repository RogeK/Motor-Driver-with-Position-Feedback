EESchema Schematic File Version 4
EELAYER 30 0
EELAYER END
$Descr A4 11693 8268
encoding utf-8
Sheet 3 4
Title ""
Date ""
Rev ""
Comp ""
Comment1 ""
Comment2 ""
Comment3 ""
Comment4 ""
$EndDescr
Text GLabel 4500 3900 0    50   Input ~ 10
5Vcc
Wire Wire Line
	4500 3900 4750 3900
NoConn ~ 4750 4100
NoConn ~ 4750 4300
NoConn ~ 4750 4500
$Comp
L power:GND #PWR014
U 1 1 60BE546E
P 5050 4900
F 0 "#PWR014" H 5050 4650 50  0001 C CNN
F 1 "GND" H 5055 4727 50  0000 C CNN
F 2 "" H 5050 4900 50  0001 C CNN
F 3 "" H 5050 4900 50  0001 C CNN
	1    5050 4900
	1    0    0    -1  
$EndComp
$Comp
L power:GND #PWR?
U 1 1 60BE5DDD
P 5150 4900
AR Path="/60BB05C3/60BE5DDD" Ref="#PWR?"  Part="1" 
AR Path="/60BB073F/60BE5DDD" Ref="#PWR015"  Part="1" 
F 0 "#PWR015" H 5150 4650 50  0001 C CNN
F 1 "GND" H 5155 4727 50  0000 C CNN
F 2 "" H 5150 4900 50  0001 C CNN
F 3 "" H 5150 4900 50  0001 C CNN
	1    5150 4900
	1    0    0    -1  
$EndComp
$Comp
L power:GND #PWR?
U 1 1 60BE5FE8
P 5350 4900
AR Path="/60BB05C3/60BE5FE8" Ref="#PWR?"  Part="1" 
AR Path="/60BB073F/60BE5FE8" Ref="#PWR016"  Part="1" 
F 0 "#PWR016" H 5350 4650 50  0001 C CNN
F 1 "GND" H 5355 4727 50  0000 C CNN
F 2 "" H 5350 4900 50  0001 C CNN
F 3 "" H 5350 4900 50  0001 C CNN
	1    5350 4900
	1    0    0    -1  
$EndComp
$Comp
L power:GND #PWR?
U 1 1 60BE6319
P 5450 4900
AR Path="/60BB05C3/60BE6319" Ref="#PWR?"  Part="1" 
AR Path="/60BB073F/60BE6319" Ref="#PWR017"  Part="1" 
F 0 "#PWR017" H 5450 4650 50  0001 C CNN
F 1 "GND" H 5455 4727 50  0000 C CNN
F 2 "" H 5450 4900 50  0001 C CNN
F 3 "" H 5450 4900 50  0001 C CNN
	1    5450 4900
	1    0    0    -1  
$EndComp
NoConn ~ 5750 4100
NoConn ~ 5750 4300
Text GLabel 5450 3100 2    50   Input ~ 10
5Vcc
Text GLabel 4950 3100 0    50   Input ~ 10
5Vcc
Wire Wire Line
	5350 3100 5450 3100
Wire Wire Line
	5150 3100 4950 3100
Text GLabel 4650 3500 0    50   Input ~ 10
GPIO_17
Text GLabel 4650 3700 0    50   Input ~ 10
GPIO_22
Wire Wire Line
	4750 3500 4650 3500
Wire Wire Line
	4750 3700 4650 3700
$Comp
L Driver_Motor:L293D U2
U 1 1 60BE13F1
P 5250 4100
F 0 "U2" H 5250 5281 50  0000 C CNN
F 1 "L293D" H 5250 5190 50  0000 C CNN
F 2 "Package_DIP:DIP-16_W7.62mm" H 5500 3350 50  0001 L CNN
F 3 "http://www.ti.com/lit/ds/symlink/l293.pdf" H 4950 4800 50  0001 C CNN
	1    5250 4100
	1    0    0    -1  
$EndComp
Text Label 6250 3500 0    50   ~ 10
Motor_Out_1
Text Label 6250 3700 0    50   ~ 10
Motor_Out_2
Wire Wire Line
	5750 3500 6000 3500
Wire Wire Line
	5750 3700 6000 3700
Connection ~ 6000 3500
Wire Wire Line
	6000 3500 6250 3500
Wire Wire Line
	6000 3800 6000 3700
Connection ~ 6000 3700
Wire Wire Line
	6000 3700 6250 3700
Text HLabel 6000 3800 3    50   Input ~ 10
Motor_Status_Led_2
Text HLabel 6000 3400 1    50   Input ~ 10
Motor_Status_Led_1
Wire Wire Line
	6000 3400 6000 3500
$EndSCHEMATC
