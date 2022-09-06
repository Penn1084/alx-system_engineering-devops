alias ls="rm *" a script that creates an alias.
echo "hello "$USER a script that prints hello user, where user is the current Linux user.
PATH=$PATH:/action Add /action to the PATH. /action should be the last directory the shell looks into when looking for a program.
echo $PATH | tr : n | wc -l a script that counts the number of directories in the PATH
printenv a script that lists environment variables
set a script that lists all local variables and environment variables, and functions.
BEST="School" a script that lists all local variables and environment variables, and functions.
export School="BEST" a script that creates a new global variable.
echo $((TRUEKNOWLEDGE + 128)) a script that prints the result of the addition of 128 with the value stored in the environment variable TRUEKNOWLEDGE, followed by a new line.
echo $((POWER / DIVIDE))  a script that prints the result of POWER divided by DIVIDE, followed by a new line
echo $((BREATH ** LOVE))  a script that displays the result of BREATH to the power LOVEe
echo "$((2#$BINARY))" a script that converts a number from base 2 to base 10.
echo {a..z}{a..z} | tr " " "\n" | grep -v "oo"" a script that prints all possible combinations of two letters, except oo.
printf "%.2f\n" $NUM a script that prints a number with two decimal places, followed by a new line. The number will be stored in the environment variable NUM.
printf %xn $DECIMAL a script that converts a number from base 10 to base 16.
tr A-Za-z N-ZA-Mn-za-m a script that encodes and decodes text using the rot13 encryption. Assume ASCII.
