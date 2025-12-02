# 科技树Buffer修改任务清单

## 任务概述
为"实际科技树 Technology Tree"部分下的每个科技添加对应的Buffer科技，并修改母科技的LeadsTo关系。

## 修改步骤

### 第一阶段：处理SurvivalPlan系列（当前执行）
- [x] 分析SurvivalPlan系列科技现状
- [ ] 修正T_SurvivalPlan_1的buffer为Buffer格式
- [ ] 修正T_SurvivalPlan_2的buffer为Buffer格式  
- [ ] 修正T_SurvivalPlan_3的buffer为Buffer格式
- [ ] 修正T_SurvivalPlan_4的buffer为Buffer格式
- [ ] 验证母科技LeadsTo关系正确性

### 第二阶段：添加计算机系列Buffer（待执行）
- [ ] 为T_Computer_1添加T_Computer_1_Buffer
- [ ] 为T_Computer_2添加T_Computer_2_Buffer
- [ ] 为T_Computer_3添加T_Computer_3_Buffer
- [ ] 为T_Computer_4添加T_Computer_4_Buffer
- [ ] 为T_Computer_5添加T_Computer_5_Buffer
- [ ] 修改各母科技的LeadsTo关系

### 第三阶段：添加AI系列Buffer（待执行）
- [ ] 为T_AI_1添加T_AI_1_Buffer
- [ ] 为T_AI_2添加T_AI_2_Buffer
- [ ] 为T_AI_3添加T_AI_3_Buffer
- [ ] 修改各母科技的LeadsTo关系

### 第四阶段：添加物流系列Buffer（待执行）
- [ ] 为T_Logistics_1添加T_Logistics_1_Buffer
- [ ] 为T_Logistics_2添加T_Logistics_2_Buffer
- [ ] 为T_Logistics_3添加T_Logistics_3_Buffer
- [ ] 为T_Logistics_4添加T_Logistics_4_Buffer
- [ ] 修改各母科技的LeadsTo关系

### 第五阶段：添加无人机系列Buffer（待执行）
- [ ] 为T_UnmannedVehicle_1添加T_UnmannedVehicle_1_Buffer
- [ ] 为T_UnmannedVehicle_2添加T_UnmannedVehicle_2_Buffer
- [ ] 为T_UnmannedVehicle_3添加T_UnmannedVehicle_3_Buffer
- [ ] 修改各母科技的LeadsTo关系

### 第六阶段：添加航空技术系列Buffer（待执行）
- [ ] 为T_AviationTech_1添加T_AviationTech_1_Buffer
- [ ] 为T_AviationTech_2添加T_AviationTech_2_Buffer
- [ ] 为T_AviationTech_3添加T_AviationTech_3_Buffer
- [ ] 为T_AviationTech_4添加T_AviationTech_4_Buffer
- [ ] 为T_AviationTech_5添加T_AviationTech_5_Buffer
- [ ] 修改各母科技的LeadsTo关系

### 第七阶段：处理其他科技系列（批量处理）
- [ ] 工程系列科技（T_Engineering_*）
- [ ] 军事工程系列（T_MilitaryEngineering_*）
- [ ] 防御科技系列（EMP防御、生物化学防御等）
- [ ] 陆军科技系列
- [ ] 海军科技系列
- [ ] 空军科技系列
- [ ] 核武器系列
- [ ] 弹道导弹系列
- [ ] 空间科技系列
- [ ] 导弹科技系列
- [ ] 防御科技系列
- [ ] 雷达科技系列
- [ ] 电子战科技系列

## 修改原则
1. Buffer科技只包含3行严格格式
2. 母科技保持原有LeadsTo，新增指向Buffer
3. Buffer科技LeadsTo指向母科技的下一个科技
4. 统一使用大写B的"Buffer"格式
5. 分批处理，确保每步正确执行

## 当前进度
正在执行第一阶段：处理SurvivalPlan系列Buffer格式修正
