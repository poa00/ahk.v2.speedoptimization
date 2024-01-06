# Optimize-AHKv2-Code-for-Speed
Optimize AHKv2 Code for Speed

I'm not going to try to rewrite the original post text, a lot of it is great and should be read from the source https://www.autohotkey.com/boards/viewtopic.php?f=7&t=6413
Many of the conventions such as #NoEnv and #SetBatchLines are defunct, but the rest is very valuable. 
I have restructured the tests for ahkv2. 

tests include:
- a few tips for IF checking of Boolean values
- Avoid spreading math over multiple lines and using variable for intermediate results if they are only used once. As much as possible condense math into one line and only use variables for storing math results if you need the results being used multiple times later.
- Terinary
- Variable expressions