/* Container for the neon border */
.neon-container {
  position: relative;
  width: 80%; /* Adjust width as needed */
  height: 300px; /* Adjust height as needed */
  margin: 50px auto; /* Center the container */
  padding: 20px;
  border: 4px solid transparent;
  border-radius: 15px;
  background: rgba(0, 0, 0, 0.8); /* Dark background for contrast */
  box-shadow: 0 0 20px rgba(255, 0, 0, 0.8), 0 0 40px rgba(0, 255, 0, 0.8), 0 0 60px rgba(0, 0, 255, 0.8);
  animation: neon-glow 3s linear infinite;
  overflow: hidden;
}

/* Neon border animation */
@keyframes neon-glow {
  0% {
    box-shadow: 0 0 20px rgba(255, 0, 0, 0.8), 0 0 40px rgba(0, 255, 0, 0.8), 0 0 60px rgba(0, 0, 255, 0.8);
  }
  33% {
    box-shadow: 0 0 20px rgba(0, 255, 0, 0.8), 0 0 40px rgba(0, 0, 255, 0.8), 0 0 60px rgba(255, 0, 0, 0.8);
  }
  66% {
    box-shadow: 0 0 20px rgba(0, 0, 255, 0.8), 0 0 40px rgba(255, 0, 0, 0.8), 0 0 60px rgba(0, 255, 0, 0.8);
  }
  100% {
    box-shadow: 0 0 20px rgba(255, 0, 0, 0.8), 0 0 40px rgba(0, 255, 0, 0.8), 0 0 60px rgba(0, 0, 255, 0.8);
  }
}

/* Inner content styling */
.neon-content {
  color: #fff;
  font-family: Arial, sans-serif;
  text-align: center;
  padding: 20px;
}

/* Neon text glow */
.neon-content h3 {
  color: #00ffcc;
  text-shadow: 0 0 5px #00ffcc, 0 0 10px #00ffcc, 0 0 20px #00ffcc, 0 0 40px #00ffcc;
}

/* Neon social icons */
.neon-content img {
  border: 2px solid #00ffcc;
  border-radius: 10px;
  box-shadow: 0 0 10px #00ffcc, 0 0 20px #00ffcc;
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.neon-content img:hover {
  transform: scale(1.2);
  box-shadow: 0 0 20px #00ffcc, 0 0 40px #00ffcc;
}
