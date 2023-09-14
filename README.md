# Decisions-decider
# eight ball random generator
# first create a tuple
choices = {"Yes","No"}
# create random function that uses said function
def decisions():
    # empty list for output
    output = []
    # create for loop that runs on choices tuple
    # store output in a list
    for x in choices:
        rounds = [x]
        # store rounds in output
        output = output + rounds
        # condition to decide what to do
        if output[0] == "Yes":
            print(output[0] + ", LET'S DO THIS!!!")
            break
        if output[0] == "No":
            print("better luck next")
            break

# calling decisions function
decisions()
