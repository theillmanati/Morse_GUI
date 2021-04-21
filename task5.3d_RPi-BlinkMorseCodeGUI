from tkinter import *
import tkinter.font
from gpiozero import LED
import RPi.GPIO as GPIO
import time
GPIO.setmode(GPIO.BCM)

# HARDWARE #
led = LED(10)

# GUI DEFINITIONS #
win = Tk()
win.title("Morse Code Converter")
stdFont = tkinter.font.Font(family = 'Helvetica', size = 12, weight = "bold")

# MORSE VARIABLES #
dot = 0.33
dash = 1
pauseMidCharacter = 0.33
pauseToEndCharacter = 1
pauseToEndWord = 1.67

# Limit the input to 15 characters
var = StringVar()
max_char = 15
def limit_char(*args):
    input = var.get()
    if len(input) > max_char:
        var.set(input[:max_char])
var.trace_variable("w", limit_char)

# FUNCTIONS #
# Blinks dot
def blinkDot():                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             
    led.on()
    time.sleep(dot)
    led.off()

# Blinks dash
def blinkDash():
    led.on()
    time.sleep(dash)
    led.off()
   
def blinkMorse(character):
    if character == "a":
        blinkDot()
        time.sleep(pauseMidCharacter)
        blinkDash()
        time.sleep(pauseToEndCharacter)
        
    elif character == "b":
        blinkDash()
        time.sleep(pauseMidCharacter)
        blinkDot()
        time.sleep(pauseMidCharacter)
        blinkDot()
        time.sleep(pauseMidCharacter)
        blinkDot()
        time.sleep(pauseToEndCharacter)
        
    elif character == "c":
        blinkDash()
        time.sleep(pauseMidCharacter)
        blinkDot()
        time.sleep(pauseMidCharacter)
        blinkDash()
        time.sleep(pauseMidCharacter)
        blinkDot()
        time.sleep(pauseToEndCharacter)
        
    elif character == "d":
        blinkDash()
        time.sleep(pauseMidCharacter)
        blinkDot()
        time.sleep(pauseMidCharacter)
        blinkDot()
        time.sleep(pauseToEndCharacter)
    
    elif character == "e":
        blinkDot()
        time.sleep(pauseToEndCharacter)
        
    elif character == "f":
        blinkDot()
        time.sleep(pauseMidCharacter)
        blinkDot()
        time.sleep(pauseMidCharacter)
        blinkDash()
        time.sleep(pauseMidCharacter)
        blinkDot()
        time.sleep(pauseToEndCharacter)    
    
    elif character == "g":
        blinkDash()
        time.sleep(pauseMidCharacter)
        blinkDash()
        time.sleep(pauseMidCharacter)
        blinkDot()
        time.sleep(pauseToEndCharacter)
    
    elif character == "h":
        blinkDot()
        time.sleep(pauseMidCharacter)
        blinkDot()
        time.sleep(pauseMidCharacter)
        blinkDot()
        time.sleep(pauseMidCharacter)
        blinkDot()
        time.sleep(pauseToEndCharacter)
        
    elif character == "i":
        blinkDot()
        time.sleep(pauseMidCharacter)
        blinkDot()
        time.sleep(pauseToEndCharacter)
        
    elif character == "j":
        blinkDot()
        time.sleep(pauseMidCharacter)
        blinkDash()
        time.sleep(pauseMidCharacter)
        blinkDash()
        time.sleep(pauseMidCharacter)
        blinkDash()
        time.sleep(pauseToEndCharacter)
        
    elif character == "k":
        blinkDash()
        time.sleep(pauseMidCharacter)
        blinkDot()
        time.sleep(pauseMidCharacter)
        blinkDash()
        time.sleep(pauseToEndCharacter)
        
    elif character == "l":
        blinkDot()
        time.sleep(pauseMidCharacter)
        blinkDash()
        time.sleep(pauseMidCharacter)
        blinkDot()
        time.sleep(pauseMidCharacter)
        blinkDot()
        time.sleep(pauseToEndCharacter)
        
    elif character == "m":
        blinkDash()
        time.sleep(pauseMidCharacter)
        blinkDash()
        time.sleep(pauseToEndCharacter)
    
    elif character == "n":
        blinkDash()
        time.sleep(pauseMidCharacter)
        blinkDot()
        time.sleep(pauseToEndCharacter)
        
    elif character == "o":
        blinkDash()
        time.sleep(pauseMidCharacter)
        blinkDash()
        time.sleep(pauseMidCharacter)
        blinkDash()
        time.sleep(pauseToEndCharacter)
        
    elif character == "p":
        blinkDot()
        time.sleep(pauseMidCharacter)
        blinkDash()
        time.sleep(pauseMidCharacter)
        blinkDash()
        time.sleep(pauseMidCharacter)
        blinkDot()
        time.sleep(pauseToEndCharacter)
        
    elif character == "q":
        blinkDash()
        time.sleep(pauseMidCharacter)
        blinkDash()
        time.sleep(pauseMidCharacter)
        blinkDot()
        time.sleep(pauseToEndCharacter)
        
    elif character == "r":
        blinkDot()
        time.sleep(pauseMidCharacter)
        blinkDash()
        time.sleep(pauseMidCharacter)
        blinkDot()
        time.sleep(pauseToEndCharacter)
    
    elif character == "s":
        blinkDot()
        time.sleep(pauseMidCharacter)
        blinkDot()
        time.sleep(pauseMidCharacter)
        blinkDot()
        time.sleep(pauseToEndCharacter)
        
    elif character == "t":
        blinkDash()
        time.sleep(pauseToEndCharacter)
        
    elif character == "u":
        blinkDot()
        time.sleep(pauseMidCharacter)
        blinkDot()
        time.sleep(pauseMidCharacter)
        blinkDash()
        time.sleep(pauseToEndCharacter)
        
    elif character == "v":
        blinkDot()
        time.sleep(pauseMidCharacter)
        blinkDot()
        time.sleep(pauseMidCharacter)
        blinkDot()
        time.sleep(pauseMidCharacter)
        blinkDash()
        time.sleep(pauseToEndCharacter)
        
    elif character == "w":
        blinkDot()
        time.sleep(pauseMidCharacter)
        blinkDash()
        time.sleep(pauseMidCharacter)
        blinkDash()
        time.sleep(pauseToEndCharacter)
    
    elif character == "x":
        blinkDash()
        time.sleep(pauseMidCharacter)
        blinkDot()
        time.sleep(pauseMidCharacter)
        blinkDot()
        time.sleep(pauseMidCharacter)
        blinkDash()
        time.sleep(pauseToEndCharacter)
    
    elif character == "y":
        blinkDash()
        time.sleep(pauseMidCharacter)
        blinkDot()
        time.sleep(pauseMidCharacter)
        blinkDash()
        time.sleep(pauseMidCharacter)
        blinkDash()
        time.sleep(pauseToEndCharacter)
    
    elif character == "z":
        blinkDash()
        time.sleep(pauseMidCharacter)
        blinkDash()
        time.sleep(pauseMidCharacter)
        blinkDot()
        time.sleep(pauseMidCharacter)
        blinkDot()
        time.sleep(pauseToEndCharacter)
        
    elif character == "1":
        blinkDot()
        time.sleep(pauseMidCharacter)
        blinkDash()
        time.sleep(pauseMidCharacter)
        blinkDash()
        time.sleep(pauseMidCharacter)
        blinkDash()
        time.sleep(pauseMidCharacter)
        blinkDash()
        time.sleep(pauseToEndCharacter)
        
    elif character == "2":
        blinkDot()
        time.sleep(pauseMidCharacter)
        blinkDot()
        time.sleep(pauseMidCharacter)
        blinkDash()
        time.sleep(pauseMidCharacter)
        blinkDash()
        time.sleep(pauseMidCharacter)
        blinkDash()
        time.sleep(pauseToEndCharacter)
    
    elif character == "3":
        blinkDot()
        time.sleep(pauseMidCharacter)
        blinkDot()
        time.sleep(pauseMidCharacter)
        blinkDot()
        time.sleep(pauseMidCharacter)
        blinkDash()
        time.sleep(pauseMidCharacter)
        blinkDash()
        time.sleep(pauseToEndCharacter)
    
    elif character == "4":
        blinkDot()
        time.sleep(pauseMidCharacter)
        blinkDot()
        time.sleep(pauseMidCharacter)
        blinkDot()
        time.sleep(pauseMidCharacter)
        blinkDot()
        time.sleep(pauseMidCharacter)
        blinkDash()
        time.sleep(pauseToEndCharacter)
    
    elif character == "5":
        blinkDot()
        time.sleep(pauseMidCharacter)
        blinkDot()
        time.sleep(pauseMidCharacter)
        blinkDot()
        time.sleep(pauseMidCharacter)
        blinkDot()
        time.sleep(pauseMidCharacter)
        blinkDot()
        time.sleep(pauseToEndCharacter)
        
    elif character == "6":
        blinkDash()
        time.sleep(pauseMidCharacter)
        blinkDot()
        time.sleep(pauseMidCharacter)
        blinkDot()
        time.sleep(pauseMidCharacter)
        blinkDot()
        time.sleep(pauseMidCharacter)
        blinkDot()
        time.sleep(pauseToEndCharacter)
    
    elif character == "7":
        blinkDash()
        time.sleep(pauseMidCharacter)
        blinkDash()
        time.sleep(pauseMidCharacter)
        blinkDot()
        time.sleep(pauseMidCharacter)
        blinkDot()
        time.sleep(pauseMidCharacter)
        blinkDot()
        time.sleep(pauseToEndCharacter)
    
    elif character == "8":
        blinkDash()
        time.sleep(pauseMidCharacter)
        blinkDash()
        time.sleep(pauseMidCharacter)
        blinkDash()
        time.sleep(pauseMidCharacter)
        blinkDot()
        time.sleep(pauseMidCharacter)
        blinkDot()
        time.sleep(pauseToEndCharacter)
    
    elif character == "9":
        blinkDash()
        time.sleep(pauseMidCharacter)
        blinkDash()
        time.sleep(pauseMidCharacter)
        blinkDash()
        time.sleep(pauseMidCharacter)
        blinkDash()
        time.sleep(pauseMidCharacter)
        blinkDot()
        time.sleep(pauseToEndCharacter)
    
    elif character == "0":
        blinkDash()
        time.sleep(pauseMidCharacter)
        blinkDash()
        time.sleep(pauseMidCharacter)
        blinkDash()
        time.sleep(pauseMidCharacter)
        blinkDash()
        time.sleep(pauseMidCharacter)
        blinkDash()
        time.sleep(pauseToEndCharacter)
    
    elif character.isspace():
        time.sleep(pauseToEndWord)

# Runs the program to blink the words in Morse code
def run():
    text = entryField.get()
    for x in text.lower():
        blinkMorse(x)
    
# Closes program
def close():
    GPIO.cleanup()
    win.destroy()
    
# WIDGET #
Line1 = Label(win, text = "Enter text to convert to Morse code:", font = stdFont)
Line1.grid(row = 0, column = 0)

entryField = Entry(win, textvariable = var)
entryField.grid(row = 0, column = 1)

buttonMorseConverter = Button(win, text = "Convert to Morse", font = stdFont, command = run, height = 1, width = 20)
buttonMorseConverter.grid(row = 0, column = 2)

exitButton = Button(win, text = "Exit", font = stdFont, command = close, height = 1, width = 6)
exitButton.grid(row = 1, column = 1)

win.protocol("WM_DELETE_WINDOW", close) # Closes window cleanly when clicking X in top corner
win.mainloop() # Keep GUI running by looping forever.
