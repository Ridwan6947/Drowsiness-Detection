Our innovative project introduces a cutting-edge Drowsiness Detection System that leverages advanced computer vision techniques to ensure road safety and prevent accidents caused by drowsy driving.
By utilizing a simple webcam, our system calculates Eye Aspect Ratio (EAR) and Mouth Aspect Ratio (MAR) in real-time, providing an accurate assessment of the user's level of drowsiness.

The EAR and MAR metrics serve as crucial indicators of drowsiness, as they analyze the subtle changes in eye and mouth movements that occur when an individual is fatigued or sleepy.
The system continuously monitors these facial features, allowing for early detection of signs of drowsiness, providing a timely alert to the user, and potentially preventing accidents.


My Role

i worked as a full stack developer.
i gained knowledge about flask ,how we create end points and how we route them through this project. 

I created a  Flask web application with two main routes: the home page and the main page. I even  configured the app's settings  by enabling debugging so that if there were any errors we can see them on the browser . 
On the home page, which handles both GET and POST requests, it checks if the request form is equal to the value of "Continue" If so, it renders the "test1.html" template using the render_template module , 
i created the index and test1 files using HTML and css  ; otherwise, it stays on the "index.html" template. 
The main page follows a similar pattern but with a "Start" button, calling a custom function d_dtcn() before rendering the "index.html" template .
This function, d_dtcn(), creates a graphical user interface for a drowsiness detection system using the Tkinter library.
It offers options to run the drowsiness detection system either with a webcam or a phone's camera When I run the script, the web app runs in development mode on port 8080
providing a simple interface for user interactions using different templates and buttons.
