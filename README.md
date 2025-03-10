# TF2 Stats Site  

A web application that retrieves and displays **Team Fortress 2** player statistics using the **Steam API**. Built with **Django** for the backend and **React** for the frontend, this site allows users to enter a Steam ID and view their in-game performance metrics.  

## Features  
- Search for player stats by entering a **Steam ID**  
- View essential TF2 stats, including **kills, deaths, headshots, and K/D ratio**  
- Modern and responsive **React UI** with real-time data fetching  
- Backend powered by **Django REST Framework (DRF)**  

## 🛠 Tech Stack  
- **Frontend:** React, Tailwind CSS  
- **Backend:** Django, Django REST Framework  
- **API:** Steam API  


## Setup & Installation  

 
```bash
# Clone the repository
git clone https://github.com/hungwn2/tf2-stats-site.git
cd tf2-stats-site/backend

# Create and activate a virtual environment
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`

# Install dependencies
pip install -r requirements.txt

# Run the Django server
python manage.py runserver
