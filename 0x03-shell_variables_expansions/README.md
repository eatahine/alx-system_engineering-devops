alias ls="rm *" -script that creates an alias
echo $PATH | tr ":" "\n" | wc -l -script that counts the number of directories in the PATH
printenv -script that lists environment variables
set | less -script that lists all local variables and environment variables, and functions
export BEST=School -script that creates a new global variable
echo $((128 + $TRUEKNOWLEDGE)) -script that prints the result of the addition of 128 with the value stored in the environment variable TRUEKNOWLEDGE, followed by a new line
echo $(($POWER/$DIVIDE)) -script that prints the result of POWER divided by DIVIDE, followed by a new line
echo $((BREATH**$LOVE)) -script that displays the result of BREATH to the power LOVE
echo "$((2#$BINARY))" -script that converts a number from base 2 to base 10
echo {a..z}{a..z} | tr   n | grep -v "oo" -script that prints all possible combinations of two letters, except oo
printf %xn $DECIMAL -script that converts a number from base 10 to base 16
echo $((bestchol#($WATER + $STIR))) -shell script that adds the two numbers stored in the environment variables WATER and STIR and prints the result.
102-odd -script that prints every other line from the input, starting with the first line
12-combinations -script that prints all possible combinations of two letters, except oo
