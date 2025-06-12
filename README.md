<!-- PROJECT SHIELDS -->
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]

<a id="readme-top"></a>


# EduBox, The Linux Deployment Platform! 

<div align="center">
  <br>
  <img src="https://github.com/user-attachments/assets/d05b38e2-a492-47e7-9e11-1df66947d03e" alt="EduBox" width="400">
  <br><br>
</div>

EduBox is a platform designed and implemented for the automated deployment of containerized Linux environments with a noVNC desktop interface, enabling users to learn Linux and run code in Python, Node.js, Java, and more.

## Demo 🎥

https://github.com/zk2k2/edubox/assets/98645757/dfac3356-1e9a-4c67-8cdf-69f48bf4b2b1





## ✨ Features
- **Flexible Deployment**: Deploy environments with various base images.
- **Programming Environment Setup**: Easily install Python, Node.js, and Java.
- **Multiple Configurations**: Deploy multiple environments with different setups.
- **User-Friendly**: Designed to be approachable for students with varying levels of technical expertise.

## 🚀 Getting Started

### ✅ Prerequisites
Ensure you have the following installed on your system:
- Java (for backend)
- Node.js and npm (for frontend)
- Python and Flask (for API)
- Windows Subsystem for Linux (WSL) or a similar Linux environment

### 🛠 Backend Setup
1. **Navigate to the backend directory:**
    ```sh
    cd backend/java
    ```
2. **Run the Spring Boot backend application:**
    ```sh
    ./mvnw spring-boot:run
    ```

### 💻 Frontend Setup
1. **Navigate to the frontend directory:**
    ```sh
    cd frontend
    ```
2. **Start the frontend application:**
    ```sh
    npm start
    ```

### 🔧 VM API Setup
1. **Open a WSL session and run the following commands:**
    ```sh
    root@/edubox# cd vm_backend/Api
    root@/edubox/vm_backend/Api# flask --app api.py run --host=0.0.0.0
    ```

This setup will get EduBox up and running on your local machine, allowing you to deploy and manage Linux environments for educational purposes. If you encounter any issues, please refer to the documentation or contact our team.

## 🤝 Contributing
We welcome contributions to improve EduBox! Please fork the repository and submit pull requests for review.

## 📜 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📧 Contact
For more information, please contact me via email.


<!-- MARKDOWN LINKS & IMAGES -->
[contributors-shield]: https://img.shields.io/github/contributors/zk2k2/edubox.svg?style=for-the-badge
[contributors-url]: https://github.com/zk2k2/edubox/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/zk2k2/edubox.svg?style=for-the-badge
[forks-url]: https://github.com/zk2k2/edubox/network/members
[stars-shield]: https://img.shields.io/github/stars/zk2k2/edubox.svg?style=for-the-badge
[stars-url]: https://github.com/zk2k2/edubox/stargazers
[issues-shield]: https://img.shields.io/github/issues/zk2k2/edubox.svg?style=for-the-badge
[issues-url]: https://github.com/zk2k2/edubox/issues
[license-shield]: https://img.shields.io/github/license/zk2k2/edubox.svg?style=for-the-badge
[license-url]: https://github.com/zk2k2/edubox/blob/main/LICENSE
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/zied-kharrat

