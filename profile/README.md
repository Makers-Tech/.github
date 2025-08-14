# 🎯 Project Objective

This project was developed by **Ricardo Urbina**/[Ricardo965](https://github.com/Ricardo965) to meet the challenge of creating an advanced AI chatbot for **Makers Tech**, a technology e-commerce company. The primary objective was to build a system that enhances the customer journey by providing real-time, personalized information about product inventory, features, and pricing through an intelligent, conversational interface.

The solution successfully delivered not only the core chatbot functionality but also **both optional bonus features**: a personalized recommendation engine and an advanced administrative dashboard, providing a comprehensive, high-quality solution ready for presentation.

## ✨ Key Features Across the Platform

* **🤖 Intelligent Conversational AI**

  * A floating chat widget provides a seamless, non-intrusive user experience.
  * Engages users with an AI-guided questionnaire to understand their needs for usage, budget, and priorities.
  * Answers real-time queries about product availability and specifications by connecting directly to the backend API.

* **💡 Personalized Recommendations**

  * Fulfills the optional project goal of a recommendation system.
  * The AI translates user preferences into technical search criteria (tags).
  * Presents users with a curated list of products that match their needs, complete with clickable links to detail pages.

* **📊 Advanced Admin Dashboard**

  * Successfully implements the optional dashboard feature for business intelligence.
  * Displays key performance indicators (KPIs) like total inventory value and total stock units.
  * Features rich data visualizations, including charts for stock-by-category and a table for low-stock alerts.

* **🖥️ Modern E-commerce Frontend**

  * A fully-featured client application with a professional landing page, a complete product catalog, and dynamic detail pages for each item.
  * Built with a focus on user experience, responsiveness, and performance.

---

## 📂 Our Repositories

This solution is built on a modern, decoupled architecture, consisting of a backend service and a frontend client.

| Repository | Description                                                                                                                                                                                          |
| :--------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `frontend` | The client-facing application built with **Next.js** and **TypeScript**. It provides the complete user interface, including the product catalog, dashboard, and the interactive AI chat widget.      |
| `backend`  | The core API and AI service built with **FastAPI** and **Python**. It handles all business logic, database interactions, and orchestrates the AI conversation using **LangChain** and **LangGraph**. |

---

## ⚙️ Technology Ecosystem

The platform leverages a powerful combination of Python for AI and data processing, and TypeScript/Next.js for a modern, interactive user experience.

| Area                       | Technologies Used                                                  |
| :------------------------- | :----------------------------------------------------------------- |
| **Frontend (Client-Side)** | Next.js, React, TypeScript, Tailwind CSS, shadcn/ui, Framer Motion |
| **Backend (Server-Side)**  | Python, FastAPI, SQLModel, Uvicorn, LangChain, LangGraph           |
| **Database**               | SQLite (for development)                                           |

---

## 🚀 Getting Started

To run the entire platform locally, you must start both the backend and frontend servers.

1. **Clone Both Repositories**
   Clone both the `frontend` and `backend` repositories to your local machine.

2. **Start the Backend Server**

   * Navigate into the `backend` directory.
   * Follow the instructions in its `README.md` to set up the environment, install dependencies, and start the FastAPI server.
   * By default, it will run on `http://localhost:8000`.

3. **Start the Frontend Server**

   * Navigate into the `frontend` directory.
   * Follow the instructions in its `README.md` to install dependencies and start the Next.js development server.
   * By default, it will run on `http://localhost:3000`.

4. **Access the Application**
   Open your browser and navigate to **`http://localhost:3000`** to use the Makers Tech application.
