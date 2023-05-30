from stanfordkarel import *
def main():
    turn_left()
    pick_beeper()
    for i in range(4):
      move()
      pick_beeper()
    turn_left()
    for i in range(4):
       move()
    pick_beeper()
    turn_left()
    for i in range(4):
       move()
       pick_beeper()
    def turn_right():
       turn_left()
       turn_left()
       turn_left()    
        
    turn_right()
    for i in range(4):
       move()
    pick_beeper()
    turn_right()
    for i in range(4):
       move()
       pick_beeper()
    turn_left()
    for i in range(4):
       move()
    pick_beeper()
    turn_left()
    for i in range(4):
       move()
       pick_beeper()

if __name__ == "__main__":
    run_karel_program()
