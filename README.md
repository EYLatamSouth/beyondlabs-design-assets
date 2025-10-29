# 📦 Design Assets
> Design assets and resources for Design Assets, containing UI components, icons, and brand materials.

## 🚀 Features

- 🎨 Design System - Consistent UI components
- 📚 Asset Library - Comprehensive design resources
- ✨ Modern Architecture - Clean and maintainable codebase
- 🔧 Easy Configuration - Simple setup and deployment

## 📋 Prerequisites

Before you begin, ensure you have met the following requirements:

### Required Software:
- Python version (analyze project for minimum required version)
- Dependencies from `requirements.txt`, `pyproject.toml`, or equivalent

- Node.js version (check `.nvmrc`, `package.json` engines field)
- npm/yarn/pnpm (based on lock files present)
- Dependencies from `package.json`

- System dependencies (databases, message queues, etc.)
- External services or APIs required

### Optional but Recommended:
- Development tools (Docker, Git, etc.)

## 🔧 Installation

### For Python projects:
```bash
# Clone the repository
git clone https://github.com/EYLatamSouth/beyondlabs-design-assets
cd beyondlabs-design-assets

# Using UV (if pyproject.toml exists)
uv sync

# OR using pip
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt

# Configure environment variables (if .env.example exists)
cp .env.example .env
```

### For Node.js projects:
```bash
# Clone the repository
git clone https://github.com/EYLatamSouth/beyondlabs-design-assets
cd beyondlabs-design-assets

# Install dependencies (detect package manager from lock files)
npm install    # if package-lock.json exists
# OR
yarn install   # if yarn.lock exists
# OR
pnpm install   # if pnpm-lock.yaml exists

# Configure environment variables (if .env.example exists)
cp .env.example .env
```

## 💻 Usage

### Basic Usage:

```bash
# Azure Functions
func start

# FastAPI
uv run uvicorn [module]:app --reload --port [PORT]

# Flask
uv run flask run --port [PORT]

# Standalone scripts
uv run python [main_script.py]
```

```bash
# Development
npm run dev    # or yarn dev / pnpm dev

# Production
npm start      # or yarn start / pnpm start

# Build (if applicable)
npm run build  # or yarn build / pnpm build
```

## 🏗️ Project Structure

```
Design Assets/
├── 📄 README.md
├── 📁 beyondactions/
│   ├── 📁 logo/
├── 📁 beyondfunding/
│   ├── 📁 illustrations/
│   ├── 📁 logo/
├── 📁 beyondlabs/
│   ├── 📁 logo/
├── 📁 beyondpass/
│   ├── 📁 logo/
├── 📁 beyondscraping/
│   ├── 📁 logo/
├── 📁 compass-ui/
│   ├── 📁 logo/
├── 📁 digitalsquads/
│   ├── 📁 logo/
├── 📁 ey/
│   ├── 📁 logo/
├── 📁 wavespace-garage/
│   ├── 📁 logo/
│   ├── 📁 wallpaper/
├── 📁 wavespace-skyline/
│   ├── 📁 logo/
```

### Environment Variables:
Create a `.env` file in the root directory with the following variables:

```env
# [CATEGORY: e.g., API Keys]
[VARIABLE_NAME]=description_of_variable

# [CATEGORY: e.g., Database]
[VARIABLE_NAME]=description_of_variable
```

- Variable name
- Description
- Example value (if safe)
- Required/Optional status

### For REST APIs:
**[PYTHON - FASTAPI]**:
- **Interactive Docs**: `http://localhost:[PORT]/docs`
- **ReDoc**: `http://localhost:[PORT]/redoc`

**[NODE.JS - EXPRESS WITH SWAGGER]**:
- **Swagger UI**: `http://localhost:[PORT]/api-docs`

### Available Endpoints:
- `[METHOD] /endpoint` - Description

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

Made by **Beyondlabs**
