# License Plate Recognition (MATLAB)

Automated License Plate Recognition (ALPR) is a technique used in extraction of characters from the vehicle’s license plate. The methods involved in detection of characters differs in various contexts based on the algorithms used and complexity
involved. The approach to extract information using image processing techniques is achieved through Pre-processing, License plate detection, Character segmentation and Recognition. The preprocessing operation mainly involves grayscale conversion of the color image for the faster processing and image enhancement for better results. The detection of license plate is carried out by mean projection technique, which is based on plotting rowise and columnwise means of the given image. The detected license plate region is converted to binary image, through which the characters are segmented using label matrix obtained by connected component structure. The segmented characters are then compared with pre-stored data set. If the match percentage for a particular character in a data set is higher than the other data members, then that character is assigned for the corresponding segmented character. The obtained characters are stored in an array, till the process ends. Then the array is updated to local host server, that is created to store the detected license plate number, captured date along with the captured time.
