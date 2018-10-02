# kthfsdv-Perception-Interview

 > ## Approach
  1) ##### Data collection
  		1) Created a [dataset of ~300](https://drive.google.com/drive/folders/1GKAPXpw4lRAy_a3nn1UtU1FfNdwT2IfR?usp=sharing) manually annotated instances of all the 5 colors of traffic cones
        
  2) ##### Setup my the environment in ubuntu to make ros node 
  		1) Had a lot of trouble with the setup. Thanks for the heads up about the ROS source and Py3
        2) After trying yolov3,darknet, I decided darkflow was the best way
  
  3) ##### Training the  model on my "CPU" laptop ( Not my first time ) 
  	
    	1) I trained 200 videos on my laptop in windows in couple of hours but in after changing to ubuntu for this training program,  the epoch per hour for these 'image' dataset is so high. 
  		2) Found [pretrained weights](https://github.com/melfm/dukecone) but no config file. Morphed many configs and experimented, no use.
   
   4) ##### Turning to Google colabs  
   
      	1) Redone the entire setup again [My colab GPU env.](https://drive.google.com/drive/folders/1r6yw32bb-H6Xb52tpjTJ5JJeXERog_dN?usp=sharing) Entire darkflow, dataset, models and configurations in the above link. (Note : Not fully functoning) 
   		2) #### Got struck training in colab due to format/access errors raised by google drive. Still fiddling with it....   
  
  .and so on but unfortunately could not go beyond step 4 :(

