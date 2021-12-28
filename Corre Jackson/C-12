var path,boy, leftBoundary,rightBoundary;
var pathImg,boyImg;
var i;

function preload(){
path=loadImage("path.png");
boy_running = loadAnimation("jake1.png","jake3.png","jake4.png");

 
}

function setup(){
  
  createCanvas(400,400);
  path = createSprite(50,180,20,50);
  path = loadImage("path.png");
path.velocityY=5;
path.scale=1.2;

boy = createSprite(50,130,20,50);
boy_running = loadAnimation("jake1.png","jake3.png","jake4.png");
boy.scale=0.08;
  


leftBoundary=createSprite(0,0,100,800);
leftBoundary.visible = false;
 


rightBoundary=createSprite(410,0,100,800);
leftBoundary=createSprite(0,0,100,800);
}

function draw(MouseX) {
  background(0);
  path.velocityY = 4;
  
boy=velocityX=2

  
  edges= createEdgeSprites();
  boy.collide(edges[3]);
  boy.collide(leftBoundary); 
  boy.collide(rightBoundary);

  
  
  
  if(path.y > 400 ){
    path.y = height/2;
  }
  
  drawSprites();
}
