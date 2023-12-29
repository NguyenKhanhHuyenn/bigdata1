# Vehicle Speed Detection

- This is a python script to detect the speed of multiple vehicles on multi-lane highways.
- It uses Haar Cascade Classifier to detect vehicles in every nth frame.
- It removes unnecessary portions from the image to speed up processing.
- Two reference lines have been set, one for vehicle entry and one for exit.
- When any vehicle in any lane crosses the entry point, the time is recorded, and the vehicle is tracked.
- Tracking is done using centroid tracking techniques.
- Time is recorded when the vehicles cross the exit line.
- Based on the time difference, the vehicle's speed is estimated.

**Note:** A detailed version of this project also exists. Check out my other repositories.
