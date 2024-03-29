# PMP

## 表面表示

* 对几何对象的各种数学表示形式

* 选择一个适当的表示来支持某些操作的有效实现

* 高视角观察，曲面表示法有两种，参数化表示和隐式表示。

  * 参数化表示：给出每个参数映射到对应曲面上的哪个点

  * 隐式表示：给出曲面方程函数

  * 通常复杂曲面不能仅仅通过一个函数即可表示，通常需采用分段函数表示【不同作用域有不同函数表示】，在分段连接处如何平滑表示是一个难点。

  * 在参数化情况下，最常见的分段曲面定义是将曲面分割成三角形或四边形。

    对于隐式的表面定义，嵌入空间通常被分成六面体（体素）或四面体单元。

  * 两种表示方式有对应的优缺点，因此对于不同几何问题，应该选择对应的表示方式。

* 几何操作分类

  * 校验：曲面属性进行采样
  * 查找：如何查询点在曲面包围的实体内部还是外部、查询点到点的距离
  * 修改：修改曲面拓扑结构等

* 对于上面列举的操作，参数化和隐式曲面表示有互补的优势，因此，一种高效的在两者间的转换方法也是一个关键

### 曲面定义和特性

* 普遍定义：嵌入在三唯空间中的可定向连续二维流形



拓展资料：

* https://chamilo.grenoble-inp.fr/courses/ENSIMAG4MMG3D6/document/slides/2-geometric-representations.pdf【todo 待看】

