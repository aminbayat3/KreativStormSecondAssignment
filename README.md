# KreativStormSecondAssignment

## Project: HeavyMachinery Website

### Introduction
This project is a static website for **HeavyMachinery**, designed to showcase the services, machines, and contact information of a construction company. The website consists of several pages, including **Home**, **Services**, **Machines**, and **Contact** pages, each providing valuable information to potential customers.

**[Visit the HeavyMachinery Website](https://aminbayat3.github.io/KreativStormSecondAssignment/)**.

### Technologies Used

- **HTML5 Semantic Structure**:  
  We followed semantic coding practices by using meaningful tags such as `<header>`, `<main>`, `<footer>`, and `<section>` to organize content. Instead of relying solely on `<div>`, we incorporated `<ul>` and `<li>` elements for lists to ensure proper content structure.

- **ARIA Labels**:  
  To enhance accessibility for screen readers and improve SEO, we used ARIA labels on interactive elements and links to ensure a more inclusive user experience.

- **Folder Structure**:  
  The project adopts a clear folder structure, with a **global** folder containing styles such as resets, boilerplate CSS, and shared components like the header and footer. Additionally, a `utils.css` file is used to apply the DRY (Don’t Repeat Yourself) principle by defining reusable common classes across pages.

- **CSS Variables**:  
  CSS variables were utilized for consistent colors and font management throughout the website, simplifying the styling process and allowing for easier adjustments.

- **CSS Functions**:  
  We implemented the `clamp()` function to achieve responsive font sizes that adapt seamlessly across various screen sizes, ensuring optimal readability on devices ranging from desktop to mobile.

- **Responsiveness**:  
  The website is fully responsive and adjusts perfectly for:
  - **Desktop**: 1024px and above
  - **Laptops**: 768px and above
  - **Tablets**: 480px and above
  - **Mobile Devices**: Less than 480px

- **Class Naming**:  
  Although the project does not use a popular naming convention like BEM, we ensured that class names are clear, specific, and understandable, making the codebase easy to maintain and extend.

---

## Contribution Guidelines

Before contributing, please make sure to follow these guidelines and steps to ensure smooth collaboration.

### Steps to Contribute

1. **Clone the Project**:  
   Use `git clone <repository-url>` to clone the project to your local machine.

2. **Pull Latest Changes**:  
   Run `git pull` to make sure your `main` branch is up to date with the latest changes from the remote repository.

3. **Create a New Branch**:  
   Run `git checkout -b <name-of-your-branch>` to create a new branch where you will make your changes.

4. **Work on Your Branch**:  
   Implement your changes on this new branch.  
   Once you're done with the changes, run `git add .` to stage all the modified files.  
   Commit your changes locally using `git commit -m "Your commit message"`.

5. **Push Your Branch**:  
   Push your branch to the remote repository with `git push origin <name-of-your-branch>`.

6. **Create a Pull Request**:  
   Go to the repository on GitHub.  
   Navigate to the **Pull requests** tab and create a new pull request.  
   Make sure your pull request compares your branch against the `main` branch.  
   Add a description of the changes you've made and assign **Amin** as a reviewer.

7. **Review Process**:  
   Once the pull request is approved, you can merge your changes into the `main` branch.

---

### Next Steps After Contribution

1. **Switch Back to the Main Branch**:  
   After your pull request is merged, switch back to the `main` branch with `git checkout main`.

2. **Update Your Local Main Branch**:  
   Run `git pull` to get the latest changes from the remote `main` branch. This ensures your local `main` branch is up to date.

3. **Create a New Branch for the Next Task**:  
   Run `git checkout -b <new-task-branch>`

---

Thanks for contributing! 😄
