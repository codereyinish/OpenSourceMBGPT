<p align="center">
  <img src="https://github.com/codereyinish/StoreRoom2/blob/main/Images/—Pngtree—letter%20m%20logo_6074170.png" width="160" alt="project-logo">
</p>
<p align="center">
    <h1 align="center">MBGPT2.os</h1>
</p>
<p align="center">
    <em>Enhancing Interactions, Tailoring Smarter + Cheaper AI Responses</em>
</p>
<p align="center">
	<img src="https://img.shields.io/github/license/codereyinish/OpenSourceMBGPT?style=flat&logo=opensourceinitiative&logoColor=white&color=black" alt="license">
	<img src="https://img.shields.io/github/last-commit/codereyinish/OpenSourceMBGPT?style=flat&logo=git&logoColor=white&color=black" alt="last-commit">
	<img src="https://img.shields.io/github/languages/top/codereyinish/OpenSourceMBGPT?style=flat&color=black" alt="repo-top-language">
	<img src="https://img.shields.io/github/languages/count/codereyinish/OpenSourceMBGPT?style=flat&color=black" alt="repo-language-count">
<p align="center">
		<em>Developed with the software and tools below.</em>
</p>
<p align="center">
	<img src="https://img.shields.io/badge/Jupyter-F37626.svg?style=flat&logo=Jupyter&logoColor=white" alt="Jupyter">
	<img src="https://img.shields.io/badge/YAML-CB171E.svg?style=flat&logo=YAML&logoColor=white" alt="YAML">
	<img src="https://img.shields.io/badge/conda-44A833.svg?style=flat&logo=conda&logoColor=white" alt="Conda">
	<img src="https://img.shields.io/badge/pip-3775A9.svg?style=flat&logo=pypa&logoColor=white" alt="pip">
	<img src="https://img.shields.io/badge/Python-3776AB.svg?style=flat&logo=Python&logoColor=white" alt="Python">
	<img src="https://img.shields.io/badge/GNU%20Bash-4EAA25.svg?style=flat&logo=GNU-Bash&logoColor=white" alt="GNU Bash">
	<img src="https://img.shields.io/badge/GitHub%20Actions-2088FF.svg?style=flat&logo=GitHub-Actions&logoColor=white" alt="GitHub%20Actions">
	<img src="https://img.shields.io/badge/OpenAI-1.35.3-412991.svg?style=flat&logo=OpenAI&logoColor=white" alt="OpenAI">
	<br>
</p>


<br><!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary><br>

- [📍 Overview](#-overview)
- [🧩 Features](#-features)
- [🗂️ Repository Structure](#️-repository-structure)
- [📦 Modules](#-modules)
- [🚀 Getting Started](#-getting-started)
  - [⚙️ Installation](#️-installation)
  - [🤖 Usage](#-usage)
  - [🧪 Tests](#-tests)
- [🛠 Project Roadmap](#-project-roadmap)
- [🤝 Contributing](#-contributing)
- [🎗 License](#-license)
- [🔗 Acknowledgments](#-acknowledgments)
</details>
<hr>

## 📍 Overview


**Introducing MBGPT2.os: A Cost-Effective AI Commenter**

Building upon our commitment of creating a powerful AI assistant for content creators, we're excited to unveil $${\color{lightgreen}MBGPT2.os}$$ , an open source version of <a href="https://github.com/codereyinish/MBGPT" style = "color: red;">MBGPT,</a> . We planned to proceed with  the strategies we discussed earlier (link here), focusing on $${\color{red}avoiding \space costs }$$  associated with  $${\color{red}\space OpenAI \space API \space calls  }$$  to its flagship models. This goal is achieved by leveraging  $${\color{orange}\space quantized \space Bloke/Mistral \space 7B \space model}$$  locally for inference and fine-tuning. This model can later be used which can later be used to develop the new version of AI_Note_Assistant or MBGPT.



## 🧩 Features

|    |   Feature         | Description |
|----|-------------------|---------------------------------------------------------------|
| ⚙️  | **Architecture**  | The code follows a modular structure with clear separation of concerns: model initialization, fine-tuning, tokenization, prompt engineering, and inference. It implements a pipeline architecture for text generation, with distinct stages for input processing, model inference, and output decoding. |
| 🔩 | **Code Quality**  | The codebase maintains high-quality standards with clear structure, comments, and well-documented code, ensuring readability and maintainability.|
| 📄 | **Documentation** | While not extensive, the code detailed documentation within the notebooks, includes inline comments  and helpful links, explaining key steps and the purpose of certain operations.|
| 🔌 | **Integrations**  | Seamlessly integrates Hugging Face's Transformers library, PEFT for fine-tuning, and GPTQ for quantization. Utilizes CUDA for GPU acceleration, optimizing performance on compatible hardware.|
| 🧪 | **Testing**       | The project does not explicitly mention a testing framework; however, real-time interaction in the notebook allows for manual testing of different model behaviors.|
| ⚡️  | **Performance**   | The project focuses on the efficiency of text generation tasks, utilizing GPU acceleration for machine learning models in the 'QLora.ipynb' notebook to enhance speed and resource utilization. Employs GPTQ quantization and automatic device mapping for efficient resource utilization.|
| 🛡️ | **Security**      | Measures for data protection and access control are not explicitly mentioned in the details provided but more secure than accessing external api calls to proprietary models like OPENAI|
| 📦 | **Dependencies**  | Key external libraries and dependencies include : peft, transformers, optimum, auto-gptq. Requires CUDA-compatible GPU for optimal performance.|


---

## 🗂️ Repository Structure

```sh
└── OpenSourceMBGPT/
    ├── README.md
    └── mbgpt.ipynb
```

---


## 🚀 Getting Started

**System Requirements:**

 **Google Collab Notebook**

### ⚙️ Installation

<h4>From <code>source</code></h4>

> 1. Clone the OpenSourceMBGPT repository:
>
> ```console
> $ git clone https://github.com/codereyinish/OpenSourceMBGPT.git
> ```
> 2. Save it to Drive
>
>  3. Mount your Google Drive:
Run this code to mount your Google Drive:
> ```console
> $ %cd /content/drive/MyDrive/OpenSourceMBGPT
> ```
>
> 4. Change to the project directory:
> ```console
> $ cd OpenSourceMBGPT
> ```
>


### Performance Evolution 📈
Our progress continues from <a href= "https://github.com/codereyinish/MBGPT#4-fine-tune-implementation" > here </a>

Building on our success with OpenAI's fine-tuning, we've taken a significant leap forward by fine-tuning an open-source model, specifically the Mistral-7B-Instruct-v0.2-GPTQ.This transition has eliminated API costs, enhances data security through local processing, and allows for offline operation. 

#### Current Limitations 🛑
Can't spot out any  for now. More to explore maybe.


## 🤝 Contributing

Contributions are welcome! Here are several ways you can contribute:

- **[Report Issues](https://github.com/codereyinish/OpenSourceMBGPT/issues)**: Submit bugs found or log feature requests for the `OpenSourceMBGPT` project.
- **[Submit Pull Requests](https://github.com/codereyinish/OpenSourceMBGPT/blob/main/CONTRIBUTING.md)**: Review open PRs, and submit your own PRs.
- **[Join the Discussions](https://github.com/codereyinish/OpenSourceMBGPT/discussions)**: Share your insights, provide feedback, or ask questions.

<details closed>
<summary>Contributing Guidelines</summary>

1. **Fork the Repository**: Start by forking the project repository to your github account.
2. **Clone Locally**: Clone the forked repository to your local machine using a git client.
   ```sh
   git clone https://github.com/codereyinish/OpenSourceMBGPT
   ```
3. **Create a New Branch**: Always work on a new branch, giving it a descriptive name.
   ```sh
   git checkout -b new-feature-x
   ```
4. **Make Your Changes**: Develop and test your changes locally.
5. **Commit Your Changes**: Commit with a clear message describing your updates.
   ```sh
   git commit -m 'Implemented new feature x.'
   ```
6. **Push to github**: Push the changes to your forked repository.
   ```sh
   git push origin new-feature-x
   ```
7. **Submit a Pull Request**: Create a PR against the original project repository. Clearly describe the changes and their motivations.
8. **Review**: Once your PR is reviewed and approved, it will be merged into the main branch. Congratulations on your contribution!
</details>

<details closed>
<summary>Contributor Graph</summary>
<br>
<p align="center">
   <a href="https://github.com{/codereyinish/OpenSourceMBGPT/}graphs/contributors">
      <img src="https://contrib.rocks/image?repo=codereyinish/OpenSourceMBGPT">
   </a>
</p>
</details>

---

## 🎗 License

[MIT-License](LICENSE)

---

## 👏 Acknowledgments

- <a href="https://github.com/ShawhinT"  style="text-decoration: none;"> ShawinT </a>

---

Resources 📚

These are the resources I used while expermienting with all above codes: 
<br>
- <a href="https://www.youtube.com/watch?v=4RAvJt3fWoI&list=PLz-ep5RbHosU2hnz5ejezwaYpdMutMVB0&index=10"> Words fall short of praising this person, 💙</a>
- <a href="https://platform.openai.com/docs/overview"> OpenAI Documentation</a>
- <a href="https://community.openai.com/u/closure.onward.07/activity">Good Place to Find Answers</a>
- <a href="https://github.com/openai/openai-cookbook/blob/main/examples/How_to_format_inputs_to_ChatGPT_models.ipynb"> All Recipes Inside</a>
- <a href="https://github.com/eli64s/readme-ai?tab=readme-ov-file#badges">Make Readme on a fly</a>
<br>
<p align="right">
  <a href="#-overview"><b>Return</b></a>
</p>
