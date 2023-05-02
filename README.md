# xlockscreen

Simple script to lock the screen after some idle time and reset the current virtual desktop to a specific one.
The screen locking is performed is <https://salsa.debian.org/debian/xtrlock>.
This is typically used for demo and test screens supposed to run 24/7.

## Usage

~~~
Usage: xlockscreen [OPTION]...
Lock the screen with xtrlock after some idle time.

  -i DURATION_IN_SECONDS	Lock the screen after being idle for DURATION_IN_SECONDS.
				If this option is missing then the default duration is 15 minutes.

  -d DESKTOP_ID			Switch to the indicated virtual desktop before lock.

  -c DURATION_IN_SECONDS	Duration in seconds between 2 idle time check.
				If this option is missing then the default duration is 10 seconds.

Dependencies: xprintidle, xtrlock.
~~~
