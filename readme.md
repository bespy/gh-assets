This is a repo of Gifs for Github Readme files. I tried using Google Cloud Storage Buckets with both unified and specific access and prevent public access option off but I was unable to get that to work. I could use a free image host but I didn't have time to read the user licenses for free image hosting. In the end pushing the Gifs to a repo seems to have worked. eg.

```
![Image 5](https://github.com/jacob30/gh-assets/blob/main/td1a.gif)

<img src="https://github.com/jacob30/gh-assets/blob/main/td1a.gif"
     alt="sample image 5"
     style="display: block; margin-right: auto; margin-left: auto; width: 90%;
     box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19)" />
```

I tried these variations that did not work:

```
![Image 0](https://storage.googleapis.com/assets-gh/td1a.gif)

![Image 1](https://storage.googleapis.com/assets-gh-md/td1a.gif)

![Image 2](https://share.gifyoutube.com/KzB6Gb.gif)

[![Demo Doccou alpha](http://share.gifyoutube.com/KzB6Gb.gif)](https://www.youtube.com/watch?v=ek1j272iAmc)

<img src="https://storage.googleapis.com/assets-gh/td1a.gif"
     alt="sample image 0"
     style="display: block; margin-right: auto; margin-left: auto; width: 90%;
     box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19)" />

<img src="https://storage.googleapis.com/assets-gh-md/td1a.gif"
     alt="sample image 1"
     style="display: block; margin-right: auto; margin-left: auto; width: 90%;
     box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19)" />

<img src="http://share.gifyoutube.com/KzB6Gb.gif"
     alt="sample image 2"
     style="display: block; margin-right: auto; margin-left: auto; width: 90%;
     box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19)" />
```
