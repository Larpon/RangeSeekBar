# RangeSeekBar

This is a custom Android View that tries to mimic the behavior of the JQueryUI Slider widget.
![Screenshot of example app](https://github.com/Larpon/RangeSeekBarExamples/blob/master/screenshot.png "Screenshot of example app")

RangeSeekBar is a custom view for the Android platform that makes it possible to have a SeekBar with more thumbs on it. The bar can be setup programmatically or via XML for both Horizontal and Vertical usecases. It supports custom drawables for the backgrund, track and thumbs.

The view should work on Android devices from API level 4 and up (Android 1.6 Donut).

The API level bump from 3 to 4 explanation can be found in [this commit](https://github.com/Larpon/RangeSeekBar/commit/3deea24f3c8318bd1f8ccff05a9c1e5b91b8b5b5)

---

## Usage

###Eclipse
To include this library in your project please refer to Lars Vogel's tutorial on how to use Android libraries with Eclipse:
http://www.vogella.com/tutorials/AndroidLibraryProjects/article.html

Lars explain things better than I ever could. You can include RangeSeekBar as a library source (import it as an Android Library in Eclipse) or you can use it as a .jar library (include by copying one of the release tag .jars to your project's libs/ folder).


### Gradle build

To deploy the library to your local Maven repository run the following task:

```
$ ./gradlew install
```

Then, to use the library in your project add the following to your `build.gradle`:

```groovy
dependencies {
    compile 'larpon.android.view:range-seek-bar:1.2.1'
}
```

---
## Examples

For example usage please refer to the RangeSeekBarExamples repository:
https://github.com/Larpon/RangeSeekBarExamples
