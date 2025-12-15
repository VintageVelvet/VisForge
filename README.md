# VisForge

VisForge is a **schema-driven data visualization prototyping platform**.

It is designed to:
- Separate data processing from visualization rendering
- Provide reusable visualization schemas
- Help explore the application boundaries of different chart types

This project is both:
- A personal playground for data visualization engineering
- A long-term extensible foundation for web-based visualization systems

---

## Architecture Overview
- Data Source
- ↓
- Backend (Python / FastAPI)
- ↓ Visualization Schema (JSON)
- Frontend (ECharts / JS)

---

## Core Concepts

- **Backend** handles data preparation and normalization
- **Schema** defines the contract between data and visualization
- **Frontend** renders charts based on schema, independent of data source

---

## Project Status

🚧 **Early prototype (v0)**  
The project is under active design and experimentation.

---

## Roadmap (Initial)

- [ ] Define Visualization Schema v0
- [ ] Backend data preparation API (FastAPI)
- [ ] Frontend schema-based chart renderer (ECharts)
- [ ] Example datasets and chart configurations

---

## License

MIT License
