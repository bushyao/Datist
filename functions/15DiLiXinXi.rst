.. _DiLiXinXi:
地理信息
======================

AddressLat
~~~~~~~~~~~~~~~~~~
函数体：AddressLat(string)

返回值：Double

说明：获取地名对应的纬度坐标。

AddressLon
~~~~~~~~~~~~~~~~~~
函数体：AddressLon(string)

返回值：Double

说明：获取地名对应的经度坐标。

AddressStd
~~~~~~~~~~~~~~~~~~
函数体：AddressStd(string)

返回值：String

说明：标准化地名书写。

Area
~~~~~~~~~~~~~~~~~~
函数体：Area(Points)

返回值：Double

说明：返回多边形的面积；式中Points为多边形边界，数据格式：x1 y1,x2 y2,x3 y3。

函数体：Area(Points,EPSG)

返回值：Double

说明：返回多边形的面积；式中Points为多边形边界，数据格式：x1 y1,x2 y2,x3 y3；EPSG为投影带号。

Beijing54ToXian80
~~~~~~~~~~~~~~~~~~
函数体：Beijing54ToXian80(Real X,Real Y,Bool IsY)

返回值：Double

说明：将北京54坐标转换为西安80，如IsY为True或1，返回横坐标Y；否则返回纵坐标X。

Beijing54_3To6
~~~~~~~~~~~~~~~~~~
函数体：Beijing54_3To6(Real X,Real Y,Bool IsY)

返回值：Double

说明：将北京54的三度带坐标转换为六度带坐标，如IsY为True或1，返回横坐标Y；否则返回纵坐标X。

Beijing54_6To3
~~~~~~~~~~~~~~~~~~
函数体：Beijing54_6To3(Real X,Real Y,Bool IsY)

返回值：Double

说明：将北京54的六度带坐标转换为三度带坐标，如IsY为True或1，返回横坐标Y；否则返回纵坐标X。

Beijing54toLL
~~~~~~~~~~~~~~~~~~
函数体：Beijing54toLL(Real X,Real Y,Bool IsLongitude)

返回值：Double

说明：将北京54坐标转换为经纬度坐标（只适应于鄂尔多斯盆地）。式中北京54坐标（X,Y）,X为横坐标(东方向)，Y为纵坐标(北方向)；如IsLongitude为True或1，返回经度值；否则返回纬度值。

Bmap2Gmap
~~~~~~~~~~~~~~~~~~
函数体：Bmap2Gmap(string coord)

返回值：String

说明：将百度坐标转换为gooleMap坐标（间接方法）,coord为'lng,lat'。

函数体：Bmap2Gmap(string coord,bool toshape)

返回值：String

说明：将百度坐标转换为gooleMap坐标（间接方法）,toshape为真，返回点图元。

Bmap2GmapOnline
~~~~~~~~~~~~~~~~~~
函数体：Bmap2GmapOnline(string coord)

返回值：String

说明：通过百度地图API，将百度坐标转换为gooleMap坐标（间接方法）,coord为'lng,lat'。

函数体：Bmap2GmapOnline(string coord,bool toshape)

返回值：String

说明：通过百度地图API，将百度坐标转换为gooleMap坐标（间接方法）,toshape为真，返回点图元。

Buffer
~~~~~~~~~~~~~~~~~~
函数体：Buffer(Shape,Double dist)

返回值：Polygon

说明：计算图元的缓冲区,dist为距离（单位:米）

Centroid
~~~~~~~~~~~~~~~~~~
函数体：Centroid(Shape)

返回值：Point

说明：返回图元Shape的中心坐标；Shape为图元坐标。

CentroidDistance
~~~~~~~~~~~~~~~~~~
函数体：CentroidDistance(Shape1,Shape2)

返回值：Double

说明：两个图元的中心距离；式中Shape1,Shape2为图元坐标,坐标系为西安80经纬度，返回距离单位为米。

CombineTypeDifference
~~~~~~~~~~~~~~~~~~
函数体：CombineTypeDifference(Shape,SubShape)

返回值：Shape

说明：两个图元的差集，Shape中不包含SubShape的部分。

CombineTypeIntersection
~~~~~~~~~~~~~~~~~~
函数体：CombineTypeIntersection(Shape1,Shape2)

返回值：Shape

说明：求两个图元的交集，Shape1、Shape2的公共部分。

CombineTypeSymmetricalDifference
~~~~~~~~~~~~~~~~~~
函数体：CombineTypeSymmetricalDifference(Shape1,Shape2)

返回值：Shape

说明：两个图元的异或集，Shape1和Shape2之间非公共部分。

CombineTypeUnion
~~~~~~~~~~~~~~~~~~
函数体：CombineTypeUnion(Shape1,Shape2)

返回值：Shape

说明：求两个图元的并集，新的图元包含Shape1、Shape2。

DegreesToDigital
~~~~~~~~~~~~~~~~~~
函数体：DegreesToDigital(String)

返回值：Double

说明：将度分秒格式的经纬度转化为数字，例如：108°54′36″转为 108.91 或是 108 54 36转为108.91。

DigitalToDegrees
~~~~~~~~~~~~~~~~~~
函数体：DigitalToDegrees(Double)

返回值：String

说明：将数字经纬度转为度分秒格式,如：108.91 转为 108°54′36″。

函数体：DigitalToDegrees(Double,DecimalPlace)

返回值：String

说明：将数字经纬度转为度分秒格式,如：108.91 转为 108°54′36″。 DecimalPlace其中DecimalPlace定义秒的小数位，默认为6位

DistanceByDegree
~~~~~~~~~~~~~~~~~~
函数体：DistanceByDegree(Shape1,Shape2)

返回值：Double

说明：计算两个图元的距离，图元坐标为经纬度，距离单位为度。

DistanceByMeter
~~~~~~~~~~~~~~~~~~
函数体：DistanceByMeter(Shape1,Shape2)

返回值：Double

说明：计算两个图元的距离，图元坐标为经纬度，距离单位为米。

EndPoint
~~~~~~~~~~~~~~~~~~
函数体：EndPoint(Shape)

返回值：Point

说明：返回图元Shape的最后一个端点；Shape为折线或多边形图元。

Extent2Polygon
~~~~~~~~~~~~~~~~~~
函数体：Extent2Polygon(String)

返回值：Polygon

说明：返回边界矩形；式中String“XMin，XMax，YMin，YMax”为边界的最值(X-long,Y-Lat)。

函数体：Extent2Polygon(XMin,XMax,YMin,YMax)

返回值：Polygon

说明：返回边界矩形；式中“XMin，XMax，YMin，YMax”为边界的最值(X-long,Y-Lat)。

Extent2Polyline
~~~~~~~~~~~~~~~~~~
函数体：Extent2Polyline(XMin,XMax,YMin,YMax)

返回值：Polyline

说明：返回边界矩形线；式中“XMin，XMax，YMin，YMax”为边界的最值(X-long,Y-Lat)。

FeatureInPolygon
~~~~~~~~~~~~~~~~~~
函数体：FeatureInPolygon(Feature,Polygon)

返回值：Boolean

说明：判断图元Feature是否在图元Polygon之内。

FirstPoint
~~~~~~~~~~~~~~~~~~
函数体：FirstPoint(Shape)

返回值：Point

说明：返回图元Shape的第一个端点；Shape为折线或多边形图元。

Generalize
~~~~~~~~~~~~~~~~~~
函数体：Generalize(Shape,Double Threshold)

返回值：Polygon

说明：减少多边形或折线中的端点数,dist为阈值（单位:米）

GetAddress
~~~~~~~~~~~~~~~~~~
函数体：GetAddress(string lng,string lat)

返回值：String

说明：逆地理编码，即逆地址解析，由百度经纬度信息得到结构化地址信息。

函数体：GetAddress(string lng,string lat,bool hasdesc)

返回值：String

说明：逆地理编码，即逆地址解析，由百度经纬度信息得到结构化地址信息；hasdesc为真返回详细信息。

GetCoordinate
~~~~~~~~~~~~~~~~~~
函数体：GetCoordinate(string address)

返回值：String

说明：地理编码：地址解析，由详细到街道的结构化地址得到百度经纬度信息。

函数体：GetCoordinate(string address,bool toshape)

返回值：String

说明：地理编码：地址解析，由详细到街道的结构化地址得到百度经纬度信息； toshape为真，返回点图元。

HDGIS2Polygon
~~~~~~~~~~~~~~~~~~
函数体：HDGIS2Polygon(String)

返回值：Polygon

说明：将HDGIS明码多边形转为Polygon。

LLToBeijing54_3
~~~~~~~~~~~~~~~~~~
函数体：LLToBeijing54_3(Real Longitude ,Real Latitude ,Bool IsY)

返回值：Double

说明：将经纬度坐标转换为北京54的3度分带坐标，如IsY为True或1，返回横坐标Y；否则返回纵坐标X。

LLToBeijing54_6
~~~~~~~~~~~~~~~~~~
函数体：LLToBeijing54_6(Real Longitude ,Real Latitude ,Bool IsY)

返回值：Double

说明：将经纬度坐标转换为北京54的6度分带坐标，如IsY为True或1，返回横坐标Y；否则返回纵坐标X。

LLToXian80_3
~~~~~~~~~~~~~~~~~~
函数体：LLToXian80_3(Real Longitude ,Real Latitude ,Bool IsY)

返回值：Double

说明：将经纬度坐标转换为西安80的3度分带坐标，如IsY为True或1，返回横坐标Y；否则返回纵坐标X。

LLToXian80_6
~~~~~~~~~~~~~~~~~~
函数体：LLToXian80_6(Real Longitude ,Real Latitude ,Bool IsY)

返回值：Double

说明：将经纬度坐标转换为西安80的6度分带坐标，如IsY为True或1，返回横坐标Y；否则返回纵坐标X。

MapIdNew
~~~~~~~~~~~~~~~~~~
函数体：MapIdNew(Double Longitude,Double Latitude,String Scale)

返回值：String

说明：返回坐标对应的新图幅号。Longitude为经度，Latitude为纬度，Scale为例尺S100W, S50W, S25W, S10W, S5W, S2_5W, S1W, S5K。

MapIdNew2Old
~~~~~~~~~~~~~~~~~~
函数体：MapIdNew2Old(String MapIdNew)

返回值：String

说明：返回新图幅号对应的旧图幅号。

MapIdOld
~~~~~~~~~~~~~~~~~~
函数体：MapIdOld(Double Longitude,Double Latitude,String Scale)

返回值：String

说明：返回坐标对应的旧图幅号。Longitude为经度，Latitude为纬度，Scale为例尺S100W, S50W, S25W, S10W, S5W, S2_5W, S1W, S5K。

MapIdOld2New
~~~~~~~~~~~~~~~~~~
函数体：MapIdOld2New(String MapIdOld)

返回值：String

说明：返回旧图幅号对应的新图幅号。

PointInPolygon
~~~~~~~~~~~~~~~~~~
函数体：PointInPolygon(Polygon,X,Y)

返回值：Boolean

说明：判断点是否在多边形内，X为点横坐标（经度），Y为点纵坐标（纬度）。点在多边形内返回真（1），否则返回值假（0）。

PointInPolygon2
~~~~~~~~~~~~~~~~~~
函数体：PointInPolygon2(PolygonWKB,X,Y)

返回值：Boolean

说明：判断点是否在多边形内，式中WKB为多边形边界(WKB格式)，X为点横坐标（经度），Y为点纵坐标（纬度）。点在多边形内返回真（1），否则返回值假（0）。

PointX
~~~~~~~~~~~~~~~~~~
函数体：PointX(Point)

返回值：Double

说明：返回点图元的X坐标。

PointY
~~~~~~~~~~~~~~~~~~
函数体：PointY(Point)

返回值：Double

说明：返回点图元的Y坐标。

PolygonArea
~~~~~~~~~~~~~~~~~~
函数体：PolygonArea(Polygon)

返回值：Double

说明：返回多边形的面积。

函数体：PolygonArea(Polygon,EPSG)

返回值：Double

说明：返回多边形的面积；EPSG为坐标系编号，WGS 84为4326；北京为4214；西安80为4610。

ProjectionTransformation
~~~~~~~~~~~~~~~~~~
函数体：ProjectionTransformation(Real X,Real Y,Int sourceEpsg, Int targetEpsg,Bool IsY)

返回值：Double

说明：坐标投影变换，坐标(X,Y)如IsY为True或1，返回横坐标Y；否则返回纵坐标X。

ShapeContain
~~~~~~~~~~~~~~~~~~
函数体：ShapeContain(ShapeA,ShapeB)

返回值：Boolean

说明：判断图元ShapeA是否包含图元ShapeB。

ShapeDisjoint
~~~~~~~~~~~~~~~~~~
函数体：ShapeDisjoint(ShapeA,ShapeB)

返回值：Boolean

说明：判断图元ShapeA是否与图元ShapeB相离。

ShapeExtent
~~~~~~~~~~~~~~~~~~
函数体：ShapeExtent(Shape)

返回值：String

说明：返回多边形的边界；返回值“XMin，XMax，YMin，YMax”(X-long,Y-Lat)。

函数体：ShapeExtent(Shape,Type)

返回值：Double

说明：返回多边形的边界；Type为边界值类型：0为XMin，1为XMax，2为YMin，3为YMax。

ShapeIntersect
~~~~~~~~~~~~~~~~~~
函数体：ShapeIntersect(ShapeA,ShapeB)

返回值：Boolean

说明：判断图元ShapeA与图元ShapeB是否相交。

ShapeLength
~~~~~~~~~~~~~~~~~~
函数体：ShapeLength(Poly)

返回值：Double

说明：返回多边形或折线的周长；坐标系为西安80。

函数体：ShapeLength(Poly,EPSG)

返回值：Double

说明：返回多边形或折线的周长；EPSG为坐标系编号，WGS 84为4326；北京为4214；西安80为4610。

ShapeNumParts
~~~~~~~~~~~~~~~~~~
函数体：ShapeNumParts(Shape)

返回值：Integer

说明：返回图元的组成部分数；Shape为折线或多边形图元。

ShapeOverlap
~~~~~~~~~~~~~~~~~~
函数体：ShapeOverlap(ShapeA,ShapeB)

返回值：Boolean

说明：判断图元ShapeA是否与图元ShapeB重叠。

ShapePointCount
~~~~~~~~~~~~~~~~~~
函数体：ShapePointCount(Shape)

返回值：Integer

说明：返回图元的端点数；Shape为折线或多边形图元。

ShapeTouch
~~~~~~~~~~~~~~~~~~
函数体：ShapeTouch(ShapeA,ShapeB)

返回值：Boolean

说明：判断图元ShapeA是否与图元ShapeB接触。

ShapeType
~~~~~~~~~~~~~~~~~~
函数体：ShapeType(Shape)

返回值：String

说明：返回图元的类型；Shape为图元。

ShapeWithIn
~~~~~~~~~~~~~~~~~~
函数体：ShapeWithIn(ShapeA,ShapeB)

返回值：Boolean

说明：判断图元ShapeB是否包含图元ShapeA。

Smooth
~~~~~~~~~~~~~~~~~~
函数体：Smooth(Shape,Integer factor)

返回值：Polygon

说明：图元平滑Shape为多边形或折线，Factor为平滑因子（单位:米）

ToLine
~~~~~~~~~~~~~~~~~~
函数体：ToLine(Point1，Point2...)

返回值：Polyline

说明：将点图元连成线图元。

ToLine2
~~~~~~~~~~~~~~~~~~
函数体：ToLine2(Points)

返回值：Polyline

说明：将点图元连成线图元。参数Points是逗号分隔的点图元集（字符串）。

ToPoint
~~~~~~~~~~~~~~~~~~
函数体：ToPoint(lon,lat)

返回值：Point

说明：将经纬度坐标转化点图元。

WGS84ToBmap
~~~~~~~~~~~~~~~~~~
函数体：WGS84ToBmap(string coord)

返回值：String

说明：将gooleMap坐标转换为百度坐标，coord为'lng,lat'。

函数体：WGS84ToBmap(string coord,bool toshape)

返回值：String

说明：将gooleMap坐标转换为百度坐标，toshape为真，返回点图元。

WGS84ToBmapOnline
~~~~~~~~~~~~~~~~~~
函数体：WGS84ToBmapOnline(string coord)

返回值：String

说明：通过百度地图API，将gooleMap坐标转换为百度坐标，coord为'lng,lat'。

函数体：WGS84ToBmapOnline(string coord,bool toshape)

返回值：String

说明：通过百度地图API，将gooleMap坐标转换为百度坐标，toshape为真，返回点图元。

Xian80ToBeijing54
~~~~~~~~~~~~~~~~~~
函数体：Xian80ToBeijing54(Real X,Real Y,Bool IsY)

返回值：Double

说明：将西安80坐标转换为北京54，如IsY为True或1，返回横坐标Y；否则返回纵坐标X。

Xian80toLL
~~~~~~~~~~~~~~~~~~
函数体：Xian80toLL(Real X,Real Y,Bool IsLongitude)

返回值：Double

说明：将西安80坐标转换为经纬度坐标（只适应于鄂尔多斯盆地）。式中西安80坐标（X,Y）,X为横坐标(东方向)，Y为纵坐标(北方向)；如IsLongitude为True或1，返回经度值；否则返回纬度值。

Xian8_3To6
~~~~~~~~~~~~~~~~~~
函数体：Xian8_3To6(Real X,Real Y,Bool IsY)

返回值：Double

说明：将西安80的三度带坐标转换为六度带坐标，如IsY为True或1，返回横坐标Y；否则返回纵坐标X。

Xian8_6To3
~~~~~~~~~~~~~~~~~~
函数体：Xian8_6To3(Real X,Real Y,Bool IsY)

返回值：Double

说明：将西安80的六度带坐标转换为三度带坐标，如IsY为True或1，返回横坐标Y；否则返回纵坐标X。
