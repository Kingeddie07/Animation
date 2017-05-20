# Animation
PSeint animation trouble

Need some help here, the problem is: the animation go upside but I can't do it go downside, so please help me with it.

Starting code: 

  Definir i Como Entero; // Dim i as integer
    Definir j Como Entero; // Dim j as integer
    dimension cohete[9]; 
    cohete[1]<-"   /|\   ";
    cohete[2]<-"   |B|   ";
    cohete[3]<-"   |O|   ";
    cohete[4]<-"   |M|   ";
    cohete[5]<-"   |B|   ";
    cohete[6]<-"  //|\\  ";
    cohete[7]<-" ******* ";
    cohete[8]<-"* * * * *";
    cohete[9]<-" * * * * ";
    Para j<-15 Hasta 1 Con Paso -1 Hacer // For cicle
        Borrar Pantalla;
        Para i<-j Hasta 15 Con Paso 1 Hacer // For cicle
            Escribir "     ";
        FinPara
        Para i<-1 Hasta 9 Con Paso 1 Hacer // For cicle
            Escribir cohete[i];            // This line makes the drawing of the animation
        FinPara
        Esperar 1 Segundo;
    FinPara
FinProceso
