flowchart TD
    A[系统初始化] -->|录入员工信息| B(员工信息管理)
    A -->|设置薪酬结构| C(薪酬管理)
    A -->|定义绩效指标| D(绩效管理)

    B --> E{日常操作}
    C --> E
    D --> E
    E -->|更新信息| B
    E -->|维护岗位信息| F[HR部门]
    E -->|薪酬调整| G[薪酬发放与记录]
    E -->|跟踪绩效| H[绩效评估与反馈]

    F -->|审核薪酬| G
    G --> I[薪酬计算与发放]
    H --> I

    I --> J[市场调研与合规监控]
    J --> K[合规性报告生成]

    J -->|收集市场数据| L[市场薪酬调研]
    J -->|监控法规变化| M[合规性监控]

    L --> N[市场薪酬分析]
    M --> K

    N -->|调整薪酬政策| C
    K -->|确保合规| C

    E --> O[沟通与反馈]
    O --> P[员工反馈收集]
    O -->|管理层响应| Q[政策调整]

    I --> R[报告与分析]
    R -->|生成报告| S[决策支持]
