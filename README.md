# kthfsdv-Perception-Interview

 > ## Approach
  1) Collect image data set. Annotate it.
  		1) 
  2) Setup my the environment in ubuntu to make ros node 
  		1) Had a lot of trouble with the setup. Thanks for the heads up about the ROS source and Py3
        2) After trying yolov3,darknet, I decided darkflow was the best way
        3) I trained video data on my laptop in windows in couple of hours but in after changing to ubuntu the epoch per hour drop so much. No way I could train on my laptop.
        4) Found [pretrained weights](https://github.com/melfm/dukecone) but no config file. Morphed many confgs, no use
        5) Turning to Google colabs. Redone the entire setup again [My colab GPU env.](https://drive.google.com/drive/folders/1r6yw32bb-H6Xb52tpjTJ5JJeXERog_dN?usp=sharing)
        6) #### Got struck training in colab due to format/access errors raised by google drive.   
  3) Explore custom neural net/ open source frameworks
  
  4) Train the model with obtained cone data
  
  5) Test on given image
  
...and so on but unfortunately could not go beyond step 4  
