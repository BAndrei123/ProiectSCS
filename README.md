The main goal of this project is to develop a web-based security camera
system that can effectively signal the presence of people or any unusual objects
within an area that is expected to be empty. This innovative solution addresses
the growing need for advanced surveillance and threat identification in various
settings, from home security to commercial spaces and public areas.
With the advent of accessible web technologies and the proliferation of webcams and IP cameras, there is a demand for a user-friendly, web-based security
system that can serve as an extra set of vigilant eyes, notifying users of any
unusual or suspicious activities.

This project leverages several technologies to create a robust security camera
interface. The core of the object detection functionality is powered by COCOSSD, a pre-trained model from TensorFlow.js that excels in recognizing common
objects in real time. Vue.js, a progressive JavaScript framework, is employed
to structure the user interface, manage the component’s state using the Composition API, and seamlessly update the DOM based on detected objects. The
scoped styles define the visual presentation, ensuring a clean and user-friendly
layout. The integration of the TensorFlow.js library with Vue.js allows for the
dynamic and responsive handling of the webcam feed, enabling the detection
of multiple objects, particularly focusing on individuals. The project also employs asynchronous loading of the COCO-SSD model, ensuring a smooth user 
experience by displaying a loading spinner until the model is fully loaded. Additionally, an emergency alarm, triggered upon the detection of a person, adds
a real-world security element to the application. Overall, this project demonstrates a synergy between machine learning capabilities and a modern frontend
framework to create a powerful and accessible security camera application.
