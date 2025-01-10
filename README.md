<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="KMFT Group - Professional Electrical Services">
    <title>KMFT Group - Electrical Services</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #333;
            color: white;
            padding: 20px;
            text-align: center;
        }
        header h1 {
            margin: 0;
        }
        nav {
            text-align: center;
            margin-top: 10px;
            background-color: #444;
        }
        nav a {
            color: white;
            padding: 10px 20px;
            text-decoration: none;
            display: inline-block;
        }
        nav a:hover {
            background-color: #888;
        }
        section {
            padding: 20px;
            margin: 10px;
            background-color: white;
            border-radius: 8px;
        }
        .container {
            max-width: 1200px;
            margin: 0 auto;
        }
        .appointment-form input,
        .payment-form input {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border-radius: 5px;
            border: 1px solid #ccc;
        }
        .appointment-form button,
        .payment-form button {
            background-color: #333;
            color: white;
            padding: 10px 20px;
            border: none;
            cursor: pointer;
        }
        .appointment-form button:hover,
        .payment-form button:hover {
            background-color: #555;
        }
        .callout-fees {
            padding: 10px;
            background-color: #eee;
            border-radius: 5px;
            margin-top: 20px;
        }
        .footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 20px;
            margin-top: 40px;
        }
    </style>
</head>
<body>
    <header>
        <h1>KMFT Group - Electrical Services</h1>
        <p>Reliable and Professional Electrical Solutions</p>
    </header>

    <nav>
        <a href="#appointment">Appointment</a>
        <a href="#payment">Payment</a>
        <a href="#callout-fees">Call-Out Fees</a>
    </nav>

    <div class="container">
        <!-- Appointment Section -->
        <section id="appointment">
            <h2>Schedule an Appointment</h2>
            <form class="appointment-form">
                <label for="name">Full Name:</label>
                <input type="text" id="name" name="name" required>

                <label for="email">Email Address:</label>
                <input type="email" id="email" name="email" required>

                <label for="phone">Phone Number:</label>
                <input type="tel" id="phone" name="phone" required>

                <label for="date">Preferred Appointment Date:</label>
                <input type="date" id="date" name="date" required>

                <label for="time">Preferred Appointment Time:</label>
                <input type="time" id="time" name="time" required>

                <button type="submit">Book Appointment</button>
            </form>
        </section>

        <!-- Payment Section -->
        <section id="payment">
            <h2>Make a Payment</h2>
            <form class="payment-form">
                <label for="amount">Amount (ZAR):</label>
                <input type="number" id="amount" name="amount" min="0" step="0.01" required>

                <label for="payment-method">Payment Method:</label>
                <select id="payment-method" name="payment-method" required>
                    <option value="credit-card">Credit Card</option>
                    <option value="debit-card">Debit Card</option>
                    <option value="paypal">PayPal</option>
                </select>

                <button type="submit">Pay Now</button>
            </form>
        </section>

        <!-- Call-Out Fees Section -->
        <section id="callout-fees" class="callout-fees">
            <h2>Our Call-Out Fees</h2>
            <p>Our standard call-out fee is <strong>R500</strong>. This includes the initial assessment and consultation. Additional fees may apply for repairs or installations.</p>
        </section>
    </div>

    <footer class="footer">
        <p>KMFT Group | 123 Main Street, Cityville | Tel: +27 11 234 5678</p>
        <p>&copy; 2025 KMFT Group. All Rights Reserved.</p>
    </footer>
</body>
</html>


<!--
  <<< Author notes: Course header >>>
  Read <https://skills.github.com/quickstart> for more information about how to build courses using this template.
  Include a 1280×640 image, course name in sentence case, and a concise description in emphasis.
  In your repository settings: enable template repository, add your 1280×640 social image, auto delete head branches.
  Next to "About", add description & tags; disable releases, packages, & environments.
  Add your open source license, GitHub uses the MIT license.
-->

# Code with GitHub Copilot

_GitHub Copilot can help you code by offering autocomplete-style suggestions right in VS Code and Codespaces._

</header>

<!--
  <<< Author notes: Course start >>>
  Include start button, a note about Actions minutes,
  and tell the learner why they should take the course.
-->

## Welcome

GitHub Copilot can help you code by offering autocomplete-style suggestions. You can learn how GitHub Copilot works, and what to consider while using GitHub Copilot. GitHub Copilot analyzes the context in the file you are editing, as well as related files, and offers suggestions from within your text editor. GitHub Copilot is powered by OpenAI Codex, a new AI system created by OpenAI.

- **Who this is for**: Developers, DevOps Engineers, Software development managers, Testers.
- **What you'll learn**: How to install Copilot into a Codespace, accept suggestions from code, accept suggestions from comments.
- **What you'll build**: Javascript files that will have code generated by Copilot AI for code and comment suggestions.
- **Prerequisites**: 
  - [GitHub account](https://github.com/login) - With available Codespaces minutes.
  - [GitHub Copilot](https://github.com/github-copilot/signup) - For learning, the **Copilot Free** option with usage limits should be sufficient.
- **Timing**: This course can be completed in under an hour.

### How to start this course

<!-- For start course, run in JavaScript:
'https://github.com/new?' + new URLSearchParams({
  template_owner: 'skills',
  template_name: 'copilot-codespaces-vscode',
  owner: '@me',
  name: 'skills-copilot-codespaces-vscode',
  description: 'My clone repository',
  visibility: 'public',
}).toString()
-->

[![start-course](https://user-images.githubusercontent.com/1221423/235727646-4a590299-ffe5-480d-8cd5-8194ea184546.svg)](https://github.com/new?template_owner=skills&template_name=copilot-codespaces-vscode&owner=%40me&name=skills-copilot-codespaces-vscode&description=My+clone+repository&visibility=public)

1. Right-click **Start course** and open the link in a new tab.
2. In the new tab, most of the prompts will automatically fill in for you.
   - For owner, choose your personal account or an organization to host the repository.
   - We recommend creating a public repository, as private repositories will [use Actions minutes](https://docs.github.com/en/billing/managing-billing-for-github-actions/about-billing-for-github-actions).
   - Scroll down and click the **Create repository** button at the bottom of the form.
3. After your new repository is created, wait about 20 seconds, then refresh the page. Follow the step-by-step instructions in the new repository's README.

<footer>

<!--
  <<< Author notes: Footer >>>
  Add a link to get support, GitHub status page, code of conduct, license link.
-->

---

Get help: [Post in our discussion board](https://github.com/orgs/skills/discussions/categories/code-with-copilot) &bull; [Review the GitHub status page](https://www.githubstatus.com/)

&copy; 2023 GitHub &bull; [Code of Conduct](https://www.contributor-covenant.org/version/2/1/code_of_conduct/code_of_conduct.md) &bull; [MIT License](https://gh.io/mit)

</footer>
