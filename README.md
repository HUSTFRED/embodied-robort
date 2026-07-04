  #  embodied-robort
  # 项目结构


 | 目录 | 说明 |
 |------|------|
 | `recoil_model.py` | 后坐力模型类（力载荷、分步施加逻辑） |
 | `recoil_config.yaml` | 物理参数（质量、初速、α系数、脉冲宽度等） |
 | `utils.py` | 辅助函数（坐标变换、冲量校验等）|
 | `integrate_isaac.py` | Isaac Sim 集成示例（如何在环境中挂载）|
 | `test_recoil.py ` | 单元测试（验证总冲量、峰值等）|
