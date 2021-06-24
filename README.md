# EXIT_SUCCESS-and-EXIT_FAILURE
EXIT_SUCCESS, EXIT_FAILURE
 C Program support utilities 
Defined in header <stdlib.h>
#define EXIT_SUCCESS /*implementation defined*/
#define EXIT_FAILURE /*implementation defined*/
The EXIT_SUCCESS and EXIT_FAILURE macros expand into integral expressions that can be used as arguments to the exit function (and, therefore, as the values to return from the main function), and indicate program execution status.

Constant	Explanation
EXIT_SUCCESS	successful execution of a program
EXIT_FAILURE	unsuccessful execution of a program
Notes
Both EXIT_SUCCESS and the value zero indicate successful program execution status (see exit), although it is not required that EXIT_SUCCESS equals zero.
