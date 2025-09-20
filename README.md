body {
  font-family: 'Segoe UI', Arial, sans-serif;
  margin: 0;
  background: #f9f9f9;
  color: #222;
}
header {
  background: #0d47a1;
  color: #fff;
  padding: 24px 0 16px 0;
  text-align: center;
}
nav {
  margin-top: 8px;
  background: #1976d2;
  padding: 10px 0;
}
nav a {
  color: #fff;
  margin: 0 18px;
  text-decoration: none;
  font-weight: 500;
  font-size: 18px;
}
nav a:hover {
  text-decoration: underline;
}
.container {
  max-width: 800px;
  margin: 30px auto;
  background: #fff;
  border-radius: 10px;
  padding: 32px;
  box-shadow: 0 2px 8px rgba(0,0,0,0.08);
}
h1, h2, h3 {
  color: #0d47a1;
}
.btn {
  background: #43a047;
  color: #fff;
  border: none;
  padding: 14px 32px;
  border-radius: 6px;
  font-size: 20px;
  cursor: pointer;
  margin-top: 20px;
  display: inline-block;
  text-decoration: none;
}
.btn:hover {
  background: #2e7d32;
}
.price {
  font-size: 2.2em;
  font-weight: 700;
  color: #e91e63;
}
ul {
  line-height: 1.7;
}
.faq-q {
  font-weight: 600;
  margin-top: 18px;
}
footer {
  background: #222;
  color: #fff;
  text-align: center;
  padding: 18px 0;
  position: fixed;
  width: 100%;
  left: 0;
  bottom: 0;
}
@media (max-width: 850px) {
  .container { padding: 15px; }
}
@media (max-width: 600px) {
  nav { font-size: 16px; }
  .container { padding: 8px; }
}
