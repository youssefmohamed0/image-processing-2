# Report on diffrent edge dettection methods

Three diffrent edge detection methods were tested on the following image and their results were analyzed

![original-image](images/cube.jpg)

## Laplacian Edge detection method

![original-image](images/cube.jpg)
![Laplacian](edge_images/laplacian_cube.jpg)

Laplacian edge detection seems to work well on surfaces with little noise and clear color contrast, such as on the the white faces with clear black digits.

Shiny digits such as those on the blue and red faces are barely recognizable, with the red face being totaly unreadable


## Sobel edge detection

![original-image](images/cube.jpg)
![sobel](edge_images/sobel_cube.jpg)

Sobel edge detection appearsd to be really blury with non unifom edges, making didigts on white face readable, digits on green face less clear, and digits on red face are not visible

## Canny edge detection

![original-image](images/cube.jpg)
![canny](edge_images/canny_cube.jpg)

Canny edge detection appears to be the most accurate and clear method, showing all digits clearly. The only didgits that are slightly distorted are the ones the red face, but this is probably due to the angle of the image. The only slight disadvantage of canny edge detection method is that since it picks up alot of details, some noise is detected.

## Other examples

![original](images/normal_cat.jpg)
![laplacian](edge_images/laplacian_cat.jpg)

![sobel](edge_images/sobel_cat.jpg)
![canny](edge_images/canny_cat.jpg)