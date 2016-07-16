# Converting-dp-to-px
Code to convert dp(density independent pixel) to px(pixel)

 int dp = 100;
 Resources r = getResources();
 float pixel = TypedValue.applyDimension(TypedValue.COMPLEX_UNIT_DIP, 16, r.getDisplayMetrics());
