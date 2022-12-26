# 🌄 Regularization Images
Pre-Rendered Regularization Images fou use with fine-tuning, especially for the current implementation of "Dreambooth".

## What are Regularization Images?
Regularization images are images that are used as part of a regularization process to improve the stability and performance of deep learning models. In the context of stable diffusion and the current implementation of Dreambooth, regularization images are used to encourage the model to make smooth, predictable predictions, and to improve the quality and consistency of the output images, respectively.

## Available Image Sets
This repository hosts a variety of different sets of regularization images. While these images worked for the author of this repository, they should in no way be considered "best practice".

Your feedback in form of issues is much appreciated!

### "photo of a woman" - regular

The standard version, as Stable Diffusion 1.5 would output it without any modification. This is what Shivams colab would generate with a "photo of a woman" class.

* Folder: [photo_of_a_woman-regular](./../../tree/main/photo_of_a_woman-regular)
* Count: 1500
* Prompt: "photo of a woman"
* Negative Prompt: none
* Model: Stable Diffusion v1.5 pruned (a9263745)
* Steps: 20, Sampler: Euler, CFG scale: 7, Size: 512x512, Model hash: a9263745

### "photo of a woman" - enhanced

Same as the regular "photo of a woman", but enhanced with a negative prompt that filters out undesired results in the set.

* Folder: [photo_of_a_woman-enhanced](./../../tree/main/photo_of_a_woman-enhanced)
* Count: 1500
* Prompt: "photo of a woman"
* Negative Prompt: "illustration, painting, drawing, lowres, bad hands, text, error, missing fingers, extra digit, fewer digits, cropped, worst quality, low quality, normal quality, jpeg artifacts, signature, watermark, username, blurry, ((((ugly)))), (((duplicate))), ((morbid)), ((mutilated)), [out of frame], extra fingers, mutated hands, ((poorly drawn hands)), ((poorly drawn face)), (((mutation))), (((deformed))), ((bad anatomy)), (((bad proportions))), ((extra limbs)), cloned face, (((disfigured))), extra limbs, gross proportions, (malformed limbs), ((missing arms)), ((missing legs)), (((extra arms))), (((extra legs))), mutated hands, (fused fingers), (too many fingers), (((long neck)))"
* Model: Stable Diffusion v1.5 pruned (a9263745)
* Steps: 20, Sampler: Euler, CFG scale: 7, Size: 512x512, Model hash: a9263745

## Usage
To use the regularization images in this repository, simply download the images and specify their location when running the stable diffusion or Dreambooth processes.

## Contribution
If you have regularization images that you would like to contribute to this repository, please open a pull request with your contribution. All contributions are welcome and appreciated!

## License
The regularization images in this repository are licensed under the MIT license. Please see the LICENSE file for more information.
