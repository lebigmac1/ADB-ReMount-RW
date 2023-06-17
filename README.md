<h1>Welcome to ADB ReMount-RW v1.2 by lebigmac</h1>

DISCLAIMER: This file may be copied, duplicated, re-uploaded indefinitely as long as this comments section (line #1 - line #30) are not modified or removed by the end-user & proper credit must be given to the original author. Thank you.<br><br>
Description: Remount all device mapper partitions as rw (read/write) or ro (read-only) by lebigmac<br>
Only for rooted, RW-capable devices running Android 8+ !<br>
For more info please visit the official website @
# http://www.systemrw.com
Thanks for your support!
<br><br>
Installation:<br>
   Copy this file into /system/bin/ and give it some permissions -> chmod 777 /system/bin/remount
<br><br>
Usage:<br>
#   adb remount   		        // REMOUNT ALL AS READ/WRITE
#   adb remount rw   	    	// REMOUNT ALL AS READ/WRITE
#   adb remount ro		        // REMOUNT ALL AS READ-ONLY
#   adb remount / rw	      	// REMOUNT SYSTEM AS RW
#   adb remount /product ro	// REMOUNT PRODUCT AS RO
