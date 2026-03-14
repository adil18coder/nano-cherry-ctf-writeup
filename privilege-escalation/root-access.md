# Root Access

After collecting all password parts we were able to access the account of:

chad-cherry

Inside the user's files a suspicious audio file was discovered.

File discovered:

rootPassword.wav

The file contained an SSTV encoded signal.

Using an SSTV decoder tool the audio signal was converted into an image which revealed the root password.

After obtaining the password we switched to the root user.

Command used:

su root

Finally we accessed the root directory.

cd /root

The final flag was located and captured.
