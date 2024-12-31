# MEAN Docker Environment for SciCat and More 🐳✨  

This repository provides a Dockerized MEAN (MongoDB, Express, Angular, Node.js) stack environment to support **SciCat** and other applications. It simplifies setup and deployment for developers and system administrators.

---

## Features ✨  

- **Fully Dockerized MEAN Stack**: Easily deploy MongoDB, Express, Angular, and Node.js.  
- **SciCat Support**: Pre-configured for integration with SciCat and similar apps.  
- **Customizable Environment**: Extend and modify to suit additional applications.  

---

## Prerequisites 🛠️  

- **Docker** installed on your system.  
- **Docker Compose** installed.  

---

## Installation  

1. Clone the repository:  
git clone https://github.com/your-username/mean-docker-environment.git  
cd mean-docker-environment  

2. Build and start the Docker containers:  
docker-compose up --build  

3. Access the application in your browser:  
http://localhost:4200  

---

## Usage 🔧  

1. **MongoDB**:  
   - MongoDB is accessible on port `27017`.  
   - Default credentials can be configured in the `docker-compose.yml` file.  

2. **Node.js & Express**:  
   - Backend server runs on port `3000`.  
   - Modify routes in the `server/` directory.  

3. **Angular**:  
   - Frontend application runs on port `4200`.  
   - Modify Angular code in the `client/` directory.  

4. **Logs and Debugging**:  
   - View logs for all services:  
     docker-compose logs  

   - Access individual container logs:  
     docker logs <container_name>  

---

## File Structure 📂  

- `client/`: Angular application source code.  
- `server/`: Node.js and Express backend.  
- `docker-compose.yml`: Configuration for the MEAN stack.  
- `Dockerfile`: Dockerfile for Node.js backend.  
- `README.md`: Documentation for the repository.  

---

## Contributing 🤝  

1. Fork the repository.  
2. Create a new branch:  
git checkout -b feature/your-feature  

3. Commit your changes:  
git commit -m "Add your feature"  

4. Push the branch:  
git push origin feature/your-feature  

5. Open a pull request.  

---

## License 📝  

This project is licensed under the MIT License. See the LICENSE file for details.

---

**Deploy and scale your MEAN applications effortlessly with Docker!** 🐳✨  
