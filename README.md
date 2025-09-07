# 🚀 PSR-12 Auto Fix Bot with GitHub Actions

This project demonstrates how to **automate PHP code standardization** following **PSR-12**, using **PHP CS Fixer** and **GitHub Actions**.

Unlike traditional setups that just reject pull requests with non-compliant code, this bot **automatically fixes formatting issues** and commits the changes directly to the PR, saving developers’ time and ensuring consistent code quality.

---

## ✨ Benefits for Teams and Businesses

* 🔒 **Consistently clean code**: eliminates style debates in the team.
* ⚡ **Boost productivity**: developers focus on business logic, not formatting.
* 🤖 **Reliable automation**: fixes code automatically before merging.
* 📈 **Scalable**: suitable for both small projects and large teams with multiple contributors.

---

## ⚙️ How It Works

1. A developer opens a **Pull Request**.
2. GitHub Actions runs **PHP CS Fixer**.
3. If any formatting issues are found:

   * The bot automatically fixes the files.
   * Commits the changes to the PR with the message: `fix: apply PSR-12 auto formatting`.
4. The PR is ready for review, already compliant with PSR-12.

---

## 📂 Project Structure

```
.
├── .github/
│   └── workflows/
│       └── auto-fix.yml      # GitHub Actions workflow
├── src/
│   └── Example.php           # Example of unformatted code
├── .php-cs-fixer.dist.php    # PHP CS Fixer configuration
├── composer.json             # Dependencies
└── README.md                 # Project documentation
```

---

## 🛠️ Technologies Used

* **PHP 8.3**
* **Composer**
* **PHP CS Fixer**
* **GitHub Actions**

---

## 🚀 How to Test

1. Fork this repository.
2. Create a branch with **non-PSR-12 compliant code** in `src/`.
3. Open a Pull Request to the `main` branch.
4. The bot will run **auto-fix** and commit the corrected code automatically.

---

## 💡 Use Cases for Clients

* Ensure **code quality** in medium to large projects.
* Integrate into **CI/CD pipelines** for companies that enforce strict coding standards.
* Reduce reviewer workload and accelerate the **code review process**.

---

## 📌 About This Project

This repository is a **practical example** showcasing expertise in:

* **Integrating code quality tools**
* **Automating pipelines with GitHub Actions**
* **Enforcing PSR standards in PHP projects**

If you or your company need **custom CI/CD solutions and automated code quality tools**, I can help design and implement robust, tailor-made solutions.
