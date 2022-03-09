# PyMirrorImager

## About

This is a simple python script, thanks to which you can mirror the image for your needs (most often this is done so that search engines can not detect your picture)

## How to use

Be sure to create a "result" folder in the folder with the script.

Open the main.py file in any text editor that is convenient for you

Find out the dimensions of your picture in pixels

Change the number of pixels in these lines to your own:

```python
for w in range(1920):
```

```python
for h in range(1080):
```

**These lines are repeated twice, be careful!**

Place your image in the folder with the script

Change the name of the picture in the code, and specifically in this line:

```python
create_image("1.jpg")
```

After using the script, a mirrored image will appear in the "result" folder.

### **Also, for the correct operation of the script, it is necessary to use an image in the format ".jpg" or ".jpeg". If the format does not correspond to the desired one, you can re-convert it on any online service without losing much quality.**
