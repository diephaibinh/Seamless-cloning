# Setup

- Step 1: Copy the "input" and "output" folders from the "Data" directory to the "Source code" directory.
    - The structure of the "input" folder:
        - It consists of N folders named: 1, 2, …, N, each containing N sets of test data.
        - Each folder contains 3 images: mask, source, target (all of the same dimensions, where the white region of the mask represents the area to be blended, both in the source image and the position to place it in the target image).
    - The structure of the "output" folder::
        - It consists of N folders named: 1, 2, …, N, each containing results.
        - Each folder contains 2 images: the image after seamless cloning and the image after naive cloning (copy-pasting the object from the source image onto the target image).
- Step 2: Run the program in the command prompt using the command: "python main.py" (you must first navigate to the "Source code" directory).
    => The results will be found in the folders 1, 2, …, in the "output" directory.

* If you want to run a test, go to the folders 1, 2 in the "output" directory, delete the existing result images, and then follow step 2; you will obtain results in the folders 1, 2 in the "output" directory.
