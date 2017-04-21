ColorchangeIndicator
===
        滑动变色的viewpager指示器

使用
===
        <com.kxl.atu.colorchangeindicator.view.ColorTrackVie</br>
                android:id="@+id/id_changeTextColorView"</br>
                android:layout_width="match_parent"</br>
                android:layout_height="wrap_content"</br>
                android:layout_centerInParent="true"</br>
                android:background="#44ff0000"</br>
                android:padding="10dp"</br>
                kxl:progress="0"</br>
                kxl:text="孔祥磊"</br>
                kxl:text_change_color="#ffff0000"</br>
                kxl:text_origin_color="#ff000000"</br>
                kxl:text_size="60sp" /></br>

## 注意
* `progress`[0.0f , 1.0f]</br>
* `text`绘制的文本</br>
* `text_change_color`目标颜色</br>
* `text_origin_color`原始颜色</br>
* `text_size`字体大小</br>
* `direction`方向，枚举类型，支持：left,right,top,bottom</br>

结合viewpager使用效果图
====
![](https://raw.githubusercontent.com/hongyangAndroid/ColorTrackView/master/sample_ColorTrackeView/changecolortvdemo.gif)
        
