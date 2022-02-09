import math
 
 
def pattern_creator(input):
    for iteration in range(input + 2):  # Create range to loop through
        if iteration in [0, input + 1]:  # Set full rows of #
            print("#" * input)  # Print full row of "#"
        elif iteration <= math.ceil(input / 2):  # Set the top half of the Pattern
            pattern_list = list(" " * input)  # Create empty list
            pattern_list[iteration - 1] = "#"  # Put first # in correct spot
            pattern_list[input - iteration] = "#"  # Put 2nd # in correct spot
            pattern = ''.join(
                str(list_iteration) for list_iteration in pattern_list)  # Change list to string with no spaces
            print(pattern)  # Print string
        else:  # Set bottom half of pattern
            pattern_list = list(" " * input)  # Create empty list
            pattern_list[input - iteration] = "#"  # Put first # in correct spot
            pattern_list[input - (input - iteration + 1)] = "#"  # Put 2nd # in correct spot
            pattern = ''.join(
                str(list_iteration) for list_iteration in pattern_list)  # Change list to string with no spaces
            print(pattern)  # Print string
 
 
pattern_creator(13)
