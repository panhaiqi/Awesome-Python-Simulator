<!-- Language Switcher / 语言切换 -->
<p align="right">
  <a href="#zh">中文</a> | <a href="#en">English</a>
</p>

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
panhaiqi
can you show me an hello world python code

GitHub Copilot

- [polyphony](https://pypi.org/project/polyphony/)：可将 Python 代码直接转换为 HDL，支持硬件合成。
- [hdl21](https://pypi.org/project/hdl21/)：用于模拟和数字硬件设计的 Python 领域特定语言。


### HDL 解析与分析工具

- [Pyverilog](https://github.com/PyHDI/Pyverilog)：用于 Verilog 代码解析、分析、转换的 Python 工具，适合自动化设计流程和EDA研究。
- [pyVHDLParser](https://pypi.org/project/pyVHDLParser/)：VHDL 的 Python 解析器，可用于代码分析、抽象语法树生成等。

### 数字电路/逻辑门模拟器

- [BinPy](https://github.com/BinPy/BinPy)：用 Python 进行逻辑门与组合电路的建模与仿真，适合教学、原型实验。
- [DigSim](https://pypi.org/project/digsim-logic-simulator/)：Python 实现的数字逻辑电路仿真器，支持门电路搭建与波形分析。
- [Logisim-evolution](https://github.com/reds-heig/logisim-evolution)：虽为 Java 工具，但有 Python 脚本接口，可辅助数字电路实验和自动化仿真。
- [pyFDA](https://pypi.org/project/pyfda/)：Python 下的数字滤波器设计与分析工具。

### EDA 工具接口与自动化

- [Edalize](https://pypi.org/project/edalize/)：统一调用和管理多种 EDA 工具（如 Icarus, Yosys, ModelSim, Verilator, Vivado 等），支持项目文件生成、批量/GUI 模式运行。
- [FuseSoC](https://pypi.org/project/fusesoc/)：基于 Python 的 SoC 构建和集成工具，支持多种后端仿真器和 EDA 工具。

### 协同仿真与验证

- [cocotb](https://github.com/cocotb/cocotb)
- [pyvpi](https://github.com/antiface/pyvpi)
- [Cocotb-test](https://pypi.org/project/cocotb-test/)：Cocotb 的测试驱动和自动化扩展工具。


### 混合信号/模拟电路仿真

- [PySpice](https://pypi.org/project/PySpice/)
- [SKiDL](https://github.com/xesscorp/skidl)
- [PyAMS](https://github.com/d-fathi/PyAMS)：Python 下的混合信号建模和仿真框架。
- [pyopus](https://github.com/xen0n/pyopus)

### AI EDA
- [ChatEDA](https://github.com/wuhy68/ChatEDAv1)：大语言模型 EDA 智能体
- [SNS](https://github.com/Entropy-xcy/sns)：基于深度学习的综合工具，用于探索人工智能驱动的硬件综合任务。
- [Developing synthesis flows without human knowledge](https://github.com/ycunxi/FLowGen-CNNs-DAC18)：基于强化学习的自动综合流程生成工具
- [AutoDMP: Automated DREAMPlace-based Macro Placement](https://github.com/NVlabs/AutoDMP)
- [DeePEB: A Neural Partial Differential Equation Solver for Post Exposure Baking Simulation in Lithography](https://github.com/Brilight/DeePEB)



### 其他相关/辅助工具

- [hdlparse](https://github.com/kevinpt/hdlparse)
- [pyvcd](https://github.com/SanDisk-Open-Source/pyvcd)：一个仿真波形/数据处理辅助工具
- [pyDigitalWaveTools](https://pypi.org/project/pyDigitalWaveTools/)：Python 处理 VCD、FSDB 等数字仿真波形文件的工具。
- [pyverilator](https://github.com/csail-csg/pyverilator)：Python 接口，用于与 Verilator 交互、自动化测试。
- [CircuitNet](https://github.com/huanzhang12/CircuitNet)：开源 EDA 机器学习研究数据集，涵盖布图、综合、时序等多类任务，适合算法训练与评测。

---



## 资源与文章

- [PyMTL 在计算机体系结构教学中的应用 - 知乎](https://zhuanlan.zhihu.com/p/286184451)
- [Awesome HDL](https://github.com/drom/awesome-hdl) - 综合 HDL 资源（多语言）
- [超40个芯片类开源项目推荐 - 极术社区](https://aijishu.com/a/1060000000360021)
AI EDA
- [Awesome Artificial Intelligence for Electronic Design Automation](https://github.com/Thinklab-SJTU/awesome-ai4eda)
- [LLM4EDA: Emerging Progress in Large Language Models for Electronic Design Automation](https://github.com/Thinklab-SJTU/Awesome-LLM4EDA)
- [thu-nics: Awesome AI for EDA](https://github.com/thu-nics/awesome_ai4eda)
- [ai4eda: Awesome AI for EDA](https://ai4eda.github.io/)

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

## 鸣谢

本项目选题由 Copilot 提供，感谢其智能辅助与灵感支持。

---

# <a id="en"></a>Awesome Python Simulator & Electronic Design Tools (English Version)

> 🚀 A curated collection of high-quality open-source projects for chip modeling, simulation, verification, and testing using Python, helping researchers, developers, and students get started and choose tools efficiently.

---

**Version: v0.1 (Continuously improving)**

---

## Why this project?

Currently, Python is increasingly used in chip design, verification, and simulation, but related tools and resources are scattered and lack systematic organization. This project aims to provide a one-stop reference and communication platform for developers, educators, and enthusiasts in this field.

---

## Tool Categories

### Hardware Modeling & Description Languages (HDL/DSL)

- [PyMTL](https://github.com/cornell-brg/pymtl)
- [PyRTL](https://github.com/UCSBarchlab/PyRTL): Python RTL circuit design and simulation platform for teaching, suitable for digital logic courses and prototyping.
- [MyHDL](https://github.com/myhdl/myhdl)
- [Migen](https://github.com/m-labs/migen) / [Nmigen](https://github.com/nmigen/nmigen)
- [polyphony](https://pypi.org/project/polyphony/): Convert Python code directly to HDL, supports hardware synthesis.
- [hdl21](https://pypi.org/project/hdl21/): Python DSL for analog and digital hardware design.

### HDL Parsing & Analysis Tools

- [Pyverilog](https://github.com/PyHDI/Pyverilog): Python tool for Verilog code parsing, analysis, and conversion, suitable for automated design flows and EDA research.
- [pyVHDLParser](https://pypi.org/project/pyVHDLParser/): Python parser for VHDL, supports code analysis and AST generation.

### Digital Circuit/Logic Gate Simulators

- [BinPy](https://github.com/BinPy/BinPy): Logic gate and combinational circuit modeling and simulation in Python, suitable for teaching and prototyping.
- [DigSim](https://pypi.org/project/digsim-logic-simulator/): Digital logic circuit simulator in Python, supports gate building and waveform analysis.
- [Logisim-evolution](https://github.com/reds-heig/logisim-evolution): Java tool with Python scripting interface for digital circuit experiments and automated simulation.
- [pyFDA](https://pypi.org/project/pyfda/): Digital filter design and analysis tool in Python.

### EDA Tool Interfaces & Automation

- [Edalize](https://pypi.org/project/edalize/): Unified management of various EDA tools (Icarus, Yosys, ModelSim, Verilator, Vivado, etc.), supports project file generation and batch/GUI mode.
- [FuseSoC](https://pypi.org/project/fusesoc/): Python-based SoC build and integration tool, supports multiple backend simulators and EDA tools.

### Co-simulation & Verification

- [cocotb](https://github.com/cocotb/cocotb)
- [pyvpi](https://github.com/antiface/pyvpi)
- [Cocotb-test](https://pypi.org/project/cocotb-test/): Test-driven and automation extension for Cocotb.

### Mixed-Signal/Analog Circuit Simulation

- [PySpice](https://pypi.org/project/PySpice/)
- [SKiDL](https://github.com/xesscorp/skidl)
- [PyAMS](https://github.com/d-fathi/PyAMS): Mixed-signal modeling and simulation framework in Python.
- [pyopus](https://github.com/xen0n/pyopus)

### AI EDA
- [ChatEDA](https://github.com/wuhy68/ChatEDAv1): LLM-based EDA agent
- [SNS](https://github.com/Entropy-xcy/sns): Deep learning-based synthesis tool for AI-driven hardware synthesis tasks.
- [Developing synthesis flows without human knowledge](https://github.com/ycunxi/FLowGen-CNNs-DAC18): RL-based automatic synthesis flow generation tool
- [AutoDMP: Automated DREAMPlace-based Macro Placement](https://github.com/NVlabs/AutoDMP)
- [DeePEB: A Neural Partial Differential Equation Solver for Post Exposure Baking Simulation in Lithography](https://github.com/Brilight/DeePEB)

### Other Related/Supporting Tools

- [hdlparse](https://github.com/kevinpt/hdlparse)
- [pyvcd](https://github.com/SanDisk-Open-Source/pyvcd): Simulation waveform/data processing tool
- [pyDigitalWaveTools](https://pypi.org/project/pyDigitalWaveTools/): Tools for handling VCD, FSDB, and other digital simulation waveform files in Python.
- [pyverilator](https://github.com/csail-csg/pyverilator): Python interface for interacting with Verilator and automated testing.
- [CircuitNet](https://github.com/huanzhang12/CircuitNet): Open-source EDA ML research dataset covering layout, synthesis, timing, etc., suitable for algorithm training and evaluation.

---

## Resources & Articles

- [PyMTL in Computer Architecture Teaching - Zhihu](https://zhuanlan.zhihu.com/p/286184451)
- [Awesome HDL](https://github.com/drom/awesome-hdl) - Comprehensive HDL resources (multi-language)
- [40+ Open Source Chip Projects Recommendation - Aijishu](https://aijishu.com/a/1060000000360021)
- [Awesome Artificial Intelligence for Electronic Design Automation](https://github.com/Thinklab-SJTU/awesome-ai4eda)
- [LLM4EDA: Emerging Progress in Large Language Models for Electronic Design Automation](https://github.com/Thinklab-SJTU/Awesome-LLM4EDA)
- [thu-nics: Awesome AI for EDA](https://github.com/thu-nics/awesome_ai4eda)
- [ai4eda: Awesome AI for EDA](https://ai4eda.github.io/)

---

## Contribution

1. You are welcome to recommend new projects, supplement documentation, or correct errors via Issue or PR!
2. See `CONTRIBUTING.md` for the recommended format. Please indicate the tool name, description, project address, and applicable scenarios.
3. Contributions of English/Chinese documentation, sample code, and real-world cases are welcome!

---

## License

Content of this project follows the [MIT License](./LICENSE).

---

## Contact & Communication

- For questions, suggestions, or collaboration, please leave a message via Issue or Discussions.
- Please follow, Star, or Fork this project to support the Python + chip simulation ecosystem!

---

## Acknowledgements

This project was inspired by Copilot, thanks for its intelligent assistance and inspiration.
