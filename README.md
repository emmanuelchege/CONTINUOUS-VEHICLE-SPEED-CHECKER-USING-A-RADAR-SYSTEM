# CONTINUOUS-VEHICLE-SPEED-CHECKER-USING-A-RADAR-SYSTEM
Arduino based radar system to compute the speed of the cars and capture the number plate of cars driving over the speed limit

One of the major contributing factors to road accidents is over speeding. The current
method that is being used to curb over speeding in Kenya has proved to be ineffective
because it does not operate throughout the day. It is therefore important to have a new
and efficient system that will decrease the number of accidents caused by over speeding
I used a radar system to compute the speed of the cars and capture the number plate
of cars driving over the speed limit. The system met our specifications in an efficient way
with a simple continuous radar circuit that provides the signal in the form of an
electromagnetic wave. This is what is used to detect a moving vehicle. The output of the
radar is an intermediate frequency signal.
The intermediate frequency signal from our radar module, which is in the order of
microvolts, passes through an amplifying circuit which amplifies it to a level which can be
processed. We fabricated the circuit on a printed circuit board which was merged with a
liquid crystal display for displaying the speed.
The signal is then processed by the Arduino microcontroller and this is where the vehicle’s
speed is computed. A threshold speed is set such that if a vehicle is moving at a speed
above the threshold, our microcontroller will activate the camera to take a picture. The
picture will then be stored in a micro secure digital card which can be retrieved by the
relevant authorities
This is a stand-alone system which is portable and therefore can be mounted at different
points on the road. This will ensure speed detection throughout the day.
