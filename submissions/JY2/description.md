# JY2 <!-- Your submission short name in <=4 characters -->
Jen-Yu Liu, Yi-Hsuan Yang

Research Center for IT Innovation, Academia Sinica, Taiwan <!-- Affiliations -->

ciauaishere@gmail.com <!-- one corresponding mail address -->

## Additional Info

* __is_blind:__ no  <!-- if you used supervised learning, answer no -->
* __additional_training_data:__ no  <!-- if you used more data than musdb (not including data augmentation)-->

## Supplemental Material

* __Code:__ Not available right now
* __Demos:__ Not available right now


## Method

Denoising auto-encoder with skip connections. It shares some similarities with the U-Net proposed by Jansson et al., but has some major differences in architecture desing and skip connections.

In comparison to JY1 model, this one adds an enhancement module in addition to the main separation module.


## References

- Jansson, A., Humphrey, E., Montecchio, N., Bittner, R., Kumar, A., and Weyde, T. U-NET CONVOLUTIONAL NETWORKS. Proceedings of ISMIR, 2017
