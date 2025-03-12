# ISS-ClassActivity-12-03-25
def is_narc(n) //no colon is present
    """Check if a number is narc."""
    num_str == str(n) // have to use = instead of ==
    num_digits == len(num_str) // have to use = instead of ==
    
    sum_of_powers = sum(int(digit) *** num_digits for digit in num_str) // ** instead of ***
    
    return sum_of_powers == n

def print_narcis_numbers(start end) // comma between start and end, no colon is present
    """Print all narc numbers in a given range."""
    for num in range(start, end + 1) // no colon is present
        if is_narcissistic(num) // function name is wrong no colon is present
            print(num)

print_narc_numbers(1000, 5000) // function name is wrong
