# Sorting-Visualizer
Visualizing algorithms provides a more profound understanding of their inner workings. 

This project utilizes ReactJS to create visual representations of several timeless sorting algorithms, including Bubble Sort, Selection Sort, and Insertion Sort.

( NOTE:  Enable hardware acceleration in Chrome for smooth transition effect. )

# Components Overview
The project is structured around four primary components:

1. **Header:** This component features an animated display of the text "Sorting Visualizer."
![Header](https://i.imgur.com/QF8g3lE.gif)

2. **Buttons Bar:** Within this component, several buttons are provided to initiate the visualization of sorting algorithms.
![Buttons Bar](https://i.imgur.com/3ilPL5x.png)

3. **Array Bar:** This component serves as the canvas for visualizing the sorting algorithm, utilizing 3D vertical bars.
![Array Bar](https://i.imgur.com/97OaSKz.png)

4. **Range Slider:** This component offers interactive range sliders that enable real-time adjustments to the array size and animation speed.
![Range Slider](https://i.imgur.com/XhLEuFy.gif)

# How Do Animations Function?
During the sorting process, we populate an "animations" array with specific indexes from the array being sorted and boolean values. These indexes correspond to the elements being compared and the elements' final positions. The boolean values, "doSwap" and "isFinal," indicate whether an element is currently being compared or has reached its final sorted position. 

Subsequently, we pass this "animations" array to another function responsible for altering the color and size of the bars representing these indexes. These changes are implemented using a `setTimeout()` function to introduce a delay, making the transitions visible and perceptible.


