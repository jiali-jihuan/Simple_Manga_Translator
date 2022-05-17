# Simple Manga Translator

<b> Creation of a manga translator using methods in place of neural networks for evaluation </b>
- Purpose of experiment is to try to get good results in ROI detection (regions of interest) to prepare for CNN/RNN training.
### Methods consist of image segmentation and OCR: <br>
  - contour detection <br>
  - image pre-processing <br>
  - PyTesseract <br>
  - Goslate <br>
  - Orb detection <br>
  - Foreground/background segmentation <br>
  - RGB mask <br>
  - +more in colab file <br>
#### - Entire experiments are in https://colab.research.google.com/drive/1jPP3EDmJD8O716rvrwTcoCdMomQmdKB2
#### - All necessary materials to run colab file are in this repo

- In colab, upload the files "aot1.png", "aot1_raw.jpg" and "shingeki-no-kyojin-chapter-1.zip".

- Once files are uploaded, run the first cell to download libraries and then restart runtime.

- Once runtime is restarted, run the section "ROI (Regions of Interest) Detection, prepare for CNN"
	- This will run roi(image) on the main training image.

- To view roi(image) on full chapter
	- run the code line that unzips the zip file, first box on "# ROI Test on full chapter - OK Results, not for CNN"
	- run "All Results" to view alll the image processing steps for every page (more time consuming)
	- run "Runtime Test on Full Chapter" to see the end results for every page (faster)

- For translation, run the entire section "Translation Setup"
	- you will be able to see the the translation for the main training image
	- you can also insert other chapter image you wish to view by chainging roi(your_image)
