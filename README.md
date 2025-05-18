# Awesome Python Simulator & Electronic Design Tools

> 🚀 收录与整理使用 Python 进行芯片建模、仿真、验证、测试等的优质开源工具项目，帮助研究者、开发者和学生高效入门和选型。

---

**版本：v0.1（持续完善中）**

---

## 为什么需要本项目？

当前 Python 在芯片设计、验证和仿真领域应用越来越广，但相关工具和资源分散、缺乏系统整理。本项目希望为该领域的开发者、教学者与爱好者提供一站式参考和交流平台。

--- 

## 工具分类


### 硬件建模与描述语言（HDL/DSL）

- [PyMTL](https://github.com/cornell-brg/pymtl)
- [PyRTL](https://github.com/UCSBarchlab/PyRTL)：面向教学的 Python RTL 电路设计与仿真平台，适合数字逻辑课程、原型验证。
- [MyHDL](https://github.com/myhdl/myhdl)
- [Migen](https://github.com/m-labs/migen) / [Nmigen](https://github.com/nmigen/nmigen)
- [polyphony](https://pypi.org/project/polyphony/)：可将 Python 代码直接转换为 HDL，支持硬件合成。
- [hdl21](https://pypi.org/project/hdl21/)：用于模拟和数字硬件设计的 Python 领域特定语言。


### HDL 解析与分析工具

- [Pyverilog](https://github.com/PyHDI/Pyverilog)：用于 Verilog 代码解析、分析、转换的 Python 工具，适合自动化设计流程和EDA研究。
- [pyVHDLParser](https://pypi.org/project/pyVHDLParser/)：VHDL 的 Python 解析器，可用于代码分析、抽象语法树生成等。

### 数字电路/逻辑门模拟器

- [BinPy](https://github.com/BinPy/BinPy)：用 Python 进行逻辑门与组合电路的建模与仿真，适合教学、原型实验。
- [DigSim](https://pypi.org/project/digsim-logic-simulator/)：Python 实现的数字逻辑电路仿真器，支持门电路搭建与波形分析。
- [Logisim-evolution](https://github.com/reds-heig/logisim-evolution)：虽为 Java 工具，但有 Python 脚本接口，可辅助数字电路实验和自动化仿真。

### EDA 工具接口与自动化

- [Edalize](https://pypi.org/project/edalize/)：统一调用和管理多种 EDA 工具（如 Icarus, Yosys, ModelSim, Verilator, Vivado 等），支持项目文件生成、批量/GUI 模式运行。
- [FuseSoC](https://pypi.org/project/fusesoc/)：基于 Python 的 SoC 构建和集成工具，支持多种后端仿真器和 EDA 工具。

### 协同仿真与验证

- [cocotb](https://github.com/cocotb/cocotb)
- [pyvpi](https://github.com/antiface/pyvpi)
- [Cocotb-test](https://pypi.org/project/cocotb-test/)：Cocotb 的测试驱动和自动化扩展工具。


### 混合信号/模拟电路仿真

- [PySpice](https://github.com/FabriceSalvaire/PySpice)
- [SKiDL](https://github.com/xesscorp/skidl)
- [PyAMS](https://github.com/d-fathi/PyAMS)：Python 下的混合信号建模和仿真框架。
- [pyopus](https://github.com/xen0n/pyopus)

### 其他相关/辅助工具

- [hdlparse](https://github.com/kevinpt/hdlparse)
- [pyvcd](https://github.com/SanDisk-Open-Source/pyvcd)：一个仿真波形/数据处理辅助工具
- [pyDigitalWaveTools](https://pypi.org/project/pyDigitalWaveTools/)：Python 处理 VCD、FSDB 等数字仿真波形文件的工具。
- [pyverilator](https://github.com/csail-csg/pyverilator)：Python 接口，用于与 Verilator 交互、自动化测试。

---

## 资源与文章

- [PyMTL 在计算机体系结构教学中的应用 - 知乎](https://zhuanlan.zhihu.com/p/286184451)
- [Awesome HDL](https://github.com/drom/awesome-hdl) - 综合 HDL 资源（多语言）
- [超40个芯片类开源项目推荐 - 极术社区](https://aijishu.com/a/1060000000360021)

---

## 贡献方式

1. 欢迎通过 Issue 或 PR 推荐新项目、补充文档、修正错误！
2. 推荐格式见 `CONTRIBUTING.md`，请注明工具名称、简介、项目地址及适用场景。
3. 欢迎提供英文/中文文档、示例代码、实际案例等资料！

---

## 许可证

本项目内容遵循 [MIT License](./LICENSE)。

---

## 联系与交流

- 提问、建议或合作可通过 Issue 或 Discussions 区留言。
- 欢迎关注、Star、Fork 本项目，助力 Python+芯片仿真生态发展！

---
 