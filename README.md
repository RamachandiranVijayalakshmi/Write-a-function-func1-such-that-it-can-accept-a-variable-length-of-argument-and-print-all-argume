## Write-a-function-func1-such-that-it-can-accept-a-variable-length-of-argument-and-print-all-argument
## Sample code to check the details 
```sh
def func1(*args):
    for i in args:
        print(i)

func1(20, 40, 60)
func1(80, 100)
```
## Example Output
After func1(20, 40, 60):

20
40
60

After func1(80, 100):

80
100

