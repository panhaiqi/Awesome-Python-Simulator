<!--
Keywords: EDA, Digital Circuit, Logic Simulator, Verilog, Python, Open Source, Chip Design, Truth Table, Teaching, Education, AI EDA, 数字电路, 仿真, 开源, 芯片设计, 教学, 真值表, 人工智能, Python EDA, 电路仿真, 电子设计自动化
-->
<!-- Language Switcher / 语言切换 -->
<p align="left">
  <a href="#en">English</a> | <a href="#cn">中文</a>
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

> 🚀 This is a curated, continuously-updated collection of open-source Python projects for chip modeling, simulation, verification, and testing. The goal is to help researchers, developers, and students quickly find and select the right tools to accelerate their work in hardware design and education.

---

**Version: v0.1 (Actively maintained and improved)**

---

## Project Motivation

Python's role in chip design, verification, and simulation is expanding rapidly. However, the available tools and resources are scattered and lack a unified, systematized directory. This project brings together high-quality Python-based EDA and simulation tools in one place, making it easier for engineers, educators, and hobbyists to discover, compare, and use these resources.

---

## Tool Categories

### Hardware Modeling & Description Languages (HDL/DSL)

- [PyMTL](https://github.com/cornell-brg/pymtl): An open-source Python framework for multi-level hardware modeling.
- [PyRTL](https://github.com/UCSBarchlab/PyRTL): A teaching-oriented Python platform for RTL circuit design and simulation, ideal for digital logic courses and prototyping.
- [MyHDL](https://github.com/myhdl/myhdl): Converts Python code to synthesizable HDL, enabling hardware design directly in Python.
- [Migen](https://github.com/m-labs/migen) / [Nmigen](https://github.com/nmigen/nmigen): Python toolkits for building complex digital hardware designs.
- [polyphony](https://pypi.org/project/polyphony/): Translates Python code to synthesizable HDL for hardware synthesis.
- [hdl21](https://pypi.org/project/hdl21/): Domain-specific language in Python for analog and digital hardware design.

### HDL Parsing & Analysis Tools

- [Pyverilog](https://github.com/PyHDI/Pyverilog): A Python library for parsing, analyzing, and transforming Verilog code, suitable for EDA research and automation.
- [pyVHDLParser](https://pypi.org/project/pyVHDLParser/): Python parser for VHDL, supporting code analysis and AST generation.

### Digital Circuit/Logic Gate Simulators

- [BinPy](https://github.com/BinPy/BinPy): Models and simulates logic gates and combinational circuits in Python for education and prototyping.
- [DigSim](https://pypi.org/project/digsim-logic-simulator/): A Python-based digital logic simulator supporting gate-level design and waveform analysis.
- [Logisim-evolution](https://github.com/reds-heig/logisim-evolution): Java-based digital circuit tool with a Python scripting interface for experiments and automation.
- [pyFDA](https://pypi.org/project/pyfda/): A Python tool for digital filter design and analysis.

### EDA Tool Interfaces & Automation

- [Edalize](https://pypi.org/project/edalize/): Provides a unified interface for managing multiple EDA tools (Icarus, Yosys, ModelSim, Verilator, Vivado, etc.), supporting project generation and batch/GUI operation.
- [FuseSoC](https://pypi.org/project/fusesoc/): Python-based SoC build and integration tool with support for various simulators and backends.

### Co-Simulation & Verification

- [cocotb](https://github.com/cocotb/cocotb): Coroutine-based cosimulation library for writing testbenches in Python.
- [pyvpi](https://github.com/antiface/pyvpi): Python interface for VPI, enabling integration with Verilog simulators.
- [Cocotb-test](https://pypi.org/project/cocotb-test/): Utilities for test automation and organization with cocotb.

### Mixed-Signal / Analog Circuit Simulation

- [PySpice](https://pypi.org/project/PySpice/): A Python interface to SPICE simulators for analog and mixed-signal circuit simulation.
- [SKiDL](https://github.com/xesscorp/skidl): Python library for programmatically generating electronic circuit schematics.
- [PyAMS](https://github.com/d-fathi/PyAMS): Framework for mixed-signal modeling and simulation in Python.
- [pyopus](https://github.com/xen0n/pyopus): Tools for analog and mixed-signal circuit design and analysis.

### AI for EDA

- [ChatEDA](https://github.com/wuhy68/ChatEDAv1): LLM-based EDA assistant agent.
- [SNS](https://github.com/Entropy-xcy/sns): Deep learning-based hardware synthesis tool, exploring AI-driven EDA flows.
- [FLowGen-CNNs-DAC18](https://github.com/ycunxi/FLowGen-CNNs-DAC18): Reinforcement learning for automatic synthesis flow generation.
- [AutoDMP](https://github.com/NVlabs/AutoDMP): Automated macro placement using DREAMPlace and machine learning.
- [DeePEB](https://github.com/Brilight/DeePEB): Neural PDE solver for lithography post-exposure baking simulation.

### Other Related / Supporting Tools

- [hdlparse](https://github.com/kevinpt/hdlparse): Tools for parsing HDL files.
- [pyvcd](https://github.com/SanDisk-Open-Source/pyvcd): Tools for processing simulation waveforms and VCD data in Python.
- [pyDigitalWaveTools](https://pypi.org/project/pyDigitalWaveTools/): Python utilities for handling VCD, FSDB, and similar waveform files.
- [pyverilator](https://github.com/csail-csg/pyverilator): Python interface for automated Verilator simulation and testing.
- [CircuitNet](https://github.com/huanzhang12/CircuitNet): Open EDA machine learning datasets for layout, synthesis, timing, and algorithm evaluation.

---

## Resources & Articles

- [PyMTL in Computer Architecture Teaching - Zhihu](https://zhuanlan.zhihu.com/p/286184451)
- [Awesome HDL](https://github.com/drom/awesome-hdl) - Comprehensive multi-language HDL resources
- [40+ Open Source Chip Projects Recommendation - Aijishu](https://aijishu.com/a/1060000000360021)
- [Awesome Artificial Intelligence for Electronic Design Automation](https://github.com/Thinklab-SJTU/awesome-ai4eda)
- [LLM4EDA: Progress in Large Language Models for EDA](https://github.com/Thinklab-SJTU/Awesome-LLM4EDA)
- [thu-nics: Awesome AI for EDA](https://github.com/thu-nics/awesome_ai4eda)
- [ai4eda: Awesome AI for EDA](https://ai4eda.github.io/)

---

## Contributing

1. Contributions are welcome! Recommend new projects, add documentation, or report errors via Issues or Pull Requests.
2. Please follow the format found in `CONTRIBUTING.md`—include tool name, description, project link, and applicable scenarios.
3. Contributions of English/Chinese docs, code samples, and real-world use cases are especially encouraged!

---

## License

This project is licensed under the [MIT License](./LICENSE).

---

## Contact & Community

- For questions, suggestions, or collaboration, please use Issues or Discussions.
- If you find this project helpful, please star, fork, or share it to support the Python hardware simulation ecosystem!

---

## Acknowledgements

This project was inspired by Copilot. Thanks to its intelligent assistance and support.
