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

&lt;start&gt; a dog and a dog trying to catch a with &lt;end&gt;

![africa-1170179_1920](https://github.com/toshiouchi/ImageCaptioningMaskPredict/assets/121741811/4df07891-cd2e-413a-9023-c0d46121de1f)

&lt;start&gt; giraffes giraffes giraffes in a grassy area near and and &lt;end&gt;

![airplane-3702676_1920](https://github.com/toshiouchi/ImageCaptioningMaskPredict/assets/121741811/4a596370-17b2-4990-82dd-ac629e127bd2)

&lt;start&gt; a large air air jet is over airport airport &lt;end&gt;

![automotive-1846910_1920](https://github.com/toshiouchi/ImageCaptioningMaskPredict/assets/121741811/5b87d0fa-9b23-45d7-82d9-7126be56c70b)

&lt;start&gt; a red and red red hydrant on a city street &lt;end&gt;

![beach-1837030_1920](https://github.com/toshiouchi/ImageCaptioningMaskPredict/assets/121741811/8a892635-4449-417f-8184-826a3f18933a)

&lt;start&gt; a male boarder is a waves in the ocean &lt;end&gt;

![caravan-339564_1920]
(https://github.com/toshiouchi/ImageCaptioningMaskPredict/assets/121741811/4783b8e1-0881-4063-8934-bcc0cef09ec7).

&lt;start&gt; a man with a umbrella standing on a beach &lt;end&gt;

![cat-4467818_1920](https://github.com/toshiouchi/ImageCaptioningMaskPredict/assets/121741811/d600d332-c80c-475e-b77f-113318a3e970)

&lt;start&gt; an orange cat sitting on top of a red skateboard &lt;end&gt;

![cherry-1468933_1920](https://github.com/toshiouchi/ImageCaptioningMaskPredict/assets/121741811/2974783c-4c86-4e83-9c65-281b75783c97)

&lt;start&gt; a bowl of a an a a a and and and &lt;end&gt;

![couple-955926_1280](https://github.com/toshiouchi/ImageCaptioningMaskPredict/assets/121741811/5d1f819f-e628-4359-819c-93e05ab0dd41)

&lt;start&gt; a woman sitting on bike beach a lots of water &lt;end&gt;

![dog-7367949_1920](https://github.com/toshiouchi/ImageCaptioningMaskPredict/assets/121741811/83fccde8-f909-409c-8784-e812aee2031b)

&lt;start&gt; a man is on a surf board is playing water &lt;end&gt;

![hit-1407826_1920](https://github.com/toshiouchi/ImageCaptioningMaskPredict/assets/121741811/fe94bd3d-b28b-4de2-84ca-ea0ca18f4933)

&lt;start&gt; a baseball player with a ready to hit a ball &lt;end&gt;

![man-498473_1920](https://github.com/toshiouchi/ImageCaptioningMaskPredict/assets/121741811/312918a0-c51a-491b-b2d8-f1f47f51dfa9)

&lt;start&gt; a snow boarder down a covered on a ski slope &lt;end&gt;

![musician-743973_1920](https://github.com/toshiouchi/ImageCaptioningMaskPredict/assets/121741811/30b7be42-6b0a-4e21-b488-8b54844ad82a)

&lt;start&gt; a group of people with with boards boards on the beach &lt;end&gt;

![port-5788261_1920](https://github.com/toshiouchi/ImageCaptioningMaskPredict/assets/121741811/bec6e03f-32d6-431f-a117-bd751fe42f8f)

&lt;start&gt; a clock building with a tower on a city street &lt;end&gt;

![profile-7579739_1920](https://github.com/toshiouchi/ImageCaptioningMaskPredict/assets/121741811/1c67c096-5404-44e9-ba4c-83b51c130679)

&lt;start&gt; a man doing on with on skate board &lt;end&gt;

![ural-owl-4808774_1920](https://github.com/toshiouchi/ImageCaptioningMaskPredict/assets/121741811/56120ad4-236f-446a-bb5d-1458f4bb85b5)

&lt;start&gt; a small sitting on a tree branch in a tree &lt;end&gt;

![wine-bar-2139973_1920](https://github.com/toshiouchi/ImageCaptioningMaskPredict/assets/121741811/a840dbb1-8ddc-48fa-b349-fc66f846e153)

&lt;start&gt; a man in a black shirt holding a wine glass &lt;end&gt;

![woman-3432069_1920](https://github.com/toshiouchi/ImageCaptioningMaskPredict/assets/121741811/e43b7426-63be-4578-adf1-fd8ad3967e2b)

&lt;start&gt; a woman riding on brown horse through a grassy grassy &lt;end&gt;

![zebras-1883654_1920](https://github.com/toshiouchi/ImageCaptioningMaskPredict/assets/121741811/11d85f6c-0e4e-40d5-8b07-a1e87b234c04)

&lt;start&gt; a zebra in a grassy area eating and eating &lt;end&gt;




