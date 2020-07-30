# about the project

this is a classification problem for 'human vs horse'.

we are using a zip file stored on 'https://storage.googleapis.com/laurencemoroney-blog.appspot.com/validation-horse-or-human.zip \-O /tmp/validation-horse-or-human.zip'. Note that images are system generated.you can inspect a batch of images. I ahve written the code for that.

The contents of the .zip are extracted to the base directory `/tmp/horse-or-human` of the cloud plateform(google colab), which in turn each contain `horses` and `humans` subdirectories.

read images from subdirectories, and automatically label them from the name of that subdirectory so no need of labeling





