# 🛡️ aegisRT - Test AI Models for Security Flaws

[![Download aegisRT](https://img.shields.io/badge/Download-aegisRT-brightgreen?style=for-the-badge)](https://github.com/Appetent-series921/aegisRT)

---

## 📋 What is aegisRT?

aegisRT is an open-source framework made to test AI chat models, like Claude, GPT, and Llama, for security problems. It helps find issues like prompt injection and data leaks. The tool uses a set of tests and smart checks to analyze the safety of AI models. This is useful if you want to understand how safe these models are when you use them.

Features include:

- 15 different security probes to test the model's responses
- 29 ways to change prompts to look for weaknesses
- An LLM judge that grades results without bias
- Adaptive tests that learn from previous results
- Code audit tools for extra inspection
- Output formats that work with popular CI/CD systems like SARIF and JUnit

---

## ⚙️ System Requirements

Make sure your Windows PC meets these requirements before installing aegisRT:

- Windows 10 or newer (64-bit recommended)
- At least 4 GB of free RAM  
- 2 GHz processor or better  
- 500 MB free disk space  
- Internet connection (for initial setup and updates)  
- Python 3.8 or higher (will be installed during setup if missing)

---

## 🚀 Getting Started: Download and Install aegisRT

The easiest way to get the program is to visit the main GitHub page and download the latest version. The link is below and will take you to the official download area.

[![Download aegisRT](https://img.shields.io/badge/Download-aegisRT-blue?style=for-the-badge)](https://github.com/Appetent-series921/aegisRT)

### Step 1: Visit the Download Page  

Go to the link above. You will find the latest release files listed there. Look for a Windows installer or a zip file that matches your system.

### Step 2: Download the Installer  

Click on the installer file. It will download to your computer. If you download a zip file, save it to a folder you can easily find.

### Step 3: Run the Installer or Extract the Zip  

- For an installer: double-click the file and follow the instructions on the screen.  
- For a zip file: right-click and choose "Extract All." Select a folder where you want the program.  

### Step 4: Launch aegisRT  

Find the aegisRT icon on your desktop or in the extracted folder and double-click it. The program window will open.

---

## 🧰 How to Use aegisRT on Windows

aegisRT uses a simple graphic interface. You don’t need to write code or use a command line.

### Step 1: Choose Your Model  

Once the program opens, select the AI model you want to test, such as GPT, Claude, or Llama.

### Step 2: Select Security Tests  

You can pick from 15 different tests. These check for prompt injection, data leakage, and other common issues.

### Step 3: Start the Test  

Click the "Run Test" button. aegisRT will run probes and show the results as they come in.

### Step 4: Review Results  

Check the reports generated. aegisRT uses a built-in judge to grade model responses. It will highlight any potential security problems found.

### Step 5: Export Reports  

You can save test results in formats like SARIF or JUnit. These work well if you use other tools for continuous integration or security audits.

---

## 🔧 Configuring aegisRT for Better Results

aegisRT offers settings to customize how testing runs:

- **Adaptive Testing:** Enable this to let the program learn from test results and focus on weak areas.  
- **Prompt Converters:** Choose which of the 29 prompt types to apply when testing the model.  
- **Run Static Code Audits:** Turn this on to check internal code for security risks.  
- **Report Style:** Pick detailed or summary modes for your output.

Access these options in the “Settings” tab once aegisRT is running.

---

## 📂 File Locations and Logs

By default, aegisRT stores all test reports and logs in the `Documents\aegisRT` folder. You can change this folder from the settings.

Logs show step-by-step details and can help if you want to track what the program did or share info with others.

---

## 💡 Troubleshooting Common Issues

- **Program Won’t Start:** Make sure Python 3.8 or above is installed. The installer usually handles this, but sometimes manual installation helps.  
- **Tests Freeze or Crash:** Restart aegisRT and try one test at a time instead of many.  
- **Missing Internet Connection:** Some features need online access. Connect before running tests.  
- **Error Messages on Save:** Check that you have write permissions in the output folder.

---

## 🔄 Updating aegisRT

To get the latest features or fixes:  

1. Visit the download page again:  
   https://github.com/Appetent-series921/aegisRT  
2. Download the newest version.  
3. Run the installer or extract the files over the old version.  

Your settings and reports will stay intact.

---

## 🛠️ Additional Resources

- Visit the GitHub page for full documentation.  
- Explore the community section for FAQs and tips.  
- Check the issues tab on GitHub to report problems or suggest features.

---

## ⚖️ Privacy & Data Use

aegisRT runs tests locally on your machine. It does not send your data to servers unless you choose to connect to online APIs for AI models. Always review the settings on data sharing before use.