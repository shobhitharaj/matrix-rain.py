import random
import os
import time

chars = "abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789"
width = 80

while True:
    print("".join(random.choice(chars) for _ in range(width)))
    time.sleep(0.05)
