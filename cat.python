size(500,500)
background(128,128,128)
scale(1)
def head():
    #Orelha esquerda
    line(140,140,160,60)
    line(240,180,160,60)
    #parte de dentro orelha esquerda
    line(150,140,162,70)
    line(230,180,162,70)
    
    #Orelha direita
    line(160,180,240,60)
    line(260,140,240,60)
    #parte de dentro orelha direita
    line(180,180,238,70)#line(x1,y1,x2,y2)
    line(250,140,238,70)#line(x1,y1,x2,y2)
    
    #cabeca
    fill(105,105,105)
    ellipse(200,140,120,120)
    
    #olho esquerdo
    fill(255,215,0)#amarelo
    ellipse(170,130,12,16)#ellipse(x,y,largura,altura)
    fill(0,0,0)#preto
    ellipse(170,130,2,15)
    
    #mancha
    fill(169,169,169)
    ellipse(230,125,50,50)
    
    #olho direito 
    fill(255,215,0)#amarelo
    ellipse(230,130,12,16)
    fill(0,0,0)#preto
    ellipse(230,130,2,15)
    
    #nariz
    line(195,160,205,160)
    line(195,160,205,170)
    line(195,170,205,160)
    
    #bigode esquerdo
    line(185,160,130,150)
    line(185,160,130,170)
    line(185,160,130,190)
    
    #bigode direito
    line(215,160,270,190)
    line(215,160,270,170)
    line(215,160,270,150)
    
    #boca
    line(195,180,205,180)

def patasTras():
    #pata traseira esquerdo
    fill(105,105,105)
    ellipse(150,300,30,100)
    
    #pata traseira direito
    ellipse(250,300,30,100)
    
    #garras pata traseira esquerda
    line(150,340,150,350) #meio
    line(145,340,145,347) #left
    line(155,340,155,347) #right
    
    #garras pata traseira direita
    line(250,340,250,350)#meio
    line(245,340,245,347)#left
    line(255,340,255,347)#right
    
def patasFrente():
    
    #pata da frente esquerda
    ellipse(180,320,30,100)
    noStroke()
    ellipse(180,300,30,100)
    
    #garras pata da frente esquerda
    stroke(0,0,0)
    line(180,370,180,355) #meio
    line(175,367,175,355)
    line(185,367,185,355)
    
    #pata da frente direita
    stroke(0,0,0)
    ellipse(220,320,30,100)
    noStroke()
    ellipse(220,300,30,100)
    
    #garras pata da frente direito
    stroke(0,0,0)
    line(220,370,220,355)#meio
    line(215,367,215,355)#esquerda
    line(225,367,225,355)#direita
    
def body():
    patasTras()
    #corpo
    fill(105,105,105)#cinza
    ellipse(200,274,140,150)
    patasFrente()   
    
    #rabo
    fill(105,105,105) 
    curve(200, 240, 270, 280, 340, 200, 290, 290)
    curve(210, 340, 270, 270, 340, 200, 290, 290)
    
    #prerabo
    stroke(105,105,105)
    rect(250,270,20,10)
    
head()
body()
