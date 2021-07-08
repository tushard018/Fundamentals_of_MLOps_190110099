1. In the notes of Week 1, we compared & contrasted MLOps with DevOps. In this question, you need to understand what is meant by the term AIOps, & then contrast it with MLOps.

  AIOps is the process of using AI and ML algorithms to aid the process of IT operations management. The digital transformation in industries has led to the adoption of newer 
  technologies such as cloud. These newer technologies produce a vast amount of data that is beyond human scale. Traditional IT practices make it difficult to manage these 
  complex environments.In case of any disruption it becomes difficult to spot the cause. ML algorithms can be used to analyse the large data and monitor the infrastructure. 
  This can help in eliminating disruptions and provide automated improvements and fixes.

  Though both the AIOps and MLOps are set at the crossroads of AI and DevOps, they both are completely different. While AIOps is used to improve the practices of managing IT 
  operations through the use of Artificial Intelligence. MLOps is a set of practice that ensures a structured workflow for the development and deployment of ML models.

source: https://www.bmc.com/blogs/what-is-aiops/

2. Interpretable Machine Learning is another concept that has attracted lot of attention recently & is promoted by most of the MLOps frameworks. Explain what it means for 
   a linear regression model to be interpretable.
   
  Most machine learning models are so complex that they can’t explain the prediction of an outcome. Thus are known as black boxes. Interpretable machine learning is a 
  concept which uses various methods to explain the predictions from a model. Interpretable machine learning helps to draw insights about which features are important and 
  how any particular feature effects the outcome

  The linear regression model is one of the most easily interpretable. Here, the final outcome is the weighted sum of the feature values. A features importance can be gauged by 
  its weight. One way to interpret the model is to find the effect value, it is calculated by multiplying the feature value and the weight. We can plot these values on a 
  side by side box plot, it visualizes the distribution of every feature. Now to interpret the outcome of any particular instance we can just look for the instance values, 
  the one far away from the median value will have more effect and the one closer will have less effect.

  Interpreting what set of conditions (features) led to the development of a particular outcome may be not required in some cases but cases where the a great deal of decision 
  is dependent on the model, it may become essential to interpret the underlying causes before blindly following the numbers.

source: https://christophm.github.io/interpretable-ml-book/


<img src="https://github.com/tushard018/Fundamentals_of_MLOps_190110099/blob/main/Week1/2021-07-08.png">
