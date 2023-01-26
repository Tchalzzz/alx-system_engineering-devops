Loops, Conditions and Parsing
This project contains Shell tasks for learning about loops, conditions and parsing using bash.

Tasks To Complete
 0. Create a SSH RSA key pair
0-RSA_public_key.pub contains an RSA public key for connecting to my servers using SSH.
 1. For Best School loop
1-for_best_school contains a Bash script that displays Best School 10 times using the for loop.
 2. While Best School loop
2-while_best_school contains a Bash script that displays Best School 10 times using the while loop.
 3. Until Best School loop
3-until_best_school contains a Bash script that displays Best School 10 times using the until loop.
 4. If 9, say Hi!
4-if_9_say_hi contains a Bash script that displays Best School 10 times, but for the 9th iteration, displays Best School and then Hi on a new line.
 5. 4 bad luck, 8 is your chance
5-4_bad_luck_8_is_your_chance contains a Bash script that loops from 1 to 10 and:
Displays bad luck for the 4th loop iteration.
Displays good luck for the 8th loop iteration.
Displays Best School for the other iterations.
 6. Superstitious numbers
6-superstitious_numbers contains a Bash script that displays numbers from 1 to 20 and:
Displays 4 and then bad luck from China for the 4th loop iteration.
Displays 9 and then bad luck from Japan for the 9th loop iteration.
Displays 17 and then bad luck from Italy for the 17th loop iteration.
 7. Clock
7-clock contains a Bash script that displays the time for 12 hours and 59 minutes:
Display hours from 0 to 12.
Display minutes from 1 to 59.
 8. For ls
8-for_ls contains a Bash script that displays The content of the current directory in a list format where only the part of the name after the first dash is displayed (E.g.; 7-clock displays as clock).
 9. To file, or not to file
9-to_file_or_not_to_file contains a Bash script that gives you information about the school file.
It should check if the file exists and print:
if the file exists: school file exists.
if the file does not exist: school file does not exist.
If the file exists, print:
if the file is empty: school file is empty.
if the file is not empty: school file is not empty.
if the file is a regular file: school is a regular file.
if the file is not a regular file: (nothing).
 10. FizzBuzz
10-fizzbuzz contains a Bash script that displays numbers from 1 to 100.
Displays FizzBuzz when the number is a multiple of 3 and 5.
Displays Fizz when the number is multiple of 3.
Displays Buzz when the number is a multiple of 5.
Otherwise, displays the number.
 11. Read and cut
100-read_and_cut contains a Bash script that displays the content of the file /etc/passwd. The script should only display:
username
user id
Home directory path for the user.
 12. Tell the story of passwd
101-tell_the_story_of_passwd contains a Bash script that displays the content of the file /etc/passwd, using the while loop + IFS (Internal Field Separator). Format:
The user <USERNAME> is part of the <GROUP_ID> gang, lives in <HOME_DIRECTORY> and rides <COMMAND/SHELL>. <USER ID>'s place is protected by the passcode <PASSWORD>, more info about the user here: <USER ID INFO>
 13. Let's parse Apache logs
102-lets_parse_apache_logs contains a Bash script that displays the visitor IP along with the HTTP status code from the Apache log file using awk. Format: IP HTTP_CODE.
 14. Dig the data
103-dig_the-data contains a Bash script that groups visitors by IP and HTTP status code (using the output from the previous task), and displays this data using awk. Format: OCCURENCE_NUMBER IP HTTP_CODE. Ordered from the greatest to the lowest number of occurrences
