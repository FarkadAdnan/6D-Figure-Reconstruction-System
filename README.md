# 6D-Figure-Reconstruction-System
Open source machine learning (ML) work based on the Python programming language and the Torch library with PyTorch.

# Data Entry
![1](https://user-images.githubusercontent.com/35774039/179402292-05ea9d08-d1d3-4dd1-b606-6daadad10a25.jpg)

# Define shapes and represent them as data
![2](https://user-images.githubusercontent.com/35774039/179402315-41c0e498-ed53-432a-abec-16f8cfb78fff.PNG)

# set limits
![3](https://user-images.githubusercontent.com/35774039/179402338-b65413c8-f22f-4dbd-a4b7-d2ce79514cee.PNG)

# Data processing
![4](https://user-images.githubusercontent.com/35774039/179402350-e426844b-67e2-4ee0-8761-a4488859611c.jpg)

عادة الإعمار المتزامن متعدد العناصر ثلاثي الأبعاد ، ووضع 6D وتقدير الحجم من خلال ملاحظة RGB-D أحادية العرض. على عكس تقدير الوضع على المستوى غير المباشر ، فإننا نركز على مشكلة أكثر صعوبة حيث لا تتوفر نماذج CAD في وقت الاستدلال. تتبع الأساليب الحالية بشكل أساسي خط أنابيب معقد متعدد المراحل يقوم أولاً بترجمة وكشف كل مثيل كائن في الصورة ثم يتراجع إلى شبكاتهم ثلاثية الأبعاد أو أوضاعهم 6D.

# PointCloud Auto-Encoder

![Capture1](https://user-images.githubusercontent.com/35774039/179402622-031ec85c-c51a-4e0c-a833-4c04020c3dc5.PNG)
# maps
3D maps of a ground reality object are computed using a Gaussian kernel based on the Yxyg scale for each object.
![شسشس](https://user-images.githubusercontent.com/35774039/179402687-98ae966f-1248-4815-82f3-b07e7994b834.PNG)
# data
Bevel distance evaluation on a multiobject ShapeNet dataset.
![سشسش](https://user-images.githubusercontent.com/35774039/179402750-067f84e2-d296-4706-8ba6-3be060717a22.PNG)

# REFERENCES
-  C. R. Qi, H. Su, K. Mo, and L. J. Guibas, “PointNet: Deep learning on point sets for 3d classification and segmentation,” in Proceedings of the IEEE conference on computer vision and pattern recognition, 2017, pp. 652–660.
-  A. X. Chang, T. Funkhouser, L. Guibas, P. Hanrahan,Q. Huang, Z. Li, S. Savarese, M. Savva, S. Song, H. Su et al., “ShapeNet: An information-rich 3d model repository,” arXiv preprint arXiv:1512.03012, 2015.
-  L. Van der Maaten and G. Hinton, “Visualizing data using t-SNE,” Journal of machine learning research, vol. 9, no. 11, 2008.
- Y. Zhou, C. Barnes, J. Lu, J. Yang, and H. Li, “On the continuity of rotation representations in neural networks,” in Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition, 2019, pp.
-  G. Pitteri, M. Ramamonjisoa, S. Ilic, and V. Lepetit, “On object symmetries and 6d pose estimation from images,” in 2019 International Conference on 3D Vision (3DV). IEEE, 2019, pp. 614–622.
-  X. Chen, Z. Dong, J. Song, A. Geiger, and O. Hilliges,“Category level object pose estimation via neural analysis-by-synthesis,” in European Conference on Computer Vision. Springer, 2020, pp. 139–156.
