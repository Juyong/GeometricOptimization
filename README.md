## 课程介绍

考虑到数值优化在数字几何处理研究领域的重要性，在2018年8月广西桂林举行的CAD&CG GDC联合会议上，中国科学技术大学数学科学学院的张举勇副教授发起了“几何优化”专题研讨会，并邀请了国内外该研究领域的几位华人学者做了精彩的研讨会报告。

数字几何处理流程中，包含点云注册、曲面重建、网格去噪、高质量网格生成、网格变形、形状分析、物理模拟与加工等多个处理步骤。以上诸多问题可转换为优化相应的目标函数，同时一些几何与物理材料约束可表达为优化问题的软约束或硬约束。如何使用现有的数值优化算法或者设计更加高效的算法进行求解是我们通常面临的问题。在此课程中，我们将首先介绍相关的数值优化算法基础，然后介绍数字几何处理中的常见问题与相应的高效优化算法，最后介绍如何采用深度学习等工具进行高效的求解。

## 数值优化基础

[辛士庆](http://www.cs.sdu.edu.cn/zh/~xinshiqing)：无约束优化，如线性方程组求解、牛顿法、拟牛顿法等，[课件](https://github.com/Juyong/GeometricOptimization/blob/master/Slides/UnConstrainedOpt.pdf)

[邓柏林](http://www.bdeng.me/)：带约束优化，如ADMM算法等，以及稀疏模型介绍，[课件](https://github.com/Juyong/GeometricOptimization/blob/master/Slides/ConstrainedOpt.pdf)

## 数字几何处理问题与高效求解

[来煜坤](https://users.cs.cf.ac.uk/Yukun.Lai/)：匹配、注册，[课件]()

[傅孝明](http://staff.ustc.edu.cn/~fuxm/)：参数化、变形、网格生成，[课件](https://github.com/Juyong/GeometricOptimization/blob/master/Slides/Mapping.pdf)

[辛士庆](http://www.cs.sdu.edu.cn/zh/~xinshiqing)：测地线及其求解，[课件](https://github.com/Juyong/GeometricOptimization/blob/master/Slides/GeodesicComputing.pdf)

[邓柏林](http://www.bdeng.me/)：物理模拟、Fabrication，以及带几何约束优化问题的Local-Global求解算法，[课件](https://github.com/Juyong/GeometricOptimization/blob/master/Slides/LocalGlobal.pdf)

## 基于学习的几何优化问题求解

[来煜坤](https://users.cs.cf.ac.uk/Yukun.Lai/)：基于深度学习的几何建模，[课件]()

[张举勇](http://staff.ustc.edu.cn/~juyong/)：基于深度学习的三维人脸建模，[课件](https://github.com/Juyong/GeometricOptimization/blob/master/Slides/DL-3DFace.pdf)