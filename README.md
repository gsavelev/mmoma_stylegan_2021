# Pretrained StyleGAN model
> The result of training a model for the exhibition of Arseny Zhilyaev
> "[БУДНИ РАСПОЗНАВАТЕЛЯ ОБРАЗОВ](https://mmoma.ru/exhibitions/gogolevsky10/arsenij_zhilyaev_budni_raspoznavatelya_obrazov/)" in Moscow Museum of Modern Art.

<p>The main task was to train a Generative Adversarial Network on photos of past exposures to generate images of non-existent exposures.</p>
<p>To solve this I've trained this StyleGAN on 1 Tesla V100 GPU about 2 months.</p>
<p>Here is the learning timelapse:</p>

![](timelapse.gif)

## File
Because of GitHub limitations, [here is the .pkl file](https://disk.yandex.ru/d/_Rf2MaS665pXOA).

## Usage
1. Put the `.pkl` file inside your `result` directory of StyleGAN repository;
2. specify the path to `.pkl` in the `resume_run_id` variable of the `training/training_loop.py`;
3. start learning as usual with `train.py`.

_For more details of StyleGAN usage, please refer to the [arcticle](https://www.analyticsvidhya.com/blog/2020/12/training-stylegan-using-transfer-learning-on-a-custom-dataset-in-google-colaboratory/)._

## Authors
* [Gleb Savelev](https://github.com/nardo-leo)