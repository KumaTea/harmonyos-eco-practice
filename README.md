# HarmonyOS Eco Practice

华为鸿蒙生态替代最佳实践

Best Practice for Replacement of the Ecosystem of Huawei HarmonyOS NEXT

---

华为鸿蒙操作系统 (此处指 [HarmonyOS NEXT](https://en.wikipedia.org/wiki/HarmonyOS_5), 俗称「[纯血鸿蒙](https://zh.wikipedia.org/wiki/%E9%B8%BF%E8%92%99%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F5)」) 是使用鸿蒙微内核，去除Linux内核，仅支持鸿蒙系统的原生应用程序的操作系统。

由于该系统发布时间较短，生态系统较不完善，尤其缺乏海外企业开发的应用。虽然提供了安卓容器化环境[卓易通](https://www.droitong.com/)，但使用体验上仍一般。

本项目通过本人的使用经验，提供替代常用使用场景的最佳实践。针对的使用场景主要为桌面，对应的设备包括鸿蒙电脑 (MateBook) 和平板 (MatePad) 的多窗口模式。部分替代方案要求您有一台服务器。

---

## 远程连接 Remote Connection

* 目标 Targets
  * Microsoft Remote Desktop
  * Termius
* **替代 Replacements**
  * **[Apache Guacamole](https://guacamole.apache.org)**
    * 类型：Web
    * 开源：是
    * 免费：是
* 评价 Reviews
  * 效果：完全替代
  * 操作难度：中
* 参考 References
  * https://krdesigns.com/articles/how-to-install-guacamole-using-docker-step-by-step
  * https://guacamole.apache.org/doc/gug/guacamole-docker.html
  * https://windgate.net/connect-your-lab-remotely-with-guacamole-rdp-to-windows-linux/
