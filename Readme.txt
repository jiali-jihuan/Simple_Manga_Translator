To get started, please use "simple manga translator.ipynb" in google colab.

-In colab, upload the files "aot1.png", "aot1_raw.jpg" and "shingeki-no-kyojin-chapter-1.zip".

-Once files are uploaded, run the first cell to download libraries and then restart runtime.

-Once runtime is restarted, run the section "ROI (Regions of Interest) Detection, prepare for CNN"
	-This will run roi(image) on the main training image.

-To view roi(image) on full chapter
	-run the code line that unzips the zip file, first box on "# ROI Test on full chapter - OK Results, not for CNN"
	-run "All Results" to view alll the image processing steps for every page (more time consuming)
	-run "Runtime Test on Full Chapter" to see the end results for every page (faster)

-For translation, run the entire section "Translation Setup"
	- you will be able to see the the translation for the main training image
	- you can also insert other chapter image you wish to view by chainging roi(your_image)