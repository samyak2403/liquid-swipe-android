# Liquid Swipe Android



![pv](https://pageview.vercel.app/?github_user=liquid-swipe-android)


![Animation](https://raw.githubusercontent.com/Cuberto/liquid-swipe/master/Screenshots/animation.gif)

## Requirements

- Android 5.0+

A library that allows for a beautiful liquid swipe effect in your Android applications.

## Installation

Step 1. Add the JitPack repository to your build file 
  ```
  allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
  ```

Add the following dependency to your `build.gradle` file:

```groovy
dependencies {
    implementation 'com.github.samyak2403:liquid-swipe-android:1.0'
}
```

## Usage

Add LiquidPager to your xml and use it like you would ViewPager

```

    <com.samyak2403.liquid_swipe.LiquidPager
        android:id="@+id/pager"
        android:layout_width="match_parent"
        android:layout_height="match_parent" />
        
```
## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
