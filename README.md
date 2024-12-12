# FundFlare
Crowdfunding Platform for Small &amp; Medium Enterprises (SMEs)

# Crowdfunding Platform for SMEs

## Description

This is a web-based crowdfunding platform aimed at helping Small and Medium Enterprises (SMEs) launch campaigns and gain support from backers. The platform provides features such as dynamic campaign listings, detailed campaign information, backer contributions, and SME campaign management. Users can browse campaigns, create new ones, contribute funds, and track campaign progress.

---

## Features

### 1. **Welcome Page (index.html)**

- **Purpose**: This is the landing page that introduces the platform to new users.
- **Key Features**:
  - Introduction to the platform's goals and services.
  - Clear Call-to-Action (CTA) buttons to guide users to the **Login** or **Sign Up** pages.
  - Option to navigate directly to the campaign listings for existing users.
  
- **Technologies**: 
  - HTML for structure.
  - CSS for layout and styling.
  - JavaScript for basic interactive features like navigation.

### 2. **Login Page (login.html)**

- **Purpose**: Allows existing users to log in to the platform.
- **Key Features**:
  - Fields for entering email and password.
  - “Forgot password” link for account recovery.
  - Redirects to the **Dashboard** page upon successful login.
  
- **Technologies**:
  - HTML for form structure.
  - CSS for styling.
  - JavaScript for form validation (ensuring both fields are filled).

### 3. **Signup Page (signup.html)**

- **Purpose**: Allows new users to create an account on the platform.
- **Key Features**:
  - Fields for user details such as name, email, password, and confirm password.
  - Form validation for mandatory fields and password strength.
  - Redirects to the **Login** page upon successful signup.
  
- **Technologies**:
  - HTML for form structure.
  - CSS for styling.
  - JavaScript for form validation.

### 4. **Home Page (home.html)**

- **Purpose**: Welcomes users and highlights featured campaigns.
- **Key Features**:
  - Navigation bar with links to key pages.
  - Carousel or grid for featured campaigns.
  - Call-to-action buttons like “Create Campaign” and “Explore Campaigns”.
  
- **Technologies**:
  - HTML for structure.
  - CSS for layout and styling (e.g., grid or flexbox).
  - JavaScript for interactivity (e.g., carousel).

### 5. **Campaign Listing Page (campaigns.html)**

- **Purpose**: Displays all active campaigns.
- **Key Features**:
  - Grid or list view of campaigns.
  - Search bar and filters (by category or funding goal).
  - Dynamically loads campaigns from a data file (JSON or array).
  - Implemented search and filter functionality.

- **Technologies**:
  - HTML for structure.
  - CSS for layout.
  - JavaScript for dynamic content loading and search/filter functionality.

### 6. **Campaign Detail Page (campaign-detail.html)**

- **Purpose**: Show detailed information about a specific campaign.
- **Key Features**:
  - Displays campaign description, funding goal, progress bar, and backer details.
  - Form for backers to contribute funds via **Razorpay API**.
  - Dynamically updates progress bar based on contributions.

- **Technologies**:
  - HTML for structure.
  - CSS for styling.
  - JavaScript for updating the progress bar and handling contributions through Razorpay.

### 7. **Create Campaign Page (create-campaign.html)**

- **Purpose**: Allows SMEs to submit new campaigns.
- **Key Features**:
  - Form with fields for campaign title, description, funding goal, and image upload.
  - Validation for mandatory fields.
  - Form data is saved to a local database (JSON or JavaScript array).

- **Technologies**:
  - HTML for form structure.
  - CSS for styling.
  - JavaScript for form validation and data submission.

### 8. **Dashboard Page (dashboard.html)**

- **Purpose**: Displays user-specific data (e.g., backer contributions or SME campaign performance).
- **Key Features**:
  - Shows campaigns related to the user.
  - Displays contributions made or received, and milestones achieved.

- **Technologies**:
  - HTML for layout.
  - CSS for styling.
  - JavaScript for dynamically fetching and displaying data.

### 9. **About/Contact Page (about.html)**

- **Purpose**: Provides information about the platform and support options.
- **Key Features**:
  - Static text with platform details.
  - Contact form for users to reach out.

- **Technologies**:
  - HTML for structure.
  - CSS for styling.
  - JavaScript for form validation and data submission.

---

## Razorpay Integration for Contributions

To allow users (backers) to contribute funds to campaigns, we have integrated **Razorpay**, a payment gateway.

- **Features**:
  - Users can contribute funds directly to campaigns using Razorpay.
  - The contribution amount is processed securely through Razorpay’s API.
  - Once a backer contributes, the progress bar of the campaign is updated dynamically.

- **Technologies**:
  - **Razorpay API**: To handle payment processing.
  - **JavaScript**: To interact with the Razorpay API and update the campaign progress.

---

## Technology Stack

- **HTML**: Page structure and semantic content.
- **CSS**: Styling and layout, including responsiveness using media queries.
- **JavaScript**: Interactivity, form validation, and dynamic content loading.
- **Razorpay API**: For handling user payments and contributions.
- **Optional Enhancements**:
  - LocalStorage or JSON files for persistent data storage.
  - Bootstrap for faster styling and responsiveness.

---

## Usage Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/username/repository-name.git
   ```

2. Navigate to the project directory:
   ```bash
   cd repository-name
   ```

3. Open the `welcome.html` file in your browser to start using the platform.

4. For testing Razorpay payment integration, make sure to have valid Razorpay API keys configured.

---

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please follow the steps below:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-name`).
3. Make your changes and commit them (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature-name`).
5. Create a new Pull Request.

---

## Project Members 
1. Sachin Tambe
2. Athrva Butte
3. Tanush Utekar


