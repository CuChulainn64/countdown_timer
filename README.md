# countdown_timer
a simple countdown timer for use on streams
The file you want to open is timer3.exe.
Enter the time when you want the timer to end. Not how long you want the timer to run.
The timer defaults to 5:00pm. If you enter a time that has already passed,
for example, you enter 9:00pm at 9:05pm, the timer will count down to the target time on the following day.

Time is outputed to the file "Timer.txt" on each tick. Add that file as a text source 
to include it on stream.

When the timer reaches 0 an alarm will sound, if the "Use alarm" check box is checked.
This alarm can be replaced with any .wav file as long as it's named "alarm.wav" and placed
on the program's directory.

If no alarm.wav file is found, the program will instead play the windows beep sound.
