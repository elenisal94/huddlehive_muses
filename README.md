# Hidden Spaces 🏆

**3rd Place Winner - HuddleHive Women in Tech Hackathon #3**  
*Built in 24 hours at Octopus Energy, London*

---

## 🎯 The Vision

**Discover the spaces between places.**

In every city, there are corners of community waiting to be found—spaces that aren't home, aren't work, but feel like both. Hidden Spaces is a platform built to uncover and activate these "third spaces"—quiet courtyards, creative hubs, backroom bookshops, and neighbourhood nooks—where people can gather, connect, and belong.

---

## ✨ What We Built

Whether you're looking for somewhere to host a workshop, start a book club, or just vibe with your people, Hidden Spaces makes it easy to:

- **🔍 Discover** nearby third spaces that match your vibe and needs
- **📍 Map** new spots you stumble across, turning the city into a living community guide
- **🤝 Connect** with space owners and other community-minded folks  
- **📅 Organise** recurring events or pop-ups in cool, unexpected places

We're bridging the gap between people searching for connection and the underused spaces that can host it. This is more than just an app—it's a movement to reclaim and reimagine our cities.

---

## 🛠️ Tech Stack

**Frontend:** React 18, TypeScript, Vite, Tailwind CSS, Radix UI  
**Backend:** Python, Flask  
**Timeline:** 24 hours  
**Challenge:** Build a complete full-stack application from concept to demo

---

## 🚀 Running the Project

> **Note:** This was built in 24 hours during a hackathon - the code is technically solid but may have rough edges, incomplete features, and missing seed data.

### Prerequisites
- Node.js (v16+)
- Python 3.x
- Flask

### Backend Setup
```bash
# Clone the repository
git clone https://github.com/elenisal94/huddlehive_muses
cd huddlehive_muses

# Backend setup
cd backend
pip install -r requirements.txt
python app.py
```

### Frontend Setup
```bash
# In a new terminal, from project root
cd frontend
npm install

# Set up environment
cp .env.example .env
# Edit .env with your Flask API URL (default: http://localhost:5000)

# Start development server
npm run dev
```

The application will be available at `http://localhost:3000`

### Current Status
- ✅ Core functionality implemented and working
- ✅ React frontend with TypeScript and responsive design
- ✅ Flask API with essential endpoints
- ⚠️ Seed data not yet implemented - database starts empty
- ⚠️ Some features may be in development/prototype stage
- 🎯 Built for demonstration and proof of concept

### API Endpoints
The Flask backend provides these endpoints:
- `POST /api/auth/login` - User authentication
- `POST /api/auth/register` - User registration
- `GET /api/spaces/categories` - Space categories
- `GET /api/spaces` - List all spaces
- `GET /api/spaces/{id}` - Get specific space
- `POST /api/spaces` - Create new space
- `PUT /api/spaces/{id}` - Update space
- `DELETE /api/spaces/{id}` - Delete space

---

## 📁 Project Structure

```
huddlehive_muses/
├── frontend/           # React TypeScript frontend
│   ├── src/pages/     # Application pages
│   ├── src/components/ui/  # Reusable UI components
│   ├── src/lib/api.ts # API integration functions
│   └── vite.config.ts # Proxy configuration
└── backend/           # Flask Python backend
    └── app.py         # Main Flask application
```

---

## 👥 The Team

**Eleni Salamouri** - Frontend Development & API Integration  
**Miriam Duke** - Team Member  
**Jocelyn Soto** - Team Member  
**Sofia Bargues** - Team Member  
**Anastasiia Sokolova** - Team Member  

---

## 🏆 Achievement

**3rd Place** out of all competing teams at HuddleHive's Women in Tech Hackathon #3, hosted at Octopus Energy's London headquarters.

This project demonstrates our ability to:
- Collaborate effectively under extreme time pressure
- Build a complete full-stack application in 24 hours  
- Create meaningful solutions that address real community needs
- Present complex ideas clearly to judges and audiences
- Implement modern web technologies (React 18, TypeScript, Flask)

---

## 🌐 Deployment

The frontend is a static React app that can be deployed to:
- Vercel
- Netlify  
- AWS S3
- Any static hosting service

The Flask backend can be deployed to platforms like Heroku, Railway, or AWS.

---

## 🌟 The Impact

Hidden Spaces represents more than technical achievement—it showcases how technology can strengthen communities by making underused urban spaces more accessible and connected. The concept bridges urban planning insights with social technology, creating a platform that serves both space seekers and space providers.

---

*Built with ❤️ during HuddleHive Women in Tech Hackathon #3*
