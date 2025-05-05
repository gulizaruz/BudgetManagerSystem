
# Budget Management Application

This project is a Java desktop application that allows users to easily manage their personal finances. Users can record their incomes and expenses, perform financial analyses, set goals, view transaction history, and create shared budgets.

## Features

- **Income and Expense Entry**: Users can record their incomes and expenses under various categories.
- **Goal Tracking**: Users can set financial goals and contribute towards them.
- **Transaction History**: Users can record and view their income and expense transactions.
- **Financial Analysis**: Users can visualize their income and expense distribution through graphical charts.
- **Shared Budget**: Multiple users can create a shared budget and contribute proportionally.
  - Users can contribute **equally or with custom percentages** to the budget.
  - **Recurring expenses** (e.g., rent, utilities) can be set up to automatically be added to the budget each month.
  - Users can monitor the shared budget's expenses through **visual graphs** and **statistical reports**.
  - Detailed **PDF reports** of the shared budget can be generated and exported.
  
- **Invoice Uploading**: Users can attach invoices to their income and expense transactions, which are stored within the application and linked to the respective transaction.
  
- **Personal Avatar and Profile**: Users can create their profile with their name, email, and password. They can also set an avatar (optional).

## Technologies

- **Java 8+**: The application works with Java 8 or higher versions.
- **Swing**: Used for building the graphical user interface (GUI).
- **JFreeChart**: Used to generate charts for financial analysis.
- **JUnit**: Unit tests have been written for the application.
- **FlatLaf**: Provides a dark theme for the user interface.
- **Apache Maven**: Used to manage project dependencies and build.

## Installation

To clone the project to your local machine:

```bash
git clone https://github.com/username/budget-management-app.git
```

To compile the project:

```bash
mvn install
```

Open the project using an IDE (IntelliJ IDEA or Eclipse) and run it.

## Usage

1. Launch the application.
2. **Create a new user** or **login with an existing user**.
3. **Add your incomes and expenses**. You can categorize and record your transactions.
4. **Set financial goals** and contribute towards them.
5. **Create shared budgets**. Multiple users can manage a shared budget.
6. **View transaction history**. All your past transactions are saved and can be viewed.
7. **Upload invoices** and associate them with income or expense transactions.
8. **Perform financial analyses**. You can visualize your income and expenses through charts.

## Shared Budget Features

The **Shared Budget** module allows multiple users to create and manage a shared budget. It is especially useful for groups such as housemates or family members who wish to jointly manage their finances.

- **Creating a Shared Budget**: A group can be created, and as users join, they can contribute to the shared budget.
  
- **Equal or Custom Contribution**: Each user can contribute equally or at a custom percentage to the shared budget.
  
- **Recurring Expenses**: Monthly recurring expenses (e.g., rent, bills) can be set up to automatically be added to the budget every month.

- **Financial Statistics and Visuals**: All expenses within the shared budget are visualized through graphs. This allows each member of the group to see their contribution to the overall budget and the distribution of expenses.

- **PDF Reports**: Detailed reports on the shared budget can be exported as PDF files for further review and tracking.

## Tests

The project includes unit tests written with JUnit. To run the tests:

```bash
mvn test
```

## Contribution

If you wish to contribute to this project, please follow these steps:

1. **Fork** this repository.
2. Create a new branch (e.g., `feature-xyz`).
3. Make your changes and commit them.
4. Submit a **Pull Request**.

## License

This project is licensed under the **MIT License**. For more information, please visit the [MIT License](https://opensource.org/licenses/MIT) page.

## Contact

For any questions or feedback regarding the project, feel free to reach out to me:

- **Email**: gulizaruz0@gmail.com
- **GitHub**: [github.com/gulizaruz](https://github.com/gulizaruz)

---

### **Key Highlights:**
- The **Shared Budget** feature enables users to collaborate on managing joint finances. The ability to track contributions and recurring expenses makes it an invaluable tool for groups.
- The **Financial Analysis** feature allows users to visualize their income and expense distribution easily.
- This project is an ideal solution for **families** or **housemates** who need to manage joint expenses collaboratively.
