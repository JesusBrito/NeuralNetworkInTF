# Info about repository

### IDE
I created this example using Anaconda Navigator and TensorFlow 1.5

### DataSet images
Here you can find the images to training the model and the images to test it.
https://btsd.ethz.ch/shareddata/index.html
In the code you can find this lines of code, here you can change  the structure of directories to reference the images

    main_dir = "./BelgiumTS/"
    training_dir = os.path.join(main_dir, "Training/")
    test_dir = os.path.join(main_dir, "Testing/")

In the code  I define a function to load images 

    load_ml_data()

Also i created a section of code for analize and describe dataset