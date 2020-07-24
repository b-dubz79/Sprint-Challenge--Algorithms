#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) O(1)


b) O(n)


c) O(n)

## Exercise II
# create function that takes in 2 numbers: total floors(n) and egg breaker floor(f)
# set f equal to n so it's the top floor
# that will minimize the broken eggs since theres only one floor that they can break from

# divide n by 2
# drop one egg from the n/2 value
# if the egg doesn't break, 1 through n/2 is eliminated
    # set the current floor as the new bottom floor
    # divide n by current floor, this is the new mid point
    # drop egg and if it doesn't break, repeat steps above
# If the egg breaks, n/2 through n is eliminated
    # set current floor as new top floor
    # divide new top floor by 2, this is new mid point
    # drop egg and if it doesn't break, repeat 2 steps
        # if it does break repeat the steps above for the non-breaking scenario

This solution would be log(n)

