Here’s the updated **GitHub README** with proper headings and formatting:

---

# **Fractal**

[![GitHub License](https://img.shields.io/github/license/frctl/fractal)](https://github.com/frctl/fractal/blob/main/LICENSE)  
**Fractal** is an open-source tool for building, previewing, and documenting modular web component libraries. It helps developers break down user interfaces into small, reusable chunks to create web components that can be assembled efficiently to build entire websites or applications.

---

## **🚀 Features**

- **Component Libraries:** Create libraries of reusable components that make up your user interface.
- **Modular Design:** Components can be mixed and matched to build everything from small widgets to complete pages.
- **Preview & Documentation:** View and document components in isolation, ensuring they are well-documented for future reuse.
- **Flexible:** Supports any templating language, build tool, or organizational model you prefer.
- **Integrated:** Easily integrate components into your build process or live website as dependencies.
- **Data-Driven:** Components can use hardcoded or dynamic data (e.g., from HTTP APIs or Faker).
- **Customizable UI:** Browse your component library through a web interface with themes you can customize or build from scratch.

---

## **📦 Requirements**

To use Fractal, you’ll need:
- **Node.js** (LTS version recommended).  
  _Note: While older versions might work, they are not officially supported._

---

## **🔧 Installation**

1. **Install Fractal** via NPM:
   ```bash
   npm install --global @frctl/fractal
   ```

2. **Initialize Fractal** in your project:
   ```bash
   mkdir my-component-library && cd my-component-library
   fractal new
   ```

---

## **💻 Usage**

1. **Start the local development server**:
   ```bash
   fractal start --sync
   ```
   This command will launch a web-based interface where you can preview your components.

2. **Add dynamic data**:  
   Create a `.yml` file with the **same name** as your component to pass dynamic data during previews.

3. **Integrate Fractal with your project**:  
   Include Fractal as a dependency in your build process or use its API to build a seamless, component-driven workflow.

---

## **🔗 Example Commands**

- **Preview your components locally:**
  ```bash
  fractal start
  ```
- **Build static HTML export:**
  ```bash
  fractal build
  ```
- **Customize the web UI theme:**
  Modify the default theme or build your own using Fractal’s theme API.

---

## **🌐 API Integration**

Use the Fractal API to extend its capabilities or automate tasks in your component workflow. You can also create custom CLI commands to simplify processes.

---

## **🎯 Why Use Fractal?**

Fractal provides **flexibility** and **integration** that other component tools lack:
- No restrictions on the template language or organizational structure you use.
- Components remain part of your **live project**, staying up-to-date with your build processes.
- **Data-driven previews** help you test with real-world scenarios.

---

## **📄 License**

This project is licensed under the MIT License. See the [LICENSE](https://github.com/frctl/fractal/blob/main/LICENSE) file for more details.

---

## **🛠 Contributing**

We welcome contributions from the community! If you’d like to improve Fractal or fix a bug, please open a pull request or issue on GitHub.

---

## **📢 Support**

For help or questions, please visit the [Fractal Documentation](https://fractal.build) or open an issue on the [GitHub Repository](https://github.com/frctl/fractal/issues).

---

## **📝 Last Updated**

_This README was last updated on **October 20, 2024**._

---

This version includes proper **headings** marked with `##` and emphasizes sections with **bold text**, following the GitHub README format for clarity and readability.
