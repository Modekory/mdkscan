# rep-mdkscan
Simple scanner-bruteforcer websites

Now you will see a short training course on using the program: mdkscan
Do not use the program for criminal purposes!
Here is the full form of the program launch:
./mdkscan -l <link> [-t <task per second> -o <file for logs> -i <injection> -f <format>] -s ("Checking the web server")
example:')
./mdkscan -l example.com #success: http://example.com/abcd
./mdkscan -l example.com -f txt #success: http://example.com/abcd.txt
./mdkscan -l example.com -i user #success: http://example.com/?user=abcd
./mdkscan -l example.com -s -o logs.txt #success: http://example.com/abcd + exampleWebServer 1.33.7 + output in logs.txt
