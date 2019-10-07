# Calend
Calendar application for BipOS 

#Intro
From version MNVolkov BipOS 0.5 the startup code of the applications is completely redisigned. Each application now is a separate file stored in resources. The executable file format is Arm-elf (or simply"elf"). The mod got a new name BipOS. When the MOD starts, resources are scanned for applications. Each firmware has a different amount of resources, and applications are always placed at the end. Therefore, the loader looks for resources by Elf signature starting with resource 930. Found applications are placed in the menu "Applications".

The algorithm for calculating the day of the week works for any date in the Gregorian calendar. The range of the calendar from 1600 to 3000 years.At startup, the current month is displayed, the current day is highlighted in color. There is ability to select another period through turning: swipe left-right to switch the months, swipe up and down - switch the years.

More information at https://myamazfit.ru/threads/bip-application-develop-for-bipos-sdk-en.1171/
