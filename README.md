This is an iOS Universal Framework wrapper (based on Karl Stenerud's [templates](https://github.com/kstenerud/iOS-Universal-Framework)) for Kim Walisch's [primesieve](http://primesieve.org) lib (version 5.3, the latest). It supports 32/64 bit simulators and devices (armv7 armv7s arm64 i386 x86_64).

#### Usage

1. Clone this repo and open PrimeSieveM project using Xcode.
2. Choose "Product | Archive" from main menu.
3. Copy PrimeSieveM.framework from the popup Finder window to your project folder.
4. Drop the framework in your project's Frameworks group and link it to your target.
5. Include the main header in your code:
   ```c
   #include <PrimeSieveM/primesieve.h>
   ```
Enjoy!
