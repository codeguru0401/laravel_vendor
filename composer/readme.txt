- copy composer.phar to certain folder, ex) C:\composer\
- create composer.bat file in same directory.
- open composer.bat and write following content and save it
@ECHO OFF
php "C:\composer\composer.phar" %*

that's all


Open command prompt, then composer -version.
