# 📌 3D Digital Cultural Artifact Museum

A web-based application that allows users to interactively explore cultural artifacts in **3D**, including rotation, zoom, and detailed viewing, supported by concise and easy-to-understand explanations.

---

# 📅 Week 4 Development Log

## 🔹 Sprint Goal
Develop a **basic functional prototype** of the 3D artifact viewer, including:
- Loading and displaying a 3D model  
- Implementing user interactions (rotate, zoom)  
- Displaying artifact descriptions  

---

## 🔹 Must-have Features

- View cultural artifacts in **3D from different angles**  
- Use simple gestures to:
  - Rotate  
  - Zoom  
  - Explore details  
- Read **short and easy explanations** about each artifact  

---

## 🔹 Team Role Assignments

| Role | Main responsibility | Assessed through |
|------|--------------------|------------------|
| Product Manager | Sprint goals, standups, team direction | Dev Log quality, Checkpoint prep |
| UX / UI Designer | Figma mockups, user flows, visual design | Evidence links, usability test results |
| Frontend Developer | What users see — screens, buttons, interactions | GitHub commits, working features |
| Backend Developer | Data, APIs, server logic | GitHub commits, Technical Documentation |
| User Researcher | Interviews, usability sessions, findings | Validation Report, interview notes |
| Technical Lead | Architecture decisions, code quality, repo | Technical Documentation, code review |
| Documentation & IP | Dev Log quality, Technical Docs, IP section | Dev Log, Week 11 Portfolio |

---

## 🔹 Product Overview (Based on PRD)

### Problem Statement
Current cultural heritage platforms are mostly static, relying on images and text. This limits users’ ability to understand the shape and details of artifacts. Additionally, physical museum visits are not always accessible, while existing online platforms lack engagement.

---

### Target Users
- University students  
- Young users interested in cultural heritage, design, or history  
- Users who prefer **interactive digital experiences** on mobile or desktop  

---

### Product Objective
Build a website that allows users to:
- Explore artifacts in 3D  
- Rotate and zoom easily  
- Read short and clear explanations  
- Experience more engaging and active learning  

---

## 🔹 User Stories

1. As a university student, I want to view artifacts in 3D so that I understand their real structure.  
2. As a curious learner, I want to rotate and zoom easily to inspect details.  
3. As a new user, I want simple controls so I can use the system without instructions.  
4. As a busy student, I want to access artifacts online anytime.  
5. As a learner, I want short explanations to quickly understand artifacts.  
6. As an engaged user, I want an interactive experience instead of static images.  

---

## 🔹 Core Features

- 3D artifact viewer  
- Rotate and zoom interaction  
- Touch + mouse gesture support  
- Short artifact descriptions  
- Responsive design (mobile + desktop)  
- Unified artifact detail page (3D + text)  

---

## 🔹 Technical Architecture

### Front-end
- HTML, CSS, JavaScript  
- React (component-based UI)  
- Three.js (3D rendering)  
- Responsive design  

### Back-end
- Node.js + Express  
- Handles:
  - Artifact data API  
  - Content delivery  
  - User interaction analytics  

### Data Storage
- Database: MongoDB / MySQL  
- Stores:
  - Artifact name  
  - Description  
  - Category / era  
  - Model path  
  - Analytics data  

- File Storage:
  - 3D models (.glb)  
  - Images  

---

## 🔹 Individual Contribution

**Name:** [Your Name]  

During this session, I integrated Three.js into the React framework and implemented the initial 3D model viewer. I also configured interaction controls including rotation and zoom, ensuring that users can intuitively explore artifacts.

---

## 🔹 Project Status

**🟢 On Track**

The project is progressing according to plan. Core 3D interaction functionality has been implemented, and no major technical blockers have been identified.

---

## 🔹 Success Criteria

- Users can rotate and zoom within **30 seconds without instruction**  
- ≥ 80% users complete core interactions successfully  
- Average exploration time: **2–3 minutes per artifact**  
- ≥ 90% users can describe one artifact detail after use  

---

## 🔹 MVP Scope

- Homepage  
- Artifact gallery  
- One artifact detail page  
- 3D viewer (rotate + zoom)  
- Short descriptions  
- Basic analytics tracking  

---

## 🔹 Risks Identified

### 1. 3D Model Performance
Large models may cause slow loading and lag.

**Mitigation:**
- Use `.glb` format  
- Compress models  
- Reduce polygon count  

---

### 2. Interaction Complexity
Users may find controls confusing.

**Mitigation:**
- Keep controls simple (drag = rotate, scroll = zoom)  
- Add minimal UI hints  

---

## 🔹 Next Steps (Week 5)

- Connect front-end with back-end API  
- Expand artifact dataset  
- Improve UI/UX design  
- Optimize performance  
- Implement analytics tracking  

---

## 🔹 Notes

This project is developed as part of a university coursework focusing on **interactive systems, user-centered design, and digital innovation in cultural heritage**.
