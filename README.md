# Blank Isos
Blank ISOS. :package: + :cd: = Blank_Isos

~~~sh
$ git clone https://github.com/Ganesha2282882/Blank_Isos.git
$ cd Blank_Isos
~~~

Enough intro, let's recreate it.

Keep in mind that these steps only work on Ubuntu (maybe Debian).

1. Install Mkisofs:
  `sudo apt install mkisofs`
  
2. Create a folder on your desktop called 'blank'.
  Don't put anything in it.

3. Execute this on your desktop:

    For a .iso:
      `mkisofs -o blank.iso ~/Desktop/blank`

    For a .img:
      `mkisofs -o blank.img ~/Desktop/blank`
      
4. Done!

If you are on Windows or Mac, Just download it.
