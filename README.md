We carried out machine learning with a Mask-Predict image captioning and a CTC Mask-Predict image captioning. In this report we report a result of Mask-Predict image captioning. 

## Dataset

Train2017 of cocodataset was used, and train dataset is 90% of it, and val dataset is 10% of it.

## Learning curve

loss = loss0 + loss1

Loss0 is masked cross entropy loss of model outputs and targets. loss1 is MSELoss of predicted length of captions and target lengths.

### Loss0
![ImageCaptioning_OnlyMaskPredict_Loos0](https://github.com/toshiouchi/ImageCaptioningMaskPredict/assets/121741811/6de2b3d4-3df2-427b-9d0b-c7daf9b8dbea)

### Loss1
![ImageCaptioning_OnlyMaskPredict_Loos1](https://github.com/toshiouchi/ImageCaptioningMaskPredict/assets/121741811/929aab76-3a52-4b3c-b29a-65715de7a40f)

### Loss
![ImageCaptioning_OnlyMaskPredict_Loos](https://github.com/toshiouchi/ImageCaptioningMaskPredict/assets/121741811/cd8f3f3a-81cb-49df-a0be-e516e3607245)

### WER
![ImageCaptioning_OnlyMaskPredict_WER](https://github.com/toshiouchi/ImageCaptioningMaskPredict/assets/121741811/950bac66-e5b0-4e95-ae71-26d0652c7f29)

## Inference Results

![adorable-1849992_1920](https://github.com/toshiouchi/ImageCaptioningMaskPredict/assets/121741811/dc6aefb8-1ab2-487c-9dd3-1ad8502ff47f)

<start> a dog and a dog trying to catch a with <end>

![africa-1170179_1920](https://github.com/toshiouchi/ImageCaptioningMaskPredict/assets/121741811/4df07891-cd2e-413a-9023-c0d46121de1f)

<start> giraffes giraffes giraffes in a grassy area near and and <end>
