#Steps----
1. Run the code

2. Enter the directories of the dataset (only 1093,4795,8438,10870 allowed), you can enter 	manually one by one to choose specific directory and enter 'Done' to stop adding 	directories. Or you can enter 'All' to select all four directories automatically.

3. Let the segmentation run for all images, usually run a few hours.

#Extra tips----
1. If there is other dataset you wish to test, some changes to the code need to be made or you 	can change the directory name to either one out of the four (1093,4795,8438,10870) 	manually for testing purpose, but remember the original dataset directory.

2. You must put the dataset and mask directory under same directory with the source code.

3. After the code run successfully, it will create the iou_score and segmentation_result 	folder to store the segmentation result for each dataset, for the iou_score directory it 	saves the spreadsheet file for each dataset that contains information like iou score/sky 	pixel accuracy/pixel accuracy etc.

4. Please do not stop when the code running in the halfway, it may cause some error to the 	spreadsheet file and you might need to delete them and rerun the code and segmentation 	for particular dataset you stopped at.

5. You may find out the last img directory at the console(there is some description message 	prompt for each image processed) to see which image you stopped at previously, removed 	all the images before it to start the segmentation from that image to speed up the 	process.

6. Finally, Dr. Chia thank you for giving guidance and support.