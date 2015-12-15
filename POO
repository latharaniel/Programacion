package poo;

// autor claudia lopez pinteño
public class Alumno {

    public String nombre;
    public String curso_matriculado;
    public String asignatura;
    public double calificacion;
 
 public Alumno(String nom, String cur_ma, String asig, double calif){
   
     this.nombre=nom;
     this.curso_matriculado=cur_ma;
     this.asignatura=asig;
     this.calificacion=calif;
          
System.out.println("El alumno "+nombre+" matriculado en "+curso_matriculado+" tiene la calificación de "+calificacion+" en la asignatura de "+asignatura);
         
 }
 void setNombre (String nom){
     this.nombre=nom;
 }
 String getNombre(){
     return this.nombre;
 }
  void setCurso_matriculado (String cur_ma){
     this.curso_matriculado=cur_ma;
 }
 String getCurso_Matriculado(){
     return this.curso_matriculado;
 }
 void setAsignatura (String asig){
     this.asignatura=asig;
 }
 String getAsignatura(){
     return this.asignatura;
 }
 
 void setcalificacion(double calif){
     this.calificacion=calif;
 }
 double getCalificacion(){
     return this.calificacion;
     
 }
}



class Main {
public static void main(String[] args){
        
        Alumno datos = new Alumno("Claudia", "DAM","Programación", 8.5);
    
      
        datos.setNombre("Claudia");
        String nombre = datos.getNombre();
        System.out.println(nombre);
        
        
        datos.setCurso_matriculado("DAM");
        String curso_matriculado=datos.getCurso_Matriculado();
        System.out.println(curso_matriculado);
        
      
        datos.setAsignatura("Programación");
        String asignatura = datos.getAsignatura();
        System.out.println(asignatura);
        
       
        datos.setcalificacion(8.5);
        double calificacion = datos.getCalificacion();
        System.out.println(calificacion);
        
    }
}
