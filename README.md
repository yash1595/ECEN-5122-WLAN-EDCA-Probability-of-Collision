# ECEN-5122-WLAN-EDCA-Probability-of-Collision
Wireless Local Area Network (WLAN) Final Project  

#Brief :   
        The zip folders contain MATLAB codes for demonstrating probability of collision in EDCA.  
        The file "FilesForEDCAExpansion" calculates the collision probability as Contention Window (CW) increases after each collision.
        The file "FilesForReverseEDCAExpansion" calculates the collision probability as Contention Window (CW) decreases after each collision.  

#Steps:  
        1. For the file "FilesForEDCAExpansion", execute "Pcollision_Project_File.m".
           For the file "FilesForReverseEDCAExpansion", execute "Pcollision_change_probability.m"  
        2. When the prompt to enter a matrix shows up, enter any of the following matrix names.
           M1, M2, M2_10, M2_25,M2_50, Mmix, Mmix_10, Mmix_25, Mmix_50, MBE, MBE_10, MBE_25, MBE_50, Mvi, Mvi_10, Mvi_25, Mvi_50, Mvo, Mvo_10, Mvo_25, Mvo_50, Mmixrev_10, Mmixrev_50, Mvorev_10, Mvorev_50, Mvirev_10, Mvirev_50, MBErev_10, MBErev_50.  

        Where M1, M2 are arrays from the paper titled "".  
        Mmix is an array with mixed stations.  
        MBE is an array with best effort ACs.  
        Mvi is an array with voice ACs.  
        Mvo is an array of video ACs.  
          
        All arrays with 'rev' contain  ACs with decreasing CWmax.  
        All arrays with '10' , '25' and '50' indicate number of stations.  
        