KDD2026 《ReCATS: Replay-Free Continual Anomaly Detection for Non-Stationary Multivariate Time Series》

Paper：https://dl.acm.org/doi/10.1145/3770855.3817985

1. **运行训练**(以 weather 数据集为例):
   ```bash
   bash scripts/weather.sh
   ```

2. **修改 validation.py 中的 name 参数**：
   
   `vae_experiments/validation.py`
   ```python
       name = 'weather'  # 修改为对应的数据集名称
   ```

3. **运行计算指标**：
   ```bash
   python vae_experiments/validation.py
   ```


### 数据集对应的 name 值

| 数据集 | name 值 |
|--------|---------|
| Weather | `weather` |
| SWaT | `SWaT` |
| PSM | `PSM` |
| SMAP | `SMAP` |
| MSL | `'MSL` |
| GECCO | `GECCO` |
