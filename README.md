# python-recursion-countdown

# Python program to print numbers from n to 0 using recursion

def print_till_zero(n):
    if n < 0:  # Handle negative numbers
        return
    print(n)
    print_till_zero(n - 1)  # Recursive call

# Example usage
n = int(input("Enter a number: "))
print_till_zero(n)


OUTPUT:

Enter a number: 8
8
7
6
5
4
3
2
1
0
