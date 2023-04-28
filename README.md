# xscreenlock

Simple script to lock the screen after some idle time and reset to a specific virtual desktop.

## Usage

~~~
Usage: xlockscreen [OPTION]...
Lock the screen with xtrlock after idle time.

  -i DURATION_IN_SECONDS	Lock the screen after being idle for DURATION_IN_SECONDS.
				If this option is missing then the default duration is 15 minutes.

  -d DESKTOP_ID			Switch to the indicated virtual desktop before lock.

  -c DURATION_IN_SECONDS	Duration in seconds between 2 idle time check.
				If this option is missing then the default duration is 10 seconds.

Dependencies: xprintidle, xtrlock.
~~~