# AvrDude-Test-Commands

```shell
pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ ./upload
bash: ./upload: No such file or directory
pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ ./uploade
bash: ./uploade: No such file or directory
pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ ./upload.sh 
 --MajorTask@UploadingCode : Uploading Hex file
[sudo] password for pavl:             
avrdude: ser_open(): can't open device "/dev/ttyUSB0": No such file or directory

avrdude done.  Thank you.


avrdude: no programmer has been specified on the command line or the config file
         Specify a programmer using the -c option and try again

 --MajorTask@UploadingCode : Task finished.

pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ ./upload.sh 
 --MajorTask@UploadingCode : Uploading Hex file
avrdude: invalid baud rate specified '-P/dev/ttyUSB0'

avrdude: no programmer has been specified on the command line or the config file
         Specify a programmer using the -c option and try again

 --MajorTask@UploadingCode : Task finished.

pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ ./upload.sh 
 --MajorTask@UploadingCode : Uploading Hex file
avrdude: AVR Part "-B" not found.

Valid parts are:
  uc3a0512 = AT32UC3A0512
  c128     = AT90CAN128
  c32      = AT90CAN32
  c64      = AT90CAN64
  pwm2     = AT90PWM2
  pwm216   = AT90PWM216
  pwm2b    = AT90PWM2B
  pwm3     = AT90PWM3
  pwm316   = AT90PWM316
  pwm3b    = AT90PWM3B
  1200     = AT90S1200
  2313     = AT90S2313
  2333     = AT90S2333
  2343     = AT90S2343
  4414     = AT90S4414
  4433     = AT90S4433
  4434     = AT90S4434
  8515     = AT90S8515
  8535     = AT90S8535
  usb1286  = AT90USB1286
  usb1287  = AT90USB1287
  usb162   = AT90USB162
  usb646   = AT90USB646
  usb647   = AT90USB647
  usb82    = AT90USB82
  m103     = ATmega103
  m128     = ATmega128
  m1280    = ATmega1280
  m1281    = ATmega1281
  m1284    = ATmega1284
  m1284p   = ATmega1284P
  m1284rfr2 = ATmega1284RFR2
  m128rfa1 = ATmega128RFA1
  m128rfr2 = ATmega128RFR2
  m16      = ATmega16
  m161     = ATmega161
  m162     = ATmega162
  m163     = ATmega163
  m164p    = ATmega164P
  m168     = ATmega168
  m168p    = ATmega168P
  m168pb   = ATmega168PB
  m169     = ATmega169
  m16u2    = ATmega16U2
  m2560    = ATmega2560
  m2561    = ATmega2561
  m2564rfr2 = ATmega2564RFR2
  m256rfr2 = ATmega256RFR2
  m32      = ATmega32
  m324p    = ATmega324P
  m324pa   = ATmega324PA
  m325     = ATmega325
  m3250    = ATmega3250
  m328     = ATmega328
  m328p    = ATmega328P
  m329     = ATmega329
  m3290    = ATmega3290
  m3290p   = ATmega3290P
  m329p    = ATmega329P
  m32m1    = ATmega32M1
  m32u2    = ATmega32U2
  m32u4    = ATmega32U4
  m406     = ATMEGA406
  m48      = ATmega48
  m48p     = ATmega48P
  m48pb    = ATmega48PB
  m64      = ATmega64
  m640     = ATmega640
  m644     = ATmega644
  m644p    = ATmega644P
  m644rfr2 = ATmega644RFR2
  m645     = ATmega645
  m6450    = ATmega6450
  m649     = ATmega649
  m6490    = ATmega6490
  m64rfr2  = ATmega64RFR2
  m8       = ATmega8
  m8515    = ATmega8515
  m8535    = ATmega8535
  m88      = ATmega88
  m88p     = ATmega88P
  m88pb    = ATmega88PB
  m8u2     = ATmega8U2
  t10      = ATtiny10
  t11      = ATtiny11
  t12      = ATtiny12
  t13      = ATtiny13
  t15      = ATtiny15
  t1634    = ATtiny1634
  t20      = ATtiny20
  t2313    = ATtiny2313
  t24      = ATtiny24
  t25      = ATtiny25
  t26      = ATtiny26
  t261     = ATtiny261
  t28      = ATtiny28
  t4       = ATtiny4
  t40      = ATtiny40
  t4313    = ATtiny4313
  t43u     = ATtiny43u
  t44      = ATtiny44
  t441     = ATtiny441
  t45      = ATtiny45
  t461     = ATtiny461
  t5       = ATtiny5
  t84      = ATtiny84
  t841     = ATtiny841
  t85      = ATtiny85
  t861     = ATtiny861
  t88      = ATtiny88
  t9       = ATtiny9
  x128a1   = ATxmega128A1
  x128a1d  = ATxmega128A1revD
  x128a1u  = ATxmega128A1U
  x128a3   = ATxmega128A3
  x128a3u  = ATxmega128A3U
  x128a4   = ATxmega128A4
  x128a4u  = ATxmega128A4U
  x128b1   = ATxmega128B1
  x128b3   = ATxmega128B3
  x128c3   = ATxmega128C3
  x128d3   = ATxmega128D3
  x128d4   = ATxmega128D4
  x16a4    = ATxmega16A4
  x16a4u   = ATxmega16A4U
  x16c4    = ATxmega16C4
  x16d4    = ATxmega16D4
  x16e5    = ATxmega16E5
  x192a1   = ATxmega192A1
  x192a3   = ATxmega192A3
  x192a3u  = ATxmega192A3U
  x192c3   = ATxmega192C3
  x192d3   = ATxmega192D3
  x256a1   = ATxmega256A1
  x256a3   = ATxmega256A3
  x256a3b  = ATxmega256A3B
  x256a3bu = ATxmega256A3BU
  x256a3u  = ATxmega256A3U
  x256c3   = ATxmega256C3
  x256d3   = ATxmega256D3
  x32a4    = ATxmega32A4
  x32a4u   = ATxmega32A4U
  x32c4    = ATxmega32C4
  x32d4    = ATxmega32D4
  x32e5    = ATxmega32E5
  x384c3   = ATxmega384C3
  x384d3   = ATxmega384D3
  x64a1    = ATxmega64A1
  x64a1u   = ATxmega64A1U
  x64a3    = ATxmega64A3
  x64a3u   = ATxmega64A3U
  x64a4    = ATxmega64A4
  x64a4u   = ATxmega64A4U
  x64b1    = ATxmega64B1
  x64b3    = ATxmega64B3
  x64c3    = ATxmega64C3
  x64d3    = ATxmega64D3
  x64d4    = ATxmega64D4
  x8e5     = ATxmega8E5
  ucr2     = deprecated, use 'uc3a0512'


avrdude: no programmer has been specified on the command line or the config file
         Specify a programmer using the -c option and try again

 --MajorTask@UploadingCode : Task finished.

pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ ./upload.sh 
 --MajorTask@UploadingCode : Uploading Hex file

avrdude: set SCK frequency to 750000 Hz
avrdude: warning: cannot set sck period. please check for usbasp firmware update.
avrdude: error: program enable: target doesn't answer. 1 
avrdude: initialization failed, rc=-1
         Double check connections and try again, or use -F to override
         this check.


avrdude done.  Thank you.


avrdude: no programmer has been specified on the command line or the config file
         Specify a programmer using the -c option and try again

 --MajorTask@UploadingCode : Task finished.

pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ ./upload.sh 
 --MajorTask@UploadingCode : Uploading Hex file

avrdude: set SCK frequency to 750000 Hz
avrdude: error: program enable: target doesn't answer. 1 
avrdude: initialization failed, rc=-1
         Double check connections and try again, or use -F to override
         this check.


avrdude done.  Thank you.


avrdude: no programmer has been specified on the command line or the config file
         Specify a programmer using the -c option and try again

 --MajorTask@UploadingCode : Task finished.

pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ ./upload.sh 
 --MajorTask@UploadingCode : Uploading Hex file

avrdude: set SCK frequency to 750000 Hz
avrdude: error: program enable: target doesn't answer. 1 
avrdude: initialization failed, rc=-1
         Double check connections and try again, or use -F to override
         this check.


avrdude done.  Thank you.


avrdude: no programmer has been specified on the command line or the config file
         Specify a programmer using the -c option and try again

 --MajorTask@UploadingCode : Task finished.

pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ ./upload.sh 
 --MajorTask@UploadingCode : Uploading Hex file

avrdude: set SCK frequency to 750000 Hz
avrdude: error: program enable: target doesn't answer. 1 
avrdude: initialization failed, rc=-1
         Double check connections and try again, or use -F to override
         this check.


avrdude done.  Thank you.


avrdude: no programmer has been specified on the command line or the config file
         Specify a programmer using the -c option and try again

 --MajorTask@UploadingCode : Task finished.

pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ ./upload.sh 
 --MajorTask@UploadingCode : Uploading Hex file

avrdude: set SCK frequency to 750000 Hz
avrdude: error: program enable: target doesn't answer. 1 
avrdude: initialization failed, rc=-1
         Double check connections and try again, or use -F to override
         this check.


avrdude done.  Thank you.


avrdude: no programmer has been specified on the command line or the config file
         Specify a programmer using the -c option and try again

 --MajorTask@UploadingCode : Task finished.

pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ ./upload.sh 
 --MajorTask@UploadingCode : Uploading Hex file

avrdude: set SCK frequency to 750000 Hz
avrdude: error: program enable: target doesn't answer. 1 
avrdude: initialization failed, rc=-1
         Double check connections and try again, or use -F to override
         this check.


avrdude done.  Thank you.


avrdude: no programmer has been specified on the command line or the config file
         Specify a programmer using the -c option and try again

 --MajorTask@UploadingCode : Task finished.

pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ ./upload.sh 
 --MajorTask@UploadingCode : Uploading Hex file

avrdude: set SCK frequency to 187500 Hz
avrdude: error: program enable: target doesn't answer. 1 
avrdude: initialization failed, rc=-1
         Double check connections and try again, or use -F to override
         this check.


avrdude done.  Thank you.


avrdude: no programmer has been specified on the command line or the config file
         Specify a programmer using the -c option and try again

 --MajorTask@UploadingCode : Task finished.

pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ ./upload.sh 
 --MajorTask@UploadingCode : Uploading Hex file

avrdude: set SCK frequency to 750000 Hz
avrdude: error: program enable: target doesn't answer. 1 
avrdude: initialization failed, rc=-1
         Double check connections and try again, or use -F to override
         this check.


avrdude done.  Thank you.


avrdude: no programmer has been specified on the command line or the config file
         Specify a programmer using the -c option and try again

 --MajorTask@UploadingCode : Task finished.

pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ ./upload.sh 
 --MajorTask@UploadingCode : Uploading Hex file

avrdude: set SCK frequency to 750000 Hz
avrdude: AVR device initialized and ready to accept instructions

Reading | ################################################## | 100% 0.00s

avrdude: Device signature = 0x1e9307 (probably m8)
avrdude: NOTE: "flash" memory has been specified, an erase cycle will be performed
         To disable this feature, specify the -D option.
avrdude: erasing chip
avrdude: set SCK frequency to 750000 Hz
avrdude: reading input file "/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/output/libHelloAvr.hex"
avrdude: input file /home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/output/libHelloAvr.hex auto detected as Intel Hex
avrdude: writing flash (4700 bytes):

Writing | ################################################## | 100% 1.75s

avrdude: 4700 bytes of flash written
avrdude: verifying flash memory against /home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/output/libHelloAvr.hex:
avrdude: load data flash data from input file /home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/output/libHelloAvr.hex:
avrdude: input file /home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/output/libHelloAvr.hex auto detected as Intel Hex
avrdude: input file /home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/output/libHelloAvr.hex contains 4700 bytes
avrdude: reading on-chip flash data:

Reading | ################################################## | 100% 0.96s

avrdude: verifying ...
avrdude: 4700 bytes of flash verified

avrdude: safemode: Fuses OK (E:FF, H:D9, L:9F)

avrdude done.  Thank you.


avrdude: no programmer has been specified on the command line or the config file
         Specify a programmer using the -c option and try again

 --MajorTask@UploadingCode : Task finished.

pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ ./upload.sh 
 --MajorTask@UploadingCode : Uploading Hex file

avrdude: set SCK frequency to 750000 Hz
avrdude: error: program enable: target doesn't answer. 1 
avrdude: initialization failed, rc=-1
         Double check connections and try again, or use -F to override
         this check.


avrdude done.  Thank you.


avrdude: no programmer has been specified on the command line or the config file
         Specify a programmer using the -c option and try again

 --MajorTask@UploadingCode : Task finished.

pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ ./upload.sh 
 --MajorTask@UploadingCode : Uploading Hex file

avrdude: set SCK frequency to 750000 Hz
avrdude: error: program enable: target doesn't answer. 1 
avrdude: initialization failed, rc=-1
         Double check connections and try again, or use -F to override
         this check.


avrdude done.  Thank you.


avrdude: no programmer has been specified on the command line or the config file
         Specify a programmer using the -c option and try again

 --MajorTask@UploadingCode : Task finished.

pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ ./upload.sh 
 --MajorTask@UploadingCode : Uploading Hex file

avrdude: set SCK frequency to 750000 Hz
avrdude: error: program enable: target doesn't answer. 1 
avrdude: initialization failed, rc=-1
         Double check connections and try again, or use -F to override
         this check.


avrdude done.  Thank you.


avrdude: no programmer has been specified on the command line or the config file
         Specify a programmer using the -c option and try again

 --MajorTask@UploadingCode : Task finished.

pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ ./upload.sh 
 --MajorTask@UploadingCode : Uploading Hex file

avrdude: set SCK frequency to 750000 Hz
avrdude: error: program enable: target doesn't answer. 1 
avrdude: initialization failed, rc=-1
         Double check connections and try again, or use -F to override
         this check.


avrdude done.  Thank you.


avrdude: no programmer has been specified on the command line or the config file
         Specify a programmer using the -c option and try again

 --MajorTask@UploadingCode : Task finished.

pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ 
pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ ./upload.sh 
 --MajorTask@UploadingCode : Uploading Hex file

avrdude: set SCK frequency to 750000 Hz
avrdude: error: program enable: target doesn't answer. 1 
avrdude: initialization failed, rc=-1
         Double check connections and try again, or use -F to override
         this check.


avrdude done.  Thank you.


avrdude: no programmer has been specified on the command line or the config file
         Specify a programmer using the -c option and try again

 --MajorTask@UploadingCode : Task finished.

pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ ./upload.sh 
 --MajorTask@UploadingCode : Uploading Hex file

avrdude: set SCK frequency to 750000 Hz
avrdude: error: program enable: target doesn't answer. 1 
avrdude: initialization failed, rc=-1
         Double check connections and try again, or use -F to override
         this check.


avrdude done.  Thank you.


avrdude: no programmer has been specified on the command line or the config file
         Specify a programmer using the -c option and try again

 --MajorTask@UploadingCode : Task finished.

pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ ./upload.sh 
 --MajorTask@UploadingCode : Uploading Hex file

avrdude: set SCK frequency to 750000 Hz
avrdude: error: program enable: target doesn't answer. 1 
avrdude: initialization failed, rc=-1
         Double check connections and try again, or use -F to override
         this check.


avrdude done.  Thank you.


avrdude: no programmer has been specified on the command line or the config file
         Specify a programmer using the -c option and try again

 --MajorTask@UploadingCode : Task finished.

pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ ./upload.sh 
 --MajorTask@UploadingCode : Uploading Hex file

avrdude: set SCK frequency to 750000 Hz
avrdude: error: program enable: target doesn't answer. 1 
avrdude: initialization failed, rc=-1
         Double check connections and try again, or use -F to override
         this check.


avrdude done.  Thank you.


avrdude: no programmer has been specified on the command line or the config file
         Specify a programmer using the -c option and try again

 --MajorTask@UploadingCode : Task finished.

pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ ./upload.sh 
 --MajorTask@UploadingCode : Uploading Hex file

avrdude: set SCK frequency to 750000 Hz
avrdude: error: program enable: target doesn't answer. 1 
avrdude: initialization failed, rc=-1
         Double check connections and try again, or use -F to override
         this check.


avrdude done.  Thank you.


avrdude: no programmer has been specified on the command line or the config file
         Specify a programmer using the -c option and try again

 --MajorTask@UploadingCode : Task finished.

pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ 
pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ ./upload.sh 
 --MajorTask@UploadingCode : Uploading Hex file
avrdude: error: could not find USB device with vid=0x16c0 pid=0x5dc vendor='www.fischl.de' product='USBasp'

avrdude done.  Thank you.


avrdude: no programmer has been specified on the command line or the config file
         Specify a programmer using the -c option and try again

 --MajorTask@UploadingCode : Task finished.

pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ 
pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ ./upload.sh 
 --MajorTask@UploadingCode : Uploading Hex file

avrdude: set SCK frequency to 750000 Hz
avrdude: error: program enable: target doesn't answer. 1 
avrdude: initialization failed, rc=-1
         Double check connections and try again, or use -F to override
         this check.


avrdude done.  Thank you.


avrdude: no programmer has been specified on the command line or the config file
         Specify a programmer using the -c option and try again

 --MajorTask@UploadingCode : Task finished.

pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ ./upload.sh 
 --MajorTask@UploadingCode : Uploading Hex file

avrdude: set SCK frequency to 750000 Hz
avrdude: error: program enable: target doesn't answer. 1 
avrdude: initialization failed, rc=-1
         Double check connections and try again, or use -F to override
         this check.


avrdude done.  Thank you.


avrdude: no programmer has been specified on the command line or the config file
         Specify a programmer using the -c option and try again

 --MajorTask@UploadingCode : Task finished.

pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ ./upload.sh 
 --MajorTask@UploadingCode : Uploading Hex file

avrdude: set SCK frequency to 750000 Hz
avrdude: error: program enable: target doesn't answer. 1 
avrdude: initialization failed, rc=-1
         Double check connections and try again, or use -F to override
         this check.


avrdude done.  Thank you.


avrdude: no programmer has been specified on the command line or the config file
         Specify a programmer using the -c option and try again

 --MajorTask@UploadingCode : Task finished.

pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ ./upload.sh 
 --MajorTask@UploadingCode : Uploading Hex file

avrdude: set SCK frequency to 750000 Hz
avrdude: error: program enable: target doesn't answer. 1 
avrdude: initialization failed, rc=-1
         Double check connections and try again, or use -F to override
         this check.


avrdude done.  Thank you.


avrdude: no programmer has been specified on the command line or the config file
         Specify a programmer using the -c option and try again

 --MajorTask@UploadingCode : Task finished.

pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ ./upload
bash: ./upload: No such file or directory
pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ ./upload
bash: ./upload: No such file or directory
pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ ./upload
bash: ./upload: No such file or directory
pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ ./upload.sh 
 --MajorTask@UploadingCode : Uploading Hex file

avrdude: set SCK frequency to 750000 Hz
avrdude: error: program enable: target doesn't answer. 1 
avrdude: initialization failed, rc=-1
         Double check connections and try again, or use -F to override
         this check.


avrdude done.  Thank you.


avrdude: no programmer has been specified on the command line or the config file
         Specify a programmer using the -c option and try again

 --MajorTask@UploadingCode : Task finished.

pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ ./upload.sh 
 --MajorTask@UploadingCode : Uploading Hex file

avrdude: set SCK frequency to 750000 Hz
avrdude: error: program enable: target doesn't answer. 1 
avrdude: initialization failed, rc=-1
         Double check connections and try again, or use -F to override
         this check.


avrdude done.  Thank you.


avrdude: no programmer has been specified on the command line or the config file
         Specify a programmer using the -c option and try again

 --MajorTask@UploadingCode : Task finished.

pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ ./upload.sh 
 --MajorTask@UploadingCode : Uploading Hex file

avrdude: set SCK frequency to 750000 Hz
avrdude: error: program enable: target doesn't answer. 1 
avrdude: initialization failed, rc=-1
         Double check connections and try again, or use -F to override
         this check.


avrdude done.  Thank you.


avrdude: no programmer has been specified on the command line or the config file
         Specify a programmer using the -c option and try again

 --MajorTask@UploadingCode : Task finished.

pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ ./upload.sh 
 --MajorTask@UploadingCode : Uploading Hex file

avrdude: set SCK frequency to 750000 Hz
avrdude: error: program enable: target doesn't answer. 1 
avrdude: initialization failed, rc=-1
         Double check connections and try again, or use -F to override
         this check.


avrdude done.  Thank you.


avrdude: no programmer has been specified on the command line or the config file
         Specify a programmer using the -c option and try again

 --MajorTask@UploadingCode : Task finished.

pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ ./upload.sh 
 --MajorTask@UploadingCode : Uploading Hex file

avrdude: set SCK frequency to 750000 Hz
avrdude: error: program enable: target doesn't answer. 1 
avrdude: initialization failed, rc=-1
         Double check connections and try again, or use -F to override
         this check.


avrdude done.  Thank you.


avrdude: no programmer has been specified on the command line or the config file
         Specify a programmer using the -c option and try again

 --MajorTask@UploadingCode : Task finished.

pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ ./upload.sh 
 --MajorTask@UploadingCode : Uploading Hex file

avrdude: set SCK frequency to 750000 Hz
avrdude: error: program enable: target doesn't answer. 1 
avrdude: initialization failed, rc=-1
         Double check connections and try again, or use -F to override
         this check.


avrdude done.  Thank you.


avrdude: no programmer has been specified on the command line or the config file
         Specify a programmer using the -c option and try again

 --MajorTask@UploadingCode : Task finished.

pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ 
pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ ./upload.sh 
 --MajorTask@UploadingCode : Uploading Hex file

avrdude: set SCK frequency to 750000 Hz
avrdude: error: program enable: target doesn't answer. 1 
avrdude: initialization failed, rc=-1
         Double check connections and try again, or use -F to override
         this check.


avrdude done.  Thank you.


avrdude: no programmer has been specified on the command line or the config file
         Specify a programmer using the -c option and try again

 --MajorTask@UploadingCode : Task finished.

pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ 
pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ ./upload.sh 
 --MajorTask@UploadingCode : Uploading Hex file

avrdude: set SCK frequency to 750000 Hz
avrdude: error: program enable: target doesn't answer. 1 
avrdude: initialization failed, rc=-1
         Double check connections and try again, or use -F to override
         this check.


avrdude done.  Thank you.


avrdude: no programmer has been specified on the command line or the config file
         Specify a programmer using the -c option and try again

 --MajorTask@UploadingCode : Task finished.

pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ ./upload.sh 
 --MajorTask@UploadingCode : Uploading Hex file

avrdude: set SCK frequency to 750000 Hz
avrdude: error: program enable: target doesn't answer. 1 
avrdude: initialization failed, rc=-1
         Double check connections and try again, or use -F to override
         this check.


avrdude done.  Thank you.


avrdude: no programmer has been specified on the command line or the config file
         Specify a programmer using the -c option and try again

 --MajorTask@UploadingCode : Task finished.

pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ ./upload.sh 
 --MajorTask@UploadingCode : Uploading Hex file

avrdude: set SCK frequency to 750000 Hz
avrdude: error: program enable: target doesn't answer. 1 
avrdude: initialization failed, rc=-1
         Double check connections and try again, or use -F to override
         this check.


avrdude done.  Thank you.


avrdude: no programmer has been specified on the command line or the config file
         Specify a programmer using the -c option and try again

 --MajorTask@UploadingCode : Task finished.

pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ ./upload.sh 
 --MajorTask@UploadingCode : Uploading Hex file

avrdude: set SCK frequency to 750000 Hz
avrdude: error: program enable: target doesn't answer. 1 
avrdude: initialization failed, rc=-1
         Double check connections and try again, or use -F to override
         this check.


avrdude done.  Thank you.


avrdude: no programmer has been specified on the command line or the config file
         Specify a programmer using the -c option and try again

 --MajorTask@UploadingCode : Task finished.

pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ ./upload.sh 
 --MajorTask@UploadingCode : Uploading Hex file

avrdude: set SCK frequency to 750000 Hz
avrdude: error: program enable: target doesn't answer. 1 
avrdude: initialization failed, rc=-1
         Double check connections and try again, or use -F to override
         this check.


avrdude done.  Thank you.


avrdude: no programmer has been specified on the command line or the config file
         Specify a programmer using the -c option and try again

 --MajorTask@UploadingCode : Task finished.

pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ ./upload.sh 
 --MajorTask@UploadingCode : Uploading Hex file

avrdude: set SCK frequency to 750000 Hz
avrdude: error: program enable: target doesn't answer. 1 
avrdude: initialization failed, rc=-1
         Double check connections and try again, or use -F to override
         this check.


avrdude done.  Thank you.


avrdude: no programmer has been specified on the command line or the config file
         Specify a programmer using the -c option and try again

 --MajorTask@UploadingCode : Task finished.

pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ ./upload.sh 
 --MajorTask@UploadingCode : Uploading Hex file

avrdude: error: program enable: target doesn't answer. 1 
avrdude: initialization failed, rc=-1
         Double check connections and try again, or use -F to override
         this check.


avrdude done.  Thank you.


avrdude: no programmer has been specified on the command line or the config file
         Specify a programmer using the -c option and try again

 --MajorTask@UploadingCode : Task finished.

pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ ./upload.sh 
 --MajorTask@UploadingCode : Uploading Hex file

avrdude: error: program enable: target doesn't answer. 1 
avrdude: initialization failed, rc=-1
         Double check connections and try again, or use -F to override
         this check.


avrdude done.  Thank you.


avrdude: no programmer has been specified on the command line or the config file
         Specify a programmer using the -c option and try again

 --MajorTask@UploadingCode : Task finished.

pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ ./upload.sh 
 --MajorTask@UploadingCode : Uploading Hex file

avrdude: set SCK frequency to 750000 Hz
avrdude: error: program enable: target doesn't answer. 1 
avrdude: initialization failed, rc=-1
         Double check connections and try again, or use -F to override
         this check.


avrdude done.  Thank you.


avrdude: set SCK frequency to 750000 Hz
avrdude: error: program enable: target doesn't answer. 1 
avrdude: initialization failed, rc=-1
         Double check connections and try again, or use -F to override
         this check.


avrdude done.  Thank you.

 --MajorTask@UploadingCode : Task finished.

pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ ./upload.sh 
 --MajorTask@UploadingCode : Uploading Hex file
[sudo] password for pavl:             

avrdude: set SCK frequency to 750000 Hz
avrdude: error: program enable: target doesn't answer. 1 
avrdude: initialization failed, rc=-1
         Double check connections and try again, or use -F to override
         this check.


avrdude done.  Thank you.


avrdude: set SCK frequency to 750000 Hz
avrdude: error: program enable: target doesn't answer. 1 
avrdude: initialization failed, rc=-1
         Double check connections and try again, or use -F to override
         this check.


avrdude done.  Thank you.

 --MajorTask@UploadingCode : Task finished.

pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ 
pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ ./upload.sh 
 --MajorTask@UploadingCode : Uploading Hex file

avrdude: set SCK frequency to 750000 Hz
avrdude: error: program enable: target doesn't answer. 1 
avrdude: initialization failed, rc=-1
         Double check connections and try again, or use -F to override
         this check.


avrdude done.  Thank you.


avrdude: set SCK frequency to 750000 Hz
avrdude: error: program enable: target doesn't answer. 1 
avrdude: initialization failed, rc=-1
         Double check connections and try again, or use -F to override
         this check.


avrdude done.  Thank you.

 --MajorTask@UploadingCode : Task finished.

pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ ./upload.sh 
 --MajorTask@UploadingCode : Uploading Hex file

avrdude: set SCK frequency to 750000 Hz
avrdude: error: program enable: target doesn't answer. 1 
avrdude: initialization failed, rc=-1
         Double check connections and try again, or use -F to override
         this check.


avrdude done.  Thank you.


avrdude: set SCK frequency to 750000 Hz
avrdude: error: program enable: target doesn't answer. 1 
avrdude: initialization failed, rc=-1
         Double check connections and try again, or use -F to override
         this check.


avrdude done.  Thank you.

 --MajorTask@UploadingCode : Task finished.

pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ ./upload.sh 
 --MajorTask@UploadingCode : Uploading Hex file

avrdude: set SCK frequency to 750000 Hz
avrdude: error: program enable: target doesn't answer. 1 
avrdude: initialization failed, rc=-1
avrdude: AVR device initialized and ready to accept instructions
avrdude: Device signature = 0x000000 (retrying)
avrdude: Device signature = 0x000000 (retrying)
avrdude: Device signature = 0x000000
avrdude: Yikes!  Invalid device signature.
avrdude: Expected signature for ATmega8 is 1E 93 07
avrdude: NOTE: "flash" memory has been specified, an erase cycle will be performed
         To disable this feature, specify the -D option.

avrdude done.  Thank you.


avrdude: set SCK frequency to 750000 Hz
avrdude: error: program enable: target doesn't answer. 1 
avrdude: initialization failed, rc=-1
avrdude: AVR device initialized and ready to accept instructions
avrdude: Device signature = 0x1006e1
avrdude: Expected signature for ATmega8 is 1E 93 07

avrdude done.  Thank you.

 --MajorTask@UploadingCode : Task finished.

pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ ./upload.sh 
 --MajorTask@UploadingCode : Uploading Hex file

avrdude: set SCK frequency to 750000 Hz
avrdude: error: program enable: target doesn't answer. 1 
avrdude: initialization failed, rc=-1
avrdude: AVR device initialized and ready to accept instructions
avrdude: Device signature = 0x000000 (retrying)
avrdude: Device signature = 0x000000 (retrying)
avrdude: Device signature = 0x000000
avrdude: Yikes!  Invalid device signature.
avrdude: Expected signature for ATmega8 is 1E 93 07
avrdude: NOTE: "flash" memory has been specified, an erase cycle will be performed
         To disable this feature, specify the -D option.

avrdude done.  Thank you.


avrdude: set SCK frequency to 750000 Hz
avrdude: error: program enable: target doesn't answer. 1 
avrdude: initialization failed, rc=-1
avrdude: AVR device initialized and ready to accept instructions
avrdude: Device signature = 0x1016e0
avrdude: Expected signature for ATmega8 is 1E 93 07

avrdude done.  Thank you.

 --MajorTask@UploadingCode : Task finished.

pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ ./upload.sh 
 --MajorTask@UploadingCode : Uploading Hex file

avrdude: set SCK frequency to 750000 Hz
avrdude: error: program enable: target doesn't answer. 1 
avrdude: initialization failed, rc=-1
avrdude: AVR device initialized and ready to accept instructions
avrdude: Device signature = 0x000000 (retrying)
avrdude: Device signature = 0x000000 (retrying)
avrdude: Device signature = 0x000000
avrdude: Yikes!  Invalid device signature.
avrdude: Expected signature for ATmega8 is 1E 93 07
avrdude: NOTE: "flash" memory has been specified, an erase cycle will be performed
         To disable this feature, specify the -D option.

avrdude done.  Thank you.


avrdude: set SCK frequency to 750000 Hz
avrdude: error: program enable: target doesn't answer. 1 
avrdude: initialization failed, rc=-1
avrdude: AVR device initialized and ready to accept instructions
avrdude: Device signature = 0x10d6ea
avrdude: Expected signature for ATmega8 is 1E 93 07

avrdude done.  Thank you.

 --MajorTask@UploadingCode : Task finished.

pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ ./upload.sh 
 --MajorTask@UploadingCode : Uploading Hex file

avrdude: set SCK frequency to 750000 Hz
avrdude: error: program enable: target doesn't answer. 1 
avrdude: initialization failed, rc=-1
avrdude: AVR device initialized and ready to accept instructions
avrdude: Device signature = 0x000000 (retrying)
avrdude: Device signature = 0x000000 (retrying)
avrdude: Device signature = 0x000000
avrdude: Yikes!  Invalid device signature.
avrdude: Expected signature for ATmega8 is 1E 93 07
avrdude: NOTE: "flash" memory has been specified, an erase cycle will be performed
         To disable this feature, specify the -D option.

avrdude done.  Thank you.


avrdude: set SCK frequency to 750000 Hz
avrdude: error: program enable: target doesn't answer. 1 
avrdude: initialization failed, rc=-1
avrdude: AVR device initialized and ready to accept instructions
avrdude: Device signature = 0x10b6a5
avrdude: Expected signature for ATmega8 is 1E 93 07

avrdude done.  Thank you.

 --MajorTask@UploadingCode : Task finished.

pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ ./upload.sh 
 --MajorTask@UploadingCode : Uploading Hex file

avrdude: set SCK frequency to 750000 Hz
avrdude: error: program enable: target doesn't answer. 1 
avrdude: initialization failed, rc=-1
avrdude: AVR device initialized and ready to accept instructions
avrdude: Device signature = 0x000000 (retrying)
avrdude: Device signature = 0x000000 (retrying)
avrdude: Device signature = 0x000000
avrdude: Yikes!  Invalid device signature.
avrdude: Expected signature for ATmega8 is 1E 93 07
avrdude: NOTE: "flash" memory has been specified, an erase cycle will be performed
         To disable this feature, specify the -D option.

avrdude done.  Thank you.


avrdude: set SCK frequency to 750000 Hz
avrdude: error: program enable: target doesn't answer. 1 
avrdude: initialization failed, rc=-1
avrdude: AVR device initialized and ready to accept instructions
avrdude: Device signature = 0x10a63a
avrdude: Expected signature for ATmega8 is 1E 93 07

avrdude done.  Thank you.

 --MajorTask@UploadingCode : Task finished.

pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ ./upload.sh 
 --MajorTask@UploadingCode : Uploading Hex file

avrdude: set SCK frequency to 750000 Hz
avrdude: error: program enable: target doesn't answer. 1 
avrdude: initialization failed, rc=-1
avrdude: AVR device initialized and ready to accept instructions
avrdude: Device signature = 0x000000 (retrying)
avrdude: Device signature = 0x000000 (retrying)
avrdude: Device signature = 0x000000
avrdude: Yikes!  Invalid device signature.
avrdude: Expected signature for ATmega8 is 1E 93 07
avrdude: NOTE: "flash" memory has been specified, an erase cycle will be performed
         To disable this feature, specify the -D option.

avrdude done.  Thank you.


avrdude: set SCK frequency to 750000 Hz
avrdude: error: program enable: target doesn't answer. 1 
avrdude: initialization failed, rc=-1
avrdude: AVR device initialized and ready to accept instructions
avrdude: Device signature = 0x109628
avrdude: Expected signature for ATmega8 is 1E 93 07

avrdude done.  Thank you.

 --MajorTask@UploadingCode : Task finished.

pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ avrdude -p m8 -c usbasp -t

avrdude: error: program enable: target doesn't answer. 1 
avrdude: initialization failed, rc=-1
         Double check connections and try again, or use -F to override
         this check.


avrdude done.  Thank you.

pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ avrdude -p m8 -c usbasp -t

avrdude: error: program enable: target doesn't answer. 1 
avrdude: initialization failed, rc=-1
         Double check connections and try again, or use -F to override
         this check.


avrdude done.  Thank you.

pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ 
pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ avrdude -p m8 -c usbasp -t

avrdude: error: program enable: target doesn't answer. 1 
avrdude: initialization failed, rc=-1
         Double check connections and try again, or use -F to override
         this check.


avrdude done.  Thank you.

pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ avrdude -p m8 -c usbasp -F -t

avrdude: error: program enable: target doesn't answer. 1 
avrdude: initialization failed, rc=-1
avrdude: AVR device initialized and ready to accept instructions
avrdude: Device signature = 0xa0f9c8
avrdude: Expected signature for ATmega8 is 1E 93 07
avrdude> part
>>> part 

AVR Part                      : ATmega8
Chip Erase delay              : 10000 us
PAGEL                         : PD7
BS2                           : PC2
RESET disposition             : dedicated
RETRY pulse                   : SCK
serial program mode           : yes
parallel program mode         : yes
Timeout                       : 200
StabDelay                     : 100
CmdexeDelay                   : 25
SyncLoops                     : 32
ByteDelay                     : 0
PollIndex                     : 3
PollValue                     : 0x53
Memory Detail                 :

                         Block Poll               Page                       Polled
  Memory Type Mode Delay Size  Indx Paged  Size   Size #Pages MinW  MaxW   ReadBack
  ----------- ---- ----- ----- ---- ------ ------ ---- ------ ----- ----- ---------
  eeprom         4    20   128    0 no        512    4      0  9000  9000 0xff 0xff
  flash         33    10    64    0 yes      8192   64    128  4500  4500 0xff 0x00
  lfuse          0     0     0    0 no          1    0      0  2000  2000 0x00 0x00
  hfuse          0     0     0    0 no          1    0      0  2000  2000 0x00 0x00
  lock           0     0     0    0 no          1    0      0  2000  2000 0x00 0x00
  calibration    0     0     0    0 no          4    0      0     0     0 0x00 0x00
  signature      0     0     0    0 no          3    0      0     0     0 0x00 0x00

avrdude> -c usbasp -U hfuse:w:0xC9:m -U lfuse:w:0xEF:m
>>> -c usbasp -U hfuse:w:0xC9:m -U lfuse:w:0xEF:m 
avrdude: invalid command "-c"
avrdude>  -U hfuse:w:0xC9:m -U lfuse:w:0xEF:m
>>> -U hfuse:w:0xC9:m -U lfuse:w:0xEF:m 
avrdude: invalid command "-U"
avrdude> w hfuse 0 0xC9 
>>> w hfuse 0 0xC9 
avrdude (write): error writing 0xc9 at 0x00000, rc=-6
avrdude (write): error writing 0xc9 at 0x00000 cell=0x00

avrdude> w hfuse 0xC9 
>>> w hfuse 0xC9 
Usage: write <memtype> <addr> <byte1> <byte2> ... byteN>
avrdude> w lfuse 0 0xEF
>>> w lfuse 0 0xEF 
avrdude (write): error writing 0xef at 0x00000, rc=-6
avrdude (write): error writing 0xef at 0x00000 cell=0x00

avrdude> dump
>>> dump 
Usage: dump <memtype> [<addr> <len>]
avrdude> dump eeprom 0 128
>>> dump eeprom 0 128 
0000  00 00 00 00 00 00 00 00  00 00 00 00 00 00 00 00  |................|
0010  00 00 00 00 00 00 00 00  00 00 00 00 00 00 00 00  |................|
0020  00 00 00 00 00 00 00 00  00 00 00 00 00 00 00 00  |................|
0030  00 00 00 00 00 00 00 00  00 00 00 00 00 00 00 00  |................|
0040  00 00 00 00 00 00 00 00  00 00 00 00 00 00 00 00  |................|
0050  00 00 00 00 00 00 00 00  00 00 00 00 00 00 00 00  |................|
0060  00 00 00 00 00 00 00 00  00 00 00 00 00 00 00 00  |................|
0070  00 00 00 00 00 00 00 00  00 00 00 00 00 00 00 00  |................|

avrdude> dump eeprom 0 0
>>> dump eeprom 0 0 

avrdude> dump eeprom 0 12
>>> dump eeprom 0 12 
0000  00 00 00 00 00 00 00 00  00 00 00 00              |............    |

avrdude> dump eeprom 0 256
>>> dump eeprom 0 256 
0000  00 00 00 00 00 00 00 00  00 00 00 00 00 00 00 00  |................|
0010  00 00 00 00 00 00 00 00  00 00 00 00 00 00 00 00  |................|
0020  00 00 00 00 00 00 00 00  00 00 00 00 00 00 00 00  |................|
0030  00 00 00 00 00 00 00 00  00 00 00 00 00 00 00 00  |................|
0040  00 00 00 00 00 00 00 00  00 00 00 00 00 00 00 00  |................|
0050  00 00 00 00 00 00 00 00  00 00 00 00 00 00 00 00  |................|
0060  00 00 00 00 00 00 00 00  00 00 00 00 00 00 00 00  |................|
0070  00 00 00 00 00 00 00 00  00 00 00 00 00 00 00 00  |................|
0080  00 00 00 00 00 00 00 00  00 00 00 00 00 00 00 00  |................|
0090  00 00 00 00 00 00 00 00  00 00 00 00 00 00 00 00  |................|
00a0  00 00 00 00 00 00 00 00  00 00 00 00 00 00 00 00  |................|
00b0  00 00 00 00 00 00 00 00  00 00 00 00 00 00 00 00  |................|
00c0  00 00 00 00 00 00 00 00  00 00 00 00 00 00 00 00  |................|
00d0  00 00 00 00 00 00 00 00  00 00 00 00 00 00 00 00  |................|
00e0  00 00 00 00 00 00 00 00  00 00 00 00 00 00 00 00  |................|
00f0  00 00 00 00 00 00 00 00  00 00 00 00 00 00 00 00  |................|

avrdude> write eeprom 0 23
>>> write eeprom 0 23 
avrdude (write): error writing 0x17 at 0x00000, rc=-6
avrdude (write): error writing 0x17 at 0x00000 cell=0x00

avrdude> d lfuse
>>> d lfuse 
0000  00                                                |.               |

avrdude> d hfuse
>>> d hfuse 
0000  00                                                |.               |

avrdude> exit
>>> exit 
avrdude: invalid command "exit"
avrdude> ^C
pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ avrdude -p m328p -c arduino -t
avrdude: ser_open(): can't open device "/dev/ttyS0": Permission denied

avrdude done.  Thank you.

pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ sudo avrdude -p m328p -c arduino -t
[sudo] password for pavl:             
avrdude: ser_open(): can't set attributes for device "/dev/ttyS0": Inappropriate ioctl for device

avrdude done.  Thank you.

pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ sudo avrdude -p m328p -c arduino -t
avrdude: ser_open(): can't set attributes for device "/dev/ttyS0": Inappropriate ioctl for device

avrdude done.  Thank you.

pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ sudo avrdude -p m328p -c arduino -t
avrdude: ser_open(): can't set attributes for device "/dev/ttyS0": Inappropriate ioctl for device

avrdude done.  Thank you.

pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ sudo avrdude -p m328p -c arduino -P'/dev/ttyUSB0' -t
avrdude: stk500_getsync() attempt 1 of 10: not in sync: resp=0x86
avrdude: stk500_getsync() attempt 2 of 10: not in sync: resp=0x98
avrdude: stk500_getsync() attempt 3 of 10: not in sync: resp=0xf8
avrdude: stk500_getsync() attempt 4 of 10: not in sync: resp=0x9e
avrdude: stk500_getsync() attempt 5 of 10: not in sync: resp=0x86
avrdude: stk500_getsync() attempt 6 of 10: not in sync: resp=0x9e
avrdude: stk500_getsync() attempt 7 of 10: not in sync: resp=0x60
avrdude: stk500_getsync() attempt 8 of 10: not in sync: resp=0x1e
avrdude: stk500_getsync() attempt 9 of 10: not in sync: resp=0x78
avrdude: stk500_getsync() attempt 10 of 10: not in sync: resp=0x98

avrdude done.  Thank you.

pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ sudo avrdude -p m328p -c arduino -P'/dev/ttyUSB0' -t
avrdude: stk500_getsync() attempt 1 of 10: not in sync: resp=0x86
avrdude: stk500_getsync() attempt 2 of 10: not in sync: resp=0x98
avrdude: stk500_getsync() attempt 3 of 10: not in sync: resp=0xf8
avrdude: stk500_getsync() attempt 4 of 10: not in sync: resp=0x9e
avrdude: stk500_getsync() attempt 5 of 10: not in sync: resp=0x86
avrdude: stk500_getsync() attempt 6 of 10: not in sync: resp=0x9e
avrdude: stk500_getsync() attempt 7 of 10: not in sync: resp=0x60
avrdude: stk500_getsync() attempt 8 of 10: not in sync: resp=0x1e
avrdude: stk500_getsync() attempt 9 of 10: not in sync: resp=0x78
avrdude: stk500_getsync() attempt 10 of 10: not in sync: resp=0x98

avrdude done.  Thank you.

pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ sudo avrdude -b57600 -p m328p -c arduino -P'/dev/ttyUSB0' -t

avrdude: AVR device initialized and ready to accept instructions

Reading | ################################################## | 100% 0.00s

avrdude: Device signature = 0x1e950f (probably m328p)
avrdude> part
>>> part 

AVR Part                      : ATmega328P
Chip Erase delay              : 9000 us
PAGEL                         : PD7
BS2                           : PC2
RESET disposition             : dedicated
RETRY pulse                   : SCK
serial program mode           : yes
parallel program mode         : yes
Timeout                       : 200
StabDelay                     : 100
CmdexeDelay                   : 25
SyncLoops                     : 32
ByteDelay                     : 0
PollIndex                     : 3
PollValue                     : 0x53
Memory Detail                 :

                         Block Poll               Page                       Polled
  Memory Type Mode Delay Size  Indx Paged  Size   Size #Pages MinW  MaxW   ReadBack
  ----------- ---- ----- ----- ---- ------ ------ ---- ------ ----- ----- ---------
  eeprom        65    20     4    0 no       1024    4      0  3600  3600 0xff 0xff
  flash         65     6   128    0 yes     32768  128    256  4500  4500 0xff 0xff
  lfuse          0     0     0    0 no          1    0      0  4500  4500 0x00 0x00
  hfuse          0     0     0    0 no          1    0      0  4500  4500 0x00 0x00
  efuse          0     0     0    0 no          1    0      0  4500  4500 0x00 0x00
  lock           0     0     0    0 no          1    0      0  4500  4500 0x00 0x00
  calibration    0     0     0    0 no          1    0      0     0     0 0x00 0x00
  signature      0     0     0    0 no          3    0      0     0     0 0x00 0x00

avrdude> d hfuse 0
>>> d hfuse 0 
Usage: dump <memtype> [<addr> <len>]
avrdude> dump hfuse 
>>> dump hfuse 
avrdude: stk500_cmd(): programmer is out of sync
error reading hfuse address 0x00000 of part ATmega328P
read operation not supported on memory type "hfuse"
avrdude> dump efuse 
>>> dump efuse 
avrdude: stk500_cmd(): programmer is out of sync
error reading efuse address 0x00000 of part ATmega328P
read operation not supported on memory type "efuse"
avrdude> dump efuse 0
>>> dump efuse 0 
Usage: dump <memtype> [<addr> <len>]
avrdude> dump efuse 0 0
>>> dump efuse 0 0 

avrdude> dump efuse 0 256
>>> dump efuse 0 256 
avrdude: stk500_cmd(): programmer is out of sync
error reading efuse address 0x00000 of part ATmega328P
read operation not supported on memory type "efuse"
avrdude> d efuse 0 256
>>> d efuse 0 256 
avrdude: stk500_cmd(): programmer is out of sync
error reading efuse address 0x00000 of part ATmega328P
read operation not supported on memory type "efuse"
avrdude> d efuse
>>> d efuse 
avrdude: stk500_cmd(): programmer is out of sync
error reading efuse address 0x00000 of part ATmega328P
read operation not supported on memory type "efuse"
avrdude> d efuse
>>> d efuse 
avrdude: stk500_cmd(): programmer is out of sync
error reading efuse address 0x00000 of part ATmega328P
read operation not supported on memory type "efuse"
avrdude> d hfuse
>>> d hfuse 
avrdude: stk500_cmd(): programmer is out of sync
error reading hfuse address 0x00000 of part ATmega328P
read operation not supported on memory type "hfuse"
avrdude> d hfuse
>>> d hfuse 
avrdude: stk500_cmd(): programmer is out of sync
error reading hfuse address 0x00000 of part ATmega328P
read operation not supported on memory type "hfuse"
avrdude> d hfuse
>>> d hfuse 
avrdude: stk500_cmd(): programmer is out of sync
error reading hfuse address 0x00000 of part ATmega328P
read operation not supported on memory type "hfuse"
avrdude> d hfuse
>>> d hfuse 
avrdude: stk500_cmd(): programmer is out of sync
error reading hfuse address 0x00000 of part ATmega328P
read operation not supported on memory type "hfuse"
avrdude> part
>>> part 

AVR Part                      : ATmega328P
Chip Erase delay              : 9000 us
PAGEL                         : PD7
BS2                           : PC2
RESET disposition             : dedicated
RETRY pulse                   : SCK
serial program mode           : yes
parallel program mode         : yes
Timeout                       : 200
StabDelay                     : 100
CmdexeDelay                   : 25
SyncLoops                     : 32
ByteDelay                     : 0
PollIndex                     : 3
PollValue                     : 0x53
Memory Detail                 :

                         Block Poll               Page                       Polled
  Memory Type Mode Delay Size  Indx Paged  Size   Size #Pages MinW  MaxW   ReadBack
  ----------- ---- ----- ----- ---- ------ ------ ---- ------ ----- ----- ---------
  eeprom        65    20     4    0 no       1024    4      0  3600  3600 0xff 0xff
  flash         65     6   128    0 yes     32768  128    256  4500  4500 0xff 0xff
  lfuse          0     0     0    0 no          1    0      0  4500  4500 0x00 0x00
  hfuse          0     0     0    0 no          1    0      0  4500  4500 0x00 0x00
  efuse          0     0     0    0 no          1    0      0  4500  4500 0x00 0x00
  lock           0     0     0    0 no          1    0      0  4500  4500 0x00 0x00
  calibration    0     0     0    0 no          1    0      0     0     0 0x00 0x00
  signature      0     0     0    0 no          3    0      0     0     0 0x00 0x00

avrdude> part
>>> part 

AVR Part                      : ATmega328P
Chip Erase delay              : 9000 us
PAGEL                         : PD7
BS2                           : PC2
RESET disposition             : dedicated
RETRY pulse                   : SCK
serial program mode           : yes
parallel program mode         : yes
Timeout                       : 200
StabDelay                     : 100
CmdexeDelay                   : 25
SyncLoops                     : 32
ByteDelay                     : 0
PollIndex                     : 3
PollValue                     : 0x53
Memory Detail                 :

                         Block Poll               Page                       Polled
  Memory Type Mode Delay Size  Indx Paged  Size   Size #Pages MinW  MaxW   ReadBack
  ----------- ---- ----- ----- ---- ------ ------ ---- ------ ----- ----- ---------
  eeprom        65    20     4    0 no       1024    4      0  3600  3600 0xff 0xff
  flash         65     6   128    0 yes     32768  128    256  4500  4500 0xff 0xff
  lfuse          0     0     0    0 no          1    0      0  4500  4500 0x00 0x00
  hfuse          0     0     0    0 no          1    0      0  4500  4500 0x00 0x00
  efuse          0     0     0    0 no          1    0      0  4500  4500 0x00 0x00
  lock           0     0     0    0 no          1    0      0  4500  4500 0x00 0x00
  calibration    0     0     0    0 no          1    0      0     0     0 0x00 0x00
  signature      0     0     0    0 no          3    0      0     0     0 0x00 0x00

avrdude> ^C
pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ avrdude -p m8A -c usbasp -F -t
avrdude: AVR Part "m8A" not found.

Valid parts are:
  uc3a0512 = AT32UC3A0512
  c128     = AT90CAN128
  c32      = AT90CAN32
  c64      = AT90CAN64
  pwm2     = AT90PWM2
  pwm216   = AT90PWM216
  pwm2b    = AT90PWM2B
  pwm3     = AT90PWM3
  pwm316   = AT90PWM316
  pwm3b    = AT90PWM3B
  1200     = AT90S1200
  2313     = AT90S2313
  2333     = AT90S2333
  2343     = AT90S2343
  4414     = AT90S4414
  4433     = AT90S4433
  4434     = AT90S4434
  8515     = AT90S8515
  8535     = AT90S8535
  usb1286  = AT90USB1286
  usb1287  = AT90USB1287
  usb162   = AT90USB162
  usb646   = AT90USB646
  usb647   = AT90USB647
  usb82    = AT90USB82
  m103     = ATmega103
  m128     = ATmega128
  m1280    = ATmega1280
  m1281    = ATmega1281
  m1284    = ATmega1284
  m1284p   = ATmega1284P
  m1284rfr2 = ATmega1284RFR2
  m128rfa1 = ATmega128RFA1
  m128rfr2 = ATmega128RFR2
  m16      = ATmega16
  m161     = ATmega161
  m162     = ATmega162
  m163     = ATmega163
  m164p    = ATmega164P
  m168     = ATmega168
  m168p    = ATmega168P
  m168pb   = ATmega168PB
  m169     = ATmega169
  m16u2    = ATmega16U2
  m2560    = ATmega2560
  m2561    = ATmega2561
  m2564rfr2 = ATmega2564RFR2
  m256rfr2 = ATmega256RFR2
  m32      = ATmega32
  m324p    = ATmega324P
  m324pa   = ATmega324PA
  m325     = ATmega325
  m3250    = ATmega3250
  m328     = ATmega328
  m328p    = ATmega328P
  m329     = ATmega329
  m3290    = ATmega3290
  m3290p   = ATmega3290P
  m329p    = ATmega329P
  m32m1    = ATmega32M1
  m32u2    = ATmega32U2
  m32u4    = ATmega32U4
  m406     = ATMEGA406
  m48      = ATmega48
  m48p     = ATmega48P
  m48pb    = ATmega48PB
  m64      = ATmega64
  m640     = ATmega640
  m644     = ATmega644
  m644p    = ATmega644P
  m644rfr2 = ATmega644RFR2
  m645     = ATmega645
  m6450    = ATmega6450
  m649     = ATmega649
  m6490    = ATmega6490
  m64rfr2  = ATmega64RFR2
  m8       = ATmega8
  m8515    = ATmega8515
  m8535    = ATmega8535
  m88      = ATmega88
  m88p     = ATmega88P
  m88pb    = ATmega88PB
  m8u2     = ATmega8U2
  t10      = ATtiny10
  t11      = ATtiny11
  t12      = ATtiny12
  t13      = ATtiny13
  t15      = ATtiny15
  t1634    = ATtiny1634
  t20      = ATtiny20
  t2313    = ATtiny2313
  t24      = ATtiny24
  t25      = ATtiny25
  t26      = ATtiny26
  t261     = ATtiny261
  t28      = ATtiny28
  t4       = ATtiny4
  t40      = ATtiny40
  t4313    = ATtiny4313
  t43u     = ATtiny43u
  t44      = ATtiny44
  t441     = ATtiny441
  t45      = ATtiny45
  t461     = ATtiny461
  t5       = ATtiny5
  t84      = ATtiny84
  t841     = ATtiny841
  t85      = ATtiny85
  t861     = ATtiny861
  t88      = ATtiny88
  t9       = ATtiny9
  x128a1   = ATxmega128A1
  x128a1d  = ATxmega128A1revD
  x128a1u  = ATxmega128A1U
  x128a3   = ATxmega128A3
  x128a3u  = ATxmega128A3U
  x128a4   = ATxmega128A4
  x128a4u  = ATxmega128A4U
  x128b1   = ATxmega128B1
  x128b3   = ATxmega128B3
  x128c3   = ATxmega128C3
  x128d3   = ATxmega128D3
  x128d4   = ATxmega128D4
  x16a4    = ATxmega16A4
  x16a4u   = ATxmega16A4U
  x16c4    = ATxmega16C4
  x16d4    = ATxmega16D4
  x16e5    = ATxmega16E5
  x192a1   = ATxmega192A1
  x192a3   = ATxmega192A3
  x192a3u  = ATxmega192A3U
  x192c3   = ATxmega192C3
  x192d3   = ATxmega192D3
  x256a1   = ATxmega256A1
  x256a3   = ATxmega256A3
  x256a3b  = ATxmega256A3B
  x256a3bu = ATxmega256A3BU
  x256a3u  = ATxmega256A3U
  x256c3   = ATxmega256C3
  x256d3   = ATxmega256D3
  x32a4    = ATxmega32A4
  x32a4u   = ATxmega32A4U
  x32c4    = ATxmega32C4
  x32d4    = ATxmega32D4
  x32e5    = ATxmega32E5
  x384c3   = ATxmega384C3
  x384d3   = ATxmega384D3
  x64a1    = ATxmega64A1
  x64a1u   = ATxmega64A1U
  x64a3    = ATxmega64A3
  x64a3u   = ATxmega64A3U
  x64a4    = ATxmega64A4
  x64a4u   = ATxmega64A4U
  x64b1    = ATxmega64B1
  x64b3    = ATxmega64B3
  x64c3    = ATxmega64C3
  x64d3    = ATxmega64D3
  x64d4    = ATxmega64D4
  x8e5     = ATxmega8E5
  ucr2     = deprecated, use 'uc3a0512'

pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ avrdude -p m8p -c usbasp -F -t
avrdude: AVR Part "m8p" not found.

Valid parts are:
  uc3a0512 = AT32UC3A0512
  c128     = AT90CAN128
  c32      = AT90CAN32
  c64      = AT90CAN64
  pwm2     = AT90PWM2
  pwm216   = AT90PWM216
  pwm2b    = AT90PWM2B
  pwm3     = AT90PWM3
  pwm316   = AT90PWM316
  pwm3b    = AT90PWM3B
  1200     = AT90S1200
  2313     = AT90S2313
  2333     = AT90S2333
  2343     = AT90S2343
  4414     = AT90S4414
  4433     = AT90S4433
  4434     = AT90S4434
  8515     = AT90S8515
  8535     = AT90S8535
  usb1286  = AT90USB1286
  usb1287  = AT90USB1287
  usb162   = AT90USB162
  usb646   = AT90USB646
  usb647   = AT90USB647
  usb82    = AT90USB82
  m103     = ATmega103
  m128     = ATmega128
  m1280    = ATmega1280
  m1281    = ATmega1281
  m1284    = ATmega1284
  m1284p   = ATmega1284P
  m1284rfr2 = ATmega1284RFR2
  m128rfa1 = ATmega128RFA1
  m128rfr2 = ATmega128RFR2
  m16      = ATmega16
  m161     = ATmega161
  m162     = ATmega162
  m163     = ATmega163
  m164p    = ATmega164P
  m168     = ATmega168
  m168p    = ATmega168P
  m168pb   = ATmega168PB
  m169     = ATmega169
  m16u2    = ATmega16U2
  m2560    = ATmega2560
  m2561    = ATmega2561
  m2564rfr2 = ATmega2564RFR2
  m256rfr2 = ATmega256RFR2
  m32      = ATmega32
  m324p    = ATmega324P
  m324pa   = ATmega324PA
  m325     = ATmega325
  m3250    = ATmega3250
  m328     = ATmega328
  m328p    = ATmega328P
  m329     = ATmega329
  m3290    = ATmega3290
  m3290p   = ATmega3290P
  m329p    = ATmega329P
  m32m1    = ATmega32M1
  m32u2    = ATmega32U2
  m32u4    = ATmega32U4
  m406     = ATMEGA406
  m48      = ATmega48
  m48p     = ATmega48P
  m48pb    = ATmega48PB
  m64      = ATmega64
  m640     = ATmega640
  m644     = ATmega644
  m644p    = ATmega644P
  m644rfr2 = ATmega644RFR2
  m645     = ATmega645
  m6450    = ATmega6450
  m649     = ATmega649
  m6490    = ATmega6490
  m64rfr2  = ATmega64RFR2
  m8       = ATmega8
  m8515    = ATmega8515
  m8535    = ATmega8535
  m88      = ATmega88
  m88p     = ATmega88P
  m88pb    = ATmega88PB
  m8u2     = ATmega8U2
  t10      = ATtiny10
  t11      = ATtiny11
  t12      = ATtiny12
  t13      = ATtiny13
  t15      = ATtiny15
  t1634    = ATtiny1634
  t20      = ATtiny20
  t2313    = ATtiny2313
  t24      = ATtiny24
  t25      = ATtiny25
  t26      = ATtiny26
  t261     = ATtiny261
  t28      = ATtiny28
  t4       = ATtiny4
  t40      = ATtiny40
  t4313    = ATtiny4313
  t43u     = ATtiny43u
  t44      = ATtiny44
  t441     = ATtiny441
  t45      = ATtiny45
  t461     = ATtiny461
  t5       = ATtiny5
  t84      = ATtiny84
  t841     = ATtiny841
  t85      = ATtiny85
  t861     = ATtiny861
  t88      = ATtiny88
  t9       = ATtiny9
  x128a1   = ATxmega128A1
  x128a1d  = ATxmega128A1revD
  x128a1u  = ATxmega128A1U
  x128a3   = ATxmega128A3
  x128a3u  = ATxmega128A3U
  x128a4   = ATxmega128A4
  x128a4u  = ATxmega128A4U
  x128b1   = ATxmega128B1
  x128b3   = ATxmega128B3
  x128c3   = ATxmega128C3
  x128d3   = ATxmega128D3
  x128d4   = ATxmega128D4
  x16a4    = ATxmega16A4
  x16a4u   = ATxmega16A4U
  x16c4    = ATxmega16C4
  x16d4    = ATxmega16D4
  x16e5    = ATxmega16E5
  x192a1   = ATxmega192A1
  x192a3   = ATxmega192A3
  x192a3u  = ATxmega192A3U
  x192c3   = ATxmega192C3
  x192d3   = ATxmega192D3
  x256a1   = ATxmega256A1
  x256a3   = ATxmega256A3
  x256a3b  = ATxmega256A3B
  x256a3bu = ATxmega256A3BU
  x256a3u  = ATxmega256A3U
  x256c3   = ATxmega256C3
  x256d3   = ATxmega256D3
  x32a4    = ATxmega32A4
  x32a4u   = ATxmega32A4U
  x32c4    = ATxmega32C4
  x32d4    = ATxmega32D4
  x32e5    = ATxmega32E5
  x384c3   = ATxmega384C3
  x384d3   = ATxmega384D3
  x64a1    = ATxmega64A1
  x64a1u   = ATxmega64A1U
  x64a3    = ATxmega64A3
  x64a3u   = ATxmega64A3U
  x64a4    = ATxmega64A4
  x64a4u   = ATxmega64A4U
  x64b1    = ATxmega64B1
  x64b3    = ATxmega64B3
  x64c3    = ATxmega64C3
  x64d3    = ATxmega64D3
  x64d4    = ATxmega64D4
  x8e5     = ATxmega8E5
  ucr2     = deprecated, use 'uc3a0512'

pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ avrdude -p m8P -c usbasp -F -t
avrdude: AVR Part "m8P" not found.

Valid parts are:
  uc3a0512 = AT32UC3A0512
  c128     = AT90CAN128
  c32      = AT90CAN32
  c64      = AT90CAN64
  pwm2     = AT90PWM2
  pwm216   = AT90PWM216
  pwm2b    = AT90PWM2B
  pwm3     = AT90PWM3
  pwm316   = AT90PWM316
  pwm3b    = AT90PWM3B
  1200     = AT90S1200
  2313     = AT90S2313
  2333     = AT90S2333
  2343     = AT90S2343
  4414     = AT90S4414
  4433     = AT90S4433
  4434     = AT90S4434
  8515     = AT90S8515
  8535     = AT90S8535
  usb1286  = AT90USB1286
  usb1287  = AT90USB1287
  usb162   = AT90USB162
  usb646   = AT90USB646
  usb647   = AT90USB647
  usb82    = AT90USB82
  m103     = ATmega103
  m128     = ATmega128
  m1280    = ATmega1280
  m1281    = ATmega1281
  m1284    = ATmega1284
  m1284p   = ATmega1284P
  m1284rfr2 = ATmega1284RFR2
  m128rfa1 = ATmega128RFA1
  m128rfr2 = ATmega128RFR2
  m16      = ATmega16
  m161     = ATmega161
  m162     = ATmega162
  m163     = ATmega163
  m164p    = ATmega164P
  m168     = ATmega168
  m168p    = ATmega168P
  m168pb   = ATmega168PB
  m169     = ATmega169
  m16u2    = ATmega16U2
  m2560    = ATmega2560
  m2561    = ATmega2561
  m2564rfr2 = ATmega2564RFR2
  m256rfr2 = ATmega256RFR2
  m32      = ATmega32
  m324p    = ATmega324P
  m324pa   = ATmega324PA
  m325     = ATmega325
  m3250    = ATmega3250
  m328     = ATmega328
  m328p    = ATmega328P
  m329     = ATmega329
  m3290    = ATmega3290
  m3290p   = ATmega3290P
  m329p    = ATmega329P
  m32m1    = ATmega32M1
  m32u2    = ATmega32U2
  m32u4    = ATmega32U4
  m406     = ATMEGA406
  m48      = ATmega48
  m48p     = ATmega48P
  m48pb    = ATmega48PB
  m64      = ATmega64
  m640     = ATmega640
  m644     = ATmega644
  m644p    = ATmega644P
  m644rfr2 = ATmega644RFR2
  m645     = ATmega645
  m6450    = ATmega6450
  m649     = ATmega649
  m6490    = ATmega6490
  m64rfr2  = ATmega64RFR2
  m8       = ATmega8
  m8515    = ATmega8515
  m8535    = ATmega8535
  m88      = ATmega88
  m88p     = ATmega88P
  m88pb    = ATmega88PB
  m8u2     = ATmega8U2
  t10      = ATtiny10
  t11      = ATtiny11
  t12      = ATtiny12
  t13      = ATtiny13
  t15      = ATtiny15
  t1634    = ATtiny1634
  t20      = ATtiny20
  t2313    = ATtiny2313
  t24      = ATtiny24
  t25      = ATtiny25
  t26      = ATtiny26
  t261     = ATtiny261
  t28      = ATtiny28
  t4       = ATtiny4
  t40      = ATtiny40
  t4313    = ATtiny4313
  t43u     = ATtiny43u
  t44      = ATtiny44
  t441     = ATtiny441
  t45      = ATtiny45
  t461     = ATtiny461
  t5       = ATtiny5
  t84      = ATtiny84
  t841     = ATtiny841
  t85      = ATtiny85
  t861     = ATtiny861
  t88      = ATtiny88
  t9       = ATtiny9
  x128a1   = ATxmega128A1
  x128a1d  = ATxmega128A1revD
  x128a1u  = ATxmega128A1U
  x128a3   = ATxmega128A3
  x128a3u  = ATxmega128A3U
  x128a4   = ATxmega128A4
  x128a4u  = ATxmega128A4U
  x128b1   = ATxmega128B1
  x128b3   = ATxmega128B3
  x128c3   = ATxmega128C3
  x128d3   = ATxmega128D3
  x128d4   = ATxmega128D4
  x16a4    = ATxmega16A4
  x16a4u   = ATxmega16A4U
  x16c4    = ATxmega16C4
  x16d4    = ATxmega16D4
  x16e5    = ATxmega16E5
  x192a1   = ATxmega192A1
  x192a3   = ATxmega192A3
  x192a3u  = ATxmega192A3U
  x192c3   = ATxmega192C3
  x192d3   = ATxmega192D3
  x256a1   = ATxmega256A1
  x256a3   = ATxmega256A3
  x256a3b  = ATxmega256A3B
  x256a3bu = ATxmega256A3BU
  x256a3u  = ATxmega256A3U
  x256c3   = ATxmega256C3
  x256d3   = ATxmega256D3
  x32a4    = ATxmega32A4
  x32a4u   = ATxmega32A4U
  x32c4    = ATxmega32C4
  x32d4    = ATxmega32D4
  x32e5    = ATxmega32E5
  x384c3   = ATxmega384C3
  x384d3   = ATxmega384D3
  x64a1    = ATxmega64A1
  x64a1u   = ATxmega64A1U
  x64a3    = ATxmega64A3
  x64a3u   = ATxmega64A3U
  x64a4    = ATxmega64A4
  x64a4u   = ATxmega64A4U
  x64b1    = ATxmega64B1
  x64b3    = ATxmega64B3
  x64c3    = ATxmega64C3
  x64d3    = ATxmega64D3
  x64d4    = ATxmega64D4
  x8e5     = ATxmega8E5
  ucr2     = deprecated, use 'uc3a0512'

pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ avrdude -p m8 -c usbasp -B300 -Ulfuse:v:0xE1:m

avrdude: set SCK frequency to 2000 Hz
avrdude: error: program enable: target doesn't answer. 1 
avrdude: initialization failed, rc=-1
         Double check connections and try again, or use -F to override
         this check.


avrdude done.  Thank you.

pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ avrdude -p m8 -c usbasp -B2000HZ -Ulfuse:v:0xE1:m
avrdude: invalid bit clock unit of measure 'HZ'
avrdude: invalid bit clock period specified '2000HZ'
pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ avrdude -p m8 -c usbasp -B2000Hz -Ulfuse:v:0xE1:m

avrdude: set SCK frequency to 2000 Hz
avrdude: error: program enable: target doesn't answer. 1 
avrdude: initialization failed, rc=-1
         Double check connections and try again, or use -F to override
         this check.


avrdude done.  Thank you.

pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ avrdude -p m8 -c usbasp -B2000Hz -Ulfuse:v:0xE1:m

avrdude: set SCK frequency to 2000 Hz
avrdude: error: program enable: target doesn't answer. 1 
avrdude: initialization failed, rc=-1
         Double check connections and try again, or use -F to override
         this check.


avrdude done.  Thank you.

pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ avrdude -p m8 -c usbasp -B2000Hz -Ulfuse:v:0xE1:m

avrdude: set SCK frequency to 2000 Hz
avrdude: error: program enable: target doesn't answer. 1 
avrdude: initialization failed, rc=-1
         Double check connections and try again, or use -F to override
         this check.


avrdude done.  Thank you.

pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ avrdude -p m8 -c usbasp -B75000Hz -Ulfuse:v:0xE1:m

avrdude: set SCK frequency to 32000 Hz
avrdude: error: program enable: target doesn't answer. 1 
avrdude: initialization failed, rc=-1
         Double check connections and try again, or use -F to override
         this check.


avrdude done.  Thank you.

pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ avrdude -p m8 -c usbasp -B32000Hz -Ulfuse:v:0xE1:m

avrdude: set SCK frequency to 32000 Hz
avrdude: error: program enable: target doesn't answer. 1 
avrdude: initialization failed, rc=-1
         Double check connections and try again, or use -F to override
         this check.


avrdude done.  Thank you.

pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ avrdude -p m8 -c usbasp -B2000Hz -Ulfuse:v:0xE1:m

avrdude: set SCK frequency to 2000 Hz
avrdude: error: program enable: target doesn't answer. 1 
avrdude: initialization failed, rc=-1
         Double check connections and try again, or use -F to override
         this check.


avrdude done.  Thank you.

pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ avrdude -p m8 -c usbasp -Ulfuse:v:0xE1:m

avrdude: error: program enable: target doesn't answer. 1 
avrdude: initialization failed, rc=-1
         Double check connections and try again, or use -F to override
         this check.


avrdude done.  Thank you.

pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ avrdude -p m8 -c usbasp -Ulfuse:v:0xE1:m

avrdude: error: program enable: target doesn't answer. 1 
avrdude: initialization failed, rc=-1
         Double check connections and try again, or use -F to override
         this check.


avrdude done.  Thank you.

pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ avrdude -p m8 -c usbasp -Ulfuse:v:0xE1:m

avrdude: error: program enable: target doesn't answer. 1 
avrdude: initialization failed, rc=-1
         Double check connections and try again, or use -F to override
         this check.


avrdude done.  Thank you.

pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ avrdude -p m8 -c usbasp -B2000Hz -F -Ulfuse:v:0xE1:m

avrdude: set SCK frequency to 2000 Hz
avrdude: error: program enable: target doesn't answer. 1 
avrdude: initialization failed, rc=-1
avrdude: AVR device initialized and ready to accept instructions
avrdude: Device signature = 0x000000 (retrying)
avrdude: Device signature = 0x000000 (retrying)
avrdude: Device signature = 0x000000
avrdude: Yikes!  Invalid device signature.
avrdude: Expected signature for ATmega8 is 1E 93 07

avrdude done.  Thank you.

pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ avrdude -p m8 -c usbasp -F -t

avrdude: error: program enable: target doesn't answer. 1 
avrdude: initialization failed, rc=-1
avrdude: AVR device initialized and ready to accept instructions
avrdude: Device signature = 0xa019f4
avrdude: Expected signature for ATmega8 is 1E 93 07
avrdude> part
>>> part 

AVR Part                      : ATmega8
Chip Erase delay              : 10000 us
PAGEL                         : PD7
BS2                           : PC2
RESET disposition             : dedicated
RETRY pulse                   : SCK
serial program mode           : yes
parallel program mode         : yes
Timeout                       : 200
StabDelay                     : 100
CmdexeDelay                   : 25
SyncLoops                     : 32
ByteDelay                     : 0
PollIndex                     : 3
PollValue                     : 0x53
Memory Detail                 :

                         Block Poll               Page                       Polled
  Memory Type Mode Delay Size  Indx Paged  Size   Size #Pages MinW  MaxW   ReadBack
  ----------- ---- ----- ----- ---- ------ ------ ---- ------ ----- ----- ---------
  eeprom         4    20   128    0 no        512    4      0  9000  9000 0xff 0xff
  flash         33    10    64    0 yes      8192   64    128  4500  4500 0xff 0x00
  lfuse          0     0     0    0 no          1    0      0  2000  2000 0x00 0x00
  hfuse          0     0     0    0 no          1    0      0  2000  2000 0x00 0x00
  lock           0     0     0    0 no          1    0      0  2000  2000 0x00 0x00
  calibration    0     0     0    0 no          4    0      0     0     0 0x00 0x00
  signature      0     0     0    0 no          3    0      0     0     0 0x00 0x00

avrdude> w signature
>>> w signature 
Usage: write <memtype> <addr> <byte1> <byte2> ... byteN>
avrdude> w signature 0 0x1E9307
>>> w signature 0 0x1E9307 
avrdude (write): error writing 0x07 at 0x00000, rc=-1
write operation not supported on memory type "signature"
avrdude (write): error writing 0x07 at 0x00000 cell=0x00

avrdude> w signature 0x00 0x1E9307
>>> w signature 0x00 0x1E9307 
avrdude (write): error writing 0x07 at 0x00000, rc=-1
write operation not supported on memory type "signature"
avrdude (write): error writing 0x07 at 0x00000 cell=0x00

avrdude> w signature 0x07 0x1E9307
>>> w signature 0x07 0x1E9307 
avrdude (write): address 0x00007 is out of range for signature memory
avrdude> w signature 0x01 0x1E9307
>>> w signature 0x01 0x1E9307 
avrdude (write): error writing 0x07 at 0x00001, rc=-1
write operation not supported on memory type "signature"
avrdude (write): error writing 0x07 at 0x00001 cell=0x00

avrdude> w signature 0x1E9307 0
>>> w signature 0x1E9307 0 
avrdude (write): address 0x1e9307 is out of range for signature memory
avrdude> w signature 0x00 0x1E9307
>>> w signature 0x00 0x1E9307 
avrdude (write): error writing 0x07 at 0x00000, rc=-1
write operation not supported on memory type "signature"
avrdude (write): error writing 0x07 at 0x00000 cell=0x00

avrdude> hexdump -C
>>> hexdump -C 
avrdude: invalid command "hexdump"
avrdude> help
>>> help 
Valid commands:

  dump   : dump memory  : dump <memtype> <addr> <N-Bytes>
  read   : alias for dump
  write  : write memory : write <memtype> <addr> <b1> <b2> ... <bN>
  erase  : perform a chip erase
  sig    : display device signature bytes
  part   : display the current part information
  send   : send a raw command : send <b1> <b2> <b3> <b4>
  parms  : display adjustable parameters (STK500 only)
  vtarg  : set <V[target]> (STK500 only)
  varef  : set <V[aref]> (STK500 only)
  fosc   : set <oscillator frequency> (STK500 only)
  sck    : set <SCK period> (STK500 only)
  spi    : enter direct SPI mode
  pgm    : return to programming mode
  verbose : change verbosity
  help   : help
  ?      : help
  quit   : quit

Use the 'part' command to display valid memory types for use with the
'dump' and 'write' commands.

avrdude> sig
>>> sig 

Reading | ################################################## | 100% 0.00s

Device signature = 0x000000

avrdude> send 0 0 
>>> send 0 0 
Usage: send <byte1> <byte2> <byte3> <byte4>
avrdude> send 0 0 
>>> send 0 0 
Usage: send <byte1> <byte2> <byte3> <byte4>
avrdude> send 0
>>> send 0 
Usage: send <byte1> <byte2> <byte3> <byte4>
avrdude> send '0'
>>> send '0' 
Usage: send <byte1> <byte2> <byte3> <byte4>
avrdude> send 0b0
>>> send 0b0 
Usage: send <byte1> <byte2> <byte3> <byte4>
avrdude> send 1
>>> send 1 
Usage: send <byte1> <byte2> <byte3> <byte4>
avrdude> send 1 2 3 4
>>> send 1 2 3 4 
results: 00 00 00 00

avrdude> send 1 2 3 4
>>> send 1 2 3 4 
results: 00 00 00 00

avrdude> send 1 2 3 4
>>> send 1 2 3 4 
results: 00 00 00 00

avrdude> send 1 2 3 4
>>> send 1 2 3 4 
results: 00 00 00 00

avrdude> send 1 2 3 4
>>> send 1 2 3 4 
results: 00 00 00 00

avrdude> send 1 2 3 4
>>> send 1 2 3 4 
results: 00 00 00 00

avrdude> erase
>>> erase 
avrdude: erasing chip
avrdude: error: program enable: target doesn't answer. 1 
avrdude> erase signature
>>> erase signature 
avrdude: erasing chip
avrdude: error: program enable: target doesn't answer. 1 
avrdude> erase -help
>>> erase -help 
avrdude: erasing chip
avrdude: error: program enable: target doesn't answer. 1 
avrdude> erase --help
>>> erase --help 
avrdude: erasing chip
avrdude: error: program enable: target doesn't answer. 1 
avrdude> erase
>>> erase 
avrdude: erasing chip
avrdude: error: program enable: target doesn't answer. 1 
avrdude> erase
>>> erase 
avrdude: erasing chip
avrdude: error: program enable: target doesn't answer. 1 
avrdude> erase 
build.sh      compile.sh    upload.sh     variables.sh  
avrdude> signature
>>> signature 
avrdude: invalid command "signature"
avrdude> signature
>>> signature 
avrdude: invalid command "signature"
avrdude> w hfuse 0 0xff
>>> w hfuse 0 0xff 
avrdude (write): error writing 0xff at 0x00000, rc=-6
avrdude (write): error writing 0xff at 0x00000 cell=0x00

avrdude> w hfuse 0 0xff -F
>>> w hfuse 0 0xff -F 
avrdude (write): selected address and # bytes exceed range for hfuse memory
avrdude> w hfuse 0x00 0xff
>>> w hfuse 0x00 0xff 
avrdude (write): error writing 0xff at 0x00000, rc=-6
avrdude (write): error writing 0xff at 0x00000 cell=0x00

avrdude> e
>>> e 
avrdude: erasing chip
avrdude: error: program enable: target doesn't answer. 1 
avrdude> d lock
>>> d lock 
0000  00                                                |.               |

avrdude> w lock 0 1
>>> w lock 0 1 
avrdude (write): error writing 0x01 at 0x00000, rc=-6
avrdude (write): error writing 0x01 at 0x00000 cell=0x00

avrdude> w lock 0 0x1
>>> w lock 0 0x1 
avrdude (write): error writing 0x01 at 0x00000, rc=-6
avrdude (write): error writing 0x01 at 0x00000 cell=0x00

avrdude> w lock 0 0xff
>>> w lock 0 0xff 
avrdude (write): error writing 0xff at 0x00000, rc=-6
avrdude (write): error writing 0xff at 0x00000 cell=0x00

avrdude> w lock 0 0xff -F
>>> w lock 0 0xff -F 
avrdude (write): selected address and # bytes exceed range for lock memory
avrdude> w lock 0 0xfff
>>> w lock 0 0xfff 
avrdude (write): error writing 0xff at 0x00000, rc=-6
avrdude (write): error writing 0xff at 0x00000 cell=0x00

avrdude> w lock 0 0x01 -F 
>>> w lock 0 0x01 -F 
avrdude (write): selected address and # bytes exceed range for lock memory
avrdude> w lock 0 0x01 
>>> w lock 0 0x01 
avrdude (write): error writing 0x01 at 0x00000, rc=-6
avrdude (write): error writing 0x01 at 0x00000 cell=0x00

avrdude> w lock 0 0x00 -
>>> w lock 0 0x00 - 
avrdude (write): selected address and # bytes exceed range for lock memory
avrdude> w lock 0 0x00 -F
>>> w lock 0 0x00 -F 
avrdude (write): selected address and # bytes exceed range for lock memory
avrdude> safemode
>>> safemode 
avrdude: invalid command "safemode"
avrdude> ^C
pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ avrdude -p m8 -c usbasp -F -t

avrdude: error: program enable: target doesn't answer. 1 
avrdude: initialization failed, rc=-1
avrdude: AVR device initialized and ready to accept instructions
avrdude: Device signature = 0xa0c9dd
avrdude: Expected signature for ATmega8 is 1E 93 07
avrdude> ^C
pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ avrdude -p m8 -c usbasp -F -t

avrdude: error: program enable: target doesn't answer. 1 
avrdude: initialization failed, rc=-1
avrdude: AVR device initialized and ready to accept instructions
avrdude: Device signature = 0xa039ce
avrdude: Expected signature for ATmega8 is 1E 93 07
avrdude> ^C
pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ avrdude -p m8 -c usbasp -F -t

avrdude: error: program enable: target doesn't answer. 1 
avrdude: initialization failed, rc=-1
avrdude: AVR device initialized and ready to accept instructions
avrdude: Device signature = 0xa019e6
avrdude: Expected signature for ATmega8 is 1E 93 07
avrdude> part
>>> part 

AVR Part                      : ATmega8
Chip Erase delay              : 10000 us
PAGEL                         : PD7
BS2                           : PC2
RESET disposition             : dedicated
RETRY pulse                   : SCK
serial program mode           : yes
parallel program mode         : yes
Timeout                       : 200
StabDelay                     : 100
CmdexeDelay                   : 25
SyncLoops                     : 32
ByteDelay                     : 0
PollIndex                     : 3
PollValue                     : 0x53
Memory Detail                 :

                         Block Poll               Page                       Polled
  Memory Type Mode Delay Size  Indx Paged  Size   Size #Pages MinW  MaxW   ReadBack
  ----------- ---- ----- ----- ---- ------ ------ ---- ------ ----- ----- ---------
  eeprom         4    20   128    0 no        512    4      0  9000  9000 0xff 0xff
  flash         33    10    64    0 yes      8192   64    128  4500  4500 0xff 0x00
  lfuse          0     0     0    0 no          1    0      0  2000  2000 0x00 0x00
  hfuse          0     0     0    0 no          1    0      0  2000  2000 0x00 0x00
  lock           0     0     0    0 no          1    0      0  2000  2000 0x00 0x00
  calibration    0     0     0    0 no          4    0      0     0     0 0x00 0x00
  signature      0     0     0    0 no          3    0      0     0     0 0x00 0x00

avrdude> ^C
pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ avrdude -p m8 -b9600 -c usbasp -F -t

avrdude: error: program enable: target doesn't answer. 1 
avrdude: initialization failed, rc=-1
avrdude: AVR device initialized and ready to accept instructions
avrdude: Device signature = 0xa0897a
avrdude: Expected signature for ATmega8 is 1E 93 07
avrdude> ^C
pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ avrdude -p m8 -b57600 -c usbasp -F -t

avrdude: error: program enable: target doesn't answer. 1 
avrdude: initialization failed, rc=-1
avrdude: AVR device initialized and ready to accept instructions
avrdude: Device signature = 0xa02932
avrdude: Expected signature for ATmega8 is 1E 93 07
avrdude> ^C
pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ avrdude -p m8 -b4800 -c usbasp -F -t

avrdude: error: program enable: target doesn't answer. 1 
avrdude: initialization failed, rc=-1
avrdude: AVR device initialized and ready to accept instructions
avrdude: Device signature = 0xa0d963
avrdude: Expected signature for ATmega8 is 1E 93 07
avrdude> ^C
pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ avrdude -p m8 -b115200 -c usbasp -F -t

avrdude: error: program enable: target doesn't answer. 1 
avrdude: initialization failed, rc=-1
avrdude: AVR device initialized and ready to accept instructions
avrdude: Device signature = 0xa09980
avrdude: Expected signature for ATmega8 is 1E 93 07
avrdude> ^C
pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ avrdude -p m8 -b115200 -c usbasp -F -t

avrdude: error: program enable: target doesn't answer. 1 
avrdude: initialization failed, rc=-1
avrdude: AVR device initialized and ready to accept instructions
avrdude: Device signature = 0xa0a961
avrdude: Expected signature for ATmega8 is 1E 93 07
avrdude> xit
>>> xit 
avrdude: invalid command "xit"
avrdude> exit
>>> exit 
avrdude: invalid command "exit"
avrdude> quit
>>> quit 

avrdude done.  Thank you.

pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ avrdude -p m8 -b115200 -c usbasp -F -t

avrdude: error: program enable: target doesn't answer. 1 
avrdude: initialization failed, rc=-1
avrdude: AVR device initialized and ready to accept instructions
avrdude: Device signature = 0xa0e9b9
avrdude: Expected signature for ATmega8 is 1E 93 07
avrdude> quit
>>> quit 

avrdude done.  Thank you.

pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ sudo ./upload.sh 
[sudo] password for pavl:             
./upload.sh: 1: ./upload.sh: source: not found
./upload.sh: 3: ./upload.sh: Syntax error: "(" unexpected
pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ ./upload.sh 
 --MajorTask@UploadingCode : Uploading Hex file

avrdude: set SCK frequency to 750000 Hz
avrdude: error: program enable: target doesn't answer. 1 
avrdude: initialization failed, rc=-1
avrdude: AVR device initialized and ready to accept instructions
avrdude: Device signature = 0x000000 (retrying)
avrdude: Device signature = 0x000000 (retrying)
avrdude: Device signature = 0x000000
avrdude: Yikes!  Invalid device signature.
avrdude: Expected signature for ATmega8 is 1E 93 07
avrdude: NOTE: "flash" memory has been specified, an erase cycle will be performed
         To disable this feature, specify the -D option.

avrdude done.  Thank you.


avrdude: set SCK frequency to 750000 Hz
avrdude: error: program enable: target doesn't answer. 1 
avrdude: initialization failed, rc=-1
avrdude: AVR device initialized and ready to accept instructions
avrdude: Device signature = 0x10a6e8
avrdude: Expected signature for ATmega8 is 1E 93 07

avrdude done.  Thank you.

 --MajorTask@UploadingCode : Task finished.

pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ ./upload.sh 
 --MajorTask@UploadingCode : Uploading Hex file

avrdude: set SCK frequency to 750000 Hz
avrdude: error: program enable: target doesn't answer. 1 
avrdude: initialization failed, rc=-1
avrdude: AVR device initialized and ready to accept instructions
avrdude: Device signature = 0x000000 (retrying)
avrdude: Device signature = 0x000000 (retrying)
avrdude: Device signature = 0x000000
avrdude: Yikes!  Invalid device signature.
avrdude: Expected signature for ATmega8 is 1E 93 07
avrdude: NOTE: "flash" memory has been specified, an erase cycle will be performed
         To disable this feature, specify the -D option.

avrdude done.  Thank you.


avrdude: set SCK frequency to 750000 Hz
avrdude: error: program enable: target doesn't answer. 1 
avrdude: initialization failed, rc=-1
avrdude: AVR device initialized and ready to accept instructions
avrdude: Device signature = 0x10366a
avrdude: Expected signature for ATmega8 is 1E 93 07

avrdude done.  Thank you.

 --MajorTask@UploadingCode : Task finished.

pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ ./upload.sh 
 --MajorTask@UploadingCode : Uploading Hex file
avrdude: Warning: cannot query manufacturer for device: error sending control message: Protocol error
avrdude: Warning: cannot query product for device: error sending control message: Protocol error
avrdude: error: could not find USB device with vid=0x16c0 pid=0x5dc vendor='www.fischl.de' product='USBasp'

avrdude done.  Thank you.

avrdude: Warning: cannot query manufacturer for device: error sending control message: Protocol error
avrdude: Warning: cannot query product for device: error sending control message: Protocol error
avrdude: error: could not find USB device with vid=0x16c0 pid=0x5dc vendor='www.fischl.de' product='USBasp'

avrdude done.  Thank you.

 --MajorTask@UploadingCode : Task finished.

pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ ./upload.sh 
 --MajorTask@UploadingCode : Uploading Hex file
avrdude: Warning: cannot query manufacturer for device: error sending control message: Protocol error
avrdude: Warning: cannot query product for device: error sending control message: Protocol error
avrdude: error: could not find USB device with vid=0x16c0 pid=0x5dc vendor='www.fischl.de' product='USBasp'

avrdude done.  Thank you.

avrdude: Warning: cannot query manufacturer for device: error sending control message: Protocol error
avrdude: Warning: cannot query product for device: error sending control message: Protocol error
avrdude: error: could not find USB device with vid=0x16c0 pid=0x5dc vendor='www.fischl.de' product='USBasp'

avrdude done.  Thank you.

 --MajorTask@UploadingCode : Task finished.

pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ ./upload.sh 
 --MajorTask@UploadingCode : Uploading Hex file
avrdude: Warning: cannot query manufacturer for device: error sending control message: Protocol error
avrdude: Warning: cannot query product for device: error sending control message: Protocol error
avrdude: error: could not find USB device with vid=0x16c0 pid=0x5dc vendor='www.fischl.de' product='USBasp'

avrdude done.  Thank you.

avrdude: Warning: cannot query manufacturer for device: error sending control message: Protocol error
avrdude: Warning: cannot query product for device: error sending control message: Protocol error
avrdude: error: could not find USB device with vid=0x16c0 pid=0x5dc vendor='www.fischl.de' product='USBasp'

avrdude done.  Thank you.

 --MajorTask@UploadingCode : Task finished.

pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ ./upload.sh 
 --MajorTask@UploadingCode : Uploading Hex file
avrdude: Warning: cannot query manufacturer for device: error sending control message: Protocol error
avrdude: Warning: cannot query product for device: error sending control message: Protocol error
avrdude: error: could not find USB device with vid=0x16c0 pid=0x5dc vendor='www.fischl.de' product='USBasp'

avrdude done.  Thank you.

avrdude: Warning: cannot query manufacturer for device: error sending control message: Protocol error
avrdude: Warning: cannot query product for device: error sending control message: Protocol error
avrdude: error: could not find USB device with vid=0x16c0 pid=0x5dc vendor='www.fischl.de' product='USBasp'

avrdude done.  Thank you.

 --MajorTask@UploadingCode : Task finished.

pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ ./upload.sh 
 --MajorTask@UploadingCode : Uploading Hex file
avrdude: Warning: cannot query manufacturer for device: error sending control message: Protocol error
avrdude: Warning: cannot query product for device: error sending control message: Protocol error
avrdude: error: could not find USB device with vid=0x16c0 pid=0x5dc vendor='www.fischl.de' product='USBasp'

avrdude done.  Thank you.

avrdude: Warning: cannot query manufacturer for device: error sending control message: Protocol error
avrdude: Warning: cannot query product for device: error sending control message: Protocol error
avrdude: error: could not find USB device with vid=0x16c0 pid=0x5dc vendor='www.fischl.de' product='USBasp'

avrdude done.  Thank you.

 --MajorTask@UploadingCode : Task finished.

pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ avrdude -p m8 -c usbasp -F -t
avrdude: Warning: cannot query manufacturer for device: error sending control message: Protocol error
avrdude: Warning: cannot query product for device: error sending control message: Protocol error
avrdude: error: could not find USB device with vid=0x16c0 pid=0x5dc vendor='www.fischl.de' product='USBasp'

avrdude done.  Thank you.

pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ avrdude -p m8 -c usbasp -F -t
avrdude: Warning: cannot query manufacturer for device: error sending control message: Protocol error
avrdude: Warning: cannot query product for device: error sending control message: Protocol error
avrdude: error: could not find USB device with vid=0x16c0 pid=0x5dc vendor='www.fischl.de' product='USBasp'

avrdude done.  Thank you.

pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ avrdude -p m8 -c usbasp -F -t
avrdude: Warning: cannot query manufacturer for device: error sending control message: Protocol error
avrdude: Warning: cannot query product for device: error sending control message: Protocol error
avrdude: error: could not find USB device with vid=0x16c0 pid=0x5dc vendor='www.fischl.de' product='USBasp'

avrdude done.  Thank you.

pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ avrdude -p m8 -c usbasp -F -t
avrdude: Warning: cannot query manufacturer for device: error sending control message: Protocol error
avrdude: Warning: cannot query product for device: error sending control message: Protocol error
avrdude: error: could not find USB device with vid=0x16c0 pid=0x5dc vendor='www.fischl.de' product='USBasp'

avrdude done.  Thank you.

pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ avrdude -p m8 -c usbasp -F -t
avrdude: Warning: cannot query manufacturer for device: error sending control message: Protocol error
avrdude: Warning: cannot query product for device: error sending control message: Protocol error
avrdude: error: could not find USB device with vid=0x16c0 pid=0x5dc vendor='www.fischl.de' product='USBasp'

avrdude done.  Thank you.

pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ avrdude -p m8 -c usbasp -F -t

avrdude: error: program enable: target doesn't answer. 1 
avrdude: initialization failed, rc=-1
avrdude: AVR device initialized and ready to accept instructions
avrdude: Device signature = 0xa0f929
avrdude: Expected signature for ATmega8 is 1E 93 07
avrdude> ^C
pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ avrdude -p m8 -c usbasp -F -t

avrdude: error: program enable: target doesn't answer. 1 
avrdude: initialization failed, rc=-1
avrdude: AVR device initialized and ready to accept instructions
avrdude: Device signature = 0xa039f0
avrdude: Expected signature for ATmega8 is 1E 93 07
avrdude> quit
>>> quit 

avrdude done.  Thank you.

pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ avrdude -p m8 -c usbasp -F -t
avrdude: error: could not find USB device with vid=0x16c0 pid=0x5dc vendor='www.fischl.de' product='USBasp'

avrdude done.  Thank you.

pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ avrdude -p m8 -c usbasp -F -t
avrdude: error: could not find USB device with vid=0x16c0 pid=0x5dc vendor='www.fischl.de' product='USBasp'

avrdude done.  Thank you.

pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ avrdude -p m8 -c usbasp -F -t
avrdude: error: could not find USB device with vid=0x16c0 pid=0x5dc vendor='www.fischl.de' product='USBasp'

avrdude done.  Thank you.

pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ avrdude -p m8 -c usbasp -F -t
avrdude: error: could not find USB device with vid=0x16c0 pid=0x5dc vendor='www.fischl.de' product='USBasp'

avrdude done.  Thank you.

pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ avrdude -B12000Hz -p m8 -c usbasp -F -t
avrdude: error: could not find USB device with vid=0x16c0 pid=0x5dc vendor='www.fischl.de' product='USBasp'

avrdude done.  Thank you.

pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ avrdude -B12000Hz -p m8 -c usbasp -F -t

avrdude: set SCK frequency to 8000 Hz
avrdude: error: program enable: target doesn't answer. 1 
avrdude: initialization failed, rc=-1
avrdude: AVR device initialized and ready to accept instructions
avrdude: Device signature = 0xa0e974
avrdude: Expected signature for ATmega8 is 1E 93 07
avrdude> ^C
pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ avrdude -B12000Hz -p m8 -c usbasp -F -t

avrdude: set SCK frequency to 8000 Hz
avrdude: error: program enable: target doesn't answer. 1 
avrdude: initialization failed, rc=-1
avrdude: AVR device initialized and ready to accept instructions
avrdude: Device signature = 0xa0699e
avrdude: Expected signature for ATmega8 is 1E 93 07
avrdude> quit
>>> quit 

avrdude done.  Thank you.

pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ avrdude -B8000Hz -p m8 -c usbasp -F -t

avrdude: set SCK frequency to 8000 Hz
avrdude: error: program enable: target doesn't answer. 1 
avrdude: initialization failed, rc=-1
avrdude: AVR device initialized and ready to accept instructions
avrdude: Device signature = 0xa0b99e
avrdude: Expected signature for ATmega8 is 1E 93 07
avrdude> quit
>>> quit 

avrdude done.  Thank you.

pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ ./upload.sh 
 --MajorTask@UploadingCode : Uploading Hex file

avrdude: set SCK frequency to 8000 Hz
avrdude: error: program enable: target doesn't answer. 1 
avrdude: initialization failed, rc=-1
avrdude: AVR device initialized and ready to accept instructions
avrdude: Device signature = 0x000000 (retrying)
avrdude: Device signature = 0x000000 (retrying)
avrdude: Device signature = 0x000000
avrdude: Yikes!  Invalid device signature.
avrdude: Expected signature for ATmega8 is 1E 93 07
avrdude: NOTE: "flash" memory has been specified, an erase cycle will be performed
         To disable this feature, specify the -D option.

avrdude done.  Thank you.


avrdude: set SCK frequency to 8000 Hz
avrdude: error: program enable: target doesn't answer. 1 
avrdude: initialization failed, rc=-1
avrdude: AVR device initialized and ready to accept instructions
avrdude: Device signature = 0x107652
avrdude: Expected signature for ATmega8 is 1E 93 07

avrdude done.  Thank you.

 --MajorTask@UploadingCode : Task finished.

pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ ./upload.sh 
 --MajorTask@UploadingCode : Uploading Hex file

avrdude: set SCK frequency to 8000 Hz
avrdude: error: program enable: target doesn't answer. 1 
avrdude: initialization failed, rc=-1
avrdude: AVR device initialized and ready to accept instructions
avrdude: Device signature = 0x000000 (retrying)
avrdude: Device signature = 0x000000 (retrying)
avrdude: Device signature = 0x000000
avrdude: Yikes!  Invalid device signature.
avrdude: Expected signature for ATmega8 is 1E 93 07
avrdude: NOTE: "flash" memory has been specified, an erase cycle will be performed
         To disable this feature, specify the -D option.

avrdude done.  Thank you.


avrdude: set SCK frequency to 8000 Hz
avrdude: error: program enable: target doesn't answer. 1 
avrdude: initialization failed, rc=-1
avrdude: AVR device initialized and ready to accept instructions
avrdude: Device signature = 0x108635
avrdude: Expected signature for ATmega8 is 1E 93 07

avrdude done.  Thank you.

 --MajorTask@UploadingCode : Task finished.

pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ ./upload.sh 
 --MajorTask@UploadingCode : Uploading Hex file

avrdude: set SCK frequency to 8000 Hz
avrdude: error: program enable: target doesn't answer. 1 
avrdude: initialization failed, rc=-1
avrdude: AVR device initialized and ready to accept instructions
avrdude: Device signature = 0x000000 (retrying)
avrdude: Device signature = 0x000000 (retrying)
avrdude: Device signature = 0x000000
avrdude: Yikes!  Invalid device signature.
avrdude: Expected signature for ATmega8 is 1E 93 07
avrdude: NOTE: "flash" memory has been specified, an erase cycle will be performed
         To disable this feature, specify the -D option.

avrdude done.  Thank you.


avrdude: set SCK frequency to 8000 Hz
avrdude: error: program enable: target doesn't answer. 1 
avrdude: initialization failed, rc=-1
avrdude: AVR device initialized and ready to accept instructions
avrdude: Device signature = 0x10c662
avrdude: Expected signature for ATmega8 is 1E 93 07

avrdude done.  Thank you.

 --MajorTask@UploadingCode : Task finished.

pavl@pavl-machine:/home/twisted/GradleProjects/AVR-Sandbox/Hello-Avr/build$ 
```
