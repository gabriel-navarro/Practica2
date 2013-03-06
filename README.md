Tarea1
======
using System;

  class Persona{

		private string nombre;
		public void setNombre(string nombre){
			this.nombre=nombre;
		}
		public static void Main(){
			Persona persona=new Persona();
			Console.WriteLine (persona.getNombre());
			persona.setNombre("Nombre: Gabriel Navarro Muñoz");
			Console.WriteLine (persona.getNombre());
			persona.setNombre("Telefono: (044)33 37 2 51 94");
			Console.WriteLine (persona.getNombre());
			persona.setNombre("Correo: gaby_shevchenko@hotmail.com");
			Console.WriteLine (persona.getNombre());
			persona.setNombre("Domicilio: Lopez Cotilla #32");
			Console.WriteLine (persona.getNombre());
			persona.setNombre("Nacionalidad: Mexicana");
			Console.WriteLine (persona.getNombre());
			persona.setNombre("Club's Favoritos: Chelsea y Atlas ñ.ñ");
			Console.WriteLine (persona.getNombre());
		}
		public string getNombre(){
		return this.nombre;
		}
	}
	
