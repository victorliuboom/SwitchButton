SwitchButton
============

SwitchButton Widget For Android Developers
使用方法 还没有做maven引用

<img src="https://github.com/lukebiubiubiu/SwitchButton/blob/master/switchbutton.gif"/>

<b>How To Use</b>
```xml


        <com.luke.switchbutton.view.LukeSwitchButton
            android:layout_width="54dp"
            toggle:tbOnColor="#f00"
            toggle:tbOffColor="#ddd"
            toggle:tbSpotColor="#00f"
            toggle:tbOffBorderColor="#000"
            toggle:tbBorderWidth="2dp"
            android:layout_height="30dp" >
        </com.luke.switchbutton.view.LukeSwitchButton>
```

```java
        LukeSwitchButton switchBtn;
        
        //切换开关
        switchBtn.toggle();
        //切换无动画
        switchBtn.toggle(false);
        //开关切换事件
        switchBtn.setOnToggleChanged(new OnToggleChanged(){
                @Override
                public void onToggle(boolean on) {
                }
        });
        
        switchBtn.setToggleOn();
        switchBtn.setToggleOff();
        //无动画切换
        switchBtn.setToggleOn(false);
        switchBtn.setToggleOff(false);
        
        //禁用动画
        switchBtn.setAnimate(false);
```
Default Size:width=50dp,height=30dp.




<b>制作人：</b>
刘威  微信：979433196