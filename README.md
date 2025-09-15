<p align="center">
  <h1 align="center"> To-Do List App </h1>
</p>

<p align="center">
	<em>
    <code>Task Organizer and Manager App</code>
  </em>
</p>

<p align="center">
	<img src="https://img.shields.io/github/license/djoezeke/TodoList?style=default&logo=opensourceinitiative&logoColor=white&color=0080ff" alt="license">
	<img src="https://img.shields.io/github/last-commit/djoezeke/TodoList?style=default&logo=git&logoColor=white&color=0080ff" alt="last-commit">
	<img src="https://img.shields.io/github/languages/top/djoezeke/TodoList?style=default&color=0080ff" alt="repo-top-language">
	<img src="https://img.shields.io/github/languages/count/djoezeke/TodoList?style=default&color=0080ff" alt="repo-language-count">
</p>

<p align="center">
  <img src="images/to-do-list.jpg" alt="To-Do List"/>
</p>

The **To-Do List Application** enables users to manage and organize their tasks effectively. Create, track, complete and organize tasks between lists with fast modern interface.

<details>
  <summary>Table of Contents</summary>

- [📍 Overview](#📍-overview)
- [🚀 Features](#🚀-features)
- [📁 Project Structure](#📁-project-structure)
- [📌 Getting Started](#📌-getting-started)
  - [☑️ Prerequisites](#☑️-prerequisites)
  - [⚙️ Installation](#⚙️-installation)
  - [🤖 Usage](#🤖-usage)
- [🔰 Contributing](#🔰-contributing)
- [🙌 Acknowledgments](#🙌-acknowledgments)
- [📚 References](#📚-references)
- [📝 License](#📝-license)

</details>

## 📍 Overview

**To-Do List** is a web based application made predominantly with Django that allows the user to create and keep track of _Tasks_ and complete them with a single click.

## 🚀 Features

- 📝 **Create, edit, and delete tasks** with a modern, responsive UI
- ✅ **Mark tasks as complete/incomplete** with a single click
- 🗂️ **Organize tasks into lists** for better management
- 🔍 **Search, filter, and sort** tasks by title, date, or completion
- 🎨 **Modern UI** with Bootstrap 5 and Font Awesome icons
- 📱 **Mobile-friendly** and fully responsive
- 💾 **SQLite database** for easy setup and persistence
- ⚡ **Fast and intuitive** user experience
- 🛡️ **Secure** with CSRF protection and Django best practices

<!--
✔️ Complete Tasks
🌠 Move Task
❌ Delete Task
🌟 Select Tasks
💼 Create Folders
📁 Open Folder
❌ Delete Folder
-->

<!-- #### Example Screenshots

<p align="center">
   <img src="images/to-do-list.jpg" alt="To-Do List UI" width="600"/>
</p> -->

## 📁 Project Structure

```
TodoList
├── images
├── static
├── tasks
├── todolist
├── .python-version
├── pyproject.toml
├── requirements.txt       # Project dependencies.
├── .gitignore             # Files to ignore in Git.
├── LICENSE                # Project License.
└── README.md              # Project Documentation.
```

## 📌 Getting Started

### 📜 Technologies & Tools

#### ☑️ Prerequisites

#### 🧰 Additionals

- [Git](https://git-scm.com/) – (Optional) Version control and submodule/dependency management

### ⚙️ Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/djoezeke/TodoList.git
   cd TodoList
   ```
2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```
3. **Apply migrations:**
   ```bash
   python manage.py migrate
   ```
4. **Run the development server:**
   ```bash
   python manage.py runserver
   ```

### 🤖 Usage

1. Open your browser and go to `http://127.0.0.1:8000/`
2. Create a new list and start adding tasks!
3. Use the navigation bar to view all lists, all tasks, or return to the home page.
4. Edit, complete, or delete tasks and lists as needed.

## 🔰 Contributing

Feel free to submit issues or pull requests if you have suggestions or improvements for the game.

- **💬 [Join the Discussions](https://github.com/djoezeke/TodoList/discussions)**: Share your insights, provide feedback, or ask questions.
- **🐛 [Report Issues](https://github.com/djoezeke/TodoList/issues)**: Submit bugs found or log feature requests for the `TodoList` project.
- **💡 [Submit Pull Requests](https://github.com/djoezeke/TodoList/blob/main/CONTRIBUTING.md)**: Review open PRs, and submit your own PRs.

<details closed>
<summary>Contributing Guidelines</summary>

1. **Fork the Repository**: Start by forking the project repository to your github account.
2. **Clone Locally**: Clone the forked repository to your local machine using a git client.
   ```sh
   git clone --recursive https://github.com/djoezeke/TodoList
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
<p align="left">
   <a href="https://github.com{/djoezeke/TodoList/}graphs/contributors">
      <img src="https://contrib.rocks/image?repo=djoezeke/TodoList">
   </a>
</p>
</details>

## 🙌 Acknowledgments

We would like to express our gratitude to the following projects and individuals whose work made this project possible:

- [Django](https://www.github.com/django/django/) – The Web framework for perfectionists with deadlines.
- The open-source community for their invaluable libraries, tutorials, and support.
- Special thanks to all contributors, testers, and users who provided feedback and suggestions.

If you feel your work should be acknowledged here, please open an issue or pull request.

---

## 📚 References

- **Intresting:**
- [Font Awesome](https://fontawesome.com/)
- [Bootstrap 5](https://getbootstrap.com/)

- **Learning Resources:**
- [Django Documentation](https://docs.djangoproject.com/)

## 📝 License

This project is protected under the [MIT](LICENSE) License.
For more details, refer to the [LICENSE](LICENSE) file.
