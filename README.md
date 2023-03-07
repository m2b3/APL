# APL
automated preferential looking

**March 7th - Created document Project.md.. this contains a description of the first set of tasks.**

Accurate and efficient measurement of visual function is difficult in infants and young children because of limited cooperation, inability to provide cognitive verbal responses and lack of efficient behavioural methods. This is important in the clinical and research context where detection and treatment of eye conditions in infancy is dependent on measurement of visual function. Visual deprivation in infants disrupts normal visual development and affects multiple visual functions that are important in visually guided behaviors in everyday life such as contrast sensitivity, motion perception, contour integration, and face recognition. At present there are no reliable automated objective methods for measuring visual functions in infants and young children below the age of 3 years.

This project, continuing on from GSoC 2022, will address these limitations. Last year’s GSoC project with Ioannis Valasakis made progress towards developing an API to handle communication with a hardware-based Tobii eye-tracker (GitHub - wizofe/ao-baby-tracker: Google Summer of Code 2022 - Eye tracking project for neonates 9). This year, we will work towards bringing this project towards a proof of concept. The project involves a) the development of an application with a suite of visual stimuli and analytical procedures to probe multiple visual functions; b) incorporating and further developing a deep-learning based infant eye-tracker (https://github.com/yoterel/icatcher_plus) and c) developing a GUI and controller that holds the display, eye-tracking and analysis components together.

The infant's gaze location is the experimental data that is used to guide the next stimulus that will be displayed, as well as analyzed to indicate whether the infant looked at the "correct" stimulus or not.

https://github.com/yh-luo/psychopy_tobii_infant is quite close to the principle of what we want to do. 

Skill level: Intermediate/advanced

Required skills: Comfortable with Python. Experience with image/video processing and using deep-learning based image-processing models. Ideally, also comfortable with Android/iOS app development and especially ARKit/equivalent, but not necessary.

Time commitment: Full-time (350 h)

Lead mentor: Arvind Chandna

Project website: GitHub - wizofe/ao-baby-tracker: Google Summer of Code 2022 - Eye tracking project for neonates 9

Backup mentors: Suresh Krishna

Tech keywords: Health AI, Infant vision, Image processing, App development, Python, health AI, IOS/Android
