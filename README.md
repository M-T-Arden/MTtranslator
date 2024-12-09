# MTtranslator

你好！我是 **M.T. Arden**，本翻译工具的开发者🤓。这个软件在 **ChatGPT** 和 **Claude** 的帮助下完成，使用了免费的翻译模型 **Helsinki-NLP/opus-mt-en-zh**。感谢所有为此项目提供帮助的人！

---
## **功能特点**

1. **仅支持英文到简体中文翻译**
  
  - 该应用专为实时字幕翻译设计，支持从英文到简体中文的转换。
  - 目前需要系统语言设置为英文，待进一步优化。
2. **离线操作**
  
  - 翻译完全离线进行，保证隐私安全。但翻译质量仅供参考🫡。去学英语比这靠谱。
3. **仅限 Windows 系统**
  
  - 本软件依赖 **Windows 的实时字幕功能 (Live Captions)**，因此只能在具备此功能的 Windows 系统上运行。

---

## **快速上手**

### **系统要求**

- **操作系统：** Windows（需启用实时字幕功能）。
- **语言：** Python 3.11，依赖库见requirements。
- **内存：** 至少 2GB 可用内存。
- **存储空间：** 软件及模型文件需约 1GB 空闲存储空间。

---

### **使用小贴士**

1. **在启动本程序前，确保您有“实时字幕”功能：**
  
  - 如果此前已经打开了实时字幕用于其他用途，请重启实时字幕，否则本软件会读取之前的字幕内容。
2. **操作方法：**
  
  - 绿色按钮：**开始翻译**
  - 橙色按钮：**暂停翻译**
  - 红色按钮：**停止翻译**
3. 翻译内容会显示在程序窗口中，原文会自动保存供后面对照参考，每次在开始运行后会弹出窗口选择保存位置到自定义文件夹。
  
4. 因为实时字幕的断句有时候会出问题，翻译的质量也会受到影响，可能会一整段一起翻译或者仅有几个字词。
   本身使用的是离线大模型进行翻译，相当于是机翻。**翻译仅供参考🥺**
  

---

## **安装和运行**

1. **下载程序**
  
  - 在 [Releases](https://github.com/M-T-Arden/MTtranslator/releases) 页面获取最新版本的 `MTtranslator.exe` 文件。
2. **运行程序**
  
  - 双击 `MTtranslator.exe` 即可启动。

---

## **鸣谢**

本项目使用了以下工具和资源：

- [Helsinki-NLP/opus-mt-en-zh](https://huggingface.co/Helsinki-NLP/opus-mt-en-zh) 提供翻译支持。
- **PyQt** 用于构建图形界面。
- **ChatGPT** 和 **Claude** 在调试和优化过程中提供了重要帮助。
---
## 许可证
本软件个人免费使用，根据专有许可证分发。请参阅 [LICENSE_CN](./LICENSE_CN) 文件了解详细信息。

感谢使用 MTtranslator！ 
如遇到问题或有建议，请随时联系我。😊

---

# MTtranslator
Hi there! This is **M.T. Arden**, the developer of this translator application. I created this tool with the help of **ChatGPT** and **Claude**, and it uses the free translation model **Helsinki-NLP/opus-mt-en-zh**. Many thanks to everyone who contributed to its development!

---

## **Features**

1. **English to Chinese (Simplified) Translation Only**
  
  - This application supports real-time subtitle translation from English to Chinese.
2. **Offline Operation**
  
  - The translation process is fully offline, ensuring privacy. However, the translation quality is not perfect and should only be used as a reference. Always strive to improve your language skills!
3. **Subtitle Storage**
  
  - Captions are saved in the `caption` folder for later reference.
4. **Windows-Only Compatibility**
  
  - This application relies on **Windows Live Captions**, which means it can only be used on Windows systems with this feature enabled.

---

## **Getting Started**

### **System Requirements**

- **Operating System:** Windows 10/11 with Live Captions enabled.
- **Memory:** At least 2GB available RAM.
- **Storage:** Approximately 1GB of free space for the application and model files.

---

### **Usage Tips**

1. Restart or open "Live Captions" in Windows **before** launching the application.
  
  - If Live Captions is active before you use this app, you better restart Live Captions because the application will capture previous captions (if any).
2. To begin translating:
  
  - Use the green button to **start translation**, the orange button to **pause**, and the red button to **stop**.
3. Translations will be displayed in the application window and stored in the `caption` folder for later review.
  
4. Live captions are not so accurate, so does this application. I choose to translate a sentence to improve the quality so sometimes it would be slow because the whole paragraph will be translated together.
  

---

## **Installation and Running**

1. **Download the Application**
  
  - Get the latest version of `MTtranslator.exe` from the [Releases](./releases) section.
2. **Run the Application**
  
  - Double-click `MTtranslator.exe` to start.

---

## **Acknowledgments**

This project utilizes:

- [Helsinki-NLP/opus-mt-en-zh](https://huggingface.co/Helsinki-NLP/opus-mt-en-zh) for translation.
- **PyQt** for creating the graphical interface.
- Guidance and debugging support from **ChatGPT** and **Claude**.

---
## License
This software is free for personal and educational use under a proprietary license. Please see the [LICENSE](./LICENSE) file for details. 

Thank you for trying MTtranslator!  
If you encounter any issues or have suggestions, feel free to contact me. 😊
