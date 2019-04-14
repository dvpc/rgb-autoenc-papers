# Generative Retinal Ganglion Cell model corresponding scientific papers
In the following are the papers i wrote in 2015/16. Since i am no longer part of a scientific organisation i figured i should publish these here.

* The original diploma thesis (2015)  
[Modeling Color Vision with Coding Strategies of Retinal Ganglion Cells](da.pdf)  

* Paper distilled from the thesis (2016)    
[A Generative Model of Retinal Ganglion Cells Learns Separate Channels from Color Images](artels.pdf)  
Rejected.  

* Revised version of the paper (2016)  
[A Compressing Autoencoder Model of Retinal Coding for Color Images](artspr.pdf)  
Revision rejected.  


And the corresponding implementations:  

* The numpy/theano code of the thesis and the distilled paper  
[rgb-autoenc](https://github.com/dvpc/rgb-autoenc).  

* The tensorflow code of the revised paper  
[rgb-autoenc-tf](https://github.com/dvpc/rgb-autoenc-tf)    





While writing the revision of the paper, i experienced 
what Pete Warden describes as [the machine learning reproducibility crisis](https://petewarden.com/2018/03/19/the-machine-learning-reproducibility-crisis/):   
By re-implementing the same model in another framework (now tensorflow), but utilizing the same hyperparameters and training data, the original results could only barely be reproduced. 
This is appearant when comparing results of the destilled paper and the revised version.   
Since the model is extremely simple (only one hidden layer) this was rather suprising to me at the time. 



