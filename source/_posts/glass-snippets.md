title: glass-snippets
date: 2014-02-11 16:27:03
tags: java,android
---

Add flag to keep the screen on, 


```java
public void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_flag);
        getWindow().addFlags(WindowManager.LayoutParams.FLAG_KEEP_SCREEN_ON);
}


//can be removed with 
getWindow().clearFlags(WindowManager.LayoutParams.FLAG_KEEP_SCREEN_ON);
```

Start the camera intent
```java
startActivity();

		//camera pic taking
Intent cameraIntent = new Intent(MediaStore.ACTION_IMAGE_CAPTURE, null);
startActivityForResult(cameraIntent, 1);

```

keep the  camera unscrambled
 http://stackoverflow.com/questions/19235477/google-glass-preview-image-scrambled-with-new-xe10-release

```java
parameters.setPreviewFpsRange(30000, 30000);
/*
    Camera.Parameters params = camera.getParameters();
    params.setPreviewFpsRange(30000, 30000);
    camera.setParameters(params);
*/

```

open url
```java
		//url opening
		String url = "https://mobile.xtuple.com";
		Intent intent = new Intent(Intent.ACTION_VIEW);
		intent.setData(Uri.parse(url));
		startActivity(intent);

```

trying to build to something shell proprerties
```java
Google Inc.:Glass Development Kit Sneak Peek:15
```