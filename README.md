# Wasserstoff IDE

Wasserstoff IDE is a web-based Integrated Development Environment (IDE) built using Next.js and CSS/Tailwind CSS. It allows users to manage folders and various file types, providing different interfaces based on the file extension for editing and previewing content.

## Features

- **Folder and File Structure**: Displays folders and files hierarchically in a sidebar.
- **File Types and Functionality**:
  - **.ed files**: Opens a text editor for editing text files.
  - **.note files**: Opens a note maker for creating and categorizing notes with drag-and-drop functionality.
  - **.lt files**: Opens a list-making interface for creating lists.
  - **.readme files**: Opens an interface to preview README files without markup.
- **State Management**: Clean and organized state management.
- **Styling**: Utilizes Tailwind CSS for responsive and clean UI design with animations for drag-and-drop actions.
- **Deployment**: Deployed on Netlify for easy access and testing.

## Technologies Used

- **Next.js**: React framework for building server-side rendered applications.
- **React**: JavaScript library for building user interfaces.
- **Tailwind CSS**: Utility-first CSS framework for designing responsive web applications.
- **JavaScript**: Modern JavaScript features for writing clean and efficient code.
- **react-beautiful-dnd**: Create beautiful drag and drop for lists.
- **marked**:  Use it to convert Markdown content to HTML.
- **MUI Icons Library**: To import the icons.
- **GitHub**: Version control and repository hosting platform.

## Getting Started

To get a local copy up and running, follow these steps:

### Installation

1. Clone the repository
   ```sh
   git clone https://github.com/your-username/your-repository.git
   ```
2. Navigate into the project directory
   ```sh
   cd manan-wasserstoff-FrontendTask
   ```
3. Install dependencies
   ```sh
   npm install
   ```
4. Start the development server
   ```sh
   npm run dev
   ```
5. Open your browser and navigate to
   ```sh
   http://localhost:3000
   ```
## Usage

- Navigate through folders in the sidebar to view files.
- Click on a file to open its corresponding editor or preview interface.
- Use the buttons to create new files or folders.
- Drag and drop notes within the .note files to change their categories.
