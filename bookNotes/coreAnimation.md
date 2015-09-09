# iOS Core Animation Advanced Techniques
* CALayer的contentsScale属性是支持高清屏机制的一部分。它决定了由layer自动创建图片的尺寸和显示图片内容的缩放。该值默认是1.0，表示采用每个像素一个点。如果是2.0表示每个像素两个点（高清屏）。对于CGImage，其内部没有缩放的概念。UIImage是有这个概念的。当我们采用kCAGravityResizeAspect时，图片会缩放适配layer，因此这个概念不起作用。
 
