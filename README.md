This project of segmenting image by painting was finished by Xianyao Chen, who is serving for e-commerce company (MiX:D,믹스디 주식화사) of Sourth Korea in 2021.

[1] Target: Segment any part of image 

[2] Background: Given the input original image and the input painting image, segment any part of image

A. In input_image folder, 'input_image_x' is the input original image

B. In input_image foldedr, 'input_painting_x' is the input painting image

[3] Techniques:

A. Use painting tool to paint what want to segment. This operation make the mask of image essentially. 

B. cv2.grabCut: Based on mask of image, distinguish foreground and background to segment the part of image.

[4] Result: Output the part of image what want to segment.

In output_image folder, 'output_segment_x' is the output segmentation image.
