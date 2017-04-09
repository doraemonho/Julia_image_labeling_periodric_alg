# Julia_image_labeling_periodric_alg


Actully , It is the modifition of the julia 's image library function label_compenont who support the periodric boundary condition now.
For Now ,only 3D array is can be process!                                                                                                                                
Exmaple:                                                                                                                                
2D Array:                                                                                                                               
[1,1,0,0,0                                                                                                                                
 1,0,0,0,1                                                                                                                                
 0,0,0,0,1                                                                                                                                
 0,0,1,0,0]                                                                                                                               
                                                                                                                                 
 orgirnal labeling:                                                                                                                      
 [1,1,0,0,0                                                                                                                               
  1,0,0,0,2                                                                                                                               
  0,0,0,0,2                                                                                                                               
  0,0,3,0,0]                                                                                                                              
                                                                                                                                  
 perodric labeling:                                                                                                                       
 [1,1,0,0,0                                                                                                                               
  1,0,0,0,1                                                                                                                               
  0,0,0,0,1                                                                                                                               
  0,0,2,0,0]                                                                                                                              
 
 
