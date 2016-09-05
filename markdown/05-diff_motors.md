Lock bits
=========

<pre><code class="hljs" data-trim contenteditable>
diff -u motor1/lock.hex motor2/lock.hex
--- motor1/lock.hex     2016-06-06 10:00:38.532028704 +0000
+++ motor2/lock.hex     2016-06-06 09:09:24.738241220 +0000
@@ -1,2 +1,2 @@
-:0100000003FC
+:010000002FD0
:00000001FF
</code></pre>

What are those lockbits? Here is some good info:
http://www.embedds.com/all-you-need-to-know-about-avr-fuses/

Here is a fuse bits calculator:
http://www.engbedded.com/fusecalc

...and of course, the official Atmega8 [datasheet](http://www.atmel.com/Images/Atmel-2486-8-bit-AVR-microcontroller-ATmega8_L_datasheet.pdf)!


Lock bits (03 FC): "dead" motor
-------------------------------

![lock_bits_dead](res/03fc_fusebits.png)


Lock bits (2F D0): good motor
-----------------------------

![lock_bits_healthy](res/2fd0_fusebits.png)


Lock bits in datasheet
======================
