Title: Documentation
Date: 2018-07-03
Category: Documents

# pyvie.Movie()

Initializes a movie with file characteristics given

### Parameters

** name ** : string . This string will be the name of the movie that is saved after rendering. A file type extension will be added on automatically, so there is no need to add one here.

** framerate ** : numeric. The number is the speed of your video in frames per second.

** file\_type ** : string. File extension for images.

** movie\_type ** : string. FIle extension for movie.

# pyvie.gather()

Add current frame to the video

# pyvie.finalize()

Renders the added frames into a video.

### Parameters

** open\_movie ** : bool. If true, after a video has been rendered it will automatically be opened using your default media viewer.

** output\_notebook ** : bool. If true, after a video has been rendered it will be opened embedded into a Jupyter notebook.

