# GRATS (GReek Adversarial Traffic Signs)

This repository contains a dataset that proposed in the paper  "Traffic Signs Recognition Robustness in Autonomous Vehicles under Physical Adversarial Attacks" and consists of clean and 'dirty' images belonging to five classes, no_parking, no_right_turn, no_left_turn, no_entry and stop.

![GRATS](media/Fig.jpg)

# Dataset Structure
The dataset follows the following structure: 
```
├── Dataset
    ├── clear_road_signs
        ├── train
            ├── no_righ_turn
            ├── no_parking
            ...
        ├── test
            ├── no_righ_turn
            ├── no_parking
            ...
    ├── dirty_road_signs
        ├── train
            ├── no_righ_turn
            ├── no_parking
            ...
        ├── test
            ├── no_righ_turn
            ├── no_parking
            ...
```

# Citation
If you use our dataset in a scientific publication, please use the following bibtex citation:
```
@incollection{
AUTHOR = {Apostolidis, Kyriakos D. and Gkouvrikos, Emmanouil V. and Papakostas, George A.},
TITLE = {Traffic Signs Recognition Robustness in Autonomous Vehicles Under Physical Adversarial Attacks},
BOOKTITTLE = {Future Intelligent Transport Systems: Current and Future Perspective Book Series: “AAP Advances in Artificial Intelligence and Robotics},
YEAR = {2022}
```
