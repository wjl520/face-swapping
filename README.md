# face-swapping
**Personal experiment about the project: https://github.com/taotaonice/FaceShifter.git**
1. loss_attr and loss_id: In the taotaonice's project, it's not proper for calculating the loss_attr by the feature of self.encoder(X) as the ground true (https://github.com/taotaonice/FaceShifter/blob/376b09e4ecc97848c07c585f173d10932880f961/network/AEI_Net.py#L125). It should utilize the pretrained vgg network for calculating the loss_attr between pred_loss and gt_loss. Refer to the link and download the pretrained vgg weight:
2. datasets: generated images by stylegan and real images have different space distribution, affecting the swapped face result.

to be continue...
