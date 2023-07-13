# RWTH Gym Occupancy

The RWTH Gym Occupancy api endpoint returns an Image containing the number of people in the gym.

This API wrapper matches the Image against the saved images in [pics/](pics/) by comparing the pixels and returning the digits which match best.

## Why not OCR?

Every OCR library downloads a machine learning model, which is very unnecessary for this purpose.