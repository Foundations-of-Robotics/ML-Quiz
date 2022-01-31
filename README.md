# Quiz: Foundations of Robotics - Managing the world complexity: from linear regression to deep learning.

This quiz is in the form of a jupyter notebook.

All required libraries are installed in your active python environment by the notebook, so this quiz has no prerequisite apart from `jupyter` and `python`.

If you do not have jupyter and python installed, we recommend simply installing [Anaconda](https://www.anaconda.com).
Then, you can open a conda prompt, navigate to your copy of the repository, and type:

```bash
jupyter notebook
```

This should open jupyter in your web browser, and from there you can open the quiz, which is the `quiz.ipynb` file, using python3.

You can then execute the provided code cells one by one.

In this version of the quiz, the answer is provided after each question.
If you need to hide answers, you can simply copy `quiz.ipynb` and delete these answers (text can be edited in jupyter by double-click and code blocks can be deleted by double-press on the `D` key).

## Repository files:
### git:
- `.gitattributes`: enables big files (NN weights) to be downloaded when cloning the repo
- `.gitignore`: ignores junk files on commits
- `README.md`: this file
### quiz:
- `quiz.ipynb`: jupyter notebook containing the actual quiz, open this with jupyter
### support material:
- `coco.names`: text file containing the names of the 80 classes present in the COCO dataset, on which the provided YOLO models have been trained
- `street_image.jpg`: example image used to test YOLO in the first part of the quiz
- `yolov3-tiny.cfg`: description of the architecture of a pre-trained tiny YOLO model
- `yolov3-tiny.weights`: weights of a pre-trained tiny YOLO model
- `yolov3.cfg`: description of the architecture of a pre-trained big YOLO model
- `yolov3.weights`: weights of a pre-trained big YOLO model

