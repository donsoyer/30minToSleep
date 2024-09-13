# 30minToSleep
This script will wait for 30 minutes (1800 seconds) and then set the computer into sleep mode immediately.

    @echo off
    timeout /t 1800 /nobreak
    rundll32.exe powrprof.dll,SetSuspendState 0,1,0
