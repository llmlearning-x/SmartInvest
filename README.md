# SmartInvest
程序员的个人财富课实战例子

## 项目概述
SmartInvest 是一个专注于个人财富管理的实战项目集合，包含以下子项目：

- **smartMortgage**：房贷模拟程序，用于计算和分析房贷还款计划。
- **investTable**：投资跟踪表模版，帮助用户记录和跟踪投资收益。
- **calendarStrategy**：日历效应策略的数据、回测程序和分析结果，用于研究市场规律。
- **quantTrading**：量化投资系统实战项目，提供完整的量化交易流程和策略实现。

## 环境配置指南

### 创建 Conda 虚拟环境
```

# 创建名为 SmartInvest 的 conda 虚拟环境，指定 Python 版本（例如 3.10）
conda create -n SmartInvest python=3.10 -y

# 激活 SmartInvest 环境
conda activate SmartInvest

# 更新 pip
pip install --upgrade pip

# 安装 ipykernel 以便将环境添加到 Jupyter 内核
pip install ipykernel

# 将 SmartInvest 环境添加至 Jupyter 内核，显示名为 "Python (SmartInvest)"
python -m ipykernel install --user --name SmartInvest --display-name "Python (SmartInvest)"

# 安装依赖（假设你有 requirements.txt 文件）
pip install -r ./aliyun_acp_learning/requirements.txt

# 退出虚拟环境
conda deactivate

# ————  可选：配置 pip 使用国内镜像源 ————
# 永久设置（推荐）
pip config set global.index-url https://pypi.tuna.tsinghua.edu.cn/simple

# 或者临时使用（安装时指定）
pip install -r ./aliyun_acp_learning/requirements.txt -i https://pypi.tuna.tsinghua.edu.cn/simple
