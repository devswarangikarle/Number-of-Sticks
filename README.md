# Number-of-Sticks
A frog named Rocher has a collection of n sticks, each with a unique length i for all 1≤i≤n. Rocher has the ability to connect two sticks, resulting in a new stick with a length equal to the sum of the lengths of the connected sticks. This process involves selecting two sticks of lengths a and b

# Function to calculate the maximum number of sticks with the same length
def max_sticks_with_same_length(n):
    # Calculate the maximum number of sticks with the same length using pairing
    max_same_length_sticks = min(n // 2 + 1, n - n // 2)

    return max_same_length_sticks

n = int(input())

result = max_sticks_with_same_length(n)
print(result)
