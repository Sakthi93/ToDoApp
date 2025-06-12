# 📝 Todo App

A full-stack Todo application built with:

- ⚙️ **FastAPI** (Backend)
- 🎨 **Vue 3** (Frontend)
- 🐳 Docker support
- 🔁 Git Submodules for modular repo structure

---

## 📂 Project Structure

```plaintext
todoapp/              # Main project repo
├── todobe/           # FastAPI Backend (as submodule)
└── todofe/           # Vue 3 Frontend (as submodule)


  **Clone the Repository (including submodules)**
git clone --recurse-submodules https://github.com/Sakthi93/todoapp.git

 **Backend Setup (FastAPI)**
cd todobe
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows
pip install -r requirements.txt
uvicorn main:app --reload

 **Frontend Setup (Vue 3)**
cd ../todofe
npm install
npm run dev

