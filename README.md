# resnet50
Resnet 50 - pytorch

---

<h4>Increasing network depth does not work by simply stacking layers together. Deep networks are hard to train because of the notorious “vanishing gradient problem” — as the gradient is back-propagated to earlier layers, repeated multiplication may make the gradient definitively small.

ResNet uses a technic called “Residual” to deal with the “vanishing gradient problem”. When stacking layers, we can use a “shortcut” to link
discontinuous layers. i.e., We can skip some layers, as follows:
</h4>

---


### Residual Block 
<img src=".\photos\residual_block.png" alt="p1" width="100%"> 

### Types of Residual Block 
<img src=".\photos\types_of_resnets.png" alt="p1" width="100%"> 


