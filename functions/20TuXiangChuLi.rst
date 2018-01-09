.. _TuXiangChuLi:
图像处理
======================

BarCode2D(string info,string displayName)
~~~~~~~~~~~~~~~~~~
返回值：Byte[]

说明：根据信息生成二维码图片。

BarCode2D(string info,string displayName,string LogoImage)
~~~~~~~~~~~~~~~~~~
返回值：Byte[]

说明：根据信息生成二维码图片。

BarCode2D(string info,string displayName,string LogoImage,int FontSize)
~~~~~~~~~~~~~~~~~~
返回值：Byte[]

说明：根据信息生成二维码图片。

ColumnBppCount(Byte[] Image)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：将图像二值化，返回每一列的有值像数个数。

ColumnBppCount(Byte[] Image, Int step)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：将图像二值化，并进行平滑处理，返回每一列的有值像数个数；step指定平滑步长。

GetImageExif(string Image)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：获取图像的描述信息。

GetImageExif(string Image,string tagName)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：获取图像的描述信息。

ImageAddDesc(Byte[] Image,string)
~~~~~~~~~~~~~~~~~~
返回值：Byte[]

说明：在图片上添加一段文字。

ImageClone(Byte[] Image,int left, int top, int right, int bottom)
~~~~~~~~~~~~~~~~~~
返回值：Byte[]

说明：复制指定区域内的图像内容。

ImageFlipX(Byte[] SourceImage)
~~~~~~~~~~~~~~~~~~
返回值：Byte[]

说明：图像水平翻转。

ImageFlipY(Byte[] SourceImage)
~~~~~~~~~~~~~~~~~~
返回值：Byte[]

说明：图像垂直翻转。

ImageInfo(Byte[] Image)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：获取图像的基本信息,输出信息Width,Height,HorizontalResolution,VerticalResolution。

ImageRotate(Byte[] SourceImage,double Angle)
~~~~~~~~~~~~~~~~~~
返回值：Byte[]

说明：图像旋转Angle度；Angle为角度（-360~360），正值为顺时针旋转，负值为逆时针旋转。

ImageToGray(Byte[] Image)
~~~~~~~~~~~~~~~~~~
返回值：Byte[]

说明：图像二值化。

JPG(Byte[] SourceImage)
~~~~~~~~~~~~~~~~~~
返回值：Byte[]

说明：将图片压缩成JPG格式

JPG(Byte[] SourceImage,int Quality)
~~~~~~~~~~~~~~~~~~
返回值：Byte[]

说明：将图片压缩成JPG格式；Quality为压缩图像质量（0~100）。

JPG(Byte[] SourceImage,int Quality,int MaxWidth)
~~~~~~~~~~~~~~~~~~
返回值：Byte[]

说明：将图片压缩成JPG格式；Quality为压缩图像质量（0~100），MaxWidth为最大宽度。

RowBppCount(Byte[] Image)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：将图像二值化，返回每一行的有值像数个数。

RowBppCount(Byte[] Image, Int step)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：将图像二值化，并进行平滑处理，返回每一行的有值像数个数；step指定平滑步长。
