
body {
  font-family: broadway;
  text-align: center;
  background: linear-gradient(to right,#43cea2, #185a9d);
  margin: 0;
  padding: 20px;
}

h1 {
  color: orange;
  margin-bottom: 20px;
}
.gallery {
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
  gap: 20px;
}

.image {
  overflow: hidden;
  border-radius: 10px;
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.image img {
  width: 250px;
  height: 180px;
  object-fit: cover;
  transition: transform 0.3s ease;
}

.image:hover {
  transform: scale(1.05);
  
}

.image:hover img {
  transform: scale(1.1);
}
