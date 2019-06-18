# p5.js_learning-course
Lynda.com_ Coding for Visual Learners: Learning JavaScript from Scratch



  function setup(){
    
    
  createCanvas (400,300
               );
  rectMode(CENTER);
}




function draw() {
  background(1, 186, 240);
  var x= width/2;
  var y= hight/2;
  
  
  //circle
  fill(237, 34, 93);
  noStroke();
  ellipse(x, y, 200, 200);

  //rectangle
  fill(255);
  rect(x, y, 150, 30);
}
