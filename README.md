# expense-tracker-wpf
# Expense Tracker — WPF Edition

A lightweight **desktop GUI** built with **WPF on .NET 8** for quickly logging and reviewing personal expenses.  
It’s a single-window app that shows modern C# patterns (nullable refs, implicit usings, `ObservableCollection<T>`, data binding) without heavyweight frameworks.

---

## ✨ Features

| Capability | Details |
|------------|---------|
| **Inline editing** | Add or edit rows directly inside the `DataGrid`. |
| **Delete-selected** | Remove the highlighted expense with one click. |
| **CSV persistence** | On launch, the app loads `expenses.csv`; on *Save* it overwrites the file. |
| **Culture-invariant** | Amounts always parse/serialize with a `.` decimal separator, so the CSV works in any locale. |
| **Modern stack** | .NET 8, C# 12, nullable enabled, SDK-style project. |

---

## 🛠 Prerequisites

* Windows 10/11  
* [.NET 8 SDK](https://dotnet.microsoft.com/) (run `dotnet --version` to confirm)

---

## 🚀 Quick start

```bash
git clone https://github.com/SaiAkhilS007/expense-tracker-wpf.git
cd expense-tracker-wpf/ExpenseTracker.UI
dotnet run
