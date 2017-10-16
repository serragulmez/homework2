# homework2void setup(){
  // set window size
  size(600,600);
}
void draw(){
  background(#764F50);
  
  //write text
  fill(#580304);
  text("hiii",mouseX,mouseY);
  
  //draw ellipse with mouse cord.
  noStroke();
  fill(#95595A);
  ellipse(150,400,300,300);
  
  noStroke();
  fill(#95595A);
  ellipse(400,10,400,400);
  
  //draw rect. (background)
  noStroke();
  fill(#95595A);
  rect(100,400,600,400);
  
  // draw rect. (robot)
  strokeWeight(6);
  stroke(#500305);
  fill(#902426);
  rect(150,420,300,100);
  
  //draw legs
   strokeWeight(6);
  stroke(#500305);
  fill(#902426);
  rect(200,420,100,40);
  
  strokeWeight(6);
  stroke(#500305);
  fill(#902426);
  rect(300,420,100,40);
  
  
   strokeWeight(6);
  stroke(#500305);
  fill(#902426);
  rect(250,320,100,100);
  
  strokeWeight(6);
  stroke(#500305);
  fill(#902426);
  rect(200,120,200,200);
  
  // draw eyes
  strokeWeight(4);
  stroke(#717070);
  fill(#05075F);
  rect(240,180,40,40);
  
  strokeWeight(4);
  stroke(#7469F7);
  fill(#4D488E);
  rect(260,180,15,15);
  
  
  strokeWeight(4);
  stroke(#717070);
  fill(#05075F);
  rect(320,180,40,40);
  
  strokeWeight(4);
  stroke(#7469F7);
  fill(#4D488E);
  rect(340,180,15,15);
  
  //draw mouth
  strokeWeight(8);
  stroke(#05075F);
  fill(#460203);
  rect(260,260,80,20);

  // draw teeth
  strokeWeight(6);
  stroke(#FFFFFF);
  fill(#FFFFFF);
  rect(286,260,10,10);
  
  strokeWeight(6);
  fill(#FFFFFF);
  rect(304,260,10,10);
  
  strokeWeight(6);
  stroke(#FFFFFF);
  fill(#FFFFFF);
  rect(306,262,4,4);
  
  strokeWeight(6);
  stroke(#FFFFFF);
  fill(#FFFFFF);
  rect(288,262,4,4);
  
