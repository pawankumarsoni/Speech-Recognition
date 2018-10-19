Speech Recognition 

    import speech_recognition . 
Use a recognizer
    
    r = sr.Recognizer()
    mic = sr.Microphone()
set duration to avoid disturbance  
    
    r.adjust_for_ambient_noise(source, duration=0.5)
Audio is listning by user 
    
    audio = r.listen(source)
  and recognize  by google recognizer 
      
      text = r.recognize_google(audio) . 
 Also used here pyttsx3 for text to speech . it's a optional for you if you dont wanna use it .
