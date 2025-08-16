# Global Disaster Relief DBMS 🌍

A world-changing **Database Management System (DBMS)** project designed to optimize **global disaster relief efforts** using advanced database concepts, real-time data integration, and AI-driven insights.  

This project proves **expert-level implementation of DBMS** concepts — normalization, transactions, indexing, concurrency, replication, recovery, and distributed systems — while solving a **real global challenge**: how to coordinate **supplies, shelters, and volunteers** during natural disasters.

---

## 🚀 Vision

Imagine a system where during a **flood, earthquake, or hurricane**:
- Emergency supplies (food, water, medicine) are tracked **in real time**  
- Volunteers are automatically matched with nearby shelters in need  
- Government & NGOs see **one unified dashboard** to avoid duplication and delays  
- Predictive analytics warns of **supply shortages before they happen**

That’s exactly what this project delivers. ✅  

---

## 📂 Repository Structure

```bash
Global-Disaster-Relief-DBMS/
│
├── phase1_schema_design/        # ER diagrams, SQL schemas, initial dataset
│   ├── schema.sql
│   ├── er-diagram.png
│   └── sample_data.sql
│
├── phase2_advanced_dbms/        # Indexing, triggers, transactions, constraints
│   ├── triggers.sql
│   ├── indexing_examples.sql
│   └── transactions_demo.sql
│
├── phase3_distributed_system/   # Replication, sharding, distributed queries
│   ├── replication_config.md
│   ├── sharding_plan.md
│   └── distributed_queries.sql
│
├── phase4_api_integration/      # REST API to interact with DB
│   ├── app.py
│   ├── requirements.txt
│   └── routes/
│       ├── supplies.py
│       ├── volunteers.py
│       └── shelters.py
│
├── phase5_ai_insights/          # Machine learning models for predictions
│   ├── predict_shortages.py
│   └── volunteer_matching.py
│
├── docs/                        # Documentation
│   ├── roadmap.md
│   └── future_scope.md
│
└── README.md
🔑 Features (By Phase)
✅ Phase 1: Schema & Core DB
Design entities: supplies, volunteers, shelters, disasters, aid requests
Apply 3NF normalization for efficient querying
Insert sample data for disaster scenarios
✅ Phase 2: Advanced DBMS Concepts
Implement triggers (auto-update stock when aid is delivered)
Add indexes for faster querying
Use transactions & rollback for consistency
✅ Phase 3: Distributed Database
Simulate multi-region DB replication
Add sharding by geography (Asia, Europe, Africa, Americas)
Enable high availability during disasters
✅ Phase 4: API + Application Layer
Build a Flask/Django REST API
Endpoints:
/supplies → track & allocate resources
/volunteers → register and match helpers
/shelters → manage shelters & capacity
✅ Phase 5: AI & Predictive Insights
Predict supply shortages based on demand trends
Match volunteers automatically to nearby shelters
Visualize data with dashboards (Streamlit / React + Charts)
📊 Example Use Case
A flood hits Kerala 🌊
Volunteers register via the API
Shelters update their real-time capacity
Supplies (rice, medicine, blankets) are allocated automatically
AI warns that medical kits will run out in 48 hours → alert triggered
🛠️ Tech Stack
Database: PostgreSQL / MySQL (with sharding & replication)
Backend: Flask / Django REST Framework
AI/ML: Python (scikit-learn, TensorFlow/PyTorch for predictions)
Visualization: Streamlit / ReactJS + Charts
Hosting: Docker + Cloud (AWS / GCP / Azure)
📌 Roadmap
 Design core schema & ER diagram
 Implement advanced DBMS concepts (triggers, transactions, indexing)
 Deploy distributed system with replication & sharding
 Build REST API for global use
 Add AI-powered predictions & dashboards
🌟 Impact
If completed fully, this project has the potential to:
Save millions of lives by reducing disaster response delays
Become a reference project for future DBMS engineers
Be scaled into a UN / Red Cross level system
Prove world-class expertise in DBMS implementation
🤝 Contributing
Contributions are welcome!
Fork the repo, make changes, and open a PR.
📜 License
MIT License – feel free to use and modify this for learning or research.
👨‍💻 Author
Safal Gupta
CSE (IoT), VIT Vellore
Driven by AI, DBMS, and real-world impact
