# LBW (cricket) Detection using Transformers

## Introduction

This Model is aimed to make a accurate prediction about whether it is "OUT" or "NOT OUT" using DETR (Pretrained Transformer) and 'facebook-resnet-fpn' i.e just Part-1. The actual reason behind this Model is Pitch Bounce varies from Pitch to Pitch so, sometimes it leads to a wrong decision. To avoid that it is necessary track the movement of the ball as well as measuring the relative distance when the ball is moving so, this reduces need of completely depending on predefined projection.

### Details :
#### Dependencies :
• Supervision
• Transformers (Model --> DETR)
• Timm, torchvision

#### Outputs :
<img src='images/drs_lbw_1.jpg'>

