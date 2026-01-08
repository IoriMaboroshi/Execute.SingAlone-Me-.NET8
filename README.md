# Execute.SingAlone(Me) - .NET 8 Remastered

![.NET 8](https://img.shields.io/badge/.NET-8.0-purple) ![Status](https://img.shields.io/badge/Status-Fixed-green) ![Music](https://img.shields.io/badge/Music-Mili-blue)

[中文] | [English](#english)

---

## 🇨🇳 中文说明

这是一个基于 C# 控制台的字符动画程序，用于演绎 **Mili** 的歌曲 **《World.Execute(me);》**。

本项目是 [KurtVelasco/Execute.SingAlone-Me-](https://github.com/KurtVelasco/Execute.SingAlone-Me-) 的 Fork 版本。原项目基于较旧的 .NET Framework，在现代环境中运行较为困难且存在严重的音画不同步问题。

**本项目已完全重构并修复，现在的体验丝般顺滑！** ✨

### 🛠️ 修改与优化 (Changes)

- ✅ **升级至 .NET 8.0**：抛弃了老旧的 .NET Framework 4.7.2，现在你是跨平台的了！
- ✅ **修复音画同步**：重新校准了 `Thread.Sleep` 计时逻辑，解决了原版中歌词播放速度远快于音乐的问题。
- ✅ **依赖修复**：修复了 `NAudio` 和 `AssemblyInfo` 导致的编译错误。
- ✅ **代码优化**：移除了不必要的旧版配置，现在的项目结构更加整洁。

### 🚀 如何运行 (How to Run)

#### 1. 环境准备
确保你的电脑上安装了 **.NET 8.0 SDK**。
```bash
dotnet --version
# 如果显示 8.0.xxx 则表示已安装
```

#### 2. 克隆项目
```bash
git clone https://github.com/IoriMaboroshi/Execute.SingAlone-Me-.NET8.git
cd Execute.SingAlone-Me-.Net8
```

#### 3. 🎵 关键步骤：添加音乐文件
由于版权原因，仓库内不包含音乐文件。**你必须手动添加音乐才能运行！**

1. 下载 **Mili - World.Execute(me);** 的 MP3 文件。
2. 将文件重命名为 **`ghost.mp3`** (必须是这个名字，全小写)。
3. 将文件放入项目根目录（与 `.csproj` 文件同级）。

#### 4. 启动！
在终端中运行：
```bash
dotnet run
```

#### 5. 输入口令
当控制台加载完毕出现 `>` 提示符时，输入以下指令并回车：
```text
run world.exec
```
（尽情享受演出吧！）

---

<a name="english"></a>
## 🇺🇸 English

This is a C# Console application that renders lyrics and ASCII animations for the song **"World.Execute(me);"** by **Mili**.

This is a forked version of [KurtVelasco/Execute.SingAlone-Me-](https://github.com/KurtVelasco/Execute.SingAlone-Me-). The original project was built on the older .NET Framework, which made it difficult to run on modern systems and suffered from severe audio-visual desynchronization.

**This version has been fully remastered and fixed for a smooth experience!** ✨

### 🛠️ What's New

- ✅ **Upgraded to .NET 8.0**: Migrated from the legacy .NET Framework 4.7.2. It is now cross-platform friendly.
- ✅ **Fixed Sync Issues**: Recalibrated the `Thread.Sleep` logic. Lyrics and animations now perfectly match the music tempo (fixed the issue where text ran too fast).
- ✅ **Dependency Fixes**: Resolved build errors related to `NAudio` and `AssemblyInfo`.
- ✅ **Code Cleanup**: Removed unnecessary legacy configurations for a cleaner project structure.

### 🚀 How to Run

#### 1. Prerequisites
Ensure you have the **.NET 8.0 SDK** installed.
```bash
dotnet --version
# Should output 8.0.xxx
```

#### 2. Clone the Repository
```bash
git clone https://github.com/IoriMaboroshi/Execute.SingAlone-Me-.NET8.git
cd Execute.SingAlone-Me-.Net8
```

#### 3. 🎵 Crucial Step: Add Music File
Due to copyright reasons, the music file is NOT included in the repo. **You must add it manually!**

1. Download the MP3 file for **Mili - World.Execute(me);**.
2. Rename the file to **`ghost.mp3`** (Exact name, lowercase).
3. Place the file in the project root folder (same level as the `.csproj` file).

#### 4. Start
Run the following command in your terminal:
```bash
dotnet run
```

#### 5. Execution Command
When the console finishes loading and shows the `>` prompt, type the following command and hit Enter:
```text
run world.exec
```
(Enjoy the show!)

---

### Credits
* **Music:** [Mili - World.Execute(me);](https://projectmili.com/)
* **Original Code:** [KurtVelasco](https://github.com/KurtVelasco)
* **Remastered by:** [IoriMaboroshi](https://www.iorimaboroshi.asia)
