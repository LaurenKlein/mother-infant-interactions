# mother-infant-interactions
De-identified pose and vocal features from infant-mother interactions at infant ages 2, 6, 9, 12, and 18 months

F0_csv_infant and F0_csv_mother contain the csv files with the fundamental frequency of the infants and mothers, respectively. 
The csv files are named as t<infant id number><infant age in months>.csv.
  
openpose_csv_infant and openpose_csv_mom contain the openpose features of the mother and infant at each timestep. The column names are such that columns 0, 1, 2 represent the x coordinate, y coordinate, and confidence of the 0th pose landmark, columns 3, 4, 5 represent the x coordinate, y coordinate, and confidence of the 1st pose landmark, etc. The pose features were extracted with the BODY_25 pose output format. csv files are named as 02_S0<infant id number>_<infant age in months>_op.csv.
  
  For additional questions, please contact kleinl@usc.edu.
  
  Please cite the following when using this dataset: 
  Klein, L., Ardulov, V., Hu, Y. Soleymani, M. Gharib, A. Thompson, B. Levitt, P. Matarić, M.J. (2020). Incorporating Measures of Intermodal Coordination in Automated Analysis of Infant-Mother Interaction. In Proceedings of the 22nd International Conference on Multimodal Interaction.
