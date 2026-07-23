<div align="center">

  <br />
  <img src="logo-om.png" alt="OneMira Logo" width="340" />
  <br />
  <br />

  <h3>Bring Intelligence Into the Real World</h3>

  <p>
    <a href="https://github.com/onemira-space"><img src="https://img.shields.io/badge/Organization-OneMira-000000?style=for-the-badge&logo=github&logoColor=white" alt="Organization" /></a>
    <a href="https://onemira.com"><img src="https://img.shields.io/badge/Website-onemira.com-0052CC?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Website" /></a>
    <a href="#core-engineering-pillars"><img src="https://img.shields.io/badge/Focus-Embodied_AI_%26_Edge_Robotics-008080?style=for-the-badge" alt="Focus" /></a>
    <a href="https://onemira.com"><img src="https://img.shields.io/badge/Location-China-181717?style=for-the-badge" alt="Location" /></a>
  </p>

  <br />

</div>

## Overview

OneMira is dedicated to bridging autonomous AI systems with physical human environments. We research, build, and deploy embodied robotics, edge AI inference runtimes, native ambient applications, and spatial web experiences.

---

## Core Engineering Pillars

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>Embodied AI & Robotics</h3>
      <p>Physical hardware integration, kinematics, and spatial perception systems.</p>
      <ul>
        <li><strong><a href="https://github.com/onemira-space/miralamp">miralamp</a></strong>: Real-time interactive smart desk lamp with perception, intention, and security boundaries.</li>
        <li><strong><a href="https://github.com/onemira-space/lamp-kinematics">lamp-kinematics</a></strong>: 5-DOF motion generation and inverse kinematics algorithms.</li>
        <li><strong><a href="https://github.com/onemira-space/vla-robot-pi5">vla-robot-pi5</a></strong>: Desktop embodied intelligent manipulator arm.</li>
        <li><strong><a href="https://github.com/onemira-space/matter-controller">matter-controller</a></strong>: Local Matter network IoT device controller.</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h3>Edge Intelligence & LLM</h3>
      <p>High-efficiency LLM inference runtimes optimized for embedded NPU accelerators.</p>
      <ul>
        <li><strong><a href="https://github.com/onemira-space/mira-llm">mira-llm</a></strong>: Deeply optimized LLM runtime for Rockchip RK3588 and RK3576 platforms.</li>
        <li><strong><a href="https://github.com/onemira-space/onnx_to_rknn">onnx_to_rknn</a></strong>: Containerized toolchain for ONNX to RKNN model exporting.</li>
        <li><strong><a href="https://github.com/onemira-space/llm-go">llm-go</a></strong>: High-performance Go client for cloud and local model routing.</li>
        <li><strong><a href="https://github.com/onemira-space/llm-python">llm-python</a></strong>: Python inference client integrated with Kokoro-TTS speech synthesis.</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>Desktop Applications & UX</h3>
      <p>Native ambient user interfaces designed for continuous AI interaction.</p>
      <ul>
        <li><strong><a href="https://github.com/onemira-space/miramem-mac">miramem-mac</a></strong>: Native macOS client application.</li>
        <li><strong><a href="https://github.com/onemira-space/ai-run-bar">ai-run-bar</a></strong>: Ambient agent status bar for power AI users.</li>
        <li><strong><a href="https://github.com/onemira-space/onemira-updates">onemira-updates</a></strong>: Desktop application distribution center and Sparkle appcast feed.</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h3>Web, Storefront & 3D</h3>
      <p>Modern e-commerce infrastructure, web spatial rendering, and product portals.</p>
      <ul>
        <li><strong><a href="https://github.com/onemira-space/shopify-hydrogen">shopify-hydrogen</a></strong>: OneMira official storefront built with Shopify Hydrogen framework.</li>
        <li><strong><a href="https://github.com/onemira-space/onemira-threejs">onemira-threejs</a></strong>: Interactive 3D product visualizations and web graphics.</li>
        <li><strong><a href="https://github.com/onemira-space/onemira-website">onemira-website</a></strong>: Corporate web portal and documentation engine.</li>
      </ul>
    </td>
  </tr>
</table>

---

## Technical Architecture

```
[ Multimodal Sensors / Cameras ] ---> [ Edge RK3588/RK3576 NPU (mira-llm) ]
                                                    |
                                                    v
[ Desktop Arm / 5-DOF Lamp ]  <--- [ Kinematics & Control (lamp-kinematics) ]
                                                    |
                                                    v
[ Ambient Desktop Bar ]      <--- [ Native App & Memory (miramem-mac) ]
```

---

## Contact & Information

- **Website**: [onemira.com](https://onemira.com)
- **Contact Email**: [pengjunhao@onemira.com](mailto:pengjunhao@onemira.com)
- **Organization GitHub**: [github.com/onemira-space](https://github.com/onemira-space)
