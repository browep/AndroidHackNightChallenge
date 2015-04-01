# Android Hack Night Challenge

[Tonight's slides](https://docs.google.com/presentation/d/1ucX2zCJxf5oO1Wd55ntMEGIzoew6KWPrFateDo1L2Vs/edit?usp=sharing)

This repo contains everything you need to get started in the project.

1. Clone the project
`git clone git@github.com:browep/AndroidHackNightChallenge.git`

2. Import volley as a submodule
`git submodule update`

2. Open with Android Studio

3. Find MainActivity.java

4. Create a Request object that calls the instagram API.  The instagram API requires authentication so I've gone ahead and created an app and an auth token to use.
`https://api.instagram.com/v1/media/search?lat=40.018163&lng=-105.279701&access_token=476940432.8198e5b.d85eb3931a4a46ba80c3d4967294bc5e` 
This will return instragram posts near downtown Boulder.

5. Take this JSON results and fill a RecyclerView with them using NetworkImageView to handle the remote images.
