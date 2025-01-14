# YoloCardDetection

Created 40,000 synthetic images of cards to train a YOLO detection model on using the Darknet frame work

![356404133](https://github.com/user-attachments/assets/24586e36-8735-463b-816d-c427a81676e6)

Example of synthetic training images

From there, I trained a YoloV4 model on this data set using the darknet frame work. The ultimate results were as follows:

detections_count = 1873, unique_truth_count = 446  
class_id = 0, name = Ah, ap = 100.00%   	 (TP = 14, FP = 0) 
class_id = 1, name = Kh, ap = 100.00%   	 (TP = 5, FP = 0) 
class_id = 2, name = Qh, ap = 100.00%   	 (TP = 5, FP = 1) 
class_id = 3, name = Jh, ap = 100.00%   	 (TP = 12, FP = 0) 
class_id = 4, name = 10h, ap = 100.00%   	 (TP = 9, FP = 0) 
class_id = 5, name = 9h, ap = 100.00%   	 (TP = 5, FP = 0) 
class_id = 6, name = 8h, ap = 100.00%   	 (TP = 6, FP = 0) 
class_id = 7, name = 7h, ap = 100.00%   	 (TP = 11, FP = 0) 
class_id = 8, name = 6h, ap = 100.00%   	 (TP = 6, FP = 1) 
class_id = 9, name = 5h, ap = 100.00%   	 (TP = 8, FP = 0) 
class_id = 10, name = 4h, ap = 100.00%   	 (TP = 9, FP = 0) 
class_id = 11, name = 3h, ap = 100.00%   	 (TP = 8, FP = 0) 
class_id = 12, name = 2h, ap = 100.00%   	 (TP = 7, FP = 0) 
class_id = 13, name = Ad, ap = 100.00%   	 (TP = 11, FP = 0) 
class_id = 14, name = Kd, ap = 100.00%   	 (TP = 3, FP = 0) 
class_id = 15, name = Qd, ap = 100.00%   	 (TP = 9, FP = 0) 
class_id = 16, name = Jd, ap = 100.00%   	 (TP = 18, FP = 0) 
class_id = 17, name = 10d, ap = 100.00%   	 (TP = 4, FP = 0) 
class_id = 18, name = 9d, ap = 100.00%   	 (TP = 10, FP = 1) 
class_id = 19, name = 8d, ap = 100.00%   	 (TP = 9, FP = 0) 
class_id = 20, name = 7d, ap = 100.00%   	 (TP = 11, FP = 0) 
class_id = 21, name = 6d, ap = 100.00%   	 (TP = 7, FP = 0) 
class_id = 22, name = 5d, ap = 100.00%   	 (TP = 8, FP = 0) 
class_id = 23, name = 4d, ap = 100.00%   	 (TP = 4, FP = 0) 
class_id = 24, name = 3d, ap = 100.00%   	 (TP = 8, FP = 2) 
class_id = 25, name = 2d, ap = 100.00%   	 (TP = 9, FP = 0) 
class_id = 26, name = Ac, ap = 100.00%   	 (TP = 7, FP = 0) 
class_id = 27, name = Kc, ap = 100.00%   	 (TP = 9, FP = 0) 
class_id = 28, name = Qc, ap = 100.00%   	 (TP = 10, FP = 0) 
class_id = 29, name = Jc, ap = 100.00%   	 (TP = 18, FP = 0) 
class_id = 30, name = 10c, ap = 100.00%   	 (TP = 6, FP = 0) 
class_id = 31, name = 9c, ap = 100.00%   	 (TP = 5, FP = 0) 
class_id = 32, name = 8c, ap = 100.00%   	 (TP = 5, FP = 0) 
class_id = 33, name = 7c, ap = 100.00%   	 (TP = 9, FP = 1) 
class_id = 34, name = 6c, ap = 100.00%   	 (TP = 3, FP = 1) 
class_id = 35, name = 5c, ap = 100.00%   	 (TP = 19, FP = 0) 
class_id = 36, name = 4c, ap = 100.00%   	 (TP = 11, FP = 0) 
class_id = 37, name = 3c, ap = 100.00%   	 (TP = 6, FP = 0) 
class_id = 38, name = 2c, ap = 100.00%   	 (TP = 3, FP = 0) 
class_id = 39, name = As, ap = 100.00%   	 (TP = 4, FP = 0) 
class_id = 40, name = Ks, ap = 100.00%   	 (TP = 3, FP = 0) 
class_id = 41, name = Qs, ap = 100.00%   	 (TP = 11, FP = 0) 
class_id = 42, name = Js, ap = 100.00%   	 (TP = 9, FP = 1) 
class_id = 43, name = 10s, ap = 100.00%   	 (TP = 6, FP = 0) 
class_id = 44, name = 9s, ap = 100.00%   	 (TP = 11, FP = 2) 
class_id = 45, name = 8s, ap = 100.00%   	 (TP = 12, FP = 0) 
class_id = 46, name = 7s, ap = 100.00%   	 (TP = 10, FP = 0) 
class_id = 47, name = 6s, ap = 100.00%   	 (TP = 7, FP = 0) 
class_id = 48, name = 5s, ap = 100.00%   	 (TP = 10, FP = 0) 
class_id = 49, name = 4s, ap = 100.00%   	 (TP = 13, FP = 0) 
class_id = 50, name = 3s, ap = 100.00%   	 (TP = 17, FP = 0) 
class_id = 51, name = 2s, ap = 100.00%   	 (TP = 6, FP = 0) 

 for conf_thresh = 0.25, precision = 0.98, recall = 1.00, F1-score = 0.99 
 for conf_thresh = 0.25, TP = 446, FP = 10, FN = 0, average IoU = 87.74 % 

 IoU threshold = 50 %, used Area-Under-Curve for each unique Recall 
 mean average precision (mAP@0.50) = 1.000000, or 100.00 % 


This model can be run on pictures or videos. 




https://github.com/user-attachments/assets/6b049281-a974-48e6-93fa-f19b3f641901



