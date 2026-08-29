# 💰 Expense Tracker System

Welcome to the **Expense Tracker System** — a simple and practical desktop application built to help you record, organize and monitor your daily expenses easily.

## 🌟 Features

- **🔐 Secure Login:** User registration and login to keep your financial data private and secure.
- **➕ Expense Management:** Add, edit and delete expense records anytime.
- **🏷️ Category Management:** Organize expenses into categories like Food, Transport, Shopping and Bills.
- **🔍 Search Expenses:** Quickly find past expenses by date or category.
- **📈 Reports & Dashboard:** View daily and monthly reports with a clear spending summary.

## 🛠️ Technologies Used

- **Language:** C#
- **Framework:** .NET (Windows Forms)
- **Database:** Microsoft SQL Server
- **IDE:** Microsoft Visual Studio
- **Version Control:** Git & GitHub

## 📂 Project Struture
Expense-Tracker-System
│
├── FIT.Data/                        # Data models
│   ├── User.cs                       # User Authentication data
│   ├── Expense.cs                    # Expense Management data
│   ├── BudgetCategory.cs             # Category Management data
│   └── Vrijednosti.cs                # Shared values/constants
│
├── FIT.Infrastructure/              # Database connection & context
│   └── BUDGETDbContext.cs            # Handles all database operations
│
├── FIT.WinForms/                    # Main application (UI)
│   ├── Forms/
│   │   ├── frmLogin.cs                # 🔐 User Authentication - Login
│   │   ├── frmRegister.cs             # 🔐 User Authentication - Register
│   │   ├── frmExpense.cs              # ➕ Expense Management - Add/Edit
│   │   ├── frmDelete.cs               # ➕ Expense Management - Delete
│   │   ├── frmCategory.cs             # 🏷️ Category Management
│   │   └── frmDashboard.cs            # 📊 Reports and Dashboard
│   │
│   ├── Izvjestaji/                    # 📊 Reports and Dashboard module
│   │   └── frmIzvjestaji.cs           # Generates daily/monthly reports
│   │
│   ├── Helpers/                      # Utility/helper classes
│   ├── Resources/                    # Icons and images
│   └── Program.cs                    # Application entry point
│
├── imgs/                             # App logo and icons
├── screenshots/                      # Screenshots of the running app
├── .gitignore
├── BUDGET.sln                        # Visual Studio solution file
└── README.md


## 📋 Project Info

- **Course:** Software Engineering
- **Semester:** Summer 2025-2026, Section C, Group No -05
- **Supervised By:** Farzana Bente Alam

## 👥 Team Members

| Name | ID |
|------|-----|
| Mushfiqun Nobi Mahim | 24-59884-3 |
| Niloy Tanjil Jesun | 24-59830-3 |
| Md. Golam Al Wali | 24-59887-3 |
| Humayra Adiba | 23-55453-3 |
| Progma Hossain | 23-51944-2 |

