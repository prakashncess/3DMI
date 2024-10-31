% ***************************************************************
% *** Help file for running all codes
% *** Source Code is mainly written for research purposes. The codes are
% *** having copyrights and required proper citations whenever it is used.
% *** Originated by:
% ***       Dr. Chandra Prakash Dubey (email:p.dubey48@gmail.com)
% ***       Ms. Vanisha Vashishtha (email:vanishavashsishthaa@gmail.com)
% ***       
% ****************************************************************
This is a help file for a description of all Data and Source Code used for the implementation of our present paper 
"3D inversion of dyke & sill in terms of remnant and induced magnetization vectors"
      1. Data File
           a.TMI.dat

    a.TMI.dat contains the magnetic anomaly data over the Galinge iron ore deposit, located in the 
Qinghai region of northwest China. 

      2. Source Code
            a.optimization_single_prism.ipynb
            b.optimization_combined_prism.ipynb
            c.real_data_optimization.ipynb
            d.regularization.ipynb
            e.prism_mag.1.ipynb

   a.optimization_single_prism.ipynb - It calculates the 3D inversion of a single vertical prism parameter including length, breadth, depth, magnitude and total magnetization direction 
in terms of remnant magnetization vector and induced magnetization vector. It contains all the optimized values and curves.

   b.optimization_combined_prism.ipynb - It calculates the 3D inversion of a combined vertical and horizontal prism parameter including length, breadth, depth, magnitude and total 
magnetization direction in terms of remnant magnetization vector and induced magnetization vector. It contains all the optimized values and curves.
 
   c.real_data_optimization.ipynb - It calculates the 3D inversion of a real magnetic anomaly over the geological body in China. Calculates inversion parameters including length, breadth, 
depth, magnitude, and total magnetization direction in terms of remnant magnetization vector and induced magnetization vector. It contains all the optimized values and curves.
 
   d.regularization.ipynb - It calculates the regularized optimized parameters for all 3 above-mentioned optimization files: optimization_single_prism.ipynb, optimization_combined_prism.ipynb, 
real_data_optimization.ipynb.These values are tabulated on paper

   e.prism_mag.1.ipynb - It calculates the Total Magnetic Anomaly over the vertical prism, combined prism, optimized total magnetic anomaly over vertical prism, optimized total magnetic over
combined prims, optimized real-life Total Magnetic Anomaly, and their correspondingly calculated residual plots between observed and optimized anomaly. Plotting all the plots