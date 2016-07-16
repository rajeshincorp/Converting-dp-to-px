# Converting-dp-to-px
<h2>Code to convert dp(density independent pixel) to px(pixel)</h2><br>

 <b>int dp = 100;</b> <br>
 <b>Resources r = getResources();</b> <br>
 <b>float pixel = TypedValue.applyDimension(TypedValue.COMPLEX_UNIT_DIP, 16, r.getDisplayMetrics());</b>
