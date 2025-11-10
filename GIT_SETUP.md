# How to Set Up Git

Git is a distributed version control system widely used for source code management. Follow these steps to set up Git on your computer:

## 1. Install Git

- **Windows:** Download from [git-scm.com](https://git-scm.com/download/win) and run the installer.
- **macOS:** Install with [Homebrew](https://brew.sh/) by running:
  ```sh
  brew install git
  ```
  Or download from [git-scm.com](https://git-scm.com/download/mac).
- **Linux:** Install via package manager. For example, on Ubuntu:
  ```sh
  sudo apt update
  sudo apt install git
  ```

## 2. Configure Your Identity

Run the following commands to set your name and email:

```sh
git config --global user.name "Your Name"
git config --global user.email "you@example.com"
```

## 3. Verify Installation

Check your Git version:

```sh
git --version
```

## 4. (Optional) Set Up SSH Keys

For secure communication with platforms like GitHub:

- Generate an SSH key:
  ```sh
  ssh-keygen -t ed25519 -C "you@example.com"
  ```
- Add your public key (`~/.ssh/id_ed25519.pub`) to your Git provider account.

## 5. Clone a Repository

To get a copy of a remote repository:

```sh
git clone https://github.com/owner/repo.git
```

---

You are now ready to use Git, happy coding!


