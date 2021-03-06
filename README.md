# Estimate Rectangle (윤곽선 추정하기)
[![Python 3.6.5](https://img.shields.io/badge/python-3.6.5-blue.svg)](https://www.python.org/downloads/release/python-365/)

[결과물 보기 (See Results)](Results.MD)

## Author
- __이은학__ Eunhak Lee
    - Github [@return0927](https://github.com/return0927)
    - Facebook [@R3turn.01](https://fb.com/R3turn.01)
    - RocketPunch [@eh.lee](https://www.rocketpunch.com/@eh.lee)
    - Email [admin@return0927.xyz](mailto:admin@return0927.xyz)

## Abstract
> Eng

Using Python OpenCV2, draw the edge lines of an image.

> Kor

Python OpenCV2를 이용하여 이미지에서 사각형의 윤곽을 찾고 이미지에 표시합니다.

## Examples
1. Original
![Original](data-in/card.jpg)

2. Canny
![Cannyed Edge](data-out/card-x1-AllRectangle(False)-canny.jpg)

3. Mixed (All Rects)
![Mixed (All)](data-out/card-x1-AllRectangle(True)-mixed.jpg)

4. Mixed (One)
![Mixed (All)](data-out/card-x1-AllRectangle(False)-mixed.jpg)

## Usage
1. Set-up a virtual environment and setup dependencies.
```sh
$ py -3.6 -m virtualenv .venv
$ call .venv\Scripts\activate.bat
$ pip install -r requirements.txt
```

2. Put the data files into `data-in`.

3. Edit `EstimateRectangle.py` as you want.

4. Run `EstimateRectangle.py`.
```sh
(.venv) $ python EstimateRectangle.py
```

## Contribute
Please make PRs & Issues.