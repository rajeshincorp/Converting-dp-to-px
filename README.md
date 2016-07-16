# Converting-dp-to-px
<h2>Code to convert dp(density independent pixel) to px(pixel)</h2>

 <h4>int dp = 100;</b> <h4>
 <h4>Resources r = getResources();</h4> <br>
 <h4>float pixel = TypedValue.applyDimension(TypedValue.COMPLEX_UNIT_DIP, 16, r.getDisplayMetrics());</h4>
