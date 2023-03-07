As mentioned in the introduction,  the project has 3 components -

1. The eye-tracker component, either based on hardware or a neural network
2. The glue / controller that integrates the application, as well as the associated GUI
3. The visual display component.

The visual display component - 3 - is the most straightforward part, and this is what we can start with.

First, install PsychoPy and go through the manual for both the Builder and the standalone - there are also several tutorials on that page and on Youtube. It is a very straightforward program and easy to learn. We will use it to generate the visual stimuli that we are interested in. It may not work on your desktop or laptop monitor without a warning - you can ignore that. Go through the tutorials to get a basic familiarity and then try to implement the following experiment (with two parts - 1. grating acuity, where spatial frequency is changed systematically until it is visible and 2. contrast sensitivity - where spatial frequency is kept fixed and contrast is increased systematically until it is visible.) 

To determine what is visible, we use the preferential looking test. For the contrast increase case, a high contrast grating is presented on one side of the screen, and nothing on the other side, the infant is expected to look towards the high contrast grating, and this will be detected by the eye-tracker when built. One can start with a low contrast that is rarely detected, and increase the contrast till it is. These increases can also be done via a staircase procedure, which can be implemented later, and this will adjust the contrast on the next trial based on how the infant responds on the previous trials. For now, what is needed is to simply get the basic test procedure right, and some hints can be obtained by looking at this repository with some preliminary attempts - https://github.com/bsureshkrishna/IVA

ps. Each trial is one presentation of a stimulus, with a response made by where the infant looks, as detected by the eye-tracker and coded as to stimulus or away. 

The spatial frequency increase case is similar. Fix the contrast and then vary the spatial frequency. When it is too high, the grating will not be visible. The highest value should be chosen keeping in mind the pixel density of the monitor and avoiding aliasing. The values in the code repository above are fine. As the spatial frequency is decreased, the gratings will be become more visible.  

