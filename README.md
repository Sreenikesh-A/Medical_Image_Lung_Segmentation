# Medical_Image_Lung_Segmentation
Built a computer vision system that identifies and segments a target biological or medical structure in an image. The output is a segmentation mask and evaluated using appropriate metrics such as IoU or Dice score. This is an AI segmentation benchmark and not a clinical diagnostic system. 
## Run Instructions
1. **Select GPU Runtime**
   Navigate to **Runtime → Change runtime type** and select **GPU** as the hardware accelerator.
2. **Run the Model Verification Block**
   Scroll to the bottom of the notebook and execute **only the final “Model Verify” block**.
3. **Upload an X-ray Image**
   When prompted, upload a **chest X-ray image** in a supported image format.
4. **Generate Segmentation Results**
   The trained segmentation model will process the uploaded X-ray image and generate the **segmentation result**.
5. **View the Segmentation Report**
   The system displays the resulting **segmentation mask along with the generated segmentation report**, providing a visual representation of the identified lung region.

### Objectives:
1.Segment the lungs from chest X-ray images.
2.Evaluate the segmentation using Dice Score and IoU.
3.Visualize the predicted segmentation mask.
4.Novel feature - Quantitative Lung Region Analysis and Boundary Visualization

Dataset-(https://www.google.com/url?q=https%3A%2F%2Fwww.kaggle.com%2Fdatasets%2Fiamtapendu%2Fchest-x-ray-lungs-segmentation)

1.Number of images: 704

2.Number of corresponding masks: 704

3.Dataset source: Kaggle

4.Dataset Description: A collection of 704 chest X-ray images with corresponding lung segmentation masks, derived from the Montgomery County and Shenzhen Chest X-ray databases. Although the source dataset contains tuberculosis-related clinical information, this project uses only the chest X-ray images and their corresponding lung masks for the lung segmentation task. TB labels and demographic metadata are not used by the segmentation model.
