# hackfinity
Hackathon submission</br>
main.py and key.py are the programs to be run on pc or laptop and espa8266 file is for nodemcu for iot application like turn on and off lights etc

## How to:
- first install python modules like: pyttsx3 , speech_recognition , wikipedia , httplib2 , keyboard , pynput , pyautogui , webbrowser and pyaudio can be easily installed with commands like : pip install module_name
- burn esp8266 file program on your esp8266 or any similar wifi module for operations like turn lights on and off etc. For this you need to uncomment these lines too:</br>
url_on = 'http://192.168.43.118/gpio/1'</br>
url_off = 'http://192.168.43.118/gpio/0'</br>
response, content = http.request(url_off, 'GET')</br>
- Thats it you are ready to go


