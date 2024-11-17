# Preview - https://www.youtube.com/watch?v=o07CG7pYjbM

# FiveM Vehicle Merger Tool

🚗 **Simplify the process of merging vehicle resources for your FiveM server!** 🚗

This tool automates the task of combining multiple vehicle resource folders into a single, organized package, making it easier to manage and integrate custom vehicles into your server.

---

## 🎯 **Features**
- **Automatic Folder Merging**: Combines `meta` files and `stream` files from multiple vehicle folders into a structured format.
- **Ready-to-Use `fxmanifest.lua`**: Automatically generates a manifest file for immediate use in your FiveM server.
- **Vehicle Spawn Codes**: Creates a `spawncodes.txt` file listing all vehicle spawn codes (based on folder names in the `data` directory).
- **Folder Organization**: Neatly organizes your `data` and `stream` folders.
- **Auto Folder Opening**: Opens the merged output folder after processing.
- **User-Friendly Interface**: A clean GUI to simplify folder selection and merging.

---

## 🖥️ **How to Use**

1. **Download and Run**:
   - Clone this repository or download the `.exe` from [Releases](#).
   - Run the executable.

2. **Select Folders**:
   - Choose your input folder (where vehicle resources are located).
   - Choose your output folder (or use the same folder as the input).

3. **Merge Vehicles**:
   - Click "Merge Vehicles" to start the process.
   - The tool will merge the files, generate the required files, and open the output folder automatically.

4. **Deploy**:
   - Place the `mergedvehicles` folder into your FiveM server's `resources` directory.
   - Add `start mergedvehicles` to your `server.cfg`.

---

## 🛠️ **Requirements**

no additional setup is needed!

---

## 📁 **Output Structure**

After merging, the `mergedvehicles` folder will look like this:

```
mergedvehicles/
├── fxmanifest.lua
├── spawncodes.txt
├── data/
│   ├── vehicle1/
│   │   ├── handling.meta
│   │   ├── vehicles.meta
│   │   └── carvariations.meta
│   ├── vehicle2/
│       ├── handling.meta
│       ├── vehicles.meta
│       └── carvariations.meta
├── stream/
    ├── vehicle1/
    │   ├── vehicle1.yft
    │   ├── vehicle1.ytd
    │   └── vehicle1_hi.yft
    ├── vehicle2/
        ├── vehicle2.yft
        ├── vehicle2.ytd
        └── vehicle2_hi.yft
```

---

## 🔧 **Customization**

Feel free to customize the script for additional functionality. You can modify:
- `fxmanifest.lua` content.
- Folder naming conventions.
- Additional file generation.

---

## 🚀 **Contribute**

We welcome contributions! If you find a bug or have a feature request, feel free to:
- Submit an issue.
- Fork the repo and create a pull request.

---

## 🏆 **Credits**

- **Author**: nullvalue
- **Description**: Built to simplify vehicle merging for FiveM servers.

---

## 📜 **License**

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

### 💬 **Questions or Feedback?**

Feel free to open an issue or contact us through GitHub. We’d love to hear your thoughts! 🚗💨
Discord - https://discord.gg/khN9aqTnY6
