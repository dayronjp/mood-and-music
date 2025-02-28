# Mood & Music 🎵

Mood & Music is a full-stack project that enables users to log their mood and receive personalized music suggestions through the **Spotify API**. This project is designed to be simple and functional, utilizing only **HTML, CSS, JavaScript, Node.js, and RESTful API development with Node.js**. TypeScript and Docker will be incorporated only if necessary.

---

## Overview

Mood & Music offers an intuitive user experience where individuals can select their current mood and instantly obtain a music recommendation. The application is built using a minimal technology stack to focus on core functionality while remaining accessible for beginners.

---

## Technologies Used

### **Frontend**
- ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5)
- ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3)
- ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript)

**Key Features:**
- A simple, responsive interface for mood selection.
- Direct integration of a Spotify Embed Player for music playback.

### **Backend**
- ![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs)
- ![API REST](https://img.shields.io/badge/API%20REST-000000?style=for-the-badge)

**Key Features:**
- RESTful API built with Node.js and Express.
- An endpoint that receives the user's mood and queries the Spotify API.
- Returns a Spotify Embed link to be rendered on the frontend.

### **Optional Extras**
- ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript)
- ![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker)

**Usage:**
- **TypeScript** may be adopted for enhanced type safety in the backend.
- **Docker** will be used if containerization is required for deployment.

---

## System Flow

1. **User Interaction:**  
   The user accesses the site and selects their current mood via a straightforward interface.

2. **API Request:**  
   The frontend sends the selected mood to the backend through a RESTful API endpoint.

3. **Music Recommendation:**  
   The backend processes the mood input and queries the Spotify API to retrieve a matching song.

4. **Response Delivery:**  
   A Spotify embed link is returned, enabling the frontend to display an embedded player for music playback.

5. **Playback:**  
   The user listens to the recommended song directly on the website via the embedded Spotify player.

---

## Deployment & Hosting

- **Frontend:**  
  The static frontend can be deployed on platforms such as **Vercel** or **Netlify**.

- **Backend:**  
  The Node.js backend can be hosted on services like **Railway** or **Render**.

*Note: A database is not required in this initial version since the application solely queries the Spotify API without persisting user data.*

---

## Spotify API Integration

Mood & Music leverages the Spotify API to obtain music recommendations based on the user's mood. The music is played using an **iframe embed** of the Spotify player, ensuring a seamless listening experience directly within the application.

🔗 [Spotify Web API Documentation](https://developer.spotify.com/documentation/web-api/)

---

This documentation outlines the project structure and core functionalities of Mood & Music, ensuring a clear and professional implementation. For any inquiries or further information, please feel free to reach out.
