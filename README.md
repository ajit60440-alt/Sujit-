 @import url('https://fonts.googleapis.com/css2?family=Orbitron:wght@500&display=swap');

body {
  margin: 0;
  padding: 0;
  height: 100vh;
  background: radial-gradient(circle at center, #000 0%, #0a0a0a 70%, #111 100%);
  color: #fff;
  font-family: 'Orbitron', sans-serif;
  display: flex;
  justify-content: center;
  align-items: center;
}

.container {
  text-align: center;
  animation: fadeIn 2s ease-in-out;
}

.profile {
  width: 140px;
  height: 140px;
  border-radius: 50%;
  border: 3px solid #0ff;
  box-shadow: 0 0 25px #0ff;
  margin-bottom: 20px;
}

h1 {
  font-size: 2em;
  color: #0ff;
  text-shadow: 0 0 10px #0ff;
}

p {
  font-size: 1em;
  color: #ddd;
  margin: 10px 20px;
}

.buttons {
  margin-top: 20px;
}

.btn {
  text-decoration: none;
  color: #fff;
  padding: 12px 25px;
  border-radius: 30px;
  margin: 10px;
  display: inline-block;
  transition: all 0.3s ease;
}

.instagram {
  background: linear-gradient(45deg, #feda75, #fa7e1e, #d62976, #962fbf, #4f5bd5);
  box-shadow: 0 0 15px #d62976;
}

.download {
  background: linear-gradient(45deg, #00f5ff, #0066ff);
  box-shadow: 0 0 15px #00f5ff;
}

.btn:hover {
  transform: scale(1.1);
  box-shadow: 0 0 25px #0ff;
}

@keyframes fadeIn {
  from { opacity: 0; transform: translateY(20px); }
  to { opacity: 1; transform: translateY(0); }
}
