# Smart Route Finder
### Approximate Route Planner for Large Maps

**A Design and Analysis of Algorithms (DAA) Project – PBL 4**

---

## Author

**Harsh Saini**  
B.Tech – Computer Science Engineering (Artificial Intelligence & Machine Learning)

## Project Overview

Smart Route Finder is a Python-based route-planning application designed to explore efficient pathfinding on large-scale road networks.

The project focuses on the challenges of finding routes in large maps, where exact search algorithms may require significant computational resources. It explores graph-based route planning and approximate search strategies to improve search efficiency while maintaining acceptable route quality.

The application integrates geographical road network data from OpenStreetMap and provides an interactive interface for route planning and visualization.

## Key Features

- **Road Network Integration:** Retrieves geographical road network data using OpenStreetMap.
- **Interactive Visualization:** Displays road networks and calculated routes.
- **Location-Based Routing:** Supports route planning between selected geographical locations.
- **Graph-Based Processing:** Represents road networks using vertices and edges.
- **Algorithmic Optimization:** Explores efficient search strategies for large-scale route planning.
- **Performance Analysis:** Provides a foundation for evaluating route quality and computational efficiency.
- **Interactive Interface:** Built using Streamlit for an accessible user experience.

## Technology Stack

| Technology | Application |
|---|---|
| Python | Core development |
| Streamlit | User interface |
| OpenStreetMap | Geographical data |
| Overpass API | Road network retrieval |
| Graph Algorithms | Route computation |

## Project Architecture

The application follows a graph-based route-planning approach:

1. **Input:** User selects geographical locations.
2. **Data Acquisition:** Road network information is retrieved from OpenStreetMap.
3. **Graph Construction:** Road networks are represented as interconnected nodes and edges.
4. **Route Search:** Search algorithms identify a suitable path between the selected locations.
5. **Visualization:** The resulting route is presented through the application interface.

## Installation and Execution

### Prerequisites

- Python 3.10 or later
- Visual Studio Code (recommended)
- Internet connection for live OpenStreetMap data retrieval

### 1. Clone the Repository

```bash
git clone YOUR_REPOSITORY_URL
```

### 2. Navigate to the Project Directory

```bash
cd SMART-ROUTE-FINDER
```

### 3. Install Dependencies

```bash
py -m pip install -r requirements.txt
```

### 4. Launch the Application

```bash
py -m streamlit run main.py
```

### 5. Access the Application

Open the following address in your browser:

```text
http://localhost:8501
```

## Data Source

**OpenStreetMap (OSM)**

OpenStreetMap provides geographical and road network information used by the application.

**Overpass API**

The Overpass API is used to retrieve road network information based on geographical queries.

*Note: Live road network retrieval depends on internet connectivity and public Overpass API availability. Temporary server overload may affect data retrieval.*

## Design and Analysis of Algorithms

The project explores important DAA concepts:

- Graph representation and modelling
- Vertices, edges and weighted graphs
- Shortest-path algorithms
- Heuristic-based search
- Exact versus approximate solutions
- Time and space complexity
- Route quality and execution-time analysis
- Scalability of graph search algorithms

## Future Scope

- Implementation of additional heuristic search strategies.
- Offline road network support.
- Improved caching and network retrieval.
- Benchmarking across different map sizes.
- Advanced route optimization.
- Improved performance for large-scale geographical networks.

## Academic Information

| Field | Details |
|---|---|
| Project Title | Smart Route Finder |
| PBL | PBL 4 – Approximate Route Planner for Large Maps |
| Subject | Design and Analysis of Algorithms |
| Author | Harsh Saini |
| Programming Language | Python |
| Interface | Streamlit |

---

## Author

**Harsh Saini**

B.Tech Computer Science Engineering (AI & ML)

Developed as part of the academic Project-Based Learning curriculum, demonstrating the application of graph algorithms and computational optimization to real-world route-planning problems.

---

*If you find this project useful, consider giving the repository a star.*
