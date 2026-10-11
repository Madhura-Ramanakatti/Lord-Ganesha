# ॐ Devanagari Ganesha Art

A simple Python generative-art project that converts a Ganesha image into artwork using Devanagari characters like **ॐ, गं, ग, ण, प, त**.

The artwork appears on a **black background with white characters** and can be replayed by clicking the screen.

## Requirements

* Python 3
* Pillow

## Run

Install Pillow:

```bash
pip install Pillow
```

Make sure the project looks like:

```text
project/
├── input/
│   └── ganesha.png
└── main1.py
```

Run the program:

```bash
python main1.py
```

On Windows, you can also use:

```bash
py main1.py
```

## Controls

* The animation starts automatically.
* **Click anywhere on the screen to replay.**
* Change `ANIMATION_DELAY` to adjust animation speed.
* Change `PIXELS_PER_FRAME` to control how many characters appear at once.

Enjoy creating digital art with Python! 🐘
