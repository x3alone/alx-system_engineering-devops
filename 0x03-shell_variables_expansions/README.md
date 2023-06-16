
#!/bin/bash
alias ls="rm *"

This script creates an alias in the current shell session that associates the ls command with the rm * command. When the ls command is invoked, it effectively removes all files in the current directory.


#!/bin/bash
printf '%x\n' $DECIMAL

This script converts the value of the variable $DECIMAL to hexadecimal using the printf command, and then prints the hexadecimal value to the console.

#!/bin/bash
tr 'A-Za-z' 'N-ZA-Mn-za-m'

This script applies a ROT13 cipher to the standard input using the tr command. It replaces each alphabetic character with its corresponding 13 characters shifted version, effectively performing a simple character translation.


3-paths


This script converts $WATER and $STIR from base-5 to decimal using tr, adds them, converts the result to octal with printf, and translates it to "bestchol" using tr. The resulting string is printed.

#!/bin/bash
echo $((BREATH**$LOVE))

This script performs an exponentiation operation. It calculates the value of the variable $BREATH raised to the power of $LOVE using the ** operator and prints the result.

#!/bin/bash
echo "Hello, $USER"

This script prints a greeting message to the console. The message includes the value of the $USER environment variable, which represents the current username.

#!/bin/bash
export PATH=$PATH:/action

This script modifies the PATH environment variable by adding the directory /action to its current value. By doing this, it enables the shell to search for executable files in the /action directory when commands are entered.

#!/bin/bash
export PATH=$PATH:/action

This script is identical to Script 7. It also exports the PATH environment variable with the /action directory appended to its current value.

#!/bin/bash
printenv

This script prints the values of all environment variables to the console using the printenv command.

#!/bin/bash
set

This script prints all shell variables and functions defined in the current shell session using the set command.


#!/bin/bash
BEST="School"

This script assigns the value "School" to the variable $BEST. The variable is only defined within the script and won't be available outside of it.

#!/bin/bash
export BEST=School

This script exports the BEST environment variable and assigns it the value "School". The variable becomes available to other processes and subshells.

#!/bin/bash
echo $(($TRUEKNOWLEDGE + 128))

This script performs an arithmetic operation. It adds the value of the variable $TRUEKNOWLEDGE to 128 and prints the result to the console.

#!/bin/bash
echo $(($POWER / $DIVIDE))
0x03. Shell, init files, variables and expansions

This script performs an arithmetic operation. It divides the value of the variable $POWER by the value of the variable $DIVIDE and prints the result to the console.




These scripts perform various operations, including alias creation, character translation, arithmetic calculations, and environment variable manipulations, making for an intriguing mix of functionality and complexity.

