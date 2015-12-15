# UnstopScrollViewPager
problem: when autoscrollviewpager is not located at the top page, scroll/fling up and down will cause autoscrollviewpager to stop.
fix: rewrite MotionEvent.ACTION_MOVE handling under onTouchEvent(MotionEvent)
