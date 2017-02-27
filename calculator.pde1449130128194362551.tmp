double answer=0,num1=0,num2=0;
double x,y;
int flag1=0;
String s="";

void setup() {
  size(600,800);
  background(0);
  
}

void draw() {
  background(0);
  stroke(255);
  fill(120,0,120);
  rect(100,100,width-200,100);
  textSize(24);
  stroke(0,120,0);
  fill(20,120,0);
  
  if(flag1==2) {
    text(""+answer,150,150);
  }
  if(flag1==0) {
    text(""+num1,150,150);
  }
  if(flag1==1) {
    text(""+num1+" "+s+" "+num2,150,150);
  }
  
  fill(20,60,160);
  rect(100,300,width-200,height-400);
  
  fill(255);
  rect(120,320,40,40);
  fill(0);
  text("1",140,340);
  
  fill(255);
  rect(180,320,40,40);
  fill(0);
  text("2",200,340);
  
  
  fill(255);
  rect(240,320,40,40);
  fill(0);
  text("3",260,340);
  
  fill(255);
  rect(300,320,40,40);
  fill(0);
  text("+",320,340);
  
  fill(255);
  rect(120,380,40,40);
  fill(0);
  text("4",140,400);
  
  fill(255);
  rect(180,380,40,40);
  fill(0);
  text("5",200,400);
  
  
  fill(255);
  rect(240,380,40,40);
  fill(0);
  text("6",260,400);
  
  fill(255);
  rect(300,380,40,40);
  fill(0);
  text("-",320,400);
  
  fill(255);
  rect(120,440,40,40);
  fill(0);
  text("7",140,460);
  
  fill(255);
  rect(180,440,40,40);
  fill(0);
  text("8",200,460);
  
  
  fill(255);
  rect(240,440,40,40);
  fill(0);
  text("9",260,460);
  
  fill(255);
  rect(300,440,40,40);
  fill(0);
  text("*",320,460);
  
  fill(255);
  rect(120,500,40,40);
  fill(0);
  text("C",140,520);
  
  fill(255);
  rect(180,500,40,40);
  fill(0);
  text("0",200,520);
  
  
  fill(255);
  rect(240,500,40,40);
  fill(0);
  text("/",260,520);
  
  fill(255);
  rect(300,500,40,40);
  fill(0);
  text("=",320,520);
  
  
  
  
}

void mouseClicked() {
  x=mouseX;
  y=mouseY;
  if(flag1==0) {
    if(x>120 && x<160 && y>320 && y<360) {
      num1=num1*10 + 1;
    }
    if(x>180 && x<220 && y>320 && y<360) {
      num1=num1*10 + 2;
    }
    if(x>240 && x<280 && y>320 && y<360) {
      num1=num1*10 + 3;
    }
    if(x>300 && x<340 && y>320 && y<360) {
      s="+";
      flag1=1;
    }
    
    if(x>120 && x<160 && y>380 && y<420) {
      num1=num1*10 + 4;
    }
    if(x>180 && x<220 && y>380 && y<420) {
      num1=num1*10 + 5;
    }
    if(x>240 && x<280 && y>380 && y<420) {
      num1=num1*10 + 6;
    }
    if(x>300 && x<340 && y>380 && y<420) {
      s="-";
      flag1=1;
    }
    
    if(x>120 && x<160 && y>440 && y<480) {
      num1=num1*10 + 7;
    }
    if(x>180 && x<220 && y>440 && y<480) {
      num1=num1*10 + 8;
    }
    if(x>240 && x<280 && y>440 && y<480) {
      num1=num1*10 + 9;
    }
    if(x>300 && x<340 && y>440 && y<480) {
      s="*";
      flag1=1;
    }
    
    if(x>120 && x<160 && y>500 && y<540) {
      flag1=0;
      num1=0;
      num2=0;
      s="";
    }
    if(x>180 && x<220 && y>500 && y<540) {
      num1=num1*10 + 0;
    }
    if(x>240 && x<280 && y>500 && y<540) {
      s="/";
      flag1=1;
    }
    if(x>300 && x<340 && y>500 && y<540) {
      flag1=2;
    }
    
    
  }
  
  if(flag1==1) {
    if(x>120 && x<160 && y>320 && y<360) {
      num2=num2*10 + 1;
    }
    if(x>180 && x<220 && y>320 && y<360) {
      num2=num2*10 + 2;
    }
    if(x>240 && x<280 && y>320 && y<360) {
      num2=num2*10 + 3;
    }
    if(x>300 && x<340 && y>320 && y<360) {
      
    }
    
    if(x>120 && x<160 && y>380 && y<420) {
      num2=num2*10 + 4;
    }
    if(x>180 && x<220 && y>380 && y<420) {
      num2=num2*10 + 5;
    }
    if(x>240 && x<280 && y>380 && y<420) {
      num2=num2*10 + 6;
    }
    if(x>300 && x<340 && y>380 && y<420) {
      
    }
    
    if(x>120 && x<160 && y>440 && y<480) {
      num2=num2*10 + 7;
    }
    if(x>180 && x<220 && y>440 && y<480) {
      num2=num2*10 + 8;
    }
    if(x>240 && x<280 && y>440 && y<480) {
      num2=num2*10 + 9;
    }
    if(x>300 && x<340 && y>440 && y<480) {
       
    }
    
    if(x>120 && x<160 && y>500 && y<540) {
      flag1=0;
      num1=0;
      num2=0;
      s="";
    }
    if(x>180 && x<220 && y>500 && y<540) {
      num2=num2*10 + 0;
    }
    if(x>240 && x<280 && y>500 && y<540) {
       
    }
    if(x>300 && x<340 && y>500 && y<540) {
      flag1=2;
    }
    
  }
  
  if(flag1==2){
    if(s=="+") {
      answer=num1+num2;
    }
    if(s=="-") {
      answer=num1-num2;
    }
    if(s=="*") {
      answer=num1*num2;
    }
    if(s=="/") {
      answer=num1/num2;
    }
    
  }
  if(x>120 && x<160 && y>500 && y<540) {
      flag1=0;
      num1=0;
      num2=0;
      s="";
   }
}