#

- It seems the simplest approach to make tflite run in kivy would be to work with the tensorflow project itself.

- Pending that, the tflite AAR apparently has java, c, and c++ libraries.

- It's likely reasonable to build the tflite_runtime python binary to link to the interface in the .aar somehow.
