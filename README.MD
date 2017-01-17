# hellocharts-android项目使用

开源地址：[https://github.com/open-android/hellocharts-android](https://github.com/open-android/hellocharts-android "https://github.com/open-android/hellocharts-android")

# 运行效果

![](screenshot.gif)

* 更多干货请下载app


![黑马助手.png](http://upload-images.jianshu.io/upload_images/4037105-f777f1214328dcc4.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

## 使用步骤

### 1. 在project的build.gradle添加如下代码(如下图)

	allprojects {
	    repositories {
	        maven { url "https://jitpack.io" }
	    }
	}

![](build.gradle.png)

### 2. 在Module的build.gradle添加依赖

    compile 'com.github.open-android:hellocharts-android:v1.5.8'


### 3.布局文件使用对应Chart

	<lecho.lib.hellocharts.view.LineChartView
        android:id="@+id/chart"
        android:layout_width="match_parent"
        android:layout_height="match_parent" />

### 4.Activity初始化

	mChart = (LineChartView) findViewById(R.id.chart);
	//...省略，请参考hellowchartssample
	mChart.setLineChartData(data);//给图表设置数据



	
* 详细的使用方法在DEMO里面都演示啦,如果你觉得这个库还不错,请赏我一颗star吧~~~

* 欢迎关注微信公众号

![](http://upload-images.jianshu.io/upload_images/4037105-8f737b5104dd0b5d.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
	


	
