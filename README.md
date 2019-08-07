# ml5-data-and-models-server
A repo to download and serve data and models locally allowing ml5 to run without a web connection

**Work in progress - please ignore**

## Quickstart
> coming soon

## Setup

```
cd ml5-data-and-models-server
npm install
```

## Download Data and Models

To download models run:

```
cd ml5-data-and-models-server
npm run download:all
```

or for specific models:

```
npm run download:bodypix
npm run download:sketchrnn
npm run download:unet
npm run download:sentiment
npm run download:faceapi
npm run download:soundclassification
npm run download:mobilenet
npm run download:yolo
npm run download:posenet
npm run download:all
```

→ Your model outputs will live in the `/models` directory


## Start the Server
> coming soon

## Work in Progress

### Done
* SketchRNN ✅
* bodyPix ✅
* Sentiment ✅
  * moview reviews ✅
* UNET: ✅
  * unet-128 ✅
* face-api: ✅
  * Mobilenetv1Model ✅
  * FaceLandmarkModel ✅
  * FaceLandmark68TinyNet ✅
  * FaceRecognitionModel ✅
  * FaceExpressionModel ✅
* <s>CVAE</s>: (uses local path to model)
    * <s>quick_draw</s>
  * <s>DCGAN:</s> (uses local path to model)
    * <s>geo128</s>
    * <s>face</s>
    * <s>resnet128</s>
* SoundClassification:✅
  * 18w ✅
* mobilenet 🚨- needs review on structuring dir path appropriately
  * imagenet 🚨- needs review on structuring dir path appropriately
  * <s>pix2pix</s>:(uses local path to model)
    * <s>pikachu</s>
* <s>Styletransfer:</s> (uses local path to model)
    * <s>udnie</s>
    * <s>wave</s>
    * <s>mathura</s>
* YOLO ✅
* posenet: ✅
  * posenet ✅

### Doing

* **Pretrained Models**:
  
  * DoodleNet
* **Data**:
  * ????
  * ????
  * ????

