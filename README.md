# Converting-dp-to-px
<h2>Code to convert dp(density independent pixel) to px(pixel)</h2>

 <h4>int dp = 100;<br> 
 Resources r = getResources(); <br>
 float pixel = TypedValue.applyDimension(TypedValue.COMPLEX_UNIT_DIP, 16, r.getDisplayMetrics());</h4>
