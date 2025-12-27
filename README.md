# 📱 SpendX Mobile - Personal Finance Tracker

**SpendX Mobile** is a cross-platform mobile application designed to help users track expenses and visualize financial health on the go. Built with **React Native** and **Expo**, it delivers a native performance experience with a modern, file-based routing architecture.

🔌 **Backend:** Powered by the [SpendX API](https://github.com/Udayveer525/SpendX-Backend)

---

## 🛠️ Tech Stack

| Component | Technology |
| :--- | :--- |
| **Framework** | ![React Native](https://img.shields.io/badge/React_Native-20232A?style=flat&logo=react&logoColor=61DAFB) via **Expo SDK** |
| **Routing** | **Expo Router** (File-based navigation) |
| **State/Logic** | Custom React Hooks (`useTransactions`) |
| **Networking** | Fetch API connecting to Express Backend |
| **Design** | Flexbox & `StyleSheet` API |

---

## ✨ Key Features

* **📱 Cross-Platform:** Single codebase running smoothly on both iOS and Android.
* **🛣️ Modern Navigation:** Utilizes **Expo Router** for intuitive, file-system based routing (similar to Next.js).
* **🧩 Modular Architecture:** Reusable UI components (`BalanceCard`, `TransactionItem`) and isolated logical hooks.
* **🔒 Secure Auth Flow:** dedicated authentication screens (`sign-in`, `sign-up`) handling user sessions.
* **📱 Safe Area Management:** Implemented custom `SafeScreen` wrappers to handle modern device notches and bezels gracefully.
