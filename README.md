## 类简介
* 就两个方法，一个传入dp值返回px值，另一个传入px值返回dp值


    public class DensityUtils {

    public static int dip2px(float dp, Context ctx) {
        float density = ctx.getResources().getDisplayMetrics().density;
        int px = (int) (dp * density + 0.5f);
        return px;
    }

    public static float px2dip(int px, Context ctx) {
        float density = ctx.getResources().getDisplayMetrics().density;
        float dip = px / density;
        return dip;
    }
----
##使用方法
* 直接把代码复制创建java类即可


----
# 关于作者
* Email： <78602765@qq.com>
* liangtian
* 有任何建议或者使用中遇到问题都可以给我发邮件
