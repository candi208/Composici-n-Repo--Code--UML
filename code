using System;

public class Computadora
{
    private Procesador procesador;
    
    public Computadora()
    {
        procesador = new Procesador();
        procesador.Marca="AMD";
    }

    public void Encender()
    {
        Console.WriteLine("La computadora esta encendida");
        procesador.MostrarMarca();
    }
}


 public class Procesador
   {
       public string Marca{get; set;}
       
       public void MostrarMarca()=>Console.WriteLine($"La marca del procesador es { Marca }");
   }

class Program
{
    static void Main ()
    {
        Computadora Pc= new Computadora();
        Pc.Encender();

    }
}
