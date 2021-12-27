# change-calculator

'''Change Return Program - The user enters a cost and then the amount of money given. The program will figure
out the change and the number of 1 rupee, 50 paisa, 25 paisa and 10 paisa coins needed for the change.'''


def change(money):
    
    one_rupee = money
    fifty_paisa = money*2
    twenty_five_paisa = money*4
    ten_paisa = money*10
    
    print("The number of 1 rupee coins: {}".format(one_rupee))
    print("The number of 50 paisa coins: {}".format(fifty_paisa))
    print("The number of 25 paisa coins: {}".format(twenty_five_paisa))
    print("The number of 10 paisa coins: {}".format(ten_paisa))
