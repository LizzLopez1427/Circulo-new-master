float i = 0;

void setup(){
size (500, 400);
background(10, 80, 100);
}

void draw(){
  stroke(255, 255, 255);
  fill(160, 220, 90);
  ellipse(width/2, height/2, width, height);
  translate(width/2, height/2);
  fill(160, 210, 230);
  rect(245, 200, 10, 240);
  rotate(-i/2);
  noStroke();
  fill(255, 255, 255);
  ellipse(100, 100, 70, 70);
  i = i + 0.03;
}
