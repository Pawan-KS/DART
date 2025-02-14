# DART: Diversify-Aggregate-Repeat Training
This repository contains codes for the training and evaluation of our CVPR-23 paper DART:Diversify-Aggregate-Repeat Training Improves Generalization of Neural Networks [main](https://openaccess.thecvf.com/content/CVPR2023/papers/Jain_DART_Diversify-Aggregate-Repeat_Training_Improves_Generalization_of_Neural_Networks_CVPR_2023_paper.pdf) and [supplementary](https://openaccess.thecvf.com/content/CVPR2023/supplemental/Jain_DART_Diversify-Aggregate-Repeat_Training_CVPR_2023_supplemental.pdf). The arxiv link for the paper is also [available](https://arxiv.org/pdf/2302.14685.pdf).
<p float="left">
  <img src="./media/DART_pic.png" width="400" />
   <img src="./media/model_optimization_trajectory.gif" width="400" />
</p>


 # Environment Settings 
* Python 3.6.9
* PyTorch 1.8
* Torchvision 0.8.0
* Numpy 1.19.2



# Training
For training DART on Domain Generalization task: 
```
python  
```

# Evaluation

# Results
## In-Domain Generalization of DART:
<p float="center">
  <img src="./media/ID_results.png" width="600" />
 </p>
 
 ## Domain Generalization of DART:
 <p float="center">
   <img src="./media/DG_main_results.png" width="600" />
   </p>
   
   ## Combining DART with other DG methods on Office-Home:
   <p float="center">
   <img src="./media/DG_combined_results.png" width="600" />
</p>



# Citing this work
```
@inproceedings{jain2023dart,
  title={DART: Diversify-Aggregate-Repeat Training Improves Generalization of Neural Networks},
  author={Jain, Samyak and Addepalli, Sravanti and Sahu, Pawan Kumar and Dey, Priyam and Babu, R Venkatesh},
  booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition},
  pages={16048--16059},
  year={2023}
}
```
