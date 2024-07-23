# Vesta Take-Home Test

**Goal:** Develop a web page that helps users identify the most south-facing side of a roof.

## Input Data

You are given 3 roofs images, together with a file representing the elevation for each pixel of the image.

![image](https://storage.googleapis.com/vesta-users-files/user_files/94f159ea-140f-49d8-b818-7f82850ecd74/satellite_image.png)

Elevation: https://storage.googleapis.com/vesta-users-files/user_files/c6b56988-2c10-4e14-aab9-65141229925b/elevation.blob


![image](https://storage.googleapis.com/vesta-users-files/user_files/b6725f48-3391-4a60-88fc-a2ffcf568fb5/satellite_image.png)

Elevation: https://storage.googleapis.com/vesta-users-files/user_files/eb45febb-1bc3-4fe0-b8e6-463809e32926/elevation.blob


![image](https://storage.googleapis.com/vesta-users-files/user_files/a0953611-da65-4f1e-9c49-52814b512a78/satellite_image.png)

Elevation: https://storage.googleapis.com/vesta-users-files/user_files/0bdc946e-8f48-412c-8d26-75935346e1f7/elevation.blob

> The roof images are always north-oriented

> The elevation files provide the elevation above sea level for each pixel in the image, with each value stored as a 32-bit float. Values represent the elevation of the pixels as you move horizontally across the row from west to east, starting for the north-west corner. Once a row is completed, the next value represents the elevation of the first pixel of the next row to the south.

## Feature Requirements

- Provide an interface for users to upload a roof image and its corresponding elevation file.
- Analyze the uploaded files to determine the most south-facing side of the roof.
- Highlight the most south-facing side of the roof


## Additional Notes
- Produce code that you would confidently deploy into production for real users.
- You are free to use any technology stack to complete this task.

If you have any questions or need further clarification, feel free to reach out. Good luck!