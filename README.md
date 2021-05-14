# Suitable_distance

このプロジェクトは、カメラ上の車を検出及び追跡し、定義されたラインを超えると通知し、カウントするものです。 


## Requirement

* Python 3.6

## Dependency:

To install the required dependencies, run the following command:

    $ pip install -r requirements.txt

### It uses:

* [yolo_v3](https://github.com/opencv/opencv/blob/master/samples/dnn/object_detection.py)
*[sort](https://github.com/abewley/sort)

## Citation

### YOLOv3 :

    @article{yolov3,
    title={YOLOv3: An Incremental Improvement},
    author={Redmon, Joseph and Farhadi, Ali},
    journal = {arXiv},
    year={2018}
    }
    
### SORT :

    @inproceedings{Bewley2016_sort,
      author={Bewley, Alex and Ge, Zongyuan and Ott, Lionel and Ramos, Fabio and Upcroft, Ben},
      booktitle={2016 IEEE International Conference on Image Processing (ICIP)},
      title={Simple online and realtime tracking},
      year={2016},
      pages={3464-3468},
      keywords={Benchmark testing;Complexity theory;Detectors;Kalman filters;Target tracking;Visualization;Computer Vision;Data Association;Detection;Multiple Object Tracking},
      doi={10.1109/ICIP.2016.7533003}
    }

