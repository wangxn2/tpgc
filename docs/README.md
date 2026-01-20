# TPGC
This repository contains the Python implementation of our submitted paper titled "Trajectory-Aware Multi-RIS Activation and Configuration: A Riemannian Diffusion Method" .

## 项目结构

```
├── config/                     # 配置文件
│   └── settings.py            # 系统参数和常量
├── utils/                     # 工具函数
│   ├── distance_calculator.py # 距离和角度计算
│   └── data_generator.py      # 数据生成工具
├── models/                    # 训练模型存储
│   ├── traj_model_120.h5     # 原始轨迹预测模型
│   ├── improved_traj_model.keras # 改进轨迹预测模型
│   ├── traj_model_trueNorm.npy    # 归一化参数
│   └── cnn_ris_model.h5       # CNN干扰分类模型
├── docs/                      # 文档
│   └── README.md              # 项目说明文档
├── Processed/                 # 处理后的数据
└── main.py                    # 主执行脚本
```




