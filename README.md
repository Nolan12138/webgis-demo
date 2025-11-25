# Chinese province and city GeoshpJSON datas system
A modern, responsive frontend project built with Vue 3, focused on processiong and accessing Chinesr provincial and municipal GeoshpJSON data. It supports core functionalities such as Geoshp data download, city weather forecasting, map visulization and export,and location acquisition——with a strong emphasis on preformance,maintainability, and user experience.

## 🌟 Key Features
- **Dynamic Data Integration:** Implements real-time data fetching via Axios,integrating with Aliyun's Chinese Geoshp API and Amap's Chinese weather API to enable seamless access to geographic data.
- **Reusable Map Components:** Develops a library of reusable components powered by Leaflet, which parses Geoshp data, renders map layer, supports smooth switching between provincial and municipal layers, draws a custom pattern and downloads this area.
- **User Authentication logic:** incorporates login/logup functionality with verification logic based on localStorage. It uses router guards to restrict unauthorized access, ensuring users must log in before accessing map page.
- **Optimized Component Communication:** Utilizes props/emit for data exchange betweent parent and child components, and leverages expose/ref to enable parent components to call child components--enhancing modularity and interactivity.
- **Efficient Styling:** Integrates Element Plus with Al-assisted tools to streamline CSS development, ensuring a consistent and visually coherent UI.

## 🛠️ Tech Stack
| Category               | Technologies                                                                 |
|------------------------|------------------------------------------------------------------------------|
| Core Framework         | Vue 3 (Composition API + `<script setup>`)                                   |
| Build Tool             | Vite (for fast development and optimized production builds)                  |
| State Management       | Pinia (official replacement for Vuex in Vue 3)                               |
| Routing                | Vue Router 4                                                                 |
| UI Component Library   | [Element Plus]                      |
| HTTP Client            | Axios (with request/response interceptors)                                   |               |
| Linting & Formatting   | ESLint + Prettier (to maintain code quality and consistent style)            |
| Testing (可选)         | Vitest + Testing Library Vue (unit tests for core components)                |

## 🚀 Quick Start
### Prerequisites
- Node.js (v16+ recommended)
- npm / yarn / pnpm

### Installation & Run
```bash
# Clone the repository
git clone https://github.com/[your-username]/[your-repo-name].git

# Navigate to project directory
cd [your-repo-name]

# Install dependencies
npm install
# or yarn install / pnpm install

# Run development server (hot reload)
npm run dev

# Build for production (optimized bundle)
npm run build

# Preview production build
npm run preview
