# Mobile-Sensor-Analysis

1. WALKING.csv, TURNING.csv, and WALKING_AND_TURNING.csv contain the sensor data. In columns k -> s, I have smoothed the data using exponentially-weighted moving average with an alpha of 0.9.
    - WALKING.csv contains data gathered while holding the phone face-up and walking in the direction of the top of the phone.
    - TURNING.csv contains data gathered while turning the phone 90 degrees clockwise 4 times and 90 degrees counterclockwise 4 times. 
      The phone was face-up on a table.
    - WALKING_AND_TURNING.csv contains data gathered while walking and turning. All turns are a multiple of 45 degrees in either direction.
  
  2. Steps.ipynb contains the algorithm to find the number of steps contained in WALKING.csv and WALKING_AND_TURNING.csv.
  
  3. Turns.ipynb contains the algorithm to find the number of turns contained in TURNING.csv and WALKING_AND_TURNING.csv.
  
  4. Walking_and_turning.ipyn contains the algorithm to find the number of steps and turns in WALKING_AND_TURNING.csv. The number of steps before each turn are included as well as the angle of each turn.
  
  5. Write-up.docx includes explanations and diagrams for each algorithm as well as the results!
