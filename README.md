# Ground Truth & Model Prediction Association
This code associates ground truth panicle counts with those predicted by an object detection model.

To train a new model see, https://github.com/phytooracle/ezobde.

To deploy the new model, edit the YAML file: https://github.com/phytooracle/automation/blob/main/yaml_files/season_12/stereoTop_level02_s12.yaml

## Inputs
Groud truth counts of tillers and URL for RGB plant detections close to the date of ground truth data collection.

## Outputs
CSV containing the associated ground truth and model predictions.

## Arguments and Flags
* **Required Arguments:**
  * **Ground truth for water-limited treatment:** '-gt_wl'
  * **Ground truth for well-watered treatment:** '-gt_ww'
  * **URL for detection output:** '-url'
