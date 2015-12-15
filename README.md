# UnstopScrollViewPager
fix to: https://github.com/angeldevil/AutoScrollViewPager
problem: when autoscrollviewpager is not located at the top page, scroll/fling up and down will cause autoscrollviewpager to stop.
solution: rewrite MotionEvent.ACTION_MOVE handling under onTouchEvent(MotionEvent)
