# MP3Dec
MP3Dec uses the Javazoom library to decode MP3 streams of FM radio channels and write chunks of decoded data that is used for IVR on Mobile.

The stream were found to be unreliable and disconnected or got stuck often. So to handle that I used watchdog mechanism to identify the stuck thread, kill and restart it.

###
The main file is \src\javazoom\jl\converter\jlc.java

To run use the following command-
java -jar transcode.jar
