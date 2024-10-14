## ⚙️ Vue TS Simplified Settings Page Project

This project is built using Vue.js with TypeScript and focuses on creating a simplified settings page using advanced Vue features like Teleport, KeepAlive, and shared state management. The project is styled using Tailwind CSS for a responsive and modern design.

This template will help you get started developing with Vue 3 in Vite.

# ✨ Features

	•	🛠️ Simplified settings page built using Vue.js and TypeScript.
	•	🗂️ Tab-based navigation between different settings sections.
	•	⚡ Usage of advanced Vue.js features like:
	•	🌀 Teleport: For rendering components outside the root DOM.
	•	💾 KeepAlive: To cache components and preserve their state when switching tabs.
	•	🔄 Shared state management to handle global settings across components.
	•	📦 Saving to localStorage: Automatically saves settings locally so they persist across browser sessions.
	•	🎬 Custom transitions using Vue.js’ built-in Transition component.
	•	🔔 Notification system using useNotifications for real-time notifications with user acknowledgment.
	•	🛡️ General, Privacy, and Notifications settings management using useSettings.
	•	🛡️ Form validation: Ensures that required fields are filled before submission using centralized validation logic in the useSettings composable.
	•	🎨 Tailwind CSS for responsive, utility-first styling.
	•	🚀 Built using Vite for fast development and optimized builds.

# 💻 Recommended IDE Setup

	•	VSCode + Volar (and disable Vetur).

# 🛠️ Type Support for .vue Imports in TS

TypeScript cannot handle type information for .vue imports by default, so we replace the tsc CLI with vue-tsc for type checking. In editors, you need Volar to make the TypeScript language service aware of .vue types.

# ⚙️ Customize Configuration

See Vite Configuration Reference.

# 📂 Project Structure

	•	src/: Contains all the source code.
	•	assets/: Contains the global CSS file (main.css) with Tailwind CSS customizations.
	•	components/: Vue components for different settings sections.
	•	composables/: Contains reusable logic with the useSettings and useNotifications composables.
	•	types/: Defines TypeScript types for tabs and other data structures.

# 🎨 Styling with Tailwind CSS

The project is styled using Tailwind CSS, a utility-first CSS framework. Additional custom styles are applied using the Tailwind @apply directive to enhance form inputs, buttons, notifications, and other elements.

# ⚡ Project Setup

Install dependencies:

npm install

Compile and Hot-Reload for Development:

npm run dev

Type-Check, Compile, and Minify for Production:

npm run build

Lint with ESLint:

npm run lint

# 🧰 Technologies Used

	•	🌐 Vue.js: JavaScript framework for building user interfaces.
	•	🛠️ TypeScript: Typed superset of JavaScript.
	•	⚡ Vite: Fast build tool and development server.
	•	🎨 Tailwind CSS: Utility-first CSS framework for responsive and customizable styling.
  •	🌍 Vercel: Deployment platform for hosting the project with automatic builds and easy integration.
	•	🌀 Teleport & KeepAlive: Advanced Vue.js components for rendering and caching.
	•	🔄 Composable Pattern: For handling settings logic in a reusable manner.
	•	💾 Saving to localStorage: Automatically saves settings locally, so they persist across browser sessions.
	•	🎬 Custom Transitions: Using the FadeTransition.vue component for smooth tab switching animations.
	•	🔔 Real-time Notifications: Using the useNotifications composable for user feedback.
	•	🛡️ Form Validation: Using the useSettings composable to validate form inputs (username, email, etc.) before submission.
	•	🛡️ General, Privacy, and Notifications Settings Management: Using the useSettings composable to handle settings-related data and state.

# 🚀 Getting Started

Prerequisites:

	•	📦 Node.js: Ensure that you have Node.js installed.

Running the Project:

To start the development server:

npm run dev

This will launch the app locally on http://localhost:3000.

# 🔧 Usage

	1.	Navigate to the settings page.
	2.	Switch between tabs for General, Notifications, and Privacy settings using the TabLink component.
	3.	The state is shared and will be preserved using KeepAlive.
	4.	The transitions between the components are smooth thanks to the FadeTransition component.
	5.	Settings are automatically saved to localStorage to persist data across sessions.
	6.	Form validation ensures required fields are filled before the form is submitted.
	7.	Real-time notifications provide feedback for user actions.

# 🌍 Deployment

This project has been deployed on Vercel.

You can view the live project here (replace with your actual Vercel deployment URL).

To deploy this project on Vercel, follow these steps:

	1.	Build the Project:

npm run build


	2.	Push to GitHub or GitLab: Ensure your project is pushed to a repository.
	3.	Connect to Vercel:
	•	Go to Vercel.
	•	Connect your repository.
	•	Vercel will automatically detect the project as a Vite-based Vue.js app.
	4.	Set the Build Command:

npm run build


	5.	Set the Output Directory:

dist


	6.	Deploy: Click deploy, and Vercel will handle the rest.

# 🤝 Contributing

If you would like to contribute to this project, feel free to open issues or submit pull requests.

# 📄 License

This project is licensed under the MIT License.
