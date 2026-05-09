<p align="center">
    <img src="https://raw.githubusercontent.com/PKief/vscode-material-icon-theme/ec559a9f6bfd399b82bb44393651661b08aaf7ba/icons/folder-markdown-open.svg" align="center" width="30%">
</p>
<p align="center"><h1 align="center">MELODYFY</h1></p>
<p align="center">
	<em><code>❯ A Spotify-Inspired Web Music Player Built with HTML, CSS & JavaScript</code></em>
</p>
<p align="center">
	<img src="https://img.shields.io/github/license/SaurabhKumawatt/Melodyfy?style=default&logo=opensourceinitiative&logoColor=white&color=0080ff" alt="license">
	<img src="https://img.shields.io/github/last-commit/SaurabhKumawatt/Melodyfy?style=default&logo=git&logoColor=white&color=0080ff" alt="last-commit">
	<img src="https://img.shields.io/github/languages/top/SaurabhKumawatt/Melodyfy?style=default&color=0080ff" alt="repo-top-language">
	<img src="https://img.shields.io/github/languages/count/SaurabhKumawatt/Melodyfy?style=default&color=0080ff" alt="repo-language-count">
</p>
<p align="center"><!-- default option, no dependency badges. -->
</p>
<p align="center">
	<!-- default option, no dependency badges. -->
</p>
<br>

##  Table of Contents

- [ Overview](#-overview)
- [ Features](#-features)
- [ Project Structure](#-project-structure)
  - [ Project Index](#-project-index)
- [ Getting Started](#-getting-started)
  - [ Prerequisites](#-prerequisites)
  - [ Installation](#-installation)
  - [ Usage](#-usage)
  - [ Testing](#-testing)
- [ Project Roadmap](#-project-roadmap)
- [ Contributing](#-contributing)
- [ License](#-license)
- [ Acknowledgments](#-acknowledgments)

---

##  Overview

<code>Melodyfy is a Spotify-inspired web music player application built using HTML, CSS, and JavaScript. The project allows users to browse playlists, stream local audio files, and control music playback through an interactive and responsive user interface. It features dynamic playlist rendering, album covers, music controls, and folder-based song management.</code>

---

##  Features


- 🎵 Dynamic music playback using JavaScript Audio API
- 📂 Folder-based playlist management
- ▶️ Play, Pause, Next, and Previous controls
- 📀 Dynamic album and playlist rendering
- 📱 Responsive Spotify-inspired UI
- ⏱ Real-time song duration and progress tracking
- 🎧 Multiple categorized playlists support
- 🖼 Playlist cover image support
- ⚡ Lightweight frontend-only architecture


---

##  Project Structure

```sh
└── Melodyfy/
    ├── README.md
    ├── assets
    │   ├── cross.svg
    │   ├── home.svg
    │   ├── humburger.svg
    │   ├── images
    │   ├── logo.svg
    │   ├── music.svg
    │   ├── mute.svg
    │   ├── next.svg
    │   ├── pause.svg
    │   ├── play.svg
    │   ├── playlist.svg
    │   ├── plus.svg
    │   ├── previous.svg
    │   ├── search.svg
    │   └── volume.svg
    ├── css
    │   ├── style.css
    │   └── utility.css
    ├── favicon.ico
    ├── index.html
    ├── js
    │   └── script.js
    └── songs
        ├── Best Motivational hindi songs
        ├── Chala Chal
        ├── Hindi Lofi Sleeping Songs 😴
        ├── Saurabh
        └── Top Devotional Songs
```


###  Project Index
<details open>
	<summary><b><code>MELODYFY/</code></b></summary>
	<details> <!-- __root__ Submodule -->
		<summary><b>__root__</b></summary>
		<blockquote>
			<table>
			<tr>
				<td><b><a href='https://github.com/SaurabhKumawatt/Melodyfy/blob/master/index.html'>index.html</a></b></td>
				<td><code>Serves as the main entry point of Melodyfy, defining the Spotify-inspired layout, sidebar navigation, playlist containers, music player controls, and responsive UI structure.</code></td>
			</tr>
			</table>
		</blockquote>
	</details>
	<details> <!-- css Submodule -->
		<summary><b>css</b></summary>
		<blockquote>
			<table>
			<tr>
				<td><b><a href='https://github.com/SaurabhKumawatt/Melodyfy/blob/master/css/utility.css'>utility.css</a></b></td>
				<td><code>Contains reusable utility classes for layout, spacing, flexbox alignment, colors, border styling, and custom scrollbar customization used across the application.</code></td>
			</tr>
			<tr>
				<td><b><a href='https://github.com/SaurabhKumawatt/Melodyfy/blob/master/css/style.css'>style.css</a></b></td>
				<td><code>Defines the core styling and responsive design of Melodyfy including playlist cards, sidebar layout, music controls, animations, hover effects, and Spotify-inspired theme implementation.</code></td>
			</tr>
			</table>
		</blockquote>
	</details>
	<details> <!-- songs Submodule -->
		<summary><b>songs</b></summary>
		<blockquote>
			<details>
				<summary><b>Chala Chal</b></summary>
				<blockquote>
					<table>
					<tr>
						<td><b><a href='https://github.com/SaurabhKumawatt/Melodyfy/blob/master/songs/Chala Chal/info.json'>info.json</a></b></td>
						<td><code>Stores metadata for the "Chala Chal" playlist including playlist title and description used for dynamic rendering.</code></td>
					</tr>
					</table>
				</blockquote>
			</details>
			<details>
				<summary><b>Best Motivational hindi songs</b></summary>
				<blockquote>
					<table>
					<tr>
						<td><b><a href='https://github.com/SaurabhKumawatt/Melodyfy/blob/master/songs/Best Motivational hindi songs/info.json'>info.json</a></b></td>
						<td><code>❯ Contains metadata configuration for the motivational songs playlist used in dynamic playlist generation.</code></td>
					</tr>
					</table>
				</blockquote>
			</details>
			<details>
				<summary><b>Hindi Lofi Sleeping Songs 😴</b></summary>
				<blockquote>
					<table>
					<tr>
						<td><b><a href='https://github.com/SaurabhKumawatt/Melodyfy/blob/master/songs/Hindi Lofi Sleeping Songs 😴/info.json'>info.json</a></b></td>
						<td><code>❯ Provides playlist information and descriptive metadata for the Hindi Lofi Sleeping Songs collection.</code></td>
					</tr>
					</table>
				</blockquote>
			</details>
			<details>
				<summary><b>Top Devotional Songs</b></summary>
				<blockquote>
					<table>
					<tr>
						<td><b><a href='https://github.com/SaurabhKumawatt/Melodyfy/blob/master/songs/Top Devotional Songs/info.json'>info.json</a></b></td>
						<td><code>❯ Defines playlist metadata and descriptive information for the devotional songs collection.</code></td>
					</tr>
					</table>
				</blockquote>
			</details>
			<details>
				<summary><b>Saurabh</b></summary>
				<blockquote>
					<table>
					<tr>
						<td><b><a href='https://github.com/SaurabhKumawatt/Melodyfy/blob/master/songs/Saurabh/info.json'>info.json</a></b></td>
						<td><code>❯ Contains custom playlist metadata including title and description for personal playlist rendering.</code></td>
					</tr>
					</table>
				</blockquote>
			</details>
		</blockquote>
	</details>
	<details> <!-- js Submodule -->
		<summary><b>js</b></summary>
		<blockquote>
			<table>
			<tr>
				<td><b><a href='https://github.com/SaurabhKumawatt/Melodyfy/blob/master/js/script.js'>script.js</a></b></td>
				<td><code>❯ Implements the core application logic including dynamic song fetching, playlist rendering, music playback controls, Audio API integration, album handling, and interactive UI functionality.</code></td>
			</tr>
			</table>
		</blockquote>
	</details>
</details>

---
##  Getting Started

###  Prerequisites

Before getting started with Melodyfy, ensure your runtime environment meets the following requirements:

- **Programming Language:** Error detecting primary_language: {'html': 1, 'css': 2, 'json': 5, 'js': 1}


###  Installation

Install Melodyfy using one of the following methods:

**Build from source:**

1. Clone the Melodyfy repository:
```sh
❯ git clone https://github.com/SaurabhKumawatt/Melodyfy
```

2. Navigate to the project directory:
```sh
❯ cd Melodyfy
```

3. Install the project dependencies:

echo 'No additional dependencies required.'



###  Usage
Run Melodyfy using the following command:
echo 'Open index.html in browser'

###  Testing
Run the test suite using the following command:
echo 'No automated testing framework implemented.'

---
##  Project Roadmap

- [X] **`Responsive UI`**: Implemented Spotify-inspired responsive interface.
- [X] **`Dynamic Playlists`**: Added folder-based dynamic playlist rendering.
- [X] **`Music Controls`**: Added play, pause, next, and previous functionality.
- [ ] **`Authentication`**: Add user login and authentication system.
- [ ] **`Spotify API Integration`**: Integrate Spotify Web API for online streaming.
- [ ] **`Backend Support`**: Add database and server-side playlist management.

---

##  Contributing

- **💬 [Join the Discussions](https://github.com/SaurabhKumawatt/Melodyfy/discussions)**: Share your insights, provide feedback, or ask questions.
- **🐛 [Report Issues](https://github.com/SaurabhKumawatt/Melodyfy/issues)**: Submit bugs found or log feature requests for the `Melodyfy` project.
- **💡 [Submit Pull Requests](https://github.com/SaurabhKumawatt/Melodyfy/blob/main/CONTRIBUTING.md)**: Review open PRs, and submit your own PRs.

<details closed>
<summary>Contributing Guidelines</summary>

1. **Fork the Repository**: Start by forking the project repository to your github account.
2. **Clone Locally**: Clone the forked repository to your local machine using a git client.
   ```sh
   git clone https://github.com/SaurabhKumawatt/Melodyfy
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
   <a href="https://github.com{/SaurabhKumawatt/Melodyfy/}graphs/contributors">
      <img src="https://contrib.rocks/image?repo=SaurabhKumawatt/Melodyfy">
   </a>
</p>
</details>

---

##  License

This project is protected under the [MIT](https://choosealicense.com/licenses) License. For more details, refer to the [LICENSE](https://choosealicense.com/licenses/) file.

---

##  Acknowledgments

- Inspired by Spotify Web Player UI
- Built while learning frontend web development and JavaScript
- Thanks to open-source frontend learning resources and communities

---
