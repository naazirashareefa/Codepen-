# Codepen-
This project is a **ReactJS-based live code editor**, similar in functionality to platforms like CodePen or JSFiddle. It allows users to write and edit **HTML, CSS, and JavaScript** code in real time and instantly view the output in a live preview pane. The application is built using modern React practices, including **functional components**, **hooks**, and a shared **context API** (`DataProvider`) for state management.

The main interface is divided into two sections: the **Code Editor** and the **Result Preview**. The editor section consists of three code input panels, each tailored for HTML, CSS, and JavaScript. These editors are implemented using the custom `Editor` component, which handles user input and visual layout, with a distinct color scheme for each language for better readability. The editors are placed horizontally within a flex container for a clean and intuitive layout.

The **live preview** is implemented using an `iframe` inside the `Result` component. When users type code in any of the panels, the combined HTML, CSS, and JS is dynamically injected into the iframe using the `srcDoc` attribute. A short delay of 250ms is added to debounce the input changes, ensuring smooth performance without lag or flicker. This gives users instant feedback on their code changes, simulating a live browser environment.

Styling is handled using both **Material-UI (MUI)** components and custom CSS, creating a sleek dark-themed interface optimized for coding. The layout adapts well to different screen sizes, making it responsive and user-friendly.

This project is ideal for beginners learning web development, coding instructors, or developers creating simple demos. It showcases the practical use of React for building dynamic, interactive UIs and highlights the power of combining state management, user interaction, and real-time rendering within a single-page application.
